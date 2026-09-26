# D4.2B — Repair Without Breaking a Passing Helper

| **Linked lesson**         | Lesson 4.2        |
|---------------------------|-------------------|
| **Type**                  | Reinforcement     |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d4-2b/solution.py |

## Instructions (Markdown)

item_cost is correct. Fix only delivered_cost so it returns the correct total. Do not change item_cost.

## Default Code Template

def item_cost(price, quantity):  
return price \* quantity  
  
def delivered_cost(price, quantity, delivery):  
subtotal = item_cost(price, quantity)  
return subtotal - delivery

## Allowed Keywords / Constructs

def, return, =, +, function call

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(200, 3, 100) =\> 700

(100, 0, 50) =\> 50
