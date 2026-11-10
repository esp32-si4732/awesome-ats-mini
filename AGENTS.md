# Repository guidelines

This repository is a curated list of ATS Mini projects and resources.

## Editing the list

- Keep entries in the appropriate README.md section.
- Sort entries alphabetically by author, callsign or organisation,
  ignoring case. Sort projects by name when the author is the same.
- Use this format:
  - [Project name (author)](URL) - Short description.
- Preserve established project names and author spelling.
- Limit descriptions to two short sentences.
- Focus on distinguishing features rather than promotional claims.
- Mention hardware requirements or experimental limitations when
  they affect whether someone can use the project.
- Preserve existing entries unless removal or correction is requested.

## Research

- Verify claims against project documentation, release notes or source.
- Distinguish implemented features from planned features.
- Check archives and download folders before concluding that source
  code is unavailable.
- Do not equate a missing licence with closed source.
- Use the following badge immediately after the project link when
  closed-source status is established:
  ![Closed source](https://img.shields.io/badge/closed%20source-grey)
- If source availability is uncertain, report that uncertainty rather
  than assigning a definitive badge.
- Avoid version numbers, star counts and other rapidly changing
  details unless they are necessary to explain compatibility.

## Scope and validation

- Keep changes focused on the requested additions or corrections.
- Do not add unchanged forks or duplicate download mirrors as
  separate projects without a clear reason.
- Preserve existing URLs unless a replacement has been verified.
- Run `git diff --check` after editing.
- Check alphabetical ordering, duplicate entries and Markdown syntax.
- No build or automated test suite is needed for list-only changes.
