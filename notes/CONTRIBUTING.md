Contributing to Test5 Poetry Collection

Thank you for your interest in contributing to the Test5 poetry collection. This document explains how to propose changes, add new poems, and follow the repository's style so contributions stay consistent and easy to review.

How to Contribute

1. Fork the repository and create a feature branch from main (or the default branch):
   - git checkout -b feature/add-new-poem

2. Add or edit files in plain text (.txt) format for poems and Markdown (.md) for documentation.
   - New poems should be added to the root directory as .txt files with descriptive filenames (e.g. summer_poem.txt).
   - If you add many poems, consider creating a poems/ directory and adding an index in README.md or DOCUMENTATION.md.

3. Follow the style guidelines (see Style Guide below) when writing or editing poetry.

4. Commit with a descriptive message and open a pull request describing your changes.
   - Example commit message: Add "Summer Breeze" poem (summer_poem.txt)

5. Use the PR description to note any stylistic choices, author attribution, and suggested reading order.

Review Process

- Maintainers will review PRs for clarity, format, and adherence to the style guide.
- Suggested edits may be requested; please address feedback by pushing additional commits to your branch.
- Once approved, a maintainer will merge the PR.

Style Guide

- File format: Poems must be saved as UTF-8 plain text (.txt).
- Filenames: Use lowercase, underscores, and descriptive names (e.g. morning_glory.txt).
- Poem header: Include a title line, followed by a blank line, then the poem body.
  - Example:
    Morning Glory

    Morning dew on blades of grass,
    Golden light through clouds that pass.

- Line endings: Use LF (\n).
- Spelling and grammar: Maintain readable language and correct spelling but preserve intentional stylistic choices.
- Metadata: If you wish to include author and date, add a short comment block at the top of the file using the following convention:
  - Title
  - Author: Name
  - Date: YYYY-MM-DD
  - (Blank line)

Attribution and Licensing

- If you add a poem you authored, state your name in the metadata block.
- For public contributions, ensure you have the rights to publish the content under the repository's license.

Accessibility and Formatting

- Keep poems readable in plain text (avoid excessive indentation or unusual characters).
- If including special symbols, ensure they render in UTF-8.

Contact

If you have questions or want to discuss larger structural changes (collection reorganization, adding audio/visual assets, etc.), open an issue or reach out via the repository's issue tracker.
