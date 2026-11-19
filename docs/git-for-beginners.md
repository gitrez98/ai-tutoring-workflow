# Git for beginners

Git is a local history of your project. A **repository** is the project and its history; a **commit** is a saved snapshot. GitHub is a separate online service that can hold a copy of a repository.

From a terminal opened in this project:

```sh
git status
git add README.md docs templates prompts config.example.md .gitignore
git status
git commit -m "Describe the change"
```

Before committing, inspect the files Git lists. Do not add student records, private links, credentials, recordings or copyrighted teaching materials. Do not use `git add .` blindly.

To publish, first create or choose a repository on your preferred service and follow that service's current instructions for connecting it. A public repository can be seen by anyone. Publishing is a separate action from saving locally; review every file and commit before pushing. If another person owns the destination, confirm you have permission to write there.
