# B1 — Return a Sum

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Checkpoint | Day 2 Baseline Checkpoint |
| Day | 2 |
| Classification | Core |
| Raw marks | 10 |
| Language | Python |

## Task

Repair the function so it returns the integer sum of `first` and `second` and produces no printed output.

## Starter Code

```python
def combined_cost(first, second):
    total = first + second
    print(total)
```

## Allowed Keywords / Constructs

- `def`
- assignment
- `+`
- `return`

## Restrictions / Forbidden Constructs

- `input()`
- `import` statements
- `eval()` or `exec()`
- hard-coded sample answers
- renaming the supplied function or parameters
- `print()` in the final solution

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `combined_cost(120, 80)` | `200` |
| `combined_cost(0, 25)` | `25` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `combined_cost(7, 8)` | `15` |
| `combined_cost(1000, 1)` | `1001` |
| `combined_cost(0, 0)` | `0` |

> **Important:** Hidden samples must be configured as private tests and must not be shown to candidates.
