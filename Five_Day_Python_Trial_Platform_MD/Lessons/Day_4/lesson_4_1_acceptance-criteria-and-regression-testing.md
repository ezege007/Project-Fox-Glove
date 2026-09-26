## Lesson 4.1 — Acceptance Criteria and Regression Testing

| **Estimated time**   | 35–40 minutes                                                    |
|----------------------|------------------------------------------------------------------|
| **Learning purpose** | Learn how to protect working behaviour while changing a program. |

### What you should be able to do

- Explain the difference between a requirement and a test case.

- Use published acceptance cases as evidence that the combined program meets the brief.

- Retest earlier passing behaviour after making a change.

- Recognise regression as a previously working behaviour that becomes broken.

### Acceptance criteria describe success

An acceptance criterion states behaviour the finished program must satisfy. A test case turns that behaviour into concrete inputs and an expected result. For example, “an exact budget match is within budget” becomes the test \`budget_status(15000, 15000) =\> "Within budget"\`.

Team projects need acceptance tests because individual components can each look correct while the full workflow still fails. Run the agreed cases on the integrated program, not only on isolated functions.

### Regression testing protects earlier work

When you change working code, rerun tests that previously passed. Suppose the team adds equipment_cost to the event total. You should test the new equipment behaviour and also repeat zero-attendee, exact-budget and summary cases. If an older case now fails, the change caused a regression.

### Record evidence, not only conclusions

Instead of writing “all tests passed,” record the input, expected result and actual result for the important cases. This gives the mentor something concrete to inspect and makes later debugging easier.

### Common mistakes to watch for

- Testing only the new change and forgetting earlier behaviour.

- Treating one happy-path test as complete acceptance evidence.

- Changing expected results to match incorrect code.

### Peer learning checkpoint

Each team member should choose one acceptance criterion and explain which concrete test proves it.

### Linked drill(s) — use these to test what you just learned

**D4.1A — Preserve Earlier Behaviour**

Add equipment_cost to event_total while preserving participant and venue calculations. Use the supplied helper.

**Type:** Core

**D4.1B — Regression Check: Exact Fit**

The brief says an exact budget match is "Within budget". Repair the function.

**Type:** Reinforcement
