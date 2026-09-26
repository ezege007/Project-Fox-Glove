# B10 — Stretch: Count Matching Values

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Checkpoint | Day 2 Baseline Checkpoint |
| Day | 2 |
| Classification | Stretch |
| Raw marks | 10 |
| Language | Python |

## Task

Return how many numbers in `values` are greater than or equal to `limit`.

## Starter Code

```python
def count_at_least(values, limit):
    pass
```

## Allowed Keywords / Constructs

- `for` / `in`
- `if`
- `>=`
- counter with `+`
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
| `count_at_least([2, 5, 7, 1], 5)` | `2` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `count_at_least([], 5)` | `0` |
| `count_at_least([5, 5, 4], 5)` | `2` |
| `count_at_least([1, 2, 3], 10)` | `0` |
| `count_at_least([10, 11], 10)` | `2` |

> **Important:** Hidden samples must be configured as private tests and must not be shown to candidates.
