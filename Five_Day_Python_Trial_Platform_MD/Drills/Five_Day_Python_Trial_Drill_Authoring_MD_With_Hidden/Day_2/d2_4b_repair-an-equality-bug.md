# D2.4B — Repair an Equality Bug

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 2.4 |
| Type | Reinforcement |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d2-4b/solution.py` |

## Instructions

The brief says an exact budget match is "Within budget". Repair the function.

## Default Code Template

```python
def budget_status(budget, total):
if total < budget:
return "Within budget"
else:
return "Over budget"
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
