## Lesson 1.5 — Strings, f-Strings and Exact Returned Messages

| **Estimated time**   | 30–35 minutes                                                           |
|----------------------|-------------------------------------------------------------------------|
| **Learning purpose** | Learn to construct text responses that match a required format exactly. |

### What you should be able to do

- Distinguish text strings from integer values.

- Use an f-string to insert supplied values into text.

- Preserve required spaces, punctuation and wording.

- Return text instead of printing it when the platform expects a returned value.

### Text is data too

Python represents text as strings. A string is written inside quotation marks, such as \`"Welcome Ada."\`. The integer \`500\` and the string \`"500"\` are not the same type of value: one is a number used for arithmetic, while the other is text. A platform test may care about both the value and its type.

### Insert values with f-strings

An f-string begins with \`f\` before the opening quote. Names inside braces are replaced by their current values. For example, \`f"Welcome {name}."\` can produce \`Welcome Ada.\` or \`Welcome Tobi.\` depending on the argument supplied to the function.

Exact-output drills are deliberately strict. If the expected result is \`Ada has 500 naira remaining.\`, then missing the full stop, adding an extra space, changing the word order, or printing instead of returning can fail the check even though the sentence looks similar to a person.

### Separate calculation from presentation

It is often useful for one function to calculate a number and another function to turn that number into a readable message. That separation will become important in the Day 2 mission and the team project.

### Worked example

def welcome(name, days):  
return f"Welcome {name}. Trial length: {days} days."  
  
def budget_message(name, remaining):  
return f"{name} has {remaining} naira remaining."

Predict the exact string returned for welcome("Ada", 5). Then change both inputs and check every character in your prediction.

### Common mistakes to watch for

- Forgetting the \`f\` before an f-string.

- Returning a number when a string is required, or a string when a number is required.

- Changing required punctuation or spacing.

### Peer learning checkpoint

Read an expected output aloud to a peer. Ask them to compare your returned string character-by-character with the requirement.

### Optional resources if you want another explanation

**Watch:** [<u>F-Strings quick tutorial (Corey Schafer)</u>](https://www.youtube.com/watch?v=nghuHvKLhJA)

### Linked drill(s) — use these to test what you just learned

**D1.5A — Welcome Message**

Return exactly "Welcome Ada." with the supplied name substituted. Preserve spaces and the final full stop.

**Type:** Core

**D1.5B — Budget Message**

Return exactly "Ada has 500 naira remaining." using the supplied name and remaining value.

**Type:** Reinforcement
