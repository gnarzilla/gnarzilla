# thatch

Building the internet for the apocalypse: Update your blog from a can on a string from the smoldering rubble.

Secure, performant, privacy-focused apps in the **Deadlight** ecosystem—open-source tools for resilient web platforms on mesh/satellite/spotty networks. User sovereignty first.

## Deadlight Ecosystem
Modular tools for blogging/email/comms without always-on servers. Optimized for slow links, batteries, text terminals.

- **blog.deadlight** (JS, ⭐13): <10KB pages, email posting. [Demo](https://deadlight.boo)
- **proxy.deadlight** (C): SMTP/IMAP/SOCKS bridge + VPN.
- **meshtastic.deadlight** (C, ⭐7): LoRa-to-internet gateway. [Site](https://meshtastic.deadlight.boo)
- **deadlight-bootstrap** (JS, ⭐13): Lightweight web framework starter for Cloudflare Workers + D1.  [Demo](https://v1.deadlight.boo)
- **lib/edge.deadlight** (JS+C): Shared libs and umbrella platform.
- **vault.deadlight** (C): Local encrypted credential store for CLI/proxies. Offline-friendly, integrates with proxy.deadlight. (MVP in progress)

## Live Deployments

[![D E A D L I G H T](https://deadlight.boo/favicon.ico)](https://deadlight.boo)[deadlight.boo](https://deadlight.boo) - Main platform demo with proxy integration

[![thatch pad](https://thatch-dt.deadlight.boo/favicon.ico)](https://thatch-dt.deadlight.boo)[thatch pad](https://thatch-dt.deadlight.boo) - Zero-JS instance with use case examples

[![mobile.deadlight](https://mobile.deadlight.boo/favicon.ico)](https://mobile.deadlight.boo)[mobile.deadlight](https://mobile.deadlight.boo) - Android deployed instance via Termux

[![meshtastic.deadlight](https://meshtastic.deadlight.boo/favicon.ico)](https://meshtastic.deadlight.boo) [meshtastic.deadlight](https://meshtastic.deadlight.boo) - LoRa gateway project blog

[![threat level midnight](https://threat-level-midnight.deadlight.boo/favicon.ico)](https://threat-level-midnight.deadlight.boo) [threat-level-midnight](https://threat-level-midnight.deadlight.boo) - Federation testing instance

[v1.deadlight](https://v1.deadlight.boo) - Legacy bootstrap framework

These demonstrate: sub-10 KB page weights, text-only client compatibility, global edge distribution, secure authentication, real-world resilience.

## Philosophy & Stack
Optimize for reality: Intermittent connectivity, scarce power, resilience > features.

- Edge-first (Cloudflare Workers/D1)
- Minimal deps, no JS required
- C for networking, JS for serverless

Stack: JS/C, SMTP/SOCKS/LoRa, Wrangler/Markdown.

## Current Focus
- Meshtastic integration, email-to-post, comments.
- Proxy dashboard, plugins, federation (ActivityPub/HF radio).

## Why Deadlight?
The internet's fragile for most people. Deadlight enables privacy-focused sites on 2G/LoRa without servers/costs/exploitation.

## Contribute
Test, docs, accessibility help welcome. Issues/PRs open.

## Contact
Email: deadlight.boo@gmail.com | Discord: t.h.a.t.c.h | [Blog: deadlight.boo](https://deadlight.boo) | [Ko-fi](https://ko-fi.com/gnarzilla)

## Stats

![Gnarzilla's GitHub Stats](https://github-readme-stats-five-chi-99.vercel.app/api?username=gnarzilla&show_icons=true&theme=radical&hide_border=true)

![Top Languages](https://github-readme-stats-five-chi-99.vercel.app/api/top-langs/?username=gnarzilla&layout=compact&theme=radical&hide_border=true&hide=python)
