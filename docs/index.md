---
title: Relay messenger
---

# Relay messenger

Relay messenger is a native macOS desktop shell for the official Meta Messenger, WhatsApp Web, and Telegram Web sites. It keeps each service in a persistent WebView behind a small sidebar, with native macOS menus for switching, reload, logout, focus mode, theme mode, and opening the current page in your default browser.

Relay messenger is not affiliated with, endorsed by, or sponsored by Meta, Messenger, WhatsApp, Telegram, or Apple.

## Support

For support, email [lubos@komfi.health](mailto:lubos@komfi.health).

Include:

- macOS version
- Relay messenger version
- Whether the issue affects Messenger, WhatsApp, Telegram, or the app shell
- What you expected to happen
- What happened instead
- Any screenshot that does not expose private messages, phone numbers, names, profile photos, or message previews

Do not send passwords, 2FA codes, cookies, tokens, exported WebView data, private messages, contact lists, or screenshots containing sensitive chat content.

## Troubleshooting

- If a service is offline, check your network connection and use `Reload`.
- If Meta, WhatsApp, or Telegram asks for login, 2FA, passkey confirmation, or QR pairing, complete that flow inside the official page shown in the app.
- If a provider security check gets stuck, open the current page in your default browser, complete the provider-owned check there, then return to Relay messenger and reload.
- If camera or microphone access is denied, restore access in macOS System Settings -> Privacy & Security.
- If you want to clear a Meta or WhatsApp session, use `Log Out of Meta` or `Log Out of WhatsApp` from the app menu. Telegram session controls stay inside Telegram Web.
- If support asks for diagnostics, use `Show Diagnostic Logs` from the app menu. Send only the redacted local diagnostic log, never exported WebView data or screenshots with private chat content.

## Privacy

Relay messenger does not collect personal data, does not run analytics, does not run telemetry, and does not have a backend server.

Read the full [Privacy Policy](./privacy/).

## Source

[github.com/lubos-buracinsky/relay-messenger](https://github.com/lubos-buracinsky/relay-messenger)

---

*Relay messenger by Supersonic™*
