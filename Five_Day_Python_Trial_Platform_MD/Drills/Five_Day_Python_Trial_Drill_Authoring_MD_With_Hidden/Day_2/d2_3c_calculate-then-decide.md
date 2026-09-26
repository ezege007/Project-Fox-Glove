# D2.3C — Calculate Then Decide

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 2.3 |
| Type | Reinforcement |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d2-3c/solution.py` |

## Instructions

Complete trip_status so it calls trip_cost and returns "Within budget" when the returned total is at most budget; otherwise return "Over budget".

## Default Code Template

```python
def trip_cost(fare, trips):
return fare * trips

def trip_status(budget, fare, trips):
pass
```

## Allowed Keywords / Constructs

def, return, =, function call, if, else, <=

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(1000, 200, 3)` | `'Within budget'` |
| `(500, 200, 3)` | `'Over budget'` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(600, 200, 3)` | `'Within budget'` |
| `(0, 0, 0)` | `'Within budget'` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
