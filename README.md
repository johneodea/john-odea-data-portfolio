# John O'Dea — Data & AI Portfolio

> **Principal Data Analyst | Enterprise Data Steward | Healthcare Payor Analytics**
> Springfield, OR · john.e.odea@gmail.com · [LinkedIn](https://www.linkedin.com/in/john-odea-569359408)

---

## Who I Am

I've had six careers at one company — claims operations, IS modernization, enterprise project management, facilities architecture, operational reporting, and now enterprise data platform leadership. That's 30 years of going where the organization needed someone who could figure things out.

Today I'm a Principal Data Analyst and Enterprise Data Steward at Providence Health Plan, supporting a Snowflake-native data mesh environment serving 17 analytics teams across a 1,300-caregiver regional health plan. I work at the intersection of healthcare payor operations and the data architecture that supports it — a combination that's harder to find than it should be.

I use AI — primarily Claude and Snowflake Cortex — as a genuine thought partner: not to replace domain expertise, but to amplify it and get from raw data to actionable insight faster than was ever practical before.

---

## What This Repository Is

This is a living portfolio and thought leadership hub. It contains:

- **My data philosophy** — how I think about data, AI, and organizational intelligence
- **Code and query templates** — Snowflake SQL patterns, semantic view structures, data quality frameworks
- **Reference material** — data dictionaries, governance artifacts, onboarding guides
- **A roadmap** — where I am today and where I'm headed

This is not a polished product. It's a working document that evolves as I learn.

---

## Table of Contents

- [Philosophy](#philosophy)
- [Technical Stack](#technical-stack)
- [Current Work](#current-work)
- [Roadmap](#roadmap)
- [Code & Templates](#code--templates)
- [Governance Artifacts](#governance-artifacts)
- [AI & Thought Partnership](#ai--thought-partnership)
- [Conference Notes](#conference-notes)
- [Contact](#contact)

---

## Philosophy

Data is not rows and columns. Data is a system — raw inputs, transformation logic, business rules, domain context, and the human judgment that turns all of it into a decision. My job is to understand that entire system, not just the tables at the end of it.

A few principles I work by:

**1. Domain expertise is the multiplier.**
AI tools are only as good as the domain knowledge you bring to them. Knowing how a claim moves through adjudication, what an HCC code means clinically, or why a HEDIS hybrid measure requires a medical record — that context is what makes the difference between an analyst who produces output and one who produces insight.

**2. AI is a thought partner, not an oracle.**
I use Claude and Snowflake Cortex the way I'd use a brilliant colleague with no ego and infinite patience — to go deeper, faster, and to pressure-test my thinking. The judgment still has to be mine.

**3. Personal productivity is just the beginning.**
The real opportunity in AI is organizational. How do you take what one expert learns and make it institutional knowledge? How do you give AI a golden definition that your whole organization agrees on, so the answers are consistent regardless of who's asking or which analyst they reached?

**4. The telephone problem is a data governance problem.**
When a business question passes through three people before it reaches an analyst, nuance dies at every handoff. Standardized definitions, governed vocabulary, and AI grounded in institutional knowledge — not individual interpretation — is how you fix that at scale.

**5. Actionability is the output.**
Analysis that doesn't inform a decision is expensive noise. Every data product I build is designed with the end consumer in mind — what do they need to know, what decision does it support, and what does it cost them if it's wrong?

---

## Technical Stack

| Layer | Tools |
|---|---|
| **Data Warehouse** | Snowflake Enterprise |
| **Architecture** | Data Mesh (12 meshes), Medallion Schema, SDM Fact/Dimension |
| **Semantic Layer** | Snowflake Semantic Views (Inpatient, HEDIS, General) |
| **AI / Cortex** | Snowflake Cortex (CoCo), Claude (Anthropic) |
| **Visualization** | Power BI, Tableau Server |
| **Integration** | FHIR R4, CDC Pipelines, Abacus, SS&C, First Databank |
| **DevOps** | Azure DevOps (CI/CD, Sprint Planning, Work Item Tracking) |
| **Collaboration** | MS Teams, SharePoint, Confluence, Office 365 |
| **Healthcare Domain** | Cognizant Facets (Elements, CareAdvance, TCS), HEDIS, HCC/Risk Adjustment, ICD-10/CPT |

---

## Current Work

### Enterprise Data Management — Providence Health Plan (2024–Present)

- Supporting a Snowflake environment with **16.1 billion rows**, **~13,000 tables**, **1,235 Bronze-layer tables**, and **300+ users** across 17 analytics teams
- Designing and maintaining the SDM (Snowflake Data Mart) — the primary Power BI consumption layer — with semantic views for Inpatient, HEDIS, and general enterprise reporting
- Serving as analyst community representative on a C-suite data governance committee (CFO, CMO, COO, Chief Growth Officer, Chief Medical Officer, Chief Enterprise IS Officer)
- Building a RACI-based reporting transition tracker managing migration of 1,500+ reports and data products to Snowflake (~90% complete)
- Standing up an enterprise analyst Community of Practice as the central hub for documentation, definitions, and knowledge sharing

### Active AI Use Cases

- **CareAdvance Data Dictionary** — used Claude to navigate Cognizant CareAdvance metadata and produce a structured data dictionary now used enterprise-wide for analyst onboarding
- **Snowflake Cortex (CoCo)** — active use for query assistance, metadata analysis, and data structure exploration
- **Session context optimization** — experimenting with persistent knowledge frameworks, reference material generation, and profile-based AI configuration to reduce compute overhead and improve response quality over time

---

## Roadmap

### Where I Am Today

**Personal AI Productivity**
- Claude as thought partner for data analysis, framing, and documentation
- Snowflake Cortex (CoCo) for in-warehouse AI assistance and query development
- Reference material generation — CareAdvance data dictionary built from metadata
- Session context and profile optimization experiments to reduce compute overhead

### Near Horizon (6–12 months)

**Socialization of Learnings**
- Community of Practice — sharing what works across 17 analyst teams
- Standardized AI prompting frameworks for common analytical tasks
- Onboarding guides and reference material tied to Confluence
- Data dictionary as a shared AI reference layer accessible to all analysts

### Mid Horizon (12–24 months)

**Organizational AI Intelligence**
- Golden definitions — governed vocabulary accessible to AI across the enterprise
- Data Governance program delivering authoritative, standardized definitions
- AI grounded in institutional knowledge, not individual interpretation
- Elimination of the telephone problem through consistent, governed meaning
- High-quality analytical output that doesn't depend on which analyst you reached

### Far Horizon (2+ years)

**Persistent Institutional Knowledge**
- AI that knows our data environment, our definitions, and our history
- Session continuity — AI that builds on prior context over time
- Automated reference material updates as data and definitions evolve
- Cross-team analytical consistency at enterprise scale
- AI-assisted governance — flagging definitional drift and surfacing conflicts

---

## Code & Templates

> *Coming soon — actively building out*

### Snowflake SQL Patterns
- Semantic view design templates
- Window function patterns for claims analytics
- HEDIS measure logic frameworks
- Data quality validation queries
- Dev→Prod pipeline promotion scripts

### Data Mesh Patterns
- Object creation standards for BI mesh
- Cross-boundary governance query patterns
- Zero-copy clone workflows for analytical snapshots

### AI Prompting Templates
- Data dictionary generation prompt framework
- Metadata analysis prompts for unfamiliar schemas
- Analytical framing prompts for business questions
- Reference material generation and update workflows

---

## Governance Artifacts

> *Sanitized and de-identified examples — actively building out*

- Data dictionary template (CareAdvance pattern)
- RACI framework for report migration tracking
- Analyst onboarding guide structure
- Community of Practice site architecture
- Domain ownership taxonomy template
- Data quality standards framework

---

## AI & Thought Partnership

### How I Use AI in Practice

I come at AI from the business problem side. The workflow I've developed:

**Business Question**
- What is the business actually trying to decide or understand?

**Domain Context**
- What do I know about this operationally — claims, HEDIS, risk adjustment, enrollment?

**Data Structure Exploration**
- Use Claude or CoCo to navigate schema, metadata, and table relationships

**Analytical Framing**
- What does this data actually mean in context?

**Insight Development**
- What story does this tell, and is it the right story?

**Actionability Layer**
- What decision does this support, and what does it cost if it's wrong?

**Socialization**
- How do I share this so others benefit — and so the organization gets smarter, not just me?

### What I'm Thinking About

**The socialization problem** — personal AI productivity is table stakes. The harder question is: how do you make what one expert learns available to the whole organization? How do you socialize AI workflows, prompting patterns, and analytical frameworks so the knowledge compounds rather than staying siloed?

**The golden definition problem** — AI is only as consistent as the definitions it draws from. A data governance program that produces governed, standardized definitions — and makes them accessible to AI as reference material — is the foundation of organizational AI intelligence.

**Persistent AI** — I'm actively interested in AI systems that build knowledge about you, your data environment, and your preferences over time. Session logs, user profile updates, reference material generation — the goal is an AI that gets more efficient with every interaction rather than starting from zero each session.

---

## Conference Notes

> *This section will be updated following each conference attended*

### AI Conference — 2026
*Notes and reflections coming post-event*

**Questions I'm bringing:**
- How are organizations moving from personal AI productivity to institutional AI knowledge?
- What does a governed, AI-accessible definition layer actually look like in practice?
- How are others solving the telephone problem — where business questions lose nuance through multiple handoffs before reaching an analyst?
- What is the state of persistent AI — systems that build context about you and your environment over time?

---

## Contact

I'm always interested in conversations at the intersection of healthcare payor operations, data architecture, and AI as organizational intelligence.

- **Email:** john.e.odea@gmail.com
- **LinkedIn:** [linkedin.com/in/john-odea-569359408](https://www.linkedin.com/in/john-odea-569359408)
- **Location:** Springfield, OR

> *Open to conversations about Principal Data Analyst and Data Architect opportunities in healthcare payor.*

---

*Last updated: July 2026*