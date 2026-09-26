# D1.6C — Trace a Returned Value

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 1.6 |
| Type | Reinforcement |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d1-6c/solution.py` |

## Instructions

Complete final_total so it calls subtotal, stores the returned answer, and adds service_fee.

## Default Code Template

```python
def subtotal(first, second):
return first + second

def final_total(first, second, service_fee):
pass
```

## Allowed Keywords / Constructs

def, return, =, +, function call

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(100, 200, 50)` | `350` |
| `(0, 0, 25)` | `25` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(10, 15, 0)` | `25` |
| `(500, 200, 100)` | `800` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
