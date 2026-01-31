# Action Repo - GitHub Webhook Trigger

This repository is used to **trigger GitHub events** that are captured by a webhook in the `webhook-repo`.  

It is part of the Developer Assessment Task to demonstrate GitHub webhook integration.  

## Features

1. **Push events**
   - Any commit pushed to this repository triggers a `push` webhook event.

2. **Pull Request events**
   - Creating a pull request triggers a `pull_request` webhook event.
   - Merging a pull request triggers a `merge` event captured in the webhook-repo.

## Test File

- `test.txt` is included to test push and pull request workflows.
- Modify it, commit changes, and push to trigger webhook events.

## Usage

1. Make changes to any file (like `test.txt`) and push to GitHub.
2. Create a pull request to simulate PR workflow.
3. Merge the PR to simulate a merge event.

> These actions will be captured in the webhook-repo via the configured webhook.
