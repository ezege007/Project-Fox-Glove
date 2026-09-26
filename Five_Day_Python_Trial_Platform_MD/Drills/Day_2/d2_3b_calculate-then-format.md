# D2.3B — Calculate Then Format

| **Linked lesson**         | Lesson 2.3        |
|---------------------------|-------------------|
| **Type**                  | Reinforcement     |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d2-3b/solution.py |

## Instructions (Markdown)

Complete budget_report so it calls budget_left and uses the returned value in the exact message "500 naira remaining."

## Default Code Template

def budget_left(budget, food, transport):  
return budget - food - transport  
  
def budget_report(budget, food, transport):  
pass

## Allowed Keywords / Constructs

def, return, =, function call, f-string

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(2000, 900, 600) =\> '500 naira remaining.'

(1000, 800, 500) =\> '-300 naira remaining.'
