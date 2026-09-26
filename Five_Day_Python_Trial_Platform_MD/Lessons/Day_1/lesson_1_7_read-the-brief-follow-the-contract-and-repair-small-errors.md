## Lesson 1.7 — Read the Brief, Follow the Contract and Repair Small Errors

| **Estimated time**   | 30–35 minutes                                                                      |
|----------------------|------------------------------------------------------------------------------------|
| **Learning purpose** | Learn to treat requirements as part of the programming problem, not as decoration. |

### What you should be able to do

- Extract function name, inputs, output type and exact wording from a brief.

- Distinguish syntax errors from logic errors at a beginner level.

- Make the smallest change needed to satisfy a stated requirement.

- Check your answer against both the examples and the wording of the brief.

### The brief is part of the test

A coding task is not only “write something that works.” It defines a contract. The contract may specify the function name, parameters, required return type, exact output text, assumptions about the inputs and restrictions such as “do not print.” If you solve a different problem from the one described, technically valid Python can still be the wrong answer.

Before coding, underline four things: the function name, the inputs, what must be returned, and any exact wording or boundary rule. Then rewrite the requirement in your own words. This two-minute habit prevents many avoidable mistakes.

### Syntax error vs logic error

A syntax error prevents Python from understanding or running the code, for example a missing colon after \`def\` or inconsistent indentation. A logic error is different: the code runs but produces the wrong answer. \`cost = pages + price_per_page\` is valid Python, but it is the wrong logic if total printing cost should be pages multiplied by price per page.

When you debug, first ask whether the program can run. If not, read the error location and inspect syntax. If it runs but fails a test, compare the expected calculation with the operations in your code.

### Do not add unrelated features

In a short trial exercise, extra menus, input validation, files or clever shortcuts can make a simple solution harder to understand and harder to grade. Solve the stated problem directly. Advanced features earn no benefit when the task does not ask for them.

### Common mistakes to watch for

- Renaming the supplied function.

- Adding \`input()\` prompts to a function-return drill.

- Solving only the visible sample instead of the general rule.

- Changing several things at once when debugging.

### Peer learning checkpoint

Exchange briefs with a peer. Without writing code, each person should state the function name, parameters, return type and one important restriction.

### Optional resources if you want another explanation

**Visualise:** [<u>Python Tutor for tracing logic</u>](https://pythontutor.com/)

### Linked drill(s) — use these to test what you just learned

**D1.7A — Follow the Brief Exactly**

Complete learner_status(name, tasks) to return exactly "Ada completed 4 tasks." Use the supplied values and keep the word tasks even when the value is 1.

**Type:** Core

**D1.7B — Repair a Small Logic Error**

The function is meant to return the remaining budget after a printing cost. Repair the arithmetic.

**Type:** Reinforcement
