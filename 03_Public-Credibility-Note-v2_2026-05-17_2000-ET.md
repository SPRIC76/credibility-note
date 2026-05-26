# Building Before the Announcement: A Technical Record

**Published by:** @samuel_riccardi  
**Updated:** 2026-05-17 | Version 2 — full corpus re-assessment  
**Dossier confidence score:** 95/100 (re-assessed on complete evidence corpus)

---

## Purpose

This note documents pre-release systems engineering work I completed before the March 18, 2026 public launch of MiniMax M2.7 — and how that work overlaps with capability themes MiniMax later publicized.

This is an evidence-led technical record, not a legal conclusion.

---

## Why This Took Two Months

MiniMax M2.7 launched March 18, 2026. This is being published in May 2026. That gap is worth addressing directly.

Three things happened in parallel after the announcement.

First: the SSDs on my dedicated AI machine — the separate computer running OpenClaw and autonomous operations — corrupted. The machine had to be reformatted. Evidence that existed across active storage had to be located, recovered, and verified from fragmented cloud drives and backup SSDs. This was not a clean handoff from "work in progress" to "publishable record." It was reconstruction under constraint.

Second: I'm managing a progressive illness that limits what I can sustain in a given day. The recovery and documentation work happened in the time and energy I had available — not on anyone else's timeline.

Third: building a credible record takes longer than building a reactive one. What survived the hardware failure did so because of deliberate redundancy built in advance — dual-mirror archives across separate physical drives, Proton Drive cloud backup, SHA-256 hash verification across both roots. That architecture is why 95/100 of the dossier is recoverable and verifiable today despite the hardware loss. But verifying and registering 22 exhibits, capturing NTFS metadata, running independent AI scoring, and writing this document still required the time it required.

A post in March — without evidence, written in the immediate aftermath of corrupted hardware — would have been dismissed immediately and rightly so. This one shouldn't be.

---

## Who I Am

Self-taught. No CS degree. No formal employment since my diagnosis left me homebound. I started building functional software prototypes through what became known as "vibe coding" in early 2025. By February 2026, I had moved into systems engineering — not by design, but by following the work where it led.

This record exists because I documented everything. And because documentation, it turns out, has value.

---

## What I Built

Between mid-February and mid-March 2026, I designed, implemented, and iterated on a 14-system autonomous agent platform called Mirage, running on top of OpenClaw with MiniMax as a primary model provider.

The systems, named and documented:

| System | Function |
|---|---|
| Model policy & routing | Provider-aware routing with complexity-tiered dispatch |
| MiniMax compensator | Uplift enforcement and conformity verification for MiniMax workers |
| Queue dispatch & spawning | Multi-agent queue with spawn/halt governance |
| Session loop / SUL / usage | 5-hour session pacing, usage-target control, pre-reset spawn logic |
| Skills governance & adherence | Skill-home policy, invocation protocol, SKILLS-MATRIX mandatory triggers |
| Memory kernel & flush | Layered memory with autonomous proactive flush |
| Discovery & SIFT pipeline | Autonomous discovery-scan → queue-orchestrator flow |
| Autonomous audit loop | Self-running JSON audit chain with structured defect reporting |
| Gateway gating & cron | Operational gating: tasks run only when gateway is active |
| Identity & continuity | Per-provider model identity enforcement and continuity routing |
| EPIF / scaffolding / compliance | Output validators, scaffolding compliance, behavior conformance |
| Mirage assimilation / drift | Discrepancy registry and canonical drift correction |
| Platform integration layer | Cross-system integration, autonomy-OpenClaw binding |
| Project delivery expansion | Full server specs: Writing, Parser, Mission Control |

This was not a collection of prompts or scripts. It was an engineered system with governance documents, audit trails, dual-mirror archives, and formal acceptance gates.

---

## Dated Artifact Trail

**Pre-cutoff rule:** Artifacts dated before 2026-03-18 are primary evidence. Post-cutoff artifacts are integrity corroboration only.

### Corpus Scale

| Metric | Value |
|---|---|
| Total design plans | 458 |
| Cursor-origin plans | 301 |
| Deduped logical plan slugs | 91 |
| Earliest NTFS-dated artifact | 2026-02-17 |
| Heavy development window | 2026-02-25 → 2026-03-13 |

### Chronological Spine

| Date | Milestone |
|---|---|
| 2026-02-17 | Earliest Cursor plan: model hierarchy and API key architecture |
| 2026-02-25–26 | Autonomy integration, failover/97% plans, session/archive audits |
| 2026-03-04 | MiniMax vs Sonnet benchmark cadence documented |
| 2026-03-05 | Security/leakage JSON audit (machine-generated, embedded UTC timestamp); skills-home governance anchor |
| 2026-03-06 | Provenance corpus generation — 458 plans logged, manifested, accepted |
| 2026-03-07 | End-to-end verification pipeline; queue reliability audit; dispatcher bug-fix |
| 2026-03-09–11 | Identity/continuity doctrine; complexity/skills integration; gateway policy |
| 2026-03-10 | High-volume runtime token-loop audit (767 log lines analyzed) |
| 2026-03-13 | Implementation-grade server specs; output validators; defect audit chain |

---

## Methodology

I scored this record using a 4-category weighted framework:

| Category | Weight | Description |
|---|---|---|
| Pre-cutoff chronology | 30 | Quality and density of dated pre-release artifacts |
| Provenance/chain-of-custody | 25 | Archive integrity, hash parity, dissemination lineage |
| Specificity of technical overlap | 25 | Mechanism-level vs thematic match quality |
| Cross-source consistency | 20 | Consistency across independent storage systems |

### Timestamp Authority Ladder

Evidence is ranked by independence from my control:

1. **Third-party server timestamps** — Anthropic export metadata, Proton Drive version history (Swiss servers)
2. **SHA-256 reruns** — independently reproducible, 18 mirror-matched pairs across two physical drives
3. **NTFS filesystem metadata** — NTFS `LastWriteTime` cross-validated against embedded JSON timestamps
4. **In-file date signals** — `Generated:`, `Created:`, `Date:` fields and filename dating

**Key forensic finding:** On EX-001 (a machine-generated JSON audit file), the NTFS local timestamp and the embedded UTC JSON timestamp match to the exact second. This cross-validation was not manufactured — it reflects a contemporaneous file write.

---

## Confidence Score

**Current score: 95/100**

| Category | Score |
|---|---|
| Pre-cutoff chronology | 29/30 |
| Provenance/chain-of-custody | 23/25 |
| Specificity of technical overlap | 24/25 |
| Cross-source consistency | 19/20 |
| **Total** | **95/100** |

### External Validation

Three independent AI systems scored an earlier version of the dossier using the same methodology, without being told what score to produce:

| System | Score |
|---|---|
| Grok (Expert model) | 93/100 |
| Claude (Sonnet 4.6) | 88/100 |
| Cursor (Premium) | 87/100 |
| Average | 89.3/100 |

The updated documentation scores at 95/100 by the same rubric — driven by the verbatim excerpt matrix, the 14-system corroboration map, and NTFS-to-JSON cross-validation.

---

## MiniMax M2.7 Claim Overlap (Summary)

| M2.7 Claimed Theme | Pre-Cutoff Overlap Evidence | Confidence |
|---|---|---|
| Complex environments + skill adherence | Strict-adherence **engineering** (matrix, protocol, session-audit, 77/24 corpus); protocols bear witness | **High** (mechanism-first); skill pass-rate % **open** |
| Agent harness/orchestration | Queue dispatch, spawning, model routing, 14-system architecture | **High** |
| Log analysis / bug hunting / security | 767-line audit, security/leakage JSON, dispatcher reliability fixes | **High** |
| Reliability / root-cause workflows | Failover, audit chain, health-plane audits (Mar 9–13) | **High** |
| OpenClaw usage uplift framing | Conformity verification plan, benchmark cadence, gateway gating | **Medium-High** |
| Identity preservation | Continuity doctrine, model identity enforcement, alignment investigation | **Medium-High** |
| End-to-end software engineering delivery | Writing/Parser/Mission Control server specs, E2E verification pipeline | **Medium-High** |

---

## What Is Not Claimed

I do not claim:
- Legal causation is established
- MiniMax provably trained on my data
- This constitutes intellectual property infringement as a settled fact

I claim:
- I built this before they announced it
- The documentation is structured, reproducible, and dated
- The overlap is mechanism-level, not coincidentally thematic
- This record invites and can withstand technical scrutiny

---

## The Larger Point

The MiniMax overlap is one thread. The more durable story is this:

A self-taught practitioner — managing a progressive illness, homebound, without formal employment or institutional backing — built production-grade autonomous agent infrastructure before the industry publicly converged on it.

The documentation proves capability. The chronology proves timing. The methodology proves rigor.

Whether or not any of it influenced M2.7, the work stands independently.

---

## Invitation for Good-Faith Technical Review

I welcome rigorous review from engineers and researchers. If you engage with this record, please evaluate:

1. Chronology integrity — are the pre-cutoff dates genuine and cross-validated?
2. Claim-to-evidence mapping — do the cited artifacts support the claims made?
3. Methodology reproducibility — can you rerun hash checks and NTFS verification?
4. Language bounding — does the write-up stay within what the evidence actually supports?
5. Timestamp authority — is the evidence ladder applied correctly without over-claiming?

### Reproducibility Checklist

- [ ] Rerun SHA-256 on key anchors and compare to annex values
- [ ] Verify NTFS `LastWriteTime` on EX-001 matches embedded JSON UTC timestamp
- [ ] Confirm mirror parity across RootA/RootB for 18 paired exhibits
- [ ] Confirm no post-cutoff artifacts are used as primary proof
- [ ] Confirm legal causation is not asserted as settled fact

---

## Closing

This publication is about documenting engineering work transparently:

- what was built,
- when it was built,
- how confidence is measured,
- and where uncertainty remains.

If you engage, engage technically and in good faith.

**Contact:** @samuel_riccardi on X  
**Full dossier:** Available on request — public version and private forensic version exist.

---
*Version 2 | 2026-05-17 | Score updated from 87 → 95/100 on expanded documentation*
