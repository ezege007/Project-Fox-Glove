# D3.1B — Implement the Status Contract

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 3.1 |
| Type | Reinforcement |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d3-1b/solution.py` |

## Instructions

Complete budget_status(budget, total). Return "Within budget" when total <= budget; otherwise return "Over budget".

## Default Code Template

```python
def budget_status(budget, total):
pass
```

## Allowed Keywords / Constructs

def, return, if, else, <=

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(16000, 15000)` | `'Within budget'` |
| `(15000, 15000)` | `'Within budget'` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(14000, 15000)` | `'Over budget'` |
| `(0, 0)` | `'Within budget'` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
