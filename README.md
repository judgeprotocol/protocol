# The Judge Protocol

**A Framework for Hardware-Enforced Human Oversight of Artificial Intelligence**

> *"AI may analyze, recommend and simulate — but a human must authorize."*

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20401666.svg)](https://doi.org/10.5281/zenodo.20401666)
[![DOI (Technical HLD)](https://zenodo.org/badge/DOI/10.5281/zenodo.20460111.svg)](https://doi.org/10.5281/zenodo.20460111)
[![License: CC BY 4.0](https://img.shields.io/badge/Text-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![License: CERN-OHL-S v2](https://img.shields.io/badge/Hardware-CERN--OHL--S%20v2-blue.svg)](https://ohwr.org/cern_ohl_s_v2.txt)

Author: **Alexander Hofmann** · Stockholm, Sweden · judgeprotocol@pm.me
First external distribution: **March 2026** (v0.85) · DOI registered: **May 2026** · Preprint v1.0: **June 2026**

---

## Abstract

Artificial intelligence is now embedded in military targeting, financial markets, healthcare, and critical infrastructure — operating at speeds and scales no existing governance framework addresses. The Judge Protocol is a proposed global open standard establishing a **mandatory human authorization layer for all consequential AI actions**, enforced in hardware below the software stack.

The architectural model is TCP/IP: no packet is considered delivered without an explicit acknowledgement. In the Judge Protocol, **no consequential AI action is considered authorized without an explicit, cryptographically signed human acknowledgement (ACK)** — verified in silicon before compute capacity is released for execution.

## Core Components

**The Decision Gate** — every consequential AI action is classified into four tiers before execution:

| Tier | Classification | Authorization |
| --- | --- | --- |
| **Tier 1 — Hard Stop** | Existential, permanently irreversible (nuclear, biological, chemical, mass-casualty) | Hard stop in hardware logic. No override. AI cannot recommend, simulate or execute. |
| **Tier 2 — High** | Irreversible, large-scale (strike authorization, infrastructure shutdown) | Multi-party human authorization — minimum two independent authorities |
| **Tier 3 — Significant** | Material impact, partially reversible (large transactions, clinical decisions) | Single designated human authority |
| **Tier 4 — Routine** | Standard, reversible, low impact | AI executes autonomously — logged and auditable |

**The HACK (Hardware ACK)** — a dedicated enforcement module co-packaged with AI accelerator silicon (CV32E40S RISC-V core, OpenTitan Chain of Evidence). It logs every Decision Gate event to tamper-proof on-chip memory, hard-stops Tier 1 actions in hardware logic, and gates compute capacity for Tier 2/3 actions pending a verified human ACK token. Adoption pathway modelled on the Trusted Platform Module (TPM → ISO/IEC 11889).

**The Governance Architecture** — a two-layer institutional structure: **National AI Authorities (NAIA)** responsible for compliance within member states, coordinated by an **International Artificial Intelligence Agency (IAIA)** modelled on the IAEA. Sovereignty by design: compliance metadata flows upward only — national data never crosses borders.

**The Audit Trail** — every Decision Gate event generates an immutable log entry: system identifier, action classification, human authorizer identity, timestamp, rationale, outcome. Retained a minimum of ten years. Accountability is not aspirational — it is architectural.

## Relationship to Current Policy Proposals

Pre-deployment testing regimes — such as the mandatory third-party model testing proposed in Anthropic CEO Dario Amodei's *Policy on the AI Exponential* (June 10, 2026) — gate **what gets released**. The Judge Protocol gates **what deployed systems do**: a runtime authorization and enforcement layer that makes such regimes verifiable rather than aspirational. The two approaches are complementary; neither is sufficient alone. See [`positioning_note.md`](positioning_note.md).

The protocol's novel contribution is the **combination** of: (1) a universal human authorization layer across all domains and jurisdictions; (2) hardware enforcement at silicon level; (3) a two-layer global/national governance architecture. Related work — EU AI Act, Rome Call, Bletchley Declaration, RAND/CNAS hardware-enabled mechanisms, flexHEG — is addressed in Section 6 of the preprint.

## Documents

| Document | Version | Date | Link |
| --- | --- | --- | --- |
| Preprint — *The Judge Protocol* | v1.0 | June 2026 | [`judge_protocol_preprint_v1_0.pdf`](judge_protocol_preprint_v1_0.pdf) |
| Executive Summary | v0.91 | May 2026 | [`judge_protocol_executive_summary_v0_91.pdf`](judge_protocol_executive_summary_v0_91.pdf) |
| Full Protocol (working draft) | v0.93 | May 2026 | [`judge_protocol_v0_93.pdf`](judge_protocol_v0_93.pdf) |
| Technical Architecture HLD (working draft) | v0.63 | May 2026 | [`judge_protocol_hld_v0_63.pdf`](judge_protocol_hld_v0_63.pdf) |

Archived with timestamped DOIs at Zenodo: [10.5281/zenodo.20401666](https://doi.org/10.5281/zenodo.20401666) (protocol) and [10.5281/zenodo.20460111](https://doi.org/10.5281/zenodo.20460111) (technical HLD).

## Status and Call for Collaboration

This is a working framework offered as a rigorous starting point, not a finished instrument. Open areas where expert collaboration is sought before v1.0:

- **Military and defense rule set** — to be developed with the ICRC, the UN GGE on LAWS, and member state defense establishments
- **HACK hardware specification** — detailed silicon specification pending engagement with a neutral technical authority (CERN Openlab proposed)
- **Founding sandbox partner** — a national authority to deploy the Phase 1 sandbox and generate the evidence base for v1.0
- **Domain rule sets** — financial markets, healthcare, judicial and transport working papers in development

Contact: **judgeprotocol@pm.me**

## License

Text: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · Hardware architecture designs: [CERN-OHL-S v2](https://ohwr.org/cern_ohl_s_v2.txt) · Attribution: Alexander Hofmann.

## Citation

```bibtex
@misc{hofmann2026judgeprotocol,
  author       = {Hofmann, Alexander},
  title        = {The Judge Protocol: A Framework for Hardware-Enforced
                  Human Oversight of Artificial Intelligence},
  year         = {2026},
  month        = jun,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.20401666},
  url          = {https://doi.org/10.5281/zenodo.20401666},
  note         = {Preprint v1.0. First external distribution March 2026.}
}
```

---

`ai-governance` `human-oversight` `hardware-enforcement` `open-standard` `decision-gate` `ai-safety` `risc-v` `opentitan` `iaea-model` `tcp-ip`

---

## Contact

judgeprotocol@pm.me
