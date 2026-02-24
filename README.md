## Hi there 👋

I'm James — a developer building tools around **Bitcoin** and **web infrastructure monitoring**. Here's what I'm working on:

---

### 🔍 BitSleuth — Bitcoin Analysis & Wallet

> **Org:** [BitSleuthAI](https://github.com/BitSleuthAI) &nbsp;|&nbsp; **Web:** [bitsleuth.ai](https://www.bitsleuth.ai)

Two projects under the BitSleuth name — a web-based wallet analyzer and an open-source mobile wallet.

#### 📊 Wallet Analyzer &nbsp;•&nbsp; [app.bitsleuth.ai](https://app.bitsleuth.ai)

A web app for investigating Bitcoin wallet addresses using AI. Paste an address and get:

- Transaction flow graphs, balance history charts, and fund-flow maps
- Plain-language AI answers to questions like *"Where did these coins come from?"*
- OPSEC risk detection — flags things like address reuse and peel chains
- On-chain privacy risk reports

No sign-up required. Currently free while in beta.

#### 📱 BitSleuth Wallet &nbsp;•&nbsp; [Source Code](https://github.com/BitSleuthAI/Wallet) &nbsp;•&nbsp; iOS & Android

A non-custodial Bitcoin wallet built with React Native, Expo, and TypeScript.

- Self-custody — recovery phrase generated and encrypted on-device; keys never leave the phone
- BIP32/39/84 with Native SegWit (Bech32) addresses
- Coin control — view, select, and freeze individual UTXOs
- RBF and CPFP fee bumping
- Biometric auth, PIN, passkey/WebAuthn, auto-lock
- Multiple wallets with custom colour themes
- No accounts, no tracking, no analytics
- Open source (AGPL-3.0)

---

### 📡 Pingara — Website Monitoring

> **Org:** [Pingara](https://github.com/Pingara) &nbsp;|&nbsp; **Web:** [pingara.io](https://www.pingara.io)

A monitoring platform that tracks uptime, performance, and SSL certificate validity for websites and services.

- HTTP/HTTPS endpoint checks at configurable intervals (30s – 60min) with keyword and status-code validation
- Multi-region monitoring (US, EU, APAC) with quorum-based status to reduce false positives
- Alerts via Email, Slack, and Webhooks — supports escalation and deduplication
- Latency dashboards (p50/p95/p99), uptime/SLA tracking, and historical trends
- SSL certificate expiry notifications
- Apdex scoring with configurable thresholds
- AI-assisted root-cause hints based on DNS, TCP, and TLS timing
- Public status pages for communicating service health

Has a free tier and a paid plan — details on the website.

---

### 📬 Get in Touch

- 🐛 **Bug reports:** Open an issue in the relevant repo
- 💡 **Ideas & feedback:** [BitSleuth Discussions](https://github.com/BitSleuthAI/.github/discussions)
