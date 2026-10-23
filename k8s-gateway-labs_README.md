# k8s-gateway-labs

Hands-on labs as I go deep on networking, Kubernetes, and API/AI gateways — kept as a **verified journal**: what I set out to do, what actually happened, and the fix. Learning in public.

> **Principle.** Every claim here is verified against ground truth before I write it down, and described at true magnitude. If I haven't actually run it, it isn't here.

## Structure
- `00-networking/` — DNS, TLS/mTLS, HTTP, proxies, load balancing
- `01-kubernetes-fundamentals/` — pods, deployments, services, `kubectl`, the reconciliation loop
- `02-ingress-and-gateway-api/` — ingress controllers, the Gateway API, routing, TLS termination
- `03-production-and-scale/` — observability, autoscaling, RBAC, NetworkPolicies, GitOps
- `04-api-and-ai-gateways/` — auth, rate limiting, model routing, guardrails, MCP

## Lab-journal template
Each lab lives in its folder as a `README.md` using this shape:

```
### Lab: <name>
- Goal:      what I'm trying to learn or prove
- Setup:     tools + exact commands (macOS)
- Expected:  what I thought would happen
- Actual:    what actually happened (output / screenshots)
- Fix:       the gap and the correction — verified against ground truth
- Attack & defend:  (where relevant) how I broke it safely, then hardened it
- Takeaway:  the one thing worth remembering
```

## Status
Honest progress, not a finished brochure — updated as each is genuinely completed:

- [ ] 00 · Networking foundations
- [ ] 01 · Kubernetes fundamentals
- [ ] 02 · Ingress & Gateway API
- [ ] 03 · Production & scale
- [ ] 04 · API & AI gateways

---

*Part of a deliberate move from "AI-first platform product" into the cloud-native and AI-infra layer underneath it. Companion write-ups: [cloud-native-for-pms](https://github.com/mohitambwani/cloud-native-for-pms) and [ai-gateways-and-guardrails](https://github.com/mohitambwani/ai-gateways-and-guardrails).*
