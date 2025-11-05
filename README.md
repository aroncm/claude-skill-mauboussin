# Mauboussin Competitive Analysis Skill

A Claude Skill for analyzing companies and assessing competitive advantages using Michael Mauboussin's investment frameworks.

## Overview

This skill enables Claude to perform rigorous company analysis using the mental models and frameworks developed by Michael Mauboussin, renowned investment strategist, author, and former Managing Director at BlueMountain Capital and Credit Suisse.

### Key Frameworks Included

1. **Competitive Advantage Assessment (Moats)**
   - Supply-side economies of scale
   - Network effects (demand-side economies of scale)
   - Switching costs
   - Intangible assets (brands, patents, regulatory licenses)
   - Cost advantages

2. **Expectations Investing**
   - Reverse-engineer market expectations from current prices
   - Identify potential expectation revision triggers
   - Focus on changes in expectations rather than absolute valuation

3. **Probabilistic Thinking & Base Rates**
   - Think in probability distributions, not point estimates
   - Apply historical base rates to anchor predictions
   - Balance outside view (statistics) with inside view (specifics)

4. **Skill vs. Luck Analysis**
   - Separate luck from skill in corporate performance
   - Assess sustainability of competitive advantages
   - Evaluate management effectiveness

5. **Capital Allocation Evaluation**
   - Assess management's capital deployment decisions
   - Evaluate returns on invested capital
   - Analyze M&A, buybacks, dividends, and reinvestment

6. **Valuation Principles**
   - DCF and intrinsic value estimation
   - Scenario analysis with probability weighting
   - Margin of safety assessment

## Installation

### For Claude Code

1. Clone or download this repository
2. Place it in your Claude Code skills directory:
   - Default location: `~/.claude/skills/`
   - Or your custom skills directory

3. The skill will automatically be available in Claude Code

```bash
# Using git
git clone <repository-url> ~/.claude/skills/mauboussin-competitive-analysis

# Or download and extract
mkdir -p ~/.claude/skills/mauboussin-competitive-analysis
# ... copy files to directory
```

### For Claude Desktop

1. Place the skill directory in your Claude configuration folder:
   - macOS: `~/Library/Application Support/Claude/skills/`
   - Windows: `%APPDATA%\Claude\skills\`
   - Linux: `~/.config/Claude/skills/`

2. Restart Claude Desktop

## Usage

The skill activates automatically when you ask Claude to analyze a company or assess competitive advantages. You can also invoke it explicitly.

### Example Prompts

**Basic Company Analysis:**
```
Analyze Apple's competitive advantages using Mauboussin's framework
```

**Expectations Analysis:**
```
What expectations are priced into Tesla's current stock price?
Use expectations investing framework to assess potential for revision.
```

**Capital Allocation Review:**
```
Evaluate Microsoft's capital allocation decisions over the past 5 years
```

**Comparative Analysis:**
```
Compare the moats of Coca-Cola vs PepsiCo using Mauboussin's competitive advantage framework
```

**Probabilistic Valuation:**
```
Provide a probabilistic valuation analysis of Amazon, including
scenario analysis with different growth assumptions
```

## What the Skill Provides

### Analytical Rigor

- **Structured Framework**: Systematic evaluation across multiple dimensions
- **Quantitative Focus**: Emphasis on measurable metrics (ROIC, market share, retention rates)
- **Probabilistic Thinking**: Distributions and scenarios, not single-point estimates
- **Base Rate Integration**: Historical context for predictions

### Key Outputs

1. **Competitive Advantage Assessment**
   - Evaluation of each moat dimension
   - Overall moat rating (None/Narrow/Wide)
   - Trajectory (Strengthening/Stable/Weakening)

2. **Expectations Analysis**
   - What's currently priced in
   - Potential revision triggers
   - Probability-weighted scenarios

3. **Management Evaluation**
   - Capital allocation track record
   - Strategic thinking quality
   - Decision-making process

4. **Investment Thesis**
   - Expected value analysis
   - Key risks and uncertainties
   - Catalysts for value realization

### Analytical Style

The skill embodies Mauboussin's analytical approach:

- ✓ **Intellectually honest** - Acknowledges uncertainties
- ✓ **Process-oriented** - Focuses on decision quality, not just outcomes
- ✓ **Probabilistic** - Uses ranges and distributions
- ✓ **Evidence-based** - References data and metrics
- ✓ **Long-term focused** - Emphasizes sustainable competitive advantages
- ✓ **Skeptical** - Seeks disconfirming evidence

## Reference Materials

The skill includes comprehensive reference documents covering:

### `/references/competitive-advantages.md`
- Detailed framework for each source of competitive advantage
- Metrics and indicators for evaluation
- Common mistakes in moat analysis
- Integration with valuation

### `/references/expectations-investing.md`
- Three-step expectations investing process
- Reverse-engineering market expectations
- Identifying expectation revision opportunities
- Scenario and sensitivity analysis

### `/references/probabilistic-thinking.md`
- Base rate thinking and outside view
- Probability distributions vs. point estimates
- Process vs. outcome evaluation
- Calibration and improving predictions

### `/references/skill-vs-luck.md`
- The skill-luck continuum
- Separating skill from luck in results
- Reversion to the mean
- Evaluating management effectiveness

### `/references/capital-allocation.md`
- Five uses of capital (reinvestment, M&A, dividends, buybacks, debt)
- Evaluation framework for each
- Management scorecard
- Red flags and green flags

### `/references/valuation-principles.md`
- DCF and intrinsic value
- Economic profit and EVA
- Scenario and sensitivity analysis
- Margin of safety

## Key Principles

The skill is guided by Mauboussin's core investment principles:

1. **Competitive advantages drive long-term value creation**
2. **Returns come from expectation revisions, not absolute value**
3. **Think probabilistically - use distributions, not point estimates**
4. **Base rates provide essential context for predictions**
5. **Process matters more than outcomes**
6. **Capital allocation is a critical management skill**
7. **Maintain intellectual honesty and humility**
8. **Focus on what's knowable and what matters**

## About Michael Mauboussin

Michael Mauboussin is one of the most respected investment strategists and thinkers in finance. He is known for:

- **Former positions**: Managing Director at BlueMountain Capital, Head of Global Financial Strategies at Credit Suisse, Chief Investment Strategist at Legg Mason
- **Academic**: Adjunct Professor at Columbia Business School
- **Author**: Multiple acclaimed books including:
  - "More Than You Know: Finding Financial Wisdom in Unconventional Places"
  - "Think Twice: Harnessing the Power of Counterintuition"
  - "The Success Equation: Untangling Skill and Luck in Business, Sports, and Investing"
  - "Expectations Investing" (with Alfred Rappaport)

- **Research**: Extensive white papers on competitive strategy, valuation, behavioral finance, and capital markets

His work emphasizes:
- Multidisciplinary thinking (psychology, statistics, competitive strategy)
- Probabilistic and Bayesian reasoning
- Process over outcomes
- Long-term value creation
- Mental models and decision-making frameworks

## Limitations and Considerations

**This skill provides frameworks and analytical tools, but:**

- Analysis quality depends on available information about the company
- Historical data and public filings required for quantitative analysis
- Cannot predict the future with certainty - focuses on probabilistic thinking
- Should be combined with your own research and judgment
- Not financial advice - for educational and analytical purposes only

**Best used for:**
- Public companies with available financial data
- Established businesses with track records
- Strategic analysis and mental model application
- Learning and applying Mauboussin's frameworks

**Less suitable for:**
- Pre-revenue startups with no operating history
- Private companies with limited disclosure
- Highly speculative or concept-stage ventures
- Short-term trading decisions

## Contributing

This skill can be enhanced with:
- Additional reference materials from Mauboussin's papers
- Industry-specific analysis templates
- Updated frameworks and research
- Example analyses of well-known companies

## License

This skill is provided for educational purposes. Michael Mauboussin's frameworks and concepts are referenced with respect to his intellectual contributions to investment analysis.

## Resources

### Michael Mauboussin's Work
- **Website**: https://www.michaelmauboussin.com
- **White Papers**: https://www.michaelmauboussin.com/writing
- **Books**: Available on Amazon and major retailers

### Related Skills
- Financial analysis
- Competitive strategy
- Behavioral finance
- Valuation modeling

## Version

**Version**: 1.0.0
**Last Updated**: 2025
**Compatibility**: Claude Code, Claude Desktop

---

**Note**: This skill helps you think like Michael Mauboussin, applying his rigorous frameworks for competitive analysis and probabilistic thinking to your investment research and company analysis.
