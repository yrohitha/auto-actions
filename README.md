# Notes

This sends an API request to GitHub to assign the PR author.
- `${{ secrets.GITHUB_TOKEN }}` is an auto-generated token for authentication.
- `${{ github.event.pull_request.user.login }}` extracts the PR author's username.

The API endpoint: https://api.github.com/repos/OWNER/REPO/issues/PR_NUMBER/assignees tells GitHub to assign the user to the PR.

We have added few github actions here.
Now, that helps us clarify users about the promotion strategy easily.
