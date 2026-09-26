# D3.1A — Implement a Component Contract

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 3.1 |
| Type | Core |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d3-1a/solution.py` |

## Instructions

Implement participant_cost exactly as specified: attendees * (food_per_person + transport_per_person). Return an integer.

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
| `(0, 0, 0)` | `0` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(3, 700, 300)` | `3000` |
| `(5, 100, 0)` | `500` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
