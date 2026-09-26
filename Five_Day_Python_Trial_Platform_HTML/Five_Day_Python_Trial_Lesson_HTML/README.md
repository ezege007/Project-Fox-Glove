# Platform-Ready Lesson HTML

This package contains one HTML file per learner-facing lesson.

## What to upload

Upload the contents of each `.html` file into the platform lesson-content field for the matching lesson.

The files are intentionally **HTML fragments**, not full websites. They contain:
- semantic headings;
- paragraphs and lists;
- metadata tables;
- code blocks;
- external resource links;
- peer-learning prompts;
- common mistakes;
- self-checks;
- linked drill descriptions.

They do **not** contain global CSS, JavaScript, navigation, checkpoints, missions, hidden tests, or private reference solutions. This allows the platform's existing theme to control the appearance.

## Lesson units included

- Day 1: Lessons 1.1–1.8
- Day 2: Lessons 2.1–2.6
- Day 3: Lessons 3.1–3.6
- Day 4: Lessons 4.1–4.4

Day 2 checkpoint, individual mission, Days 3–4 team mission, and Day 5 assessments are separate platform units and are intentionally not included as lesson files.

## Recommended platform styling hooks

The fragments use these classes:
- `l2e-lesson`
- `lesson-header`
- `lesson-kicker`
- `lesson-body`
- `lesson-meta-table`
- `lesson-section-title`
- `resources-title`
- `drills-title`

The root `<article>` also includes:
- `data-day`
- `data-lesson`
- `data-linked-drills`

These may be used by engineering for navigation, progress tracking, or presentation.
