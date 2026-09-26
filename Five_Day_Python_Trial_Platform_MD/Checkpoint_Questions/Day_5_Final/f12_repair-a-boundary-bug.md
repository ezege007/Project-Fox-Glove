# F12 — Repair a Boundary Bug

**Checkpoint:** Day 5 Final Coding Checkpoint

## Task

The exact-fit case should return `"Within budget"`. Repair the condition.

## Starter Code

```python
def budget_status(budget, total):
    if total < budget:
        return "Within budget"
    else:
        return "Over budget" 
```

## Published Sample Checks

| Call | Expected result |
| --- | --- |
| `budget_status(15000, 15000)` | `"Within budget"` |
| `budget_status(14000, 15000)` | `"Over budget"` |

## Before You Move On

- Keep the supplied function name and parameters unchanged unless the question says otherwise.
- Use the supplied inputs instead of hard-coding the sample answers.
- Run the published sample checks where time allows.
- Save your latest attempt before moving to the next question.
