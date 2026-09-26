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
