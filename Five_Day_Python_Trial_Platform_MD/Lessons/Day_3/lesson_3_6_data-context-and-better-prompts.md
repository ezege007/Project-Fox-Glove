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
