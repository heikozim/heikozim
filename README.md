<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/heikozim/hilde/main/docs/logo/hilde-wordmark-dark.svg">
  <img src="https://raw.githubusercontent.com/heikozim/hilde/main/docs/logo/hilde-wordmark-light.svg" alt="Hilde" width="310" height="100">
</picture>

IT security by profession, open source by conviction.  Most of what I
write in my own time is Hilde, a programming language that is
High-Integrity, Linear, Deterministic and Explicit, and the software built
on it.  Website: https://hilde-lang.org/

## The Hilde family

| Project | What |
|---|---|
| [Hilde](https://github.com/heikozim/hilde) | the language: linear types and mandatory contracts |
| [Wolly](https://github.com/heikozim/hilde-wolly) | a web framework in Hilde: Web-ready, OpenBSD-first, Linear, Lean, Yours |
| [RAMBO](https://github.com/heikozim/hilde-rambo) | Rights, Accounts, Multi-factor, Bearer tokens & OAuth: an OpenID provider with passkeys, written in Hilde on Wolly |
| [MIRCO](https://github.com/heikozim/hilde-mirco) | a science kit in Hilde: Matrices, Interpolation, Random numbers, Calculus, Optimization |
| [ROXIE](https://github.com/heikozim/hilde-roxie) | a log collector written in Hilde on Wolly |

The repositories here are mirrors; releases are signed with signify.

## Contributions

To the web server [Hiawatha](https://hiawatha.leisink.net/):

- sharded HTTP/2 event loops (H2EventLoops), bans of ChallengeClient over
  HTTP/2 and the fix for truncated large HTTP/2 downloads (12.4)
- HTTP/2 via nghttp2 (12.1)
- the OS sandbox (12.0)
- the update to mbed TLS 4.0.0, and strcpy()/sprintf() replaced by
  strlcpy()/snprintf() (12.0)

## Other

- [Inga](https://github.com/heikozim/dart-inga), an HTTP header and
  Cloudflare inspector for Firefox and Chrome, in Dart, on
  [webext](https://github.com/heikozim/dart-webext)

Contact: code@heiko-zimmermann.com
