# D3.3B — Repair a Teammate Component

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 3.3 |
| Type | Reinforcement |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d3-3b/solution.py` |

## Instructions

A teammate wrote the wrong operation. Repair event_total so it adds venue_cost after calling participant_cost.

## Default Code Template

```python
def participant_cost(attendees, food_per_person, transport_per_person):
return attendees * (food_per_person + transport_per_person)

def event_total(attendees, food_per_person, transport_per_person, venue_cost):
people = participant_cost(attendees, food_per_person, transport_per_person)
return people - venue_cost
```

## Allowed Keywords / Constructs

def, return, =, +, function call

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(10, 800, 200, 5000)` | `15000` |
| `(0, 0, 0, 0)` | `0` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(3, 700, 300, 2000)` | `5000` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
