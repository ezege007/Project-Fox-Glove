# D3.2B — Build the Final Event Summary

> **PRIVATE PLATFORM-AUTHORING COPY**  
> Hidden samples below are for platform configuration only. Do not expose them to candidates.

| Field | Value |
| --- | --- |
| Linked lesson | Lesson 3.2 |
| Type | Reinforcement |
| Coins | 10 |
| Language | Python |
| Suggested graded file | `d3-2b/solution.py` |

## Instructions

Complete event_summary(event_name, total, status). Return exactly "Study Day: total 15000 naira. Within budget." with supplied values substituted.

## Default Code Template

```python
def event_summary(event_name, total, status):
pass
```

## Allowed Keywords / Constructs

def, return, f-string, string

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

| Input / call | Expected result |
| --- | --- |
| `('Study Day', 15000, 'Within budget')` | `'Study Day: total 15000 naira. Within budget.'` |
| `('Tech Day', 17000, 'Over budget')` | `'Tech Day: total 17000 naira. Over budget.'` |

## Private Hidden Sample Tests

| Input / call | Expected result |
| --- | --- |
| `('A', 0, 'Within budget')` | `'A: total 0 naira. Within budget.'` |

> **Important:** Hidden samples must be stored in the platform's private test configuration and must not be rendered to the learner.
