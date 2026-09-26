# F8 — Two-Branch Decision

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

Return `"Enough"` when `budget >= cost`; otherwise return `"Not enough"`.

## Starter Code

```python
def funding_status(budget, cost):
    pass
```

## Allowed Keywords / Constructs

- `if` / `else`
- `>=`
- `return`

## Restrictions / Forbidden Constructs

- `input()`
- `import` statements
- `eval()` or `exec()`
- hard-coded sample answers
- renaming the supplied function or parameters
- `print()`

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `funding_status(700, 700)` | `"Enough"` |
| `funding_status(500, 700)` | `"Not enough"` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `funding_status(701, 700)` | `"Enough"` |
| `funding_status(0, 0)` | `"Enough"` |
| `funding_status(699, 700)` | `"Not enough"` |

> **Important:** Hidden samples must be configured as private tests and must not be shown to candidates.
