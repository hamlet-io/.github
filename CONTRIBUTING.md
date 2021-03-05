# Contributing to Hamlet Deploy

Hamlet Deploy encourages contributions from the community.

To contribute to any of the Hamlet Deploy repositories, please follow the process outlined below.

 1. fork the repository
 2. update your changes in a feature branch
 3. Push to your fork's origin
 4. Create a Pull Request from your Fork to the Upstream master.

 ```bash
 # fork the repository on Github.
 # https://github.com/hamlet-io/executor-python.git
 # add your upstream repo
 git remote add upstream https://github.com/hamlet-io/executor-python.git
 # create your working branch
 git checkout -b feat/my-feature-branch
 # make your changes / updates / fixes in as many commits as necessary.
 # rebase your work into only relevant commit messages
 # example: I've made 3 commits, but two of them are fixups.
 # git rebase -i HEAD~3
 # mark the fixups and save the commits
 git rebase -i HEAD~<number of commits since HEAD>
 # push your feature branch to your origin (the fork)
 git push --set-upstream origin feat/my-feature-branch
 # on Github, create a PR from your fork/feature-branch to upstream/master.
 # make sure you complete any Issue/PR templates provided.
 ```

 For additional information on Hamlet Deploy, see https://docs.hamlet.io