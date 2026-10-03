ANSWER1. --global saves the Git username and email as default settings for my user account on the computer, applying them to all my Git repositories. Without it, the settings apply only to the current repository.

ANSWER2. The .git directory appeared in ls -a but not in the regular ls output because it is a hidden directory. It stores Git's internal information, including repository history, configuration, and references.

ANSWER3. Git was offering to track the files and folders inside my coding-cafe directory, including the .venv folder and its contents. Since .venv contains Python environment files that I didn't create myself, it shouldn't be tracked by Git.

ANSWER4. After adding .gitignore, the .venv/ folder and its contents no longer appeared in git status because Git was ignoring them. The .gitignore file itself appeared as an untracked file.

ANSWER5. The .gitignore file should be committed rather than ignored. It specifies which files and folders Git should exclude, and committing it ensures that everyone working on the project follows the same rules.

ANSWER6. README.md moved from “Untracked files” to “Changes to be committed.” According to the three-places model, it moved from the working directory to the staging area after I ran git add README.md.

ANSWER7.  [master (root-commit) 4fc2ea7] Initial commit
5 files changed, 360 insertions(+)

ANSWER8. 4fc2ea7

ANSWER9.   git status
 git add lab4/notes.md
git commit -m “Add lab 4 notes”
git log - -oneline

ANSWER10. GitHub gives README.md a special role because it automatically appears on the repository’s main page. It introduces the project and explains what the repository contains without requiring visitors to open other files.

ANSWER11. gh auth login logged me into my GitHub account and set up authentication for Git operations over HTTPS. This allows Git to verify my identity when I push changes without asking for my GitHub password every time.

ANSWER12. The README.md file appears on the main page of my GitHub repository because GitHub automatically displays it as an introduction and documentation for the project.

ANSWER13. No, pushing did not change my local history. It only uploaded my existing commits to GitHub, leaving my local commits and their history unchanged.

ANSWER14. A private repository exists on GitHub, but only the owner and people with permission can access it. If a repository does not exist on GitHub, there is no online version of the project or its Git history available there.