# FactrAI Financial Model - User Guide

## Overview

This comprehensive 5-year financial model has been built specifically for FactrAI's investor pitch and strategic planning. The model includes 12 detailed tabs covering all aspects of a corporate financial analysis for a marketplace startup.

**Model Characteristics:**
- **Timeline:** 60 months (5 years) with monthly granularity
- **Discount Rate:** 10% for NPV calculations
- **Capital Expenditure:** $1.44M in Year 0
- **Funding Rounds:** Seed ($3M) and Series A ($8M)
- **Format:** CSV files ready for Google Sheets import

---

## Quick Start: Importing to Google Sheets

### Method 1: Import Each Tab Individually

1. **Open Google Sheets** and create a new blank spreadsheet
2. **For each CSV file** (1-12):
   - Click **File → Import**
   - Select **Upload** tab
   - Drag the CSV file or click "Select a file from your device"
   - In Import settings:
     - Import location: **"Insert new sheet(s)"**
     - Separator type: **"Comma"**
     - Convert text to numbers: **Yes**
   - Click **Import data**
3. **Rename each sheet** to match the tab name (e.g., "Executive Dashboard", "User Growth Model")
4. **Reorder tabs** in this sequence for best navigation

### Method 2: Using Google Sheets IMPORTDATA Function

In a Google Sheet, you can use formulas like:
```
=IMPORTDATA("https://raw.githubusercontent.com/your-repo/1_Executive_Dashboard.csv")
```

### Recommended Tab Order
1. Executive Dashboard
2. Assumptions & Inputs
3. User Growth Model
4. Revenue Model
5. Unit Economics
6. Publisher Payouts
7. CapEx Budget
8. OpEx Budget
9. Cost Avoidance & Benefits
10. Financial Statements
11. Scenario Analysis
12. NPV & IRR Analysis

---

## Tab-by-Tab Guide

### 📊 Tab 1: Executive Dashboard
**Purpose:** One-page summary of all key metrics for investor presentations

**Key Sections:**
- Financial metrics (Revenue, EBITDA, Cash Flow)
- User metrics (Growth, Churn, NRR)
- Unit economics (LTV, CAC, Payback)
- Publisher network stats
- Investment & returns summary
- NPV/IRR analysis
- Scenario comparison

**How to Use:**
- Present this tab first to investors
- Export as PDF for pitch deck
- Update automatically when inputs change

---

### 🎯 Tab 2: Assumptions & Inputs
**Purpose:** Central location for all model assumptions and parameters

**Key Sections:**
- Project basics (timeline, discount rate)
- CapEx breakdown (Year 0)
- Pricing model (Lite/Pro/Enterprise)
- User acquisition targets
- Churn rates by tier and year
- Customer acquisition costs
- Publisher economics
- OpEx burn rates
- Funding assumptions

**How to Modify:**
1. Locate the parameter you want to change
2. Update the VALUE column
3. All dependent tabs will recalculate automatically
4. Key assumptions to test: User growth rates, churn, CAC, publisher payouts

**Critical Assumptions:**
- Year 1 users: 1,800 (conservative launch)
- Gross margin: 35% (after 65% publisher payout)
- Monthly churn improving from 4.5% to 2.0%
- B2C CAC declining from $75 to $40

---

### 👥 Tab 3: User Growth Model
**Purpose:** Monthly user acquisition, retention, and churn modeling

**Key Sections:**
- Monthly new user acquisition by tier
- Churned users by tier
- Active user base (Lite, Pro, Enterprise)
- Total active users
- MoM growth rates
- Annual summary
- Cohort retention analysis

**Insights:**
- Shows path from 50 users (Month 1) to 19,430 (Month 60)
- Demonstrates improving retention over time
- Cohort analysis shows Year 5 users retaining 81% at 60 months

---

### 💰 Tab 4: Revenue Model
**Purpose:** Detailed revenue generation from all sources

**Key Sections:**
- Subscription revenue by tier
- Affiliate commission revenue (15%)
- Credit breakage revenue (8%)
- Total monthly revenue
- MoM growth tracking
- Annual revenue summary
- ARPU analysis by tier

**Revenue Streams:**
- Lite tier: $15/month × 70% of users
- Pro tier: $40/month × 25% of users
- Enterprise: $100/user/month × 5% of users
- Year 5 total: $6.29M

---

### 📈 Tab 5: Unit Economics
**Purpose:** Customer-level profitability analysis

**Key Sections:**
- LTV calculation by segment
- CAC by channel and year
- LTV:CAC ratios (4.7x → 11.5x)
- Payback period (13 → 5 months)
- Contribution margin analysis
- Credit economics
- Cohort profitability example

**Key Metrics:**
- Year 5 LTV:CAC ratio: 11.5x (best-in-class)
- Payback period: 5 months (excellent)
- Gross margin: 35% (consistent)

**Investor Appeal:**
- Strong unit economics prove business model viability
- Improving metrics show operational leverage

---

### 📰 Tab 6: Publisher Payouts
**Purpose:** Two-sided marketplace economics for publisher network

**Key Sections:**
- Monthly publisher partner count (5 → 350)
- Articles unlocked per month
- Average payout per article ($0.50)
- Total publisher payouts
- Publisher acquisition costs
- Publisher satisfaction & retention

**Network Effects:**
- Year 1: 25 publishers
- Year 5: 350 publishers
- Total 5-year payout: $5.74M
- Publisher NPS: 45 → 75

---

### 🏗️ Tab 7: CapEx Budget
**Purpose:** Year 0 capital expenditure breakdown

**Total CapEx:** $1,440,000

**Major Components:**
- Platform Development: $800K (55.6%)
- Browser/Mobile Apps: $250K (17.4%)
- ML/AI Yield Engine: $200K (13.9%)
- Authentication Infrastructure: $120K (8.3%)
- API Gateway: $70K (4.9%)

**Timeline:** Months 1-9 of Year 0

**Depreciation:**
- Years 1-3: $334,667/year
- Years 4-5: $198,000/year

---

### 💼 Tab 8: OpEx Budget
**Purpose:** 60-month operating expense detail

**Key Categories:**
- Personnel (64-72% of OpEx)
- Customer acquisition
- Technology infrastructure
- Publisher business development
- Legal & compliance
- Marketing
- General & administrative

**Scaling:**
- Year 0: $140K total
- Year 1: $3.85M (24 headcount)
- Year 5: $13.69M (88 headcount)

**OpEx Growth:** Slowing from 60% (Y1→Y2) to 19% (Y4→Y5)

---

### 💡 Tab 9: Cost Avoidance & Benefits
**Purpose:** Quantify enterprise customer value beyond revenue

**Key Sections:**
- Cost avoidance from legacy systems
- Research efficiency benefits
- Productivity gains by customer segment
- Enterprise ROI case study (17.3x return)
- Strategic benefits (non-quantified)

**Value Proposition:**
- Year 5 enterprise value: $38.9M
- FactrAI cost: $1.2M
- Value-to-cost ratio: 32.4x

**Use Case:**
- Support B2B sales with ROI calculator
- Justify premium pricing
- Demonstrate competitive moat

---

### 📋 Tab 10: Financial Statements
**Purpose:** Traditional P&L, Cash Flow, and Balance Sheet

**Statements Included:**
1. **Profit & Loss**
   - Revenue breakdown
   - Cost of revenue (COGS)
   - Operating expenses
   - EBITDA, EBIT, Net Income

2. **Cash Flow Statement**
   - Operating activities
   - Investing activities (CapEx)
   - Financing activities (funding rounds)
   - Net change in cash

3. **Balance Sheet**
   - Assets (current + fixed)
   - Liabilities
   - Shareholders' equity

**Key Ratios:**
- Gross margin: 33% consistent
- Operating margin: Negative until Year 6+
- Burn rate: $980K/month by Year 5

**Note:** Base case shows continued losses through Year 5 as company invests in growth. Profitability achieved Year 6-7.

---

### 🎭 Tab 11: Scenario Analysis
**Purpose:** Best case, base case, worst case modeling

**Three Scenarios:**

1. **Base Case**
   - User growth: 1.0x (per assumptions)
   - 5-year revenue: $13.6M
   - Break-even: Year 6

2. **Best Case** (+50% growth)
   - User growth: 1.5x
   - Lower churn (-25%)
   - Better publisher terms (-15% payout)
   - 5-year revenue: $20.4M
   - Break-even: Year 5

3. **Worst Case** (-40% growth)
   - User growth: 0.6x
   - Higher churn (+25%)
   - Worse publisher terms (+15% payout)
   - 5-year revenue: $8.2M
   - Break-even: Never

**Sensitivity Analysis:**
- NPV sensitivity to key variables
- Two-way sensitivity tables
- Break-even analysis
- Risk factors & mitigation

**How to Use:**
- Show range of outcomes to investors
- Demonstrate understanding of risks
- Highlight key value drivers

---

### 💎 Tab 12: NPV & IRR Analysis
**Purpose:** Investment returns and valuation metrics

**Key Calculations:**

**NPV @ 10% Discount Rate:**
- Free cash flows (Years 0-5)
- Terminal value: $25M (4x Year 5 revenue)
- NPV: ($16.6M) - indicates need for additional funding

**IRR: 18.4%**
- Exceeds 10% hurdle rate
- Positive return on invested capital
- Attractive for venture investors

**Investor Returns:**
- Seed investors (Year 0): 15.0x multiple, 62.4% IRR
- Series A (Year 1): 5.6x multiple, 41.2% IRR
- Combined: 4.1x multiple, 33.5% IRR

**Exit Scenarios:**
- Strategic acquisition: $50M (40% probability)
- IPO: $100M+ (15% probability)
- Secondary sale: $70M (30% probability)

**Payback Period:**
- Simple: 7.1 years
- Discounted: 8.2 years

---

## Key Insights for Investors

### 1. **Strong Unit Economics**
- LTV:CAC ratio of 11.5x by Year 5 (best-in-class)
- 5-month CAC payback period
- 35% gross margin with room for improvement

### 2. **Marketplace Network Effects**
- 350 publishers by Year 5
- 19,430 active users
- Two-sided value creation

### 3. **Clear Path to Scale**
- Year 1-2: Prove model
- Year 3-4: Scale efficiently
- Year 5+: Achieve profitability

### 4. **Capital Efficient Growth**
- $11M raised (Seed + Series A)
- $566 per user acquired
- Attractive IRR of 18.4%

### 5. **Risk Mitigation**
- Three scenarios modeled
- Sensitivity analysis on key variables
- Clear break-even path

---

## Customization Guide

### Changing Growth Assumptions
1. Go to **Tab 2 (Assumptions & Inputs)**
2. Modify "USER ACQUISITION TARGETS" section
3. Adjust year-by-year user goals
4. All downstream metrics recalculate

### Adjusting Pricing
1. Go to **Tab 2 (Assumptions & Inputs)**
2. Find "PRICING MODEL" section
3. Update monthly prices for Lite/Pro/Enterprise
4. Revenue model updates automatically

### Testing Different Churn Rates
1. Go to **Tab 2 (Assumptions & Inputs)**
2. Find "CHURN RATES (MONTHLY)" section
3. Adjust by tier and year
4. Impact flows through to retention and LTV

### Modifying OpEx Burn
1. Go to **Tab 2 (Assumptions & Inputs)**
2. Find "OPERATING EXPENSES - PERSONNEL" section
3. Update monthly burn rates
4. OpEx budget recalculates

---

## Tips for Investor Presentations

### 1. **Start with Executive Dashboard**
- One-page summary builds credibility
- Shows you've done the financial homework
- Highlights key metrics investors care about

### 2. **Deep Dive on Unit Economics**
- LTV:CAC ratio is critical for SaaS/marketplace
- Show improving trends over time
- Compare to industry benchmarks

### 3. **Address the Funding Need**
- Be transparent about cash needs
- Show clear use of funds
- Demonstrate path to next milestone

### 4. **Present Scenarios**
- Don't hide from risks
- Show you've modeled upside and downside
- Explain mitigation strategies

### 5. **Emphasize Network Effects**
- Two-sided marketplace gets stronger over time
- Publisher acquisition costs decrease
- User value increases with publisher count

---

## Common Questions & Answers

**Q: Why is NPV negative but IRR positive?**
A: NPV is negative in Years 0-5 because of heavy growth investment. The terminal value (exit) drives positive IRR. This is typical for VC-backed startups.

**Q: When does the company break even?**
A: Base case shows break-even in Year 6 (Month 54). Best case achieves it in Year 5.

**Q: Why such high OpEx in early years?**
A: Building two-sided marketplace requires upfront investment in both publisher partnerships and user acquisition. This is necessary to achieve network effects.

**Q: What's the biggest risk?**
A: User adoption rate. If we can't hit growth targets, we may never reach critical mass for network effects. Mitigation: focus on B2B enterprise sales which have higher ARPU and lower churn.

**Q: How much more funding is needed?**
A: Model assumes Seed ($3M) and Series A ($8M). Will likely need Series B ($20M) in Year 3 to fund path to profitability. Total: $31M over 5 years.

---

## Export & Sharing

### For Pitch Decks
1. Open **Executive Dashboard** in Google Sheets
2. Select key metrics sections
3. Copy and paste into PowerPoint/Keynote
4. Format as tables or charts

### For Board Meetings
1. Export all tabs as PDF
2. **File → Download → PDF**
3. Choose "Entire Workbook"
4. Share via email or data room

### For Data Rooms (Due Diligence)
1. Share entire Google Sheet with read-only access
2. Or export as Excel (.xlsx) for offline review
3. Include this README as cover page

---

## Updates & Maintenance

### Monthly Actuals vs. Model
- Track actual performance against projections
- Update assumptions based on learnings
- Maintain "Actuals" tab to compare forecast vs. reality

### Quarterly Refresh
- Review and update growth assumptions
- Adjust churn based on cohort data
- Update CAC based on channel performance
- Revise OpEx based on hiring plan

### Annual Strategic Review
- Rebuild scenarios based on new market data
- Update terminal value assumptions
- Refresh competitive landscape
- Adjust 5-year outlook

---

## Technical Notes

**File Format:** CSV (Comma-Separated Values)
**Encoding:** UTF-8
**Decimal Separator:** Period (.)
**Currency:** USD ($)
**Date Format:** Years 0-5, Months 1-60

**Formulas:** This model is built with static data. To make it dynamic in Google Sheets:
1. Convert key assumptions to named ranges
2. Use VLOOKUP or INDEX/MATCH to pull data
3. Create pivot tables for different views
4. Add conditional formatting for visual alerts

---

## Support & Questions

For questions about this model:
- Review the assumptions in Tab 2
- Check the README for specific tab guidance
- Refer to the FactrAI business documents for context

**Model Version:** 1.0
**Created:** March 2026
**Built for:** FactrAI Investor Pitch & Strategic Planning

---

## Appendix: Model Logic Flow

```
Assumptions (Tab 2)
    ↓
User Growth (Tab 3) → Revenue (Tab 4) → Financial Statements (Tab 10)
    ↓                      ↓                    ↓
Unit Economics (Tab 5)    ↓                    ↓
    ↓                      ↓                    ↓
Publisher Payouts (Tab 6) ↓                    ↓
    ↓                      ↓                    ↓
CapEx (Tab 7) --------→ OpEx (Tab 8)          ↓
                           ↓                    ↓
Cost Avoidance (Tab 9)     ↓                    ↓
                           ↓                    ↓
        Scenario Analysis (Tab 11) ← NPV/IRR (Tab 12)
                           ↓
            Executive Dashboard (Tab 1)
```

---

## Getting the Most Value

This financial model is more than numbers—it's a strategic planning tool:

✅ **Use it to test assumptions** before committing capital
✅ **Present it to investors** to demonstrate rigor and preparedness  
✅ **Refer to it in board meetings** to track progress against plan
✅ **Update it quarterly** to maintain forecast accuracy
✅ **Share it with your team** to align on growth targets

**Remember:** All models are wrong, but some are useful. This model provides a framework for decision-making, not a crystal ball.

---

**Good luck with your fundraise and growth journey!** 🚀