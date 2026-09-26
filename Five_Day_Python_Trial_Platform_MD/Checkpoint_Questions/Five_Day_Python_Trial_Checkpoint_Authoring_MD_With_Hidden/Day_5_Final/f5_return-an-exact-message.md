# F5 — Return an Exact Message

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

Return exactly `Ada completed 4 tasks.` using the supplied values.

## Starter Code

```python
def learner_message(name, tasks):
    pass
```

## Allowed Keywords / Constructs

- strings
- f-strings or string formatting
- `return`

## Restrictions / Forbidden Constructs

- `input()`
- `import` statements
- `eval()` or `exec()`
- hard-coded sample answers
- renaming the supplied function or parameters
- `print()`
- hard-coding sample values

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `learner_message("Ada", 4)` | `"Ada completed 4 tasks."` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `learner_message("Tobi", 0)` | `"Tobi completed 0 tasks."` |
| `learner_message("Mira", 12)` | `"Mira completed 12 tasks."` |

> **Important:** Hidden samples must be configured as private tests and must not be shown to candidates.
