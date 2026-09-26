## Lesson 1.4 — Variables, Values and Arithmetic

| **Estimated time**   | 35–40 minutes                                                               |
|----------------------|-----------------------------------------------------------------------------|
| **Learning purpose** | Use named values and arithmetic operators to represent simple calculations. |

### What you should be able to do

- Explain what a variable represents in the small programs used here.

- Use +, -, and \* correctly with integer inputs.

- Break a calculation into readable intermediate steps.

- Check an arithmetic expression against a hand-calculated expected result.

### Names make calculations readable

A variable is a name that refers to a value while the program is running. In \`total = fare \* trips\`, the name \`total\` refers to the result of multiplying \`fare\` by \`trips\`. A useful variable name helps another person understand what the value means. Compare \`x = a \* b\` with \`total = fare \* trips\`; both may work, but the second communicates the purpose more clearly.

Variables are not permanent boxes stored forever. In these beginner functions, they are temporary names used while one function call is executing. When the function is called again with different values, the calculations are performed again with those new values.

### Arithmetic operators

Use \`+\` to add, \`-\` to subtract and \`\*\` to multiply. Parentheses can make the intended order explicit. For example, an event with 10 attendees, food at ₦800 per person and transport at ₦200 per person has a participant cost of \`10 \* (800 + 200)\`, which is ₦10,000.

When several operations appear in one expression, do not rely only on intuition. Work out the expected result by hand and, where helpful, split the calculation into named steps. Readable code is easier to test and easier to explain.

### Use the inputs — never the sample answer

If a drill shows \`travel_cost(200, 3) =\> 600\`, returning the number 600 directly is not a solution. The function must use \`fare\` and \`trips\` so it also works when the grader supplies different values. Hidden tests exist specifically to check that your logic generalises beyond the example.

### Worked example

def travel_cost(fare, trips):  
total = fare \* trips  
return total  
  
def budget_left(budget, food, transport):  
remaining = budget - food - transport  
return remaining

For travel_cost(200, 3), total becomes 600. For budget_left(2000, 900, 600), remaining becomes 500. Change the inputs and recalculate before running.

### Common mistakes to watch for

- Using \`+\` when the brief requires multiplication.

- Changing sample numbers inside the function instead of using parameters.

- Ignoring zero values even though zero is a valid input.

### Peer learning checkpoint

Choose one arithmetic function and ask a peer to predict the output for a new set of values. Compare the prediction with the actual result and explain any difference.

### Optional resources if you want another explanation

**Read:** [<u>Python tutorial: numbers and basic expressions (optional reference)</u>](https://docs.python.org/3/tutorial/introduction.html)

**Visualise:** [<u>Python Tutor</u>](https://pythontutor.com/)

### Linked drill(s) — use these to test what you just learned

**D1.4A — Travel Cost**

Complete travel_cost(fare, trips). Return fare multiplied by trips.

**Type:** Core

**D1.4B — Budget After Two Costs**

Complete budget_left(budget, food, transport). Return budget minus food minus transport.

**Type:** Core

**D1.4C — Participant Cost**

Complete participant_cost(attendees, food_per_person, transport_per_person). Return attendees multiplied by the sum of the two per-person costs.

**Type:** Reinforcement
