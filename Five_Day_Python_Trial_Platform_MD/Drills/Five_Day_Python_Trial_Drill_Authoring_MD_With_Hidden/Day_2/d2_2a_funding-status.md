# D2.2A — Funding Status

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 2.2 |
| Type | Core |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d2-2a/solution.py` |

## Instructions

Return "Enough" when budget is greater than or equal to cost. Otherwise return "Not enough". Exact equality counts as enough.

## Default Code Template

```python
def funding_status(budget, cost):
pass
```

## Allowed Keywords / Constructs

def, return, if, else, >=, string

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(1000, 700)` | `'Enough'` |
| `(700, 700)` | `'Enough'` |
| `(500, 700)` | `'Not enough'` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `(0, 0)` | `'Enough'` |
| `(200, 500)` | `'Not enough'` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
