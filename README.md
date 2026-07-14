# The Judge Protocol

**A universal governance standard for human oversight of artificial intelligence.**

*"AI may analyze, recommend and simulate — but a human must authorize."*

---

## Why now

When one government can switch off global AI without control — June 2026, US export directive, Fable 5 — the case for international authorization infrastructure is no longer theoretical.

Every proposed governance regime addresses testing, safety classification, or model release. None mandates a runtime human authorization layer. The Judge Protocol specifies one.

*Testing gates the release. Authorization gates the action.*

---

## What it is

The Judge Protocol is a proposed global governance framework that requires explicit human authorization for every consequential AI action — enforced at the hardware level, governed internationally, owned by no single state.

The framework proposes:

- An **International Artificial Intelligence Agency (IAIA)** — a UN specialized agency modelled on the IAEA, with national implementation bodies (NAIA) in every member state
- **HACK — Hardware ACK** — a hardware enforcement mechanism embedded in AI accelerator silicon, implementing a chip-level gate that locks compute capacity until a verified human authorization token is received
- A **four-tier Decision Gate** — a structured human authorization mechanism covering all consequential AI actions across twelve domains
- **ACP — Action Classification Protocol** — a lightweight descriptor attached to every compute instruction, providing context for the HACK chip before execution
- **PACK — Physical ACK** — a two-part human authorization for the physical domain, covering robotics and autonomous systems

Built on the same architectural principle as TCP/IP: just as no packet is considered delivered without an explicit ACK, no consequential AI action is considered authorized without an explicit human acknowledgement.

---

## The Four-Tier Decision Gate

| Tier | Classification | Authorization |
|---|---|---|
| Tier 1 — Hard Stop | Existential, permanently irreversible | Hardware logic — no override, no execution |
| Tier 2 — High | Irreversible, large-scale | Multi-party human authorization |
| Tier 3 — Significant | Material impact, partially reversible | Single designated human authority |
| Tier 4 — Routine | Standard, reversible, low impact | AI executes autonomously — logged and auditable |

---

## Documents

| Document | Description | DOI |
|---|---|---|
| [Executive Summary v0.91](https://github.com/judgeprotocol/protocol/blob/main/judge_protocol_executive_summary_v0_91.pdf) | Start here — 9-page overview of the framework | [10.5281/zenodo.20401666](https://doi.org/10.5281/zenodo.20401666) |
| [The Judge Protocol v0.93](https://github.com/judgeprotocol/protocol/blob/main/judge_protocol_v0_93.pdf) | Full framework — governance structure, decision gate, hardware enforcement, domain rules, funding model | [10.5281/zenodo.20425549](https://doi.org/10.5281/zenodo.20425549) |
| [Technical Architecture HLD v0.65](https://github.com/judgeprotocol/protocol/blob/main/judge_protocol_hld_v0_65.pdf) | Hardware and software architecture — HACK chip, COE, ACP, three-layer stack, phased implementation |[Technical Architecture HLD v0.65](...) | [10.5281/zenodo.20722119](https://doi.org/10.5281/zenodo.20722119) |
| [Master Deck](https://github.com/judgeprotocol/protocol/blob/main/judge_protocol_master_deck.pdf) | Presentation deck — 15 slides covering the full framework for briefings and outreach | — |

---

## Governance model

The Judge Protocol is not owned by any company, government, or individual. It is an open standard.

- Text released under [Creative Commons Attribution 4.0 (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)
- Hardware architecture released under [CERN Open Hardware Licence v2 — Strongly Reciprocal (CERN-OHL-S v2)](https://ohwr.org/cern_ohl_s_v2.txt)
- Institutional home: **Judge Protocol Foundation**, Stockholm, Sweden — *ideell förening*, neutral jurisdiction, no VC, no single-state control

The CERN OHL-S licence is chosen deliberately: CERN played this role for the World Wide Web. The HACK chip standard is designed to follow the same path — open, internationally governed, owned by nobody.

---

## Interactive Demo

A working software simulation of the Decision Gate authorization mechanism:
[Try the Decision Gate Simulator](https://judgeprotocol.org/Demos/judge_protocol_decision_gate_simulator.html)

Select any of four example scenarios spanning all four tiers — from a routine
report to a lethal-engagement request — and see how each is classified
(reversibility, blast radius, novelty) and gated in real time: silent
autonomous execution, single-authority ACK, dual-authority ACK, or an
unconditional hard stop. Every action is recorded to a live audit log.

**Note:** this is a software simulation of the mechanism for demonstration
purposes. The published architecture (see HLD §6) enforces Tier 1 in
hardware, below the software stack — no UI can substitute for that guarantee.

---

## Status

Working draft — open for review, contribution, and collaboration. The framework is designed to evolve through an explicit Evolution Clause with two-year review cycles.

Published by the **Judge Protocol Foundation**, Stockholm, Sweden.

---

## Contact

judgeprotocol@pm.me · [judgeprotocol.org](https://judgeprotocol.org)
