# D4.2B — Repair Without Breaking a Passing Helper

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 4.2 |
| Type | Reinforcement |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d4-2b/solution.py` |

## Instructions

item_cost is correct. Fix only delivered_cost so it returns the correct total. Do not change item_cost.

## Default Code Template

```python
def item_cost(price, quantity):
return price * quantity

def delivered_cost(price, quantity, delivery):
subtotal = item_cost(price, quantity)
return subtotal - delivery
```

## Allowed Keywords / Constructs

def, return, =, +, function call

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(200, 3, 100)` | `700` |
| `(100, 0, 50)` | `50` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(25, 4, 0)` | `100` |
| `(0, 5, 20)` | `20` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
