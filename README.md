# Pulse Commit support

This repository is the public issue tracker for the Pulse Commit iOS app. It
contains support forms and policies only; the app source is maintained
separately.

Current support target: pre-release Pulse Commit 1.0 (build 1) on iOS 17 or
later. This compatibility statement describes the current development target
and does not claim App Store availability.

## Before opening an issue

Never post Health exports, GitHub or Telegram tokens, Telegram chat IDs, or
personal health metrics. Remove names, repository details, message contents,
and other identifying information from error text before submitting it.

- [Report a bug](https://github.com/gaiverrr/pulsecommit-support/issues/new?template=bug.yml)
- [Request a feature](https://github.com/gaiverrr/pulsecommit-support/issues/new?template=feature.yml)
- Read the [Privacy Policy](https://pulsecommit.app/privacy)

For a suspected security vulnerability, do not open a public issue. Follow the
private reporting instructions in [SECURITY.md](SECURITY.md).

## Support expectations

Support is best-effort. There is no response or resolution SLA, and a submitted
request does not promise a fix, feature, or delivery date.

## Triage workflow

New forms receive a type label (`bug` or `enhancement`) and `needs-triage`.
A maintainer then applies one of these states:

- `needs-info`: a safe, reproducible report needs more non-sensitive detail.
- `confirmed`: a bug has enough evidence to reproduce and track.
- `planned`: a feature request has been accepted for future work.

Duplicates, unsupported requests, and reports that cannot be investigated
safely may be closed with a public explanation. When private application work
resolves an issue, a maintainer can close it with a cross-repository commit
reference. GitHub shows people without access only minimal reference details;
private source and implementation details stay private.
