## Lesson 3.1 — Break a Team Problem into Components and Contracts

| **Estimated time**   | 35–40 minutes                                                           |
|----------------------|-------------------------------------------------------------------------|
| **Learning purpose** | Learn how a team can divide one program without dividing understanding. |

### What you should be able to do

- Identify separate responsibilities in a larger brief.

- Write a simple contract for each component.

- Understand ownership without creating isolated silos.

- Explain what another component expects from your component.

### A team project is one system

The Event Budget Helper is larger than the Day 2 mission, but it is built from the same kinds of small functions. The safest way to collaborate is to agree on the component contracts before everyone starts coding. A contract should name the function, list its inputs, state its returned value and describe the rule it owns.

For example, participant_cost owns attendee-based food and transport cost. event_total owns the addition of venue cost to that participant cost. budget_status owns the comparison between total and budget. event_summary owns the final readable message. If these contracts are clear, team members can work separately and still create compatible pieces.

### Ownership does not mean ignorance

Every learner should own code, but every learner should also understand how their component connects to at least one other component. A team member assigned only to presentation or administration has not produced enough technical evidence. Likewise, the strongest learner should not silently rewrite everyone else’s work.

### Define before you build

Write the four contracts on paper or in your team notes. Agree on exact function names and return types. Then allocate owners and reviewers. This prevents integration failures caused by one person returning text where another component expects a number, or by inconsistent names.

### Common mistakes to watch for

- Starting to code before agreeing on function names and outputs.

- Giving one learner all difficult technical work.

- Changing another person’s contract without telling the team.

### Peer learning checkpoint

As a team, each learner should explain one component they do not own and describe what value enters it and what value should leave it.

### Linked drill(s) — use these to test what you just learned

**D3.1A — Implement a Component Contract**

Implement participant_cost exactly as specified: attendees \* (food_per_person + transport_per_person). Return an integer.

**Type:** Core

**D3.1B — Implement the Status Contract**

Complete budget_status(budget, total). Return "Within budget" when total \<= budget; otherwise return "Over budget".

**Type:** Reinforcement
