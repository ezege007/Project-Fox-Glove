# F10 — Reuse a Returned Value

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

Complete `event_total` by calling `participant_cost` and adding `venue_cost`.

## Starter Code

```python
def participant_cost(attendees, food_per_person, transport_per_person):
    return attendees * (food_per_person + transport_per_person)

def event_total(attendees, food_per_person, transport_per_person, venue_cost):
    pass
```

## Allowed Keywords / Constructs

- function call to `participant_cost`
- `+`
- `return`

## Restrictions / Forbidden Constructs

- `input()`
- `import` statements
- `eval()` or `exec()`
- hard-coded sample answers
- renaming the supplied function or parameters
- changing `participant_cost`
- duplicating the helper's calculation instead of calling it

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `event_total(10, 800, 200, 5000)` | `15000` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `event_total(0, 800, 200, 5000)` | `5000` |
| `event_total(5, 1000, 0, 2500)` | `7500` |
| `event_total(2, 500, 500, 0)` | `2000` |

> **Important:** Hidden samples must be configured as private tests and must not be shown to candidates.
