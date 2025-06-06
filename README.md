# action-repo

This repository is part of a GitHub webhook demonstration project. It serves as the source repository that triggers webhook events when actions like push, pull requests, and merges occur.

## Purpose

When actions are performed on this repository:
1. GitHub sends webhook events to our webhook endpoint
2. The webhook endpoint stores these events in MongoDB
3. A UI displays the events in real-time

## Webhook Events

This repository is configured to send the following webhook events:
- Push events
- Pull request events
- Merge events

## Testing

To test the webhook functionality:
1. Make changes and push to this repository
2. Create a pull request
3. Merge a pull request