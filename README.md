# GIT EXERCISES

# Bundle-1

## Exercise-1
```bash

innocent@innocent-ThinkPad-X240:~/Desktop/thegym/bundle-1-exercise-1$ git init
Reinitialized existing Git repository in /home/innocent/Desktop/thegym/bundle-1-exercise-1/.git/
innocent@innocent-ThinkPad-X240:~/Desktop/thegym/bundle-1-exercise-1$ git branch -m main
innocent@innocent-ThinkPad-X240:~/Desktop/thegym/bundle-1-exercise-1$ touch README.md
innocent@innocent-ThinkPad-X240:~/Desktop/thegym/bundle-1-exercise-1$ git add README.md 
innocent@innocent-ThinkPad-X240:~/Desktop/thegym/bundle-1-exercise-1$ git commit -m 'Adding readme file'
[main (root-commit) 04842f6] Adding readme file
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
innocent@innocent-ThinkPad-X240:~/Desktop/thegym/bundle-1-exercise-1$ git remote add origin git@github.com:innotuyi/Gym-Git-Exercise-Solutions.git
innocent@innocent-ThinkPad-X240:~/Desktop/thegym/bundle-1-exercise-1$ git branch -M main
innocent@innocent-ThinkPad-X240:~/Desktop/thegym/bundle-1-exercise-1$ git push -u origin main

innocent@innocent-ThinkPad-X240:~/Desktop/thegym/bundle-1-exercise-1$ git branch
* dev
  main
innocent@innocent-ThinkPad-X240:~/Desktop/thegym/bundle-1-exercise-1$ git switch -c test
Switched to a new branch 'test'
innocent@innocent-ThinkPad-X240:~/Desktop/thegym/bundle-1-exercise-1$ git branch
  dev
  main
* test
innocent@innocent-ThinkPad-X240:~/Desktop/thegym/bundle-1-exercise-1$ git checkout dev
M       README.md
Switched to branch 'dev'
innocent@innocent-ThinkPad-X240:~/Desktop/thegym/bundle-1-exercise-1$ git branch -d test 
Deleted branch test (was 04842f6).
innocent@innocent-ThinkPad-X240:~/Desktop/thegym/bundle-1-exercise-1$ git branch
* dev
  main

```
