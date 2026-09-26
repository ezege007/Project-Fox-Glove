# D1.6B — Return, Do Not Display

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 1.6 |
| Type | Reinforcement |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d1-6b/solution.py` |

## Instructions

Repair combined_cost so that it returns the sum instead of printing it. It must produce no printed output.

## Default Code Template

```python
def combined_cost(first, second):
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
| `(20, 30)` | `50` |
| `(0, 5)` | `5` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(350, 125)` | `475` |
| `(0, 0)` | `0` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
