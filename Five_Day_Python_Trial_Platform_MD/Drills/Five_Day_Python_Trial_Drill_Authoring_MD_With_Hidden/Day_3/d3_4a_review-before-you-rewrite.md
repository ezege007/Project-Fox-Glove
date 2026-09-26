# D3.4A — Review Before You Rewrite

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 3.4 |
| Type | Core |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d3-4a/solution.py` |

## Instructions

Repair only the incorrect comparison in budget_status. Do not rename the function, change its inputs, or add unrelated features.

## Default Code Template

```python
def budget_status(budget, total):
if total >= budget:
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
