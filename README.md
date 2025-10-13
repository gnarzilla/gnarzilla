# thatch

I develop with a focus on secure, performant, and privacy-focused applications deployed at the edge. My work primarily involves the Deadlight ecosystem, a set of open-source tools for modular web platforms, multi-protocol proxies, and edge-native libraries, using Cloudflare Workers, Tailscale and lightweight services. These tools emphasize zero-configuration setups, global scalability, and security. User empowerment is my core design principle. 

My public repositories are available at [github.com/gnarzilla](https://github.com/gnarzilla). For a detailed overview of Deadlight, see my blog post: [What is Deadlight?](https://deadlight.boo/post/what-is-deadlight) (September 18, 2025).

## Deadlight Ecosystem

Deadlight provides a way to maintain a personal online presence, such as a blog, email management, and privacy controls without requiring always-on servers or complex hosting. It addresses challenges like technical setup for blogging, email control, and privacy trade-offs.

The system consists of:
- **blog.deadlight**: A secure blog platform on Cloudflare Workers, with global distribution for low-latency access.
- **proxy.deadlight**: A network proxy for protocol bridging (e.g., SMTP, IMAP/S, SOCKS4/5), now including VPN gateway functionality. It runs locally as needed.
- **lib.deadlight**: Shared libraries for authentication, database models, UI components, and utilities across the ecosystem.

The umbrella project is **edge.deadlight**, which integrates these components into a cohesive platform.

Benefits include no vendor lock-in, minimal costs for basic use, and extensibility for developers. Start with a simple blog deployment and add features like email integration or federation as required.

## Repositories

- **[edge.deadlight](https://github.com/gnarzilla/edge.deadlight)**  
  A production-ready edge platform combining modular site frameworks with proxy management. Built for performance, privacy, and scalability on Cloudflare.  
  *Stars: 0* | *Forks: 0* | *Languages: JavaScript, C*

- **[blog.deadlight](https://github.com/gnarzilla/blog.deadlight)**  
  A modular, security-hardened blog platform with integrated multi-protocol proxy management. Supports email federation.  
  *Stars: 3* | *Forks: 1* | *Language: JavaScript*  
  [Live Demo](https://deadlight.boo) | [Getting Started](https://deadlight.boo/post/47) | [Use Cases](https://thatch-dt.deadlight.boo/post/use-cases)

- **[proxy.deadlight](https://github.com/gnarzilla/proxy.deadlight)**  
  A high-performance network proxy serving as a stateless protocol bridge, including VPN gateway support. Connects TCP protocols to stateless systems.  
  *Stars: 0* | *Forks: 0* | *Language: C*

- **[lib.deadlight](https://github.com/gnarzilla/lib.deadlight)**  
  A modular, edge-native library providing core utilities for the Deadlight ecosystem.  
  *Stars: 0* | *Forks: 0* | *Languages: JavaScript, C*

- **[deadlight-bootstrap](https://github.com/gnarzilla/deadlight-bootstrap)**  
  A lightweight web framework on Cloudflare Workers with authentication and D1 integration. Suitable for simple sites.  
  *Stars: 13* | *Forks: 1* | *Language: JavaScript*  
  [Live Demo (v1)](https://v1.deadlight.boo)

  - **[Guardian](https://github.com/gnarzilla/guardian)**  
  Git User Authentication & Repository Development Interface Assistant & Navigator.
  *Stars: 1* | | *Language: Python*  

All repositories are open-source under permissive licenses. Contributions via issues or pull requests are welcome.

## Live Demos

[![D E A D L I G H T](https://deadlight.boo/favicon.ico)](https://deadlight.boo) | 
[D E A D L I G H T](https://deadlight.boo): Main blog platform with proxy integration

[THREAT LEVEL MIDNIGHT](https://threat-level-midnight.deadlight.boo): Isolated deployment for testing federation.

[![thatch-dt](https://thatch-dt.deadlight.boo/favicon.ico)](https://thatch-dt.deadlight.boo) | [thatch's blog](http://thatch-dt.deadlight.boo): Instance with use case examples.

`v1.deadlight.boo` [v1.deadlight.boo](https://v1.deadlight.boo): Legacy bootstrap version.


These demonstrate features like secure authentication, protocol bridging, and global delivery.


## Skills and Technologies

- **Languages:** JavaScript (Node.js), C
- **Platforms:** Cloudflare Workers, Pages, D1, Tailscale
- **Tools:** Wrangler CLI, GLib, JWT, Markdown rendering
- **Areas:** Edge computing, network proxies, security (CSRF/XSS protection, TLS), federation (email/ActivityPub), serverless deployments

## GitHub Stats

![Gnarzilla's GitHub Stats](https://github-readme-stats.vercel.app/api?username=gnarzilla&show_icons=true&theme=radical&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=gnarzilla&layout=compact&theme=radical&hide_border=true&hide=python)

## Contact

- **GitHub:** [@gnarzilla](https://github.com/gnarzilla)
- **Email:** gnarzilla@deadlight.boo
- **Blog:** See demos above

I am open to discussions on edge technologies or collaborations on Deadlight.
