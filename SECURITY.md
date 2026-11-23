# Security

Report a vulnerability in Sclip privately: open https://github.com/Adityasamant011/sclip/security/advisories/new (GitHub private vulnerability reporting). Please do not post exploitable details in a public issue.

Include what you found, the Sclip version (shown in **About**) and a way to reproduce it. This is a small project, so replies are best effort.

Most worth reporting: the local agent connection (it listens on 127.0.0.1 and needs a token), any way for an agent to export without the person's approval when that setting is off, the `weftcut-media://` and
`motif://` file handlers, and how stored keys for optional services are protected.
