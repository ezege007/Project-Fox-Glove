# Five-Day Python Trial Curriculum

## Overview

The **Five-Day Python Trial Curriculum** is a self-learning, peer-supported beginner programming trial designed to help candidates build foundational Python skills, demonstrate how they learn, and develop early awareness of how modern software engineers work with AI.

The curriculum is structured as an intensive five-day boot camp. Learners are not taught through traditional lectures. Instead, each lesson is written as a complete self-learning resource that teaches the concept directly, provides examples and guided practice, and is followed by one or more drills that test the knowledge taught in that lesson.

The trial is designed to collect meaningful evidence about each candidate's:

- technical understanding;
- problem-solving ability;
- ability to learn from feedback;
- ability to explain their reasoning;
- individual work;
- collaboration with peers;
- contribution to team work;
- progress from baseline to final assessment.

---

## Core Learning Model

The curriculum follows a simple rule:

> **The lesson teaches. The drill tests.**

Each lesson should contain enough explanation for a beginner to learn the topic without requiring a facilitator to teach it.

Where appropriate, a lesson contains:

1. **Learning outcome**
2. **Why the concept matters**
3. **Concept explanation**
4. **Worked examples**
5. **Prediction or reasoning activities**
6. **Practice tasks**
7. **Peer-learning prompts**
8. **Common mistakes**
9. **Self-check questions**
10. **Optional videos and further-reading resources**
11. **One or more linked drills**

The number of drills depends on the size and complexity of the lesson. A simple lesson may require one drill, while a broader lesson may require two, three, or more.

Some lessons intentionally do not have coding drills. For example, the introductory Git/Gitea lesson is primarily an orientation and workflow lesson.

---

## Technology and Workflow

The curriculum uses:

- **Python** for programming exercises;
- **Git** for version control;
- **Gitea** for repository hosting and learner code repositories;
- the learning platform for lessons, drills, missions, checkpoints, inspections, and progress tracking.

Learners should understand that:

- **Git** is the version-control system;
- **Gitea** is the platform where Git repositories are hosted;
- a **repository** stores a project's files and version history;
- commits record meaningful versions of work;
- learners should save and submit their own work through the provided repository workflow.

The curriculum should not refer to GitHub as the trial repository platform.

---

## Five-Day Structure

### Day 1 — Foundations and First Working Code

Day 1 introduces candidates to the learning environment and the foundations they need before project work begins.

Typical topics include:

- using Git and Gitea;
- understanding repositories and commits;
- breaking a problem into instructions;
- input, processing, and output;
- reading a simple Python function;
- variables;
- arithmetic expressions;
- strings and formatted text;
- `return` versus `print`;
- parameters, arguments, and function calls;
- tracing returned values;
- common beginner errors;
- introductory AI awareness.

Day 1 is primarily a learning and orientation day. It is not intended to carry a major scored project.

---

### Day 2 — Baseline Assessment and Individual Build

Day 2 combines further Python learning with the first individual project.

It includes:

- a **supervised 10-question baseline checkpoint**;
- comparisons and Boolean expressions;
- conditional execution with `if/else`;
- function contracts;
- testing expected versus actual results;
- debugging;
- combining simple functions;
- planning a small program;
- generative AI and prompting awareness;
- linked coding drills;
- the guided **Personal Budget Helper** individual mission.

The Day 2 checkpoint is used partly to establish the learner's current level. It should not be treated only as a test of Day 1 content.

---

### Day 3 — Team Mission Launch

Day 3 shifts toward collaboration and transfer of learning.

It includes:

- function/component ownership;
- breaking a larger task into smaller parts;
- integrating functions;
- testing components before integration;
- peer review;
- code handover;
- communication and team responsibility;
- AI as a coding assistant;
- data, context, and prompts;
- linked drills;
- launch of the **Event Budget Helper** team mission.

The team mission expands the thinking used in the Day 2 Personal Budget Helper into a shared project.

---

### Day 4 — Integration, Testing, and Improvement

Day 4 focuses on completing, testing, and improving the team project.

It includes:

- acceptance testing;
- regression testing;
- debugging;
- explaining code ownership;
- cross-team testing;
- applying feedback;
- documenting fixes;
- AI hallucinations, verification, and responsible AI use;
- mentor inspection of team work.

The emphasis is on evidence of improvement, collaboration, and the ability to explain what was built.

---

### Day 5 — Final Assessment and Reflection

Day 5 is focused on final evidence rather than introducing major new Python concepts.

It includes:

- a **supervised 15-question final coding checkpoint**;
- learner reflection;
- final submission checks;
- an AI-awareness multiple-choice assessment.

No AI tool should be used during the supervised coding checkpoint.

The final checkpoint provides stronger evidence of what the learner can do independently after the full trial.

---

## Assessment Model

The agreed selection model is:

| Component | Weight |
| --- | ---: |
| Day 2 Individual Mission | 25% |
| Checkpoints | 30% |
| Learning & Improvement | 20% |
| Individual Collaboration | 15% |
| Shared Team Result | 10% |
| **Total** | **100%** |

### Checkpoint breakdown

The checkpoint component contains:

- **Day 2 baseline checkpoint:** 10 questions
- **Day 5 final checkpoint:** 15 questions

The final checkpoint should carry more importance than the baseline because the Day 2 assessment partly measures prior exposure, while Day 5 measures the learner after the trial experience.

### Informational metrics

The following are tracked but should not directly add points to the 100-point selection score:

- AI-awareness score;
- total active hours;
- active/inactive status;
- last activity time;
- lesson completion speed.

These metrics support review and interpretation but should not reward a learner simply for spending more time online.

---

## Missions

### Individual Mission — Personal Budget Helper

The Day 2 project is intentionally guided.

Learners apply arithmetic, functions, returned values, and formatted messages to build a small budget helper.

The mission is used to assess:

- correctness;
- use of supplied values;
- tests;
- explanation;
- response to feedback;
- independent revision.

### Team Mission — Event Budget Helper

The Day 3–4 team mission is an expanded version of the individual project.

Teams of approximately 2–4 learners build a program that can:

- calculate attendance-based costs;
- add venue costs;
- compare spending with a budget;
- return a budget status;
- produce a readable event summary.

The team receives a shared project score, while individual collaboration is assessed separately.

---

## Drill Design Rules

Drills should always be linked to specific lesson content.

A drill must test something that the learner has already been taught.

### A good drill should:

- be short and focused;
- use the same concept in a different example;
- require the learner to use supplied inputs;
- avoid hard-coded sample answers;
- return the requested value or message;
- contain visible sample tests;
- contain private hidden tests where supported;
- avoid introducing an untaught Python concept.

### Drill quantity

There is no fixed rule that every lesson must have exactly one drill.

Use:

- **1 drill** for a narrow concept;
- **2–3 drills** when multiple aspects need separate verification;
- more only when each drill provides distinct evidence.

Do not add drills purely to increase quantity.

### Exceptions

A lesson may have no coding drill where a coding challenge would not be meaningful.

Examples:

- Git/Gitea orientation;
- some AI-awareness lessons.

AI-awareness concepts should normally be checked using short conceptual questions or MCQs rather than Python coding challenges.

---

## Private Drill Authoring Bank

The private drill authoring bank is for curriculum administrators and platform authors.

It contains implementation details such as:

- drill display name;
- linked lesson;
- instructions;
- starter code;
- allowed constructs;
- restrictions;
- sample tests;
- hidden tests;
- inspection questions;
- reference solutions;
- core/reinforcement classification.

**Do not publish private tests or reference solutions to learners.**

---

## AI Awareness

The trial does not attempt to teach learners how to build machine-learning models or large language models.

The goal is to establish basic AI literacy for future AI-native software engineers.

Topics may include:

- what AI is;
- what AI is not;
- generative AI;
- large language models at a surface level;
- prompts and context;
- AI as a coding assistant;
- hallucinations;
- verification;
- responsible use;
- privacy and sensitive information.

AI content should remain lightweight and should not displace the Python programming objectives of the trial.

---

## Peer Learning

The curriculum is self-learning **with peers**, not facilitator-led classroom teaching.

Learners should be encouraged to:

- compare predictions;
- explain code to one another;
- ask specific questions;
- review another learner's tests;
- discuss why an answer is correct;
- give hints without taking over another person's work.

The learner should still produce attributable individual work.

---

## Facilitator and Coding Mentor Role

Facilitators and coding mentors should support the learning environment without becoming the primary source of instruction.

They should:

- resolve technical blockers;
- clarify ambiguous instructions;
- encourage learners to use lesson resources;
- observe how learners ask for and apply help;
- inspect missions;
- verify ownership of work;
- ask learners to explain their code;
- record evidence of collaboration and improvement.

They should not routinely provide complete solutions to drills or missions.

---

## Progress and Dashboard Metrics

The platform should make it possible to review, for each learner:

- lessons completed;
- lesson completion time;
- drills attempted;
- drills passed;
- drill scores/results;
- checkpoint performance;
- mission submissions;
- team mission result;
- individual collaboration evidence;
- learning/improvement evidence;
- daily active hours;
- active/inactive state;
- last activity timestamp;
- AI-awareness score;
- overall trial progress.

The student-facing dashboard may summarize progress using statuses such as:

- **Getting Started**
- **On Track**
- **Strong Candidate**
- **Needs Review**

These statuses are progress indicators, not automatic final selection decisions.

---

## Resource Strategy

Each lesson should be complete enough to stand on its own.

External resources are supplementary.

Where helpful, lessons may include:

- short YouTube videos;
- official Python documentation;
- beginner-friendly programming references;
- Git documentation;
- Gitea documentation;
- optional further-reading links.

Avoid sending beginners to long or highly technical documentation without explaining which specific section is relevant.

---

## Files in This Curriculum Package

Typical package files include:

- `Five_Day_Python_Trial_Rich_Self_Learning_Curriculum_Gitea.html`  
  Learner-facing curriculum in professionally formatted HTML.

- `Five_Day_Python_Trial_Private_Drill_Authoring_Bank_Gitea.html`  
  Private platform-authoring reference for drills.

- Markdown (`.md`) versions of the same content may also be maintained for easier editing and platform import.

---

## Publishing Guidance

When publishing content to the learner platform:

1. Publish lessons as separate learner-facing units.
2. Link each lesson to its appropriate drill(s).
3. Keep hidden tests and solutions private.
4. Keep mission instructions separate from drill authoring metadata.
5. Verify all code blocks render correctly.
6. Verify all sample tests before release.
7. Confirm Gitea repository links and learner access.
8. Confirm lesson completion and drill completion events are tracked.
9. Test the student journey before the cohort begins.
10. Archive or reset trial repositories according to the trial operations policy after the cohort ends.

---

## Quality Standard

Before a lesson is approved for publishing, ask:

- Does the lesson actually teach the concept?
- Could a beginner learn this without a lecturer?
- Is the explanation long enough to be useful but short enough to remain engaging?
- Are examples correct?
- Are drills aligned only to taught content?
- Do drills test understanding rather than copying?
- Are resources relevant and optional?
- Is the learner told what to do next?
- Is there evidence the platform can collect from this lesson?
- Does this lesson help prepare the learner for the next mission or checkpoint?

If the answer to any critical question is no, revise the lesson before publishing.

---

## Curriculum Principle

The trial should not reward only people who already know Python.

It should create enough structure to identify:

- what a learner could do when they arrived;
- how they approached new material;
- whether they could apply feedback;
- how independently they could work later;
- how they collaborated;
- what they could do by the end of Day 5.

That progression is central to the design of the Five-Day Python Trial.
