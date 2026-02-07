# Bulgaria Real Estate Investment Opportunity Assessment

An agentic prompt system for comprehensive real estate market analysis in Bulgaria.

## System Architecture

```
┌──────────────┐  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐
│ PROMPT       │  │ PROMPT       │  │ PROMPT       │  │ PROMPT       │  │ PROMPT       │
│ INPUT 1      │  │ INPUT 2      │  │ INPUT 3      │  │ INPUT 4      │  │ INPUT 5      │
│ Property     │  │ Location &   │  │ Market       │  │ Financial &  │  │ Legal, Tax   │
│ Data         │  │ Macro-Econ   │  │ Dynamics     │  │ Deal         │  │ & Regulatory │
└──────┬───────┘  └──────┬───────┘  └──────┬───────┘  └──────┬───────┘  └──────┬───────┘
       │                 │                 │                 │                 │
       └────────────┬────┴────────┬────────┴────────┬────────┴────────┬───────┘
                    │             │                  │                 │
                    ▼             ▼                  ▼                 ▼
            ┌─────────────────────────────────────────────────────────────┐
            │              MASTER DEEP RESEARCH PROMPT                    │
            │         Investment Opportunity Assessment Engine            │
            └─────────────────────────┬───────────────────────────────────┘
                                      │
                                      ▼
                          ┌───────────────────────┐
                          │   SCORED & RANKED      │
                          │   INVESTMENT REPORT    │
                          └───────────────────────┘
```

## Folder Structure

```
real-estate/
├── README.md                          # This file
├── prompts/                           # All prompt templates
│   ├── 01-property-data.md            # Property-Level Data Sheet
│   ├── 02-location-macro.md           # Location & Macro-Economic Research
│   ├── 03-market-dynamics.md          # Real Estate Market Dynamics
│   ├── 04-financial-deal.md           # Financial & Deal Structure
│   ├── 05-legal-tax-regulatory.md     # Legal, Tax & Regulatory Framework
│   └── master-assessment.md           # Master Investment Assessment Engine
├── guides/                            # Reference guides and documentation
│   ├── workflow-usage.md              # Step-by-step usage guide
│   ├── data-sources.md                # Bulgaria-specific data sources
│   ├── scoring-benchmarks.md          # Bulgaria market benchmarks
│   ├── quick-screening.md             # Quick decision matrix
│   ├── financial-glossary.md          # Financial metrics definitions
│   └── risk-taxonomy.md               # Comprehensive risk catalog
└── raw response.md                    # Original combined document
```

## Quick Start

1. **Identify Properties** → Browse listing portals and shortlist 3-8 candidates
2. **Fill Input 1** → Complete property data sheet for each property
3. **Run Input 2 & 3** → Research location and market dynamics (reusable per location)
4. **Complete Input 4** → Financial modeling for each property
5. **Run Input 5** → Legal/tax framework (run once, update as needed)
6. **Execute Master Prompt** → Feed all 5 inputs for comprehensive assessment

## Investment Range

**Target Budget:** €100,000 – €300,000

## Key Features

- **10-Dimension Scoring Framework** with weighted composite score
- **Risk Matrix Analysis** with 15 risk categories
- **3-Scenario Financial Modeling** (Optimistic, Base, Pessimistic)
- **Comparative Property Ranking** for portfolio decisions
- **Actionable Recommendations** with negotiation strategies
