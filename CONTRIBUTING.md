# Contribution guidelines

## Public-data rule

This repository must remain safe to publish.

- Use synthetic or intentionally public demo data only.
- Never commit employee names, client contacts, prospect lists, internal notes, account status, territory assignments or other business-confidential information.
- Keep real datasets local and excluded by `.gitignore`, or use a separate private repository.

## Structure

- Keep the public prototype small and understandable.
- Use descriptive names and avoid temporary or duplicate files.
- Separate reusable application logic from data if the project grows beyond a single prototype file.
- Do not add unrelated projects to this repository.

## Quality

- Test search, filters, map markers and export after changes.
- Preserve mobile usability and accessibility.
- Keep external dependencies minimal and pinned to known versions when practical.
- Use concise commit messages describing the actual change.
