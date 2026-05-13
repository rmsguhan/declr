# What is Declr

> *The advertising model is broken. Consumers are surveilled, brands are wasteful, and neither side wins. Declr inverts the model entirely — consumers broadcast exactly what they want, and the market competes to win the deal.*

---

## The Problem

Advertising is a $1.17 trillion global industry built on a fundamental inefficiency: brands spend enormous sums trying to *guess* what consumers want, interrupt them with irrelevant messages, and hope for a conversion.
- **$750B+** was spent on digital advertising in 2025, representing over 75% of all ad spend globally. ([eMarketer, 2025](https://www.emarketer.com/content/worldwide-ad-spending-forecast-2025))
- **Only 43.9 cents** of every $1 entering a programmatic DSP actually reaches a consumer as a viewed ad. ([ANA, 2025](https://martech.org/ana-study-finds-25-of-programmatic-ad-dollars-are-wasted/))
- **$72B+** in ad spend was lost to invalid traffic globally in 2024. ([Statista](https://www.statista.com/statistics/1440980/ad-spend-lost-invalid-traffic-worldwide/))

Consumers, meanwhile, have lost trust:

- **81%** of US adults feel uncomfortable with how companies use their data. ([Pew Research, 2023](https://www.pewresearch.org/internet/2023/10/18/how-americans-view-data-privacy/))
- **75%** refuse to buy from companies they don't trust with their data. ([DemandLocal, 2025](https://www.demandlocal.com/blog/privacy-compliance-marketing-statistics/))

Despite this, brands continue to pay for audience profiles, segment targeting, and probabilistic intent signals — because there has been no alternative. Until now.

---

## The Hypothesis

**What if the consumer could just tell you what they want?**

Real purchase intent — explicit, structured, real-time — is worth exponentially more than inferred intent modeled from browsing history or third-party data. 

Declr makes intent the primary product — not an approximation, but a declaration.

The hierarchy of data quality:

- Third-party data (behavioral, probabilistic) — dying
- First-party data (loyalty, email, on-site) — the industry's current scramble, expensive and still guesswork
- Zero-party data (consumer-declared intent) — what Declr is built on; the gold standard

---

## What is Declr

Declr inverts the commerce model. Instead of brands targeting consumers with ads, **consumers broadcast purchase intent and the market competes to win the deal**.

A consumer **Declare**(s) a structured statement of what they want to buy or sell, they control the negotiation parameters. They dont share any PII information to the marketplace. AI agents parse and refine the Declare, then match it against the market. Sellers and brands see the anonymous intent and respond with offers specific to the declared intent. The on-device agent negotiates on the consumer's behalf with important decisions always presented back to the human in the loop. The consumer only acts when a deal clears their parameters and satisfies the declared intent. 

No ads. No tracking. No personal data sold. Just explicit, actionable intent — matched to the market in real time.

### The Declare as Ad Unit

| Old Model | Declr Model |
|---|---|
| Brand creates ad → broadcasts to audience | Consumer posts Declare → brands see explicit intent |
| Guesses at what consumers want | Knows exactly what consumers want |
| Pays for impressions, hopes for conversion | Responds only to real, confirmed purchase intent |
| Consumer is the product | Consumer is the publisher |
| Massive reach, low relevance | Reduced waste, 100% relevance by definition |

### Why It's More Valuable Than Any Ad Signal

Companies today pay significant premiums for intent signals derived from browsing behavior, search queries, and third-party data — all probabilistic. Today's advertising ecosystem infers consumer intent from behavioral surveillance and charges brands $40–300+ per acquisition with 2–5% conversion rates. Consumers receive nothing for their attention and data. Third-party cookies are collapsing, privacy regulations are tightening, and brands are desperate for higher-quality demand signals. 

A Declare is categorically different:

- **Explicit** — the consumer stated their intent in their own words
- **Structured** — AI parses it into actionable fields (category, price range, condition, timeline)
- **Real-time** — it represents active, in-market demand right now
- **Committed** — the consumer is ready to transact; not just browsing

A Declare is what every market research survey, focus group, and behavioral data model is trying to approximate.

---

## How It Works

### For Consumers
1. Post a Declare: "I want a used MacBook Pro M3, 16GB RAM, max $1,200, good condition, within 30 days"
2. On-device AI refines and structures the intent (Private, all operates on your device)
3. The Declare is indexed anonymously — brands and sellers see the intent, never the person
4. Offers arrive in an anonymous inbox; Custom inbox allows for commerce specific CTAs. The on-device agent (can) evaluate(s) them against consumer-set negotiation parameters
5. The consumer approves the best deal; identity is only disclosed at point of purchase

### For Sellers and Brands
1. Subscribe to the **Declr intent stream** — real, live purchase intent from active buyers
2. Respond with a structured offer tied to the Declare
3. The offer is Declr-exclusive — accessible only through the app (affiliate enforcement)
4. Pay only when a deal converts — not for impressions, not for clicks

### Privacy Architecture
Privacy is not a policy — it is architecturally enforced. On-device frontier models handle intent parsing and negotiation. No personal data leaves the device until the consumer approves a deal. The matching index stores only anonymized, structured fields. The consumer's anonymous inbox is their only identity in the ecosystem. Sellers and brands interact with the Declare — never the person behind it.

---

## The Market

### Why P2P First

The secondhand and resale market is a $188B global market in 2024, projected to reach $310B by 2029 — growing 5–6× faster than traditional retail. ([DontPayFull Recommerce Report](https://www.dontpayfull.com/explore/recommerce-statistics)) 93% of US consumers purchased a pre-owned item in the past year.

P2P is the right beachhead for Declr because:
- No brand partnerships required to launch
- Supply and demand are real and motivated on both sides
- Validates the core intent-broadcasting loop with authentic transactions
- The social feed creates organic discovery and network effects

### The Enterprise Opportunity

Declr Signal — the enterprise layer — transforms the consumer intent feed into the most valuable commercial intelligence product in existence. High-engagement Declares (many "Looks") are not just one person wanting something; they are evidence of latent, real demand from an active buyer population. A brand responding to a Declare with 500 Looks is executing a guaranteed-demand campaign — something no traditional ad platform can offer.

The buyer intent tools market today ($3.5B by 2033) serves mostly B2B workflows. Declr Signal addresses the far larger B2C gap: explicit consumer purchase intent at scale.

---

## Implementation Phases

### Phase 1 — MVP: Prove the Loop (P2P Commerce)

**Goal:** Validate that consumers will broadcast purchase and sale intent, and that other consumers will respond with offers — without any brand involvement.

**What we build:**
- iOS consumer app with Declare creation (purchase + sale intents)
- On-device AI for intent parsing and structuring (Apple Foundation Models)
- Anonymous matching index (backend)
- Anonymous inbox for offer delivery
- Basic on-device negotiation parameters (price range, condition, timeline)
- Social feed with Look + Pin engagement
- Commission capture at confirmed transaction

**Success criteria:**
- Consumers post Declares without friction
- Offers arrive in response to Declares
- At least one confirmed transaction completes end-to-end
- Declare-to-offer and offer-to-close conversion rates are measurable

**What we learn:**
- What categories generate the most Declares organically
- How much the social feed drives new Declare creation
- Whether on-device negotiation meaningfully reduces time-to-deal vs. manual back-and-forth
- Baseline commission economics per transaction

---

### Phase 2 — Growth: Social Feed + Enterprise Signal (Beta)

**Goal:** Grow the consumer intent graph to a density where it has standalone value, and onboard the first enterprise subscribers to Declr Signal.

**What we build:**
- Trending feed — surface high-engagement Declares at scale
- Refined Declr Protocol — extensible negotiation schema (bundle discounts, condition tiers, timeline incentives)
- Declr Signal (web) beta — enterprise dashboard for subscribing to anonymized intent streams
- Brand-facing offer tools — structured offer creation tied to Declares
- Analytics layer — conversion tracking, intent fulfillment rates, category intelligence for enterprises
- Identity handoff integrations — plug into existing payment rails, escrow, and logistics providers for B2C transactions

**Success criteria:**
- Consumer MAU growing week-over-week driven by social feed virality
- Enterprises willing to pay subscription fee to access intent stream
- First brand-originated offer responding to a consumer Declare
- Clear data on which categories convert best for enterprise targeting

**What we learn:**
- Enterprise willingness to pay for intent-based offer creation vs. traditional CPM/CPC
- Which Declare categories attract both P2P and brand supply (unified surface validation)
- Real negotiation dynamics — how often agents resolve autonomously vs. escalating to human
- Privacy threshold — how much structured intent data enterprises want without identifying the consumer

---

### Phase 3 — Scale: Intent Graph as Platform

**Goal:** Operate Declr as a platform where the intent graph is the core product, powering both the consumer experience and the enterprise intelligence layer.

**What we build:**
- Declr Connect — enterprise integration layer for CDP, CRM, and MarTech tools
- Advanced Declr Protocol — multi-brand negotiation, basket-level offers, loyalty tier integration
- Real-time intent stream API for programmatic enterprise access
- Cross-category intent graph — Declr as a searchable, structured demand signal across all consumer verticals
- Agent-to-agent negotiation at scale — buyers and sellers operating fully autonomously within declared parameters
- International expansion and category-specific surfaces (automotive, real estate, travel)

**Success criteria:**
- Enterprises treating Declr Signal as a core channel in their acquisition strategy
- Intent graph covering multiple high-GMV categories with sufficient density to provide reliable demand signals
- Commission revenue from P2P + enterprise subscription revenue both material
- On-device negotiation resolving the majority of deals without human intervention

**What we learn:**
- Whether Declr's monetization model (commission + subscription) outperforms traditional ad-based models on a per-impression basis
- Which verticals are most amenable to declare-first commerce
- Whether on-device AI agents can fully replace human negotiation in high-stakes transactions

---

## Business Model

Declr is built on a principle: **the consumer is not the product**.

Revenue comes from two sources:

1. **Commission on confirmed transactions** — charged to both buyer and seller at point of purchase confirmation. This scales with GMV and aligns Declr's incentives with successful deal-making.

2. **Enterprise subscriptions via Declr Signal** — brands and retailers pay for access to anonymized, real-time intent streams and the ability to respond with offers. Priced on seat/stream access, not CPM.

No advertising. No consumer data sales. No third-party tracking. The product is the match — not the attention.

---

## Why Now

Three forces converge to make Declr's timing right:

1. **On-device frontier models are good enough.** Apple Foundation Models and similar on-device AI make private, high-quality intent parsing and agent negotiation possible without sending sensitive data to a server. This was not viable two years ago.

2. **Consumer privacy demand has hit a tipping point.** 69% of consumers have abandoned a purchase over data concerns. 144 countries now have data protection laws. The era of surveillance-funded commerce is ending by both consumer preference and legal pressure.

3. **The resale/recommerce market has proven the consumer intent.** 93% of US consumers bought pre-owned goods in the past year. The market is $188B and growing at 5–6× the rate of traditional retail. Consumers are already comfortable broadcasting intent around price-sensitive, condition-specific purchases — the exact use case Declr is built for.

---

## Open Questions

The following remain open and are being actively explored. See [`open-questions-and-decisions.md`](./open-questions-and-decisions.md) for the full list.

- Anonymous inbox recovery across device reinstalls
- Minimum viable Declr Protocol schema
- Technical mechanism for offer exclusivity enforcement
- Identity and payment handoff integrations at close
- Push vs. pull architecture for the matching index

---
## Resources
- The buyer intent data tools market already validates this: it's projected to reach $3.5B by 2033 at a 15.9% CAGR ([OpenPR](https://www.openpr.com/news/4207737/buyer-intent-data-tools-market-to-reach-usd-3-5-billion-by-2033)) — and that's a market built on *approximations* of intent from behavioral signals.
Sources:
- ([Management Science / Kellogg – ATT impact study](https://www.kellogg.northwestern.edu/faculty/research/detail/2024/privacy-regulation-and-targeted-advertising-evidence-from-apples-app/))
- ([Experian – cookie deprecation guide ](https://www.experian.com/blogs/marketing-forward/cookie-deprecation/))
- ([Statista – ATT impact on UA performance](https://www.statista.com/statistics/1447318/impact-apple-att-ua-performance-worldwide/)
*Last updated: May 2026*
