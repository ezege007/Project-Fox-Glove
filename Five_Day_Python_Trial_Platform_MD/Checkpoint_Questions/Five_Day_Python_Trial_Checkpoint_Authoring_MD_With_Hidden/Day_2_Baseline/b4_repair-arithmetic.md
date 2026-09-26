# B4 — Repair Arithmetic

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

The function has two arithmetic mistakes. Repair it so it returns `budget - (pages * price_per_page)`.

## Starter Code

```python
def print_balance(budget, pages, price_per_page):
    cost = pages + price_per_page
    return budget + cost
```

## Allowed Keywords / Constructs

- `def`
- assignment
- `*`
- `-`
- `return`

## Restrictions / Forbidden Constructs

- `input()`
- `import` statements
- `eval()` or `exec()`
- hard-coded sample answers
- renaming the supplied function or parameters
- changing the function signature

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `print_balance(1000, 4, 100)` | `600` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `print_balance(500, 6, 100)` | `-100` |
| `print_balance(0, 0, 100)` | `0` |
| `print_balance(2000, 3, 250)` | `1250` |

> **Important:** Hidden samples must be configured as private tests and must not be shown to candidates.
