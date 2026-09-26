# F14 — Calculate Then Decide

**Checkpoint:** Day 5 Final Coding Checkpoint

## Task

Use `event_total` to calculate `total`, then return `budget_status(budget, total)`. Keep both supplied helpers unchanged.

## Starter Code

```python
def event_total(attendees, per_person, venue):
    return attendees * per_person + venue

def budget_status(budget, total):
    if total <= budget:
        return "Within budget"
    return "Over budget"

def event_result(attendees, per_person, venue, budget):
    pass
```

## Published Sample Checks

| Call | Expected result |
| --- | --- |
| `event_result(10, 1000, 5000, 16000)` | `"Within budget"` |

## Before You Move On

- Keep the supplied function name and parameters unchanged unless the question says otherwise.
- Use the supplied inputs instead of hard-coding the sample answers.
- Run the published sample checks where time allows.
- Save your latest attempt before moving to the next question.
