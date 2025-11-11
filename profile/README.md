<div align="center">

# Render Network OS

**Building the Infrastructure for the Creator Economy**

[![Website](https://img.shields.io/badge/Website-rendernet.work-blue?style=for-the-badge)](https://rendernet.work)
[![Discord](https://img.shields.io/badge/Discord-Join%20Us-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/rendernet)
[![Twitter](https://img.shields.io/badge/Twitter-Follow-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/rendernetwork)

</div>

---

## 🌟 Our Mission

We're building open-source infrastructure that empowers creators to monetize their work, prove their value, and build sustainable businesses—without platform lock-in, high fees, or complex integrations.

**The Vision:** A world where any creator can accept payments anywhere, verify genuine engagement, and share revenue transparently—all powered by decentralized technology that puts creators first.

---

## 🏗️ What We Build

### 555x402: Universal Payment Infrastructure

A Solana-native suite enabling **verifiable attention** and **programmable payments** for the modern internet.

**Three Core Protocols:**

#### 💰 AGG (Payment Aggregator)
*Accept payments from anyone, anywhere, instantly*

- **x402 Protocol**: Pay-per-request API access using HTTP 402 "Payment Required"
- **Multi-Facilitator Routing**: Automatically selects optimal payment provider (PayAI, Conduit, or direct Solana)
- **Instant Settlement**: Sub-2-second transaction finality on Solana
- **Crypto + Fiat**: USDC, SOL, and credit card support (fiat converts to on-chain USDC)
- **0.5-1% Fees**: 10-100x cheaper than traditional payment processors

**Use Cases:** API monetization, AI agent payments, content paywalls, microtransactions

#### 🎯 VAP (Verifiable Attention Protocol)
*Earn rewards for real, verified attention*

- **Cryptographic Proof**: Ed25519 signature-based attention verification
- **Real-Time Rewards**: Instant micro-payments for genuine engagement
- **State Channels**: Off-chain accumulation with on-chain settlement
- **Platform Agnostic**: Works on any website, app, or streaming platform

**Use Cases:** Watch-to-earn video platforms, read-to-earn articles, listen-to-earn podcasts, play-to-earn games

#### 🔗 Hyperlink (Universal Payment Links)
*One link to accept payments everywhere*

- **Username Support**: Pretty URLs like `rendernet.work/@alice`
- **Embedded Wallets**: Recipients don't need existing crypto wallet
- **Shareable Anywhere**: Twitter, Discord, WhatsApp, QR codes, email
- **No Platform Integration**: Works without API access or partnerships
- **Analytics Built-In**: Track clicks, conversions, earnings

**Use Cases:** Creator tips, freelancer invoices, event tickets, donations, peer-to-peer payments

---

## 🚀 Technology Stack

**Built for Scale, Security, and Speed**

### Blockchain
- **Solana**: 400ms finality, $0.00025 transaction fees
- **Smart Contracts**: Anchor framework for safety and auditability
- **SPL Tokens**: Native USDC, SOL, and custom token support

### Backend Services
- **Rust**: High-performance payment routing and settlement
- **Go**: Low-latency API gateway and session management
- **Node.js/TypeScript**: Indexing, analytics, and integrations

### Infrastructure
- **Kubernetes (DOKS)**: Auto-scaling microservices on DigitalOcean
- **Redpanda**: Kafka-compatible streaming for real-time events
- **PostgreSQL**: Transactional data integrity
- **Redis**: Sub-millisecond caching and state management

### Developer Tools
- **TypeScript SDKs**: `@555x402/agg`, `@vap/sdk`, `@555x402/hyperlink`
- **Go Packages**: Coming soon
- **Rust Crates**: Coming soon
- **Comprehensive Docs**: API references, guides, examples

---

## 🌍 Supporting the x402 Ecosystem

We're committed to advancing the [x402 protocol](https://x402.org)—an open standard for internet-native payments developed by Coinbase and Cloudflare.

**Our Contributions:**
- ✅ **Multi-facilitator aggregation**: Route payments through best provider automatically
- ✅ **Terminology standardization**: Universal sender/recipient model (not merchant/customer)
- ✅ **Open-source implementations**: Reference implementations for Solana x402
- ✅ **Developer-first SDKs**: Make x402 adoption trivial
- ✅ **Cross-chain ready**: Architecture supports multiple blockchains

**x402 Partners We Integrate:**
- [PayAI](https://payai.network) - AI agent micropayments
- [Conduit](https://getconduit.io) - Gasless payment facilitator
- Corbits, Crossmint, and more coming soon

---

## 🤖 Artificial Intelligence Integration

We're building infrastructure that enables **AI agents to transact autonomously**:

**For AI Developers:**
- Pay-per-use APIs without subscriptions
- Micropayments as low as $0.001
- No user accounts or credit cards
- Instant settlement (no monthly billing cycles)

**AI Agent Use Cases:**
- Access premium data APIs on-demand
- Pay for compute resources dynamically
- Buy cloud services programmatically
- Transact peer-to-peer without human intervention

**Technical Enablement:**
- RESTful APIs with standard HTTP 402 responses
- Webhook notifications for async confirmation
- Idempotent requests for reliability
- Automatic retry and fallback logic

---

## 🎨 The Sustainable Creator Economy

**Our North Star:** Every creator should own their audience, control their revenue, and build without platform dependency.

### Problems We Solve

**Traditional Platforms:**
- ❌ 20-50% platform fees
- ❌ Opaque algorithms
- ❌ No revenue portability
- ❌ Platform lock-in
- ❌ Delayed payouts (30-90 days)

**555x402 Alternative:**
- ✅ 0.5-1% total fees
- ✅ Cryptographic proof of engagement
- ✅ Portable payment links (work anywhere)
- ✅ Platform-agnostic (own your audience)
- ✅ Instant settlement (2 seconds)

### Real-World Impact

**For Creators:**
- Accept payments in 5 minutes (no complex integration)
- Keep 99%+ of revenue (minimal fees)
- Verify genuine engagement (no bot manipulation)
- Build sustainable income streams

**For Audiences:**
- Support creators directly
- Earn rewards for real attention
- Privacy-preserving (no data exploitation)
- True ownership (crypto wallets)

**For Platforms:**
- Monetization layer without billing infrastructure
- Fraud-resistant reward systems
- Revenue share without intermediaries
- Developer-friendly APIs

---

## 📦 Open Source Repositories

### Core Infrastructure

| Repository | Description | Language | Status |
|------------|-------------|----------|--------|
| [555x402-agg-facilitator-router](https://github.com/Render-Network-OS/555x402-agg-facilitator-router) | Payment aggregation and facilitator routing | Rust | ✅ Production |
| [555x402-api-gateway](https://github.com/Render-Network-OS/555x402-api-gateway) | Public API gateway with auth and rate limiting | Go | ✅ Production |
| [555x402-hyperlink-link-service](https://github.com/Render-Network-OS/555x402-hyperlink-link-service) | Payment link management and tracking | Go | ✅ Production |
| [555x402-session-manager](https://github.com/Render-Network-OS/555x402-session-manager) | VAP session orchestration and signature verification | Go | ✅ Production |
| [555x402-agg-indexer](https://github.com/Render-Network-OS/555x402-agg-indexer) | Settlement indexing and status tracking | TypeScript | ✅ Production |
| [555x402-agg-facilitator-watchdog](https://github.com/Render-Network-OS/555x402-agg-facilitator-watchdog) | Facilitator health monitoring and scoring | Go | ✅ Production |

### Developer SDKs

| Package | Description | Downloads | Docs |
|---------|-------------|-----------|------|
| [@555x402/agg](https://github.com/Render-Network-OS/555x402-agg-sdk) | Payment aggregation client for TypeScript/Node | ![npm](https://img.shields.io/npm/dm/@555x402/agg) | [API Ref](https://docs.rendernet.work/sdk/agg) |
| [@vap/sdk](https://github.com/Render-Network-OS/555x402-vap-sdk) | Verifiable attention WebSocket client | ![npm](https://img.shields.io/npm/dm/@vap/sdk) | [Guide](https://docs.rendernet.work/sdk/vap) |
| [@555x402/hyperlink](https://github.com/Render-Network-OS/555x402-hyperlink) | Payment link React components | ![npm](https://img.shields.io/npm/dm/@555x402/hyperlink) | [Components](https://docs.rendernet.work/sdk/hyperlink) |
| [@555x402/solana402-express](https://github.com/Render-Network-OS/555x402-solana-express) | Express middleware for pay-per-request APIs | ![npm](https://img.shields.io/npm/dm/@555x402/solana402-express) | [Middleware](https://docs.rendernet.work/sdk/express) |

### Applications

| Repository | Description | Tech Stack |
|------------|-------------|------------|
| [555x402-hyperlink-landing](https://github.com/Render-Network-OS/555x402-hyperlink-landing) | Modern payment link landing page | Next.js 14, Privy, TailwindCSS |
| [555x402-examples](https://github.com/Render-Network-OS/555x402-examples) | Sample applications and integration guides | TypeScript, React |

### Infrastructure & Documentation

| Repository | Description |
|------------|-------------|
| [555x402-infra](https://github.com/Render-Network-OS/555x402-infra) | Kubernetes manifests, Terraform, Helm charts |
| [555x402-docs](https://github.com/Render-Network-OS/555x402-docs) | Comprehensive documentation and guides |

---

## 🎯 Our Principles

### 1. **Open Source First**
All core infrastructure is MIT licensed. No proprietary lock-in. Fork, modify, self-host.

### 2. **Developer Experience**
World-class SDKs with comprehensive docs. Integration in minutes, not weeks.

### 3. **Creators Own Everything**
Your audience, your data, your revenue. We're infrastructure, not a platform.

### 4. **Technically Excellent**
Production-grade: tested, monitored, scalable. Built for real-world use from day one.

### 5. **Economically Sustainable**
Minimal fees (0.5-1%) to support infrastructure. Revenue transparency. No hidden costs.

### 6. **Privacy-Preserving**
Minimal data collection. Cryptographic verification instead of surveillance. User sovereignty.

---

## 🚀 Getting Started

### For Developers

**Quickstart: Accept Payments in 5 Minutes**

```bash
npm install @555x402/agg
```

```typescript
import { AggClient } from '@555x402/agg';

const client = new AggClient(process.env.API_KEY);

app.post('/premium-api', async (req, res) => {
  const payment = req.headers['x-payment'];
  
  if (!payment) {
    return res.status(402).json({ 
      error: 'Payment required',
      price: { amount: 0.10, asset: 'USDC' }
    });
  }
  
  await client.verifyAndSettle(payment, {
    amount: 0.10,
    mint: USDC_MINT,
    recipient: YOUR_WALLET
  });
  
  res.json({ data: 'premium content' });
});
```

**Resources:**
- 📚 [Documentation](https://docs.rendernet.work)
- 🎓 [Tutorials](https://docs.rendernet.work/tutorials)
- 💬 [Discord Community](https://discord.gg/rendernet)
- 🐛 [Report Issues](https://github.com/Render-Network-OS/555x402-infra/issues)

### For Creators

**Create Your Payment Link:**

1. Visit [555.rendernet.work](https://555.rendernet.work)
2. Choose your @username
3. Connect wallet (or create embedded wallet)
4. Share your link anywhere

**Features:**
- Accept crypto + fiat payments
- No wallet required for payers
- Instant settlement
- Track all payments and analytics
- Free to start

### For Contributors

We welcome contributions! See our [Contributing Guide](https://github.com/Render-Network-OS/555x402-infra/blob/main/CONTRIBUTING.md) for:
- Development workflow
- Branching strategy
- Code standards
- Testing requirements

**Good First Issues:** Check repositories with the `good-first-issue` label.

---

## 📊 Platform Stats

<div align="center">

| Metric | Value |
|--------|-------|
| **Transaction Speed** | <2 seconds |
| **Platform Fees** | 0.5-1% |
| **API Latency (p95)** | <500ms |
| **Uptime** | 99.9% SLA |
| **Supported Tokens** | USDC, SOL, + custom SPL |

</div>

---

## 🗺️ Roadmap

### Q4 2025 - Foundation ✅
- [x] Core infrastructure deployed
- [x] AGG payment routing operational
- [x] Hyperlink payment links live
- [x] Developer SDKs published
- [x] x402 facilitator integration (PayAI)

### Q1 2026 - Expansion
- [ ] VAP production deployment
- [ ] Mobile SDKs (React Native)
- [ ] Multi-chain support (Ethereum, Base)
- [ ] Fiat on-ramp integration (Stripe, Circle)
- [ ] Creator dashboard and analytics

### Q2 2026 - Ecosystem
- [ ] Marketplace for x402 APIs
- [ ] Creator monetization templates
- [ ] AI agent SDK extensions
- [ ] Community-driven facilitators
- [ ] Grants program for ecosystem projects

### Q3 2026 - Scale
- [ ] 1M+ transactions per day
- [ ] 100+ integrated facilitators
- [ ] 10,000+ creators earning
- [ ] Multi-region deployment
- [ ] Enterprise support tier

---

## 🤝 Partnerships & Integrations

**x402 Ecosystem:**
- [PayAI](https://payai.network) - AI micropayment facilitator
- [Conduit](https://getconduit.io) - Instant settlement provider
- [Crossmint](https://crossmint.com) - Wallet infrastructure
- [Helius](https://helius.xyz) - Solana RPC provider

**Infrastructure Partners:**
- [DigitalOcean](https://digitalocean.com) - Kubernetes hosting
- [Cloudflare](https://cloudflare.com) - CDN and DDoS protection
- [Privy](https://privy.io) - Embedded wallet provider

**Open Source Contributors:**
- [Solana Foundation](https://solana.org)
- [Anchor Framework](https://anchor-lang.com)
- [Redpanda](https://redpanda.com)

---

## 💡 Why Open Source?

**Transparency:** Every line of code is public. Audit our security, understand our architecture, trust the system.

**Portability:** Fork and self-host. No vendor lock-in. Your infrastructure, your rules.

**Innovation:** Community contributions make us better. Shared learnings accelerate the ecosystem.

**Sustainability:** Open source prevents monopolies. Compete on service quality, not proprietary moats.

**Alignment:** We succeed when creators succeed. Open source aligns incentives for the long term.

---

## 📈 By the Numbers

**Developer Adoption:**
- 13 open-source repositories
- 4 production-ready SDKs
- 2,500+ lines of documentation
- 600+ lines of test coverage
- 10+ workflow automations

**Technical Excellence:**
- 5/6 microservices operational
- 99.9% uptime SLA
- <500ms API latency (p95)
- 1000+ RPS load tested
- Zero-downtime deployments

**Creator Economy Impact:**
- Instant settlements (vs 30-90 day traditional)
- 99%+ revenue kept (vs 50-80% on platforms)
- Universal payment links (vs platform-specific)
- Cryptographic engagement proof (vs opaque algorithms)

---

## 🛠️ Technical Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                    555x402 Platform                          │
├─────────────────────────────────────────────────────────────┤
│                                                              │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐      │
│  │     AGG      │  │     VAP      │  │  Hyperlink   │      │
│  │   Payment    │  │  Attention   │  │   Payment    │      │
│  │  Aggregator  │  │   Protocol   │  │    Links     │      │
│  └──────┬───────┘  └──────┬───────┘  └──────┬───────┘      │
│         │                  │                  │               │
│         └──────────────────┼──────────────────┘              │
│                            │                                  │
│                   ┌────────▼────────┐                        │
│                   │   API Gateway   │                        │
│                   └────────┬────────┘                        │
│                            │                                  │
│         ┌──────────────────┼──────────────────┐             │
│         │                  │                  │              │
│    ┌────▼────┐      ┌─────▼─────┐      ┌────▼────┐        │
│    │ Kafka   │      │ PostgreSQL │      │  Redis  │        │
│    │(Redpanda│      │            │      │         │        │
│    └─────────┘      └───────────┘      └─────────┘        │
│                                                              │
│                   ┌────────────────┐                        │
│                   │ Solana Mainnet │                        │
│                   │  (Settlement)  │                        │
│                   └────────────────┘                        │
└─────────────────────────────────────────────────────────────┘
```

**Key Design Decisions:**
- **Microservices**: Independent scaling and deployment
- **Event-Driven**: Kafka for reliable message delivery
- **Facilitator Abstraction**: Pluggable payment providers
- **Stateless Services**: Horizontal scaling without coordination
- **Observability-First**: Prometheus metrics, distributed tracing

---

## 🔐 Security & Compliance

**Security Practices:**
- ✅ Automated security scanning (Trivy)
- ✅ Dependency auditing
- ✅ HMAC webhook signatures
- ✅ Rate limiting and DDoS protection
- ✅ Secrets management (never in code)
- ✅ Regular penetration testing

**Compliance:**
- GDPR-ready (minimal data collection)
- SOC 2 preparation underway
- Open-source auditability
- Transparent operations

---

## 🌱 Join the Movement

**We're building infrastructure for a better internet—one where creators thrive, users are rewarded, and platforms are utilities, not gatekeepers.**

### Ways to Participate

**Build:**
- Fork our repos and improve them
- Create integrations and tools
- Share your implementation feedback

**Create:**
- Use 555x402 to monetize your work
- Share your success stories
- Help other creators get started

**Contribute:**
- Code contributions (see CONTRIBUTING.md)
- Documentation improvements
- Community support
- Bug reports and feature requests

**Partner:**
- Integrate 555x402 into your platform
- Become an x402 facilitator
- Build on our APIs

### Connect With Us

- 🌐 **Website**: [rendernet.work](https://rendernet.work)
- 📖 **Documentation**: [docs.rendernet.work](https://docs.rendernet.work)
- 💬 **Discord**: [discord.gg/rendernet](https://discord.gg/rendernet)
- 🐦 **Twitter**: [@rendernetwork](https://twitter.com/rendernetwork)
- 📧 **Email**: hello@rendernet.work
- 💼 **Partnerships**: partnerships@rendernet.work

---

## 📜 License

All repositories are licensed under **MIT** unless otherwise specified. See individual repositories for details.

---

<div align="center">

**Building the future of the creator economy, one commit at a time.**

[Get Started](https://docs.rendernet.work) • [Join Discord](https://discord.gg/rendernet) • [Follow Updates](https://twitter.com/rendernetwork)

Made with ❤️ by the Render Network OS team and contributors worldwide

</div>

