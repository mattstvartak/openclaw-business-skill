# openclaw-business-skill

Comprehensive business operations skill for AI agents. Covers strategy, marketing, sales, accounting, e-commerce, pricing, legal compliance, content strategy, and economic analysis. Turns an AI agent into a business-literate operator.

Compatible with [Finch](https://github.com/mattstvartak/finch-core), [OpenClaw](https://github.com/openclaw), and any agent platform that loads SKILL.md files.

## What This Skill Covers

The main SKILL.md (~170 lines) provides the operating framework. Twelve reference files provide deep knowledge loaded on demand:

| Reference File | Content |
|---------------|---------|
| `revenue-models.md` | SaaS, marketplace, productized service, digital products, affiliate, ads, lead gen, data licensing, multi-revenue architecture |
| `unit-economics.md` | CAC, LTV, churn, margins, break-even formulas, payback period, growth math, budget allocation |
| `channel-playbooks.md` | SEO, content marketing, organic social, paid ads, email, cold outreach, communities, Product Hunt, partnerships |
| `pricing-strategies.md` | Value-based, competitive, freemium, tiered pricing, pricing psychology, testing methodology |
| `legal-compliance.md` | Business structures, CCPA/GDPR, CAN-SPAM, FTC, platform TOS, IP, AI transparency, data monetization rules |
| `reporting-templates.md` | Weekly report template, monthly P&L template, opportunity evaluation scorecard |
| `economic-indicators.md` | Consumer confidence, GDP, inflation, interest rates, where to find data, how to interpret signals |
| `revenue-stacking.md` | Multi-stream playbooks by business type, when to activate each stream, data monetization specifics |
| `accounting-basics.md` | Bookkeeping (cash vs accrual), P&L, balance sheet, cash flow, taxes, invoicing, AR management |
| `sales-process.md` | Pipeline stages, cold email templates, follow-up cadence, objection handling, closing techniques, CRM basics |
| `ecommerce-operations.md` | Product sourcing, platform selection (Shopify/Etsy/Amazon), listing optimization, CRO, fulfillment, returns |
| `content-strategy.md` | SEO content clusters, editorial calendars, video strategy, content repurposing, measurement |
| `service-business.md` | Scoping, proposals, client management, scope creep prevention, scaling from solo to agency |

## Core Framework

The SKILL.md itself includes:

- **Operating principles** -- action over analysis, revenue is the score, kill fast, track everything, multi-revenue thinking
- **Decision scoring framework** -- 8 dimensions (revenue velocity, scalability, defensibility, automation potential, budget fit, legal compliance, data asset value, audience accumulation), scored 1-5 each
- **Agent delegation guide** -- which specialist agent handles what type of work
- **Market research protocol** -- 5-step process for evaluating opportunities
- **Marketing execution checklist** -- research, test, track, scale, cut
- **Financial reporting format** -- weekly and monthly report structures
- **Legal and ethical boundaries** -- clear rules on compliance, transparency, data privacy
- **Design and brand standards** -- visual quality expectations for customer-facing material
- **Economic awareness** -- how to factor macroeconomic conditions into decisions

## Install

### Finch

```bash
git clone https://github.com/mattstvartak/openclaw-business-skill.git
cp -r openclaw-business-skill ~/.finch/skills/business-operator/
finch gateway restart
```

### OpenClaw

```bash
git clone https://github.com/mattstvartak/openclaw-business-skill.git
cp -r openclaw-business-skill ~/.agents/skills/business-operator/
```

Or place in any skills directory your agent scans.

## How It Works

This is a **SKILL.md** with **references/** (declarative, no code). The SKILL.md stays under 500 lines and is always available in the agent's context. Reference files are loaded on demand when the agent needs deep knowledge on a specific topic.

The `description` field triggers on business-related topics: strategy, revenue, pricing, marketing, budgets, competitive analysis, reports, and more.

### Progressive Disclosure

1. **Always loaded** (~100 words): skill name and description
2. **Loaded when triggered** (~170 lines): the full SKILL.md framework
3. **Loaded on demand** (unlimited): specific reference files when the agent needs depth

This keeps the context window efficient. The agent does not load accounting formulas when discussing marketing strategy.

## Use Cases

- **"What's our best path to $10k MRR?"** -- Agent loads unit economics, scores revenue streams, recommends a plan
- **"Start marketing on Facebook"** -- Agent loads channel playbook, researches audience, drafts copy
- **"Weekly report"** -- Agent uses the reporting template to produce a structured update
- **"Should we add a $199 tier?"** -- Agent loads pricing strategies, analyzes competitors, scores the decision
- **"Research the CRM market"** -- Agent dispatches research agents, loads market research protocol
- **"What's our CAC by channel?"** -- Agent loads unit economics, calculates from available data

## Customization

All files are markdown. Edit them to fit your business:

- Add industry-specific knowledge to references
- Modify the decision framework weights
- Adjust the reporting templates
- Add competitor-specific analysis to channel playbooks
- Update economic indicators for your region

## License

MIT
