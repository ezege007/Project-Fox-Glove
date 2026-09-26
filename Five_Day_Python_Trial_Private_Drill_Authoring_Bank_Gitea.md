Administrator / curriculum team copy — do not publish hidden tests or reference solutions

**Self-learning • peer-supported • beginner-friendly • AI-aware**

# How to Use This File

This file translates the learner-facing drill titles into platform-authoring fields similar to the challenge configuration screen: display name, coins, instructions, default code template, allowed constructs, restrictions, visible sample checks, private hidden checks and inspection prompts. Hidden tests and reference solutions must not be visible to learners.

Core drills are the minimum linked assessment after the lesson. Reinforcement drills test the same lesson from another angle and may be assigned when time permits or when a learner needs more practice. Drill coins reward completion/activity only; they do not directly change the agreed 100-point selection weighting.

**Repository platform note:** Lesson 1.1 teaches Git concepts using Gitea, the repository hosting platform used for the trial. It intentionally has no coding drill; repository use is observed as work evidence instead.

# Lesson-to-Drill Map

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>Lesson</strong></th>
<th><strong>Core drill(s)</strong></th>
<th><strong>Reinforcement drill(s)</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Lesson 1.2</td>
<td>D1.2A Add Two Item Costs</td>
<td>D1.2B Calculate Remaining Money</td>
</tr>
<tr class="even">
<td>Lesson 1.3</td>
<td>D1.3A Complete Your First Function</td>
<td>D1.3B Repair the Missing Return</td>
</tr>
<tr class="odd">
<td>Lesson 1.4</td>
<td>D1.4A Travel Cost<br />
D1.4B Budget After Two Costs</td>
<td>D1.4C Participant Cost</td>
</tr>
<tr class="even">
<td>Lesson 1.5</td>
<td>D1.5A Welcome Message</td>
<td>D1.5B Budget Message</td>
</tr>
<tr class="odd">
<td>Lesson 1.6</td>
<td>D1.6A Use a Supplied Helper</td>
<td>D1.6B Return, Do Not Display<br />
D1.6C Trace a Returned Value</td>
</tr>
<tr class="even">
<td>Lesson 1.7</td>
<td>D1.7A Follow the Brief Exactly</td>
<td>D1.7B Repair a Small Logic Error</td>
</tr>
<tr class="odd">
<td>Lesson 2.1</td>
<td>D2.1A Can the Budget Cover the Cost?</td>
<td>D2.1B Compare Two Totals</td>
</tr>
<tr class="even">
<td>Lesson 2.2</td>
<td>D2.2A Funding Status</td>
<td>D2.2B Capacity Status<br />
D2.2C Positive Places</td>
</tr>
<tr class="odd">
<td>Lesson 2.3</td>
<td>D2.3A Event Total with a Helper</td>
<td>D2.3B Calculate Then Format<br />
D2.3C Calculate Then Decide</td>
</tr>
<tr class="even">
<td>Lesson 2.4</td>
<td>D2.4A Repair Printing Cost</td>
<td>D2.4B Repair an Equality Bug<br />
D2.4C Retest After a Fix</td>
</tr>
<tr class="odd">
<td>Lesson 2.5</td>
<td>D2.5A Build from a Written Brief</td>
<td>D2.5B Apply Feedback Without Changing the Contract</td>
</tr>
<tr class="even">
<td>Lesson 3.1</td>
<td>D3.1A Implement a Component Contract</td>
<td>D3.1B Implement the Status Contract</td>
</tr>
<tr class="odd">
<td>Lesson 3.2</td>
<td>D3.2A Integrate Participant and Venue Costs</td>
<td>D3.2B Build the Final Event Summary</td>
</tr>
<tr class="even">
<td>Lesson 3.3</td>
<td>D3.3A Test a Component with Zero</td>
<td>D3.3B Repair a Teammate Component</td>
</tr>
<tr class="odd">
<td>Lesson 3.4</td>
<td>D3.4A Review Before You Rewrite</td>
<td>—</td>
</tr>
<tr class="even">
<td>Lesson 4.1</td>
<td>D4.1A Preserve Earlier Behaviour</td>
<td>D4.1B Regression Check: Exact Fit</td>
</tr>
<tr class="odd">
<td>Lesson 4.2</td>
<td>D4.2A Find the First Wrong Operation</td>
<td>D4.2B Repair Without Breaking a Passing Helper</td>
</tr>
<tr class="even">
<td>Lesson 4.3</td>
<td>D4.3A Explainable Repair</td>
<td>—</td>
</tr>
</tbody>
</table>

# D1.2A — Add Two Item Costs

| **Linked lesson**         | Lesson 1.2        |
|---------------------------|-------------------|
| **Type**                  | Core              |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d1-2a/solution.py |

## Instructions (Markdown)

Complete item_total(first, second). Return the total cost of the two supplied non-negative integer amounts. Do not hard-code the sample answer.

## Default Code Template

def item_total(first, second):  
pass

## Allowed Keywords / Constructs

def, return, +

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(200, 300) =\> 500

(450, 150) =\> 600

## Private Hidden Tests

(0, 0) =\> 0

(125, 375) =\> 500

(900, 100) =\> 1000

## Private Reference Solution

def item_total(first, second):  
return first + second

# D1.2B — Calculate Remaining Money

| **Linked lesson**         | Lesson 1.2        |
|---------------------------|-------------------|
| **Type**                  | Reinforcement     |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d1-2b/solution.py |

## Instructions (Markdown)

Complete remaining_money(budget, spent). Return budget minus spent. A negative answer is allowed.

## Default Code Template

def remaining_money(budget, spent):  
pass

## Allowed Keywords / Constructs

def, return, -

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(1000, 600) =\> 400

(500, 500) =\> 0

## Private Hidden Tests

(0, 0) =\> 0

(300, 450) =\> -150

(2500, 125) =\> 2375

## Private Reference Solution

def remaining_money(budget, spent):  
return budget - spent

# D1.3A — Complete Your First Function

| **Linked lesson**         | Lesson 1.3        |
|---------------------------|-------------------|
| **Type**                  | Core              |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d1-3a/solution.py |

## Instructions (Markdown)

Complete add_costs(first, second) so that it returns the sum of the supplied values. Keep the function name and parameters unchanged.

## Default Code Template

def add_costs(first, second):  
pass

## Allowed Keywords / Constructs

def, return, +

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(120, 80) =\> 200

(0, 25) =\> 25

## Private Hidden Tests

(7, 8) =\> 15

(1000, 1) =\> 1001

(0, 0) =\> 0

## Private Reference Solution

def add_costs(first, second):  
return first + second

# D1.3B — Repair the Missing Return

| **Linked lesson**         | Lesson 1.3        |
|---------------------------|-------------------|
| **Type**                  | Reinforcement     |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d1-3b/solution.py |

## Instructions (Markdown)

The function calculates the correct value but does not return it. Repair the function so the caller receives the integer result and the function prints nothing.

## Default Code Template

def total_cost(first, second):  
total = first + second  
print(total)

## Allowed Keywords / Constructs

def, return, +, =

## Restrictions / Forbidden Strings

print, input, import

## Visible Sample Tests

(50, 75) =\> 125

(0, 10) =\> 10

## Private Hidden Tests

(900, 100) =\> 1000

(4, 6) =\> 10

## Private Reference Solution

def total_cost(first, second):  
total = first + second  
return total

# D1.4A — Travel Cost

| **Linked lesson**         | Lesson 1.4        |
|---------------------------|-------------------|
| **Type**                  | Core              |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d1-4a/solution.py |

## Instructions (Markdown)

Complete travel_cost(fare, trips). Return fare multiplied by trips.

## Default Code Template

def travel_cost(fare, trips):  
pass

## Allowed Keywords / Constructs

def, return, \*

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(200, 3) =\> 600

(150, 0) =\> 0

## Private Hidden Tests

(75, 4) =\> 300

(0, 9) =\> 0

(1000, 1) =\> 1000

## Private Reference Solution

def travel_cost(fare, trips):  
return fare \* trips

# D1.4B — Budget After Two Costs

| **Linked lesson**         | Lesson 1.4        |
|---------------------------|-------------------|
| **Type**                  | Core              |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d1-4b/solution.py |

## Instructions (Markdown)

Complete budget_left(budget, food, transport). Return budget minus food minus transport.

## Default Code Template

def budget_left(budget, food, transport):  
pass

## Allowed Keywords / Constructs

def, return, -

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(2000, 900, 600) =\> 500

(1000, 700, 300) =\> 0

## Private Hidden Tests

(1000, 800, 500) =\> -300

(0, 0, 0) =\> 0

(2500, 250, 500) =\> 1750

## Private Reference Solution

def budget_left(budget, food, transport):  
return budget - food - transport

# D1.4C — Participant Cost

| **Linked lesson**         | Lesson 1.4        |
|---------------------------|-------------------|
| **Type**                  | Reinforcement     |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d1-4c/solution.py |

## Instructions (Markdown)

Complete participant_cost(attendees, food_per_person, transport_per_person). Return attendees multiplied by the sum of the two per-person costs.

## Default Code Template

def participant_cost(attendees, food_per_person, transport_per_person):  
pass

## Allowed Keywords / Constructs

def, return, +, \*, (, )

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(10, 800, 200) =\> 10000

(0, 800, 200) =\> 0

## Private Hidden Tests

(3, 700, 300) =\> 3000

(5, 0, 100) =\> 500

(2, 50, 50) =\> 200

## Private Reference Solution

def participant_cost(attendees, food_per_person, transport_per_person):  
return attendees \* (food_per_person + transport_per_person)

# D1.5A — Welcome Message

| **Linked lesson**         | Lesson 1.5        |
|---------------------------|-------------------|
| **Type**                  | Core              |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d1-5a/solution.py |

## Instructions (Markdown)

Return exactly "Welcome Ada." with the supplied name substituted. Preserve spaces and the final full stop.

## Default Code Template

def welcome_message(name):  
pass

## Allowed Keywords / Constructs

def, return, f-string, string

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

('Ada',) =\> 'Welcome Ada.'

('Tobi',) =\> 'Welcome Tobi.'

## Private Hidden Tests

('Mary Jane',) =\> 'Welcome Mary Jane.'

('A',) =\> 'Welcome A.'

## Private Reference Solution

def welcome_message(name):  
return f"Welcome {name}."

# D1.5B — Budget Message

| **Linked lesson**         | Lesson 1.5        |
|---------------------------|-------------------|
| **Type**                  | Reinforcement     |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d1-5b/solution.py |

## Instructions (Markdown)

Return exactly "Ada has 500 naira remaining." using the supplied name and remaining value.

## Default Code Template

def budget_message(name, remaining):  
pass

## Allowed Keywords / Constructs

def, return, f-string, string

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

('Ada', 500) =\> 'Ada has 500 naira remaining.'

('Tobi', -300) =\> 'Tobi has -300 naira remaining.'

## Private Hidden Tests

('Chika', 0) =\> 'Chika has 0 naira remaining.'

('Mary Jane', 125) =\> 'Mary Jane has 125 naira remaining.'

## Private Reference Solution

def budget_message(name, remaining):  
return f"{name} has {remaining} naira remaining."

# D1.6A — Use a Supplied Helper

| **Linked lesson**         | Lesson 1.6        |
|---------------------------|-------------------|
| **Type**                  | Core              |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d1-6a/solution.py |

## Instructions (Markdown)

item_cost is supplied and correct. Complete delivered_cost so it calls item_cost(price, quantity), then adds delivery to the returned subtotal.

## Default Code Template

def item_cost(price, quantity):  
return price \* quantity  
  
def delivered_cost(price, quantity, delivery):  
pass

## Allowed Keywords / Constructs

def, return, =, +, function call

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(200, 3, 100) =\> 700

(100, 0, 50) =\> 50

## Private Hidden Tests

(25, 4, 0) =\> 100

(0, 5, 20) =\> 20

(1, 1, 1) =\> 2

## Inspection Checklist

- Does delivered_cost call the unchanged item_cost helper with price and quantity?

## Private Reference Solution

def item_cost(price, quantity):  
return price \* quantity  
  
def delivered_cost(price, quantity, delivery):  
subtotal = item_cost(price, quantity)  
return subtotal + delivery

# D1.6B — Return, Do Not Display

| **Linked lesson**         | Lesson 1.6        |
|---------------------------|-------------------|
| **Type**                  | Reinforcement     |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d1-6b/solution.py |

## Instructions (Markdown)

Repair combined_cost so that it returns the sum instead of printing it. It must produce no printed output.

## Default Code Template

def combined_cost(first, second):  
total = first + second  
print(total)

## Allowed Keywords / Constructs

def, return, +, =

## Restrictions / Forbidden Strings

print, input, import

## Visible Sample Tests

(20, 30) =\> 50

(0, 5) =\> 5

## Private Hidden Tests

(350, 125) =\> 475

(0, 0) =\> 0

## Private Reference Solution

def combined_cost(first, second):  
total = first + second  
return total

# D1.6C — Trace a Returned Value

| **Linked lesson**         | Lesson 1.6        |
|---------------------------|-------------------|
| **Type**                  | Reinforcement     |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d1-6c/solution.py |

## Instructions (Markdown)

Complete final_total so it calls subtotal, stores the returned answer, and adds service_fee.

## Default Code Template

def subtotal(first, second):  
return first + second  
  
def final_total(first, second, service_fee):  
pass

## Allowed Keywords / Constructs

def, return, =, +, function call

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(100, 200, 50) =\> 350

(0, 0, 25) =\> 25

## Private Hidden Tests

(10, 15, 0) =\> 25

(500, 200, 100) =\> 800

## Inspection Checklist

- Does final_total use the value returned by subtotal?

## Private Reference Solution

def subtotal(first, second):  
return first + second  
  
def final_total(first, second, service_fee):  
base = subtotal(first, second)  
return base + service_fee

# D1.7A — Follow the Brief Exactly

| **Linked lesson**         | Lesson 1.7        |
|---------------------------|-------------------|
| **Type**                  | Core              |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d1-7a/solution.py |

## Instructions (Markdown)

Complete learner_status(name, tasks) to return exactly "Ada completed 4 tasks." Use the supplied values and keep the word tasks even when the value is 1.

## Default Code Template

def learner_status(name, tasks):  
pass

## Allowed Keywords / Constructs

def, return, f-string, string

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

('Ada', 4) =\> 'Ada completed 4 tasks.'

('Tobi', 0) =\> 'Tobi completed 0 tasks.'

## Private Hidden Tests

('A', 1) =\> 'A completed 1 tasks.'

('Mary Jane', 2) =\> 'Mary Jane completed 2 tasks.'

## Private Reference Solution

def learner_status(name, tasks):  
return f"{name} completed {tasks} tasks."

# D1.7B — Repair a Small Logic Error

| **Linked lesson**         | Lesson 1.7        |
|---------------------------|-------------------|
| **Type**                  | Reinforcement     |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d1-7b/solution.py |

## Instructions (Markdown)

The function is meant to return the remaining budget after a printing cost. Repair the arithmetic.

## Default Code Template

def print_balance(budget, pages, price_per_page):  
cost = pages + price_per_page  
return budget + cost

## Allowed Keywords / Constructs

def, return, =, \*, -

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(1000, 4, 100) =\> 600

(500, 6, 100) =\> -100

## Private Hidden Tests

(1500, 5, 200) =\> 500

(800, 0, 50) =\> 800

## Private Reference Solution

def print_balance(budget, pages, price_per_page):  
cost = pages \* price_per_page  
return budget - cost

# D2.1A — Can the Budget Cover the Cost?

| **Linked lesson**         | Lesson 2.1        |
|---------------------------|-------------------|
| **Type**                  | Core              |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d2-1a/solution.py |

## Instructions (Markdown)

Return True when budget is greater than or equal to cost; otherwise return False.

## Default Code Template

def can_afford(budget, cost):  
pass

## Allowed Keywords / Constructs

def, return, \>=, True, False

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(1000, 700) =\> True

(700, 700) =\> True

## Private Hidden Tests

(500, 700) =\> False

(0, 0) =\> True

## Private Reference Solution

def can_afford(budget, cost):  
return budget \>= cost

# D2.1B — Compare Two Totals

| **Linked lesson**         | Lesson 2.1        |
|---------------------------|-------------------|
| **Type**                  | Reinforcement     |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d2-1b/solution.py |

## Instructions (Markdown)

Return True when actual is exactly equal to expected; otherwise return False.

## Default Code Template

def matches_expected(actual, expected):  
pass

## Allowed Keywords / Constructs

def, return, ==, True, False

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(500, 500) =\> True

(499, 500) =\> False

## Private Hidden Tests

(0, 0) =\> True

(-1, -1) =\> True

(10, 11) =\> False

## Private Reference Solution

def matches_expected(actual, expected):  
return actual == expected

# D2.2A — Funding Status

| **Linked lesson**         | Lesson 2.2        |
|---------------------------|-------------------|
| **Type**                  | Core              |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d2-2a/solution.py |

## Instructions (Markdown)

Return "Enough" when budget is greater than or equal to cost. Otherwise return "Not enough". Exact equality counts as enough.

## Default Code Template

def funding_status(budget, cost):  
pass

## Allowed Keywords / Constructs

def, return, if, else, \>=, string

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(1000, 700) =\> 'Enough'

(700, 700) =\> 'Enough'

(500, 700) =\> 'Not enough'

## Private Hidden Tests

(0, 0) =\> 'Enough'

(200, 500) =\> 'Not enough'

## Private Reference Solution

def funding_status(budget, cost):  
if budget \>= cost:  
return "Enough"  
else:  
return "Not enough"

# D2.2B — Capacity Status

| **Linked lesson**         | Lesson 2.2        |
|---------------------------|-------------------|
| **Type**                  | Reinforcement     |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d2-2b/solution.py |

## Instructions (Markdown)

Return "Fits" when booked is at most capacity; otherwise return "Too many".

## Default Code Template

def booking_status(capacity, booked):  
pass

## Allowed Keywords / Constructs

def, return, if, else, \<=, string

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(10, 7) =\> 'Fits'

(10, 10) =\> 'Fits'

## Private Hidden Tests

(10, 11) =\> 'Too many'

(0, 0) =\> 'Fits'

(0, 1) =\> 'Too many'

## Private Reference Solution

def booking_status(capacity, booked):  
if booked \<= capacity:  
return "Fits"  
else:  
return "Too many"

# D2.2C — Positive Places

| **Linked lesson**         | Lesson 2.2        |
|---------------------------|-------------------|
| **Type**                  | Reinforcement     |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d2-2c/solution.py |

## Instructions (Markdown)

Return "Available" when places is greater than zero; otherwise return "Full".

## Default Code Template

def space_status(places):  
pass

## Allowed Keywords / Constructs

def, return, if, else, \>, string

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(2,) =\> 'Available'

(0,) =\> 'Full'

## Private Hidden Tests

(1,) =\> 'Available'

(50,) =\> 'Available'

## Private Reference Solution

def space_status(places):  
if places \> 0:  
return "Available"  
else:  
return "Full"

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

## Private Hidden Tests

(3, 700, 300, 2000) =\> 5000

(0, 0, 0, 0) =\> 0

## Inspection Checklist

- Does event_total call participant_cost rather than repeat the entire calculation?

## Private Reference Solution

def participant_cost(attendees, food_per_person, transport_per_person):  
return attendees \* (food_per_person + transport_per_person)  
  
def event_total(attendees, food_per_person, transport_per_person, venue_cost):  
people = participant_cost(attendees, food_per_person, transport_per_person)  
return people + venue_cost

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

## Private Hidden Tests

(0, 0, 0) =\> '0 naira remaining.'

(500, 125, 125) =\> '250 naira remaining.'

## Inspection Checklist

- Does budget_report use budget_left?

## Private Reference Solution

def budget_left(budget, food, transport):  
return budget - food - transport  
  
def budget_report(budget, food, transport):  
remaining = budget_left(budget, food, transport)  
return f"{remaining} naira remaining."

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

## Private Hidden Tests

(600, 200, 3) =\> 'Within budget'

(0, 0, 0) =\> 'Within budget'

## Inspection Checklist

- Does trip_status call trip_cost and use its result?

## Private Reference Solution

def trip_cost(fare, trips):  
return fare \* trips  
  
def trip_status(budget, fare, trips):  
total = trip_cost(fare, trips)  
if total \<= budget:  
return "Within budget"  
else:  
return "Over budget"

# D2.4A — Repair Printing Cost

| **Linked lesson**         | Lesson 2.4        |
|---------------------------|-------------------|
| **Type**                  | Core              |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d2-4a/solution.py |

## Instructions (Markdown)

The function is meant to return the remaining budget after a printing cost. Repair the arithmetic.

## Default Code Template

def print_balance(budget, pages, price_per_page):  
cost = pages + price_per_page  
return budget + cost

## Allowed Keywords / Constructs

def, return, =, \*, -

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(1000, 4, 100) =\> 600

(500, 6, 100) =\> -100

## Private Hidden Tests

(1500, 5, 200) =\> 500

(800, 0, 50) =\> 800

## Private Reference Solution

def print_balance(budget, pages, price_per_page):  
cost = pages \* price_per_page  
return budget - cost

# D2.4B — Repair an Equality Bug

| **Linked lesson**         | Lesson 2.4        |
|---------------------------|-------------------|
| **Type**                  | Reinforcement     |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d2-4b/solution.py |

## Instructions (Markdown)

The brief says an exact budget match is "Within budget". Repair the function.

## Default Code Template

def budget_status(budget, total):  
if total \< budget:  
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

## Private Hidden Tests

(14000, 15000) =\> 'Over budget'

(0, 0) =\> 'Within budget'

## Private Reference Solution

def budget_status(budget, total):  
if total \<= budget:  
return "Within budget"  
else:  
return "Over budget"

# D2.4C — Retest After a Fix

| **Linked lesson**         | Lesson 2.4        |
|---------------------------|-------------------|
| **Type**                  | Reinforcement     |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d2-4c/solution.py |

## Instructions (Markdown)

Repair seats_left so it subtracts booked from capacity. The platform will test normal, zero and exact-fit cases.

## Default Code Template

def seats_left(capacity, booked):  
return capacity + booked

## Allowed Keywords / Constructs

def, return, -

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(10, 3) =\> 7

(10, 10) =\> 0

## Private Hidden Tests

(0, 0) =\> 0

(7, 0) =\> 7

(20, 8) =\> 12

## Private Reference Solution

def seats_left(capacity, booked):  
return capacity - booked

# D2.5A — Build from a Written Brief

| **Linked lesson**         | Lesson 2.5        |
|---------------------------|-------------------|
| **Type**                  | Core              |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d2-5a/solution.py |

## Instructions (Markdown)

A community workshop charges fee_per_person for each attendee and has a fixed room_cost. Complete workshop_total to return the full integer cost.

## Default Code Template

def workshop_total(attendees, fee_per_person, room_cost):  
pass

## Allowed Keywords / Constructs

def, return, \*, +

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(10, 500, 2000) =\> 7000

(0, 500, 2000) =\> 2000

## Private Hidden Tests

(3, 1000, 0) =\> 3000

(1, 0, 250) =\> 250

## Private Reference Solution

def workshop_total(attendees, fee_per_person, room_cost):  
return attendees \* fee_per_person + room_cost

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

## Private Hidden Tests

('Mary Jane', -50) =\> 'Mary Jane has -50 naira left.'

## Private Reference Solution

def remaining_message(name, remaining):  
return f"{name} has {remaining} naira left."

# D3.1A — Implement a Component Contract

| **Linked lesson**         | Lesson 3.1        |
|---------------------------|-------------------|
| **Type**                  | Core              |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d3-1a/solution.py |

## Instructions (Markdown)

Implement participant_cost exactly as specified: attendees \* (food_per_person + transport_per_person). Return an integer.

## Default Code Template

def participant_cost(attendees, food_per_person, transport_per_person):  
pass

## Allowed Keywords / Constructs

def, return, +, \*, (, )

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(10, 800, 200) =\> 10000

(0, 0, 0) =\> 0

## Private Hidden Tests

(3, 700, 300) =\> 3000

(5, 100, 0) =\> 500

## Private Reference Solution

def participant_cost(attendees, food_per_person, transport_per_person):  
return attendees \* (food_per_person + transport_per_person)

# D3.1B — Implement the Status Contract

| **Linked lesson**         | Lesson 3.1        |
|---------------------------|-------------------|
| **Type**                  | Reinforcement     |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d3-1b/solution.py |

## Instructions (Markdown)

Complete budget_status(budget, total). Return "Within budget" when total \<= budget; otherwise return "Over budget".

## Default Code Template

def budget_status(budget, total):  
pass

## Allowed Keywords / Constructs

def, return, if, else, \<=

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(16000, 15000) =\> 'Within budget'

(15000, 15000) =\> 'Within budget'

## Private Hidden Tests

(14000, 15000) =\> 'Over budget'

(0, 0) =\> 'Within budget'

## Private Reference Solution

def budget_status(budget, total):  
if total \<= budget:  
return "Within budget"  
else:  
return "Over budget"

# D3.2A — Integrate Participant and Venue Costs

| **Linked lesson**         | Lesson 3.2        |
|---------------------------|-------------------|
| **Type**                  | Core              |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d3-2a/solution.py |

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

## Private Hidden Tests

(3, 700, 300, 2000) =\> 5000

(0, 0, 0, 0) =\> 0

## Inspection Checklist

- Does event_total call participant_cost rather than repeat the entire calculation?

## Private Reference Solution

def participant_cost(attendees, food_per_person, transport_per_person):  
return attendees \* (food_per_person + transport_per_person)  
  
def event_total(attendees, food_per_person, transport_per_person, venue_cost):  
people = participant_cost(attendees, food_per_person, transport_per_person)  
return people + venue_cost

# D3.2B — Build the Final Event Summary

| **Linked lesson**         | Lesson 3.2        |
|---------------------------|-------------------|
| **Type**                  | Reinforcement     |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d3-2b/solution.py |

## Instructions (Markdown)

Complete event_summary(event_name, total, status). Return exactly "Study Day: total 15000 naira. Within budget." with supplied values substituted.

## Default Code Template

def event_summary(event_name, total, status):  
pass

## Allowed Keywords / Constructs

def, return, f-string, string

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

('Study Day', 15000, 'Within budget') =\> 'Study Day: total 15000 naira. Within budget.'

('Tech Day', 17000, 'Over budget') =\> 'Tech Day: total 17000 naira. Over budget.'

## Private Hidden Tests

('A', 0, 'Within budget') =\> 'A: total 0 naira. Within budget.'

## Private Reference Solution

def event_summary(event_name, total, status):  
return f"{event_name}: total {total} naira. {status}."

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

## Private Hidden Tests

(3, 700, 300, 2000) =\> 5000

## Inspection Checklist

- Does the learner preserve and call participant_cost?

## Private Reference Solution

def participant_cost(attendees, food_per_person, transport_per_person):  
return attendees \* (food_per_person + transport_per_person)  
  
def venue_only_total(attendees, food_per_person, transport_per_person, venue_cost):  
people = participant_cost(attendees, food_per_person, transport_per_person)  
return people + venue_cost

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

## Private Hidden Tests

(3, 700, 300, 2000) =\> 5000

## Inspection Checklist

- Can the learner explain what was wrong and which test exposed it?

## Private Reference Solution

def participant_cost(attendees, food_per_person, transport_per_person):  
return attendees \* (food_per_person + transport_per_person)  
  
def event_total(attendees, food_per_person, transport_per_person, venue_cost):  
people = participant_cost(attendees, food_per_person, transport_per_person)  
return people + venue_cost

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

## Private Hidden Tests

(14000, 15000) =\> 'Over budget'

(0, 0) =\> 'Within budget'

## Inspection Checklist

- Can the learner identify the smallest necessary change?

## Private Reference Solution

def budget_status(budget, total):  
if total \<= budget:  
return "Within budget"  
else:  
return "Over budget"

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

## Private Hidden Tests

(3, 700, 300, 2000, 500) =\> 5500

(0, 0, 0, 0, 0) =\> 0

## Inspection Checklist

- Does the learner reuse participant_cost and preserve previous behaviour?

## Private Reference Solution

def participant_cost(attendees, food_per_person, transport_per_person):  
return attendees \* (food_per_person + transport_per_person)  
  
def event_total(attendees, food_per_person, transport_per_person, venue_cost, equipment_cost):  
people = participant_cost(attendees, food_per_person, transport_per_person)  
return people + venue_cost + equipment_cost

# D4.1B — Regression Check: Exact Fit

| **Linked lesson**         | Lesson 4.1        |
|---------------------------|-------------------|
| **Type**                  | Reinforcement     |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d4-1b/solution.py |

## Instructions (Markdown)

The brief says an exact budget match is "Within budget". Repair the function.

## Default Code Template

def budget_status(budget, total):  
if total \< budget:  
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

## Private Hidden Tests

(14000, 15000) =\> 'Over budget'

(0, 0) =\> 'Within budget'

## Private Reference Solution

def budget_status(budget, total):  
if total \<= budget:  
return "Within budget"  
else:  
return "Over budget"

# D4.2A — Find the First Wrong Operation

| **Linked lesson**         | Lesson 4.2        |
|---------------------------|-------------------|
| **Type**                  | Core              |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d4-2a/solution.py |

## Instructions (Markdown)

Repair the two arithmetic mistakes so print_balance returns the remaining budget.

## Default Code Template

def print_balance(budget, pages, price_per_page):  
cost = pages + price_per_page  
return budget + cost

## Allowed Keywords / Constructs

def, return, =, \*, -

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(1000, 4, 100) =\> 600

(500, 6, 100) =\> -100

## Private Hidden Tests

(800, 0, 50) =\> 800

(300, 4, 100) =\> -100

## Private Reference Solution

def print_balance(budget, pages, price_per_page):  
cost = pages \* price_per_page  
return budget - cost

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

## Private Hidden Tests

(25, 4, 0) =\> 100

(0, 5, 20) =\> 20

## Inspection Checklist

- Did the learner leave item_cost unchanged?

## Private Reference Solution

def item_cost(price, quantity):  
return price \* quantity  
  
def delivered_cost(price, quantity, delivery):  
subtotal = item_cost(price, quantity)  
return subtotal + delivery

# D4.3A — Explainable Repair

| **Linked lesson**         | Lesson 4.3        |
|---------------------------|-------------------|
| **Type**                  | Core              |
| **Coins**                 | 10                |
| **Language**              | Python            |
| **README location**       | README.md         |
| **Suggested graded file** | d4-3a/solution.py |

## Instructions (Markdown)

Repair seats_left. During inspection, be ready to explain the failing case, the change you made, and the retest you used.

## Default Code Template

def seats_left(capacity, booked):  
return capacity + booked

## Allowed Keywords / Constructs

def, return, -

## Restrictions / Forbidden Strings

input, print, import

## Visible Sample Tests

(10, 3) =\> 7

(10, 10) =\> 0

## Private Hidden Tests

(0, 0) =\> 0

(20, 8) =\> 12

## Inspection Checklist

- Can the learner state the failing case, the exact change, and a retest result?

## Private Reference Solution

def seats_left(capacity, booked):  
return capacity - booked

# AI Lesson Knowledge Checks — Authoring Guidance

AI awareness lessons should use MCQ/knowledge-check items rather than coding challenges. Keep the questions conceptual and directly tied to the lesson. They remain informational and outside the technical selection weighting. Suggested pattern: 2–3 questions after each AI lesson, plus the separate 10-question Day 5 AI Awareness Check.

- Day 1: distinguish AI from generative AI; recognise that fluent output can be wrong.

- Day 2: identify a clearer prompt; recognise sensitive information that should not be shared.

- Day 3: choose an appropriate AI-assistance use; identify missing context in a prompt; choose a verification step.

- Day 4: identify hallucination risk; choose a responsible verification action; recognise privacy/security concerns.
