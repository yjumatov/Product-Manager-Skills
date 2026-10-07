---
name: product-manager-skills
description: 77 product management skills (discovery, strategy, delivery, finance, AI PM, market intel, lifecycle/EOL, career). Use for PM tasks like PRDs, user stories, roadmaps, pricing, competitive analysis.
---

# Product Manager Skills (compact edition)

A library of 77 PM skills in one bundle. This file is the router: pick the matching skill below, **read its file in `references/`, and follow it exactly** as if it were the active skill. Do not load more than the one to three skills you need.

## How to use

1. Match the user's request to the best skill in the index (use the "Use when" column).
2. Read `references/<skill-name>.md`. Follow its Purpose, Input, and Application sections.
3. If the index shows `+tpl`, the fill-in output template is at `templates/<skill-name>.md`. Use it for the deliverable.
4. Skill types: **Component** = produce one artifact; **Interactive** = ask 3-5 questions one at a time, then offer numbered options; **Workflow** = run a multi-step process.
5. Skills cross-reference each other by name (e.g. `prioritization-advisor.md`) and live side by side in `references/`.
6. If several skills fit, name the top two and recommend one. If none fit, say so and work without a skill.

For interactive or facilitated skills, also read `references/workshop-facilitation.md` for the shared facilitation protocol.

## Skill index

### ai-agents

| Skill | Type | Use when |
|---|---|---|
| [agent-orchestration-advisor](references/agent-orchestration-advisor.md) | interactive | Design multi-agent AI workflows with clear boundaries, handoffs, and monitoring. Use when a complex PM task should run as parallel specialized agents instead of one linear process. |
| [ai-shaped-readiness-advisor](references/ai-shaped-readiness-advisor.md) | interactive | Assess whether your product work is AI-first or AI-shaped. Use when evaluating AI maturity and choosing the next team capability to build. |
| [context-engineering-advisor](references/context-engineering-advisor.md) | interactive | Diagnose context stuffing vs. context engineering. Use when an AI workflow feels bloated, brittle, or hard to steer reliably. |

### career-leadership

| Skill | Type | Use when |
|---|---|---|
| [altitude-horizon-framework](references/altitude-horizon-framework.md) +tpl | component | Understand the PM-to-Director transition through altitude and horizon thinking. Use when diagnosing scope, time-horizon, or leadership-level gaps. |
| [director-readiness-advisor](references/director-readiness-advisor.md) | interactive | Guide the PM-to-Director transition across preparing, interviewing, landing, and recalibrating. Use when leadership scope is changing and you need practical coaching. |
| [executive-onboarding-playbook](references/executive-onboarding-playbook.md) +tpl | workflow | Plan a VP or CPO 30-60-90 day diagnostic onboarding path. Use when entering a new executive product role and avoiding premature change. |
| [product-sense-interview-answer](references/product-sense-interview-answer.md) +tpl | component | Structure a spoken PM product-sense answer with assumptions, segmentation, pain-point prioritization, and MVP tradeoffs. Use when practicing design, improve, or build-next interview questions. |
| [vp-cpo-readiness-advisor](references/vp-cpo-readiness-advisor.md) | interactive | Guide the transition to VP or CPO across preparing, interviewing, landing, and recalibrating. Use when executive product scope is changing fast. |

### discovery-research

| Skill | Type | Use when |
|---|---|---|
| [discovery-interview-prep](references/discovery-interview-prep.md) | interactive | Plan customer discovery interviews with the right goal, segment, constraints, and method. Use when preparing interviews for problem validation, churn research, or new product ideas. |
| [discovery-process](references/discovery-process.md) +tpl | workflow | Run a full discovery cycle from problem hypothesis to validated solution. Use when a team needs a structured path through framing, interviews, synthesis, and experiments. |
| [jobs-to-be-done](references/jobs-to-be-done.md) +tpl | component | Uncover customer jobs, pains, and gains in a structured JTBD format. Use when clarifying unmet needs, repositioning a product, or improving discovery and messaging. |
| [opportunity-solution-tree](references/opportunity-solution-tree.md) +tpl | interactive | Build an Opportunity Solution Tree from outcomes to opportunities, solutions, and tests. Use when a stakeholder request needs problem framing before you decide what to build. |
| [problem-framing-canvas](references/problem-framing-canvas.md) +tpl | interactive | Guide teams through MITRE's Problem Framing Canvas. Use when you need a clearer problem statement before jumping to solutions. |
| [problem-statement](references/problem-statement.md) +tpl | component | Write a user-centered problem statement with who is blocked, what they are trying to do, why it matters, and how it feels. Use when framing discovery, prioritization, or a PRD. |
| [proto-persona](references/proto-persona.md) +tpl | component | Create a proto-persona from current research, market signals, and team knowledge. Use when you need a working customer profile before deeper validation. |

### eol-transition

| Skill | Type | Use when |
|---|---|---|
| [eol-checklist](references/eol-checklist.md) +tpl | component | Build a phase-gated EOL checklist sized to the sunset, with a named owner on every item. Use when the decision to retire is made and you need the operational plan. |
| [eol-internal-enablement](references/eol-internal-enablement.md) +tpl | component | Build the support FAQ, sales talking points, and objection handling teams need before an EOL announcement. Use when customer-facing teams must be ready before customers hear. |
| [eol-message](references/eol-message.md) +tpl | component | Write a right-sized EOL announcement — brief notice through full phased comms — with rationale, customer impact, and next steps. Use when retiring a product, feature, or plan. |
| [eol-process](references/eol-process.md) +tpl | workflow | Run a product sunset end to end — decide, align, plan, prepare, announce, close. Use when you need the whole EOL process, not just one artifact. |
| [eol-readiness-advisor](references/eol-readiness-advisor.md) | interactive | Run a go/no-go assessment for retiring a product or feature, then right-size the effort. Use when someone says \"we should probably kill this\" and nobody has made the call. |
| [eol-stakeholder-sequence](references/eol-stakeholder-sequence.md) +tpl | component | Plan who to talk to about a sunset, in what order, and what each conversation must cover. Use when an EOL decision is made and you want the landmines found before the announcement. |

### finance-metrics

| Skill | Type | Use when |
|---|---|---|
| [acquisition-channel-advisor](references/acquisition-channel-advisor.md) | interactive | Evaluate acquisition channels using unit economics, customer quality, and scalability. Use when deciding whether to scale, test, or kill a growth channel. |
| [business-health-diagnostic](references/business-health-diagnostic.md) | interactive | Diagnose SaaS business health across growth, retention, efficiency, and capital. Use when preparing a business review or prioritizing urgent fixes. |
| [feature-investment-advisor](references/feature-investment-advisor.md) | interactive | Evaluate feature investments using revenue impact, cost structure, ROI, and strategy. Use when deciding whether a feature deserves investment. |
| [finance-based-pricing-advisor](references/finance-based-pricing-advisor.md) | interactive | Evaluate pricing changes using ARPU, conversion, churn risk, NRR, and payback. Use when deciding whether a pricing move should ship. |
| [finance-metrics-quickref](references/finance-metrics-quickref.md) +tpl | component | Look up SaaS finance metrics, formulas, and benchmarks fast. Use when you need a quick metric definition, formula, or benchmark during analysis. |
| [saas-economics-efficiency-metrics](references/saas-economics-efficiency-metrics.md) +tpl | component | Evaluate SaaS unit economics and capital efficiency. Use when deciding whether the business can scale efficiently or needs correction. |
| [saas-revenue-growth-metrics](references/saas-revenue-growth-metrics.md) +tpl | component | Calculate SaaS revenue, retention, and growth metrics. Use when diagnosing momentum, churn, expansion, or product-market-fit signals. |

### market-intelligence

| Skill | Type | Use when |
|---|---|---|
| [ansoff-matrix](references/ansoff-matrix.md) +tpl | workflow | Map evidence-backed growth options across the Ansoff Matrix with risk-rated sequencing. Use when the question is where the next tranche of growth comes from, and at what risk. |
| [autonomous-investigation](references/autonomous-investigation.md) +tpl | workflow | The protocol behind every investigation skill. Use when AI research must proceed without you: search-plan gate, Fact/Inference/Assumption labels, confidence stacking, diffable outputs. |
| [battle-card-builder](references/battle-card-builder.md) +tpl | workflow | Research and draft a competitive battle card from public evidence — every claim labeled and sourced. Use when a rep needs a field-action card, not a research report. |
| [company-intel](references/company-intel.md) +tpl | workflow | Research a company, industry, or competitor set using web search and seven analytical lenses. Use when you need structured intel that feeds downstream PM skills. |
| [company-research](references/company-research.md) +tpl | component | Create a company research brief with executive quotes, product strategy, and org context. Use when preparing for interviews, competitive analysis, partnerships, or market-entry work. |
| [competitive-analysis-process](references/competitive-analysis-process.md) +tpl | workflow | Orchestrate a complete competitive analysis across six steps, from landscape to strategic direction. Use when you need the full picture, not a single scan or card. |
| [competitive-intel-watch](references/competitive-intel-watch.md) +tpl | workflow | Scheduled delta monitoring against a prior competitive snapshot. Use when tracking competitors on a cadence: material shifts only, cited evidence, battle-card update flags, runs unattended. |
| [competitive-research-snapshot](references/competitive-research-snapshot.md) +tpl | workflow | Research a competitive landscape with cited snapshots, a comparison matrix, and so-what implications. Use when a product decision needs competitive grounding, not a market report. |
| [intel-discipline-advisor](references/intel-discipline-advisor.md) +tpl | interactive | Triage a competitive or market question into the right intelligence disciplines, cadence, and executing skill. Use when you know something needs researching but not which channel to run. |
| [intelligence-collection-disciplines](references/intelligence-collection-disciplines.md) +tpl | component | Run competitive research like an intelligence agency: eight collection disciplines (OSINT to MASINT), signal-to-inference chains, and fusion. Use when one-source research isn't enough. |
| [market-landscape-scan](references/market-landscape-scan.md) +tpl | workflow | Map a market's segments, players, substitutes, and whitespace with cited evidence. Use when entering or re-evaluating a market before sizing, positioning, or picking competitors to study. |
| [pestel-analysis](references/pestel-analysis.md) +tpl | component | Analyze political, economic, social, technological, environmental, and legal forces. Use when external market shifts could materially affect a product, roadmap, or strategy. |
| [pestel-delta-monitor](references/pestel-delta-monitor.md) +tpl | workflow | Quarterly re-scan of a prior PESTEL analysis. Use when checking which macro factors moved, which assumptions broke, and what's new — turning PESTEL from a workshop artifact into a radar. |
| [porters-five-forces](references/porters-five-forces.md) +tpl | workflow | Read an industry's structure through Porter's Five Forces with documented signals per rating, ending at the profit pool. Use when weighing market entry or when margins erode and nobody can say why. |
| [pricing-packaging-tracker](references/pricing-packaging-tracker.md) +tpl | workflow | Track competitor pricing and packaging as a diffable time series. Use when monitoring tiers, gates, limits, and price moves on a monthly or quarterly cadence. |
| [swot-analysis](references/swot-analysis.md) +tpl | workflow | Build an evidence-cited SWOT of one company — yours or a competitor's — from public sources, ending with the S-O/W-T crossings. Use for strategy reviews, board prep, or competitor depth. |
| [tam-sam-som-calculator](references/tam-sam-som-calculator.md) +tpl | interactive | Calculate TAM, SAM, and SOM with explicit assumptions, methods, and caveats. Use when sizing a market for a product idea, business case, or executive review. |
| [voice-of-customer-miner](references/voice-of-customer-miner.md) +tpl | workflow | Mine public reviews, app stores, and forums for unmet needs, competitor weaknesses, and switching triggers — with quoted evidence. Use when you want customer voice without waiting on interviews. |

### meta-authoring

| Skill | Type | Use when |
|---|---|---|
| [pm-skill-creator](references/pm-skill-creator.md) | interactive | Design a new PM skill through guided conversation. Use when you have raw content or an idea and want to shape it into a compliant skill. |
| [skill-authoring-workflow](references/skill-authoring-workflow.md) +tpl | workflow | Turn raw PM content into a compliant, publish-ready skill. Use when creating or updating a repo skill without breaking standards. |

### pm-artifacts

| Skill | Type | Use when |
|---|---|---|
| [epic-breakdown-advisor](references/epic-breakdown-advisor.md) | interactive | Break down epics into user stories with Humanizing Work split patterns. Use when a backlog item is too large to estimate, sequence, or deliver safely. |
| [epic-hypothesis](references/epic-hypothesis.md) +tpl | component | Frame an epic as a testable hypothesis with target user, expected outcome, and validation method. Use when defining a major initiative before roadmap, discovery, or delivery planning. |
| [prd-development](references/prd-development.md) +tpl | workflow | Build a structured PRD that connects problem, users, solution, and success criteria. Use when turning discovery notes into an engineering-ready document for a major initiative. |
| [press-release](references/press-release.md) +tpl | component | Write an Amazon-style press release that defines customer value before building. Use when aligning stakeholders on a new product, feature, or strategic bet. |
| [storyboard](references/storyboard.md) +tpl | component | Create a six-frame storyboard that shows a user's journey from problem to solution. Use when you need a fast narrative for alignment, concept reviews, or demos. |
| [user-story](references/user-story.md) +tpl | component | Create user stories with Mike Cohn format and Gherkin acceptance criteria. Use when turning user needs into development-ready work with clear outcomes and testable conditions. |
| [user-story-mapping](references/user-story-mapping.md) +tpl | component | Create a user story map that lays out activities, steps, tasks, and release slices. Use when planning a workflow, backlog, or MVP around the user journey. |
| [user-story-splitting](references/user-story-splitting.md) +tpl | component | Break a large story or epic into smaller deliverable stories using proven split patterns. Use when backlog items are too big for estimation, sequencing, or independent release. |

### product-lifecycle

| Skill | Type | Use when |
|---|---|---|
| [lifecycle-play-advisor](references/lifecycle-play-advisor.md) | interactive | Diagnose where a product sits in its lifecycle and which play fits — extend, replace, or retire. Use when a product is fading and you need the call, not just the worry. |
| [product-lifecycle-plays](references/product-lifecycle-plays.md) +tpl | component | Map a product's lifecycle stage and choose between extension, replacement, and retirement plays. Use when a product is maturing or declining and the next move isn't obvious. |

### stakeholder-comms

| Skill | Type | Use when |
|---|---|---|
| [incoming-request-advisor](references/incoming-request-advisor.md) +tpl | interactive | Decode an incoming message into a structured breakdown separating the literal ask from the job-to-be-done. Use when a loaded Slack ping, email, mandate, or escalation needs a reply. |
| [stakeholder-engagement-advisor](references/stakeholder-engagement-advisor.md) | interactive | Plan engagement for a specific stakeholder. Use when preparing an outreach, navigating resistance, or aligning a critical relationship before a key milestone. |
| [stakeholder-identification](references/stakeholder-identification.md) +tpl | component | Map every stakeholder before engaging anyone. Use when launching an initiative, scoping discovery, or building an engagement plan from scratch. |
| [stakeholder-mapping](references/stakeholder-mapping.md) +tpl | component | Prioritize stakeholders using two complementary grids. Use when setting engagement strategy and surfacing whose voice needs elevating after stakeholder identification. |

### strategy-positioning

| Skill | Type | Use when |
|---|---|---|
| [organic-growth-advisor](references/organic-growth-advisor.md) +tpl | interactive | Identify which organic growth path to pursue — new segments, geographies, channels, or products. Use when diagnosing where a growth constraint lives and which McKinsey growth level to act on next. |
| [positioning-statement](references/positioning-statement.md) +tpl | component | Create a Geoffrey Moore-style positioning statement. Use when clarifying who you serve, what problem you solve, your category, and why you're different from alternatives. |
| [prioritization-advisor](references/prioritization-advisor.md) | interactive | Choose a prioritization framework based on stage, team context, and stakeholder needs. Use when deciding between RICE, ICE, value/effort, or another scoring approach. |
| [product-strategy-session](references/product-strategy-session.md) +tpl | workflow | Run an end-to-end product strategy session across positioning, discovery, and roadmap planning. Use when a team needs validated direction before committing to execution. |
| [roadmap-planning](references/roadmap-planning.md) +tpl | workflow | Plan a strategic roadmap across prioritization, epic definition, stakeholder alignment, and sequencing. Use when turning strategy into a release plan that teams can execute. |

### validation-experiments

| Skill | Type | Use when |
|---|---|---|
| [derisk-measurement-advisor](references/derisk-measurement-advisor.md) | interactive | Identify what to measure, test, or track to de-risk a product or AI idea. Use when stress-testing an idea across internal (DUFV) and external (PESTEL) dimensions. |
| [lean-ux-canvas](references/lean-ux-canvas.md) +tpl | interactive | Guide teams through Lean UX Canvas v2. Use when framing a business problem, surfacing assumptions, and defining what to learn next. |
| [pol-probe](references/pol-probe.md) +tpl | component | Define a Proof of Life probe to test a risky hypothesis cheaply. Use when you need harsh truth before building real product. |
| [pol-probe-advisor](references/pol-probe-advisor.md) | interactive | Select the right Proof of Life (PoL) probe based on hypothesis, risk, and resources. Use this to match the validation method to the real learning goal, not tooling comfort. |
| [recommendation-canvas](references/recommendation-canvas.md) +tpl | component | Evaluate an AI product idea across outcomes, hypotheses, risks, and positioning. Use when deciding whether an AI solution deserves investment or recommendation. |

### workshops-facilitation

| Skill | Type | Use when |
|---|---|---|
| [customer-journey-map](references/customer-journey-map.md) +tpl | component | Create a customer journey map across stages, touchpoints, actions, emotions, and metrics. Use when diagnosing a broken experience or aligning a team on the full customer flow. |
| [customer-journey-mapping-workshop](references/customer-journey-mapping-workshop.md) | interactive | Run a customer journey mapping workshop with adaptive questions and outputs. Use when you need to map stages, actions, emotions, pain points, and opportunities for a persona and scenario. |
| [positioning-workshop](references/positioning-workshop.md) | interactive | Run a positioning workshop that surfaces target customer, unmet need, category, benefits, and differentiation. Use when your product messaging feels fuzzy, generic, or misaligned. |
| [user-story-mapping-workshop](references/user-story-mapping-workshop.md) +tpl | interactive | Run a user story mapping workshop with adaptive questions and a structured map output. Use when you need backbone activities, tasks, and release slices for a workflow. |
| [workshop-facilitation](references/workshop-facilitation.md) | interactive | Facilitate workshop sessions in a one-step, multi-turn flow. Use when an interactive skill needs consistent pacing, options, and progress tracking. |

## Notes

- Compact edition: worked examples and helper scripts from the full library are omitted to fit the 200-file upload limit. Fill-in templates are kept.
- License: CC BY-NC-SA 4.0. Source: https://github.com/deanpeters/Product-Manager-Skills
