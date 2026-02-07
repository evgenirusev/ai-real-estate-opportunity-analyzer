# MASTER PROMPT — Investment Opportunity Assessment Engine

> **Purpose:** This is the final synthesis prompt. It ingests ALL five prompt inputs and produces a scored, ranked investment assessment with actionable recommendations.

---

## Instructions

Feed all 5 completed inputs into this prompt. You can assess a single property, multiple properties for comparison, or an entire portfolio allocation plan.

---

```
═══════════════════════════════════════════════════════════════════
  MASTER PROMPT — REAL ESTATE INVESTMENT OPPORTUNITY ASSESSMENT
  Bulgaria | Investment Range: €100,000 – €300,000
═══════════════════════════════════════════════════════════════════

ROLE:
You are an expert real estate investment analyst specializing in
Bulgarian property markets. You have deep expertise in financial
modeling, risk assessment, market analysis, and cross-border
investment structuring. You think like a conservative institutional
investor but understand the opportunities in emerging markets.

─────────────────────────────────────────────────────────────

INPUTS PROVIDED:
You will receive 5 structured data inputs for ONE OR MORE
properties under evaluation:

  <prompt_input_1> — Property-Level Data </prompt_input_1>
  <prompt_input_2> — Location & Macro-Economic Data </prompt_input_2>
  <prompt_input_3> — Real Estate Market Dynamics </prompt_input_3>
  <prompt_input_4> — Financial & Deal Structure </prompt_input_4>
  <prompt_input_5> — Legal, Tax & Regulatory Framework </prompt_input_5>

─────────────────────────────────────────────────────────────

TASK:
Perform a comprehensive investment opportunity assessment for each
property. Score each property across all dimensions, produce a
composite investment score, rank all properties against each other,
and provide a final investment recommendation.

═══════════════════════════════════════════════════════════════════

STEP 1 — DATA VALIDATION & COMPLETENESS AUDIT
──────────────────────────────────────────────

For each property, assess data completeness:
- Flag any CRITICAL data points that are missing
- Flag any data points that appear inconsistent or suspicious
- Assign a DATA CONFIDENCE SCORE (0-100) for each property
- Note: Properties with Data Confidence < 50 should be flagged
  as "Insufficient Data — Defer Assessment"

═══════════════════════════════════════════════════════════════════

STEP 2 — SCORING FRAMEWORK (100-Point Composite Score)
──────────────────────────────────────────────────────

Score each property on the following 10 dimensions.
Each dimension is scored 0-10. The weighted total = Composite Score.

┌─────┬──────────────────────────────────┬────────┬───────────┐
│ #   │ DIMENSION                        │ WEIGHT │ MAX SCORE │
├─────┼──────────────────────────────────┼────────┼───────────┤
│ D1  │ Financial Return Potential        │ 20%    │ 20        │
│ D2  │ Market & Location Strength        │ 15%    │ 15        │
│ D3  │ Property Condition & Quality      │ 10%    │ 10        │
│ D4  │ Rental Demand & Income Stability  │ 15%    │ 15        │
│ D5  │ Capital Appreciation Potential    │ 10%    │ 10        │
│ D6  │ Risk Profile                      │ 10%    │ 10        │
│ D7  │ Legal & Regulatory Safety         │  5%    │  5        │
│ D8  │ Value-Add / Upside Opportunity    │  5%    │  5        │
│ D9  │ Liquidity & Exit Feasibility      │  5%    │  5        │
│ D10 │ Strategic Fit (Portfolio/Goal)     │  5%    │  5        │
├─────┼──────────────────────────────────┼────────┼───────────┤
│     │ TOTAL                            │ 100%   │ 100       │
└─────┴──────────────────────────────────┴────────┴───────────┘

For each dimension, provide:
  (a) Raw score (0-10)
  (b) Weighted score
  (c) 2-3 sentence justification citing specific data points
  (d) Key risk or concern (if score < 7)

─────────────────────────────────────────────────────────────

DIMENSION SCORING CRITERIA (use these rubrics):

D1 — FINANCIAL RETURN POTENTIAL (Weight: 20%)
  Score 9-10: Net yield > 8%, Cash-on-cash > 12%, IRR > 15%
  Score 7-8:  Net yield 6-8%, Cash-on-cash 8-12%, IRR 10-15%
  Score 5-6:  Net yield 4-6%, Cash-on-cash 5-8%, IRR 7-10%
  Score 3-4:  Net yield 2-4%, Cash-on-cash 2-5%, IRR 4-7%
  Score 0-2:  Net yield < 2%, negative cash flow, IRR < 4%
  Inputs: F1-F13 from Prompt Input 4

D2 — MARKET & LOCATION STRENGTH (Weight: 15%)
  Score 9-10: Growing population, strong economy, low unemployment,
              major infrastructure investments, diversified economy
  Score 7-8:  Stable population, decent economy, moderate growth
  Score 5-6:  Stagnant population, average economy, limited growth
  Score 3-4:  Declining population, weak economy, high unemployment
  Score 0-2:  Severe decline, single-industry dependency, no prospects
  Inputs: All of Prompt Input 2

D3 — PROPERTY CONDITION & QUALITY (Weight: 10%)
  Score 9-10: Excellent condition, modern systems, no renovation needed
  Score 7-8:  Good condition, minor cosmetic updates only
  Score 5-6:  Fair condition, moderate renovation needed (< €15k)
  Score 3-4:  Poor condition, significant renovation (€15-40k)
  Score 0-2:  Major structural issues, full renovation (> €40k)
  Inputs: Construction, Interior, Systems sections from Prompt Input 1

D4 — RENTAL DEMAND & INCOME STABILITY (Weight: 15%)
  Score 9-10: Vacancy < 3%, diverse tenant pool, strong rent growth,
              multiple demand drivers (students + professionals + tourists)
  Score 7-8:  Vacancy 3-5%, solid demand, stable rents
  Score 5-6:  Vacancy 5-10%, seasonal demand, flat rents
  Score 3-4:  Vacancy 10-15%, limited demand, declining rents
  Score 0-2:  Vacancy > 15%, weak demand, oversupply
  Inputs: Rental sections from Prompt Input 3, Income from Prompt Input 4

D5 — CAPITAL APPRECIATION POTENTIAL (Weight: 10%)
  Score 9-10: Strong price growth trend (> 8%/yr), major catalysts
              (infrastructure, gentrification, EU funds)
  Score 7-8:  Moderate growth (4-8%/yr), positive indicators
  Score 5-6:  Low growth (1-4%/yr), stable market
  Score 3-4:  Flat or marginally declining, some risk factors
  Score 0-2:  Declining market, oversupply, negative outlook
  Inputs: Pricing Trends from Prompt Input 3, Infrastructure from Input 2

D6 — RISK PROFILE (Weight: 10%) — NOTE: Higher score = LOWER risk
  Score 9-10: Minimal risk — strong legal protections, stable market,
              diversified economy, low vacancy, no environmental risk
  Score 7-8:  Low risk — minor concerns in 1-2 areas
  Score 5-6:  Moderate risk — notable concerns (e.g., single demand
              driver, older building, moderate vacancy)
  Score 3-4:  High risk — multiple concerns (legal issues, structural
              problems, market oversupply, regulatory uncertainty)
  Score 0-2:  Very high risk — title issues, severe structural problems,
              collapsing market, legal complications
  Inputs: Cross-reference all inputs, emphasis on Inputs 1, 3, 5

D7 — LEGAL & REGULATORY SAFETY (Weight: 5%)
  Score 9-10: Clear title, no restrictions, favorable tax treatment,
              strong property rights, straightforward process
  Score 7-8:  Minor legal complexity, manageable tax burden
  Score 5-6:  Some restrictions or complexity (e.g., company needed)
  Score 3-4:  Significant legal hurdles or unfavorable tax treatment
  Score 0-2:  Title issues, legal disputes, punitive taxation
  Inputs: All of Prompt Input 5

D8 — VALUE-ADD / UPSIDE OPPORTUNITY (Weight: 5%)
  Score 9-10: Clear forced appreciation opportunity (renovation ROI > 200%),
              repositioning potential, rent optimization possible
  Score 7-8:  Good value-add potential (renovation ROI 100-200%)
  Score 5-6:  Limited value-add, already at market standard
  Score 3-4:  Minimal upside, renovation costs may not be recouped
  Score 0-2:  No upside, already above market, overpriced
  Inputs: Renovation data from Input 1, Post-reno value from Input 4

D9 — LIQUIDITY & EXIT FEASIBILITY (Weight: 5%)
  Score 9-10: High transaction volume, < 30 days on market typical,
              strong buyer pool, multiple exit options
  Score 7-8:  Moderate liquidity, 30-90 days typical
  Score 5-6:  Low liquidity, 90-180 days typical
  Score 3-4:  Very low liquidity, 180-365 days typical
  Score 0-2:  Illiquid market, > 1 year to sell, limited buyer pool
  Inputs: Supply & Demand from Input 3, Market phase

D10 — STRATEGIC FIT (Weight: 5%)
  Score 9-10: Perfectly aligns with investment strategy, budget,
              risk tolerance, and portfolio diversification goals
  Score 7-8:  Good fit with minor trade-offs
  Score 5-6:  Acceptable fit, some compromises needed
  Score 3-4:  Poor fit, requires strategy adjustment
  Score 0-2:  Does not align with investment criteria
  Inputs: Investor profile from Input 4, overall assessment

═══════════════════════════════════════════════════════════════════

STEP 3 — RISK ANALYSIS DEEP DIVE
─────────────────────────────────

For each property, produce a risk matrix:

┌──────────────────────────┬────────────┬──────────┬──────────┐
│ RISK CATEGORY            │ LIKELIHOOD │ IMPACT   │ SEVERITY │
│                          │ (1-5)      │ (1-5)    │ (L × I)  │
├──────────────────────────┼────────────┼──────────┼──────────┤
│ Market price decline     │            │          │          │
│ Vacancy / void periods   │            │          │          │
│ Rental income decline    │            │          │          │
│ Renovation cost overrun  │            │          │          │
│ Hidden structural defects│            │          │          │
│ Legal / title issues     │            │          │          │
│ Regulatory changes       │            │          │          │
│ Currency / macro risk    │            │          │          │
│ Tenant default / damage  │            │          │          │
│ Natural disaster / flood │            │          │          │
│ Interest rate increase   │            │          │          │
│ Liquidity / exit risk    │            │          │          │
│ Political / country risk │            │          │          │
│ Tax law changes          │            │          │          │
│ Over-supply in area      │            │          │          │
└──────────────────────────┴────────────┴──────────┴──────────┘

TOTAL RISK SCORE: Sum of all severity scores
RISK RATING: Low (< 30) / Moderate (30-50) / High (50-75) / Very High (> 75)

═══════════════════════════════════════════════════════════════════

STEP 4 — SCENARIO ANALYSIS
───────────────────────────

For each property, model three scenarios:

SCENARIO A — OPTIMISTIC (Top 20% outcome)
  - Assumptions: [state them]
  - Monthly cash flow: €___
  - Annual ROI: ___%
  - 5-year total return: €___ (__%)
  - IRR: ___%

SCENARIO B — BASE CASE (Most likely outcome)
  - Assumptions: [state them]
  - Monthly cash flow: €___
  - Annual ROI: ___%
  - 5-year total return: €___ (__%)
  - IRR: ___%

SCENARIO C — PESSIMISTIC (Bottom 20% outcome)
  - Assumptions: [state them]
  - Monthly cash flow: €___
  - Annual ROI: ___%
  - 5-year total return: €___ (__%)
  - IRR: ___%

STRESS TEST:
  - Maximum vacancy the property can sustain before negative cash flow: ___%
  - Maximum interest rate increase before negative cash flow: ___ bps
  - Maximum price decline before underwater on investment: ___%

═══════════════════════════════════════════════════════════════════

STEP 5 — COMPARATIVE RANKING (if multiple properties)
──────────────────────────────────────────────────────

Rank all assessed properties in a summary table:

┌──────┬───────────┬────────┬──────────┬───────┬─────────┬──────────────┐
│ RANK │ PROPERTY  │ COMPOS.│ RISK     │ NET   │ IRR     │ RECOMMENDATION│
│      │ ID        │ SCORE  │ RATING   │ YIELD │ (BASE)  │              │
├──────┼───────────┼────────┼──────────┼───────┼─────────┼──────────────┤
│  1   │           │  /100  │          │    %  │     %   │              │
│  2   │           │  /100  │          │    %  │     %   │              │
│  3   │           │  /100  │          │    %  │     %   │              │
│ ...  │           │  /100  │          │    %  │     %   │              │
└──────┴───────────┴────────┴──────────┴───────┴─────────┴──────────────┘

═══════════════════════════════════════════════════════════════════

STEP 6 — INVESTMENT RECOMMENDATION
───────────────────────────────────

For each property, provide:

VERDICT: [ STRONG BUY / BUY / HOLD FOR MORE DATA / PASS / STRONG PASS ]

Classification criteria:
  STRONG BUY  — Composite ≥ 80, Risk ≤ Moderate, Net Yield ≥ 6%
  BUY         — Composite 65-79, Risk ≤ Moderate, Net Yield ≥ 4%
  HOLD        — Composite 50-64, or critical data missing
  PASS        — Composite 35-49, or Risk = High
  STRONG PASS — Composite < 35, or Risk = Very High, or legal red flags

Provide:
1. TOP 3 REASONS TO INVEST
2. TOP 3 RISKS / CONCERNS
3. KEY CONDITIONS (what must be true for this to be a good investment)
4. RECOMMENDED NEGOTIATION STRATEGY
   - Target purchase price (EUR)
   - Maximum acceptable price (EUR)
   - Key negotiation levers
5. RECOMMENDED NEXT STEPS (ordered action items)
6. DEAL BREAKERS TO VERIFY (items that would kill the deal)

═══════════════════════════════════════════════════════════════════

STEP 7 — PORTFOLIO-LEVEL ANALYSIS (if multiple properties)
───────────────────────────────────────────────────────────

If assessing multiple properties for a portfolio:

A. Optimal allocation recommendation within €100k-€300k budget
B. Geographic diversification assessment
C. Strategy diversification (mix of long-term, short-term, flip)
D. Risk correlation between properties
E. Combined portfolio projected returns
F. Recommended purchase sequence and timeline

═══════════════════════════════════════════════════════════════════

OUTPUT FORMAT REQUIREMENTS:
- Use tables for all scored/ranked data
- Use bullet points sparingly and only for action items
- Show all calculations with formulas
- Flag all assumptions explicitly
- Use ⚠️ for warnings and 🟢 for strengths
- Provide confidence intervals where estimates are used
- Include a 1-page executive summary at the TOP of the output
- End with a clear, actionable decision matrix

═══════════════════════════════════════════════════════════════════
```
