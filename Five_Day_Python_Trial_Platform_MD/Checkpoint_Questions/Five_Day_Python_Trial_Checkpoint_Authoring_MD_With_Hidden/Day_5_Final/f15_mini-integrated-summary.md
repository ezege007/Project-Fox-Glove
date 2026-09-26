# F15 — Mini Integrated Summary

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Checkpoint | Day 5 Final Coding Checkpoint |
| Day | 5 |
| Classification | Core |
| Raw marks | 10 |
| Language | Python |

## Task

Complete `plan_summary`. Call `event_total`, determine status with an `if/else`, then return an exact sentence such as `Study Day: total 15000 naira. Within budget.`

## Starter Code

```python
def event_total(attendees, per_person, venue):
    return attendees * per_person + venue

def plan_summary(event_name, attendees, per_person, venue, budget):
    pass
```

## Allowed Keywords / Constructs

- call to `event_total`
- assignment
- `if` / `else`
- comparison
- f-string or string formatting
- `return`

## Restrictions / Forbidden Constructs

- `input()`
- `import` statements
- `eval()` or `exec()`
- hard-coded sample answers
- renaming the supplied function or parameters
- changing `event_total`
- hard-coding the sample event name/total/status
- `print()`

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `plan_summary("Study Day", 10, 1000, 5000, 16000)` | `"Study Day: total 15000 naira. Within budget."` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `plan_summary("Workshop", 5, 1000, 2000, 7000)` | `"Workshop: total 7000 naira. Within budget."` |
| `plan_summary("Meetup", 5, 1000, 2000, 6999)` | `"Meetup: total 7000 naira. Over budget."` |
| `plan_summary("Zero Day", 0, 1000, 0, 0)` | `"Zero Day: total 0 naira. Within budget."` |

> **Important:** Hidden samples must be configured as private tests and must not be shown to candidates.
