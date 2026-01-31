# action-repo
Repository to test GitHub actions with webhook
## Purpose

- Trigger webhook events for **Push** and **Pull Request** actions.
- Forward events to a Flask server running locally and exposed via **ngrok**.
- Later, events will be stored in **MongoDB** and displayed in a minimal UI.

## How to Test

1. Make changes to files (like this README) and push to GitHub.
2. Flask server should receive the webhook payload.
3. Verify in Flask console that the webhook data is printed.

