# D1.3B — Repair the Missing Return

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 1.3 |
| Type | Reinforcement |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d1-3b/solution.py` |

## Instructions

The function calculates the correct value but does not return it. Repair the function so the caller receives the integer result and the function prints nothing.

## Default Code Template

```python
def total_cost(first, second):
total = first + second
print(total)
```

## Allowed Keywords / Constructs

def, return, +, =

## Restrictions / Forbidden Strings

print, input, import

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(50, 75)` | `125` |
| `(0, 10)` | `10` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(900, 100)` | `1000` |
| `(4, 6)` | `10` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
