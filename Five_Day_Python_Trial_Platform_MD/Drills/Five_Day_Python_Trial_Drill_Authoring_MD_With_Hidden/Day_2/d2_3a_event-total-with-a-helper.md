# D2.3A — Event Total with a Helper

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 2.3 |
| Type | Core |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d2-3a/solution.py` |

## Instructions

participant_cost is supplied. Complete event_total by calling participant_cost and adding venue_cost.

## Default Code Template

```python
def participant_cost(attendees, food_per_person, transport_per_person):
return attendees * (food_per_person + transport_per_person)

def event_total(attendees, food_per_person, transport_per_person, venue_cost):
pass
```

## Allowed Keywords / Constructs

def, return, =, +, function call

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(10, 800, 200, 5000)` | `15000` |
| `(0, 800, 200, 5000)` | `5000` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(3, 700, 300, 2000)` | `5000` |
| `(0, 0, 0, 0)` | `0` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
