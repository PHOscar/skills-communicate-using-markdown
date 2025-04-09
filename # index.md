# Code Example
```
$ git init
Initialized empty Git repository in /Users/skills/Projects/recipe-repository/.git/
```

- name: Check markdown syntax, code example
  uses: skills/action-check-file@v1
  with:
    file: "index.md"
    search: "```"
