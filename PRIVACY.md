# Sclip Privacy Policy

Last updated: 24 November 2026

## The short version

Sclip runs on your Mac. **The Sclip project does not collect data from Sclip.** There are no accounts, no analytics, no crash reports and no tracking inside the app.

## What stays on your computer

Your projects, media, exports, settings and downloaded models are stored on your Mac. Keys you enter for optional services are stored encrypted by macOS and never inside a project, a log or
a diagnostic report. Sclip's local connection point for agents listens only on your own computer (127.0.0.1) and requires a secret token.

## When Sclip connects to the internet

Only when you ask it to, with one exception: Sclip looks for a newer version by itself.

| What | Why | To whom |
|---|---|---|
| Looking for a new version of Sclip | Automatically when Sclip starts and every few hours; turn it off in Settings (Help, Check for Updates works either way). The file is signed, and an update is downloaded only when you choose it, or when you have switched on installing on exit | GitHub (github.com): a small file naming the newest version; GitHub sees your IP address, as any website does, and nothing about you or your projects is sent |
| Downloading models and runtimes (speech, voices, vision) | You pressed Set up, or chose a model | GitHub release downloads and Hugging Face |
| Searching stock photos and videos | You searched in the Media Library | Pexels and Openverse (Pexels needs your key) |
| Creating a voiceover with ElevenLabs | You chose it and entered a key | ElevenLabs (the script text) |
| Generating with Higgsfield | You chose it and entered a key | Higgsfield (your prompt) |
| Opening a bug report | You pressed Help, then Report an issue | GitHub, in your browser, with the app version and OS, which you can edit before sending |

Those companies handle your data under their own policies. Sclip sends them nothing else.

## Agents you connect

If you connect an AI assistant or other software to Sclip, it can read and edit the open project through Sclip's local connection. What that software does with the information is governed by
its own provider's policy, not ours.

## Children

Sclip is not directed at children under 16, and the project does not knowingly collect data from anyone.

## Your rights

Because the Sclip project holds no personal data from the app, there is nothing for us to access, correct or delete. To remove everything Sclip stored on your Mac, delete the app and the folder
`~/Library/Application Support/Sclip`. If you open a public issue on GitHub, GitHub's policy applies to what you post there.

## Changes and contact

We will post changes here and update the date. Contact: open an issue at https://github.com/Adityasamant011/sclip/issues.
