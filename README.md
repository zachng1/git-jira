# git-jira

This is a simple git hook which will find a pattern matching a Jira ticket id in your branch name and prepend it to all commit messages on that branch.

If your branch name does not match the pattern ([A-Z]+-[0-9]+) for a Jira ticket it will not prepend anything.

Enable it by placing it in `.git/hooks` and making it executable.
