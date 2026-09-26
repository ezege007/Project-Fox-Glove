# D2.5B — Apply Feedback Without Changing the Contract

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 2.5 |
| Type | Reinforcement |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d2-5b/solution.py` |

## Instructions

The original function returns the wrong sentence. Fix only the function body. Keep its name and parameters unchanged and return exactly "Tobi has 250 naira left." for name="Tobi", remaining=250.

## Default Code Template

```python
def remaining_message(name, remaining):
return f"{remaining} left for {name}"
```

## Allowed Keywords / Constructs

def, return, f-string, string

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `('Tobi', 250)` | `'Tobi has 250 naira left.'` |
| `('Ada', 0)` | `'Ada has 0 naira left.'` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `('Mary Jane', -50)` | `'Mary Jane has -50 naira left.'` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
