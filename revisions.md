## Revisions and the Cloud

The beauty of Git and Github is that is allows collaboration and redundant back ups to protect projects from catastrophic failures, i.e. not keeping all your eggs in one basket.

Programmers work on their code locally and when they're ready to submit their code to the master branch in the cloud, they go through an ACP process: git add, git commit, and git push.

git add tracks a file for staging. This tags the file to let git know that it's ready to be committed.

git commit takes a snapshot of all modifications to tracked files in the working directory. In simple terms, it's just saving that version of your changes.

git push sends it to a remote repository from your local repository, allowing your changes to be published, cloned, and otherwise interacted with.
