# Repository guidelines

Maintain a curated list of ATS Mini projects and resources in README.md.

## Entries

- Use the appropriate section and sort by author/callsign/organisation,
  then project name, ignoring case.
- Format: `[Project name (author)](URL) - Description.`
- Preserve established names. Describe distinguishing features in at
  most two short sentences, including relevant hardware requirements
  and experimental limitations.
- Append unlinked Shields.io badges as HTML `<img>` tags with descriptive
  `alt` text and `height="16"` (default baseline alignment): grey
  `closed source` when confirmed, orange `paid` when purchase is required,
  and blue `updated YYYY-MM-DD` when known.

## Verification

- Check claims against project documentation, release notes or source;
  distinguish implemented features from plans.
- Check archives and download folders before classifying firmware as
  closed source. A missing licence or source you cannot find is not
  sufficient evidence.
- Date badges use the latest commit on the linked GitHub branch
  (default branch unless specified), or the latest documented firmware
  update, including development versions.
- Avoid volatile details such as versions and star counts unless
  needed for compatibility; update-date badges are an exception.

## Changes

- Keep edits within the requested scope; preserve existing entries
  and URLs unless a correction or replacement is justified.
- Include forks and mirrors separately only when they offer something
  distinct.
- Check ordering, duplicates and Markdown syntax, then run
  `git diff --check`.
