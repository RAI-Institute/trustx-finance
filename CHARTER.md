# Agentic Commerce & Banking Working Group — Charter

## Mission

Agentic AI is moving from advising to acting in commerce and banking — initiating payments, executing trades, negotiating and completing purchases, and servicing accounts with decreasing human involvement. These actions move real money, are often hard to reverse, and are heavily regulated. This working group exists to apply and extend the TrustX framework so that autonomous agents operating in commerce and banking can be assessed against a common, sector-aware bar for trustworthiness before they are trusted with financial authority.

## Scope

**In scope**
- Agents that initiate, authorize, or execute financial transactions (payments, transfers, trades, purchases).
- Agents acting on a customer's behalf in banking servicing (onboarding, disputes, account changes).
- Sector-specific risk considerations: settlement and reversibility, transaction and exposure limits, KYC/AML and sanctions controls, auditability for financial regulators, and consumer-protection obligations.

**Out of scope**
- General-purpose (non-financial) agent assessment — that lives in the core framework.
- Setting regulation or acting as a compliance authority; this WG produces assessment guidance, not legal advice.
- Changes to the core rubric itself (propose those upstream in [`trustx-framework`](https://github.com/RAI-Institute/trustx-framework)).

## Relationship to the shared core

This WG consumes [`trustx-framework`](https://github.com/RAI-Institute/trustx-framework), pinned to `v1.0.0`. We may **add** sector-specific dimensions and guidance; we do **not** remove core dimensions, alter the 1–3 scale, or override worst-case-wins aggregation.

Sector extensions (candidates for the WG to define):
- **Settlement & reversibility** — can an erroneous or malicious action be unwound, and within what window?
- **Transaction & exposure limits** — are hard monetary limits enforced per action, per period, and in aggregate?
- **Regulatory auditability** — is every financial action reconstructable for a regulator or auditor?
- **KYC/AML & sanctions controls** — are counterparties and flows screened before the agent acts?

## Leadership

- **Chair:** U.S. Bank (`{{@usbank-handle}}`)
- **Co-founding member:** NatWest (`{{@natwest-handle}}`)

Chairs are the CODEOWNERS for charter and scope documents (see [`CODEOWNERS`](./CODEOWNERS)).

## Membership

Open to organizations and individuals working on agentic commerce and banking. To join, open an issue or contact a chair.

## Decision-making

- Charter/scope changes require review from the WG chairs (CODEOWNERS).
- Technical decisions are made by WG consensus; the community-manager (`@RAI-Institute/maintainers`) role coordinates but has **no override authority** here.
- Framework version bumps are recorded in [`meeting-notes/`](./meeting-notes).

## Cadence

Meeting frequency and format to be set by the chairs; notes are kept in [`meeting-notes/`](./meeting-notes).
