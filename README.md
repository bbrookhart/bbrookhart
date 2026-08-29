<div align="center">

<img src="./assets/darkcurrent-hero.svg" alt="AI security research across autonomous, cyber-physical, and high-consequence systems" width="100%" />

### AI Security Researcher · Secure Autonomous Systems · Cyber-Physical Security

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Brian_Brookhart-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/brian-brookhart/)
[![Focus](https://img.shields.io/badge/Research-Agentic_AI_Security-0891B2?style=flat-square)](#research-focus)

</div>

> **As AI systems move from generating information to taking action, security becomes a problem of authority, capability, provenance, and consequence.**

I build and evaluate security architectures for **autonomous AI and cyber-physical systems operating in high-consequence environments**. My work focuses on a practical question:

> **How can capable AI systems remain useful while preventing model failure, adversarial influence, or compromised agents from becoming unauthorized digital or physical action?**

The projects below are treated as research artifacts rather than concept demos. Each flagship is organized around an explicit threat model, a testable security claim, enforceable controls, adversarial evaluation, measurable evidence, and reproducibility.

---

## Selected Research

| Project | Research problem | Evidence |
|---|---|---|
| **[VIGIL](https://github.com/bbrookhart/VIGIL)** | Can consequential AI-agent actions be intercepted and constrained before execution? | Rust/Python enforcement core, deterministic policy, signed capabilities, provenance tracking, fuzzing, extensive negative-security tests |
| **[BLACKSTART](https://github.com/bbrookhart/blackstart-cyber-range)** | Can engineered backstops prevent digital compromise from becoming unsafe physical consequence? | Reproducible cyber-physical experiment, safety invariants, causal evidence, independent metric verification |
| **[CRUCIBLE](https://github.com/bbrookhart/crucible-ai)** | How should cyber capability and defensive uplift of advanced AI systems be measured without confusing demos with evidence? | Bounded evaluation harness, task-scoped tools, scoring isolation, contamination controls, tamper-evident evidence packages |
| **[CERBERUS NULL](https://github.com/bbrookhart/cerberus-null)** | Can autonomous cyber-defense agents reason flexibly without acquiring unrestricted authority? | Deterministic control plane, capability model, formal constraints, policy enforcement, adversarial TEVV |


---

## Research Method

<div align="center">

**Threat Model** → **Security Property** → **Control** → **Adversarial Evaluation** → **Measurement** → **Evidence** → **Reproduction**

</div>

The standard is straightforward: a security claim should survive inspection of the architecture, execution path, experiment, evidence, limitations, and reproduction procedure.

### What I optimize for

- **Authority outside the model.** Models may propose and reason; deterministic controls decide whether consequential actions are authorized.
- **Least privilege for agents.** Capabilities should be task-scoped, narrow, revocable, and independently enforced.
- **Pre-execution control.** Dangerous actions should be blocked before they reach the operating system, network, tool, or physical process.
- **Evidence over demos.** Results should be reproducible, machine-verifiable where possible, and explicit about limitations.
- **High-consequence failure analysis.** Security is evaluated in terms of what an action can actually change, not only whether a prompt or model output looks malicious.

---

## Additional Engineering & Research

<details>
<summary><b>Agentic AI security and autonomous defense</b></summary>
<br>

| Project | Focus |
|---|---|
| **[Security-First Multi-Agentic SOC](https://github.com/bbrookhart/secure-agentic-soc)** | Deterministic routing, least privilege, human approval, proposal-only containment, and auditable local-LLM SOC workflows |
| **[NIGHTGLASS](https://github.com/bbrookhart/nightglass)** | Persistent malicious influence across agent sessions and delayed unauthorized effects |
| **[FALSEPROXY](https://github.com/bbrookhart/falseproxy)** | Identity, provenance, delegation, authorization, and revocation for interoperating agent ecosystems |
| **[GHOSTLEDGER](https://github.com/bbrookhart/ghostledger)** | Agent sabotage where visible task success masks degradation of mission integrity |

</details>

<details>
<summary><b>Critical infrastructure, trust, and resilience</b></summary>
<br>

| Project | Focus |
|---|---|
| **[IRONVEIL](https://github.com/bbrookhart/ironveil)** | Software/firmware provenance and source-to-installed-state assurance |
| **[HARVEST//ZERO](https://github.com/bbrookhart/harvest-zero)** | Post-quantum cryptographic inventory, migration prioritization, and crypto agility |
| **[DEADFALL](https://github.com/bbrookhart/deadfall)** | Detection of persistent access established for possible future disruption |

</details>

<details>
<summary><b>Applied AI security and governance</b></summary>
<br>

| Project | Focus |
|---|---|
| **[Northstar Medical AI Deployment](https://github.com/bbrookhart/northstar-medical-ai-deployment)** | Secure deployment of constrained internal agentic AI in a high-stakes healthcare environment |
| **[Meridian Atlas Security](https://github.com/bbrookhart/meridian-atlas-security)** | Adversarial testing, silent-failure detection, control validation, and audit evidence for an intentionally vulnerable LLM application |

</details>

---

## Public Release Model

Public repositories are designed to provide enough implementation, architecture, tests, experiments, and evidence for technical review. Where work becomes security-sensitive, operationally risky, unpublished, or potentially proprietary, those components should remain outside the public release.

I do **not** use README-only placeholders as substitutes for implementation. Public flagship projects are expected to contain inspectable engineering evidence: source code, tests, threat models, reproducible experiments, evaluation results, or other artifacts that support the stated claim.

---

## Research Focus

| Secure autonomy | High-consequence systems | Trust and assurance |
|---|---|---|
| Agentic AI security · task-scoped authorization · runtime policy · human approval · adversarial TEVV | Cyber-physical systems · critical infrastructure · OT/ICS · autonomous systems | Formal constraints · provenance · software supply chain · post-quantum security · reproducibility |

**Security:** threat modeling · adversarial evaluation · detection engineering · runtime enforcement · vulnerability research  
**AI/ML:** Python · PyTorch · local LLMs · agent architectures · evaluation harnesses · RAG security  
**Systems:** Rust · Docker · Linux · cloud security · telemetry · CI/CD · infrastructure-as-code  
**Assurance:** NIST AI RMF · NIST CSF · ISO/IEC 42001 · ISO 27001 · OWASP GenAI guidance · MITRE ATT&CK / ATLAS

---

## Education & Credentials

| | |
|---|---|
| **Incoming PhD, Information Technology** | Cybersecurity research focus |
| **M.S., Cybersecurity & Information Assurance** | Completed |
| **BBA, Business Analytics** | Completed |
| **CompTIA PenTest+ · CySA+ · ISC2 CC** | Certified |

---

## Security Philosophy

> **The attack surface is no longer only the infrastructure. It is the decision, the authority behind it, and the action that follows.**

AI security cannot stop at policy or model behavior. Controls must become technical boundaries that are observable, testable, enforceable, and auditable at runtime.

<div align="center">

### Securing autonomous systems where failure has real-world consequences.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/brian-brookhart/)

</div>
