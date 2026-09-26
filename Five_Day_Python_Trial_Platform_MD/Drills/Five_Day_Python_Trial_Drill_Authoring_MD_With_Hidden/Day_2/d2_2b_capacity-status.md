# D2.2B — Capacity Status

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 2.2 |
| Type | Reinforcement |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d2-2b/solution.py` |

## Instructions

Return "Fits" when booked is at most capacity; otherwise return "Too many".

## Default Code Template

```python
def booking_status(capacity, booked):
pass
```

## Allowed Keywords / Constructs

def, return, if, else, <=, string

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(10, 7)` | `'Fits'` |
| `(10, 10)` | `'Fits'` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(10, 11)` | `'Too many'` |
| `(0, 0)` | `'Fits'` |
| `(0, 1)` | `'Too many'` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
