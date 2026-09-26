# D4.1A — Preserve Earlier Behaviour

| **Linked lesson**         | Lesson 4.1        |
|---------------------------|-------------------|
| **Type**                  | Core              |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d4-1a/solution.py |

## Instructions (Markdown)

Add equipment_cost to event_total while preserving participant and venue calculations. Use the supplied helper.

## Default Code Template

def participant_cost(attendees, food_per_person, transport_per_person):  
return attendees \* (food_per_person + transport_per_person)  
  
def event_total(attendees, food_per_person, transport_per_person, venue_cost, equipment_cost):  
pass

## Allowed Keywords / Constructs

def, return, =, +, function call

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(10, 800, 200, 5000, 1000) =\> 16000

(0, 0, 0, 5000, 0) =\> 5000
