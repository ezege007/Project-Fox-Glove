# D2.4C — Retest After a Fix

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 2.4 |
| Type | Reinforcement |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d2-4c/solution.py` |

## Instructions

Repair seats_left so it subtracts booked from capacity. The platform will test normal, zero and exact-fit cases.

## Default Code Template

```python
def seats_left(capacity, booked):
return capacity + booked
```

## Allowed Keywords / Constructs

def, return, -

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(10, 3)` | `7` |
| `(10, 10)` | `0` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(0, 0)` | `0` |
| `(7, 0)` | `7` |
| `(20, 8)` | `12` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
