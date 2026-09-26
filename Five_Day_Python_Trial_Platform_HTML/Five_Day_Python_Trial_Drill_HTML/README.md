# Platform-Ready Drill HTML

This package contains one learner-facing HTML fragment per coding drill.

## What is included in each drill

Each upload fragment contains:
- drill ID and title;
- linked lesson;
- Core/Reinforcement label;
- coin value;
- learner instructions;
- starter code;
- allowed constructs;
- restrictions;
- visible sample tests;
- a short submission checklist.

## What is intentionally excluded

The learner-facing HTML does **not** include:
- private hidden tests;
- private reference solutions;
- mentor inspection checklists;
- internal authoring notes.

Those remain in the private drill authoring bank.

## Organization

- Day 1 drills
- Day 2 drills
- Day 3 drills
- Day 4 drills

Git/Gitea Lesson 1.1 has no coding drill by design.

AI-awareness lessons use conceptual MCQ/knowledge checks rather than Python coding drills, so they are not included in this coding-drill package.

## Suggested platform CSS hooks

Each fragment uses:
- `l2e-drill`
- `drill-header`
- `drill-kicker`
- `drill-meta`
- `drill-meta-item`
- `drill-section`
- `sample-tests`
- `chip`
- `allowed`
- `forbidden`
- `drill-reminder`

The root article contains useful data attributes such as:
- `data-drill`
- `data-day`
- `data-linked-lesson`
- `data-practice-type`
- `data-coins`
