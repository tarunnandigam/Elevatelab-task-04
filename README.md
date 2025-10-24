# Elevatelab-task-04
## Development branch changes


The goal of this task was to manage a DevOps project using Git best practices, including branching, merging, using pull requests, tags, .gitignore.

Tools Used :
Git – version control
GitHub – remote repository and collaboration
VS Code / Terminal – local development
YouTube tutorials, GitHub documentation

Pull Requests & Merging :
On GitHub, created a PR to merge feature/update-readme → dev.
Merged dev → main to keep main branch production-ready.
Ensured proper merge messages and cleaned up branches after merging.

problems faced :
1)Changes Not Committed
Cause: Edited file but forgot to stage them before committing.
Solution: Run git add <file> to stage the changes, then git commit -m "message" to successfully commit.

2)Confusion with Branching & Merging
Cause: Unsure about the order of merging feature → dev → main.
Solution: Followed GitHub best practices:
Merged feature branch → dev using Pull Request
Then merged dev → main using Pull Request
Deleted feature branch after merge to keep repo clean.


Outcome:
Successfully completed a version-controlled DevOps project
Implemented proper branching, commits, .gitignore, and tagging
Documented workflow clearly for reproducibility
