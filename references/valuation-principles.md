# Valuation Principles

## Core Philosophy

> "Price is what you pay. Value is what you get." - Warren Buffett

Mauboussin's approach to valuation emphasizes:
1. **Fundamentals matter**: Cash flows and returns on capital drive value
2. **Expectations analysis**: What's priced in?
3. **Probability distributions**: Range of outcomes, not point estimates
4. **Margin of safety**: Room for error
5. **Long-term focus**: Value emerges over time

## Intrinsic Value Framework

### Definition

**Intrinsic Value** = Present value of all future cash flows to investors

### The Fundamental Formula

```
Value = Σ [CFₜ / (1 + r)ᵗ]
```

Where:
- CF = Free cash flow in period t
- r = Discount rate (cost of capital)
- t = Time period

### Key Drivers of Value

Every valuation ultimately depends on:

1. **Sales Growth**: Revenue trajectory
2. **Operating Margin**: Profitability
3. **Capital Efficiency**: Asset turnover, ROIC
4. **Cost of Capital**: Risk-adjusted required return
5. **Competitive Advantage Period**: Duration of excess returns

## Discounted Cash Flow (DCF) Analysis

### Why DCF Is Fundamental

- Based on economic reality (cash flows)
- Explicit about assumptions
- Flexible for different scenarios
- Forces disciplined thinking

### DCF Components

#### 1. Free Cash Flow

**Formula**:
```
FCF = NOPAT - Net Investment
    = EBIT(1-Tax) - (Capex + ΔWC - Depreciation)
```

**Key Considerations**:
- Use unlevered FCF for enterprise value
- Normalize for cyclicality
- Adjust for one-time items
- Distinguish maintenance from growth capex

#### 2. Discount Rate (WACC)

**Formula**:
```
WACC = (E/V × Cost of Equity) + (D/V × Cost of Debt × (1-Tax))
```

**Cost of Equity** (CAPM):
```
r = Rf + β(Rm - Rf)
```

Where:
- Rf = Risk-free rate
- β = Beta (systematic risk)
- Rm - Rf = Equity risk premium

**Key Considerations**:
- Use forward-looking estimates
- Adjust beta for leverage
- Consider size and liquidity premiums
- Use market-based costs when possible

#### 3. Forecast Period

**Two-Stage Model**:

**Stage 1: Explicit Forecast (5-10 years)**:
- Detailed year-by-year projections
- Based on specific business drivers
- Higher growth/returns

**Stage 2: Terminal Value**:
- Perpetuity growth or exit multiple
- Sustainable long-term growth
- Fade to normalized returns

**Terminal Value Formula (Perpetuity Growth)**:
```
TV = FCFₙ₊₁ / (WACC - g)
```

Where:
- FCFₙ₊₁ = First year of terminal period
- g = Perpetual growth rate (usually GDP or less)

#### 4. Terminal Value Considerations

**Critical Because**:
- Often 60-80% of total value
- Highly sensitive to assumptions
- Small changes = big impact

**Key Assumptions**:

**Perpetuity Growth Rate (g)**:
- Usually 2-3% (GDP growth)
- Never above GDP long-term
- Mature, sustainable growth

**Terminal Returns (ROIC)**:
- Fade toward WACC over time
- Only widest moats sustain high returns
- Most companies ROIC → WACC

**Sanity Checks**:
- Implied terminal multiple reasonable?
- Implied terminal margin/ROIC sustainable?
- Growth rate × reinvestment = ROIC achievable?

## Mauboussin's EXPECTATIONS Framework

### Beyond Traditional DCF

Rather than estimating value from scratch, start with what's priced in:

### Step 1: Reverse-Engineer Current Expectations

**Question**: What must happen for current price to be fair?

**Approach**:
1. Take current enterprise value
2. Back out implied cash flows or growth
3. Identify assumptions embedded in price

**Example**:
Stock at $100, FCF = $5, WACC = 10%

If price = value, what growth is implied?

**Solve**:
```
$100 = Σ [FCF × (1+g)ᵗ / (1.10)ᵗ]
```

**Results**:
- If g = 7%, value ≈ $100 ✓
- Market expects ~7% perpetual FCF growth

### Step 2: Assess Likelihood

**Questions**:
- Is 7% growth achievable?
- Compare to base rates (most companies: 3-5%)
- What would enable 7%? Prevent it?
- How does this compare to history?

### Step 3: Identify Revision Opportunities

**If growth likely <7%**: Stock overvalued, expectations will decline
**If growth likely >7%**: Stock undervalued, expectations will rise

**Focus**: What will cause expectations to change?

## Valuation Multiples

### When to Use Multiples

**Advantages**:
- Quick and simple
- Market-based
- Useful for comparisons
- Capture market sentiment

**Limitations**:
- Black box (hides assumptions)
- Sensitive to comparables selection
- Can perpetuate mispricings
- Less rigorous than DCF

### Key Multiples

#### Enterprise Value Multiples

**EV/EBITDA**:
- Capital structure neutral
- Pre-tax
- Useful for LBOs, M&A
- Best for mature, stable businesses

**EV/Sales**:
- Revenue-based (hard to manipulate)
- Useful for early-stage/unprofitable
- Implies margin assumptions
- Compare to margin × EV/EBIT

**EV/EBIT**:
- Operating profit multiple
- After depreciation
- Capital structure neutral
- Assumes similar capex needs

#### Equity Multiples

**P/E (Price/Earnings)**:
- Most common
- After interest and tax
- Affected by leverage
- Sensitive to earnings quality

**Forward P/E**:
- Based on expected earnings
- Better for growth
- Only as good as estimates

**PEG (P/E / Growth)**:
- Adjusts for growth
- Rule of thumb: PEG < 1 attractive
- Simplistic but useful screen

**P/B (Price/Book)**:
- For asset-heavy businesses
- Banks, real estate
- ROE driver of P/B premium
- Less relevant for intangible-heavy

**P/S (Price/Sales)**:
- Revenue-based
- Growth companies
- Implies margin assumptions

### Multiple Analysis Best Practices

**Selecting Comparables**:
1. **Business Model**: Similar operations
2. **Size**: Market cap, revenue
3. **Growth**: Similar growth profiles
4. **Profitability**: Similar margins
5. **Geography**: Similar markets
6. **Risk**: Similar financial risk

**Adjustments**:
- Normalize for one-time items
- Adjust for accounting differences
- Consider growth differences
- Account for margin differences

**Interpretation**:
- Look at multiple multiples
- Understand drivers of differences
- Compare to history
- Sanity check vs. DCF implications

## Economic Profit / EVA

### What Is Economic Profit?

**Formula**:
```
Economic Profit = NOPAT - (WACC × Invested Capital)
```

Or:
```
Economic Profit = (ROIC - WACC) × Invested Capital
```

### Why It Matters

**Accounting profit ≠ Economic profit**

- Accounting: Earnings after interest
- Economic: Earnings after all capital costs

**Key Insight**: Only economic profit creates value

**Applications**:
- Evaluate value creation
- Compare business units
- Assess management performance
- Guide capital allocation

### MVA (Market Value Added)

**Formula**:
```
MVA = Market Value - Book Value
     = PV(Future Economic Profits)
```

**Interpretation**:
- MVA > 0: Market expects value creation
- MVA < 0: Market expects value destruction
- Change in MVA = Wealth created/destroyed

## Sum-of-the-Parts Valuation

### When to Use

- Conglomerates
- Multiple business units
- Different growth/risk profiles
- Potential spinoffs

### Process

1. **Identify segments**: Separate business units
2. **Value each separately**: DCF or multiples
3. **Add corporate overhead**: Allocate costs
4. **Net out debt**: Enterprise → Equity value
5. **Compare to market cap**: Conglomerate discount?

### Considerations

- Are segments truly independent?
- How allocate corporate costs?
- Any synergies between segments?
- What's realistic breakup value?

## Scenario Analysis

### Why Scenarios Matter

Single-point estimates are wrong. Use probability-weighted scenarios.

### Building Scenarios

**Identify Key Uncertainties**:
- TAM size and growth
- Market share trajectory
- Margin evolution
- Competitive dynamics
- Regulatory changes

**Create Scenarios**:

**Bull Case** (20% probability):
- TAM larger than expected
- Market share gains
- Margin expansion
- Multiple expansion
- Value: $150

**Base Case** (50% probability):
- TAM as expected
- Market share stable
- Margins flat
- Multiple stable
- Value: $100

**Bear Case** (25% probability):
- TAM smaller
- Market share loss
- Margin compression
- Multiple contraction
- Value: $60

**Distress Case** (5% probability):
- Major competitive threat
- Business model disruption
- Significant value destruction
- Value: $20

**Expected Value**:
```
EV = (0.20 × $150) + (0.50 × $100) + (0.25 × $60) + (0.05 × $20)
   = $30 + $50 + $15 + $1 = $96
```

**Current Price**: $80

**Expected Return**: 20%

### Sensitivity Analysis

**Key Variables**:
- Revenue growth rate
- Operating margin
- WACC
- Terminal growth rate
- Terminal multiple

**Approach**:
- Vary one variable at a time
- Build sensitivity tables
- Identify most critical assumptions
- Understand range of values

**Example Matrix**:

|Growth\WACC| 8% | 10% | 12% |
|-----------|-----|-----|-----|
| 3% | $120 | $100 | $85 |
| 5% | $140 | $115 | $95 |
| 7% | $165 | $135 | $110|

Helps visualize how assumptions drive value.

## Margin of Safety

### Benjamin Graham's Principle

**Definition**: Difference between intrinsic value and price

### Mauboussin's Application

**Why Margin of Safety Matters**:
1. Models are uncertain
2. Future is unpredictable
3. Surprises happen
4. Downside protection crucial

**How Much Margin?**

Depends on:
- **Uncertainty**: Higher uncertainty = wider margin
- **Business quality**: Lower quality = wider margin
- **Visibility**: Less visibility = wider margin
- **Leverage**: More leverage = wider margin

**General Guidelines**:
- High-quality, visible: 20-30% margin
- Moderate quality/visibility: 30-40% margin
- Low quality/high uncertainty: 40-50%+ margin

**Rule**: Required margin inversely related to confidence

## Common Valuation Mistakes

### 1. False Precision

**Mistake**: "This stock is worth $47.23"

**Reality**: Valuation is a range, not a point

**Fix**: "Value likely $40-55, expected value ~$47"

### 2. Extrapolating Recent Past

**Mistake**: Assuming last 3 years continue forever

**Reality**: Reversion to mean is powerful

**Fix**: Use base rates, normalize for cycles

### 3. Ignoring Capital Requirements

**Mistake**: Focusing only on earnings growth

**Reality**: Growth requires investment

**Fix**: Focus on FCF and ROIC, not just earnings

### 4. Misusing Multiples

**Mistake**: Applying average P/E to any company

**Reality**: Multiples embed assumptions about growth, risk, returns

**Fix**: Adjust for differences or use DCF

### 5. Terminal Value Heroics

**Mistake**: Aggressive terminal assumptions

**Reality**: Terminal value is most of value but least certain

**Fix**: Conservative terminal growth, fade ROIC to WACC

### 6. Ignoring Downside

**Mistake**: Only modeling upside scenarios

**Reality**: Losses hurt more than gains help

**Fix**: Serious attention to downside cases

### 7. Anchoring on Price

**Mistake**: Letting current price influence value estimate

**Reality**: Price and value can diverge significantly

**Fix**: Value independently, then compare to price

### 8. Ignoring Business Quality

**Mistake**: Buying cheap without considering moat

**Reality**: Low quality often cheap for a reason

**Fix**: Pay up for quality, avoid value traps

## Valuation in Practice

### Pre-Investment Checklist

1. ✓ **DCF with explicit assumptions**
2. ✓ **Scenario analysis with probabilities**
3. ✓ **Reverse-engineer current expectations**
4. ✓ **Comparable company analysis**
5. ✓ **Sensitivity to key assumptions**
6. ✓ **Downside scenarios and probability**
7. ✓ **Margin of safety adequate?**
8. ✓ **Catalysts for value realization?**
9. ✓ **What would change your mind?**
10. ✓ **Expected return vs. alternatives?**

### During Ownership

**Monitor**:
1. Are assumptions tracking reality?
2. Has intrinsic value changed?
3. Has price moved relative to value?
4. New information affecting outlook?
5. Better opportunities elsewhere?

**Update Valuation**:
- Quarterly earnings
- Major events
- Strategy changes
- Competitive dynamics shifts
- Market condition changes

**Sell Discipline**:
- Price exceeds value (+ margin)
- Thesis broken (assumptions wrong)
- Better opportunity found
- Risk/reward no longer attractive

## Key Principles Summary

1. **Value is present value of future cash flows**
2. **Focus on expectations, not just value**
3. **Think probabilistically, not precisely**
4. **Margin of safety is essential**
5. **Quality matters (moats create value)**
6. **Terminal value is critical but uncertain**
7. **Capital requirements matter, not just growth**
8. **Process > precision**
9. **Compare to base rates**
10. **Stay humble, update with new information**

## Integration with Other Frameworks

**With Competitive Advantage**:
- Moats enable sustained high ROIC
- Higher ROIC → Higher value
- Duration of advantage → Terminal value

**With Expectations Investing**:
- Don't just value, see what's priced in
- Focus on expectation revision opportunities
- Probability of change matters

**With Probabilistic Thinking**:
- Range of values, not point estimate
- Scenario probabilities
- Expected value framework

**With Capital Allocation**:
- How well does management deploy capital?
- ROIC on new investment
- Value creation vs. destruction

## Remember

> "It is better to be approximately right than precisely wrong."

Valuation is an art informed by science. Use rigorous frameworks, acknowledge uncertainty, think probabilistically, and always maintain a margin of safety.

**The goal**: Understand what you own, what it's worth, and what you're paying for it.
