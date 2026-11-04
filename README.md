# Awesome URL Shortener [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of the best URL shorteners, link management platforms, and self-hosted solutions in 2025.

Whether you're a marketer tracking campaigns, a developer building integrations, or a business looking for branded short links, this guide helps you find the perfect URL shortener for your needs.

## Contents

- [URL Shortener Comparison Table](#url-shortener-comparison-table)
- [Detailed Reviews](#detailed-reviews)
  - [Enterprise & API-First](#enterprise--api-first)
  - [Marketing & Branding Focused](#marketing--branding-focused)
  - [Free & Simple](#free--simple)
  - [Regional Services](#regional-services)
  - [Niche & Specialized](#niche--specialized)
- [Self-Hosted Solutions](#self-hosted-solutions)
- [Deprecated Services](#deprecated-services)
- [How to Choose](#how-to-choose-a-url-shortener)
- [Contributing](#contributing)

---

## URL Shortener Comparison Table

| Service | Free Tier | API | Custom Domains | Analytics | Best For | Rating |
|---------|-----------|-----|----------------|-----------|----------|--------|
| [Dub.co](https://dub.co) | 25 links | Yes | Unlimited | Advanced | Modern teams, Open-source fans | ⭐⭐⭐⭐⭐ |
| [Short.io](https://short.io) | 1,000 links | Yes | 3 domains | Good | Budget-conscious teams | ⭐⭐⭐⭐½ |
| [Rebrandly](https://rebrandly.com) | 10 links | Yes | 1 domain | Advanced | Branding-focused marketers | ⭐⭐⭐⭐ |
| [Bitly](https://bitly.com) | 10 links | Paid | Paid | Advanced | Enterprise, Brand recognition | ⭐⭐⭐⭐ |
| [BL.INK](https://www.bl.ink) | Trial only | Yes | Yes | Enterprise | Large enterprises, Compliance | ⭐⭐⭐⭐ |
| [TinyURL](https://tinyurl.com) | Unlimited | Basic | No | Basic | Quick, no-signup shortening | ⭐⭐⭐½ |
| [Cutt.ly](https://cutt.ly) | 30 links/mo | Limited | Yes | Good | Small marketing teams | ⭐⭐⭐½ |
| [T.LY](https://t.ly) | Yes | Yes | Yes | Good | Browser extension users | ⭐⭐⭐½ |
| [is.gd](https://is.gd) | Unlimited | Yes | No | Basic | Privacy-conscious, Simple use | ⭐⭐⭐ |
| [jo4.io](https://jo4.io) | No (14-day Pro trial) | Full REST API + MCP server | Yes | Advanced | Developers, White-label, API-first apps | ⭐⭐⭐⭐⭐ |

---

## Detailed Reviews

### Enterprise & API-First

#### [jo4.io](https://jo4.io) ⭐⭐⭐⭐⭐

**The API-first URL shortener built for developers.**

| Aspect | Details |
|--------|---------|
| **Market Position** | Growing, developer-focused |
| **UX** | Clean dashboard, fast link creation, intuitive analytics |
| **DX** | Full REST API, MCP server, OpenAPI docs, scoped API keys, webhooks |
| **Pricing** | No free plan • Pro: $16/mo (14-day free trial, card required) • Pro Plus: $48/mo |
| **Standout Features** | White-label support, ownership transfer, bio pages, QR codes, team workspaces |

**Notes:** Unlike competitors that treat APIs as an afterthought, jo4.io was built API-first. White-label option means your customers never see "jo4" branding. Ideal for SaaS products embedding link shortening, agencies serving clients, and developers who want full control.

---

#### [Dub.co](https://dub.co) ⭐⭐⭐⭐⭐

**Modern, open-source link management platform.**

| Aspect | Details |
|--------|---------|
| **Market Position** | Fast-growing since 2022 launch |
| **UX** | Beautiful UI, keyboard shortcuts, AI slug suggestions |
| **DX** | Excellent API, open-source, self-hostable |
| **Pricing** | Free: 25 links • Pro: $24/mo • Enterprise: Custom |
| **Standout Features** | A/B testing, geo-targeting, deep links, referral programs |

**User Reviews:** "Most complete feature set with best DX + UX" Common G2 feedback. Praised for real-time analytics and intuitive interface.

**Notes:** Created by ex-Vercel engineer. Open-source nature appeals to developers. Recent price increase (was $9/mo) may concern budget users. Not yet SOC 2/GDPR compliant, which matters for some enterprises.

---

#### [BL.INK](https://www.bl.ink) ⭐⭐⭐⭐

**Enterprise-grade link management with compliance focus.**

| Aspect | Details |
|--------|---------|
| **Market Position** | Enterprise segment leader |
| **UX** | Feature-rich but complex |
| **DX** | Robust API, CRM integrations |
| **Pricing** | From $48/mo, 21-day trial |
| **Standout Features** | ISO 27001, SOC 2, HIPAA, GDPR compliance, SSO |

**User Reviews:** Valued for compliance certifications and bulk link management. Some report occasional bugs and prefer desktop over mobile UI.

**Notes:** Best choice for regulated industries (healthcare, finance). Overkill for small teams. If you need compliance certifications, BL.INK delivers what Bitly and others don't at lower tiers.

---

### Marketing & Branding Focused

#### [Bitly](https://bitly.com) ⭐⭐⭐⭐

**The most recognized name in URL shortening.**

| Aspect | Details |
|--------|---------|
| **Market Position** | ~19% market share, industry standard |
| **UX** | Polished, well-documented |
| **DX** | Good API, but restricted on lower tiers |
| **Pricing** | Free: 10 links/mo (with ads!) • Core: $35/mo |
| **Standout Features** | Brand recognition, QR codes, link-in-bio |

**User Reviews:** Trusted by enterprises. Free tier complaints: limited to 10 links with interstitial ads. Paid users report 88% traffic growth vs. free users seeing 48% decline.

**Notes:** The "safe choice" for enterprises. Free tier is now essentially unusable for serious work. Custom domains require paid plans. If budget matters, look elsewhere. If you need the brand credibility for stakeholder buy-in, Bitly delivers.

---

#### [Rebrandly](https://rebrandly.com) ⭐⭐⭐⭐

**Branding-first link management.**

| Aspect | Details |
|--------|---------|
| **Market Position** | Strong in marketing segment |
| **UX** | Clean, branding-focused |
| **DX** | Flexible API, good documentation |
| **Pricing** | Free: 10 links • Essentials: $14/mo |
| **Standout Features** | Branded links (39% higher CTR), historical tracking |

**User Reviews:** Scores 9.5/10 for branded shortlinks on G2 (vs. Bitly's 9.3). Strong historical tracking helps analyze long-term performance.

**Notes:** Best for solo marketers and small teams focused on brand consistency. Less suited for developer-heavy workflows. The 39% CTR increase from branded links is well-documented and often pays for itself.

---

#### [Short.io](https://short.io) ⭐⭐⭐⭐½

**Best value for branded links.**

| Aspect | Details |
|--------|---------|
| **Market Position** | Strong in SMB segment |
| **UX** | Clean, straightforward |
| **DX** | Good API, AI domain suggestions |
| **Pricing** | Free: 1,000 links, 50K clicks • Pro: $19/mo |
| **Standout Features** | Custom domains on free tier, generous limits |

**User Reviews:** Praised for exceptional free tier value. Custom domains without paying sets it apart from most competitors.

**Notes:** If you want branded links without commitment, Short.io's free tier is unmatched. Lacks deep enterprise features but covers 90% of use cases. Great stepping stone before committing to paid plans elsewhere.

---

### Free & Simple

#### [TinyURL](https://tinyurl.com) ⭐⭐⭐½

**The original URL shortener, still going strong.**

| Aspect | Details |
|--------|---------|
| **Market Position** | Legacy leader, broad awareness |
| **UX** | Dead simple, no signup required |
| **DX** | Basic API, recently improved |
| **Pricing** | Free unlimited • Pro: $9.99/mo |
| **Standout Features** | No signup needed, unlimited free links |

**User Reviews:** "Reliable, no downtime worries." Analytics could be more detailed. API described as "not bad, just basic."

**Notes:** Perfect for quick, one-off shortening. No-signup flow is unmatched for speed. Lacks advanced features but excels at doing one thing well. If you just need to shorten a URL right now, TinyURL works.

---

#### [Cutt.ly](https://cutt.ly) ⭐⭐⭐½

**Feature-rich free option with reliability concerns.**

| Aspect | Details |
|--------|---------|
| **Market Position** | Popular free alternative |
| **UX** | Modern interface |
| **DX** | Limited API on free tier |
| **Pricing** | Free: 30 links/mo • From $12/mo |
| **Standout Features** | QR codes, link expiration, A/B testing |

**User Reviews:** Praised for features comparable to Bitly at lower cost. However, "three major outages in one week" reported by some users.

**Notes:** Strong feature set undermined by reliability issues. If uptime matters (and it should), consider alternatives. Good for testing features before committing to paid service elsewhere.

---

#### [T.LY](https://t.ly) ⭐⭐⭐½

**Browser-extension focused shortener.**

| Aspect | Details |
|--------|---------|
| **Market Position** | Niche, extension users |
| **UX** | Simple, extension-driven workflow |
| **DX** | Basic API |
| **Pricing** | Free tier available |
| **Standout Features** | Browser extension, smart geo-redirect URLs |

**User Reviews:** Extension makes link creation instant. Limited feature depth compared to full platforms.

**Notes:** Best for users who create links ad-hoc from their browser. Smart URLs with geo-targeting add value. Less suitable for programmatic or bulk use cases.

---

#### [is.gd](https://is.gd) / [v.gd](https://v.gd) ⭐⭐⭐

**Ethical, no-tracking URL shorteners.**

| Aspect | Details |
|--------|---------|
| **Market Position** | Privacy-focused niche |
| **UX** | Minimal, functional |
| **DX** | Simple API |
| **Pricing** | 100% Free |
| **Standout Features** | No ads, no tracking, Wikipedia-approved |

**User Reviews:** Trusted for privacy. 3B+ URLs shortened, 93B+ clicks served. One of few shorteners allowed on Wikipedia.

**Notes:** Same creator runs both. v.gd shows preview before redirect. No branding options, no advanced analytics. Perfect for privacy-conscious users who just need basic shortening.

---

### Regional Services

| Service | Region | Notes |
|---------|--------|-------|
| [bitly.kr](https://bitly.kr) | Korea | Korean-language Bitly alternative |
| [han.gl](https://han.gl) | Korea | Popular Korean URL shortener |
| [vo.la](https://vo.la) | Korea | Korean URL shortening service |
| [KurzeLinks.de](https://kurzelinks.de) | Germany | German-based, GDPR-focused |

---

### Niche & Specialized

| Service | Use Case | Notes |
|---------|----------|-------|
| [oe.cd](https://oe.cd) | OECD only | Restricted to OECD-related URLs |
| [LinkHuddle](https://linkhuddle.com) | Link aggregation | Combine multiple links into one |
| [LinkSplit](https://linksplit.io) | A/B testing | Split traffic between destinations |
| [reduced.to](https://reduced.to) | Open-source | Self-hostable with analytics |
| [spoo.me](https://spoo.me) | Simple | "Shorten URLs, not possibilities" |

---

## Self-Hosted Solutions

For teams requiring full data control, privacy, or customization.

| Solution | Language | Stars | Best For |
|----------|----------|-------|----------|
| [Dub.co](https://github.com/dubinc/dub) | TypeScript | 19k+ | Teams wanting premium features self-hosted |
| [Shlink](https://shlink.io) | PHP | 3k+ | Comprehensive features, REST API, Docker support |
| [YOURLS](https://yourls.org) | PHP | 10k+ | Simple setup, extensive plugin ecosystem |
| [Kutt](https://github.com/thedevs-network/kutt) | Node.js | 8k+ | Modern stack, clean UI |
| [Polr](https://polrproject.org) | PHP | 5k+ | Quick setup, modern design |
| [Sink](https://github.com/ccbikai/sink) | Cloudflare | 3k+ | Edge deployment, zero-cost hosting |

### Self-Hosted Comparison

| Feature | Shlink | YOURLS | Kutt |
|---------|--------|--------|------|
| Docker Support | Excellent | Good | Good |
| REST API | Full | Basic | Full |
| Web UI | Via client | Built-in | Built-in |
| Analytics | Advanced | Basic | Good |
| Learning Curve | Medium | Low | Low |

**Notes:** Shlink is "perhaps the most comprehensive self-hosted option." YOURLS has the largest plugin ecosystem. Kutt offers the most modern stack. Choose based on your team's technical preferences.

---

## Deprecated Services

These services are no longer available:

| Service | Status | Date |
|---------|--------|------|
| [goo.gl](https://goo.gl) | Deprecated by Google | March 2018 |
| [git.io](https://git.io) | Deprecated by GitHub | January 2022 |
| [me2.do](https://me2.do) | Deprecated by Naver | August 2016 |
| cutit.org | Suspended | - |
| s2r.co | Offline | - |
| soo.gd | Offline | - |
| hoy.kr | Offline | - |
| 3.ly | Offline | - |

---

## How to Choose a URL Shortener

### For Developers & API Integration
**Best choice: [jo4.io](https://jo4.io)**
- Full REST API with OpenAPI documentation
- Scoped API keys (read/write/delete)
- Webhooks for click events
- White-label for embedding in your product

### For Marketing Teams
**Best choice: [Rebrandly](https://rebrandly.com) or [Bitly](https://bitly.com)**
- Strong branding capabilities
- Campaign tracking
- Team collaboration features

### For Budget-Conscious Teams
**Best choice: [Short.io](https://short.io)**
- 1,000 free branded links
- Custom domains on free tier
- Generous click tracking

### For Enterprise & Compliance
**Best choice: [BL.INK](https://www.bl.ink)**
- SOC 2, ISO 27001, HIPAA, GDPR certified
- Enterprise SSO
- Advanced security features

### For Privacy-Focused Users
**Best choice: [is.gd](https://is.gd)**
- No tracking
- No ads
- No registration required

### For Self-Hosting
**Best choice: [Shlink](https://shlink.io) or [Dub.co](https://dub.co)**
- Full data control
- Docker deployment
- Active development

---

## Market Statistics (2025)

- **Global URL shortener market:** $360M (2024) → projected $1B+ (2033)
- **Growth rate:** 11-20% CAGR
- **Market leaders:** Google (legacy share), Bitly (~19%), Others
- **Trend:** Custom domains deliver 2.3x more clicks than generic short links

---

## Contributing

Read [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

**To add a service:**
1. Fork this repository
2. Add the service in the appropriate category
3. Include: name, URL, brief description, and any standout features
4. Submit a pull request

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

---

*Last updated: December 2025*

*Looking for an API-first URL shortener with white-label support? Check out [jo4.io](https://jo4.io) built by developers, for developers.*
