# AGK Template Registry

This folder contains the local template registry index for AgenticGoKit.

## Files
- index.json: Registry entries used by `agk template list` and `agk init`.
- LICENSE: Registry license file.

## Updating the registry
1) Add or update entries in index.json.
2) Keep entries consistent with template metadata (name, version, description).
3) Validate locally with:
   - agk template list
   - agk init <project> --template <name>

## Local development tips
- Use `agk template add <path>` to add local templates.
- Use `agk template remove <name|source>` to clear cached templates.
- If a template is cached, remove and re-add to pick up changes.
