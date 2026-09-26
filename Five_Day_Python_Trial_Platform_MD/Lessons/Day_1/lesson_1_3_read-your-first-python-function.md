## Lesson 1.3 — Read Your First Python Function

| **Estimated time**   | 35–40 minutes                                                                  |
|----------------------|--------------------------------------------------------------------------------|
| **Learning purpose** | Build a mental model for the small function pattern used throughout the trial. |

### What you should be able to do

- Identify a function name, parameters, body and return statement.

- Explain what indentation means in a Python function.

- Trace supplied arguments into parameters.

- Predict the returned value of a small function.

### Read code as a story

You do not need to memorise every symbol before you can read code. Start by asking what task the function represents, what values enter it, what happens to those values, and what answer leaves it. Consider the function below.

def item_total(first, second):  
total = first + second  
return total  
  
item_total(200, 300)

### What each part means

\`def\` begins a function definition. \`item_total\` is the function name. \`first\` and \`second\` are parameters: names that will receive values when the function is called. The colon marks the start of the indented function body. \`total = first + second\` performs the calculation and assigns the result to the name \`total\`. \`return total\` sends that value back to the caller.

The call \`item_total(200, 300)\` supplies the arguments 200 and 300. During that call, \`first\` refers to 200 and \`second\` refers to 300. The function calculates 500 and returns 500. If you change the second argument to 450, the returned result should become 650.

### Indentation is structure, not decoration

Python uses indentation to show which lines belong together. The calculation and return lines are indented because they belong to the function body. If indentation is missing or inconsistent, Python may reject the code or interpret its structure differently from what you intended.

### Trace it by hand

Before running a function, write the parameter values beside the names. Then calculate each assignment in order. Finally, identify the value returned. This habit becomes especially useful when one function calls another later in the trial.

### Common mistakes to watch for

- Confusing parameters in the definition with arguments in the call.

- Forgetting that the indented lines belong to the function.

- Assuming \`return\` and \`print\` mean the same thing.

### Peer learning checkpoint

Explain the function to a peer line by line without saying “it just does it.” Your explanation should say where 200 and 300 go and which value comes back.

### Optional resources if you want another explanation

**Watch:** [<u>Python Functions for Beginners (Corey Schafer)</u>](https://www.youtube.com/watch?v=9Os0o3wzS_I)

**Visualise:** [<u>Python Tutor: step through code execution</u>](https://pythontutor.com/)

### Linked drill(s) — use these to test what you just learned

**D1.3A — Complete Your First Function**

Complete add_costs(first, second) so that it returns the sum of the supplied values. Keep the function name and parameters unchanged.

**Type:** Core

**D1.3B — Repair the Missing Return**

The function calculates the correct value but does not return it. Repair the function so the caller receives the integer result and the function prints nothing.

**Type:** Reinforcement
