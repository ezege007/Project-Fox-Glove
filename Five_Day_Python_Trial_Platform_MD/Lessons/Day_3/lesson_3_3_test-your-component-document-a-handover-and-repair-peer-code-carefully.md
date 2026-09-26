## Lesson 3.3 — Test Your Component, Document a Handover and Repair Peer Code Carefully

| **Estimated time**   | 35–40 minutes                                                             |
|----------------------|---------------------------------------------------------------------------|
| **Learning purpose** | Make individual work safe to integrate and easy for a teammate to review. |

### What you should be able to do

- Test a component independently before handing it over.

- Include normal, zero and boundary cases when relevant.

- Write a short handover note that another learner can use.

- Review peer code by identifying the smallest necessary change rather than taking over.

### A component is not ready because it ran once

Before handing your function to the team, run the published sample and at least one additional case. If zero is allowed, include it. If a boundary exists, include equality. Record the expected and actual result. This gives the integrator evidence that the component behaved correctly on its own.

### A useful handover is short and concrete

A handover note can contain four lines: component owned; what it returns; tests run; any assumption or unresolved issue. This is enough for another learner to integrate your work without guessing what you intended.

### Review without taking over

When reviewing peer code, first explain the observed problem and the evidence for it. Ask the owner what they think is happening. Point to the relevant rule or test. Only after the owner has had a chance to reason should you suggest a specific change. A reviewer who replaces the whole solution removes learning evidence from the owner.

### Common mistakes to watch for

- Handing over untested code.

- Saying “it works” without listing a test result.

- Rewriting a teammate’s entire function when one operator is wrong.

### Peer learning checkpoint

Exchange one component with another learner. The reviewer must first state one passing test and one question before suggesting any code change.

### Linked drill(s) — use these to test what you just learned

**D3.3A — Test a Component with Zero**

Complete venue_only_total so it returns venue_cost when attendees is zero and otherwise returns attendee costs plus venue. Use the supplied participant_cost helper.

**Type:** Core

**D3.3B — Repair a Teammate Component**

A teammate wrote the wrong operation. Repair event_total so it adds venue_cost after calling participant_cost.

**Type:** Reinforcement
