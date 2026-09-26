# F1 — Return, Do Not Print

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

Repair `combined_cost` so it returns the integer result and produces no printed output.

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
| `combined_cost(150, 50)` | `200` |
| `combined_cost(0, 0)` | `0` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `combined_cost(17, 23)` | `40` |
| `combined_cost(900, 100)` | `1000` |
| `combined_cost(1, 0)` | `1` |

> **Important:** Hidden samples must be configured as private tests and must not be shown to candidates.
