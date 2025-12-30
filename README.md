# VP Operations - Vendor Spend Analysis

## Overview

This assessment analyzes vendor spend data to identify cost-saving opportunities using **Claude Code from first principles**.

---

## How to Run

```bash
cd "/Users/gowtham/Downloads/AIAgent/VP Operations"
python3 vendor_spend_analysis.py
```

**Requirements:**
- Python 3 (no external packages needed)

---

## Input Files

| File | Description |
|------|-------------|
| `A - TEMPLATE - RWA - Vendor Spend Strategy (NAME) - Config.csv` | Allowed departments |
| `A - TEMPLATE - RWA - Vendor Spend Strategy (NAME) - Vendor Analysis Assessment.csv` | Raw vendor data |

---

## Output Files Generated

| File | Description |
|------|-------------|
| `Vendor_Analysis_Assessment_FINAL.csv` | Complete vendor analysis (386 vendors) |
| `Top_3_Opportunities.md` | Top 3 cost-saving opportunities |
| `CEO_CFO_Memo.md` | Executive memo for leadership |
| `Methodology.md` | How the analysis was done |

---

## Results Summary

| Metric | Value |
|--------|-------|
| Vendors Analyzed | 386 |
| Total Spend | $7,887,359 |
| Departments | 11 (from Config) |
| Unique Descriptions | 386 (100%) |
| Identified Savings | $1,032,475 (13.1%) |

---

## What the Script Does

1. **Reads Config** - Loads allowed departments
2. **Loads Vendors** - Parses 386 vendors from template
3. **Classifies** - Assigns department to each vendor
4. **Describes** - Generates unique 1-line description
5. **Recommends** - Optimize / Consolidate / Terminate
6. **Calculates Savings** - By category with rates
7. **Writes Outputs** - All 4 deliverables

---

## Claude Code File

**`vendor_spend_analysis.py`** - Single script that generates all deliverables from first principles.

---

*All analysis completed using Claude Code.*
