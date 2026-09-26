## Lesson 3.2 — Integrate Components and Reuse Returned Values

| **Estimated time**   | 35–40 minutes                                              |
|----------------------|------------------------------------------------------------|
| **Learning purpose** | Connect separately tested functions into one working flow. |

### What you should be able to do

- Call one component from another where the design requires it.

- Trace a value from one function to the next.

- Recognise interface mismatches during integration.

- Keep integration code simple and inspectable.

### Integration is where contracts meet

A component can pass its own tests and still fail when connected to the rest of the program if the team disagreed about names, types or meanings. Integration means connecting the pieces and checking that the output of one component is suitable as the input to the next.

The Event Budget Helper flow is: calculate participant cost → calculate event total → determine budget status → build the summary. Each step produces a value that the next step can use.

people = participant_cost(10, 800, 200)  
total = event_total(10, 800, 200, 5000)  
status = budget_status(16000, total)  
summary = event_summary("Study Day", total, status)

### Integrate in small steps

Do not wait until every component is “finished” and then combine everything at once. First confirm one helper works. Connect the next function and rerun. Then connect the decision. Finally connect the summary. When a failure appears, the smaller integration step makes it easier to locate the mismatch.

### Common mistakes to watch for

- Copying calculations instead of using the agreed helper.

- Integrating all components at once and not knowing where a wrong value appeared.

- Changing a function signature during integration without coordinating with the owner.

### Peer learning checkpoint

Trace one sample through the entire program as a team. Each owner should say what value their function receives and returns.

### Linked drill(s) — use these to test what you just learned

**D3.2A — Integrate Participant and Venue Costs**

participant_cost is supplied. Complete event_total by calling participant_cost and adding venue_cost.

**Type:** Core

**D3.2B — Build the Final Event Summary**

Complete event_summary(event_name, total, status). Return exactly "Study Day: total 15000 naira. Within budget." with supplied values substituted.

**Type:** Reinforcement
