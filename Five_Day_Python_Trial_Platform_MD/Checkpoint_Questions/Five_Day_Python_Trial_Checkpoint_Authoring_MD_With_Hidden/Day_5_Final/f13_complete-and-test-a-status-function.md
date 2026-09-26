# F13 — Complete and Test a Status Function

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

Complete `booking_status` and write one extra boundary test of your own. Return `"Fits"` when booked is at most capacity, otherwise `"Too many"`.

## Starter Code

```python
def booking_status(capacity, booked):
    pass
```

## Allowed Keywords / Constructs

- `if` / `else`
- `<=`
- `return`
- an additional learner-written test

## Restrictions / Forbidden Constructs

- `input()`
- `import` statements
- `eval()` or `exec()`
- hard-coded sample answers
- renaming the supplied function or parameters
- `print()`
- changing required return strings

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `booking_status(10, 7)` | `"Fits"` |
| `booking_status(10, 10)` | `"Fits"` |
| `booking_status(10, 11)` | `"Too many"` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `booking_status(0, 0)` | `"Fits"` |
| `booking_status(5, 4)` | `"Fits"` |
| `booking_status(5, 6)` | `"Too many"` |

> **Important:** Hidden samples must be configured as private tests and must not be shown to candidates.
