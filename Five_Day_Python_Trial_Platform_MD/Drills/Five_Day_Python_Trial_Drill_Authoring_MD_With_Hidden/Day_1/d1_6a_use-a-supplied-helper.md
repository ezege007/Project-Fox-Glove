# D1.6A — Use a Supplied Helper

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 1.6 |
| Type | Core |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d1-6a/solution.py` |

## Instructions

item_cost is supplied and correct. Complete delivered_cost so it calls item_cost(price, quantity), then adds delivery to the returned subtotal.

## Default Code Template

```python
def item_cost(price, quantity):
return price * quantity

def delivered_cost(price, quantity, delivery):
pass
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
| `(1, 1, 1)` | `2` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
