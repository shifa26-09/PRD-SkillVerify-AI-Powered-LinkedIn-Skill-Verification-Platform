# SkillVerify: AI-Powered LinkedIn Skill Verification Platform

**A clickable prototype for a product that turns self-reported LinkedIn skills into evidence-backed, recruiter-trusted credentials.**

🔗 **[Live demo](https://prd-skill-verify-ai-powered-linked.vercel.app/)**: 5 interactive screens, no signup required
📄 **[Full PRD](https://app.notion.com/p/38c9422dc78d81df944bc313268c70c1)**: 19-section product requirements document

---

## The problem

Anyone can list "Python Expert" on LinkedIn with zero verification. Recruiters know this, which is why technical screening still takes days even for genuinely qualified candidates. There's no portable, evidence-backed signal recruiters can filter on *before* investing screening time.

## What this is

SkillVerify connects LinkedIn, ingests evidence (resume, GitHub, certificates), runs AI-generated adaptive assessments, and produces an **explainable** 0 to 100 confidence score per skill. Never a black-box number. Recruiters get a dashboard to search and filter candidates by verified skill instead of skimming resumes.

This repo contains the **frontend prototype only**: a single static HTML file with no backend. All data is hardcoded/simulated to demonstrate the product flow end-to-end.

## Screens

| Screen | What it shows |
|---|---|
| **Landing** | Value proposition, "How it works" walkthrough modal, login flow |
| **Job Seeker Dashboard** | Skill cards with tiered badges, evidence sources, and a Skill Gap Intelligence panel comparing scores against live job-market demand |
| **AI Assessment** | Adaptive question flow with a real-time score projection |
| **Public Verification Profile** | Shareable, recruiter-facing badge profile with evidence breakdown |
| **Recruiter Dashboard** | Filterable candidate search, match scoring, and outcome-tagging (hired/rejected) that feeds the scoring model's calibration loop |

## Key design decisions

- **Explainable scoring, not a black box.** Every score breaks down into its evidence sources (assessment, code, certs, resume) so recruiters can see *why* a number is what it is. That's the trust mechanism the whole product depends on.
- **Standalone value for job seekers from day one.** The Skill Gap Intelligence panel gives candidates a reason to verify even with zero recruiters on the platform. This avoids the classic two-sided marketplace cold-start problem.
- **A compounding moat, not just a feature.** Recruiter-confirmed hiring outcomes feed back into the scoring model, so the weighting gets more accurate the longer the product runs. This is something a competitor can't copy by cloning the UI.

## Status

Concept, prototype, and full PRD complete. Pre-build stage. This is a portfolio/case-study artifact, not a production product.

## Author

Shifa Fatima 
