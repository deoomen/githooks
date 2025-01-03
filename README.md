# githooks

My custom and sample githooks

## Usage

Copy the file you want to your `<project_path>/.git/hooks/` directory and cut off everything from `_` sign. Remember to check if the file is executable!

## Hooks

| Filename | Description |
| --- | --- |
| commit-msg_conventional-commits | Checks before creating a commit whether the commit title meets the requirements of Conventional Commits. |
| prepare-commit-msg_jira_link | Add link to Jira issue in the commits footer. **You must modify this hook before use!** |
