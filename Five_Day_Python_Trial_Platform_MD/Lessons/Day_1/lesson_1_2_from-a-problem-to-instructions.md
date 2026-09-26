## Lesson 1.2 — From a Problem to Instructions

| **Estimated time**   | 30–35 minutes                                              |
|----------------------|------------------------------------------------------------|
| **Learning purpose** | Learn to understand a small problem before writing Python. |

### What you should be able to do

- Identify input, processing and output in a small problem.

- Rewrite a short problem as ordered solution steps.

- Predict a simple numeric answer before coding.

- Recognise that code is an executable form of a solution plan.

### Start with the problem, not the syntax

Programming begins before Python. A computer follows instructions exactly, so the first job of a programmer is to decide what information is available, what should happen to that information, and what result should be produced. A useful beginner model is input → processing → output.

Imagine that you buy one item for ₦200 and another for ₦300. The inputs are 200 and 300. The processing is addition. The output is 500. Nothing about that reasoning depends on Python. Python is simply the language we will use to express the reasoning in a form the computer can execute.

### Turn the problem into an algorithm

An algorithm is a sequence of steps for solving a problem. For the two-item example, a plain-language algorithm could be: receive the first cost; receive the second cost; add the two costs; return the total. Writing the steps first helps prevent a common beginner mistake: typing code before deciding what the code is supposed to do.

Now consider a daily budget of ₦2,000 with ₦900 spent on food and ₦600 on transport. The inputs are budget, food and transport. The processing is \`budget - food - transport\`. The output is ₦500. If your expected answer is clear before you run code, you have something to compare the program against.

### Think before you run

For each problem, write an expected result first. This builds the habit of reasoning independently rather than trusting whatever the computer displays. Computers execute the instructions we give them; if the instructions are wrong, a program can run successfully and still return the wrong answer.

### Mini activity

You have ₦3,000. Lunch costs ₦1,200 and transport costs ₦700. Write the three inputs, the processing step and the expected output. Compare your answer with a peer before writing any Python.

### Common mistakes to watch for

- Starting to type code before deciding what the output should be.

- Hard-coding the sample answer instead of using the supplied inputs.

- Treating a successful run as proof that the logic is correct.

### Peer learning checkpoint

Take one everyday calculation and explain its input, processing and output to a peer. Your peer should be able to repeat the steps without seeing your notes.

### Optional resources if you want another explanation

**Watch:** [<u>Python in 100 Seconds (high-level orientation)</u>](https://www.youtube.com/watch?v=x7X9w_GIm1s)

### Linked drill(s) — use these to test what you just learned

**D1.2A — Add Two Item Costs**

Complete item_total(first, second). Return the total cost of the two supplied non-negative integer amounts. Do not hard-code the sample answer.

**Type:** Core

**D1.2B — Calculate Remaining Money**

Complete remaining_money(budget, spent). Return budget minus spent. A negative answer is allowed.

**Type:** Reinforcement
