## Lesson 2.4 — Testing Expected Results and Debugging Small Programs

| **Estimated time**   | 40–45 minutes                                                                           |
|----------------------|-----------------------------------------------------------------------------------------|
| **Learning purpose** | Learn a disciplined way to decide whether code is correct and repair it when it is not. |

### What you should be able to do

- Write an expected answer before running a test.

- Compare expected and actual results.

- Distinguish syntax failures from wrong-result failures.

- Change one likely cause at a time and rerun the failing case.

- Retest earlier passing cases after a fix.

### A test starts with an expectation

If you run code without deciding what should happen, the result can look convincing even when it is wrong. A basic test has an input, an expected result and an actual result. You calculate or reason about the expected result first, run the function, and compare the two.

A strong small test set contains different kinds of cases: a usual case, a zero case when zero is allowed, and a boundary case when a decision rule contains equality. Different cases reveal different mistakes.

### Debugging is a process, not guessing

When a test fails, avoid changing several lines at random. First identify the earliest place where the calculation or decision differs from what the problem requires. Make one focused change. Rerun the failing case. Then rerun earlier passing cases because a fix can accidentally break behaviour that already worked.

If the code does not run at all, read the error message and inspect syntax near the reported line: colons, parentheses, indentation and spelling are common beginner causes. If it runs but returns the wrong value, compare the operators and branch conditions with the written brief.

### Keep evidence of improvement

During the trial, the first attempt and the improved attempt are both useful evidence. A mistake is not automatically a negative signal. The important question is whether you can interpret feedback, make an appropriate change, explain why it works and retest it.

### Common mistakes to watch for

- Changing multiple lines at once and not knowing which change fixed the issue.

- Checking only the sample that already passed.

- Treating a failed test as a reason to rewrite everything.

### Peer learning checkpoint

Show a failing input and expected result to a peer, but not your intended fix. Ask the peer to point to the first line they would investigate and explain why.

### Optional resources if you want another explanation

**Visualise:** [<u>Python Tutor for step-by-step debugging</u>](https://pythontutor.com/)

### Linked drill(s) — use these to test what you just learned

**D2.4A — Repair Printing Cost**

The function is meant to return the remaining budget after a printing cost. Repair the arithmetic.

**Type:** Core

**D2.4B — Repair an Equality Bug**

The brief says an exact budget match is "Within budget". Repair the function.

**Type:** Reinforcement

**D2.4C — Retest After a Fix**

Repair seats_left so it subtracts booked from capacity. The platform will test normal, zero and exact-fit cases.

**Type:** Reinforcement
