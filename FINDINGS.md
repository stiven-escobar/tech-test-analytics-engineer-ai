# Findings

## Executive Summary

The purpose of this assessment was to identify the correct FY2026 Q2 net revenue and determine why Finance no longer trusted the warehouse.

The original pipeline reported:

**FY2026 Q2 Net Revenue: 727,922.09 USD**

After investigating the data model, business rules, and SQL pipeline, I identified several material defects affecting revenue calculations.

After implementing the highest-impact fixes, the pipeline produced:

**FY2026 Q2 Net Revenue: 382,929.62 USD**

Difference:

**344,992.47 USD (-47.39%)**

The final solution improved the test suite from:

**4/7 passing → 7/7 passing**
