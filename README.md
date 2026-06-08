# thatch

I build open-source tools for resilient, user-owned networking: proxies, mesh gateways, tiny publishing systems, and local-first security tools.

Building the internet for the apocalypse: update your blog from a can on a string from the smoldering rubble.

**Deadlight** is an ecosystem for publishing, proxying, and routing across unreliable networks — mesh, satellite, mobile, offline-first, and hostile connectivity included.

The stack has three layers: transport (`deadlight-proxy` and `deadmesh` bridge HTTP/SOCKS/SMTP/LoRa), security (`vault.deadlight` handles credentials without network dependency), and application (`blog.deadlight` publishes content from anywhere). Each component works standalone, but they are designed to thrive together.

## Deadlight Ecosystem
Modular tools for user sovereignty and freedom from centralized cloud services / commercialized network infrastructure. Taking back the internet one paywall at a time. 

- **[blog.deadlight](https://github.com/gnarzilla/blog.deadlight)** (JS, ★ 14): <10KB pages, email posting. [Demo](https://deadlight.boo)
- **[deadlight-proxy](https://github.com/gnarzilla/deadlight-proxy)** (C, ★ 10): Multi-protocol proxy with plugins, REST API, Android app, and optional VPN gateway.
- **[deadmesh](https://github.com/gnarzilla/deadmesh)** (C, ★ 90): LoRa-to-internet gateway. [Project site](https://deadmesh.boo)
- **[deadlight-bootstrap](https://github.com/gnarzilla/deadlight-bootstrap)** (JS, ★ 17): Lightweight web framework starter for Cloudflare Workers + D1.  [Demo](https://v1.deadlight.boo)
- **lib.deadlight** (JS+C): Shared libs and umbrella platform.
- **vault.deadlight** (C): Local encrypted credential store for CLI/proxies. Offline-friendly, integrates with proxy.deadlight. (MVP in progress)

## Live

<img src="https://deadlight.boo/apple-touch-icon.png" width="32" height="32" alt="Deadlight Logo">  [deadlight](https://deadlight.boo) - Main platform demo

<img src="https://deadmesh.boo/apple-touch-icon.png" width="32" height="32" alt="Deadmesh Logo"> [deadmesh](https://deadmesh.boo) - LoRa gateway project blog

<img src="https://thatch-dt.deadlight.boo/apple-touch-icon.png" width="32" height="32" alt="Thatch Logo"> [thatch](https://thatch-dt.deadlight.boo) - Zero-JS instance with use case examples

<img src="https://mobile.deadlight.boo/apple-touch-icon.png" width="32" height="32" alt="Mobile.Deadlight Logo"> [deadroid](https://mobile.deadlight.boo) - Android deployed instance via Termux

<img src="https://threat-level-midnight.deadlight.boo/apple-touch-icon.png" width="32" height="32" alt="Threat Level Midnight Logo">  [threat-level-midnight](https://threat-level-midnight.deadlight.boo) - Federation testing instance

## Deadlight Proxy Android App

<table>
  <tr>
    <td width="40%" align="center" valign="top">
      <img src="https://raw.githubusercontent.com/gnarzilla/deadlight-proxy/main/src/assets/app/deadlight-proxy-wsettings-1.1.7.gif" width="260" alt="GuillotineMode">
      <img src="https://raw.githubusercontent.com/gnarzilla/deadlight-proxy/main/src/assets/app/android-tablet-color-notif.gif" width="260" alt="Android App - Curl tests in tablet">
    </td>
    <td width="60%" valign="middle" align="center">
      <h3>Android APK Available Now</h3>
      <p>Run <code>deadlight-proxy</code> natively on your mobile device or tablet. Features real-time traffic visibility, protocol auto-detection, and a low-footprint local proxy UI right from your phone.</p>
      <br />
      <a href="https://ko-fi.com/s/bc2cb7c2ee" target="_blank">
        <img src="https://raw.githubusercontent.com/gnarzilla/blog.deadlight/main/src/assets/apple-touch-icon/App-Store-Logo-transp.png" width="120" alt="Download Deadlight Proxy">
      </a>
      &nbsp;&nbsp;
      <a href="https://play.google.com/store/apps/details?id=boo.deadlight.proxy">
        <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" height="60" alt="Get it on Google Play">
      </a>
    </td>
  </tr>
</table>

Stack: JS/C, SMTP/SOCKS/LoRa, Wrangler/Markdown.

## Contact
Email: gnarzilla@deadlight.boo | Discord: t.h.a.t.c.h | [Blog: deadlight.boo](https://deadlight.boo) | [Ko-fi](https://ko-fi.com/gnarzilla)

