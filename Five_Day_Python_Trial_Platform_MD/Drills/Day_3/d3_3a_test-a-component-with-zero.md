# D3.3A — Test a Component with Zero

| **Linked lesson**         | Lesson 3.3        |
|---------------------------|-------------------|
| **Type**                  | Core              |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d3-3a/solution.py |

## Instructions (Markdown)

Complete venue_only_total so it returns venue_cost when attendees is zero and otherwise returns attendee costs plus venue. Use the supplied participant_cost helper.

## Default Code Template

def participant_cost(attendees, food_per_person, transport_per_person):  
return attendees \* (food_per_person + transport_per_person)  
  
def venue_only_total(attendees, food_per_person, transport_per_person, venue_cost):  
pass

## Allowed Keywords / Constructs

def, return, =, +, function call

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(0, 800, 200, 5000) =\> 5000

(10, 800, 200, 5000) =\> 15000
