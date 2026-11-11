# eternia-qa-course

A QA fixture course for Eternia's staging environment. It exists so the
Eternia app can install a course from a GitHub release and open its lessons
in a test run. It is not a real course.

- `eternia-course.json` — the course manifest
- `sections/01-basics/01-markdown-lesson.md` — a Markdown lesson (format v1)
- `sections/01-basics/02-folder-lesson/` — a lesson folder (format v2):
  `index.html` and the `lesson.md` it names

Releases (`qa-1`, …) are what staging lists.

The text is original QA filler, licensed CC BY 4.0 (see `LICENSE`).
