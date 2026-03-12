# Local Quiz Review Checklist

Use this checklist before opening a pull request.

## File location and naming
- File lives at: docs/<pillar>/<concept-slug>/quiz/q-<github-handle>-<n>.yaml
- Filename matches: q-<github-handle>-<n>.yaml
- <github-handle> is lowercase, matches your GitHub username
- <n> starts at 1 and increments per concept

## Required fields and structure
- Required fields present: author, date, question, options
- date format is YYYY-MM-DD (valid calendar date)
- question is at least 20 characters
- options array has exactly 4 items
- Exactly one option has correct: true
- Each option includes non-empty text and explanation
- Each explanation is at least 10 characters

## Consistency checks
- author matches the GitHub handle in the filename
- Filename handle matches the PR author (case-insensitive)
- File is new; do not edit another student's file

## Question quality
- Tests reasoning or application, not pure vocabulary recall
- Correct answer is unambiguously correct
- Wrong answers are plausible misconceptions
- Explanations are clear and instructional
- Uses Markdown where helpful (bold, inline code, math)
