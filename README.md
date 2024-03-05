# Basic ci

This repo aims at demonstrating how to put basic Github actions in place:

## GitHub Actions

GitHub Actions make it easy to automate all your software workflows as it integrates perfectly with GitHub without any configuration effort on the developer’s side

✅ Plus, it’s free for public GitHub repositories!

### A few details to consider:

- An event can be any git action (push, new branch, etc.) but also any GitHub-specific event
- Only events on your remote GitHub repository will be considered; if you commit on your local machine but do not push, nothing will be triggered
- An action can be really anything: shell command, another GitHub Action, etc.
