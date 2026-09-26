# D1.7B — Repair a Small Logic Error

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 1.7 |
| Type | Reinforcement |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d1-7b/solution.py` |

## Instructions

The function is meant to return the remaining budget after a printing cost. Repair the arithmetic.

## Default Code Template

```python
def print_balance(budget, pages, price_per_page):
cost = pages + price_per_page
return budget + cost
```

## Allowed Keywords / Constructs

def, return, =, *, -

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(1000, 4, 100)` | `600` |
| `(500, 6, 100)` | `-100` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(1500, 5, 200)` | `500` |
| `(800, 0, 50)` | `800` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
