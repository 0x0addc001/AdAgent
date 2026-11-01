# AdAgent

**Agent-as-a-Service for advertising workflows.**

AdAgent plans, generates, evaluates, and revises campaigns under brand, audience, budget, and placement constraints.

面向广告业务的 Agent：在品牌、受众、预算和版位约束下生成、投放、评估并迭代广告素材。

**Status:** Project scaffold · [Portfolio](https://0x0addc001.github.io/#use-cases)

## Agent loop

| Stage | Responsibility |
|---|---|
| Data | Briefs, creative assets, audiences, performance feedback |
| Models | Multimodal content model, targeting model, policy model |
| Training | Brief-to-creative SFT, brand preference optimization |
| Inference | Copy generation, asset variants, scoring, allocation |
| Harness | Ad platform, asset delivery, budget and approval tools |
| Eval | Brand safety, lift, acquisition cost, constraint compliance |

## Initial scope

- Represent campaign goals and constraints explicitly.
- Generate multiple creative variants with provenance.
- Combine offline critique with online performance feedback.

## Roadmap

- [ ] Campaign brief schema
- [ ] Creative evaluation baseline
- [ ] Policy and brand-safety checks
- [ ] Budget-aware variant selection
- [ ] Closed-loop performance learning

## Engineering principles

- Human approval for consequential spend.
- Keep brand and policy constraints deterministic.
- Separate creative quality from media performance.

