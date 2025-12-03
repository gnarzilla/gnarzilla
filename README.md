# thatch

Building the internet for the apocolypse. Update your blog with a can on a string from the smoldering rubble.

I develop secure, performant, privacy-focused applications deployed at the edge under the **Deadlight** ecosystem. A cohesive collection of open-source tools for resilient web platforms, multi-protocol networking, and edge-native infrastructure. These systems are designed for the 80% of the planet that doesn't have datacenter-grade connectivity: mesh networks, satellite links, intermittent connectivity, resource-constrained devices.

Core design principle: **user sovereignty over platform convenience.**

---

## What I'm Building

### Deadlight Ecosystem

A modular platform for maintaining online presence (blogging, email, communications) without requiring always-on servers or reliable connectivity. Built for real-world conditions: slow links, intermittent uptime, hostile networks, resource constraints.

**The problem:** Most web platforms assume fiber, cheap power, and stable connectivity. This excludes billions of users and makes the internet fragile.

**The solution:** Edge-native architecture that works over LoRa mesh, satellite with 2-second latency, 2G mobile, or text-only terminals. Posts are 3-8 KB. Zero JavaScript required. Deployable from a phone. (Achieved via a C-based multi-protocol bridge and serverless JS frontend optimized for minimal payload and caching.)

#### Production Components

**[blog.deadlight](https://github.com/gnarzilla/blog.deadlight)** ⭐ 6  
Cloudflare Workers blog platform optimized for terrible connectivity. <10 KB pages, works in lynx, post via email.  
*JavaScript* · [Live Demo](https://deadlight.boo) · [Getting Started](https://deadlight.boo/post/what-is-deadlight)

**[proxy.deadlight](https://github.com/gnarzilla/proxy.deadlight)**  
High-performance protocol bridge (SMTP/IMAP/SOCKS4/5) + VPN gateway. Connects stateless edge apps to stateful protocols.  
*C*

**[meshtastic.deadlight](https://github.com/gnarzilla/meshtastic.deadlight)** ⭐ 3  
Internet-over-LoRa gateway. Bridge between Meshtastic mesh networks and the public internet.  
*C* · [Project Site](https://meshtastic.deadlight.boo) · [Getting Started](https://meshtastic.deadlight.boo/post/getting-started)

**[lib.deadlight](https://github.com/gnarzilla/lib.deadlight)**  
Shared edge-native libraries: auth, database models, security utilities, UI components.  
*JavaScript + C*

**[edge.deadlight](https://github.com/gnarzilla/edge.deadlight)**  
Umbrella platform integrating all components into a cohesive system.  
*JavaScript + C*

**[deadlight-bootstrap](https://github.com/gnarzilla/deadlight-bootstrap)** ⭐ 14
Lightweight web framework starter for Cloudflare Workers + D1.  
*JavaScript* · [Live Demo](https://v1.deadlight.boo)

---

## Live Deployments

[![D E A D L I G H T](https://deadlight.boo/favicon.ico)](https://deadlight.boo)[deadlight.boo](https://deadlight.boo) - Main platform demo with proxy integration

[![thatch pad](https://thatch-dt.deadlight.boo/favicon.ico)](https://thatch-dt.deadlight.boo)[thatch pad](https://thatch-dt.deadlight.boo) - Zero-JS instance with use case examples

[![mobile.deadlight](https://mobile.deadlight.boo/favicon.ico)](https://mobile.deadlight.boo)[mobile.deadlight](https://mobile.deadlight.boo) - Amdroid deployed instance via Termux

[![meshtastic.deadlight](https://meshtastic.deadlight.boo/favicon.ico)](https://meshtastic.deadlight.boo) [meshtastic.deadlight](https://meshtastic.deadlight.boo) - LoRa gateway project blog

[![threat level midnight](https://threat-level-midnight.deadlight.boo/favicon.ico)](https://threat-level-midnight.deadlight.boo)[threat level midnight](https://threat-level-midnght.deadlight.boo) - Federation testing instance

[v1.deadlight](https://v1.deadlight.boo) - Legacy bootstrap framework

These demonstrate: sub-10 KB page weights, text-only client compatibility, global edge distribution, secure authentication, real-world resilience.

---

## Technical Philosophy

**Optimize for reality, not ideals:**
- Most connectivity is intermittent, high-latency, or expensive
- Power is often scarce (solar, battery-only devices)
- Many users have text-only interfaces (mesh clients, terminal browsers)
- Resilience matters more than features

**Design choices this drives:**
- Edge-first architecture (Cloudflare Workers, D1)
- Minimal dependencies (~8 npm packages for blog.deadlight)
- No build steps where possible
- Zero external requests by default
- Works on ARM64 without emulation (deployable from phones)
- Text content prioritized over media

**Why C + JavaScript:**
- C for protocol bridging, VPN, performance-critical networking
- JavaScript for edge compute, serverless deployments
- Both: auditable, minimal dependencies, portable

---

## Technical Stack

**Languages:** JavaScript (Node.js, edge runtimes), C (GLib, POSIX)  
**Platforms:** Cloudflare Workers, Pages, D1 · Tailscale  
**Infrastructure:** Edge computing, serverless, mesh networking  
**Security:** JWT, CSRF/XSS protection, TLS, rate limiting  
**Protocols:** SMTP/IMAP, SOCKS4/5, HTTP/2, WebSocket, LoRa  
**Tools:** Wrangler CLI, Markdown rendering (marked + DOMPurify)

---

## Current Focus

**Immediate (2025 Q4):**
- Meshtastic integration testing (LoRa → blog publishing)
- Email-to-post workflow stabilization
- Comment system for blog.deadlight
- Federation between Deadlight instances

**Near-term (2026 Q1-Q2):**
- Full proxy dashboard integration
- Meshtastic-native client for posting
- Plugin architecture for blog.deadlight
- Documentation expansion

**Long-term:**
- ActivityPub federation
- HF radio transport layer
- Satellite-optimized protocols
- Offline-first mobile clients

---

## Why This Matters

**The convenient internet is fragile.** It assumes:
- Reliable power grids
- Low-latency fiber connections
- Always-on servers
- Modern browsers with JavaScript
- Cheap, unlimited data

**Most of the world doesn't have this.** And increasingly, even those who do face:
- Natural disasters disrupting infrastructure
- Intentional network shutdowns
- Privacy and surveillance concerns
- Rising costs and platform lock-in

**Deadlight proves you can build differently:**
- Deploy a blog from a PinePhone over 2G
- Post updates via LoRa mesh when conventional internet is down
- Run a personal site with zero ongoing server costs
- Maintain privacy without corporate platforms
- Use email protocols for federation instead of proprietary APIs

It's not about preparing for some hypothetical collapse. It's about building systems that work for **how people actually live** - not how Silicon Valley wishes they lived.

---

## Contributions Welcome

All repositories are open-source under permissive licenses. Areas where help is especially valuable:

- **Testing:** Email workflows on various providers, LoRa gateway deployment scenarios
- **Documentation:** Setup guides, troubleshooting, translations
- **Accessibility:** Testing with screen readers, keyboard navigation
- **Performance:** Optimization for extremely constrained environments
- **Use cases:** Real-world deployment stories and feedback

File issues, open PRs, or reach out directly.

---

## Stats

![Gnarzilla's GitHub Stats](https://github-readme-stats-five-chi-99.vercel.app/api?username=gnarzilla&show_icons=true&theme=radical&hide_border=true)

![Top Languages](https://github-readme-stats-five-chi-99.vercel.app/api/top-langs/?username=gnarzilla&layout=compact&theme=radical&hide_border=true&hide=python)

---

## Contact

- **GitHub:** [@gnarzilla](https://github.com/gnarzilla)
- **Email:** gnarzilla@deadlight.boo
- **Discord**: @t.h.a.t.c.h
- **Blog:** [deadlight.boo](https://deadlight.boo), [thatch pad](https://thatch-dt.deadlight.boo)
- **Support:** [ko-fi.com/gnarzilla](https://ko-fi.com/gnarzilla)

Open to collaboration on edge computing, resilient networking, or related projects.

---
