# F7 — Exact Boundary Comparison

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

Return `True` when `booked` is at most `capacity`, otherwise `False`.

## Starter Code

```python
def fits(capacity, booked):
    pass
```

## Allowed Keywords / Constructs

- comparison with `<=`
- Boolean return value
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
| `fits(10, 10)` | `True` |
| `fits(10, 11)` | `False` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `fits(10, 9)` | `True` |
| `fits(0, 0)` | `True` |
| `fits(5, 6)` | `False` |

> **Important:** Hidden samples must be configured as private tests and must not be shown to candidates.
