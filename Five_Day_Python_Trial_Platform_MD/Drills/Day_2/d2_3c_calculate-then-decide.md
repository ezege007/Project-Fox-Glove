# D2.3C — Calculate Then Decide

| **Linked lesson**         | Lesson 2.3        |
|---------------------------|-------------------|
| **Type**                  | Reinforcement     |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d2-3c/solution.py |

## Instructions (Markdown)

Complete trip_status so it calls trip_cost and returns "Within budget" when the returned total is at most budget; otherwise return "Over budget".

## Default Code Template

def trip_cost(fare, trips):  
return fare \* trips  
  
def trip_status(budget, fare, trips):  
pass

## Allowed Keywords / Constructs

def, return, =, function call, if, else, \<=

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(1000, 200, 3) =\> 'Within budget'

(500, 200, 3) =\> 'Over budget'
