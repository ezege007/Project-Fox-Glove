# F12 — Repair a Boundary Bug

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Checkpoint | Day 5 Final Coding Checkpoint |
| Day | 5 |
| Classification | Core |
| Raw marks | 10 |
| Language | Python |

## Task

The exact-fit case should return `"Within budget"`. Repair the condition.

## Starter Code

```python
def budget_status(budget, total):
    if total < budget:
        return "Within budget"
    else:
        return "Over budget" 
```

## Allowed Keywords / Constructs

- `if` / `else`
- `<=` or equivalent correct boundary comparison
- `return`

## Restrictions / Forbidden Constructs

- `input()`
- `import` statements
- `eval()` or `exec()`
- hard-coded sample answers
- renaming the supplied function or parameters
- changing the required return strings

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `budget_status(15000, 15000)` | `"Within budget"` |
| `budget_status(14000, 15000)` | `"Over budget"` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `budget_status(15001, 15000)` | `"Within budget"` |
| `budget_status(0, 0)` | `"Within budget"` |
| `budget_status(999, 1000)` | `"Over budget"` |

> **Important:** Hidden samples must be configured as private tests and must not be shown to candidates.
