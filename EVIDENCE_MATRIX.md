# Recruiter Evidence Matrix

Use this matrix to keep resume, interview, and GitHub claims aligned.

| Claim | Public proof | What to explain in an interview | Boundary |
|---|---|---|---|
| Built a Shopify-connected e-commerce experience | [MyWowPet repository](https://github.com/Ggeorge73/mywowpet), [`package.json`](https://github.com/Ggeorge73/mywowpet/blob/main/package.json), [`PRODUCT_SHOPIFY_AUDIT.md`](https://github.com/Ggeorge73/mywowpet/blob/main/PRODUCT_SHOPIFY_AUDIT.md) | Product/variant mapping, cart and checkout flow, storefront-to-Shopify responsibilities, and launch validation | Do not claim transaction volume, revenue, customer count, or full production launch without verified data |
| Built a CI/CD delivery pipeline connected to Shopify | [`CICD_README.md`](https://github.com/Ggeorge73/mywowpet/blob/main/CICD_README.md), [`playwright.yml`](https://github.com/Ggeorge73/mywowpet/blob/main/.github/workflows/playwright.yml), [`security-gates.yml`](https://github.com/Ggeorge73/mywowpet/blob/main/.github/workflows/security-gates.yml) | Trigger strategy, lint/test/security gates, protected environments, secret handling, Shopify theme deployment, and rollback/readiness decisions | Distinguish implemented workflow code from environment settings that still require repository or Shopify configuration |
| Implemented automated quality checks | [`playwright.config.ts`](https://github.com/Ggeorge73/mywowpet/blob/main/playwright.config.ts), [`e2e-tests`](https://github.com/Ggeorge73/mywowpet/tree/main/e2e-tests) | Desktop/mobile coverage, retries, screenshots/video on failure, artifacts, nightly runs, and business-critical user journeys | Do not quote pass rates or coverage percentages unless measured |
| Applied DevSecOps controls | [`security-gates.yml`](https://github.com/Ggeorge73/mywowpet/blob/main/.github/workflows/security-gates.yml), [`DevSecOps_Runbook.md`](https://github.com/Ggeorge73/mywowpet/blob/main/DevSecOps_Runbook.md) | Gitleaks, Semgrep, Trivy, SARIF results, least-privilege workflow permissions, and protected production approvals | Do not state a clean security audit without reviewing the latest workflow results |
| Used AI-assisted development to build products | [MyWowPet](https://github.com/Ggeorge73/mywowpet), [DiamondEcho](https://github.com/Ggeorge73/DiamondEcho), and [Edge Racer](https://github.com/Ggeorge73/edge-racer) commit histories and implementation files | Which tools accelerated discovery/coding, what you personally decided, how you debugged, and how you verified output | Do not imply that AI generated a correct result without human review, testing, and iteration |
| Designed responsible AI/product boundaries | [`DiamondEcho/backend/ai/README.md`](https://github.com/Ggeorge73/DiamondEcho/blob/main/backend/ai/README.md) | Citation requirements, jurisdiction checks, fair-housing protections, deterministic calculators, human escalation, and production evaluation gates | Position this as an MVP design and implementation boundary, not legal, tax, mortgage, or investment advice |
| Built deterministic product analytics | [`DiamondEcho/backend/deal_intelligence/README.md`](https://github.com/Ggeorge73/DiamondEcho/blob/main/backend/deal_intelligence/README.md) | Formula versioning, explicit assumptions, input validation, warning behavior, scenario analysis, and auditability | Do not describe it as an automated valuation model or live-market data product |
| Integrated authentication and cloud persistence | [`Edge Racer Firebase module`](https://github.com/Ggeorge73/edge-racer/blob/main/src/lib/firebase.ts), [`GameCanvas.tsx`](https://github.com/Ggeorge73/edge-racer/blob/main/src/components/GameCanvas.tsx) | Google sign-in, authentication state, per-user progress, atomic race counts, and leaderboard persistence | Firebase web configuration is client configuration; security depends on correctly deployed Firestore rules |

## Evidence gap to close

The public repositories currently provide strong proof for one flagship e-commerce implementation: MyWowPet. The statement that you built **multiple e-commerce sites** should be supported before a recruiter review by adding at least one of the following:

1. A second public repository with a strong README and screenshots
2. A sanitized case study for a private repository
3. A live-site link plus an architecture and contribution summary
4. A short demo video showing the second build and its deployment workflow

Until that evidence is available, describe MyWowPet as the flagship public example and explain that additional builds are private or being prepared for publication.

