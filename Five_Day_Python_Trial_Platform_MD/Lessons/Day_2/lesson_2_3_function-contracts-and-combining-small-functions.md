## Lesson 2.3 — Function Contracts and Combining Small Functions

| **Estimated time**   | 40–45 minutes                                                                     |
|----------------------|-----------------------------------------------------------------------------------|
| **Learning purpose** | Build larger behaviour by connecting small functions with clear responsibilities. |

### What you should be able to do

- Describe a function contract using inputs, output and responsibility.

- Call a helper rather than duplicating its calculation.

- Pass a returned value into another calculation or decision.

- Explain why small functions are easier to test and combine.

### A function should have a clear job

A function contract tells you what values the function receives, what it promises to return and what responsibility belongs inside it. For example, \`participant_cost(attendees, food_per_person, transport_per_person)\` owns the attendance-based cost calculation. \`event_total(...)\` can then call that helper and add a venue cost. Separating responsibilities makes both pieces easier to test.

### Build from small pieces

When one function already solves part of the problem, reuse it. The goal is not merely shorter code. Reuse creates a single place responsible for a rule. If the participant-cost formula changes later, a program that consistently calls the helper is easier to update than a program that copied the formula into several places.

def participant_cost(attendees, food_per_person, transport_per_person):  
return attendees \* (food_per_person + transport_per_person)  
  
def event_total(attendees, food_per_person, transport_per_person, venue_cost):  
people = participant_cost(attendees, food_per_person, transport_per_person)  
return people + venue_cost

### Trace the contract chain

For \`event_total(10, 800, 200, 5000)\`, the helper receives 10, 800 and 200 and returns 10,000. The caller stores that returned value in \`people\`, adds 5,000 and returns 15,000. A later status function can receive that 15,000 and compare it with a budget. This chain of small contracts is the foundation of the Day 3 team mission.

### Common mistakes to watch for

- Repeating helper logic when the task requires the helper to be called.

- Changing the supplied helper instead of completing the missing function.

- Calling a function but ignoring its returned value.

### Peer learning checkpoint

Draw boxes for two functions. Label the inputs and returned output of each, then draw an arrow showing how the first function’s answer becomes data for the second.

### Optional resources if you want another explanation

**Watch:** [<u>Python Functions for Beginners (Corey Schafer)</u>](https://www.youtube.com/watch?v=9Os0o3wzS_I)

**Visualise:** [<u>Python Tutor</u>](https://pythontutor.com/)

### Linked drill(s) — use these to test what you just learned

**D2.3A — Event Total with a Helper**

participant_cost is supplied. Complete event_total by calling participant_cost and adding venue_cost.

**Type:** Core

**D2.3B — Calculate Then Format**

Complete budget_report so it calls budget_left and uses the returned value in the exact message "500 naira remaining."

**Type:** Reinforcement

**D2.3C — Calculate Then Decide**

Complete trip_status so it calls trip_cost and returns "Within budget" when the returned total is at most budget; otherwise return "Over budget".

**Type:** Reinforcement
