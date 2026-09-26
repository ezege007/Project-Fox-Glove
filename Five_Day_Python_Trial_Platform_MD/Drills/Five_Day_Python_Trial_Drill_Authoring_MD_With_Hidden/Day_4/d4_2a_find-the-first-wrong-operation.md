# D4.2A — Find the First Wrong Operation

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 4.2 |
| Type | Core |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d4-2a/solution.py` |

## Instructions

Repair the two arithmetic mistakes so print_balance returns the remaining budget.

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
| `(800, 0, 50)` | `800` |
| `(300, 4, 100)` | `-100` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
