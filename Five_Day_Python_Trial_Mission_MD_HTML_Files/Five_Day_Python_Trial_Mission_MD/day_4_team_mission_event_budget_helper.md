# Day 4 Team Mission — Event Budget Helper

> **Full-Day Team Mission · Teams of 2–4**

Day 3 is now a **lessons-and-drills day only**. Those lessons and drills prepare candidates for this mission.

Day 4 is the complete team mission. The activities that were previously split across Day 3 and Day 4 are now combined into one professional build cycle:

> **plan → build → test → hand over → review → integrate → cross-test → improve → retest → explain**

---

## Mission Goal

Build a working **Event Budget Helper** that can:

1. calculate participant-related costs;
2. add the venue cost to get the total event cost;
3. decide whether the event is within budget;
4. return a clear event summary.

Use these four functions:

```python
def participant_cost(attendees, food_per_person, transport_per_person):
    pass

def event_total(attendees, food_per_person, transport_per_person, venue_cost):
    pass

def budget_status(budget, total):
    pass

def event_summary(event_name, total, status):
    pass
```

---

## Component Contracts

### A. `participant_cost`

Return:

```text
attendees * (food_per_person + transport_per_person)
```

Example:

```text
participant_cost(10, 800, 200) => 10000
```

### B. `event_total`

It must:

1. call `participant_cost`;
2. add `venue_cost`;
3. return the combined total.

Example:

```text
event_total(10, 800, 200, 5000) => 15000
```

### C. `budget_status`

Return `"Within budget"` when:

```text
total <= budget
```

Otherwise return `"Over budget"`.

The exact-budget boundary matters.

```text
budget_status(15000, 15000) => "Within budget"
```

### D. `event_summary`

Return a readable message using the supplied values.

Required pattern:

```text
Study Day: total 15000 naira. Within budget.
```

Do not hard-code the event name, total, or status.

---

## Team Rule — Divide the Work, Not the Understanding

Every learner must have:

- an attributable code contribution;
- at least one test they personally ran or verified;
- at least one peer-review or cross-testing action;
- at least one documented improvement, fix, or verification;
- enough understanding to explain how their work connects to the full program.

A learner may own one component, but every learner should understand the complete flow.

---

## Phase 1 — Plan and Assign Ownership

Agree on:

- exact function names;
- exact parameters;
- exact return values;
- dependencies between functions;
- who owns each component.

Example:

| Learner | Primary responsibility |
| --- | --- |
| Learner A | `participant_cost` |
| Learner B | `event_total` |
| Learner C | `budget_status` |
| Learner D | `event_summary` |

Teams with fewer than four learners may assign more than one component to a learner.

---

## Phase 2 — Predict Before Coding

Use:

```text
event_name = "Study Day"
attendees = 10
food_per_person = 800
transport_per_person = 200
venue_cost = 5000
budget = 16000
```

Predict:

| Stage | Expected result |
| --- | --- |
| `participant_cost` | `10000` |
| `event_total` | `15000` |
| `budget_status` | `"Within budget"` |
| `event_summary` | `"Study Day: total 15000 naira. Within budget."` |

---

## Phase 3 — Build and Test Components

Each component owner should:

1. implement the assigned function;
2. run the required example;
3. run at least one additional test;
4. record expected and actual results;
5. save the work;
6. commit the contribution through the assigned Gitea workflow.

Do not wait until the whole program is assembled before testing.

### Minimum component tests

**`participant_cost`**
- normal attendee count;
- zero attendees.

**`event_total`**
- normal participant cost plus venue;
- zero attendees with a non-zero venue.

**`budget_status`**
- below budget;
- exactly equal to budget;
- over budget.

**`event_summary`**
- required Study Day example;
- one different event name and total.

---

## Phase 4 — Handover

Each owner should provide:

```text
Component:
What it receives:
What it returns:
Tests run:
Known issue, if any:
```

Keep the handover short and technical.

---

## Phase 5 — Peer Review

Every learner should review at least one teammate contribution.

A useful review should:

- identify the requirement being checked;
- inspect the relevant code;
- run or inspect a test;
- ask the owner a specific question;
- report a concrete issue if one exists.

Do not take over a teammate's work.

---

## Phase 6 — Integrate One Step at a Time

Integrate in this order:

```text
participant_cost
      ↓
event_total
      ↓
budget_status
      ↓
event_summary
```

After every connection:

1. run a test;
2. compare expected and actual results;
3. resolve failures before adding the next step.

---

## Full Acceptance Case

```python
people = participant_cost(10, 800, 200)
total = event_total(10, 800, 200, 5000)
status = budget_status(16000, total)
summary = event_summary("Study Day", total, status)
```

Expected:

```text
people  => 10000
total   => 15000
status  => "Within budget"
summary => "Study Day: total 15000 naira. Within budget."
```

---

## Phase 7 — Acceptance Testing

The team must test:

1. **Normal event**
2. **Zero attendees**
3. **Exact budget** — equality must return `"Within budget"`
4. **Over budget**
5. **Summary formatting**

Record evidence:

| Test / Input | Expected | Actual | Pass / Fail |
| --- | --- | --- | --- |
| Normal event | ... | ... | ... |
| Zero attendees | ... | ... | ... |
| Exact budget | ... | ... | ... |
| Over budget | ... | ... | ... |
| Summary format | ... | ... | ... |

“Everything passed” is not enough evidence.

---

## Phase 8 — Cross-Test with Another Team

Exchange the integrated program with another team.

Use this defect format:

```text
Input:
Expected:
Actual:
Component suspected:
```

The reviewing team should test the program, not rewrite it.

---

## Phase 9 — Improve and Retest

If a defect is found:

1. identify the failing behaviour;
2. identify the likely component;
3. change only what is necessary;
4. rerun the failing case;
5. rerun at least one earlier passing case.

This final step checks for **regression** — something that worked before becoming broken after a change.

Every learner should be able to identify at least one improvement, fix, or verification they personally contributed to.

---

## Phase 10 — Prepare for Coding Mentor Inspection

Each learner should be ready to show and explain:

1. the component or change they personally owned;
2. their own code contribution;
3. one test they ran and its expected/actual result;
4. how data moves through the four functions;
5. one teammate contribution they reviewed;
6. one defect, fix, improvement, or verification they worked on;
7. what they retested after a change;
8. Gitea evidence of their contribution;
9. what cross-testing revealed.

A strong explanation follows:

```text
requirement → observed problem → change → evidence
```

---

## Final Submission

### Shared team evidence

- final integrated program;
- component-test evidence;
- acceptance-test evidence;
- cross-team defect report(s);
- corrected and retested version;
- shared final result.

### Individual evidence

Every learner must show:

- attributable code contribution;
- at least one personal test or verification;
- at least one review or cross-test action;
- at least one documented improvement, fix, or verification;
- Gitea evidence where applicable;
- clear explanation during mentor inspection.

---

## Final Checklist

- [ ] All four required functions are present.
- [ ] Every function follows its contract.
- [ ] `event_total` reuses `participant_cost`.
- [ ] The integrated program runs.
- [ ] Normal-event behaviour was tested.
- [ ] Zero-attendee behaviour was tested.
- [ ] Exact-budget behaviour was tested.
- [ ] Over-budget behaviour was tested.
- [ ] Summary formatting was tested.
- [ ] Every learner has an attributable contribution.
- [ ] Every learner reviewed or cross-tested something.
- [ ] Cross-team testing was completed.
- [ ] Defects include input, expected, and actual results.
- [ ] Fixes were retested.
- [ ] Earlier passing behaviour was checked after changes.
- [ ] Gitea evidence is available where required.
- [ ] Every learner can explain their own work.
- [ ] The team is ready for coding mentor inspection.

---

## What a Strong Submission Looks Like

A strong team does more than produce the correct final sentence.

It shows:

- clear ownership;
- correct function contracts;
- deliberate tests;
- meaningful review;
- careful integration;
- evidence-based debugging;
- regression checks;
- visible individual contribution;
- a working final program;
- learners who can explain what they did and why.
