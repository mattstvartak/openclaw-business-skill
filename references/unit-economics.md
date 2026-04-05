# Unit Economics

## Core Metrics

### Customer Acquisition Cost (CAC)
```
CAC = Total acquisition spend / Number of customers acquired
```
- Include all costs: ads, content creation, tools, time value
- Calculate per-channel: CAC(Facebook), CAC(SEO), CAC(cold email)
- Target: CAC < 1/3 of LTV (3:1 LTV:CAC ratio minimum)

### Lifetime Value (LTV)
```
LTV = ARPU * Gross Margin % * Average Customer Lifespan (months)
```
- For subscription: LTV = Monthly Revenue Per Customer / Monthly Churn Rate
- For one-time: LTV = Average Order Value * Average Purchases Per Customer
- Segment LTV by acquisition channel -- not all customers are equal

### Churn Rate
```
Monthly Churn = Customers lost this month / Customers at start of month
Annual Churn = 1 - (1 - Monthly Churn)^12
```
- SaaS targets: <5% monthly for SMB, <2% for enterprise
- Revenue churn matters more than logo churn (losing big accounts hurts more)
- Net revenue retention = (Revenue from existing customers including expansion) / Starting revenue
- NRR > 100% means you grow even without new customers

### Gross Margin
```
Gross Margin = (Revenue - COGS) / Revenue
```
- SaaS: target 70-85%
- Digital products: target 85-95%
- Services: target 40-60%
- Include hosting, API costs, payment processing fees, support costs

### Break-Even Analysis
```
Break-even point = Fixed Costs / (Price per Unit - Variable Cost per Unit)
Monthly break-even = Total monthly fixed costs / Average gross profit per customer
```
- Know your monthly burn rate (all fixed costs)
- Know how many paying customers cover that burn

## Payback Period
```
CAC Payback = CAC / (Monthly Revenue Per Customer * Gross Margin %)
```
- Target: < 12 months for bootstrapped, < 18 months for funded
- If payback > 12 months on a micro budget, the economics do not work yet

## Revenue Growth Math
```
New MRR = New Customers * ARPU
Net New MRR = New MRR + Expansion MRR - Churned MRR
Months to target = ln(Target MRR / Current MRR) / ln(1 + Monthly Growth Rate)
```
- 10% month-over-month growth = 3.1x annual
- 15% MoM = 5.3x annual
- 20% MoM = 8.9x annual

## Per-Channel Economics
Track separately for every acquisition channel:
- Spend per channel
- Leads generated
- Cost per lead (CPL)
- Lead-to-customer conversion rate
- CAC per channel
- LTV of customers from that channel
- ROI per channel = (LTV - CAC) / CAC

Kill channels where CAC > LTV/3. Double down where CAC < LTV/5.

## Budget Allocation Framework
On a micro budget, allocate:
- 60% to the highest-performing channel (by ROI)
- 25% to testing new channels (rotate weekly)
- 15% to retention and activation (reducing churn pays like acquisition)
