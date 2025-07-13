# GitHub Action Trigger Repository

This repository is used to **trigger webhook events** (e.g., `push`, `pull_request`, `merge_group`) which are sent to a separate **Flask-based webhook listener**.


## Related Repositories

- [Webhook Listener (Flask App)](https://github.com/ishitagupta26/webhook-repo)

##  How It Works

Perform any of the following in this repo to trigger the webhook:

- `git push`
- Create a `pull request`
- Merge a branch into `main`

These actions send JSON payloads to the webhook URL configured in GitHub → Settings → Webhooks.

## Webhook URL Configured
https://sweet-bananas-return.loca.lt/webhook
