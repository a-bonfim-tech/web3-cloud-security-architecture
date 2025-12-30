# Web3 Wallet & Identity — Threat Model (Operator Perspective)

## Context
This document outlines a practical threat model for Web3 wallet usage from the perspective of a security-conscious operator and cloud security architect.

The focus is on identity, trust boundaries, and operational risk — not on trading or speculation.

---

## Assets
- Private keys / seed phrases
- Wallet identity (address reputation)
- Signing authority
- Governance rights
- Off-chain identity linkage (GitHub, Snapshot)

---

## Threat Actors
- Phishing campaigns
- Malicious dApps
- Approval drainers
- Compromised browser extensions
- Social engineering via Discord / X
- Supply chain attacks

---

## Attack Surfaces
- Browser environment
- Wallet extensions
- Message signing requests
- Token approvals
- Bridges and third-party integrations

---

## Key Risks
- Blind message signing
- Unlimited token approvals
- Identity poisoning via low-quality interactions
- Cross-wallet contamination
- Overexposure of professional identity

---

## Mitigations
- Wallet role separation (Vault / Identity / Experimental)
- Strict hygiene and minimal exposure
- revoke.cash usage
- Snapshot as off-chain governance entry
- Delay of ENS registration until signal exists
- Zero Trust mindset applied to Web3 interactions

---

## Residual Risk
Even with strong hygiene, Web3 identity remains probabilistic.
Risk is reduced, not eliminated.

---

## Conclusion
In Web3, wallet usage is identity usage.
Security decisions are reputational decisions.

