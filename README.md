### Hi, I'm Christian 👋

Lead Software Engineer on the Email Platforms team at [Klaviyo](https://klaviyo.com). I have more
than 20 years of experience in backend development, distributed systems, databases, systems
operations, and networking. I also led teams for SaaS, AI/ML, and data platforms. I live in
Boston, MA.

- 🔭 Now: at Klaviyo, I build the systems that deliver email reliably at high volume
- 🛠 Before: Director of Engineering at DataRobot (MLOps and Governance), CTO and co-founder of
  Ubivox (newsletter platform)
- 🌱 My spare-time projects are about SMTP, DNS, and networking. See the list below
- 📫 [christian@technobabble.dk](mailto:christian@technobabble.dk) ·
  [linkedin.com/in/joergensen](https://linkedin.com/in/joergensen) ·
  [technobabble.dk](https://technobabble.dk)

### Languages and tools

![Go](https://img.shields.io/badge/Go-161b22?style=flat-square&logo=go&logoColor=3fb950)
![Rust](https://img.shields.io/badge/Rust-161b22?style=flat-square&logo=rust&logoColor=3fb950)
![Python](https://img.shields.io/badge/Python-161b22?style=flat-square&logo=python&logoColor=3fb950)
![JavaScript](https://img.shields.io/badge/JavaScript-161b22?style=flat-square&logo=javascript&logoColor=3fb950)
![Kubernetes](https://img.shields.io/badge/Kubernetes-161b22?style=flat-square&logo=kubernetes&logoColor=3fb950)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-161b22?style=flat-square&logo=postgresql&logoColor=3fb950)
![WireGuard](https://img.shields.io/badge/WireGuard-161b22?style=flat-square&logo=wireguard&logoColor=3fb950)

### Things I maintain

These are hobby projects outside of work, for fun.

**[Conduit](https://conduit.email)**: a self-hosted gateway from email to webhook, built on
`smtpd`. Conduit converts inbound mail into an HTTP POST request. The response from the webhook
maps to an SMTP status code. Then the remote mail server does its own retries.

**[ZeroDrop](https://zerodrop.app)**: free uptime monitoring from multiple locations. A control
plane in Go controls distributed agents over a WireGuard mesh. The agents test HTTP, TCP, and TLS.
The agents must agree before ZeroDrop sends an alert.

**[Doctor Whois](https://doctorwhois.net)**: a small single-page application and REST API with
network and cryptography tools.

| Package | Description |
| --- | --- |
| [smtpd](https://github.com/chrj/smtpd) | Build SMTP servers with STARTTLS, authentication, XCLIENT, and HELO/RCPT/DATA checks |
| [pflog](https://github.com/chrj/pflog) | Parse Postfix mail logs into Go structures |
| [wgnet](https://github.com/chrj/wgnet) | Build user-space services inside WireGuard VPNs |
| [ssrf](https://github.com/chrj/ssrf) | Prevent SSRF in `http.Transport` |
| [keyrate](https://github.com/chrj/keyrate) | Rate limiters with a key (per user, per IP), based on `x/time/rate` |
| [diggity](https://github.com/chrj/diggity) | DNS health checker: delegation, TTLs, DNSSEC chain of trust, cross-server answers |
| [vanguard](https://github.com/chrj/vanguard) | Prometheus black-box exporter (HTTP/TCP/SSH/SMTP) that operates over WireGuard |
| [ircbot](https://github.com/chrj/ircbot) | Asynchronous IRC bot framework for Rust, built on Tokio and proc macros |
| [dmarc-report-parser](https://github.com/chrj/dmarc-report-parser) | Parse DMARC aggregate feedback reports (Rust library and CLI) |
| [spamhaus-submission](https://github.com/chrj/rust-spamhaus-submission) | Async Rust client for the Spamhaus Submission Portal API |
| [abuse-contact](https://github.com/chrj/rust-abuse-contact) | Find where to report abuse for an IP address or a domain name (Rust) |
| [prometheus-dnssec-exporter](https://github.com/chrj/prometheus-dnssec-exporter) | Monitor DNSSEC and RRSIG expiration |
| [prometheus-ssl-exporter](https://github.com/chrj/prometheus-ssl-exporter) | Monitor SSL certificate expiration and connectivity |

More at [technobabble.dk](https://technobabble.dk).
