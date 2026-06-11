# Testing Gates the Release. Authorization Gates the Action.

**The Judge Protocol and "Policy on the AI Exponential" — a positioning note**

*Alexander Hofmann · Stockholm, June 2026 · judgeprotocol@pm.me · DOI: 10.5281/zenodo.20401666*

On June 10, 2026, Anthropic CEO Dario Amodei published *Policy on the AI Exponential*, proposing that frontier AI models above a compute threshold undergo mandatory third-party testing — for cybersecurity, biological weapons, loss of control, and automated R&D risks — with government authority to block deployment of models that fail. The essay marks a significant shift: the leading frontier AI lab now argues that transparency is no longer enough and that binding regulation with enforcement teeth is required.

I agree. And I believe the proposal stops one layer short.

Pre-deployment testing gates **what gets released**. It certifies, at a point in time, that a model meets a safety standard. It says nothing about what that model — or the agentic systems built on it — does afterward, in production, at machine speed, across millions of consequential decisions. A blocked release is enforceable at the moment of release. An authorized release then operates for years under governance that exists only on paper.

The Judge Protocol — published in working versions since March 2026 and archived with timestamped DOIs in May 2026 (10.5281/zenodo.20401666; technical architecture 10.5281/zenodo.20460111) — specifies the layer Amodei's regime would need to be verifiable rather than aspirational: **runtime human authorization, enforced in hardware**.

Its core principle is borrowed from the architecture of the internet itself. In TCP/IP, no packet is considered delivered without an explicit acknowledgement. In the Judge Protocol, no consequential AI action is considered authorized without an explicit, cryptographically signed human acknowledgement — verified in silicon, below the software stack, where governance cannot be patched away. A four-tier Decision Gate classifies actions from hard-stopped existential categories down to logged routine automation. A two-layer institutional architecture — national AI authorities coordinated by an international agency modelled on the IAEA — provides the verification regime, with sovereignty by design: compliance metadata flows upward, national data never crosses borders.

The two frameworks are complementary, and both are necessary:

| | *Policy on the AI Exponential* (June 2026) | The Judge Protocol (March–June 2026) |
| --- | --- | --- |
| **Object governed** | Frontier model release | Consequential AI actions at runtime |
| **Mechanism** | Mandatory third-party testing | Tiered human authorization (Decision Gate) |
| **Enforcement** | Legal authority to block deployment | Hardware ACK in accelerator silicon |
| **Institution** | FAA-style agency or authorized evaluators | IAIA/NAIA (IAEA model), open standard body |
| **Scope** | US-led, coalition of democracies | Universal open standard, owned by nobody |

The same logic extends to the essay's geopolitical pillar. A coalition controlling chips and semiconductor manufacturing equipment is, today, enforced by customs paperwork and end-use declarations. Hardware-level attestation — the enforcement substrate the Judge Protocol specifies — is what turns a chip coalition from a promise into a verifiable regime, just as IAEA safeguards inspections turned the Non-Proliferation Treaty from words into a system.

The Judge Protocol is an open standard: CC BY 4.0 for the framework, CERN-OHL-S v2 for the hardware architecture. It is offered not as a competing proposal but as the missing enforcement layer of the regime the frontier labs themselves are now asking for.

The policy conversation has arrived at the gate. The question is what stands behind it.

**Full documents:** github.com/judgeprotocol/protocol · Zenodo DOI 10.5281/zenodo.20401666
