Rich self-learning edition with lesson-aligned drills and AI awareness

**Self-learning • peer-supported • beginner-friendly • AI-aware**

# Purpose of This Edition

This edition is written for the learner, not for a lecturer. Every lesson must teach the concept inside the lesson itself. A learner should be able to read the explanation, follow the worked example, try a small activity, discuss a specific question with a peer, and then complete one or more drills that test the exact knowledge taught in that lesson.

The design principle is simple: lesson first, drill second. The lesson explains; the drill tests. Drills are short and focused. Some lessons need one drill, while broader lessons use two or three so that different parts of the lesson are checked separately. The Git lesson is intentionally not graded with a coding drill because its purpose is orientation to version control and saving work.

| **Trial goal**        | Measure how candidates think, learn, build, test, collaborate and improve over five intensive days.                                              |
|-----------------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| **Python scope**      | Problem decomposition, functions, variables, arithmetic, strings, returned values, comparisons, if/else, helper calls, testing and debugging.    |
| **AI scope**          | Awareness only: what AI is, generative AI, prompting, coding assistance, context, hallucinations and verification.                               |
| **Assessment**        | Day 2: supervised 10-question baseline. Day 5: supervised 15-question final checkpoint. AI awareness is checked separately and is informational. |
| **Selection weights** | Individual mission 25%; checkpoints 30%; learning & improvement 20%; individual collaboration 15%; shared team result 10%.                       |

# How a learner should use every lesson

1.  Read the lesson from beginning to end before opening the drill.

2.  Pause at worked examples and predict what should happen before running code.

3.  Use the peer checkpoint to explain your understanding aloud. A peer may question your reasoning but should not type your solution for you.

4.  Complete the linked core drill(s). Use reinforcement drills when provided to strengthen the same skill.

5.  If a drill fails, read the failure, return to the relevant part of the lesson, change one thing, and retry.

6.  Use optional resources only when another explanation would help. The lesson itself contains the knowledge required for its drills.

# Five-Day Learning Map

| **Day** | **Learn**                                                                                                                  | **Build / practise**                                             | **Evidence**                                                            |
|---------|----------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------|-------------------------------------------------------------------------|
| 1       | Git basics; problem solving; first Python functions; variables; arithmetic; strings; calls; reading briefs; AI foundations | Lesson-linked drills after each coding lesson                    | Completed lessons/drills, working code, explanations; no scored mission |
| 2       | Baseline checkpoint; comparisons; if/else; function contracts; testing; debugging; planning; generative AI                 | 10-question baseline, drills, guided Personal Budget Helper      | Baseline + individual mission + feedback/retest evidence                |
| 3       | Decomposition; component ownership; integration; component tests; peer review; AI coding assistance/context                | Drills + team Event Budget Helper launch                         | Attributable component, tests, review, collaboration evidence           |
| 4       | Regression testing; systematic debugging; evidence-based explanation; responsible AI                                       | Drills + team integration + cross-team tests + mentor inspection | Shared team result + individual collaboration + improvement evidence    |
| 5       | No new Python content                                                                                                      | 15-question final checkpoint + AI awareness MCQ + reflection     | Final independent result and progression evidence                       |

# Day 1 — Foundations, Git and First Working Code

| **Day outcome**  | Understand how code represents instructions; read and modify small Python functions; save work using Git concepts. |
|------------------|--------------------------------------------------------------------------------------------------------------------|
| **Day emphasis** | Teaching-heavy day. Every coding lesson is followed by drills. Git is orientation only and has no coding drill.    |

## Lesson 1.1 — Git, Repositories and Saving Your Work

| **Estimated time**   | 25–30 minutes                                                                 |
|----------------------|-------------------------------------------------------------------------------|
| **Learning purpose** | Understand the basic version-control ideas you will use throughout the trial. |

### What you should be able to do

- Explain in simple language what Git, a repository and a commit are.

- Recognise the difference between Git and Gitea.

- Understand the basic save cycle: edit → check → stage → commit → push.

- Know why meaningful commit messages make project history easier to understand.

### Why software engineers use version control

When you write code, your project changes constantly. You add a function, repair a bug, rename something, or try an idea that later turns out to be wrong. If the only copy of your project is the latest folder on your computer, it can be difficult to remember what changed or return to an earlier working version. Git is a version-control system: it records the history of changes to a project so that you can see what changed and save useful snapshots as you work.

A repository, often shortened to repo, is the project together with its tracked history. You can think of the project folder as the work itself and Git as the history that remembers important versions of that work. Gitea is the Git hosting and collaboration platform used during this trial. It hosts Git repositories so your work can be stored remotely, reviewed and shared with the people who have access. Git and Gitea are related, but they are not the same thing: Git tracks the history of your code, while Gitea provides the server and web interface where the repository is hosted.

### The basic Git workflow

A beginner does not need every Git command on Day 1. You only need a mental model of a few actions. First, you edit files. Second, you check what Git sees as changed. Third, you choose the changes you want in the next snapshot. Fourth, you create the snapshot with a short message. Finally, when a remote repository is being used, you send your commits to it.

git status  
git add solution.py  
git commit -m "Complete travel cost drill"  
git push

\`git status\` tells you what has changed. \`git add\` stages a file for the next commit. \`git commit\` creates a snapshot in the repository history. \`git push\` sends your local commits to the remote repository hosted on Gitea. During the trial, use the Gitea repository assigned to you and follow the repository workflow provided by the platform. Do not create extra branches or change repository configuration unless instructed.

### What makes a useful commit

A commit should represent a meaningful piece of progress. Messages such as “stuff”, “work” or “final final” tell your future self very little. Prefer messages that describe the change: “Complete budget message”, “Fix exact-fit comparison”, or “Add zero-attendee test”. Small, understandable commits make it easier to review how your work developed.

### Quick self-check

In your own words, explain the difference between a repository and a commit. Then explain why a developer may want a history of working versions instead of one final folder.

### Optional resources if you want another explanation

**Watch:** [<u>Git Explained in 100 Seconds (Fireship)</u>](https://www.youtube.com/watch?v=hwP7WQkmECE)

**Read:** [<u>Gitea Docs: What is Gitea?</u>](https://docs.gitea.com/)

**Try later:** [<u>Gitea repository guide</u>](https://docs.gitea.com/usage/repository/)

### Drill

No coding drill is attached to this lesson. The goal is to understand the workflow and use the trial repository correctly. Repository activity can still be observed as part of your work evidence.

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

## Lesson 1.4 — Variables, Values and Arithmetic

| **Estimated time**   | 35–40 minutes                                                               |
|----------------------|-----------------------------------------------------------------------------|
| **Learning purpose** | Use named values and arithmetic operators to represent simple calculations. |

### What you should be able to do

- Explain what a variable represents in the small programs used here.

- Use +, -, and \* correctly with integer inputs.

- Break a calculation into readable intermediate steps.

- Check an arithmetic expression against a hand-calculated expected result.

### Names make calculations readable

A variable is a name that refers to a value while the program is running. In \`total = fare \* trips\`, the name \`total\` refers to the result of multiplying \`fare\` by \`trips\`. A useful variable name helps another person understand what the value means. Compare \`x = a \* b\` with \`total = fare \* trips\`; both may work, but the second communicates the purpose more clearly.

Variables are not permanent boxes stored forever. In these beginner functions, they are temporary names used while one function call is executing. When the function is called again with different values, the calculations are performed again with those new values.

### Arithmetic operators

Use \`+\` to add, \`-\` to subtract and \`\*\` to multiply. Parentheses can make the intended order explicit. For example, an event with 10 attendees, food at ₦800 per person and transport at ₦200 per person has a participant cost of \`10 \* (800 + 200)\`, which is ₦10,000.

When several operations appear in one expression, do not rely only on intuition. Work out the expected result by hand and, where helpful, split the calculation into named steps. Readable code is easier to test and easier to explain.

### Use the inputs — never the sample answer

If a drill shows \`travel_cost(200, 3) =\> 600\`, returning the number 600 directly is not a solution. The function must use \`fare\` and \`trips\` so it also works when the grader supplies different values. Hidden tests exist specifically to check that your logic generalises beyond the example.

### Worked example

def travel_cost(fare, trips):  
total = fare \* trips  
return total  
  
def budget_left(budget, food, transport):  
remaining = budget - food - transport  
return remaining

For travel_cost(200, 3), total becomes 600. For budget_left(2000, 900, 600), remaining becomes 500. Change the inputs and recalculate before running.

### Common mistakes to watch for

- Using \`+\` when the brief requires multiplication.

- Changing sample numbers inside the function instead of using parameters.

- Ignoring zero values even though zero is a valid input.

### Peer learning checkpoint

Choose one arithmetic function and ask a peer to predict the output for a new set of values. Compare the prediction with the actual result and explain any difference.

### Optional resources if you want another explanation

**Read:** [<u>Python tutorial: numbers and basic expressions (optional reference)</u>](https://docs.python.org/3/tutorial/introduction.html)

**Visualise:** [<u>Python Tutor</u>](https://pythontutor.com/)

### Linked drill(s) — use these to test what you just learned

**D1.4A — Travel Cost**

Complete travel_cost(fare, trips). Return fare multiplied by trips.

**Type:** Core

**D1.4B — Budget After Two Costs**

Complete budget_left(budget, food, transport). Return budget minus food minus transport.

**Type:** Core

**D1.4C — Participant Cost**

Complete participant_cost(attendees, food_per_person, transport_per_person). Return attendees multiplied by the sum of the two per-person costs.

**Type:** Reinforcement

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

## AI Lesson 1.8 — What Artificial Intelligence Is — and Is Not

| **Estimated time**   | 20–25 minutes                                                                    |
|----------------------|----------------------------------------------------------------------------------|
| **Learning purpose** | Build basic AI literacy without turning the trial into an AI-development course. |

### What you should be able to do

- Describe AI as a broad field rather than a single product.

- Recognise generative AI as one category of AI systems.

- Explain why AI output can be useful without always being correct.

- Distinguish using AI from understanding and verifying software work.

### AI is a broad idea

Artificial intelligence describes computer systems designed to perform tasks associated with capabilities such as pattern recognition, language understanding, prediction, recommendation, decision support and content generation. AI is not one chatbot and it is not magic. Different AI systems are built for different tasks and may use very different methods.

Generative AI is the category that produces new content such as text, images, audio or code in response to instructions. Large language models are one kind of generative AI system. During this trial, you are not learning how to train a large language model. You are developing enough awareness to use modern tools thoughtfully as your software-engineering skills grow.

### AI output is not proof

An AI system can produce an answer that sounds confident and is still wrong. It may misunderstand context, invent details or produce code that looks reasonable but fails important cases. An AI-native engineer is therefore not someone who copies output quickly. It is someone who can define a problem, ask useful questions, inspect the output, test it and take responsibility for the final result.

### During the trial

AI tools may be discussed in the awareness lessons, but supervised checkpoints are independent work. The purpose is to measure what you can reason through yourself. When AI use is allowed in future learning, verification remains your responsibility.

### Peer learning checkpoint

Name one useful AI application and one reason a human still needs to verify its output. Compare your examples with a peer.

### Optional resources if you want another explanation

**Read:** [<u>IBM: What is Artificial Intelligence?</u>](https://www.ibm.com/think/topics/artificial-intelligence)

**Explore later:** [<u>Elements of AI introductory course</u>](https://digital-skills-jobs.europa.eu/en/learning-space/training-catalogue/elements-ai)

### Drill

No coding drill. Complete the short AI knowledge check attached to the lesson on the platform. It checks concepts only and does not contribute to the technical selection score.

# Day 2 — Baseline, Decisions and Individual Build

| **Day outcome**  | Establish current ability, learn decisions/testing, and build the guided Personal Budget Helper.                                                                 |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Day emphasis** | The supervised baseline happens before Day 2 teaching so it remains a genuine starting-point measure. Lessons then teach new skills and each has aligned drills. |

## Day 2 Supervised Baseline Checkpoint — 10 Questions

Complete the baseline independently before today’s new lessons. This checkpoint is designed to show your current level, including any knowledge you had before the trial. It is not expected that every beginner will answer every question. Questions become progressively more demanding. Do not use AI tools, personal notes, previous solutions or peer assistance. You may run your code and retry during the allowed time.

| **Questions**              | 10                                                    |
|----------------------------|-------------------------------------------------------|
| **Purpose**                | Baseline/current ability, not a test of Day 1 only    |
| **Selection contribution** | 5 points within the combined 30% checkpoint component |
| **Supervision**            | Individual, no AI, no peer assistance                 |

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

## Lesson 2.2 — Make Decisions with if/else and Test the Boundary

| **Estimated time**   | 35–40 minutes                                    |
|----------------------|--------------------------------------------------|
| **Learning purpose** | Use a comparison to choose between two outcomes. |

### What you should be able to do

- Write a two-branch if/else function.

- Explain that only one branch runs in this pattern.

- Handle equality according to the brief.

- Return the required value from each branch.

### From a question to a decision

A comparison produces \`True\` or \`False\`. An \`if/else\` statement uses that result to decide which block of code should run. If the condition is true, Python executes the indented \`if\` block. Otherwise it executes the \`else\` block. For a simple two-outcome problem, exactly one of these branches runs.

def funding_status(budget, cost):  
if budget \>= cost:  
return "Enough"  
else:  
return "Not enough"

### Read the rule before choosing the operator

The important part is not memorising \`if\`. The important part is translating the requirement correctly. If the brief says an exact match is enough, then equality must be included. If you accidentally use \`budget \> cost\`, a budget of 700 and cost of 700 will go to the wrong branch.

Indentation again shows structure. Both return statements are indented under the branch they belong to. The colon after the \`if\` condition and after \`else\` is required syntax.

### Test three categories

Whenever a rule has a boundary, test below, equal and above. For funding_status with a cost of 700, try budgets of 699, 700 and 701. For a capacity rule where booked must be at most capacity, test one below capacity, exactly capacity and one above capacity.

### Common mistakes to watch for

- Forgetting the colon after \`if\` or \`else\`.

- Using the wrong comparison at the equality boundary.

- Returning the right words from the wrong branch.

### Peer learning checkpoint

Before running any code, take one drill sample and explain which branch should run and why. Your peer should challenge the equality case.

### Optional resources if you want another explanation

**Watch:** [<u>Conditionals and Booleans (Corey Schafer)</u>](https://www.youtube.com/watch?v=DZwmZ8Usvnk)

### Linked drill(s) — use these to test what you just learned

**D2.2A — Funding Status**

Return "Enough" when budget is greater than or equal to cost. Otherwise return "Not enough". Exact equality counts as enough.

**Type:** Core

**D2.2B — Capacity Status**

Return "Fits" when booked is at most capacity; otherwise return "Too many".

**Type:** Reinforcement

**D2.2C — Positive Places**

Return "Available" when places is greater than zero; otherwise return "Full".

**Type:** Reinforcement

## Lesson 2.3 — Function Contracts and Combining Small Functions

| **Estimated time**   | 40–45 minutes                                                                     |
|----------------------|-----------------------------------------------------------------------------------|
| **Learning purpose** | Build larger behaviour by connecting small functions with clear responsibilities. |

### What you should be able to do

- Describe a function contract using inputs, output and responsibility.

- Call a helper rather than duplicating its calculation.

- Pass a returned value into another calculation or decision.

- Explain why small functions are easier to test and combine.

### A function should have a clear job

A function contract tells you what values the function receives, what it promises to return and what responsibility belongs inside it. For example, \`participant_cost(attendees, food_per_person, transport_per_person)\` owns the attendance-based cost calculation. \`event_total(...)\` can then call that helper and add a venue cost. Separating responsibilities makes both pieces easier to test.

### Build from small pieces

When one function already solves part of the problem, reuse it. The goal is not merely shorter code. Reuse creates a single place responsible for a rule. If the participant-cost formula changes later, a program that consistently calls the helper is easier to update than a program that copied the formula into several places.

def participant_cost(attendees, food_per_person, transport_per_person):  
return attendees \* (food_per_person + transport_per_person)  
  
def event_total(attendees, food_per_person, transport_per_person, venue_cost):  
people = participant_cost(attendees, food_per_person, transport_per_person)  
return people + venue_cost

### Trace the contract chain

For \`event_total(10, 800, 200, 5000)\`, the helper receives 10, 800 and 200 and returns 10,000. The caller stores that returned value in \`people\`, adds 5,000 and returns 15,000. A later status function can receive that 15,000 and compare it with a budget. This chain of small contracts is the foundation of the Day 3 team mission.

### Common mistakes to watch for

- Repeating helper logic when the task requires the helper to be called.

- Changing the supplied helper instead of completing the missing function.

- Calling a function but ignoring its returned value.

### Peer learning checkpoint

Draw boxes for two functions. Label the inputs and returned output of each, then draw an arrow showing how the first function’s answer becomes data for the second.

### Optional resources if you want another explanation

**Watch:** [<u>Python Functions for Beginners (Corey Schafer)</u>](https://www.youtube.com/watch?v=9Os0o3wzS_I)

**Visualise:** [<u>Python Tutor</u>](https://pythontutor.com/)

### Linked drill(s) — use these to test what you just learned

**D2.3A — Event Total with a Helper**

participant_cost is supplied. Complete event_total by calling participant_cost and adding venue_cost.

**Type:** Core

**D2.3B — Calculate Then Format**

Complete budget_report so it calls budget_left and uses the returned value in the exact message "500 naira remaining."

**Type:** Reinforcement

**D2.3C — Calculate Then Decide**

Complete trip_status so it calls trip_cost and returns "Within budget" when the returned total is at most budget; otherwise return "Over budget".

**Type:** Reinforcement

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

## Lesson 2.5 — Plan from a Brief, Build a First Attempt, Use Feedback and Retest

| **Estimated time**   | 35–40 minutes                                                    |
|----------------------|------------------------------------------------------------------|
| **Learning purpose** | Bring the earlier skills together before the individual mission. |

### What you should be able to do

- Extract a small program plan from a written requirement.

- Choose inputs, output and ordered calculation steps before coding.

- Produce an inspectable first attempt rather than hiding mistakes.

- Apply a specific hint without changing the task contract.

- Retest after revision and record what changed.

### Planning prevents accidental complexity

Before the mission, practise turning a short brief into a plan. Write the function name and parameters exactly as supplied. State what should be returned. List the calculations or decisions in order. Identify one normal test and one edge or boundary test. Only then write the function body.

This does not need to be a formal flowchart. A few clear steps are enough. The goal is to reduce the amount of problem-solving you are trying to do at the same moment that you are remembering Python syntax.

### Preserve the first attempt

Your first attempt shows how you understood the task before feedback. Save it even if it is incomplete. When you receive a hint, avoid replacing your entire solution with someone else’s answer. Use the hint to identify the part of your reasoning that needs to change, then make the smallest appropriate revision.

### Retest and explain

After a change, rerun the case that failed and at least one earlier case. Then write one or two sentences explaining what was wrong and why your change addresses the requirement. This is exactly the kind of behaviour measured under learning and improvement.

### Common mistakes to watch for

- Coding without first identifying the required output.

- Replacing the whole solution after feedback instead of understanding the issue.

- Claiming a fix works without rerunning tests.

### Peer learning checkpoint

Read a new brief together, but separate before coding. Compare only your plans first: function inputs, output, calculation steps and test cases.

### Linked drill(s) — use these to test what you just learned

**D2.5A — Build from a Written Brief**

A community workshop charges fee_per_person for each attendee and has a fixed room_cost. Complete workshop_total to return the full integer cost.

**Type:** Core

**D2.5B — Apply Feedback Without Changing the Contract**

The original function returns the wrong sentence. Fix only the function body. Keep its name and parameters unchanged and return exactly "Tobi has 250 naira left." for name="Tobi", remaining=250.

**Type:** Reinforcement

## AI Lesson 2.6 — Generative AI and Prompting Basics

| **Estimated time**   | 20–25 minutes                                                               |
|----------------------|-----------------------------------------------------------------------------|
| **Learning purpose** | Understand how clear context and constraints affect AI-generated responses. |

### What you should be able to do

- Explain generative AI in simple terms.

- Identify the purpose, context, constraints and desired output in a prompt.

- Recognise that a polished AI answer still requires verification.

- Avoid sharing secrets, credentials or unnecessary personal data with AI tools.

### A prompt is part of the input

Generative AI systems produce content in response to instructions and context. A vague request such as “fix my code” leaves many assumptions unspecified. A better prompt states the goal, the relevant code or error, constraints such as “do not change the function signature”, and what kind of response would help, for example “explain the bug before showing a corrected version.”

Good prompting is not a replacement for programming knowledge. The more clearly you understand the problem, the better you can describe it and the better you can evaluate the response.

### Protect information

Do not paste passwords, access tokens, private keys, confidential customer information or unnecessary personal data into an AI tool. An AI-native engineer treats information security as part of responsible tool use.

### Verify, do not merely accept

When AI suggests code, inspect whether it matches the requirements, run tests, check boundary cases and make sure you can explain the final solution. During supervised trial checkpoints, AI tools are not allowed because the checkpoint measures your own reasoning.

### Peer learning checkpoint

Rewrite the vague prompt “help with my budget program” into a clearer prompt containing the goal, relevant context, one constraint and the desired form of help.

### Optional resources if you want another explanation

**Read:** [<u>IBM AI overview</u>](https://www.ibm.com/think/topics/artificial-intelligence)

### Drill

Complete the attached AI knowledge check (MCQ). It is an awareness check, not a coding drill and does not add technical selection points.

## Day 2 Individual Mission — Personal Budget Helper

This is a guided individual build. It deliberately reuses the ideas taught in Days 1 and 2 so that a beginner is not asked to invent an unfamiliar architecture. You still have to understand the brief, write the function bodies, test them, preserve your first attempt and improve the work after feedback.

| **Mission weight**    | 25% of final selection score                                                        |
|-----------------------|-------------------------------------------------------------------------------------|
| **Functions**         | budget_remaining(budget, food, transport) and budget_message(name, remaining)       |
| **Inputs**            | Whole-number naira amounts; names are non-empty text                                |
| **Required evidence** | First attempt, tests, feedback received, improved attempt, retest, short reflection |

def budget_remaining(budget, food, transport):  
pass  
  
def budget_message(name, remaining):  
pass

Acceptance behaviour: budget_remaining returns budget - food - transport. Negative remaining values are allowed. budget_message returns exactly: \`Ada has 500 naira remaining.\` with supplied values substituted. Do not add input prompts or unrelated output inside these functions.

### Mission workflow

7.  Write the inputs, required outputs and solution steps before coding.

8.  Implement budget_remaining and test a normal case, zero case and overspend case.

9.  Implement budget_message and compare the returned string character-by-character with the required format.

10. Save the first complete attempt.

11. Receive one specific hint or review point.

12. Revise only what is needed, rerun the failing case and at least one earlier passing case.

13. Submit final code, test results and a short explanation of what changed.

# Day 3 — Team Decomposition, Integration and Mission Launch

| **Day outcome**  | Transfer individual skills into a team project with clear component ownership and testable contracts.                |
|------------------|----------------------------------------------------------------------------------------------------------------------|
| **Day emphasis** | Less new syntax, more application. Each lesson is followed by focused drills before the team mission work continues. |

## Lesson 3.1 — Break a Team Problem into Components and Contracts

| **Estimated time**   | 35–40 minutes                                                           |
|----------------------|-------------------------------------------------------------------------|
| **Learning purpose** | Learn how a team can divide one program without dividing understanding. |

### What you should be able to do

- Identify separate responsibilities in a larger brief.

- Write a simple contract for each component.

- Understand ownership without creating isolated silos.

- Explain what another component expects from your component.

### A team project is one system

The Event Budget Helper is larger than the Day 2 mission, but it is built from the same kinds of small functions. The safest way to collaborate is to agree on the component contracts before everyone starts coding. A contract should name the function, list its inputs, state its returned value and describe the rule it owns.

For example, participant_cost owns attendee-based food and transport cost. event_total owns the addition of venue cost to that participant cost. budget_status owns the comparison between total and budget. event_summary owns the final readable message. If these contracts are clear, team members can work separately and still create compatible pieces.

### Ownership does not mean ignorance

Every learner should own code, but every learner should also understand how their component connects to at least one other component. A team member assigned only to presentation or administration has not produced enough technical evidence. Likewise, the strongest learner should not silently rewrite everyone else’s work.

### Define before you build

Write the four contracts on paper or in your team notes. Agree on exact function names and return types. Then allocate owners and reviewers. This prevents integration failures caused by one person returning text where another component expects a number, or by inconsistent names.

### Common mistakes to watch for

- Starting to code before agreeing on function names and outputs.

- Giving one learner all difficult technical work.

- Changing another person’s contract without telling the team.

### Peer learning checkpoint

As a team, each learner should explain one component they do not own and describe what value enters it and what value should leave it.

### Linked drill(s) — use these to test what you just learned

**D3.1A — Implement a Component Contract**

Implement participant_cost exactly as specified: attendees \* (food_per_person + transport_per_person). Return an integer.

**Type:** Core

**D3.1B — Implement the Status Contract**

Complete budget_status(budget, total). Return "Within budget" when total \<= budget; otherwise return "Over budget".

**Type:** Reinforcement

## Lesson 3.2 — Integrate Components and Reuse Returned Values

| **Estimated time**   | 35–40 minutes                                              |
|----------------------|------------------------------------------------------------|
| **Learning purpose** | Connect separately tested functions into one working flow. |

### What you should be able to do

- Call one component from another where the design requires it.

- Trace a value from one function to the next.

- Recognise interface mismatches during integration.

- Keep integration code simple and inspectable.

### Integration is where contracts meet

A component can pass its own tests and still fail when connected to the rest of the program if the team disagreed about names, types or meanings. Integration means connecting the pieces and checking that the output of one component is suitable as the input to the next.

The Event Budget Helper flow is: calculate participant cost → calculate event total → determine budget status → build the summary. Each step produces a value that the next step can use.

people = participant_cost(10, 800, 200)  
total = event_total(10, 800, 200, 5000)  
status = budget_status(16000, total)  
summary = event_summary("Study Day", total, status)

### Integrate in small steps

Do not wait until every component is “finished” and then combine everything at once. First confirm one helper works. Connect the next function and rerun. Then connect the decision. Finally connect the summary. When a failure appears, the smaller integration step makes it easier to locate the mismatch.

### Common mistakes to watch for

- Copying calculations instead of using the agreed helper.

- Integrating all components at once and not knowing where a wrong value appeared.

- Changing a function signature during integration without coordinating with the owner.

### Peer learning checkpoint

Trace one sample through the entire program as a team. Each owner should say what value their function receives and returns.

### Linked drill(s) — use these to test what you just learned

**D3.2A — Integrate Participant and Venue Costs**

participant_cost is supplied. Complete event_total by calling participant_cost and adding venue_cost.

**Type:** Core

**D3.2B — Build the Final Event Summary**

Complete event_summary(event_name, total, status). Return exactly "Study Day: total 15000 naira. Within budget." with supplied values substituted.

**Type:** Reinforcement

## Lesson 3.3 — Test Your Component, Document a Handover and Repair Peer Code Carefully

| **Estimated time**   | 35–40 minutes                                                             |
|----------------------|---------------------------------------------------------------------------|
| **Learning purpose** | Make individual work safe to integrate and easy for a teammate to review. |

### What you should be able to do

- Test a component independently before handing it over.

- Include normal, zero and boundary cases when relevant.

- Write a short handover note that another learner can use.

- Review peer code by identifying the smallest necessary change rather than taking over.

### A component is not ready because it ran once

Before handing your function to the team, run the published sample and at least one additional case. If zero is allowed, include it. If a boundary exists, include equality. Record the expected and actual result. This gives the integrator evidence that the component behaved correctly on its own.

### A useful handover is short and concrete

A handover note can contain four lines: component owned; what it returns; tests run; any assumption or unresolved issue. This is enough for another learner to integrate your work without guessing what you intended.

### Review without taking over

When reviewing peer code, first explain the observed problem and the evidence for it. Ask the owner what they think is happening. Point to the relevant rule or test. Only after the owner has had a chance to reason should you suggest a specific change. A reviewer who replaces the whole solution removes learning evidence from the owner.

### Common mistakes to watch for

- Handing over untested code.

- Saying “it works” without listing a test result.

- Rewriting a teammate’s entire function when one operator is wrong.

### Peer learning checkpoint

Exchange one component with another learner. The reviewer must first state one passing test and one question before suggesting any code change.

### Linked drill(s) — use these to test what you just learned

**D3.3A — Test a Component with Zero**

Complete venue_only_total so it returns venue_cost when attendees is zero and otherwise returns attendee costs plus venue. Use the supplied participant_cost helper.

**Type:** Core

**D3.3B — Repair a Teammate Component**

A teammate wrote the wrong operation. Repair event_total so it adds venue_cost after calling participant_cost.

**Type:** Reinforcement

## Lesson 3.4 — Peer Review and Visible Individual Contribution

| **Estimated time**   | 25–30 minutes                                             |
|----------------------|-----------------------------------------------------------|
| **Learning purpose** | Make collaboration observable and technically meaningful. |

### What you should be able to do

- Distinguish contribution from merely being present in a team.

- Give review feedback tied to a requirement or test.

- Record what you changed, reviewed or verified.

- Explain your own code and one part you reviewed.

### What counts as contribution

Individual collaboration evidence should come from actions that can be inspected: code you own, a test you wrote, a bug you identified with evidence, a review question that helped improve a component, or a clear handover. Talking a lot or controlling the keyboard is not automatically strong collaboration.

The shared project receives one team result, but individual collaboration is evaluated separately. That means every learner should leave a visible technical trail even though the final project belongs to the team.

### Review against the contract

Useful review comments point to something concrete: “The brief says equality is within budget; this condition uses \`\<\`.” Less useful feedback sounds like “this is wrong” or “I would write it differently.” Review the required behaviour, not personal style.

### Peer learning checkpoint

Each learner should identify one concrete contribution they have already made and one contribution they still need to make before Day 4 ends.

### Linked drill(s) — use these to test what you just learned

**D3.4A — Review Before You Rewrite**

Repair only the incorrect comparison in budget_status. Do not rename the function, change its inputs, or add unrelated features.

**Type:** Core

## AI Lesson 3.5 — AI as a Coding Assistant — Helpful, but Not the Owner

| **Estimated time**   | 20 minutes                                                                             |
|----------------------|----------------------------------------------------------------------------------------|
| **Learning purpose** | Understand appropriate uses of AI during software work without surrendering reasoning. |

### What you should be able to do

- List useful assistance tasks such as explaining errors, generating examples or suggesting tests.

- Recognise risky behaviour such as pasting generated code you cannot explain.

- Describe a verification workflow for AI-generated code.

### AI can accelerate some tasks

An AI assistant may help explain an unfamiliar error message, suggest edge cases, rewrite a vague explanation, or propose a small example that makes a concept easier to understand. These uses can reduce friction when the learner still owns the reasoning and checks the result.

### The engineer remains responsible

Generated code can introduce incorrect assumptions, hidden dependencies, security problems or logic that does not match the brief. Before accepting it, compare it with the contract, run tests, inspect the exact changes and make sure you can explain why it works. If you cannot explain the code, you do not yet own the solution.

### Peer learning checkpoint

Name one task where AI could help a developer learn and one task where blindly accepting AI output would be dangerous.

### Optional resources if you want another explanation

**Read:** [<u>IBM AI overview</u>](https://www.ibm.com/think/topics/artificial-intelligence)

### Drill

Complete the attached AI awareness MCQs. These questions are informational and are not technical coding drills.

## AI Lesson 3.6 — Data, Context and Better Prompts

| **Estimated time**   | 20 minutes                                                                      |
|----------------------|---------------------------------------------------------------------------------|
| **Learning purpose** | See why useful AI responses depend on the information and constraints supplied. |

### What you should be able to do

- Explain why missing context can produce a poor answer.

- Provide relevant code, expected behaviour and constraints without oversharing sensitive data.

- Ask for explanations and tests, not only final code.

### Context changes the answer

If you ask an assistant “why does my function fail?” but do not provide the function, the expected result or the failure message, the system must guess. A useful prompt supplies only the relevant context: the brief, the small code sample, the failing input and expected result, and any restrictions such as “keep the function signature unchanged.”

Good context is not the same as dumping everything. More information can create noise and may expose confidential data. Select the smallest amount of information needed to explain the problem.

### Ask for reasoning that you can verify

Instead of only asking “give me the fixed code,” ask the assistant to identify the likely cause, explain it in beginner language, suggest a test that would expose it, and then show a small correction. This makes the interaction more useful for learning and easier to verify.

### Peer learning checkpoint

Take a vague debugging prompt and add: the expected behaviour, the actual behaviour, one relevant code snippet and one constraint.

### Drill

Complete the attached AI awareness MCQs. No coding drill is required for this awareness lesson.

## Days 3–4 Team Mission — Event Budget Helper

Teams of 2–4 build a small event-budget program. This is an expanded version of the Day 2 individual mission so the conceptual jump stays manageable while collaboration becomes the new challenge.

| **A — participant_cost** | Return attendees \* (food_per_person + transport_per_person).          |
|--------------------------|------------------------------------------------------------------------|
| **B — event_total**      | Call participant_cost and add venue_cost.                              |
| **C — budget_status**    | Return "Within budget" when total \<= budget; otherwise "Over budget". |
| **D — event_summary**    | Return a readable exact summary using event name, total and status.    |

By the end of Day 3, each learner must have one attributable code contribution, at least one test result and one review action. Incomplete components may be temporarily replaced with a labelled facilitator stub so the team can continue, but a stub is not credited as learner work.

# Day 4 — Regression Testing, Debugging and Team Mission Completion

| **Day outcome**  | Finish the shared program, test it systematically, improve it after feedback and explain ownership with evidence. |
|------------------|-------------------------------------------------------------------------------------------------------------------|
| **Day emphasis** | Very little new syntax. The day is mainly about quality, repair, verification and mentor inspection.              |

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

## Lesson 4.3 — Explain a Change with Evidence and Prepare for Inspection

| **Estimated time**   | 30–35 minutes                                        |
|----------------------|------------------------------------------------------|
| **Learning purpose** | Turn project work into evidence a mentor can verify. |

### What you should be able to do

- Explain what was wrong before a change.

- Describe the exact change made and why it matches the brief.

- Show a failing test before and passing retest after the change.

- Explain your own component and one peer-reviewed component.

### Explanation is part of engineering work

A correct final file does not show how the team reached it. During inspection, a mentor may ask what you owned, what problem you encountered, what test exposed it, what you changed and how you know the fix did not break something else. These questions are not a memory test; they help verify understanding and contribution.

### Use a simple evidence pattern

Use four statements: requirement; observed problem; change; evidence. Example: “The requirement says exact spending is within budget. Our condition used \`\<\`, so the equality test returned Over budget. I changed it to \`\<=\`. The equality case now passes and the over-budget case still returns Over budget.” This explanation is short but technically meaningful.

### Prepare, do not rehearse a script

You should not memorise a polished speech. Open your code and tests, and be ready to point to the relevant lines. If you really understand the work, you should be able to explain it in slightly different words each time.

### Peer learning checkpoint

Use the four-part evidence pattern on one change your team made today: requirement → problem → change → evidence.

### Linked drill(s) — use these to test what you just learned

**D4.3A — Explainable Repair**

Repair seats_left. During inspection, be ready to explain the failing case, the change you made, and the retest you used.

**Type:** Core

## AI Lesson 4.4 — Hallucinations, Verification, Privacy and Responsible Use

| **Estimated time**   | 25 minutes                                                         |
|----------------------|--------------------------------------------------------------------|
| **Learning purpose** | End the AI-awareness thread with a practical verification mindset. |

### What you should be able to do

- Explain what an AI hallucination means in practical use.

- Verify generated claims or code instead of trusting confidence or fluency.

- Recognise sensitive information that should not be shared unnecessarily.

- State when human review is especially important.

### Confident does not mean correct

Generative AI systems can produce plausible statements, references or code that are incorrect. This is often described as hallucination. In software work, the response may use a nonexistent library feature, misunderstand a function contract or produce code that passes one sample but fails a boundary case.

### Verification is a workflow

For code: compare with the requirement, run tests, inspect dependencies, check edge cases and understand the logic. For factual claims: prefer authoritative sources and confirm important details. For decisions with meaningful consequences, human review is essential.

Privacy also matters. Avoid sharing passwords, API keys, private repository secrets, confidential customer data or other information that is not necessary for the task. Responsible AI use is part of professional software practice, not an optional extra.

### Peer learning checkpoint

Give one example of an AI answer that should be tested with code and one example of an AI factual claim that should be checked against a reliable source.

### Optional resources if you want another explanation

**Read:** [<u>IBM AI overview and limitations context</u>](https://www.ibm.com/think/topics/artificial-intelligence)

### Drill

Complete the attached AI awareness MCQs. These questions are informational and remain outside the technical selection weighting.

## Team Mission Part 2 — Integrate, Cross-Test, Improve and Inspect

14. Finish all four components and run the shared runner.

15. Run published acceptance cases, including zero and exact-boundary cases.

16. Exchange the integrated program with another team for cross-testing.

17. Record defects as input + expected + actual, not vague comments.

18. Each learner implements or verifies at least one documented improvement.

19. Rerun the previously failing case and relevant earlier passing cases.

20. Submit the final program, test evidence and individual contribution records.

21. Complete coding mentor inspection; each learner explains their own work and one reviewed area.

# Day 5 — Final Supervised Checkpoint and Reflection

| **Day outcome**  | Demonstrate independent Python ability after four days of learning and project work.                   |
|------------------|--------------------------------------------------------------------------------------------------------|
| **Day emphasis** | No new Python topic. The day measures independent performance and compares it with the Day 2 baseline. |

## Day 5 Final Coding Checkpoint — 15 Questions

The final checkpoint contains 15 supervised coding questions. The first questions check the core patterns repeatedly practised in lessons and drills. Later questions combine more than one taught idea, such as calculating a value and then making a decision or using a helper and formatting a result. No question should require a Python topic that was not taught during Days 1–4.

| **Questions**              | 15                                                                         |
|----------------------------|----------------------------------------------------------------------------|
| **Selection contribution** | 25 points within the combined 30% checkpoint component                     |
| **Allowed support**        | Common syntax reference supplied to all learners                           |
| **Not allowed**            | Peer assistance, AI tools, personal mission solutions or external websites |
| **Progress comparison**    | Day 2 baseline → mission/project evidence → Day 5 final                    |

## AI Awareness Check — 10 MCQs

The separate AI-awareness assessment checks whether the learner understood the surface-level ideas introduced across Days 1–4: what AI and generative AI are, prompt quality, verification, hallucinations, privacy and responsible use. This result may appear on the dashboard as an informational metric such as 8/10, but it does not contribute technical selection points.

## Final Reflection

- What could you do on Day 5 that you could not do confidently on Day 2?

- Which feedback changed the way you approached a problem?

- Which test or debugging habit helped you most?

- What did you contribute to your team?

- What is one Python concept you still need to practise?

- What does responsible AI use mean to you as a future software engineer?

# Assessment and Evidence Summary

| **Day 2 Individual Mission** | 25%                                               |
|------------------------------|---------------------------------------------------|
| **Combined Checkpoints**     | 30% — Day 2 baseline 5%, Day 5 final 25%          |
| **Learning & Improvement**   | 20%                                               |
| **Individual Collaboration** | 15%                                               |
| **Shared Team Result**       | 10%                                               |
| **AI Awareness**             | Informational only; 0%                            |
| **Activity hours**           | Tracked for context; not a direct selection score |

# Resource Library

External resources are optional. They provide another explanation when needed; they do not replace the lesson text.

**Git video:** [<u>Git Explained in 100 Seconds</u>](https://www.youtube.com/watch?v=hwP7WQkmECE)

**Gitea reference:** [<u>Gitea Docs: What is Gitea?</u>](https://docs.gitea.com/)

**Gitea practice:** [<u>Gitea repository guide</u>](https://docs.gitea.com/usage/repository/)

**Python orientation:** [<u>Python in 100 Seconds</u>](https://www.youtube.com/watch?v=x7X9w_GIm1s)

**Code visualizer:** [<u>Python Tutor</u>](https://pythontutor.com/)

**Functions video:** [<u>Corey Schafer: Python Functions</u>](https://www.youtube.com/watch?v=9Os0o3wzS_I)

**F-strings video:** [<u>Corey Schafer: F-Strings</u>](https://www.youtube.com/watch?v=nghuHvKLhJA)

**Conditionals video:** [<u>Corey Schafer: Conditionals and Booleans</u>](https://www.youtube.com/watch?v=DZwmZ8Usvnk)

**Python reference:** [<u>Official Python Tutorial (optional reference; assumes some programming background)</u>](https://docs.python.org/3/tutorial/introduction.html)

**AI reference:** [<u>IBM: What is Artificial Intelligence?</u>](https://www.ibm.com/think/topics/artificial-intelligence)

**AI optional course:** [<u>Elements of AI</u>](https://digital-skills-jobs.europa.eu/en/learning-space/training-catalogue/elements-ai)

# Help Ladder

22. Read the requirement again and underline the required output.

23. Return to the relevant worked example in the lesson.

24. Predict one small case by hand.

25. Read the failing test or error message carefully.

26. Ask a peer a specific question and show what you already tried.

27. Use the optional resource for another explanation.

28. Ask a coding mentor for a concept hint or technical-access help. Do not request a complete solution.
