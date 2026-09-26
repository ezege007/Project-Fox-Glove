# D1.7A — Follow the Brief Exactly

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 1.7 |
| Type | Core |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d1-7a/solution.py` |

## Instructions

Complete learner_status(name, tasks) to return exactly "Ada completed 4 tasks." Use the supplied values and keep the word tasks even when the value is 1.

## Default Code Template

```python
def learner_status(name, tasks):
pass
```

## Allowed Keywords / Constructs

def, return, f-string, string

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `('Ada', 4)` | `'Ada completed 4 tasks.'` |
| `('Tobi', 0)` | `'Tobi completed 0 tasks.'` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `('A', 1)` | `'A completed 1 tasks.'` |
| `('Mary Jane', 2)` | `'Mary Jane completed 2 tasks.'` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
