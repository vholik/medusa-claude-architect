---
description: Install the Medusa.js codebase to the latest version
argument-hint: <feature or update description>
---

# Install Medusa.js codebase command

This command installs or updates the Medusa.js codebase to the latest version in your project.

You will need to run the following commands in this directory: `~/.medusa-agents`

Use this when you need to:

- Set up the Medusa codebase for the first time
- Update to the latest version of Medusa
- Refresh your local copy of the documentation

## Task

1. Create `~/.medusa-agents` folder if not exist.

2. Execute the following git subtree pull command inside `~/.medusa-agents` directory:

```bash
  git subtree pull --prefix resources/medusa https://github.com/medusajs/medusa.git main
```

Command will fetch the latest changes from the upstream repository and merge them into the local subtree. There should be no conflicts, if there are ask the user what they want to do.
