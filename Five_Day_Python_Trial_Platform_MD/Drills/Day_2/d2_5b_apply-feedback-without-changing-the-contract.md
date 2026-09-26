# D2.5B — Apply Feedback Without Changing the Contract

| **Linked lesson**         | Lesson 2.5        |
|---------------------------|-------------------|
| **Type**                  | Reinforcement     |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d2-5b/solution.py |

## Instructions (Markdown)

The original function returns the wrong sentence. Fix only the function body. Keep its name and parameters unchanged and return exactly "Tobi has 250 naira left." for name="Tobi", remaining=250.

## Default Code Template

def remaining_message(name, remaining):  
return f"{remaining} left for {name}"

## Allowed Keywords / Constructs

def, return, f-string, string

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

('Tobi', 250) =\> 'Tobi has 250 naira left.'

('Ada', 0) =\> 'Ada has 0 naira left.'
