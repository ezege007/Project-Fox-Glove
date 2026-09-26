# D2.3A — Event Total with a Helper

| **Linked lesson**         | Lesson 2.3        |
|---------------------------|-------------------|
| **Type**                  | Core              |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d2-3a/solution.py |

## Instructions (Markdown)

participant_cost is supplied. Complete event_total by calling participant_cost and adding venue_cost.

## Default Code Template

def participant_cost(attendees, food_per_person, transport_per_person):  
return attendees \* (food_per_person + transport_per_person)  
  
def event_total(attendees, food_per_person, transport_per_person, venue_cost):  
pass

## Allowed Keywords / Constructs

def, return, =, +, function call

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(10, 800, 200, 5000) =\> 15000

(0, 800, 200, 5000) =\> 5000
