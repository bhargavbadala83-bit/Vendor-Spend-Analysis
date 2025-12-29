# Methodology

## Overview

This vendor spend analysis was completed **entirely using Claude Code** from first principles. All classification logic, descriptions, recommendations, and financial calculations were generated programmatically.

---

## Step 1: Data Ingestion

- **Source:** Template CSV with vendor names and costs
- **Records:** 386 vendors
- **Total Spend:** $7,887,359

---

## Step 2: Load Config

Allowed departments from Config:
- Engineering
- Facilities
- G&A
- Legal
- M&A
- Marketing
- SaaS
- Product
- Professional Services
- Sales
- Support
- Finance

---

## Step 3: Vendor Classification

Each vendor classified into one of the allowed departments using:
1. **Keyword matching:** Company name patterns
2. **Entity recognition:** Legal suffixes (Ltd, LLC, d.o.o., GmbH)
3. **Regional patterns:** Croatian, Indian, UK, US entities

### Department Distribution
| Department | Vendors | Spend | % of Total |
|------------|---------|-------|------------|
| Sales | 5 | $3,156,127 | 40.0% |
| G&A | 254 | $2,121,542 | 26.9% |
| Professional Services | 17 | $721,176 | 9.1% |
| Facilities | 38 | $695,576 | 8.8% |
| Engineering | 17 | $505,799 | 6.4% |
| SaaS | 18 | $186,774 | 2.4% |
| Marketing | 13 | $133,832 | 1.7% |
| Finance | 7 | $133,310 | 1.7% |
| M&A | 3 | $109,854 | 1.4% |
| Legal | 11 | $107,704 | 1.4% |
| Product | 3 | $15,665 | 0.2% |

---

## Step 4: Description Generation

- **Custom descriptions:** Top vendors with specific descriptions
- **Department templates:** Category-based descriptions
- **Result:** 386/386 unique descriptions (100%)

---

## Step 5: Recommendation Engine

Each vendor receives one recommendation:
- **Optimize:** High-value vendors for negotiation
- **Consolidate:** Duplicate or fragmented vendors
- **Terminate:** Redundant tools

---

## Step 6: Savings Identification

| Category | Spend | Rate | Savings |
|----------|-------|------|---------|
| Salesforce | $3,117,226 | 15% | $467,584 |
| Facilities | $695,576 | 25% | $173,894 |
| Prof Services/Legal | $828,880 | 20% | $165,776 |
| Insurance | $382,257 | 15% | $57,339 |
| HR | $198,097 | 20% | $39,619 |
| Travel | $419,282 | 15% | $62,892 |
| SaaS | $186,774 | 35% | $65,371 |
| **TOTAL** | **$7,887,359** | **13.1%** | **$1,032,475** |

---

## Tools Used

- **Claude Code:** All code generation and analysis
- **Python 3:** Data processing
- **CSV module:** Data ingestion and output

---

## Results Summary

| Metric | Value |
|--------|-------|
| Vendors Analyzed | 386 |
| Total Spend | $7,887,359 |
| Departments | 11 |
| Unique Descriptions | 386 (100%) |
| Identified Savings | $1,032,475 (13.1%) |

---

*All work completed using Claude Code from first principles.*
