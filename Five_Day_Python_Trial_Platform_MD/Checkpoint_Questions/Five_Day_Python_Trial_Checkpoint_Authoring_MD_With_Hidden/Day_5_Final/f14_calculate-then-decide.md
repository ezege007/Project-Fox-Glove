# F14 — Calculate Then Decide

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

## Allowed Keywords / Constructs

- calls to `event_total` and `budget_status`
- assignment
- `return`

## Restrictions / Forbidden Constructs

- `input()`
- `import` statements
- `eval()` or `exec()`
- hard-coded sample answers
- renaming the supplied function or parameters
- changing either supplied helper
- duplicating helper logic instead of calling the helpers

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `event_result(10, 1000, 5000, 16000)` | `"Within budget"` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `event_result(10, 1000, 5000, 15000)` | `"Within budget"` |
| `event_result(10, 1000, 5000, 14999)` | `"Over budget"` |
| `event_result(0, 1000, 5000, 5000)` | `"Within budget"` |

> **Important:** Hidden samples must be configured as private tests and must not be shown to candidates.
