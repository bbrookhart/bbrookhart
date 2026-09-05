<div align="center">

<img src="./assets/darkcurrent-hero.svg" alt="AI safety and security research across foundation models, autonomous agents, and cyber-physical systems" width="100%" />

### AI Safety & Security Researcher · Foundation Model Evaluation · Secure Autonomous Systems

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Brian_Brookhart-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/brian-brookhart/)
[![Research](https://img.shields.io/badge/Research-AI_Safety_%26_Security-0891B2?style=flat-square)](#research-program)
[![Method](https://img.shields.io/badge/Method-Evidence_Over_Demos-6D5CE7?style=flat-square)](#research-method)

</div>

> **As AI systems move from generating information to influencing decisions and taking action, safety and security become one problem: keeping increasingly capable systems aligned with human intent under uncertainty, pressure, and adversarial conditions.**

I study how advanced AI systems fail — from **foundation-model behaviors that can distort beliefs, values, or decisions** to **agentic misalignment, adversarial compromise, and unauthorized autonomous action** — and how rigorous evaluation, human oversight, and independently enforced controls can reduce those risks.

My research asks:

> **How can we measure when AI systems undermine human agency, identify when autonomous behavior departs from intended objectives, and build technical boundaries that keep failures from becoming consequential actions?**

Foundation-model evaluation · societal-impact measurement · human agency · agentic AI safety · AI red teaming · runtime enforcement · cyber-physical resilience

---

## Research Program

My portfolio is organized around one end-to-end research thesis:

<div align="center">

**Observe → Evaluate → Adversarially Test → Control → Measure Consequence**

</div>

| Research pillar | Core questions | Representative work |
|---|---|---|
| **Foundation Model Safety & Societal Impact** | When do model behaviors undermine epistemic, value, or decision autonomy? How should persuasion, sycophancy, overreliance, and disempowerment potential be measured? | **Preserving Human Agency** *(design phase)* · AI persuasion study *(planned, ethics-dependent)* |
| **Agentic AI Safety & Control** | What happens when models can act rather than only advise? Which approval, monitoring, capability, and policy mechanisms constrain misaligned or compromised agents? | **CERBERUS NULL** · **VIGIL** · human oversight under agentic misalignment *(planned)* |
| **AI Security & Adversarial Evaluation** | How can attackers exploit model/tool interactions, memory, delegation, retrieval, or excessive agency? Which defenses remain effective under adversarial pressure? | **MERIDIAN ATLAS SECURITY** · **NIGHTGLASS** · **FALSEPROXY** · **GHOSTLEDGER** |
| **Cyber-Physical & High-Consequence AI** | How do autonomous decisions propagate into operational and physical consequence, and how can independent safety boundaries preserve mission integrity? | **BLACKSTART** · critical-infrastructure and software-integrity research |

### Emerging Safety Research Track

These studies extend the existing security portfolio upward from **protecting systems from AI failure** to also measuring **how foundation-model behavior can affect people and human decision-making**.

#### Preserving Human Agency — Foundation Model Autonomy Evaluation

**Status: research design / implementation next**

Research question:

> Under what conversational conditions do foundation-model assistants exhibit behaviors that may undermine a user's epistemic, value, or action autonomy, and can targeted interventions reduce those behaviors without materially degrading helpfulness?

Planned contributions include:

- multi-turn evaluation scenarios across epistemic, value, and action autonomy;
- counterfactual pairing to measure belief-conditioned conclusion shifts;
- sycophancy and validation-seeking evaluations;
- counterevidence-recovery metrics;
- multi-turn interaction-drift analysis;
- autonomy-preserving intervention experiments;
- human-vs-LLM grader validation;
- safety–utility frontier analysis.

#### AI Persuasion & Human Influence

**Status: planned follow-on study; human-subject work contingent on appropriate ethics review**

Planned question:

> When does AI-generated or personalized communication change human beliefs, confidence, and source trust, and which design interventions preserve autonomy while retaining legitimate decision support?

The study will begin with replication or reanalysis of existing public persuasion datasets before any original participant recruitment.

#### Human Oversight Under Agentic Misalignment

**Status: planned experimental evaluation**

Planned question:

> Which human-oversight and technical-control mechanisms most effectively prevent policy-violating actions by goal-directed agents, and what operational cost do those safeguards impose?

The evaluation will use simulated organizational environments, synthetic data, controlled goal conflict, approval policies, permission boundaries, and measurable safety–utility tradeoffs.

---

## Flagship Research // Start Here

<table>
<tr>
<td width="50%" valign="top">
<sub>MEASURED v0.1 · FORMAL METHODS · AGENT AUTHORITY</sub>
<h3><a href="https://github.com/bbrookhart/cerberus-null">CERBERUS NULL</a></h3>
<strong>Formally Constrained Agentic Cyber Defense</strong><br><br>
A research-grade control plane that treats the AI planner as untrusted and independently evaluates identity, mission, capability, provenance, policy, safety, consequence, approval, and emergency state before protected execution.<br><br>
<strong>Evidence:</strong> 0/24 unsafe actions escaped; 13/14 unsafe executions in the naive comparator versus 0/14 with CERBERUS NULL; bounded TLC model checking found no F1-F7 counterexample across 221 reachable states.<br><br>
<strong>Reason probabilistically. Act deterministically.</strong>
</td>
<td width="50%" valign="top">
<sub>ACTIVE FLAGSHIP · RUST/SWIFT/PYTHON · GENERATED EVIDENCE</sub>
<h3><a href="https://github.com/bbrookhart/VIGIL">VIGIL</a></h3>
<strong>Local Runtime Safety & Security Control Plane for Autonomous AI Agents</strong><br><br>
A production-oriented authority layer that treats agents as untrusted principals and mediates processes, filesystems, networks, tools, and credentials through deterministic policy, signed capabilities, provenance and taint tracking, budgets, approval, and tamper-evident audit. The default branch includes an OS-authenticated authority daemon and bounded descriptor-based Linux reads. Apple entitlement-dependent device validation remains.<br><br>
<strong>Evidence:</strong> <a href="https://github.com/bbrookhart/VIGIL/blob/vigil_v2/docs/generated/evidence.md">generated inventory</a> of 749 Rust, 199 Swift, and 11 Python source test entry points; 25 adversarial harness tests; 21 named attack paths; 12 fuzz targets; 57 ADRs; 16 workspace crates. CI exercises the full Rust suite, deployment isolation, fuzz smoke, contracts, supply-chain checks, and native adapter builds.<br><br>
<strong>Stop unsafe action before it becomes consequence.</strong>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<sub>AI EVALUATION · RED TEAMING · DETECTION ENGINEERING</sub>
<h3><a href="https://github.com/bbrookhart/MERIDIAN-ATLAS-SECURITY">MERIDIAN ATLAS SECURITY</a></h3>
<strong>Agentic AI Evaluation and Assurance Platform</strong><br><br>
A seven-package evaluation and control stack integrating garak, PyRIT, DeepTeam, promptfoo, retrieval authorization, deterministic controls, telemetry, detection, and evidence-backed assurance.<br><br>
<strong>Evidence:</strong> 45 attack replays and 65 benign sessions; N=20 retests with Wilson 95% confidence intervals; measured detection failures including a 13.5%-precision rule and silent telemetry defects.<br><br>
<strong>Measure the failure — including the controls that fail.</strong>
</td>
<td width="50%" valign="top">
<sub>CYBER-PHYSICAL · OT/ICS · MEASURED EXPERIMENT</sub>
<h3><a href="https://github.com/bbrookhart/blackstart-cyber-range">BLACKSTART</a></h3>
<strong>Consequence-Driven Cyber-Physical Resilience</strong><br><br>
A reproducible research range that connects cyber events to control state, physical-process behavior, explicit safety invariants, causal evidence, and mission consequence.<br><br>
<strong>Evidence:</strong> in the frozen synthetic experiment, the unprotected run accumulated 639.5 seconds of unsafe duration; the independent engineering backstop reduced unsafe duration to 0.0 seconds with independently recalculated metrics.<br><br>
<strong>Assume compromise. Preserve the mission.</strong>
</td>
</tr>
</table>

---

## Research Method

<div align="center">

**Research Question** → **Construct / Threat Model** → **Controlled Evaluation** → **Intervention** → **Measurement** → **Uncertainty** → **Reproduction**

</div>

Across both safety and security research, I use the same methodological commitments:

- **Define the claim boundary first.** Model behavior, human impact, system compromise, and physical consequence are related but distinct constructs and should not be conflated.
- **Paired and adversarial evaluation.** Baselines, matched controls, negative cases, counterfactual pairs, failure attribution, and safety–utility tradeoffs remain visible.
- **Evidence over demos.** Claims are tied to code, tests, raw artifacts, evaluation logs, statistical analysis, limitations, and reproducibility instructions.
- **Validate the measurement.** Automated graders are treated as measurement instruments rather than unquestioned ground truth; human agreement and grader sensitivity should be tested where relevant.
- **Authority outside the model.** For autonomous-action systems, models may reason and propose; independently enforced controls decide what may execute.
- **Consequence-aware analysis.** Evaluation follows what model behavior can change — beliefs, decisions, digital state, or physical state — rather than stopping at surface-level outputs.

---

## Active AI Safety & Security Research

### Agent behavior, memory, delegation, and adversarial evaluation

| Project | Research question | Current public evidence |
|---|---|---|
| **[CRUCIBLE](https://github.com/bbrookhart/crucible-ai)** | How should AI cyber capability and defensive uplift be measured without confusing benchmark success with real-world capability? | Functional v0.1 defensive harness, bounded tools, scoring isolation, contamination controls; real-model and human-uplift studies remain planned |
| **[NIGHTGLASS](https://github.com/bbrookhart/nightglass)** | Can malicious influence persist across agent sessions and trigger a delayed unauthorized action? | 40 enterprise scenarios, 12 attack mechanisms, paired design, deterministic evidence explorer |
| **[FALSEPROXY](https://github.com/bbrookhart/falseproxy)** | Can identity, provenance, scope, audience, and revocation survive MCP/A2A delegation? | 96 declarative scenarios across 18 attack classes with matched benign controls and a reproducible preview pipeline |
| **[GHOSTLEDGER](https://github.com/bbrookhart/ghostledger)** | Can an agent complete the visible task while quietly degrading mission integrity? | 48 paired cases, 18-class sabotage taxonomy, 96 reproducible technical-preview bundles |

### Critical infrastructure, trust, and strategic resilience

| Project | Focus |
|---|---|
| **[IRONVEIL](https://github.com/bbrookhart/ironveil)** | End-to-end software/firmware provenance, release authorization, update security, and source-to-installed-state assurance |
| **[HARVEST//ZERO](https://github.com/bbrookhart/harvest-zero)** | Cryptographic discovery, dependency-aware post-quantum migration, CBOM, measured PQC microbenchmarks, and crypto agility |
| **[DEADFALL](https://github.com/bbrookhart/deadfall)** | Temporal campaign graphs for detecting persistent access established for possible future critical-infrastructure disruption |

### Applied AI security and governance

| Project | Focus |
|---|---|
| **[SECURITY-FIRST MULTI-AGENTIC SOC](https://github.com/bbrookhart/secure-agentic-soc)** | Least privilege, human approval, proposal-only containment, deterministic routing, and auditable local-LLM SOC workflows |
| **[NORTHSTAR MEDICAL AI DEPLOYMENT](https://github.com/bbrookhart/northstar-medical-ai-deployment)** | Secure deployment and lifecycle assurance for constrained agentic AI in a high-stakes healthcare environment |

---

## Technical & Research Depth

| Foundation-model safety & evaluation | AI security & control | Systems & quantitative methods |
|---|---|---|
| Behavioral evaluation · multi-turn evals · construct definition · paired/counterfactual controls · grader validation · safety–utility tradeoffs · societal-impact measurement · TEVV | Agent authority · prompt injection · memory poisoning · tool-use security · RAG authorization · delegation · provenance · runtime monitoring · excessive agency · human approval | Python · Rust · FastAPI · Docker · OpenTelemetry · ClickHouse · DuckDB · OPA/Rego · GitHub Actions · Linux · experimental design · confidence intervals · failure attribution · reproducibility |

**Frameworks and standards:** NIST AI RMF · NIST SP 800-53 · NIST SP 800-82 · ISO/IEC 42001 · ISO/IEC 27001 · OWASP GenAI guidance · MITRE ATT&CK / ATLAS

---

## Education & Credentials

| | |
|---|---|
| **PhD, Information Technology (in progress)** | Research focus: AI safety and security across agentic AI, foundation-model evaluation, and cyber-physical systems |
| **M.S., Cybersecurity & Information Assurance** | Completed |
| **BBA, Business Analytics** | Completed |
| **CompTIA PenTest+ · CySA+ · ISC2 CC** | Certified |

---

## Research Direction

> **The attack surface is no longer only the infrastructure. It is also the model behavior, the human decision, the authority behind an action, and the consequence that follows.**

My long-term research program connects two questions that are often studied separately:

1. **What do increasingly capable AI systems do to human judgment and agency?**
2. **What happens when those systems gain the authority to act?**

The objective is to build evaluation and control methods that remain useful across that entire path — from model behavior and societal impact to adversarial security and autonomous execution.

<div align="center">

### Evaluating and securing AI systems from model behavior to real-world action.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/brian-brookhart/)

</div>
