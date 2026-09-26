## Lesson 2.2 — Make Decisions with if/else and Test the Boundary

| **Estimated time**   | 35–40 minutes                                    |
|----------------------|--------------------------------------------------|
| **Learning purpose** | Use a comparison to choose between two outcomes. |

### What you should be able to do

- Write a two-branch if/else function.

- Explain that only one branch runs in this pattern.

- Handle equality according to the brief.

- Return the required value from each branch.

### From a question to a decision

A comparison produces \`True\` or \`False\`. An \`if/else\` statement uses that result to decide which block of code should run. If the condition is true, Python executes the indented \`if\` block. Otherwise it executes the \`else\` block. For a simple two-outcome problem, exactly one of these branches runs.

def funding_status(budget, cost):  
if budget \>= cost:  
return "Enough"  
else:  
return "Not enough"

### Read the rule before choosing the operator

The important part is not memorising \`if\`. The important part is translating the requirement correctly. If the brief says an exact match is enough, then equality must be included. If you accidentally use \`budget \> cost\`, a budget of 700 and cost of 700 will go to the wrong branch.

Indentation again shows structure. Both return statements are indented under the branch they belong to. The colon after the \`if\` condition and after \`else\` is required syntax.

### Test three categories

Whenever a rule has a boundary, test below, equal and above. For funding_status with a cost of 700, try budgets of 699, 700 and 701. For a capacity rule where booked must be at most capacity, test one below capacity, exactly capacity and one above capacity.

### Common mistakes to watch for

- Forgetting the colon after \`if\` or \`else\`.

- Using the wrong comparison at the equality boundary.

- Returning the right words from the wrong branch.

### Peer learning checkpoint

Before running any code, take one drill sample and explain which branch should run and why. Your peer should challenge the equality case.

### Optional resources if you want another explanation

**Watch:** [<u>Conditionals and Booleans (Corey Schafer)</u>](https://www.youtube.com/watch?v=DZwmZ8Usvnk)

### Linked drill(s) — use these to test what you just learned

**D2.2A — Funding Status**

Return "Enough" when budget is greater than or equal to cost. Otherwise return "Not enough". Exact equality counts as enough.

**Type:** Core

**D2.2B — Capacity Status**

Return "Fits" when booked is at most capacity; otherwise return "Too many".

**Type:** Reinforcement

**D2.2C — Positive Places**

Return "Available" when places is greater than zero; otherwise return "Full".

**Type:** Reinforcement
