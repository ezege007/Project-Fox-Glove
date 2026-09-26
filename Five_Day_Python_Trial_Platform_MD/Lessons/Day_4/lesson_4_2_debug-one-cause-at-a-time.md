## Lesson 4.2 — Debug One Cause at a Time

| **Estimated time**   | 35–40 minutes                                              |
|----------------------|------------------------------------------------------------|
| **Learning purpose** | Use a controlled debugging loop instead of random changes. |

### What you should be able to do

- Reproduce a failure consistently.

- Locate the earliest incorrect value or decision.

- Make one focused change and retest.

- Avoid modifying code that already passes its own tests.

### First reproduce the problem

A bug you cannot reproduce is difficult to reason about. Write down the failing input, expected result and actual result. Run it again. Once you can reproduce it, trace the calculation from the inputs until the first value differs from what you expected.

### Protect known-good components

If \`item_cost\` passes its tests but \`delivered_cost\` fails, do not rewrite \`item_cost\` simply because both functions are in the same file. Start at the boundary where known-good output enters the failing function. This reduces the number of possible causes and prevents new bugs.

### Change one thing

Random debugging often creates a moving target: several lines change, one test begins to pass, and nobody knows why. Make the smallest change that addresses the evidence, rerun the failing case, then rerun related passing cases.

### Common mistakes to watch for

- Editing a helper that already passes.

- Making several speculative changes at once.

- Ignoring the actual failing input and debugging a different example.

### Peer learning checkpoint

One learner describes a failing case without giving the fix. Another learner identifies the first variable or decision they would inspect.

### Optional resources if you want another explanation

**Visualise:** [<u>Python Tutor</u>](https://pythontutor.com/)

### Linked drill(s) — use these to test what you just learned

**D4.2A — Find the First Wrong Operation**

Repair the two arithmetic mistakes so print_balance returns the remaining budget.

**Type:** Core

**D4.2B — Repair Without Breaking a Passing Helper**

item_cost is correct. Fix only delivered_cost so it returns the correct total. Do not change item_cost.

**Type:** Reinforcement
