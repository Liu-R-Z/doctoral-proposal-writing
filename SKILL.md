---
name: doctoral-proposal-writing
description: |
  Use when the user asks to draft, restructure, or audit a Chinese doctoral or master's research proposal, opening report, or research plan. Turn a research topic or supplied materials into a bounded scientific problem, evidence-aware literature gap, why-what-how design, goal-content-method matrix, technical route, evaluation plan, risks, and next actions. Do not use for standalone topic discovery, full literature novelty audits, experiment protocols, language polishing, translation, or formatting when the research design is already fixed. Never invent citations, data, results, novelty, official requirements, or endorsements.
---
# Academic Writing: Research Proposal Design

Use this Skill to move a research idea from topic to executable proposal. The method framework was distilled from a Chinese academic-writing course taught by a Yangtze River Scholar and implemented as an independent Skill.

## Trigger boundary

### Trigger

Use when the request contains proposal context and asks to:

- draft or expand a doctoral or master's opening report;
- restructure a research proposal or research plan;
- turn a topic and materials into research questions, objectives, contents, methods, or a technical route;
- audit proposal logic, feasibility, innovation claims, or risks.

### Do not take over

Hand off or stay narrow when the request is only:

- discovering topics without a proposal-design goal;
- conducting a complete literature search or novelty audit;
- designing an approved experiment or statistical protocol;
- polishing, translating, typesetting, or adapting a fixed design;
- checking a school's latest official template without supplied requirements.

## Operating protocol

1. **Classify the intent.** Choose one primary mode: `problem-framing`, `topic-gap`, `design`, or `audit`.
2. **Inspect the supplied material.** Separate what the user supplied from what is inferred. If a material decision is missing, ask one highest-priority question at a time. For a research request, resolve the core problem before asking about data, method, or venue.
3. **Build an evidence ledger.** Mark important statements as one of:
   - `[已提供事实]` — directly present in user material or a checked source;
   - `[用户假设]` — supplied as an assumption, not yet verified;
   - `[候选方案]` — a proposed research or method option;
   - `[预期结果]` — a result the study may produce, not an observed result;
   - `[待核验]` — requires literature, data, policy, method, or permission checks.
4. **Load only what is needed.** Read the primary capability card first. Add at most one helper card when its condition is met. Do not load all capability cards by default.
5. **Produce the mode-specific output.** Use the contracts below and keep claims no stronger than their evidence status.
6. **Run the closeout check.** Confirm that the core problem, evidence, goal, content, method, evaluation, expected output, risks, and unresolved decisions are visible and connected.

## Mode contracts

### `problem-framing`

Return:

- research object and context;
- observed phenomenon or practical pressure;
- central tension;
- one bounded core scientific question;
- two to four supporting questions, if needed;
- scope and exclusions;
- observable outcomes;
- unresolved assumptions.

Do not turn a product, platform, algorithm, or broad field name into a scientific question.

### `topic-gap`

Return:

- literature comparison dimensions;
- established findings and disagreements, each with source status;
- candidate gap;
- relation to the proposed study;
- similar-work checks still required;
- current claim strength: `candidate`, `partially supported`, or `verified`.

Without supplied or independently checked literature, write a candidate gap and a retrieval task. Do not claim “first,” “fills a gap,” or complete coverage.

### `design`

Build the proposal in this order:

1. why: source of the problem, purpose, significance, and boundary;
2. what: overall objective, two to five research contents, key questions, and expected outputs;
3. how: data or materials, theory, method, technical route, evaluation, stages, dependencies, and risks.

Always include a goal-content-method-evaluation-output matrix. A missing field remains `[待核验]` or `[待补充]`; do not fill it with generic facts. Distinguish a proposal skeleton, a draft, and a submission-ready document.

### `audit`

Return findings in priority order:

- **Blocker**: prevents a credible proposal or makes the planned study unactionable;
- **Major**: weakens evidence, logic, novelty, or feasibility;
- **Minor**: can be fixed during expansion or polishing.

For every finding, give the location, reason, evidence status, concrete fix, and the layer to revisit: problem, gap, method, evaluation, or output. Do not silently rewrite a blocked design into a different study.

## Stop conditions

Stop at a structured draft plus a confirmation list when any of these is missing:

- a bounded research problem;
- evidence for a literature or novelty claim;
- data, access, sample, or permission needed by the proposed method;
- an evaluation criterion for the claimed result;
- a current institutional or venue requirement that the user expects to be followed.

Do not invent citations, data, experiments, findings, supervisor opinions, funding, institutional rules, or publication outcomes. Do not present a course example as evidence for the user's field.

## Capability routing

| Intent | Primary card | Add one helper only when |
|---|---|---|
| Narrow a broad topic into a research question | `references/capabilities/problem-framing.md` | a concrete literature gap is already part of the request |
| Compare prior work and locate a gap | `references/capabilities/topic-gap-analysis.md` | the research problem itself is still ambiguous |
| Build or restructure a proposal | `references/capabilities/design.md` | the core problem is unclear or a supplied literature gap must be checked |
| Audit an existing proposal | `references/capabilities/audit.md` | the audit finds a missing design mapping that must be reconstructed |

For terminology, rules, or the full capability index, read `references/glossary.md`, `references/cheatsheet.md`, or `references/capability-index.md` only when needed. Use `references/overview.md` for a high-level description.
