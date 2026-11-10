# Security Policy

AccountMap stores sensitive information about how people's accounts can be recovered, so security reports are taken seriously.

## Reporting a vulnerability

**Please don't open a public issue.** Report privately through GitHub:

1. Go to the **Security** tab of the affected repository (for example [AccountMap/accountmap](https://github.com/AccountMap/accountmap/security)).
2. Click **Report a vulnerability** and describe the problem, how to reproduce it, and its impact.

AccountMap is maintained by a small team, so please allow up to **7 days** for a first response. We'll keep you updated while we work on a fix and credit you in the release notes unless you'd rather stay anonymous.

## In scope

- Encryption, key derivation, and vault handling
- Any way the app leaks map data off the device (network requests, logs, crash reports, analytics)
- The browser extension, including communication with web pages and the desktop app
- The sync service, once it exists
- accountmap.org and the hosted demos

## Out of scope

- The hackathon demo stores data **unencrypted** in browser storage by design and warns users not to enter real data. Issues that only follow from that design are out of scope.
- Reports that require a device that's already fully compromised
- Missing best-practice headers or similar findings without a demonstrated impact

## Supported versions

AccountMap is pre-release. Fixes go into the latest version only.
