# F15 — Mini Integrated Summary

**Checkpoint:** Day 5 Final Coding Checkpoint

## Task

Complete `plan_summary`. Call `event_total`, determine status with an `if/else`, then return an exact sentence: `Study Day: total 15000 naira. Within budget.`

## Starter Code

```python
def event_total(attendees, per_person, venue):
    return attendees * per_person + venue

def plan_summary(event_name, attendees, per_person, venue, budget):
    pass
```

## Published Sample Checks

| Call | Expected result |
| --- | --- |
| `plan_summary("Study Day", 10, 1000, 5000, 16000)` | `"Study Day: total 15000 naira. Within budget."` |

## Before You Move On

- Keep the supplied function name and parameters unchanged unless the question says otherwise.
- Use the supplied inputs instead of hard-coding the sample answers.
- Run the published sample checks where time allows.
- Save your latest attempt before moving to the next question.
