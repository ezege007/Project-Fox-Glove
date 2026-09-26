# D1.5B — Budget Message

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 1.5 |
| Type | Reinforcement |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d1-5b/solution.py` |

## Instructions

Return exactly "Ada has 500 naira remaining." using the supplied name and remaining value.

## Default Code Template

```python
def budget_message(name, remaining):
pass
```

## Allowed Keywords / Constructs

def, return, f-string, string

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `('Ada', 500)` | `'Ada has 500 naira remaining.'` |
| `('Tobi', -300)` | `'Tobi has -300 naira remaining.'` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `('Chika', 0)` | `'Chika has 0 naira remaining.'` |
| `('Mary Jane', 125)` | `'Mary Jane has 125 naira remaining.'` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
