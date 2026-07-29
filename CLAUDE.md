# CLAUDE.md - your course workspace, operated with an AI assistant

This repo is **yours** for the whole course: where you read materials, see your grades, and keep
your own notes, journal, and project. An AI coding assistant (e.g. Claude Code) can drive it with
you - you describe what you want in plain language, it helps you study, plan, and draft. This file
is the assistant's standing instructions and stays in this repo (it is read in-context).

The full platform documentation is the **single source of truth** and lives in the platform repo's
`docs/` set (<https://github.com/tjakoen/github-native-course-platform/tree/main/docs>). This repo's
`README.md` is your day-one guide (how to create the repo under the course org, name it, keep it
private).

## What this repo is

Two zones:

- **Delivered to you (read-only in practice):** `content/` (course materials), `grades/` (your
  results), `attendance/`. These are written by the class's automated publish step and are
  **overwritten on the next publish** - do not hand-edit them; your changes there will be lost and
  they are not the source of truth. If a grade looks wrong, raise it with your instructor, don't
  edit the file.
- **Yours to edit:** `notes/`, `journal/`, `project/`. This is your workspace - the assistant helps
  you here.

`student.json` is your identity in the class (subject, class, GitHub username). Don't change it
unless your instructor tells you to.

## Safety rules (do not violate)

1. **Academic integrity is the whole point.** The assistant helps you *learn* - plan, explain,
   review, draft, debug. Graded work you submit must be your own understanding. Don't have it produce
   an answer you can't explain; if you can't explain it, you didn't learn it.
2. **Never edit `grades/`, `content/`, or `attendance/` to change what they say.** They're
   downstream of the class engine and get republished. A hand-edit is both futile and dishonest.
3. **Keep this repo Private and under the course org.** Never make it public; never add another
   student as a collaborator. Your work is yours; their work is theirs.
4. **No secrets or tokens in the repo.** Nothing in git history.
5. **When something's ambiguous** (a grade, a due date, a materials mismatch), ask your instructor -
   don't guess and don't "correct" delivered files.

## How I work here

This workspace follows Tjakoen's personal standards for building and writing with an AI, published
at <https://tjakoen.github.io/standards> - **reference them, don't fork them.** For any prose in your
own name, the short version of [VOICE.md](https://tjakoen.github.io/standards/voice): honest,
concrete, your own words; no backticks or em-dashes in prose.

## Commit convention

No AI attribution trailers on commits (`Co-Authored-By: Claude` etc.). Your commits are your record
of your own work.
