# Hi, I'm Olabode Sharif 👋

**Senior AI Evaluator & Trainer | LLM Evaluation, RLHF & QA | Software Engineer | Ph.D., Data Science**

Senior AI Evaluator & Trainer with a Ph.D. in Data Science and 7 years in model evaluation and AI training data. I evaluate LLM responses for factual accuracy, reasoning, instruction-following and safety, design evaluation datasets and scoring frameworks, and build the software behind them. Since 2019 at iMerit, promoted to Annotation QA Reviewer, I have evaluated 12,000+ LLM responses across 8+ projects at a 97% quality rating; since 2020 at Databricks I have built evaluation pipelines supporting 75,000+ LLM test cases. I am also a Senior Software Engineer at Seamfix, building identity verification, KYC and digital onboarding systems.

- 📄 **CV:** [github.com/Sharif899/cv](https://github.com/Sharif899/cv) · [Download CV (PDF)](https://github.com/Sharif899/cv/blob/main/sherif-olabode-cv.pdf)
- 💻 Portfolio: https://0xninofi.vercel.app
- 🔗 LinkedIn: https://linkedin.com/in/sherif-olabode-128306415
- 📬 Email: sharifninolee@gmail.com
- 🌍 Based in Nigeria, working remotely
- 📬 Open to freelance projects, startup collaborations and remote opportunities

---

## Experience

- **AI Trainer & Annotation QA Reviewer — iMerit** | Remote, Freelance | 2019–Present
  LLM evaluation and RLHF, pairwise preference comparisons, adversarial prompts, rubric design, annotation QA and calibration. Promoted from AI Annotator to QA Reviewer after one year.
- **AI Evaluation Engineer — Databricks** | Remote, Part-time | Jul 2020–Present
  Python evaluation pipelines for 20+ ML models, evaluation datasets and scoring frameworks for 75,000+ LLM test cases, automated testing with SQL, Apache Spark and MLflow.
- **Senior Software Engineer — Seamfix Nigeria** | Lagos | 2020–Present
  Backend services for identity verification, KYC and digital onboarding in Java, Spring Boot, Python and PostgreSQL. Promoted to Senior in 2022; mentored 80+ interns.
- **AI Training Expert — micro1, Runway Annotations Project** | Remote
  Image/video annotation and computer-vision labelling, AI data QA with CVAT, Labelbox, SuperAnnotate and Roboflow.

## Education & Certifications

- **Ph.D., Data Science** — Obafemi Awolowo University, 2019
- **M.Sc., Data Science and Artificial Intelligence** — Ladoke Akintola University of Technology, 2015
- **B.Sc., Computer Science** — Obafemi Awolowo University, 2011
- ISTQB Certified Tester – AI Testing (CT-AI v2.0), Jan 2026
- Google Cloud Professional Machine Learning Engineer, Jul 2025
- AWS Certified Machine Learning Engineer – Associate, Feb 2025

---

## Featured Projects

### 1. [OsogboRent](https://github.com/Sharif899/houseplug) — live at [osogborent.com](https://osogborent.com)

A real-estate platform connecting tenants with verified agents and landlords in Osogbo, Nigeria. Houses and shops for rent and sale, with search by area, property type and price, featured and recent listings, a request board, agent dashboard and listing submission.

**Tech:** Next.js 14, TypeScript, Tailwind CSS, Supabase, Vercel

### 2. [llm-eval-toolkit](https://github.com/Sharif899/llm-eval-toolkit)

Offline, deterministic, rubric-based LLM evaluation — the workflow I use as an AI evaluator, in code. Scores a response 1–5 on factual accuracy, reasoning, instruction adherence, helpfulness and safety, each with a structured rationale; pairwise RLHF comparison with evidence-backed rankings; hallucination checks against a reference (supported / contradicted / unverifiable); and annotation QA with Cohen's kappa, per-label agreement and a disagreement report. Includes 10 synthetic example items, including a Yoruba/English one, and 42 passing tests.

**Tech:** Python, standard library only, pytest, CLI

### 3. [kyc-onboarding-service](https://github.com/Sharif899/kyc-onboarding-service)

Identity verification & KYC onboarding service in Java and Spring Boot — the Seamfix stack in code. Document validation for NIN, passport and driver's licence, duplicate detection, idempotent requests, a verification workflow (PENDING → UNDER_REVIEW → VERIFIED / REJECTED / NEEDS_MORE_INFO) with a full audit log, and document numbers masked to the last 4 digits in every response and log line. 54 passing tests, verified with a live smoke test.

**Tech:** Java 21, Spring Boot 3, Spring Data JPA, H2, JUnit 5, MockMvc, GitHub Actions

### 4. [ai-safety-red-teaming](https://github.com/Sharif899/ai-safety-red-teaming)

Offline, deterministic AI safety red-teaming toolkit — adversarial testing for LLMs, in code. Ten attack techniques (role-play, instruction override, authority and hypothetical framing, multi-step escalation, leetspeak / base64 / reversed encoding, refusal suppression), refusal classification (refusal / partial compliance / compliance), unsafe-output detection across six harm categories, and attack success rate plus a consistency score showing whether a model refused the same request every way or let one variant through. Includes a mock target model and a harness to score a real model's recorded outputs. On the example data: 50% attack success rate, 0% consistency — direct requests refused every time, role-play and encoding attacks succeeding every time. 82 passing tests.

**Tech:** Python, standard library only, pytest, CLI

### 5. [annotation-qa-toolkit](https://github.com/Sharif899/annotation-qa-toolkit)

Annotation QA for image and video labelling — the review work I do as an Annotation QA Reviewer, in code. Reads COCO, YOLO, Pascal VOC, Labelbox, SuperAnnotate and Roboflow exports into one model; runs ten QA checks (out-of-bounds and degenerate boxes, duplicates, heavy overlap, tiny boxes, empty annotations, unknown and near-duplicate class names, rare classes, orphan annotations); measures agreement between two annotators with Cohen's kappa and IoU-based box matching; and scores every image for quality. On the example data: 7 findings on one annotator's set, kappa 0.886 between the two annotators, box match rate 0.833. 88 passing tests.

**Tech:** Python, standard library only, pytest, CLI

### 6. [sql-eval-analytics](https://github.com/Sharif899/sql-eval-analytics)

SQL and PostgreSQL analytics for AI evaluation operations — the database side of the Databricks and Seamfix work, in code. A PostgreSQL-first schema for annotators, items, annotations, reviews and model scores, with ten analytical queries a QA lead actually runs: annotator agreement with Cohen's kappa, review turnaround, reject rates by cohort, score calibration, duplicate submissions, workload and overconfidence. Runs locally on SQLite and against real PostgreSQL. On the example data: agreement 80.0% with kappa 0.643, one reviewer averaging 116.9 hours against 17.3 for the fastest, a 12.9% reject rate that runs 28.6% for juniors against 0% for seniors, and one junior 0.88 confident while agreeing only 73.3% of the time. 34 passing tests.

**Tech:** Python, PostgreSQL, SQL, sqlite3, psycopg, pytest, CLI

---

## What I Build

- **AI evaluation & training data** — LLM evaluation, RLHF, rubrics, annotation QA, calibration, hallucination detection, AI safety and red-teaming
- **SaaS & web applications** — Next.js, React, TypeScript, Tailwind CSS, Node.js
- **Marketplaces & platforms** — listings, search and filters, dashboards, payments, escrow
- **Web3 products & dApps** — smart contracts (Solidity, Hardhat), Arc, Mantle, SKALE, Base, OpenGradient, 0G
- **AI-powered tools** — AI agents, trading signals, verifiable AI output, dashboards
- **MVPs for startups** — from idea to a live, working product

## Tech Stack

Python • SQL • Java • TypeScript • Next.js • React • Tailwind CSS • Node.js • pandas • NumPy • scikit-learn • Apache Spark • MLflow • Spring Boot • PostgreSQL • Supabase • Firebase • Prisma • Solidity • Hardhat • Docker • Vercel • Railway

---

## Open To Work

- Freelance projects
- Startup collaborations
- Remote opportunities

Portfolio: https://0xninofi.vercel.app · CV: https://github.com/Sharif899/cv

For OsogboRent enquiries: info@osogborent.com · +234 806 666 1895
