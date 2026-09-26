# D2.3B — Calculate Then Format

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 2.3 |
| Type | Reinforcement |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d2-3b/solution.py` |

## Instructions

Complete budget_report so it calls budget_left and uses the returned value in the exact message "500 naira remaining."

## Default Code Template

```python
def budget_left(budget, food, transport):
return budget - food - transport

def budget_report(budget, food, transport):
pass
```

## Allowed Keywords / Constructs

def, return, =, function call, f-string

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(2000, 900, 600)` | `'500 naira remaining.'` |
| `(1000, 800, 500)` | `'-300 naira remaining.'` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(0, 0, 0)` | `'0 naira remaining.'` |
| `(500, 125, 125)` | `'250 naira remaining.'` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
