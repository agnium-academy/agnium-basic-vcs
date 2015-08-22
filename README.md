# Agnium VCS Basic

Agnium Course: Learn the basics of VCS with Git and GitHub.

Revision Control, Version Control System (VCS), or sometimes referred as Source Code Management (SCM) is a tool and system to manage the changes of repository. The repository could contain any kind of files, documents, computer programs, and other various media.

##Overview

| Subject | Description	| Exercise | Duration (H) |
|:--------|:------------|:---------|:-------------|
| About VCS	| <ul><li>What is version control system?</li><li>Why do we need that?</li><li>What kind of VCS we’re going to use?</li><li>How to do a basic setup with Git?</li></ul> | Setup Git on both terminal and GUI application such as Github, SmartGit or SourceTree. | 1 |
| Initialization & Saving Changes | <ul><li>Initializing a new repository and cloning an existing repository using `init` and `clone` respectively.</li><li>Staging current working copy to index with `add`, and commit staged changes into local repo using `commit`.</li></ul> | Create a new repo and clone from the existing new one. Create new files and stage them before doing commit to current repo. | 1 |
| Branching |	<ul><li>Branching with `branch`.</li><li>Navigate between branches with `checkout`.</li><li>Put a forked history back together again with `merge`.</li></ul> | Create a new branch from current working branch, and do some changes, and then merge them back together. |	2 |
| Undoing Changes |	<ul><li>Checkout to specific commit or branch with `commit`.</li><li>Revert commit with `revert`, reset commit with `reset`, difference between `revert` and `reset`.</li></ul> | Create several commits in a single branch, switch them using reset and revert. | 2 |
| Rewriting History |	<ul><li>Amend the most recent commit with `commit --amend`.</li><li>Rebasing with other local repo with `rebase` / `rebase -i`.</li></ul> | Create new local branches, start working on the branches and master branch, and start rebasing. | 4 |
| Syncing |	<ul><li>Connect to remote repo with `remote`.</li><li>Import remote commits to local repo with `fetch`.</li><li>Merging upstream changes into local repo with `pull`.</li><li>Transfer commits from local repository to a remote repo with `push`</li></ul> | Create changes and commit them into local repo before pushing it into remote repo. And other team member do fetch for the last upstream changes before they pull it into local repo. | 2 |
| Forking & Pull Request | <ul><li>What is fork and pull request?</li><li>How are these two related?</li><li>What circumstances do we fork and issue a pull request?</li></ul> | Each team member create private central repo and forked by others. Contribute by adding some new files and create pull request. | 2 |
| <strong>FINAL TEST</strong> ||||

## Resources
+ http://git-scm.com
  + http://git-scm.com/doc
  + http://git-scm.com/book
+ https://github.com
+ http://bitbucket.com
+ https://www.atlassian.com/git
+ https://training.github.com
+ https://try.github.io
+ http://gitimmersion.com
+ http://pcottle.github.io/learnGitBranching
