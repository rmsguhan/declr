# Declr Negotiation Protocol (DNP)

> An open, extensible peer-to-peer negotiation protocol for autonomous commerce agents — built on the [Google Agent2Agent (A2A) protocol](https://a2a-protocol.org/) and the [Schema.org](https://schema.org/) commerce vocabulary.

---
## What is Declr ?
What if brands only saw what you wanted them to see?
What if you could shop without being tracked, targeted, or turned into a data point?
What if instead of ads guessing at your intent — you just **declared** it?

Commerce should work for the consumer. Your intent is yours. Your identity stays yours. Brands and providers earn your attention by responding to exactly what you asked for — nothing more.

No profiles. No targeting. No guesswork. Just intent.

---

## Design Principles

1. **Stateless messaging.** Every message carries the full negotiation state. No agent needs to remember anything to validate the next message.
2. **A2A-native.** DNP rides on top of the Agent2Agent protocol. Any A2A-compatible agent infrastructure can host a DNP-speaking agent.
3. **Schema.org first.** Items, offers, and demands use the standard `Product`, `Offer`, and `Demand` types — not a bespoke schema.
4. **Open protocol, pluggable intelligence.** The protocol and base negotiation strategy classes are open source. The model intelligence that picks counter-offers is your competitive layer.
5. **Human-in-the-loop is a first-class flow.** Agents can escalate to a human at any round. The protocol treats `agent ↔ agent`, `agent ↔ human`, and `human ↔ human` as the same shape.
6. **Forward-compatible.** Today: bilateral peer-to-peer. Tomorrow: brand bidding, auctions, bundling, payment terms — added as new strategies, not protocol rewrites.