# Pharma Wholesaler Chargeback Reconciliation

Validate wholesaler chargebacks at contract-customer and NDC level and reconcile credits and deductions.

**Primary buyer:** Pharmaceutical manufacturers. **Evidence:** customer contracts, identifiers, NDCs, wholesaler sales, chargeback claims, contract prices, eligibility dates, duplicates, credits, and deductions.

Full local application built with React, Vite, Express, PostgreSQL, and OpenRouter. Includes 15 domain-specific capabilities, 105 custom AI workbench fields, three scenario-fill controls per feature, operational registers, workflow transitions, analytics, professional AI decision briefs, audit history, and at least 15 PostgreSQL records per capability.

## Domain capabilities

- Contract customer registry
- Identifier hierarchy mapping
- NDC product registry
- Wholesaler sales ingestion
- Eligibility date validation
- Contract price calculation
- WAC price comparison
- Chargeback amount calculation
- Duplicate claim detection
- Indirect customer validation
- Wholesaler deduction matching
- Rejection remediation
- Credit memo reconciliation
- Accrual true-up
- Wholesaler product analytics

Run `./start.sh`, then open <http://127.0.0.1:4709>. API: `5709`.

Administrator: `runtime-admin@example.com` / `LocalDemo!2026`. Operator and reviewer credential buttons are available on the login page.
