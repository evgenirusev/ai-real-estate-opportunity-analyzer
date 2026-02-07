# Workflow & Usage Guide

> **Purpose:** Step-by-step guide on how to use this prompt system effectively in practice.

---

## PHASE 1: Identify Candidate Properties

1. Browse listing portals (see [data-sources.md](data-sources.md))
2. Filter for your budget range (€100k-€300k)
3. Shortlist 3-8 properties for deep analysis
4. For each property, fill out **Prompt Input 1** as completely as possible from the listing + agent inquiries

---

## PHASE 2: Location Research (per unique location)

5. For each unique city/town in your shortlist, run **Prompt Input 2** as a deep research prompt
6. Run **Prompt Input 3** for market-specific data (can be combined with Input 2 if same location)
7. Save outputs — these are reusable for all properties in the same location

---

## PHASE 3: Financial Modeling (per property)

8. For each property, complete **Prompt Input 4**
   - Use data from Inputs 1-3 to fill calculated fields
   - Model at least base-case scenario
   - Get renovation quotes if significant work needed

---

## PHASE 4: Legal & Tax Framework (once, update as needed)

9. Run **Prompt Input 5** once for your investor profile
10. Update only if property type or purchase structure changes

---

## PHASE 5: Master Assessment

11. Feed ALL five inputs into the **Master Prompt**
12. You can assess:
    - A single property (detailed report)
    - Multiple properties (comparative ranking)
    - An entire portfolio allocation plan

---

## PHASE 6: Decision & Action

13. Use the output to:
    - Eliminate PASS / STRONG PASS properties
    - Deep-dive HOLD properties (gather missing data)
    - Negotiate on BUY / STRONG BUY properties
    - Execute using recommended next steps

---

## Iteration Cycle

- Re-run every time you get new data (e.g., after a property visit, after receiving renovation quotes, after rent market changes)
- The system is designed to be iterative — each pass should improve data confidence and score accuracy

---

## Tips for Best Results

| Tip | Details |
|-----|---------|
| **Fill in as many fields as possible** | More data = better scores |
| **Use "unknown" or "N/A" rather than guessing** | The system accounts for data gaps |
| **Cross-reference agent claims** | Always verify with independent data |
| **Visit properties in person** | Before moving past "BUY" stage |
| **Get independent renovation estimates** | Don't trust seller claims |
| **Verify title and legal status** | Through a Bulgarian lawyer |
| **Use scenario analysis** | To stress-test your assumptions |

---

## Quick Reference: Assessment Workflow

```
┌─────────────────────────────────────────────────────────────────┐
│                    ASSESSMENT WORKFLOW                          │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   [1] Property Data  ──┐                                        │
│                        │                                        │
│   [2] Location Data  ──┼──► [MASTER PROMPT] ──► SCORED REPORT   │
│                        │                                        │
│   [3] Market Data    ──┤                                        │
│                        │                                        │
│   [4] Financial Data ──┤                                        │
│                        │                                        │
│   [5] Legal/Tax Data ──┘                                        │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```
