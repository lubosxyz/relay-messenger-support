---
title: Privacy Policy — Relay messenger
permalink: /privacy/
---

# Privacy Policy

**Effective date:** 2026-05-08
**Product:** Relay messenger (macOS desktop app)
**Publisher:** Supersonic — published through the Apple Developer Program

## Summary

Relay messenger is a desktop shell that hosts the official Meta Messenger and WhatsApp Web sites in two separate native macOS WebViews. We do not read, store, transmit, or analyze your messages, contacts, calls, or any other content from those services.

We do not collect **personal data**. Chat data stays inside the official web sessions you log into, on Apple's WebKit storage on your Mac, and on Meta's servers — the same provider-owned surfaces you use when opening facebook.com/messages or web.whatsapp.com in a browser.

## Data we collect from you

**None.** We do not collect, transmit, sell, or share any personal data. We do not run analytics. We do not run telemetry. We do not have a server.

## Data stored locally on your Mac

When you sign in to Meta Messenger or WhatsApp Web inside Relay messenger, the official sites store the same data they would store in any browser:

- Login session cookies and tokens (so you stay signed in)
- Chat caches and offline storage (IndexedDB, local storage, service worker caches)
- Any media or attachments those services choose to cache

This data is written by Meta's own web code into Apple's WebKit storage, inside the macOS App Sandbox container assigned to Relay messenger. It never leaves your Mac through us.

You can clear this data at any time from the app menu — `Log Out of Meta` and `Log Out of WhatsApp` wipe cookies, local storage, IndexedDB, and caches for the corresponding service.

Relay messenger may also write a small local diagnostic log for app-owned failures such as blocked external links, failed menu actions, failed service switching, service-load timeouts, completed service loads over five seconds, and unusually slow app-owned actions. This log stays on your Mac, is limited in size, and redacts URL-like text, local file paths, email-like or phone-like contact details, tokens, cookies, passwords, authorization values, session identifiers, secrets, private message or chat content labels, contact-list details, profile-photo references, screenshots, screen captures, local storage, IndexedDB, and WebView data references. It is not sent to us automatically. You can open the folder from the app menu with `Show Diagnostic Logs` if support asks for it.

## Third-party services

When you use Relay messenger, you are interacting directly with:

- **Meta Platforms** (Meta Messenger at facebook.com/messages) — see [Meta's Privacy Policy](https://www.facebook.com/policy.php).
- **WhatsApp** (WhatsApp Web at web.whatsapp.com) — see [WhatsApp's Privacy Policy](https://www.whatsapp.com/legal/privacy-policy).

Anything you send, receive, or store in those services is governed by their privacy policies, not ours. Relay messenger has no control over what data those services collect or how they use it.

## Camera and microphone

macOS asks for your explicit permission the first time Relay messenger needs the camera or microphone. We only request access when a chat service (a call you start in Messenger or WhatsApp) needs it. The audio and video stream goes from your Mac directly to Meta's servers via WebRTC, the same way it does in any browser. Relay messenger does not see, record, copy, or relay this stream.

You can revoke camera or microphone access at any time in **System Settings → Privacy & Security**.

## Children

Relay messenger is not directed to children under 13. The third-party services it hosts (Meta Messenger, WhatsApp Web) have their own age requirements — please follow theirs.

## Changes to this policy

If this policy changes, the new version will be published at the same URL with an updated effective date. Material changes will also be noted in the app's release notes.

## Contact

Email: lubos@komfi.health

---

*This policy applies only to the Relay messenger desktop app. It does not apply to the Meta Messenger or WhatsApp services themselves, which are operated by Meta Platforms, Inc.*
