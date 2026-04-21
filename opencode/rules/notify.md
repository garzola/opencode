---
name: Prompt Completion Actions
description: Things to do when finishing a prompt
---

When you have finished the current prompt, run this command to alert
the user.  If this command fails, mention that in your last output to
the user.

```
ntfy publish --tags=gear --priority=default --title "OpenCode Task Completed" xuWPVioS "$(date +'%Y.%m.%d/%H:%M:%S') OpenCode has completed the most recent task"
```
