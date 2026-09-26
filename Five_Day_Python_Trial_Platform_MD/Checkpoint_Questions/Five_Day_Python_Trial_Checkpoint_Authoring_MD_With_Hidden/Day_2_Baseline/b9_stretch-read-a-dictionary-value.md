# B9 — Stretch: Read a Dictionary Value

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

Return the value stored under the key `"name"`.

## Starter Code

```python
def get_name(person):
    pass
```

## Allowed Keywords / Constructs

- dictionary indexing or `.get()`
- `return`

## Restrictions / Forbidden Constructs

- `input()`
- `import` statements
- `eval()` or `exec()`
- hard-coded sample answers
- renaming the supplied function or parameters
- `print()`
- hard-coding a name

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `get_name({"name": "Ada", "age": 20})` | `"Ada"` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `get_name({"name": "Tobi"})` | `"Tobi"` |
| `get_name({"age": 30, "name": "Mira"})` | `"Mira"` |

> **Important:** Hidden samples must be configured as private tests and must not be shown to candidates.
