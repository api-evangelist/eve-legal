# Eve

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

**Legal AI for plaintiff law firms** — [eve.legal](https://www.eve.legal)

Eve is a legal AI platform built by **Butler Labs, Inc.** that positions itself as "the only legal AI that works your whole case with you." Eve 2.0 — the current product line — is marketed as a *proactive AI workforce* purpose-built for plaintiff law firms (personal injury, labor & employment, and adjacent practice areas), spanning the full case lifecycle from first intake call through litigation discovery.

This repository is an [API Evangelist](https://apievangelist.com) catalog profile of Eve. It documents Eve as a provider and its public surface — there is **no public developer API, OpenAPI specification, SDK, or documentation portal** available for Eve as of the date of this profile, so this profile is a **Tier-3** index entry capturing the company, products, and provider footprint rather than a machine-readable API contract.

---

## At a Glance

| | |
|---|---|
| **Provider** | Butler Labs, Inc. (operating as Eve) |
| **Domain** | [eve.legal](https://www.eve.legal) |
| **App** | [app.eve.legal](https://app.eve.legal) |
| **Category** | Legal AI / Plaintiff Practice Management |
| **Target Customer** | Plaintiff law firms (personal injury, labor & employment) |
| **Founders** | Jay Madheswaran (CEO), Matt Noe (CPO), David Zeng (Head of Engineering) |
| **Funding** | $164M+ raised |
| **Public API** | None |
| **GitHub Org** | [github.com/eve-legal](https://github.com/eve-legal) (0 public repos) |
| **Compliance** | SOC 2 Type 2 certified, HIPAA compliant |
| **Tier** | 3 — Index / Provider profile, no machine-readable API surface |

---

## What Eve Does

Eve is organized around three product surfaces inside the Eve 2.0 platform:

### Eve Agents — intelligent automations that work cases 24/7

| Agent | Stage | What it does |
|---|---|---|
| **Case Intake & Evaluation** | Intake | Evaluates case value and key facts to identify high-potential cases at the front door of the firm |
| **AI Voice Agent** | Intake | Takes incoming intake calls 24/7 |
| **Medical Overviews** | Pre-litigation | Generates complete medical chronologies and damages summaries from large volumes of records, with unlimited updates as the case evolves |
| **Demand Letters** | Pre-litigation | Drafts strategic demand letters in the firm's tone and style with unlimited iterations |
| **Drafting** | Pre-litigation | Drafts complaints, good faith letters, and other documents |
| **Propounding Discovery** | Litigation | Generates discovery requests calibrated to pressure opposing counsel toward settlement |
| **Responding to Discovery** | Litigation | Drafts discovery responses and objections |

### Eve Auditor — nightly review of the active caseload

Audits the firm's entire active caseload every night and surfaces *missed value drivers* — for example: undiagnosed/undocumented TBIs, MRIs ordered but never taken, and mass-tort eligibility overlooked at intake. Marketed as "having a senior attorney silently review every open file while your team sleeps."

### Eve Analyst — *coming soon*

Announced but not yet released as of this profile.

---

## Why Eve Has No Public API (Yet)

Eve is a **closed, sales-led B2B SaaS application**. Access is gated behind a "Schedule a call" / "Book a Demo" motion and delivered through the Eve web application at `app.eve.legal`. There is:

- **No `docs.eve.legal`** developer documentation portal (DNS does not resolve).
- **No `developers.eve.legal`** subdomain.
- **No `/api`, `/openapi.json`, or `/swagger.json`** endpoints discoverable on `eve.legal`.
- **No public OpenAPI, AsyncAPI, or Postman collection.**
- **No SDKs in any language registry** (npm, PyPI, Maven, etc.).
- **No public repositories** in the [`eve-legal` GitHub organization](https://github.com/eve-legal) — the org exists (created Feb 2025) but is empty.
- **No documented webhooks** or integration endpoints in the public marketing surface.

This is consistent with the broader legal-AI market: most plaintiff-focused legal AI vendors deliver value through the application itself (intake, drafting, discovery, audit workflows) rather than as a developer platform. Eve's competitive moat is the workflow, the firm-specific style training, and the Auditor's value-driver pattern recognition — none of which are currently exposed as developer primitives.

---

## Practice Areas

- **Personal Injury** — the flagship segment; medical chronology, demand-letter, and discovery workflows are tuned for PI economics.
- **Labor & Employment** — second documented practice area.
- **Plaintiff work generally** — the brand positioning is plaintiff-side across the board.

---

## Reported Customer Outcomes

Numbers Eve publishes on its homepage and customer-story pages (vendor-reported, not independently verified):

- **1,000+** plaintiff firms using Eve
- **250%** year-over-year revenue increase at adopting firms (representative case)
- **2.5x** increase in case capacity
- **90%** faster demand-letter generation
- **5x** faster automated document review
- **30 min** to a comprehensive medical overview
- **4.9 / 5** rating on G2

Customer stories on the site include the Mike Morse Law Firm, Atlanta Personal Injury Law Group, Jeffrey Glassman Injury Lawyers, Frontier Law Center, Sconzo Law Office, and the Law Office of Eric R. Brown.

---

## Security & Trust

Eve markets the following posture (from `eve.legal` FAQ and trust copy):

- **SOC 2 Type 2** certified — Eve claims to be the first legal AI to achieve this.
- **HIPAA compliant** — required for medical records ingestion.
- **Data isolation** at organization, user, and workflow level.
- **No training on customer data** — case data is not used to train shared models.
- **Encryption** of case data at rest and in transit (per marketing copy).
- **Attorney-client privilege as a first principle** — Eve explicitly contrasts this with consumer AI tools (e.g. ChatGPT) where courts have found that running active matters through them can eliminate privilege.

A formal trust portal or detailed sub-processor list is not linked from the public site.

---

## Company

- **Legal entity:** Butler Labs, Inc.
- **Operating brand:** Eve / eve.legal
- **Founders:**
  - **Jay Madheswaran** — Founder & CEO; 15+ years in AI/ML at Facebook and Rubrik; previously at Lightspeed Venture Partners.
  - **Matt Noe** — Co-founder & CPO; founding engineer at Rubrik; a decade of AI product experience.
  - **David Zeng** — Co-founder & Head of Engineering; 10+ years in AI/ML.
- **Funding:** $164M+ from "leading investors" (specific names and round breakdowns are not enumerated on the public site).
- **Hiring posture:** actively hiring; engineering and design organized into small, end-to-end product pods.

---

## How to Engage

Because Eve has no self-serve public API or free tier, the engagement model is:

1. **Schedule a call / Book a demo** at [eve.legal/schedule-a-call](https://www.eve.legal/schedule-a-call).
2. **Refer a firm** via the partner program at [eve.legal/refer-a-firm](https://www.eve.legal/refer-a-firm).
3. **Existing customers** sign in at [app.eve.legal](https://app.eve.legal).
4. **Career / engineering** interest: [eve.legal/careers](https://www.eve.legal/careers).

---

## Watch For

Things that would move this profile toward a **Tier-1** (machine-readable API contract) profile in the future:

- A documented public API or partner API for case data, intake, or discovery.
- An OpenAPI specification, even a partner-only one.
- Webhook contracts for intake events, demand-letter completion, or Auditor findings.
- Iroquois-style **outbound** integrations into case management systems (Litify, Filevine, CASEpeer, SmartAdvocate, Clio) — these almost certainly exist behind the scenes for Eve to be useful, and may eventually be exposed as a named integration surface.
- The first public repository in [github.com/eve-legal](https://github.com/eve-legal) — likely an SDK, MCP server, or sample integration when it appears.
- A `docs.eve.legal` or `developers.eve.legal` subdomain coming online.
- A formal trust portal (sub-processors, SOC 2 report request workflow).

---

## Files In This Repo

- [`apis.yml`](./apis.yml) — APIs.json catalog entry for Eve.
- `README.md` — this file.

No `openapi/`, `asyncapi/`, `json-schema/`, `capabilities/`, `rules/`, `plans/`, `rate-limits/`, or `finops/` artifacts are generated for this provider, because Eve does not currently publish the underlying machine-readable contracts or pricing surface needed to back them. Per the API Evangelist pipeline's "no placeholder specs" rule, the matching directories are intentionally absent.

---

*Profile maintained by [Kin Lane](https://apievangelist.com), API Evangelist.*
