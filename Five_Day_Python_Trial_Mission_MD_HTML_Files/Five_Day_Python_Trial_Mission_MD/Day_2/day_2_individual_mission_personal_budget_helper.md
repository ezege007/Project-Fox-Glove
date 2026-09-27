# Day 2 Individual Mission — Personal Budget Helper

> **Individual Mission · 25% of the final selection score**

You have spent the first part of the trial learning how to read a brief, work with variables and arithmetic, return values from functions, build exact messages, make simple decisions, test your code, and improve a first attempt after feedback.

This mission brings those habits together in one small program.

You are not expected to invent a large application. The goal is to show that you can **understand a clear brief, build two small functions, test them carefully, respond to feedback, and explain what you changed**.

---

## Mission Goal

Build a small **Personal Budget Helper** with two functions:

```python
def budget_remaining(budget, food, transport):
    pass

def budget_message(name, remaining):
    pass
```

Your program should calculate how much money remains after food and transport expenses, then produce a clear message using the supplied name and remaining amount.

---

## What You Are Building

### Function 1 — `budget_remaining`

This function receives:

- `budget`
- `food`
- `transport`

It must return:

```text
budget - food - transport
```

Negative remaining values are allowed.

### Function 2 — `budget_message`

This function receives:

- `name`
- `remaining`

It must return a message in this exact pattern:

```text
Ada has 500 naira remaining.
```

The values must come from the function arguments. Do not hard-code the example name or amount.

---

## Acceptance Criteria

Your mission is complete when all of the following are true:

- `budget_remaining` returns `budget - food - transport`.
- A zero expense is handled correctly.
- An overspend can produce a negative remaining amount.
- `budget_message` uses the supplied `name`.
- `budget_message` uses the supplied `remaining` value.
- The returned message matches the required wording and punctuation exactly.
- Neither function asks the user for input.
- Neither function prints unrelated output.
- You preserve evidence of your first complete attempt before making feedback-based changes.
- You retest after making a change.

---

## Recommended Working Process

### Step 1 — Understand the Brief Before Coding

Before writing Python, write down:

**Inputs**
- What information does each function receive?

**Processing**
- What calculation or formatting must happen?

**Output**
- What exactly must each function return?

Do this in your own words first.

---

### Step 2 — Predict the Results

Before running any code, predict the answers for the following cases.

#### `budget_remaining`

| Budget | Food | Transport | Expected result |
| ---: | ---: | ---: | ---: |
| 2000 | 900 | 600 | 500 |
| 1500 | 0 | 0 | 1500 |
| 1000 | 800 | 500 | -300 |

Your prediction should come before your code test.

---

### Step 3 — Implement `budget_remaining`

Start with:

```python
def budget_remaining(budget, food, transport):
    pass
```

Replace `pass` with your implementation.

Do not hard-code any of the sample answers. The function should work for other valid whole-number naira amounts as well.

---

### Step 4 — Test `budget_remaining`

Run at least these three categories:

1. **Normal case** — money remains.
2. **Zero case** — one or more expenses may be zero.
3. **Overspend case** — the result becomes negative.

Record:

- input;
- expected result;
- actual result;
- pass/fail.

A test is useful because it gives you evidence. Do not stop at “the code ran.”

---

### Step 5 — Implement `budget_message`

Start with:

```python
def budget_message(name, remaining):
    pass
```

The function should return a string in this exact pattern:

```text
Ada has 500 naira remaining.
```

The name and amount must come from the supplied arguments.

Examples:

```text
budget_message("Ada", 500)
=> "Ada has 500 naira remaining."

budget_message("Tobi", -300)
=> "Tobi has -300 naira remaining."
```

Pay attention to:

- spaces;
- spelling;
- punctuation;
- the final full stop;
- using the arguments rather than fixed values.

---

## Test Your Full Mission

Use a small set of tests such as:

```python
remaining = budget_remaining(2000, 900, 600)
print(remaining)

message = budget_message("Ada", remaining)
print(message)
```

Your functions themselves should **return** values. You may use `print()` outside the functions while testing, but do not replace the required `return` statements with printing.

---

## Save Your First Complete Attempt

Once both functions work well enough to form a complete first attempt:

1. Save your files.
2. Make sure your code runs.
3. Preserve this version before receiving feedback.
4. Commit it to your assigned Gitea repository.

A useful commit message could be:

```text
Complete first Personal Budget Helper attempt
```

The first attempt matters because the trial also looks at how you improve your work.

---

## Feedback Round

Receive **one specific review point or hint** from a peer or coding mentor.

Good feedback is specific.

Examples:

- “Your overspend case is returning the wrong value.”
- “Your message is missing the final full stop.”
- “Your function prints the answer instead of returning it.”

Avoid feedback such as:

- “This is wrong.”
- “Rewrite everything.”
- “Use my code.”

The goal is to help you reason about your own work.

---

## Improve One Thing at a Time

After receiving feedback:

1. Identify the exact problem.
2. Change only what is needed.
3. Rerun the failing case.
4. Rerun at least one earlier passing case.
5. Record what changed and why.

Then save and commit your improved version.

A useful commit message could be:

```text
Fix budget message after feedback
```

---

## Evidence You Must Submit

Submit the following:

### 1. Final code

Your final versions of:

```python
budget_remaining(budget, food, transport)
budget_message(name, remaining)
```

### 2. Test evidence

Show at least:

- one normal case;
- one zero case;
- one overspend case;
- one message-format case.

### 3. First attempt evidence

Keep the version that existed before feedback.

### 4. Feedback received

Write the specific hint or review point you received.

### 5. Improved attempt

Show the change you made after feedback.

### 6. Short reflection

Answer these questions in 2–4 sentences each:

1. What part of the mission was easiest for you?
2. What test exposed a mistake or gave you confidence that your code was correct?
3. What feedback did you receive?
4. What exactly did you change after the feedback?
5. If you had ten more minutes, what would you check again?

---

## Before You Submit

Use this checklist:

- [ ] I used the required function names.
- [ ] I kept the required parameters.
- [ ] I used the supplied values instead of hard-coding the examples.
- [ ] My functions return values.
- [ ] I tested a normal case.
- [ ] I tested a zero case.
- [ ] I tested an overspend case.
- [ ] My message matches the required format.
- [ ] I preserved my first complete attempt.
- [ ] I recorded the feedback I received.
- [ ] I retested after making my improvement.
- [ ] I can explain my own code.

---

## Mission Reminder

A perfect first attempt is not the only goal.

This mission is also looking for evidence that you can:

**understand → build → test → receive feedback → improve → explain**

Work carefully, keep your evidence, and make sure the final code is still your own.
