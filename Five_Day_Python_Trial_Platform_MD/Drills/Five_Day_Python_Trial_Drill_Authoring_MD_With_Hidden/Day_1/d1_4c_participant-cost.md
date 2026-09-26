# D1.4C — Participant Cost

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 1.4 |
| Type | Reinforcement |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d1-4c/solution.py` |

## Instructions

Complete participant_cost(attendees, food_per_person, transport_per_person). Return attendees multiplied by the sum of the two per-person costs.

## Default Code Template

```python
def participant_cost(attendees, food_per_person, transport_per_person):
pass
```

## Allowed Keywords / Constructs

def, return, +, *, (, )

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(10, 800, 200)` | `10000` |
| `(0, 800, 200)` | `0` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(3, 700, 300)` | `3000` |
| `(5, 0, 100)` | `500` |
| `(2, 50, 50)` | `200` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
