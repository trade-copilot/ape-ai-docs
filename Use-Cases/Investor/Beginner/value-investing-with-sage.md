# Value Investing with Sage

---

**Time:** 60-90 minutes
**Cost:** $0 to learn (plus investment capital when ready)
**Platform:** Ape AI (askape.com) + Your brokerage
**Best for:** Investors seeking undervalued companies with long-term potential
**Persona:** Sage (for value analysis and strategy) + Money (for financial metrics)

---

## What You'll Learn

By the end of this workflow, you'll be able to:

1. ✅ Understand what value investing is and why it works
2. ✅ Identify undervalued stocks using key metrics (P/E, P/B, P/S)
3. ✅ Calculate intrinsic value to determine if a stock is "on sale"
4. ✅ Distinguish between value traps and genuine opportunities
5. ✅ Use Sage to find value stocks that match your criteria
6. ✅ Build a value-focused portfolio from scratch
7. ✅ Understand the patience required for value investing success

---

## What is Value Investing?

### The Philosophy

**Value investing** is buying stocks that trade for less than their intrinsic (true) worth. Think of it as shopping for $100 bills selling for $60.

**The Core Principle:**
> "Price is what you pay. Value is what you get." — Warren Buffett

The market sometimes misprices stocks due to:
- Short-term bad news (temporary problem, not permanent)
- Sector-wide sell-offs (baby thrown out with bathwater)
- Lack of attention (boring companies nobody talks about)
- Fear and panic (emotional selling)

Value investors exploit these mispricings by buying when others are fearful and selling when others are greedy.

### Historical Performance

**Why Value Investing Works:**
- From 1927-2020, value stocks outperformed growth stocks by ~3% annually
- $10,000 invested in value stocks (1927) = ~$90 million (2020)
- Same amount in growth stocks = ~$30 million
- Fama-French research shows "value premium" persists across decades

**Famous Value Investors:**
- **Warren Buffett** - Turned $10,000 into $300+ billion using value principles
- **Benjamin Graham** - Father of value investing, mentor to Buffett
- **Charlie Munger** - Buffett's partner, focused on "wonderful companies at fair prices"
- **Seth Klarman** - Baupost Group, 20%+ annual returns for 40 years

### Value vs. Growth Investing

| Aspect | Value Investing | Growth Investing |
|--------|----------------|------------------|
| **Focus** | Undervalued, established companies | Fast-growing companies regardless of price |
| **Metrics** | Low P/E, P/B, P/S ratios | High revenue/earnings growth rates |
| **Timeframe** | Patient (2-5+ years for revaluation) | Can be shorter (riding momentum) |
| **Risk** | Value traps (cheap for a reason) | Overvaluation (paying too much) |
| **Best Markets** | Bear markets, recessions | Bull markets, economic expansions |
| **Examples** | Banks, industrials, energy | Tech, biotech, emerging sectors |

**Neither is "better"** - both have their place. This workflow focuses on value.

---

## Key Value Investing Metrics

### Metric #1: Price-to-Earnings (P/E) Ratio

**Formula:**
```
P/E Ratio = Stock Price / Earnings Per Share (EPS)
```

**What it means:**
How many dollars you pay for each $1 of earnings.

**Example:**
- Stock trades at $100
- Company earns $5/share (EPS)
- P/E = $100 / $5 = 20

Interpretation: You're paying $20 for every $1 of annual earnings.

**What's "Low"?**
- **S&P 500 average:** 15-20 historically
- **Value territory:** P/E of 10-15
- **Deep value:** P/E under 10
- **Expensive:** P/E over 25

**Important Notes:**
- Compare P/E to industry peers (not just absolute number)
- Tech companies often have higher P/E (30-50+) - that's normal
- Banks/industrials typically have lower P/E (8-15)
- Negative P/E = company is losing money (avoid for value investing)

**Using Sage to Find Low P/E Stocks:**
```
Hey Sage, I'm looking for value stocks with P/E ratios under 15 in the following sectors: [Financials / Industrials / Energy / Healthcare].

Can you suggest 5 stocks that:
1. Have P/E under 15
2. Are profitable (positive earnings)
3. Have solid fundamentals (not cheap for bad reasons)
4. Include brief explanation of why each might be undervalued

I want to build a value portfolio focused on established companies.
```

### Metric #2: Price-to-Book (P/B) Ratio

**Formula:**
```
P/B Ratio = Stock Price / Book Value Per Share
```

**What is Book Value?**
- Company's total assets minus total liabilities
- What shareholders would get if company liquidated today
- Also called "equity" or "net worth"

**Example:**
- Stock trades at $50
- Book value per share is $40
- P/B = $50 / $40 = 1.25

Interpretation: Stock trades at 1.25× its book value.

**What's "Low"?**
- **P/B under 1.0:** Trading below book value (potential bargain)
- **P/B 1.0-3.0:** Reasonable for most companies
- **P/B over 3.0:** Expensive (paying big premium over book value)

**Best Used For:**
- Banks and financial institutions (assets are mostly cash/securities)
- Manufacturing companies (lots of physical assets)
- Real estate companies

**Less Useful For:**
- Tech companies (assets are intangible: software, patents, brand)
- Service businesses (value is in people/processes, not physical assets)

**Example Value Screen:**
```
Hey Sage, can you screen for financial stocks (banks, insurance) with:
- P/B ratio under 1.5
- Profitable last 12 months
- Dividend yield over 2%
- Market cap over $5 billion

I'm looking for undervalued financials for my value portfolio.
```

### Metric #3: Price-to-Sales (P/S) Ratio

**Formula:**
```
P/S Ratio = Market Cap / Total Revenue
OR
P/S Ratio = Stock Price / Revenue Per Share
```

**What it means:**
How much you're paying for each dollar of the company's sales.

**Example:**
- Company has market cap of $10 billion
- Annual revenue is $5 billion
- P/S = $10B / $5B = 2.0

Interpretation: Paying $2 for every $1 of sales.

**What's "Low"?**
- **P/S under 1.0:** Very cheap (often undervalued or distressed)
- **P/S 1.0-2.0:** Value territory
- **P/S 2.0-5.0:** Fair to moderately expensive
- **P/S over 5.0:** Expensive (growth premium)

**Why It's Useful:**
- Works for unprofitable companies (unlike P/E)
- Harder to manipulate than earnings
- Good for cyclical industries (earnings vary, but sales more stable)

**Best Used For:**
- Retail companies
- Airlines and transportation
- Cyclical industrials
- Early-stage companies (not yet profitable but generating revenue)

### Metric #4: PEG Ratio (P/E to Growth)

**Formula:**
```
PEG Ratio = P/E Ratio / Earnings Growth Rate
```

**What it means:**
Whether the P/E ratio is justified by the company's growth rate.

**Example:**
- Stock has P/E of 20
- Earnings growing at 25% annually
- PEG = 20 / 25 = 0.8

**What's "Good"?**
- **PEG under 1.0:** Undervalued (growth justifies or exceeds P/E)
- **PEG around 1.0:** Fairly valued
- **PEG over 2.0:** Overvalued (paying too much for growth)

**Why It's Better Than P/E Alone:**
- A stock with P/E of 30 might be cheap if earnings are growing 40%/year
- A stock with P/E of 10 might be expensive if earnings are declining

**Example:**
Company A: P/E = 15, Growth = 5%, PEG = 3.0 (expensive!)
Company B: P/E = 25, Growth = 30%, PEG = 0.83 (undervalued!)

Company B is the better value despite higher P/E.

### Metric #5: Dividend Yield

**Formula:**
```
Dividend Yield = (Annual Dividend / Stock Price) × 100
```

**Why Value Investors Love Dividends:**
- Provides income while waiting for stock to appreciate
- Dividend-paying companies tend to be stable (can't fake cash payments)
- Forces companies to be disciplined with capital
- High yield can indicate undervaluation

**Value Investor's Dividend Sweet Spot:**
- **3-6% yield:** Solid income + reasonable safety
- **Above 6%:** Investigate carefully (could be distressed)
- **Below 2%:** Not really a value play (unless growth is high)

**Warning Signs:**
- Yield doubled overnight = stock crashed (why?)
- Payout ratio over 100% = dividend likely to be cut
- Dividend hasn't grown in 5+ years = stagnant business

---

## The Value Investing Process

### Step 1: Screen for Value Candidates

**Using Sage for Initial Screening:**

**Prompt Template:**
```
Hey Sage, I want to screen for value stocks with these criteria:

Financial Metrics:
- P/E ratio: [range, e.g., 8-15]
- P/B ratio: [range, e.g., under 2.0]
- P/S ratio: [range, e.g., under 1.5]
- Market cap: [e.g., over $2 billion]
- Dividend yield: [e.g., over 3%]

Business Quality:
- Profitable last 12 months
- Revenue growth: [positive / stable]
- Sector: [specific sectors or "any"]

Can you suggest 10-15 stocks that fit these criteria with a brief explanation of each?
```

**Example Screen (Conservative Value):**
```
Hey Sage, I want to screen for value stocks with these criteria:

Financial Metrics:
- P/E ratio: 8-15
- P/B ratio: under 1.5
- Dividend yield: over 3%
- Market cap: over $5 billion

Business Quality:
- Profitable for last 5 consecutive years
- Positive free cash flow
- Sector: Financials, Industrials, Energy, Consumer Staples

Can you suggest 10-15 stocks that fit these criteria with a brief explanation of why each might be undervalued?
```

**What Sage Will Provide:**
- List of 10-15 stocks matching your criteria
- Current valuation metrics for each
- Brief business description
- Reasons why the stock might be undervalued
- Any red flags to investigate further

### Step 2: Deep Dive Analysis (Pick Top 3-5)

From Sage's list, pick 3-5 stocks that interest you most. Now dig deeper.

**Questions to Ask Money:**

```
Hey Money, I'm considering [TICKER] as a value investment. Can you analyze:

1. VALUATION:
   - Current P/E, P/B, P/S ratios
   - How these compare to 5-year historical averages
   - How these compare to industry peers

2. FINANCIAL HEALTH:
   - Revenue and earnings trends (last 5 years)
   - Free cash flow generation
   - Debt-to-equity ratio
   - Return on Equity (ROE)

3. WHY IS IT CHEAP?
   - Recent news or events causing price decline
   - Temporary vs. permanent issues
   - Market sentiment

4. CATALYSTS FOR REVALUATION:
   - What could cause the market to re-rate this stock higher?
   - Any upcoming events (new product, restructuring, etc.)

5. RISKS:
   - What could go wrong?
   - What would make this a "value trap" instead of true value?

Give me your honest assessment: Is this a genuine value opportunity or a value trap?
```

**What Money Will Analyze:**
- Complete financial picture with trends
- Comparison to historical valuation and peers
- Specific reasons for current undervaluation
- Potential catalysts for stock appreciation
- Risk factors and red flags
- Clear buy/hold/avoid recommendation

### Step 3: Calculate Intrinsic Value

**Intrinsic value** = What the stock is actually worth (independent of current price)

There are several methods. Here's the simplest for beginners:

**Method 1: P/E-Based Valuation**

Formula:
```
Intrinsic Value = EPS × Fair P/E Ratio
```

**Example:**
- Company earns $5/share (EPS)
- Historical average P/E is 15
- Industry average P/E is 18
- Conservative fair P/E estimate: 15

Intrinsic Value = $5 × 15 = $75/share

Current price: $50
**Margin of Safety:** ($75 - $50) / $75 = 33%

If margin of safety is 25%+, it's a buy candidate.

**Ask Sage to Calculate:**
```
Hey Sage, can you help me estimate the intrinsic value of [TICKER]?

Use the following method:
1. Find the current EPS
2. Find the company's 5-year average P/E ratio
3. Find the industry average P/E ratio
4. Use the LOWER of the two as "fair P/E"
5. Calculate: Intrinsic Value = EPS × Fair P/E
6. Compare to current stock price
7. Calculate margin of safety

Is this stock undervalued based on this analysis?
```

**Method 2: Dividend Discount Model (For Dividend Stocks)**

Formula:
```
Intrinsic Value = Annual Dividend / (Required Return - Dividend Growth Rate)
```

**Example:**
- Stock pays $3/year dividend
- You require 10% return
- Dividend has grown 5%/year historically

Intrinsic Value = $3 / (0.10 - 0.05) = $3 / 0.05 = $60

Current price: $45
**Margin of Safety:** ($60 - $45) / $60 = 25%

**Ask Sage:**
```
Hey Sage, can you calculate the intrinsic value of [TICKER] using the Dividend Discount Model?

Current annual dividend: $[amount]
Historical dividend growth rate: [%]
Required return: 10% (standard for stocks)

What's the estimated intrinsic value, and how does it compare to the current price?
```

**Method 3: Ask Sage for Multiple Valuation Methods**

```
Hey Sage, can you estimate the intrinsic value of [TICKER] using multiple methods:

1. P/E-based valuation (EPS × fair P/E)
2. P/B-based valuation (book value × fair P/B)
3. Dividend Discount Model (if applicable)
4. Discounted Cash Flow (if you can simplify it for me)

Then give me a range of intrinsic values and your opinion on whether the stock is undervalued at $[current price].
```

### Step 4: Identify the "Why It's Cheap" Reason

Every undervalued stock is cheap for a reason. Your job: Determine if it's temporary or permanent.

**GOOD Reasons (Temporary - BUY):**

✅ **Sector-wide sell-off:**
- Example: All bank stocks down 20% due to rate fears
- Company fundamentals unchanged
- Market overreacting to macro news

✅ **Short-term earnings miss:**
- Company missed quarterly earnings by 2%
- Long-term growth story intact
- Stock sold off 15%+ on overreaction

✅ **Cyclical downturn:**
- Industry in temporary slump (housing, commodities, travel)
- Company has strong balance sheet to weather it
- Will recover when cycle turns

✅ **Boring/unloved sector:**
- Nobody talks about it (utilities, industrials, consumer staples)
- Steady earnings, just not "sexy"
- Market ignores it, creating value

✅ **Spin-off or restructuring:**
- Company spun off from parent
- Forced selling by index funds
- Fundamentals improving but market hasn't noticed

**BAD Reasons (Permanent - AVOID):**

❌ **Dying business model:**
- Example: Declining revenue for 3+ years
- Technology disruption (Blockbuster vs. Netflix)
- Can't adapt to market changes

❌ **Unsustainable debt:**
- Debt-to-equity ratio over 2.0
- Interest payments eating into profits
- Risk of bankruptcy

❌ **Management problems:**
- CEO scandal, fraud, incompetence
- High executive turnover
- Consistently poor capital allocation

❌ **Permanent competitive disadvantage:**
- Competitors have better products/tech
- Losing market share year after year
- No moat, no differentiation

❌ **Secular decline:**
- Entire industry shrinking (newspapers, landline phones, coal)
- No amount of good management can fix
- Fighting against inevitable trends

**Ask Sage to Diagnose:**
```
Hey Sage, [TICKER] is trading at what looks like a low valuation (P/E of [X], P/B of [Y]).

Can you investigate WHY it's cheap? Specifically:
1. What caused the recent price decline?
2. Is the underlying business deteriorating or is this temporary?
3. Is this a value trap (cheap for good reason) or a value opportunity (cheap due to overreaction)?
4. What's the bull case and bear case?

Be brutally honest - I want to avoid value traps.
```

### Step 5: Check for Margin of Safety

**Margin of Safety** = The gap between intrinsic value and current price

**Benjamin Graham's Rule:**
> "Only buy stocks trading at least 25-30% below intrinsic value."

**Why It Matters:**
- Protects you if your valuation estimate is wrong
- Provides cushion against unexpected bad news
- Gives room for stock to appreciate to fair value

**Example:**
- Intrinsic value estimate: $100
- Required margin of safety: 30%
- Maximum buy price: $70

Current price: $65 ✅ (35% margin - GOOD)
Current price: $75 ❌ (25% margin - BORDERLINE)
Current price: $85 ❌ (15% margin - WAIT)

**Conservative Approach:**
- 30%+ margin = Strong buy
- 20-30% margin = Buy if high conviction
- 10-20% margin = Watch and wait
- <10% margin = Pass

### Step 6: Look for Catalysts

**Catalyst** = An event that could trigger the market to re-rate the stock

**Common Catalysts:**
- **Earnings surprise:** Company beats estimates after quarters of misses
- **New CEO/management:** Activist investor or turnaround expert comes in
- **Asset sale:** Company sells underperforming division, unlocks value
- **Dividend increase:** Signals management confidence, attracts income investors
- **Buyback announcement:** Company buying back shares (reduces supply, increases EPS)
- **Sector rotation:** Investors rotating back into unloved sector
- **Analyst upgrade:** Major bank initiates coverage with "Buy" rating
- **Inclusion in index:** S&P 500 addition forces funds to buy

**Ask Sage:**
```
Hey Sage, I'm considering [TICKER] as a value play. Current price is $[X], intrinsic value is ~$[Y].

What potential catalysts could cause the market to re-rate this stock higher in the next 1-2 years?

Examples:
- Upcoming earnings reports or guidance changes
- Management changes or activist involvement
- Industry trends that could benefit the company
- Pending asset sales or restructuring
- Potential M&A activity

I want to understand what could unlock the value.
```

**Important:** Don't require a catalyst to buy (value can be unlocked slowly), but having one increases odds of timely revaluation.

---

## Building a Value Portfolio

### Portfolio Construction Principles

**1. Diversification (Essential):**
- Minimum 10-15 stocks
- Spread across 5+ sectors
- No single stock over 10% of portfolio
- Mix of deep value, moderate value, and "value with catalysts"

**Why?** Value investing has higher single-stock risk. Diversification protects against value traps.

**2. Patience (Critical):**
- Value stocks can take 2-5 years to be re-rated
- Don't expect quick gains
- Measure success in years, not months
- Dividend income helps you wait

**3. Rebalancing:**
- When a stock reaches intrinsic value (or above), consider trimming/selling
- Redeploy proceeds to new undervalued opportunities
- Don't fall in love with stocks - be willing to sell when fairly valued

### Sample Value Portfolio ($10,000)

**Allocation Strategy:**
- 40% Deep Value (P/E <10, P/B <1.0) - Higher risk, higher potential return
- 40% Moderate Value (P/E 10-15, P/B 1.0-2.0) - Balanced
- 20% Value ETF (Diversification backstop)

**Example Holdings:**

**Deep Value (40% = $4,000):**
- 10% Bank of America (BAC) - $1,000
- 10% Ford (F) - $1,000
- 10% Citigroup (C) - $1,000
- 10% Vale (VALE) - $1,000

**Moderate Value (40% = $4,000):**
- 10% CVS Health (CVS) - $1,000
- 10% Walgreens (WBA) - $1,000
- 10% AT&T (T) - $1,000
- 10% Pfizer (PFE) - $1,000

**Value ETF (20% = $2,000):**
- 20% Vanguard Value ETF (VTV) or iShares Russell 1000 Value (IWD) - $2,000

**Portfolio Characteristics:**
- Blended P/E: ~11
- Blended P/B: ~1.3
- Average dividend yield: ~4.2%
- Annual dividend income: ~$420

**Expected Performance:**
- Value stocks historically return 10-12% annually long-term
- With dividends reinvested: ~12-14% potential
- Requires 3-5 year holding period for full revaluation

### Alternative: 100% Value ETF Portfolio

**For hands-off investors:**

**Allocation:**
- 50% VTV (Vanguard Value ETF) - Large-cap value
- 30% VBR (Vanguard Small-Cap Value ETF) - Small-cap value (higher return potential)
- 20% VYMI (Vanguard International High Dividend Yield) - International value

**Pros:**
- Instant diversification (1,000+ stocks)
- Low maintenance
- Captures value premium automatically
- Low fees (0.04-0.15% expense ratios)

**Cons:**
- Can't outperform (just match value index)
- Less control
- Lower yields than hand-picked portfolio

**Best for:** Beginners who want value exposure without stock picking

---

## Value Traps: What to Avoid

**Value Trap** = A stock that looks cheap but deserves to be cheap (or get cheaper)

### Red Flag #1: Deteriorating Fundamentals

**Warning signs:**
- Revenue declining 3+ consecutive years
- Profit margins shrinking
- Free cash flow turning negative
- Increasing debt levels

**Example:**
- Retail stock with P/E of 8 (looks cheap!)
- But revenue down 15% last 3 years
- Profit margins compressed from 10% to 3%
- This is cheap for a reason - AVOID

**Check with Money:**
```
Hey Money, [TICKER] looks statistically cheap (P/E of [X]), but I want to check for value trap signs.

Can you analyze:
1. Revenue trend last 5 years (growing, stable, or declining?)
2. Profit margin trend (expanding or contracting?)
3. Free cash flow trend (positive and growing, or negative?)
4. Debt trend (increasing or decreasing?)

Is this a value opportunity or a value trap?
```

### Red Flag #2: Unsustainable Dividend

**Warning signs:**
- Payout ratio over 100% (paying more than earning)
- Dividend hasn't grown in 5+ years (frozen = trouble)
- Free cash flow doesn't cover dividend
- Recently cut dividend

**Example:**
- Stock yields 8% (looks attractive!)
- Payout ratio is 120%
- Dividend likely to be cut soon
- When cut, stock will crash further - VALUE TRAP

**Check with Money:**
```
Hey Money, [TICKER] has a high dividend yield of [%]. Can you verify if it's sustainable?

1. What's the payout ratio?
2. Does free cash flow cover the dividend?
3. Has the dividend been growing, frozen, or cut recently?
4. What's the probability of a dividend cut in the next 12 months?
```

### Red Flag #3: Cheap But Getting Cheaper

**Pattern:**
- Stock has low P/E for years
- Keeps getting cheaper
- "Dead money" - just sits there declining

**Example:**
- 3 years ago: P/E of 10, stock at $50
- 2 years ago: P/E of 9, stock at $40
- 1 year ago: P/E of 8, stock at $30
- Today: P/E of 7, stock at $25

**This is not value - it's a failing business!**

**Check with Sage:**
```
Hey Sage, [TICKER] has had a low P/E ratio for several years, but the stock price keeps declining.

Can you check:
1. What's the 5-year stock price trend?
2. What's the 5-year earnings trend?
3. Is the business actually improving, or is this a slow decline?
4. Should I avoid this as a potential value trap?
```

### Red Flag #4: Heavy Debt Load

**Warning signs:**
- Debt-to-equity ratio over 2.0
- Interest coverage ratio under 3× (earnings barely cover interest payments)
- Debt coming due soon (refinancing risk)

**Example:**
- Company has $10B in debt
- Only earns $500M/year (20× debt-to-earnings)
- If rates rise or business weakens, could face bankruptcy
- VALUE TRAP despite low P/E

**Safe Debt Levels:**
- Debt-to-Equity under 1.0 = Very safe
- 1.0-2.0 = Manageable
- Over 2.0 = Risky (investigate carefully)

**Check with Money:**
```
Hey Money, what's [TICKER]'s debt situation?

1. Debt-to-equity ratio
2. Interest coverage ratio (EBIT / Interest Expense)
3. Any debt maturities coming due soon?
4. Is the debt level a concern for this company?
```

### Red Flag #5: Accounting Red Flags

**Warning signs:**
- Frequent restatements of earnings
- Complex accounting (hard to understand)
- Auditor changes or disputes
- Large discrepancies between reported earnings and cash flow

**Rule:** If you can't understand the financials, don't invest.

**Check with Sage:**
```
Hey Sage, I'm looking at [TICKER] as a value investment. Can you check for any accounting red flags?

1. Any recent earnings restatements?
2. Has the auditor changed recently?
3. Are there any unusual accounting practices?
4. Is there a big gap between reported earnings and actual cash flow?

I want to avoid accounting fraud or manipulation.
```

---

## Using Sage for Value Investing

### Best Prompts for Finding Value Stocks

**Weekly Value Screen:**
```
Hey Sage, I run a weekly screen for new value opportunities. Here's what I'm looking for this week:

MUST HAVE:
- P/E ratio: 8-15
- P/B ratio: under 2.0
- Profitable (positive earnings)
- Market cap: over $5 billion
- U.S. listed stocks

PREFER:
- Dividend yield: over 3%
- Revenue growth: positive or stable (not declining)
- Sectors: Financials, Industrials, Energy, Consumer, Healthcare

AVOID:
- Recent dividend cuts
- Negative free cash flow
- Debt-to-equity over 2.5

Can you suggest 10 stocks that fit this screen with a brief explanation of each?
```

**Value + Catalyst Screen:**
```
Hey Sage, I want to find value stocks with upcoming catalysts. Please screen for:

VALUE CRITERIA:
- Trading below historical average P/E
- P/E lower than industry average
- Market cap over $2 billion

CATALYST CRITERIA:
- Recent management change OR
- Activist investor involvement OR
- Upcoming earnings report (where a beat is likely) OR
- Potential index inclusion OR
- Asset sale/restructuring in progress

Can you find 5-8 stocks that meet BOTH value criteria AND have a clear catalyst?
```

**Turnaround Opportunities:**
```
Hey Sage, I'm looking for potential turnaround value plays:

CRITERIA:
- Stock down 30%+ from 52-week high
- Company was profitable historically (last 5 years avg)
- Recent CEO change or new turnaround plan announced
- Debt-to-equity under 1.5 (not distressed)
- Market cap over $3 billion

AVOID:
- Secular decline industries (newspapers, etc.)
- Consistent revenue declines
- Recent dividend cuts

What are 5-7 potential turnaround candidates worth investigating?
```

### Value Analysis Prompts for Individual Stocks

**Complete Value Assessment:**
```
Hey Sage, I want to do a complete value analysis of [TICKER]. Please provide:

SECTION 1: VALUATION
- Current P/E, P/B, P/S ratios
- 5-year historical averages for these ratios
- Industry peer comparison (3-5 similar companies)
- Is this stock cheap relative to history and peers?

SECTION 2: INTRINSIC VALUE ESTIMATE
- Using P/E-based method (EPS × fair P/E)
- Using P/B-based method (book value × fair P/B)
- Your estimated intrinsic value range
- Margin of safety at current price

SECTION 3: WHY IS IT CHEAP?
- What caused the stock to become undervalued?
- Is the reason temporary or permanent?
- Value trap risk assessment (1-10 scale, 10 = definitely a trap)

SECTION 4: QUALITY CHECK
- Financial health (debt, cash flow, profitability trends)
- Business quality (competitive position, moat, management)
- Any red flags I should be aware of

SECTION 5: CATALYSTS
- What could cause the market to re-rate this stock higher?
- Expected timeline for revaluation (if any)

SECTION 6: RECOMMENDATION
- Buy / Hold / Avoid with clear reasoning
- If Buy: Suggested position size (% of portfolio)
- If Avoid: What would need to change for you to reconsider?

Be thorough and honest - I want to make a well-informed decision.
```

**Peer Comparison for Value:**
```
Hey Sage, I'm deciding between [TICKER1], [TICKER2], and [TICKER3] for a value investment.

Can you compare:
1. Valuation metrics (P/E, P/B, P/S, Dividend Yield)
2. Financial health (debt, cash flow, profitability)
3. Business quality (which has the best competitive position?)
4. Growth prospects (which has the best runway?)
5. Risk factors (which has the most downside risk?)

Rank them from best to worst value investment with reasoning.
```

**Value + Quality Screen:**
```
Hey Sage, I want to find "quality value" stocks - companies that are undervalued BUT also have strong fundamentals.

CRITERIA:
- P/E ratio: 10-15 (moderately undervalued)
- Return on Equity: over 15% (profitable, efficient)
- Debt-to-Equity: under 1.0 (strong balance sheet)
- Free cash flow: positive and growing
- Revenue: growing or stable (not declining)
- Dividend: paying and growing for 5+ years

This combines Warren Buffett's "wonderful companies at fair prices" with traditional value.

Can you find 8-10 stocks that fit this quality value screen?
```

---

## Patience: The Value Investor's Superpower

### Why Value Investing Requires Patience

**The Reality:**
- Value stocks can take 2-5 years to be re-rated by the market
- Sometimes longer (7-10 years for deep value)
- You'll often be "wrong" for 1-2 years before being proven right
- Your portfolio may underperform during bull markets

**Why Most People Fail at Value Investing:**
1. They sell too soon (give up after 6 months of underperformance)
2. They chase performance (switch to growth stocks during rallies)
3. They lack conviction (didn't do enough research to hold through volatility)
4. They need excitement (value investing is boring by design)

**Warren Buffett's Wisdom:**
> "The stock market is a device for transferring money from the impatient to the patient."

### How to Stay Patient

**1. Track Multiple Metrics, Not Just Price:**

Don't obsess over daily stock price. Instead, track:
- Quarterly earnings (are they growing?)
- Revenue trends (improving or deteriorating?)
- Debt levels (being paid down?)
- Dividend payments and growth (increasing over time?)
- P/E ratio compression (is it re-rating higher?)

**Example:**
- Stock bought at $50 with P/E of 10
- 2 years later: Stock at $52 (only +4%)
- But: EPS grew from $5 to $6.50 (+30%)
- New P/E: $52 / $6.50 = 8 (even cheaper!)

**Conclusion:** Stock is MORE undervalued now, not less. Business improving, market hasn't noticed yet. HOLD (or buy more).

**2. Collect Dividends While You Wait:**

Many value stocks pay dividends. This makes waiting easier.

**Example:**
- Buy stock at $50 with 4% yield
- Year 1: Collect $2/share in dividends
- Year 2: Collect $2.10/share (5% dividend growth)
- Year 3: Stock re-rates to $65, collect $2.20/share

**Total 3-year return:**
- Capital gain: $15 ($50 → $65)
- Dividends: $6.30
- Total: $21.30 on $50 investment = 42.6% (12.5% annualized)

Dividends cushion your wait and compound over time.

**3. Maintain a "Value Journal":**

When you buy a stock, write down:
- **Date purchased:** [Date]
- **Price paid:** $[X]
- **Investment thesis:** Why is this undervalued? (2-3 paragraphs)
- **Intrinsic value estimate:** $[Y]
- **Margin of safety:** [%]
- **Expected holding period:** [years]
- **What would prove me wrong:** (Specific metrics or events)

**Review quarterly:**
- Is the thesis still intact?
- Have fundamentals improved, worsened, or stayed the same?
- Has the margin of safety expanded or contracted?

This prevents emotional selling and keeps you focused on fundamentals.

**4. Reframe "Underperformance" as "Opportunity":**

When your value stocks underperform growth stocks:
- Don't get discouraged
- View it as an opportunity to buy more at lower prices
- Remember: Mean reversion is powerful (what goes down often goes back up)

**Historical Pattern:**
- 1990s: Growth crushed value (tech boom)
- 2000-2009: Value crushed growth (tech bust, financial crisis)
- 2010-2021: Growth crushed value (tech boom 2.0)
- 2022-2024: Value outperformed (inflation, rate hikes)

Cycles repeat. Patience wins.

---

## Value Investing Success Stories

### Case Study #1: Warren Buffett and American Express (1960s)

**Situation:**
- 1963: American Express faced "Salad Oil Scandal" (fraud by subsidiary)
- Stock crashed from $65 to $35 (-46%)
- Market feared bankruptcy

**Buffett's Analysis:**
- Core credit card business unaffected
- Brand reputation intact (people still using Amex)
- Trading at P/E of 10 vs. historical 20
- Margin of safety: ~50%

**Action:**
- Buffett invested $13 million (40% of his fund)
- Held patiently while others panicked

**Result:**
- 5 years later: Stock at $180 (5× return)
- Became one of Buffett's greatest investments
- Held for decades, worth billions

**Lesson:** Temporary problems in quality companies create value opportunities.

### Case Study #2: Financial Crisis (2008-2009)

**Situation:**
- 2008-2009: Financial stocks crashed 50-80%
- Bank of America: $50 → $3
- Citigroup: $55 → $1
- Wells Fargo: $45 → $8
- Market feared total collapse

**Value Investor's Analysis:**
- Not all banks would fail (government wouldn't allow it)
- Some had strong balance sheets (Wells Fargo, JPMorgan)
- Trading at P/B ratios under 0.5 (below liquidation value)
- 50-70% margin of safety if they survived

**Action:**
- Value investors (including Buffett) bought aggressively
- Required conviction and courage
- Many held cash waiting for this opportunity

**Results (2009-2015):**
- Bank of America: $3 → $18 (6× return)
- Citigroup: $1 → $50+ (50×+ return)
- Wells Fargo: $8 → $55 (7× return)
- JPMorgan: $15 → $70 (5× return)

**Lesson:** The best value opportunities come during maximum fear.

### Case Study #3: Tobacco Stocks (2010s)

**Situation:**
- 2010-2020: Tobacco stocks unloved due to health concerns
- Altria, Philip Morris: Consistent earnings, low P/E (8-12)
- High dividend yields (6-8%)
- Market assumed industry would die

**Value Investor's Analysis:**
- Declining volume but pricing power intact
- Shifting to reduced-risk products (vapes, heat-not-burn)
- Massive free cash flow generation
- Trading at 30-40% discount to fair value

**Action:**
- Value investors accumulated positions
- Collected 6-8% dividends while waiting
- Reinvested dividends for compound growth

**Results:**
- Altria: Total return ~200% over decade (with dividends reinvested)
- Philip Morris International: ~150% total return
- Massive dividend income along the way

**Lesson:** "Boring" or "unloved" industries can be excellent value plays.

---

## Common Beginner Questions

**Q: How long should I hold a value stock?**

A: Until one of these happens:
1. Stock reaches intrinsic value (or above) → Consider selling
2. Fundamentals deteriorate permanently → Sell immediately
3. You find a better opportunity → Swap into better value
4. Thesis proves wrong → Exit and admit mistake

**Minimum hold period:** 2-3 years (value takes time to be realized)
**Average hold period:** 3-7 years
**Buffett's hold period:** "Forever" (for his best picks)

**Q: What if the stock keeps dropping after I buy?**

A: Ask yourself:
- Have the fundamentals changed?
- Is my thesis still intact?
- Is the margin of safety now even larger?

**If fundamentals intact:** This is an opportunity to buy more (average down)
**If fundamentals deteriorating:** Cut losses and exit

**Q: Should I use value investing in a bull market?**

A: Yes, but:
- You'll likely underperform growth stocks during euphoric rallies
- Stay disciplined (don't chase overvalued growth)
- Use the time to accumulate positions while others chase momentum
- When the cycle turns, you'll be glad you did

**Q: How much of my portfolio should be in value stocks?**

**Aggressive value investor:** 80-100%
**Balanced investor:** 40-60% (rest in growth, index funds)
**Conservative beginner:** 20-40% (learn while managing risk)

Start with 20-30% allocation, increase as you gain experience and conviction.

**Q: Can I combine value and dividend investing?**

A: Absolutely! They complement each other well.
- Many value stocks pay dividends (financials, consumer staples, industrials)
- Dividends provide income while waiting for revaluation
- Focus on "value + yield" stocks (P/E <15, yield >3%)

**Q: What sectors are best for value investing?**

**Historically value-rich sectors:**
- **Financials** (banks, insurance) - Often trade at low P/E and P/B
- **Energy** - Cyclical, frequently undervalued during downturns
- **Industrials** - Boring but steady, often overlooked
- **Consumer Staples** - Defensive, sometimes undervalued during growth manias
- **Utilities** - Slow growth, high dividends, often cheap

**Less common (but possible):**
- **Healthcare** - Can find value in pharma during patent cliff fears
- **Materials** - Cyclical, value opportunities during downturns
- **Real Estate** - REITs sometimes trade below NAV

**Usually NOT value sectors:**
- **Technology** - Typically growth-oriented (but exceptions exist)
- **Communication Services** - Mixed (some value, some growth)

---

## Success Checklist

By the end of this workflow, you should have:

- [ ] Understood the core principles of value investing (buy $100 bills for $60)
- [ ] Learned key valuation metrics (P/E, P/B, P/S, PEG, dividend yield)
- [ ] Used Sage to screen for value stock candidates
- [ ] Performed deep-dive analysis on 3-5 value stocks using Money
- [ ] Calculated intrinsic value using at least one method
- [ ] Identified the "why it's cheap" reason for your stocks
- [ ] Checked for value trap warning signs
- [ ] Calculated margin of safety (should be 25%+)
- [ ] Identified potential catalysts for revaluation
- [ ] Built or planned your first value portfolio (10-15 stocks or ETF-based)
- [ ] Set up a value journal to track investment theses
- [ ] Committed to 2-5 year holding period (patience is key!)

**🎉 Congratulations!** You've learned the time-tested principles that have created more billionaires than any other investing strategy!

---

## What's Next?

Now that you've mastered value investing basics:

### Related Workflows:
- **[Growth Stock Selection](./growth-stock-selection.md)** - Learn the opposite: buying growth at any price
- **[Dividend Investing Strategy](./dividend-investing-strategy.md)** - Many value stocks pay dividends
- **[Understanding Stock Fundamentals](./understanding-stock-fundamentals.md)** - Deepen your analysis skills
- **[Monthly Portfolio Review](../intermediate/monthly-portfolio-review.md)** - Track your value holdings
- **[Rebalancing Your Portfolio](./rebalancing-your-portfolio.md)** - Sell when stocks reach fair value

### Continue Learning:
- Read **"The Intelligent Investor"** by Benjamin Graham (the value investing bible)
- Study Warren Buffett's annual letters (free on Berkshire Hathaway website)
- Follow value investors on Twitter/X (find contrarian thinkers)
- Join value investing communities (r/ValueInvesting on Reddit)

### Practice:
- Run weekly value screens using Sage
- Analyze 1-2 value stocks per week
- Paper trade value positions before using real money
- Track your picks (even if you don't buy) to learn pattern recognition

**Remember:** Value investing requires patience, discipline, and independent thinking. You'll often be "wrong" in the short term before being proven right in the long term.

**"Be fearful when others are greedy, and greedy when others are fearful."** — Warren Buffett

Your future self will thank you! 🚀📈
