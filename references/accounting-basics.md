# Accounting Basics

## Bookkeeping Fundamentals

### Cash vs Accrual
- **Cash basis:** Record revenue when money arrives, expenses when money leaves. Simple. Good for small operations.
- **Accrual basis:** Record revenue when earned (invoice sent), expenses when incurred (bill received). Required above ~$25M revenue or if carrying inventory. More accurate picture of financial health.
- Start with cash basis. Switch to accrual when complexity demands it.

### Chart of Accounts
Organize all financial activity into these categories:

**Revenue accounts:**
- Product/SaaS revenue (by tier if multiple)
- Service revenue
- Affiliate/commission income
- Advertising revenue
- Data licensing revenue
- Other income

**Cost of Goods Sold (COGS):**
- Hosting and infrastructure
- API costs (AI, payment processing, third-party services)
- Payment processor fees (Stripe takes 2.9% + $0.30)
- Direct labor for service delivery
- Domain and SSL costs

**Operating Expenses:**
- Marketing and advertising
- Software and tools (subscriptions)
- Contractor payments
- Legal and professional fees
- Insurance
- Office/workspace costs
- Travel (if applicable)

**Owner's equity:**
- Owner draws/distributions
- Retained earnings

### Double-Entry Basics
Every transaction has two sides:
- Revenue received: debit Cash, credit Revenue
- Expense paid: debit Expense, credit Cash
- Invoice sent (accrual): debit Accounts Receivable, credit Revenue
- Invoice paid (accrual): debit Cash, credit Accounts Receivable

## Financial Statements

### Profit & Loss (Income Statement)
```
Revenue
- COGS
= Gross Profit (Gross Margin %)
- Operating Expenses
= Operating Profit (Operating Margin %)
- Taxes
= Net Profit (Net Margin %)
```
Produce monthly. Compare to prior month and same month last year.

### Balance Sheet
```
Assets = Liabilities + Owner's Equity

Assets:
  Cash and bank accounts
  Accounts receivable (money owed to you)
  Prepaid expenses
  Equipment/property

Liabilities:
  Accounts payable (money you owe)
  Credit card balances
  Loans
  Deferred revenue (annual subscriptions not yet delivered)

Owner's Equity:
  Initial investment
  Retained earnings
  Owner draws
```

### Cash Flow Statement
Track where cash actually moves:
- **Operating:** Revenue collected minus expenses paid
- **Investing:** Equipment purchases, software development
- **Financing:** Loans taken or repaid, owner investment or draws

Cash flow is more important than profit for survival. A profitable business can die from poor cash flow (e.g., big expenses before revenue arrives).

## Tax Essentials

### Self-Employment Tax (US)
- 15.3% on net profit (12.4% Social Security + 2.9% Medicare)
- Applies to sole proprietors and LLC members
- Paid on top of income tax
- Deduct half of SE tax from income tax

### Quarterly Estimated Taxes
- Due: April 15, June 15, September 15, January 15
- Pay if expecting > $1,000 in annual tax liability
- Calculate: (Expected annual tax) / 4
- Underpayment penalty if you owe > $1,000 at year-end
- Safe harbor: pay 100% of last year's tax (110% if income > $150k)

### Common Deductions
- Home office (simplified: $5/sq ft, max 300 sq ft = $1,500)
- Internet and phone (business percentage)
- Software subscriptions used for business
- Marketing and advertising costs
- Professional development (courses, books, conferences)
- Health insurance premiums (self-employed deduction)
- Retirement contributions (SEP IRA up to 25% of net earnings)
- Vehicle expenses (standard mileage rate or actual expenses)

### Record Keeping
- Keep all receipts (digital is fine -- use a folder or app)
- Separate business and personal bank accounts
- Reconcile bank statements monthly
- Keep records for 7 years minimum
- Track mileage if using a vehicle for business

## Invoicing Best Practices

- Invoice immediately upon delivery (or on schedule for recurring)
- Payment terms: Net 15 for small clients, Net 30 for established
- Include: invoice number, date, due date, line items, total, payment instructions
- Offer multiple payment methods (ACH, credit card, PayPal)
- Automate recurring invoices for subscription clients
- Follow up on overdue invoices: Day 1 (reminder), Day 7 (firm), Day 14 (final notice), Day 30+ (consider collections)
- Late payment fee: 1.5%/month is standard. State it in terms.

## Accounts Receivable Management

- Track aging: Current, 30 days, 60 days, 90+ days
- Target: 95% collected within 30 days
- Automate payment reminders
- For high-risk clients: require deposit or prepayment
- Write off bad debt after 90-120 days of non-payment (tax deductible)

## Tools

- **Bookkeeping:** Wave (free), QuickBooks Self-Employed ($15/month), Xero
- **Invoicing:** Stripe Invoicing, Wave, FreshBooks
- **Expense tracking:** Wave, Expensify, manual spreadsheet
- **Tax prep:** TurboTax Self-Employed, TaxAct, or hire a CPA ($300-800/year)
- **Banking:** Separate business checking account (Mercury, Relay, any credit union)
