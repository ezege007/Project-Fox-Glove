# Day 4 Team Mission — Event Budget Helper, Part 2

> **Team Mission Completion · Integration, Cross-Testing, Improvement and Inspection**

Day 3 was about building components and producing a first integrated version.

Day 4 is about proving that the program works, finding weak points, improving the program without breaking earlier behaviour, and showing clear evidence of each learner's contribution.

---

## Mission Goal

Finish and verify the shared **Event Budget Helper**.

The four required components remain:

```python
participant_cost(attendees, food_per_person, transport_per_person)
event_total(attendees, food_per_person, transport_per_person, venue_cost)
budget_status(budget, total)
event_summary(event_name, total, status)
```

Do not redesign the project simply because it is Day 4. Improve the existing work using evidence.

---

## Part 1 — Finish the Four Components

Confirm that all four functions are complete and callable.

Before moving on, each component owner should rerun the tests they used on Day 3.

If a component still fails, record:

- failing input;
- expected result;
- actual result.

Then repair one cause at a time.

---

## Part 2 — Run Shared Acceptance Tests

Your integrated program should cover at least these categories:

### Normal event

A standard event with attendees, participant expenses and venue cost.

### Zero attendees

The venue cost should still be included even if no attendees are present.

### Exact budget

When:

```text
total == budget
```

the result must be:

```text
"Within budget"
```

### Over budget

When:

```text
total > budget
```

the result must be:

```text
"Over budget"
```

### Summary output

The event summary must use the supplied event name, total and status.

Do not change expected results to match incorrect code.

---

## Part 3 — Record Test Evidence

For important cases, record:

| Input / case | Expected result | Actual result | Pass / Fail |
| --- | --- | --- | --- |
| Normal event | ... | ... | ... |
| Zero attendees | ... | ... | ... |
| Exact budget | ... | ... | ... |
| Over budget | ... | ... | ... |

Evidence is stronger than writing “all tests passed.”

---

## Part 4 — Cross-Test with Another Team

Exchange the integrated program with another team.

The reviewing team should not rewrite your project.

They should provide defects in this format:

```text
Input:
Expected:
Actual:
Location or component suspected:
```

Avoid comments such as:

```text
This does not work.
```

A useful defect report should make the failure reproducible.

---

## Part 5 — Implement or Verify an Improvement

Each learner must implement or verify at least one documented improvement.

Examples include:

- correcting a wrong arithmetic operation;
- correcting an exact-boundary condition;
- fixing a summary format;
- repairing integration between two components;
- adding a missing test;
- confirming that a peer fix solved the reported failure.

The change must be attributable to the learner.

---

## Part 6 — Retest After Every Fix

After a change:

1. rerun the previously failing case;
2. rerun at least one related case that passed before;
3. confirm that the fix did not create a regression.

A regression is when behaviour that previously worked becomes broken after a change.

---

## Part 7 — Prepare for Coding Mentor Inspection

Each learner should be ready to explain:

1. what component or change they owned;
2. what requirement applied;
3. what problem or test they worked on;
4. what they changed or verified;
5. what evidence shows that the change works;
6. one area of teammate code they reviewed.

A useful explanation pattern is:

```text
Requirement → observed problem → change → evidence
```

Example:

```text
The requirement says an exact budget match is Within budget.
The function used <, so equality returned Over budget.
I changed the comparison to <=.
The equality case now passes, and the over-budget case still passes.
```

Do not memorise a speech. Use your actual code and test evidence.

---

## Final Team Submission

Submit:

### Shared team evidence

- final integrated program;
- final acceptance-test evidence;
- cross-team defect reports;
- corrected/retested version;
- shared final result.

### Individual evidence

Each learner must submit or be able to show:

- attributable code contribution;
- test evidence;
- one review or cross-test action;
- one documented improvement or verification;
- handover/contribution record;
- explanation during mentor inspection.

---

## Final Mission Checklist

- [ ] All four required components are present.
- [ ] The integrated program runs.
- [ ] Normal-event behaviour was tested.
- [ ] Zero-attendee behaviour was tested.
- [ ] Exact-budget behaviour was tested.
- [ ] Over-budget behaviour was tested.
- [ ] Summary formatting was tested.
- [ ] Cross-team testing was completed.
- [ ] Defects were recorded with input, expected and actual results.
- [ ] Fixes were retested.
- [ ] Earlier passing behaviour was retested after changes.
- [ ] Every learner has visible technical evidence.
- [ ] Every learner can explain their own work.
- [ ] The team is ready for coding mentor inspection.

---

## Mission Finish Line

The goal is not only to have code that works.

A strong Day 4 result shows that the team can:

**integrate → test → find evidence → repair carefully → retest → explain ownership**
