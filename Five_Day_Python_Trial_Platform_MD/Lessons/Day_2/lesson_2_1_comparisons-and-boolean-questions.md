## Lesson 2.1 — Comparisons and Boolean Questions

| **Estimated time**   | 30–35 minutes                                        |
|----------------------|------------------------------------------------------|
| **Learning purpose** | Teach programs to ask yes/no questions about values. |

### What you should be able to do

- Explain what True and False represent.

- Use ==, \>, \<, \>= and \<= in simple comparisons.

- Distinguish assignment \`=\` from equality comparison \`==\`.

- Predict the result of a comparison before running code.

### Programs often need questions, not only calculations

Yesterday most functions followed one straight path: receive values, calculate something and return an answer. Many useful programs also need to ask questions. Is the budget enough? Is the total exactly equal to the expected value? Has capacity been reached? A comparison answers a question with one of two Boolean values: \`True\` or \`False\`.

\`budget \>= cost\` asks whether budget is greater than or equal to cost. \`actual == expected\` asks whether two values are equal. The double equals sign is important: a single \`=\` assigns a value to a name, while \`==\` compares two values.

### Boundary values matter

Words such as “at least”, “at most”, “greater than”, “less than” and “exactly” translate into different comparisons. “At least 18” includes 18, so \`age \>= 18\` is appropriate. “More than 18” does not include 18, so \`age \> 18\` is different. Small wording differences create real logic differences.

### Predict first

For each comparison, choose a value just below the boundary, exactly on the boundary, and just above it. If the rule is “budget is enough when budget \>= cost”, test 699, 700 and 701 against a cost of 700. This pattern helps reveal off-by-one and equality mistakes early.

### Worked example

def can_afford(budget, cost):  
return budget \>= cost  
  
def matches_expected(actual, expected):  
return actual == expected

can_afford(700, 700) returns True because equality is included. can_afford(699, 700) returns False.

### Common mistakes to watch for

- Using \`=\` instead of \`==\` for equality.

- Using \`\>\` when the words say “greater than or equal to”.

- Testing only values far away from the boundary.

### Peer learning checkpoint

Create one English rule containing “at least” or “at most.” Ask a peer to choose the correct comparison operator and explain why equality is or is not included.

### Optional resources if you want another explanation

**Watch:** [<u>Conditionals and Booleans (Corey Schafer)</u>](https://www.youtube.com/watch?v=DZwmZ8Usvnk)

**Read:** [<u>Python control flow reference (optional)</u>](https://docs.python.org/3/tutorial/controlflow.html)

### Linked drill(s) — use these to test what you just learned

**D2.1A — Can the Budget Cover the Cost?**

Return True when budget is greater than or equal to cost; otherwise return False.

**Type:** Core

**D2.1B — Compare Two Totals**

Return True when actual is exactly equal to expected; otherwise return False.

**Type:** Reinforcement
