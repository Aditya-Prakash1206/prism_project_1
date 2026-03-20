# prism_project_1

what git is?
-> Git is a distributed version control system used to track changes in source code during software development.  It allows developers to manage different versions of files, collaborate efficiently, and maintain a complete history of changes
how to push code to github
-> 


- Install Git from git-scm.com if not already installed
- Configure your identity: `git config --global user.name "Your Name"` and `git config --global user.email "you@example.com"`

**Create or clone a repo**

- To start fresh: create a new repo on GitHub, then clone it with `git clone <repo-url>`
- To use an existing local project: run `git init` in your project folder, then link it with `git remote add origin <repo-url>`

**Stage your changes**

- Add specific files: `git add filename.txt`
- Add everything: `git add .`

**Commit your changes**

- `git commit -m "Your descriptive commit message"`

**Push to GitHub**

- First push: `git push -u origin main` (sets upstream tracking)
- Subsequent pushes: `git push`

important points:
- Run `git status` anytime to see what's staged or unstaged
- Run `git log` to see your commit history
- If your default branch is `master` instead of `main`, replace accordingly
- Use a Personal Access Token (PAT) or SSH key for authentication instead of a password\
what is markdown?
->
Here are the key points about Markdown:

Markdown is a lightweight markup language used to format plain text
Created by John Gruber in 2004
Uses simple symbols like #, *, - to format text
Gets converted into HTML or other formats
Easy to read and write without knowing HTML
Where it is used:

GitHub  README files and documentation
Reddit and Discord  chat and post formatting
Notion and Obsidian  note-taking apps
Blogs like Dev.to and Medium
AI tools like Claude and ChatGPT