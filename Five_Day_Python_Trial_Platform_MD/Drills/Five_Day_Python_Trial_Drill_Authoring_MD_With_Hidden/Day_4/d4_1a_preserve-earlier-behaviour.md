# D4.1A — Preserve Earlier Behaviour

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 4.1 |
| Type | Core |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d4-1a/solution.py` |

## Instructions

Add equipment_cost to event_total while preserving participant and venue calculations. Use the supplied helper.

## Default Code Template

```python
def participant_cost(attendees, food_per_person, transport_per_person):
return attendees * (food_per_person + transport_per_person)

def event_total(attendees, food_per_person, transport_per_person, venue_cost, equipment_cost):
pass
```

## Allowed Keywords / Constructs

def, return, =, +, function call

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(10, 800, 200, 5000, 1000)` | `16000` |
| `(0, 0, 0, 5000, 0)` | `5000` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(3, 700, 300, 2000, 500)` | `5500` |
| `(0, 0, 0, 0, 0)` | `0` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
