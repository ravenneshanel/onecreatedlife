# Ravenne Website Workflow

This repo controls the live website at:

https://onecreatedlife.com

## Simple Version

1. Ask Codex for a website edit.
2. Codex edits the local repo files.
3. Preview the change locally.
4. When ready, Codex commits and pushes to GitHub.
5. Vercel automatically deploys the update.
6. The change appears on `onecreatedlife.com`.

## What Each Place Means

- Local repo: the safe editing copy on this computer.
- GitHub: the official saved code.
- Vercel: the publisher that turns GitHub changes into the live website.
- Live website: what visitors see at `onecreatedlife.com`.

## Safety

Do not commit passwords, API keys, private client information, or payment details to this repo.

Use Vercel Environment Variables or a secrets manager for sensitive values.

