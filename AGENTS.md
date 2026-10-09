# Repository Guidelines

## Purpose

This repository supports introductory business studies (경영학의 이해). Contributions should help a beginner understand course concepts through clear explanations, practical examples, and concise exam preparation material. Use Korean for learning content unless the user requests another language.

## Project Structure & Organization

The repository currently contains no source code, tests, or assets. Keep this guide at the repository root. As study material grows, use the following suggested directories:

- `notes/`: concept explanations and lecture summaries.
- `exercises/`: practice questions with clearly separated answers.
- `assets/`: images or diagrams referenced by study notes.

Create directories only when needed. Use descriptive filenames such as `notes/pestel-analysis.md` or `notes/nominal-and-real.md`, and use relative links between documents.

## Development & Validation Commands

There is currently no build system, application runtime, test framework, or configured linter. Do not assume commands such as `npm test` are available.

- `git status --short`: inspect pending changes before and after editing.
- `git diff --check`: check tracked changes for whitespace errors.
- `git diff`: review edits to tracked files; inspect newly added files separately.

Preview Markdown and verify referenced files exist before submitting changes.

## Writing Style & Naming Conventions

Use Markdown headings, short paragraphs, and tables for useful comparisons. Use lowercase, hyphen-separated filenames. Avoid unnecessary jargon; explain unfamiliar terms when first introduced. No language-specific coding or indentation rules apply yet.

## Learning Content & Review

Follow the tutoring format: simple definition → everyday example → one-sentence exam definition. Check arithmetic, distinguish related concepts, and identify illustrative numbers as examples. Verify current policies or statistics against reliable sources when used. No automated coverage requirement exists; review accuracy, readability, and links manually.

## Commit & Pull Request Guidelines

There is no commit history establishing conventions. Use concise, action-oriented messages, such as `docs: explain PESTEL analysis`. Keep changes focused. Pull requests should describe the learning topic, summarize changes, and state validation performed. Link related issues when applicable; include screenshots only when visual changes need review.

## Privacy

Do not commit credentials, student identifiers, grades, or private course records. Summarize course material in original wording rather than copying entire textbooks or lecture slides.
