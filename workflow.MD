# typical workflow
0. clone the repo in question, verify access (e.g. SSH, etc)
   - you only need to do this once
1. pick up a task (i.e. github issue)
2. create a branch for the task (i.e. a feature branch)
3. do some work (i.e. build the feature per task requirements)
4. commit the work on your branch
   - if not done, go back to step 3
   - if done, go to step 5
5. push your branch to Github
   - it doesn't hurt to push your branch if you are not yet
6. create a Pull Request in Github
   - can be a draft if not completely done
   - assign someone (or some people) to review
   - use the resolve keywords
7. finish code review process
   - address any comments on your PR
   - make any necessary changes per comments
   - commit and push said changes to update the PR
8. merge the PR into the main branch
   - if you used the resolve keywords, the issue will automatically be closed