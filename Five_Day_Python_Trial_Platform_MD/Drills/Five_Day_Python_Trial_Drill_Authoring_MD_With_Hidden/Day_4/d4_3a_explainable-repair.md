# D4.3A — Explainable Repair

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 4.3 |
| Type | Core |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d4-3a/solution.py` |

## Instructions

Repair seats_left. During inspection, be ready to explain the failing case, the change you made, and the retest you used.

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
| `(20, 8)` | `12` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
