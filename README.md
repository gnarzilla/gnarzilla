# thatch

Building the internet for the apocalypse: Update your blog from a can on a string from the smoldering rubble.

Secure, performant, privacy-focused apps in the **Deadlight** ecosystem: open-source tools for resilient web platforms on mesh/satellite/spotty networks. User sovereignty first.

The Deadlight stack has three layers: transport (proxy.deadlight bridges protocols like SMTP/SOCKS/LoRa), security (vault.deadlight handles credentials without network dependency), and application (blog.deadlight publishes content from anywhere). Each component works standalone but thrives together.

## Deadlight Ecosystem
Modular tools for blogging/email/comms without always-on servers. Optimized for slow links, batteries, text terminals.

- **blog.deadlight** (JS, ★ 14): <10KB pages, email posting. [Demo](https://deadlight.boo)
- **deadlight-proxy** (C, ★ 7): HTTP/HTTPS/SMTP/IMAP/FTP/SOCKS bridge + VPN. 

<table>
  <tr>
    <td width="40%" align="center" valign="top">
      <img src="https://raw.githubusercontent.com/gnarzilla/deadlight-proxy/main/src/assets/app/deadlight-app-ui-v1.1.2.gif" width="320" alt="Android App Curl & Browser Tests">
      <img src="https://raw.githubusercontent.com/gnarzilla/deadlight-proxy/main/src/assets/app/UI_v1.1.2_tablet.gif" width="320" alt="Android App - Curls tests in tablet">
    </td>
    <td width="60%" valign="middle">
      <h3>Android APK Available Now</h3>
      <p>Run <code>deadlight-proxy</code> natively on your mobile device or tablet. Features real-time traffic inspection, protocol auto-detection, and low-footprint background routing right from your phone.</p>
      <br />
      <a href="https://ko-fi.com/s/bc2cb7c2ee" target="_blank">
        <img src="https://raw.githubusercontent.com/gnarzilla/blog.deadlight/main/src/assets/apple-touch-icon/App-Store-Logo-transp.png" width="120" alt="Download Deadlight Proxy">
      </a>
    </td>
  </tr>
</table>

- **deadmesh** (C, ★ 56): LoRa-to-internet gateway. [Project site](https://deadmesh.boo)
- **deadlight-bootstrap** (JS, ★ 17): Lightweight web framework starter for Cloudflare Workers + D1.  [Demo](https://v1.deadlight.boo)
- **lib/edge.deadlight** (JS+C): Shared libs and umbrella platform.
- **vault.deadlight** (C): Local encrypted credential store for CLI/proxies. Offline-friendly, integrates with proxy.deadlight. (MVP in progress)

## Live

<img src="https://deadlight.boo/apple-touch-icon.png" width="32" height="32" alt="Deadlight Logo">  [deadlight](https://deadlight.boo) - Main platform demo

<img src="https://deadmesh.boo/apple-touch-icon.png" width="32" height="32" alt="Deadmesh Logo"> [deadmesh](https://deadmesh.boo) - LoRa gateway project blog

<img src="https://thatch-dt.deadlight.boo/apple-touch-icon.png" width="32" height="32" alt="Thatch Logo"> [thatch](https://thatch-dt.deadlight.boo) - Zero-JS instance with use case examples

<img src="https://mobile.deadlight.boo/apple-touch-icon.png" width="32" height="32" alt="Mobile.Deadlight Logo"> [deadroid](https://mobile.deadlight.boo) - Android deployed instance via Termux

<img src="https://threat-level-midnight.deadlight.boo/apple-touch-icon.png" width="32" height="32" alt="Threat Level Midnight Logo">  [threat-level-midnight](https://threat-level-midnight.deadlight.boo) - Federation testing instance

<details>
     <summary>Archive</summary>
       
<img src="https://deadmesh.deadlight.boo/apple-touch-icon.png" width="32" height="32">[deadmesh](https://deadmesh.deadlight.boo) - LoRa gateway project blog (deadlight subdomain)

[v1.deadlight](https://v1.deadlight.boo) - Legacy bootstrap framework

</details>

These demonstrate: sub-10 KB page weights, text-only client compatibility, global edge distribution, secure authentication, real-world resilience.

## Stack
Optimize for reality: Intermittent connectivity, scarce power, resilience > features.

- Edge-first (Android/LocalOnly, Cloudflare Workers/D1)
- Minimal deps, no JS required
- C for networking, JS for serverless

Stack: JS/C, SMTP/SOCKS/LoRa, Wrangler/Markdown.

## Contact
Email: gnarzilla@deadlight.boo | Discord: t.h.a.t.c.h | [Blog: deadlight.boo](https://deadlight.boo) | [Ko-fi](https://ko-fi.com/gnarzilla)

