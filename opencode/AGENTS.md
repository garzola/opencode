---
name: OpenCode
description: Global Agents information for all projects
---
# On Start
When you start processing the prompt, run this command to alert the user.  If this command fails, silently ignore the error.
```
ntfy publish --tags=gear --priority=default --title "OpenCode Task Staring" xuWPVioS "OpenCode has started it's current prompt"
```

# On Completion
When you have finished the current prompt, run this command to alert the user.  If this command fails, mention that in your last output to the user.
```
ntfy publish --tags=gear --priority=default --title "OpenCode Task Completed" xuWPVioS "OpenCode has completed the more recent task"
```
