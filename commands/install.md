---
description: Install the Medusa.js codebase
argument-hint: <feature or update description>
---

# Install Medusa.js codebase command

This command installs the Medusa.js codebase to the latest version in your project.

You will need to run the following commands in current directory (`./`)

Use this when you need to:

- Set up the Medusa codebase for the first time

## Task

1. Create `./.medusa` folder if folder does not exist.

2. Go to `./.medusa`

```bash
cd .medusa
```

3. Execute the following command to add repo

```bash
git subtree add --prefix medusa-repo https://github.com/medusajs/medusa.git develop --squash
```

Command will fetch the latest Medusa repository and add them into the local subtree.
