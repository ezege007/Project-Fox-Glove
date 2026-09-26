## Lesson 1.6 — Return vs Print, Function Calls and Tracing Values

| **Estimated time**   | 35–40 minutes                                                              |
|----------------------|----------------------------------------------------------------------------|
| **Learning purpose** | Understand how one function can return a value that another function uses. |

### What you should be able to do

- Explain the difference between returning a value and displaying a value.

- Call a supplied helper function from another function.

- Store a returned value in a variable and continue a calculation.

- Trace a value across two connected functions.

### Return and print solve different problems

\`print()\` displays text in the output area. \`return\` sends a value back to the code that called the function. The trial platform normally calls your function itself and checks the returned value. That is why adding \`input()\` prompts or relying on \`print()\` usually breaks the expected contract.

Imagine a cashier who calculates a subtotal. Printing the subtotal is like shouting the number across the room. Returning it is like handing the number to the next person who still needs to add delivery. Both can make the value visible in some sense, but only the returned value is directly available for the next calculation.

### Functions can reuse other functions

When \`delivered_cost\` calls \`item_cost\`, the helper performs one small job and returns its answer. The caller stores that answer in \`subtotal\`, then adds delivery. This is reuse: instead of rewriting the same multiplication everywhere, one named function owns that calculation.

def item_cost(price, quantity):  
return price \* quantity  
  
def delivered_cost(price, quantity, delivery):  
subtotal = item_cost(price, quantity)  
return subtotal + delivery

### Trace the flow

For \`delivered_cost(200, 3, 100)\`, first call \`item_cost(200, 3)\`. It returns 600. Then \`subtotal\` becomes 600. Finally the caller returns 600 + 100, which is 700. If you can trace this sequence on paper, you understand the core pattern used later in the team mission.

### Common mistakes to watch for

- Using \`print()\` where the platform expects \`return\`.

- Calling a helper but ignoring the value it returns.

- Repeating the helper calculation instead of using the helper when the brief requires a call.

### Peer learning checkpoint

One person should play the helper function and the other the calling function. Pass the input values and returned value verbally to make the flow concrete.

### Optional resources if you want another explanation

**Watch:** [<u>Python Functions for Beginners (Corey Schafer)</u>](https://www.youtube.com/watch?v=9Os0o3wzS_I)

**Visualise:** [<u>Python Tutor: watch function frames appear step-by-step</u>](https://pythontutor.com/)

### Linked drill(s) — use these to test what you just learned

**D1.6A — Use a Supplied Helper**

item_cost is supplied and correct. Complete delivered_cost so it calls item_cost(price, quantity), then adds delivery to the returned subtotal.

**Type:** Core

**D1.6B — Return, Do Not Display**

Repair combined_cost so that it returns the sum instead of printing it. It must produce no printed output.

**Type:** Reinforcement

**D1.6C — Trace a Returned Value**

Complete final_total so it calls subtotal, stores the returned answer, and adds service_fee.

**Type:** Reinforcement
