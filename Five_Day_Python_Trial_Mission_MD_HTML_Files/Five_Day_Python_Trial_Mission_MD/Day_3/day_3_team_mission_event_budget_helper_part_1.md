# Day 3 Team Mission — Event Budget Helper, Part 1

> **Team Mission · Teams of 2–4 · Day 3 Build and Integration**

Your team will build a small **Event Budget Helper**.

This mission expands the ideas from the Day 2 Personal Budget Helper. The new challenge is not a completely new Python topic. The challenge is learning how to divide one program into clear components, own a piece of work, test it, hand it over, review another learner's work, and integrate the pieces without losing understanding.

---

## Mission Goal

Build these four components:

### A — `participant_cost`

```python
def participant_cost(attendees, food_per_person, transport_per_person):
    pass
```

Required behaviour:

```text
attendees * (food_per_person + transport_per_person)
```

### B — `event_total`

```python
def event_total(attendees, food_per_person, transport_per_person, venue_cost):
    pass
```

Required behaviour:

- call `participant_cost`;
- add `venue_cost`;
- return the combined total.

### C — `budget_status`

```python
def budget_status(budget, total):
    pass
```

Required behaviour:

```text
"Within budget" when total <= budget
"Over budget" otherwise
```

### D — `event_summary`

```python
def event_summary(event_name, total, status):
    pass
```

Required behaviour:

Return an exact readable summary using the supplied values.

Example:

```text
Study Day: total 15000 naira. Within budget.
```

---

## Team Rule: Divide the Work, Not the Understanding

Each learner should have a visible technical contribution.

By the end of Day 3, every learner must have:

- one attributable code contribution;
- at least one test result;
- at least one review action;
- enough understanding to explain what their component receives and returns.

A team member may own one component, but every learner should understand how the full flow works.

---

## Recommended Team Workflow

### Step 1 — Read the Four Contracts Together

Before coding, agree on:

- the exact function names;
- the exact parameters;
- the exact return values;
- which component depends on another component.

Do not change a function signature without team agreement.

---

### Step 2 — Assign Component Ownership

Assign each learner a primary component or clear technical responsibility.

Example:

| Learner | Primary responsibility |
| --- | --- |
| Learner A | `participant_cost` |
| Learner B | `event_total` |
| Learner C | `budget_status` |
| Learner D | `event_summary` |

If your team has fewer than four learners, one learner may own more than one component.

Ownership does not mean working in isolation. It means there is one clear person responsible for understanding, testing, and handing over that component.

---

### Step 3 — Predict Before Coding

As a team, predict the full flow for:

```text
attendees = 10
food_per_person = 800
transport_per_person = 200
venue_cost = 5000
budget = 16000
event_name = "Study Day"
```

Expected flow:

```text
participant_cost => 10000
event_total      => 15000
budget_status    => "Within budget"
event_summary    => "Study Day: total 15000 naira. Within budget."
```

---

### Step 4 — Build Components Separately

Each owner should:

1. implement the assigned component;
2. run the published sample;
3. run at least one additional case;
4. record expected and actual results;
5. commit the component to the assigned Gitea workflow.

Do not wait until every component is “finished” before testing.

---

## Minimum Component Tests

### `participant_cost`

Test at least:

- a normal attendee count;
- zero attendees.

### `event_total`

Test at least:

- normal attendee cost plus venue;
- zero attendees with a non-zero venue.

### `budget_status`

Test:

- below budget;
- exactly equal to budget;
- over budget.

### `event_summary`

Test:

- the required example;
- one different event name and total.

---

## Step 5 — Write a Short Handover Note

Each owner should give the team a short handover containing:

1. component owned;
2. what it returns;
3. tests run;
4. any assumption or unresolved issue.

Example:

```text
Component: budget_status
Returns: "Within budget" when total <= budget, otherwise "Over budget"
Tests: below budget, exact budget, over budget
Issue: none
```

Keep the handover short and technical.

---

## Step 6 — Review Without Taking Over

Before integration, each learner should review at least one teammate component.

A useful review should:

- identify one requirement or test;
- check the code against it;
- ask the owner a question;
- point out a specific issue if one exists;
- allow the owner to make the correction.

Do not replace a teammate's work with your own solution.

---

## Step 7 — Integrate in Small Steps

Connect the program in this order:

```text
participant_cost
      ↓
event_total
      ↓
budget_status
      ↓
event_summary
```

After connecting each new component, run a test.

Do not integrate all four components at once and hope the final output is correct.

---

## Day 3 Acceptance Case

Your team should be able to run a complete example equivalent to:

```python
people = participant_cost(10, 800, 200)
total = event_total(10, 800, 200, 5000)
status = budget_status(16000, total)
summary = event_summary("Study Day", total, status)
```

Expected result:

```text
people  => 10000
total   => 15000
status  => "Within budget"
summary => "Study Day: total 15000 naira. Within budget."
```

---

## Day 3 Evidence Required

Each learner must leave evidence of:

- their code contribution;
- at least one test result;
- one review action;
- one short handover note.

The team should also preserve:

- the integrated Day 3 program;
- the current test results;
- any unresolved issue to continue on Day 4.

---

## Day 3 Finish Line

You do **not** need a polished final product by the end of Day 3.

You need:

- clear component ownership;
- working or testable components;
- visible individual contributions;
- evidence of review;
- a first integrated version that the team can improve on Day 4.
