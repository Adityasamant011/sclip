# Sclip

**A free video editor you can use by hand, and your own AI agent can drive.** Sclip runs on your Mac (Apple silicon, macOS 13 or newer). Edit with the mouse and keyboard, or connect Claude, Codex, Cursor or any
MCP client and watch it edit the same timeline while you watch. Sclip itself contains no AI agent: the agent is yours.

This repository is the public home of Sclip: the legal documents, the downloads (see Releases) and the place to report problems. The source code is not published.

- **Report a bug or ask for something:** [Issues](https://github.com/Adityasamant011/sclip/issues)
- **Terms of Use:** [TERMS.md](TERMS.md) · **Privacy:** [PRIVACY.md](PRIVACY.md) · **Licence:** [LICENSE](LICENSE)
- **Third-party software:** [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md) · **FFmpeg source offer:** [SOURCE-OFFER.md](SOURCE-OFFER.md)
- **Security reports:** [SECURITY.md](SECURITY.md)

## Install (Mac)

1. Download the DMG from Releases and drag **Sclip** into **Applications**.
2. The first time, macOS may say it cannot verify the developer, because Sclip is not yet signed with a paid Apple developer ID. Open **System Settings, Privacy & Security** and press **Open Anyway**, or run
   `xattr -dr com.apple.quarantine /Applications/Sclip.app` once in Terminal.
3. To connect an agent, open **Settings, Agent**, press **Copy setup prompt** and paste it into your agent.

Sclip is built on WeftCut (MIT, Copyright (c) 2026 UncleChair).
