### Hi, I'm Christian 👋

Lead Software Engineer on the Email Platforms team at [Klaviyo](https://klaviyo.com). 20+ years in
backend development, distributed systems, databases, systems operations, and networking, with
stints leading teams for SaaS, AI/ML, and data platforms. Based in Boston, MA.

- 🔭 Currently building systems that deliver email reliably at massive scale, at Klaviyo
- 🛠 Previously: Director of Engineering at DataRobot (MLOps & Governance), CTO/co-founder of
  Ubivox (newsletter platform)
- 🌱 Spare-time projects mostly live in the SMTP/DNS/networking space, see below
- 📫 [christian@technobabble.dk](mailto:christian@technobabble.dk) ·
  [linkedin.com/in/joergensen](https://linkedin.com/in/joergensen) ·
  [technobabble.dk](https://technobabble.dk)

### Languages & tools

![Go](https://img.shields.io/badge/Go-161b22?style=flat-square&logo=go&logoColor=3fb950)
![Rust](https://img.shields.io/badge/Rust-161b22?style=flat-square&logo=rust&logoColor=3fb950)
![Python](https://img.shields.io/badge/Python-161b22?style=flat-square&logo=python&logoColor=3fb950)
![JavaScript](https://img.shields.io/badge/JavaScript-161b22?style=flat-square&logo=javascript&logoColor=3fb950)
![Kubernetes](https://img.shields.io/badge/Kubernetes-161b22?style=flat-square&logo=kubernetes&logoColor=3fb950)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-161b22?style=flat-square&logo=postgresql&logoColor=3fb950)
![WireGuard](https://img.shields.io/badge/WireGuard-161b22?style=flat-square&logo=wireguard&logoColor=3fb950)

### Things I maintain

Hobby projects, outside of work, just for fun.

**[Conduit](https://conduit.email)**: self-hosted email-to-webhook gateway built on `smtpd`.
Inbound mail becomes an HTTP POST; the webhook's response maps back to an SMTP status so the
sending server retries natively.

**[ZeroDrop](https://zerodrop.app)**: free, multi-location uptime monitoring. Go control plane
coordinates distributed agents over a WireGuard mesh, probing HTTP/TCP/TLS and reaching consensus
before alerting.

**[Doctor Whois](https://doctorwhois.net)**: a small SPA + REST API of network and crypto tools.

| Package | Description |
| --- | --- |
| [smtpd](https://github.com/chrj/smtpd) | Build SMTP servers with STARTTLS, auth, XCLIENT, HELO/RCPT/DATA checks |
| [pflog](https://github.com/chrj/pflog) | Parse Postfix mail logs into Go structures |
| [wgnet](https://github.com/chrj/wgnet) | Build user-space services inside WireGuard VPNs |
| [ssrf](https://github.com/chrj/ssrf) | SSRF prevention for `http.Transport` |
| [keyrate](https://github.com/chrj/keyrate) | Keyed rate limiters (per-user, per-IP, ...) based on `x/time/rate` |
| [diggity](https://github.com/chrj/diggity) | DNS health checker: delegation, TTLs, DNSSEC chain of trust, cross-server answers |
| [vanguard](https://github.com/chrj/vanguard) | Prometheus black-box exporter (HTTP/TCP/SSH/SMTP) served over WireGuard |
| [ircbot](https://github.com/chrj/ircbot) | Async IRC bot framework for Rust, powered by Tokio and proc macros |
| [dmarc-report-parser](https://github.com/chrj/dmarc-report-parser) | Parse DMARC aggregate feedback reports (Rust lib + CLI) |
| [prometheus-dnssec-exporter](https://github.com/chrj/prometheus-dnssec-exporter) | Monitor DNSSEC / RRSIG expiration |
| [prometheus-ssl-exporter](https://github.com/chrj/prometheus-ssl-exporter) | Monitor SSL certificate expiration and connectivity |

More at [technobabble.dk](https://technobabble.dk).
