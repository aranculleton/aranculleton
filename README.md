# Aran Culleton

**Data Science Consultant at Xantura (Newton Europe)** · previously British Airways and the BBC

I build models and data pipelines that change operational decisions: risk scoring,
forecasting and pricing, and the engineering that makes them trustworthy in production.

- **Focus:** applied machine learning · risk decisioning · forecasting · analytics engineering
- **Recent:** prioritization models over 1.5M+ sensitive records; ingestion and QA workflows that cut data-prep cycles from weeks to days
- **Stack:** Python · SQL · scikit-learn · Airflow · dbt · Azure Data Factory · Snowflake · Databricks · AWS · Power BI
- **Certified:** Databricks Data Engineer Associate · AWS Machine Learning Engineer Associate

## Projects

### [last-job-search](https://github.com/aranculleton/last-job-search)

An AI agent system that runs a whole job search on Claude Code, from finding the roles to
preparing for the interview.

- **Finds and ranks** thousands of postings per run across job boards and employers' own
  careers systems, scoring each against the candidate in deterministic Python, so models are
  used only where judgement matters
- **Writes and verifies** a tailored resume and cover letter for each chosen role, checks
  every claim against the candidate's real history, and reads each PDF the way an applicant
  tracking system does
- **Works the network:** finds the right people at each employer, drafts the outreach,
  tracks every thread, and keeps a cold application from landing on top of a warm introduction
- **Learns from results:** which messages drew replies and which applications reached
  interview shape what it does next
- Human in the loop by design: it never sends anything. A public template people copy into
  a private repo that keeps itself updated, with 900+ tests

### [openroles](https://github.com/aranculleton/openroles)

An open-source Python library and MCP server: one interface to employers' own job boards on
Greenhouse, Lever, Ashby and Workday.

- Finds which system a company uses from its name or careers page
- One schema across all four, with no API key and no dependencies
- Polite by design: honours robots.txt and backs off when a board asks
- Works as a CLI, a Python API, or a tool any AI agent can call

### [CaseSignal](https://github.com/aranculleton/casesignal)

A credit-risk decisioning prototype on synthetic data, inspired by my work at Xantura
(Newton Europe). It ranks accounts by escalation risk with a transparent baseline model plus
auditable, AI-extracted signals from servicing notes, and tests whether those signals
improve top-k review.

### [CopulAX](https://github.com/aranculleton/copulax) · contributor

A JAX library for copula modelling and probability distributions.

## Away from data

I'm also a chef. Off the clock you'll find me cooking, travelling, or watching films and
logging every one on [Letterboxd](https://letterboxd.com/ar9n/).

## Find me

[LinkedIn](https://www.linkedin.com/in/aranculleton)
