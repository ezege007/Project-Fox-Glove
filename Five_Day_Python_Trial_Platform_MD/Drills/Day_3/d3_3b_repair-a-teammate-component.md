# D3.3B — Repair a Teammate Component

| **Linked lesson**         | Lesson 3.3        |
|---------------------------|-------------------|
| **Type**                  | Reinforcement     |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d3-3b/solution.py |

## Instructions (Markdown)

A teammate wrote the wrong operation. Repair event_total so it adds venue_cost after calling participant_cost.

## Default Code Template

def participant_cost(attendees, food_per_person, transport_per_person):  
return attendees \* (food_per_person + transport_per_person)  
  
def event_total(attendees, food_per_person, transport_per_person, venue_cost):  
people = participant_cost(attendees, food_per_person, transport_per_person)  
return people - venue_cost

## Allowed Keywords / Constructs

def, return, =, +, function call

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(10, 800, 200, 5000) =\> 15000

(0, 0, 0, 0) =\> 0
