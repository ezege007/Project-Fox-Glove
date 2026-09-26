# F10 — Reuse a Returned Value

**Checkpoint:** Day 5 Final Coding Checkpoint

## Task

Complete `event_total` by calling `participant_cost` and adding `venue_cost`.

## Starter Code

```python
def participant_cost(attendees, food_per_person, transport_per_person):
    return attendees * (food_per_person + transport_per_person)

def event_total(attendees, food_per_person, transport_per_person, venue_cost):
    pass
```

## Published Sample Checks

| Call | Expected result |
| --- | --- |
| `event_total(10, 800, 200, 5000)` | `15000` |

## Before You Move On

- Keep the supplied function name and parameters unchanged unless the question says otherwise.
- Use the supplied inputs instead of hard-coding the sample answers.
- Run the published sample checks where time allows.
- Save your latest attempt before moving to the next question.
