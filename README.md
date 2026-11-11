# eternia-qa-course

A QA fixture course for Eternia's staging environment. It exists so the
Eternia app can install a course from a GitHub release and open its lessons
in a test run. It is not a real course.

- `eternia-course.json` — the course manifest (format v2)
- `sections/01-basics/01-first-lesson/` and `sections/01-basics/02-folder-lesson/`
  — lesson folders: an `index.html` and the `lesson.md` it names

Releases (`qa-2`, …) are what staging lists. `qa-1` is an older release that
still carried a single-file Markdown lesson; it is not used.

The text is original QA filler, licensed CC BY 4.0 (see `LICENSE`).
