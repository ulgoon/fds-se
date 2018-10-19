# Frontend Dev SCHOOL
## Software Engineering

### index
- git extended
- Software Engineering

## How to work with your co-worker

PM
- (git init ->) git flow init
- some change -> add,commit,push develop

Dev team
- fork PM's repo -> clone
- git flow init

- git flow feature start <feat-name>
- some change -> add, commit, push to feature/<feat-name>
- git flow feature finish <feat-name>

-  git remote add pmorigin <PM's repo addr>
-  git pull pmorigin develop

- git push origin develop -> create PR (dev to dev)
