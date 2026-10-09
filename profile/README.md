# Unwrapped

Small, fast desktop apps, written in Rust. Each one replaces an app we found slow, heavy or
stuck on one platform.

The apps share one foundation, so they look and behave alike. Each aims to open in under
300 ms and use under 100 MB when idle, and benchmarks run on every change so a slowdown
fails the build. Everything here is early.

| App | What it is | Runs on |
|---|---|---|
| [three dots](https://threedots.chat) | Messenger as a small, fast Mac app | macOS |
| Disk Space | See what's filling your disk, and what filled it recently | macOS, Linux |
| Meeting Notes | Live notes and suggested answers during calls, with no bot joining | macOS, Linux |
| API Client | An API client that keeps requests as plain files next to your code | macOS, Linux |

There are no Windows builds yet. Apps are GPL-3.0; the foundation is MIT or Apache-2.0.

[unwrapped.sh](https://unwrapped.sh)
