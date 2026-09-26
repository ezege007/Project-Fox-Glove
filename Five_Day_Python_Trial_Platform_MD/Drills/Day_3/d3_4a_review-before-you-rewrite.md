# D3.4A — Review Before You Rewrite

| **Linked lesson**         | Lesson 3.4        |
|---------------------------|-------------------|
| **Type**                  | Core              |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d3-4a/solution.py |

## Instructions (Markdown)

Repair only the incorrect comparison in budget_status. Do not rename the function, change its inputs, or add unrelated features.

## Default Code Template

def budget_status(budget, total):  
if total \>= budget:  
return "Within budget"  
else:  
return "Over budget"

## Allowed Keywords / Constructs

def, return, if, else, \<=

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(16000, 15000) =\> 'Within budget'

(15000, 15000) =\> 'Within budget'
