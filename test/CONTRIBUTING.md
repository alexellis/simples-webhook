# Derek

Derek is our enforcer, don't worry he's very polite when he's working hard to save us time in helping you to contribute.  Derek checks that particular part of our contributing guide are being adhered to when you submit your PRs, and if he finds you've inadvertently missed a step he'll try to help out by applying labels and leaving you a message.

## Your commit doesn't appear to be signed-off
You'll see a `no-dco` label applied and a short note from Derek reminding you to sign off your commits so that we are able to merge your work.  The easiest means of achieving this is:

On your local repo amend the commit:

`git commit --amend --signoff`

Then force push:

`git push -f <remote> <branch>`

With future commits avoid seeing this message by adding `-s` to your commit command:

`git commit -sm'Good commit subject using imperative mood`

## Please check that your commit messages fit within these guidelines
You'll see a `review/commit-message` label applied and a short note from Derek directing you to observe our desired conventions for commit messages.

On your local repo amend the commit:

`git commit --amend`

Edit the commit message and after saving force push:

`git push -f <remote> <branch>`