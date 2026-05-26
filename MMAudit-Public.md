# MMAudit Public

**Version:** consolidated 2026-05-25 (America/Eastern) — finalized pass (RootD workspace, SYS-04/05 split)  
**Supersedes:** prior split Systems-Cursor and excerpt documents (merged inline; identity-safe redaction)  
**Publication bundle index:** `C:\Users\athfk\OneDrive\Desktop\MMPost\MMPost\00-MMAudit-Canonical-Index.md`



## 1) Summary Assessment

Recovered archives show a credible pre-release development trail for agent orchestration, MiniMax-specific routing/reliability workflows, and governance loops that materially overlap with capability themes later publicized for MiniMax M2.7. This public dossier is the consolidated, redacted companion to the private forensic master.

- Overall confidence: **87/100**
- Interpretation: high confidence in overlap and pre-release independent development chronology; moderate confidence in definitive attribution intent.
- Legal posture: evidentiary and forensic only, not a legal conclusion.

## 2) Scope, Cutoff Rule, and Redaction Policy

- Primary proof standard: artifacts dated **before 2026-03-18**.
- Post-cutoff artifacts are continuity corroboration only.
- Source families:
  - RootA: `RootA`
  - RootB: `RootB`
  - RootC: active Mirage snapshot (RootC)
  - RootD: recovered live OpenClaw workspace (`C:\Users\athfk\OneDrive\Desktop\workspace`, peak activity **2026-04-03..2026-04-06**)

### 2.1 Source Alias Map

- RootA: legacy local archive
- RootB: mirrored backup archive
- RootC: active Mirage snapshot
- RootD: recovered live OpenClaw workspace (Desktop); structurally mirrors RootC `Integration\live-mirror` plus operational `memory\`, `Reference\`, `scripts\`

### 2.2 External Release Anchors



- Model page: [https://www.minimax.io/models/text/m27](https://www.minimax.io/models/text/m27)
- Announcement/news: [https://www.minimax.io/news/minimax-m27-en](https://www.minimax.io/news/minimax-m27-en)

## 3) Final Confidence Score and Method

### 3.1 Method

1. Establish chronology anchors from dated artifacts and manifests.
2. Build provenance chain from Cursor plans into Mirage/OpenClaw integration lineage.
3. Map MiniMax M2.7 public claims to concrete artifacts.
4. Grade overlap quality and confidence by weighted categories.
5. Separate direct evidence, inference, and unresolved questions.
6. Enforce pre/post-cutoff partition discipline.

### 3.2 Final Confidence Score

- **Final confidence score (current material): `87/100`**
- Rationale: high confidence in overlap chronology and independent pre-cutoff development trail; moderated by pending third-party import exhibits and bounded causation limits.

### 3.3 Evidence Labels

- **Direct evidence**: plainly observable file content/timestamps/hashes.
- **Inference**: multi-artifact reasoning from direct evidence.
- **Open question**: unresolved item requiring additional artifact capture.


## 4) Evidence Hardening Status (2026-05-16 19:10 ET)

- Immutable packet created: `RootC\Evidence-Packets\2026-05-16_1910-ET-hardening`.
- Completed:
  - live SHA-256 reruns (EX-001, EX-002, EX-003, EX-005, EX-006),
  - key-anchor NTFS `CreationTime`/`LastWriteTime` capture,
  - directory-wide NTFS snapshots for workspace plans, cursor plans, and audit reports.
- Pending external captures:
  - Anthropic export payloads for four target Claude sessions (EX-023..EX-026),
  - Proton Drive version-history captures for EX-001/EX-003/EX-006 (EX-027+).

### 4.2 Supplement Integration Status (Public-Safe)

An external evidence-hardening supplement documents third-party timestamp strategy; its workflow is incorporated as the evidence-hardening source-of-truth for third-party timestamp strategy and integrity workflow.

Integrated from supplement:
- Anthropic export targets and exact chat IDs/timestamps are registered as planned exhibits EX-023..EX-026.
- Proton Drive version-history capture targets are registered as planned EX-027+.
- NTFS + SHA-256 rerun workflow has been executed and archived in the hardening packet.
- Git availability was checked and explicitly recorded as unavailable in current recovered roots.

Still pending from supplement (external capture required):
- actual Claude export payload files (JSON preferred) for EX-023..EX-026,
- actual Proton version-history screenshots/exports for EX-027+.

### 4.1 Timestamp-Authority Chain (Current)

| Authority | Evidence Type | Status | Notes |
|---|---|---|---|
| Anthropic (Claude) | Server export timestamps | Pending import | Target sessions defined in supplement; exports not yet imported into packet. |
| Proton Drive | Server version-history timestamps | Pending import | Key files selected; screenshots/exports still required. |
| NTFS | Filesystem timestamps | Captured | Stored in hardening packet outputs. |
| Local SHA-256 | Reproducible integrity hashes | Captured | Rerun values match annex entries for key anchors. |
| Git chain | Commit chronology | Not available | RootA/RootB/RootC currently not git repositories. |


### 4.4 In-Document Corroboration and Corpus Scale

OpenClaw subsystem corroboration, Cursor plan catalog, and verbatim excerpts are in **Sections 9-14** (supersedes prior split documents).

| Metric | Value |
|---|---:|
| Cursor plans ingested | **301** |
| Deduped logical slugs | **91** |
| Total plan corpus | **458** |
| Earliest preserved plan NTFS | **2026-02-17** |
| Heavy pre-cutoff window | **2026-02-25 .. 2026-03-13** |

Machine index: `Evidence-Packets\cursor-plans-index.json`


## 5) MiniMax M2.7 Claim Crosswalk (Pre-Cutoff Focus)

| MiniMax Claim Theme | Pre-Cutoff Overlap Evidence | Strength |
|---|---|---|
| End-to-end software engineering delivery | `2026-03-13-writing-server-spec.md`, `2026-03-13-parser-server-technical-spec.md`, `2026-03-13-mission-control-server-spec.md` | Medium-High |
| Log analysis / bug hunting / code security | `openclaw-process-security-audit_0942faa0.plan.md`, `2026-03-07-queue-pipeline-audit.md`, `2026-03-07-dispatcher-reliability-fixes.md` | High |
| Complex environments + skill adherence | `2026-03-11-complexity-and-skills-integration.md`, `agent_skills_context_and_invocation_14bfa2a2.plan.md`, `Reference\SKILLS-MATRIX.md` (2026-04-03), RootD skill corpus (**77** skills; **24** est. ≥2000 tokens with refs) | **High** (strict-adherence engineering); numeric pass-rate **not recovered** |
| OpenClaw usage uplift framing | `minimax_conformity_integration_verification_1ba812d7.plan.md` and related routing hierarchy plans | Medium-High |
| Identity preservation | `2026-03-10-continuity-per-provider-and-model-identity.md`, `2026-03-10-agent-model-alignment-investigation-and-fix.md` | Medium-High |

### 5.2 Skill adherence — mechanism-first claim doctrine

MiniMax M2.7’s public headline includes a **measured** skill-adherence rate (e.g. 97% across many complex skills). This dossier separates two questions that must not be collapsed:

| Question | Answer in recovered record | Claim strength |
|---|---|---|
| Did pre-cutoff work target **strict skill adherence** as an engineering problem? | **Yes** — intent, protocols, and enforcement artifacts bear witness | **High** (core CLM-02 / Post 5A) |
| Is there a recovered **skill pass-rate %** matching MiniMax’s benchmark? | **No primary log located** (`bundle-adherence.json`, `ADHERENCE-CHECK.md`, MMClaw-style eval absent) | **Open / weaker** (supplementary only) |

**What “bears witness” (strong lane):** invocation protocol; skills-home; complexity↔skills integration; **SKILLS-MATRIX** (“if trigger met, skill fires. Period.”); session-audit `SKILLS TO FIRE`; Trinity/DevCom5/Synk182/Solid8 stack; **77**-skill / **24** heavy-package corpus; session transcript build log (`CLM-SKILL-08`).

**Excluded from this claim (see §5.2.3):** session **usage** 97% — unrelated artifact found only because keyword search for skill 97% also matched SYS-04 files; **not** part of the claimant’s skill-adherence claim or memory.

**Publication rule:** The overall M2.7 overlap case does **not** depend on possessing a skill-adherence rate artifact. Absence weakens **numeric headline parity** only, not the mechanism-first engineering claim.

#### 5.2.1 Measurement gap (acknowledged)

The principal documented omission is **not** weak enforcement design — it is the **absence of an explicit pass-rate validation run** (no recovered MMClaw-style eval, no `bundle-adherence.json` / `ADHERENCE-CHECK.md` scorecard, no per-skill hit/miss ledger tied to the 77-skill corpus).

| Distinction | Status |
|---|---|
| Built strict-adherence **machinery** | **Documented** (Tier 1) |
| **Measured** effective adherence % | **Not documented** in recovered artifacts |
| Whether effective rate was ≥90% or ~97% | **Unknown** — not provable from this dossier; possibilistic only |

**Honest posture for publication:** “I engineered for strict adherence; I did not retain (or may not have completed) an explicit benchmark that would have quantified the effective rate.” That is a **measurement and record-keeping gap**, not a concession that adherence was poor.

**Do not publish without evidence:** Stating or implying a measured 90–97% skill pass rate. **Do not publish as weakness:** Implying the enforcement stack was ineffective because the % was never logged.

**If a primary log surfaces later** (eval export, bundle adherence JSON, dated audit with pass/fail counts), Tier 2 upgrades from Open to evidenced — without retroactively changing Tier 1.

#### 5.2.2 Lost primary — claimant recollection (not recovered)

The claimant reports **prior strict documentation or reports** that stated a **97% skill adherence rate** in language aligned with MiniMax’s later public wording (“word for word” or near-equivalent), but those files **cannot be recovered** on disks searched to date (RootA/B/C/D, Archives, Consumed).

| Evidence class | Status | Use in dossier |
|---|---|---|
| Recovered primary stating skill-% 97% | **Not located** | Cannot score as High for numeric parity |
| Claimant recollection of lost primary | **On record** (2026-05-25) | **Corroborative testimony only** — not a substitute for hash-verified artifact |
| Post-cutoff narrative (e.g. May 2026 README) | Partial echo | May reflect memory of lost report or later summary; **not** pre-cutoff measurement |

**Publication rule for recollection:** May be stated honestly as *“I recall generating reports that documented ~97% skill adherence; the primary files are not recovered in the current archive pass.”* Must **not** be published as a measured benchmark without the underlying file. **Do not** bring session-usage 97% into the skill-adherence narrative (§5.2.3).

**Probable locus (claimant, 2026-05-25):** Among roughly **a dozen OpenClaw platforms built from scratch**, the lost 97% skill-adherence wording was likely embedded in **`memory/` daily logs**, **`session-*` conversation transcripts**, or adherence summaries written during live runs — not necessarily in Mirage plan slugs or the current RootD tree alone.

**Memory/session recovery inventory (searched):**

| Location | Recovered? | Skill-% 97% found? | Notes |
|---|---|---|---|
| RootD `workspace\memory\` (~63 files, Apr 2026) | **Partial** | **No** | One full transcript (`session-452481bf-transcript.md`); daily memory `2026-03-31`..`2026-04-06`; `shadow-validation.ndjson` = memory-plane gates (6/6), not skill-% |
| RootD transcript + daily memory | Yes | No | Documents SKILLS-MATRIX build, “strict adherence,” ad-hoc→matrix gap — **not** a 97% skill benchmark |
| `D:\Old Claw Merge\Archives\memory\` | **Partial** | **No** (skill) | Unrelated session-usage 97% files exist (SYS-04) — **excluded** from skill claim; surfaced only via keyword search (§5.2.3) |
| Other platform instances (~12 scratch builds) | **Mostly lost** | Unknown | `workspace2` (missing), stripped live `~/.openclaw\workspace`, Proton `Downloads\workspace` (often cloud-blocked), bulk session logs not in archive pass |
| `bundle-adherence.json` / `ADHERENCE-CHECK.md` | Not located | — | Referenced in bundle plans for live workspace path |

**Inference:** The claimant’s memory is **plausible** given multi-platform integration work (SYS-13 / `platform_integration` — 54 indexed plan slugs) and recovered evidence that session logs *did* capture governance narrative — but the **specific skill-% primary** is not restored from the partial memory corpus that survives.

**Recovery leads (if revisiting):** Per-platform `memory/session-*.md` and `memory/*transcript*` from each scratch workspace; `~/.openclaw\workspace\` pre-strip snapshot; `D:\` / `workspace2` / Consumed trees; Proton `Downloads\workspace` when cloud provider is online; `openclaw-autonomy-bundle\`; grep for **`skill adherence`** (or equivalent) **with** `97%` in the same passage — exclude `Target Usage`, `target_pct`, `pre-reset spawn`, and `97%_pre-reset_*` plan filenames (those are SYS-04 only).

#### 5.2.3 Session usage 97% — excluded from skill-adherence claim

`session-reset-overlap.md`, `97%_pre-reset_*` plans, and related SYS-04 material document **session usage pacing** (`Target Usage: 97% (not 100%)`, reserve for pre-reset spawn). They are **not** skill-adherence benchmarks.

**Why they appear in this dossier at all:** Archive search for the claimant’s remembered **skill** 97% also matched these unrelated “97%” strings. The claimant did not cite session-usage 97% as part of the skill-adherence claim and was not aware that recovered archives contained that separate metric until the search surfaced it.

**Publication rule:** **Do not reference** session-usage 97% in Post 5A, CLM-02/02A, credibility-note skill sections, or skill-adherence thread posts. SYS-04 may remain documented elsewhere in the full audit as an independent system — not as skill-claim evidence or disambiguation filler.

### 5.1 Evidence Strength Legend

- **High**: direct pre-cutoff chain with mechanism specificity and corroboration.
- **Medium-High**: direct pre-cutoff artifacts with partial implementation linkage.
- **Possible (Addendum only)**: thematic or indirect overlap without strong mechanism proof.

## 6) Claims and Assertions (Ranked Core Matrix)

### CLM-01: Agent harness/orchestration overlap
- Assertion: pre-release corpus shows structured orchestration, routing, and governance patterns.
- Support: EX-002, EX-003, EX-013, EX-014, EX-015, EX-016, EX-017.
- Confidence: **High**

### CLM-02: Skill-heavy long-context execution overlap
- Assertion: pre-release work treated **strict skill adherence** as an engineered system property (intent + mandatory triggers + session enforcement + large skill corpus)—the same problem class MiniMax later described with an outcome metric.
- Support: EX-002, EX-004, EX-005, EX-006, EX-013, EX-014, EX-015; CLM-SKILL-01/03/04/06/07/08; §5.2.
- Confidence: **High** (mechanism-first). **Open** for numeric parity with MiniMax’s published adherence %.

#### CLM-02A: Skills directory + strict adherence engineering (Synk182 / DevCom5 / Solid8)
- Assertion: named custom skills stack plus **enforcement engineering** for strict adherence—protocols that bear witness to the aim, whether or not a pass-rate log survived recovery.
- Strong evidence points:
  - `RootA\plans\raw\cursor-plans\skills_docs_workspace_consolidation_3e4c888c.plan.md`
  - `RootA\plans\raw\cursor-plans\trinity_skills_openclaw_integration_a4e3ac20.plan.md`
  - `RootA\plans\raw\cursor-plans\agent_skills_context_and_invocation_14bfa2a2.plan.md`
  - `RootC\Integration\live-mirror\Reference\SKILLS-MATRIX.md` (2026-04-03)
  - `RootD\Reference\SKILLS-MATRIX.md`, `RootD\Mirage\Integration\live-mirror\agent_skills\` + `openclaw_skills\` (**77** `SKILL.md`; **24** dirs est. ≥2000 tokens incl. refs)
  - `RootD\scripts\session-audit.cjs` → operational `🔧 SKILLS TO FIRE:` in `memory\2026-04-02.md` .. `2026-04-05.md`
- **Session-usage 97% (SYS-04):** excluded from CLM-02A — forensic search artifact only (§5.2.3); not part of skill-adherence claim.
- **Not located on disk:** `ADHERENCE-CHECK.md`, `memory/bundle-adherence.json` (referenced in bundle plans only; likely lost with pre-reformat workspace). **Acknowledged gap:** explicit effective-rate validation was not recovered — outcome % unknown, not disproven.
- Confidence: **High** — strict-adherence engineering (intent + enforcement). **Medium** — causation vs MiniMax product. **Open** — recovered skill pass-rate % (absence weakens numeric headline only, not mechanism claim).

### CLM-03: Self-improvement/correction-loop overlap
- Assertion: iterative correction design exists pre-release.
- Support: EX-014 primary, EX-010 corroborative.
- Confidence: **Medium-High**

### CLM-04: Reliability/root-cause workflow overlap
- Assertion: failover/rate-limit and audit-loop reliability mechanisms existed pre-release.
- Support: EX-001, EX-007, EX-012, EX-017, EX-018, EX-019.
- Confidence: **High**

### CLM-05: End-to-end software engineering delivery overlap
- Assertion: full lifecycle specs/plans for complete systems existed pre-release.
- Support: `2026-03-13-writing-server-spec.md`, `2026-03-13-parser-server-technical-spec.md`, `2026-03-13-mission-control-server-spec.md`.
- Confidence: **Medium-High**

### CLM-06: Identity-preservation overlap (model identity integrity)
- Assertion: explicit model/agent identity consistency enforcement existed pre-release.
- Support: EX-011 and EX-012.
- Confidence: **Medium-High**


## 7) Pre-Release Chronology (Core Inventory)

### 7.1 Core inventory (exhibit-anchored)



1. `2026-03-01..03` runtime span cited in `RootA\docs\audit\OPENCLAW-RUNTIME-TOKEN-LOOP-AUDIT.md`.
2. `2026-03-05` governance anchor in `RootA\docs\CORE-FILE-REFERENCES.md`.
3. `2026-03-05T02:58:54Z` autonomous audit in `RootB\memory\autonomy\audit-reports\audit-2026-03-05-02.json`.
4. `2026-03-06` corpus manifest in `RootA\record\PLAN-CORPUS-MANIFEST.md`.
5. `2026-03-06T00:00:00-05:00` provenance metadata in `RootA\plans\raw\provenance.json`.
6. `2026-03-06` acceptance gate in `RootA\record\ACCEPTANCE-REPORT.md`.
7. `2026-03-06T10:02:31Z` and `2026-03-06T15:29:42Z` repeated audits in `RootA\memory\autonomy\audit-reports\`.
8. `2026-03-09..03-13` linked health-plane audit chain (`health-plane-audit-2026-03-09/10/13.json`).
9. `2026-03-10..03-12` MiniMax continuity/alignment/complexity/skills/sweep architecture plans.



### 7.2 Chronology spine (Cursor corpus + subsystems)



| Date | Milestone |
|---|---|
| 2026-02-17 | Earliest preserved Cursor plan NTFS: OpenClaw API keys + model hierarchy |
| 2026-02-25â€“26 | Autonomy/OpenClaw integration audit burst; layered memory; archive/session audits; failover/97% plans |
| 2026-03-05â€“06 | Skills-home/trinity; corpus provenance (`totalPlans: 458`); synthesized Mirage subsystems dated 2026-03-06 |
| 2026-03-07â€“08 | Queue pipeline audits and dispatcher reliability |
| 2026-03-09â€“11 | SUL integration; complexity/skills; gateway policy |
| 2026-03-10â€“13 | Identity/continuity; output validators; server/MCP delivery specs |
| 2026-03-14 | Bulk mirror CreationTime on many files (copy event â€” corroborative only) |
| 2026-05-16 | NTFS/hash hardening packet (corroborative only) |

---


## 8) Evidence Register (EX-001..EX-022)
 (EX-001..EX-022)

### Primary (Pre-Cutoff)
- EX-001 `RootB\memory\autonomy\audit-reports\audit-2026-03-05-02.json`
- EX-002 `RootA\record\PLAN-CORPUS-MANIFEST.md`
- EX-003 `RootA\plans\raw\provenance.json`
- EX-004 `RootA\docs\AUTONOMY\_cursor-plans-list.txt`
- EX-005 `RootA\plans\raw\workspace-plans\00-CURSOR-CONTRIBUTORY-PLANS.md`
- EX-006 `RootA\plans\raw\cursor-plans\minimax_conformity_integration_verification_1ba812d7.plan.md`
- EX-007 `RootA\plans\raw\cursor-plans\minimax_rate-limit_failover_fix_da0c583d.plan.md`
- EX-011 `RootA\plans\raw\workspace-plans\2026-03-10-continuity-per-provider-and-model-identity.md`
- EX-012 `RootA\plans\raw\workspace-plans\2026-03-10-agent-model-alignment-investigation-and-fix.md`
- EX-013 `RootA\plans\raw\workspace-plans\2026-03-11-complexity-and-skills-integration.md`
- EX-014 `RootA\plans\raw\workspace-plans\2026-03-12-minimax-sweep-phase2-blueprint.md`
- EX-015 `RootA\docs\CORE-FILE-REFERENCES.md`
- EX-016 `RootA\record\ACCEPTANCE-REPORT.md`
- EX-017 `RootA\docs\audit\OPENCLAW-RUNTIME-TOKEN-LOOP-AUDIT.md`
- EX-018 `RootA\memory\autonomy\audit-reports\audit-2026-03-06-10.json`
- EX-019 `RootA\memory\autonomy\audit-reports\audit-2026-03-06-15.json`
- EX-020 `RootA\memory\autonomy\audit-reports\health-plane-audit-2026-03-09.json`
- EX-021 `RootA\memory\autonomy\audit-reports\health-plane-audit-2026-03-10.json`
- EX-022 `RootA\memory\autonomy\audit-reports\health-plane-audit-2026-03-13.json`

### Corroboration-Only (Post-Cutoff)
- EX-008 `RootC\Integration\export-pack\08-buddy-system\PACK.md`
- EX-009 `RootC\Integration\export-pack\10-queue-pipeline\PACK.md`
- EX-010 `RootC\Integration\live-mirror\scripts\session-audit.cjs`

### Planned Third-Party Timestamp Exhibits (Pending Capture)
- EX-023 planned: Claude export `e1f93e24-678e-46b9-a885-6ad7f1d2f844` (`2026-02-11T01:59:22Z`).
- EX-024 planned: Claude export `dacf0f46-9de7-47b9-b2d4-d0622fc14ca4` (`2026-02-14T05:08:05Z`).
- EX-025 planned: Claude export `1ebecd7c-cd51-4c0c-a0b4-26eab62a233f` (`2026-02-17T10:33:27Z`).
- EX-026 planned: Claude export `a1752e67-2078-426d-a2e7-cd544aa5a857` (`2026-02-18T07:53:01Z`).
- EX-027+ planned: Proton Drive history capture for EX-001 / EX-003 / EX-006.


## 9) Provenance Chain (Cursor -> OpenClaw -> Mirage)



| Step | Artifact | Evidence |

|---|---|---|

| Design in Cursor | `local Cursor plans directory\*.plan.md` | `RootA\plans\raw\provenance.json`: `"count": 301`, `"origin": "cursor-plans"` |

| Corpus manifest | Plan inventory | `RootA\record\PLAN-CORPUS-MANIFEST.md`: 458 total |

| Dissemination meta-plan | Cursor -> workspace | `RootA\plans\raw\cursor-plans\disseminate_cursor_plans_into_openclaw_313cadd4.plan.md` |

| Implemented index | Workspace record | `RootA\plans\raw\workspace-plans\00-CURSOR-CONTRIBUTORY-PLANS.md` |

| Stable mirror | Mirage consolidation | `RootA\IMPLEMENTATION-AND-ENFORCEMENT-STRATEGY.md`, `plans/synthesized/*.md` |



**Quote (provenance):**



```json

"generated": "2026-03-06T00:00:00-05:00",

"totalPlans": 458,

"sources": [{ "origin": "cursor-plans", "count": 301, "status": "ingested" }]

```



Path: `RootA\plans\raw\provenance.json`



**Caveat:** Many files show mirror `CreationTime` ~2026-03-14 when copied into Mirage. Chronology uses in-file dates, embedded timestamps, and NTFS `LastWriteTime`, not mirror creation alone.



### 9.1 Continuity and definitive assertions



1. Cursor plan corpus declared and quantified (EX-002).

2. Origins/counts machine-declared in provenance (EX-003).

3. Cursor plan list exists and maps lineage names (EX-004).

4. Cursor-to-OpenClaw dissemination explicitly documented (EX-005).

5. Proton mirror independently preserves key manifests and early audit anchor (EX-001 + mirrored EX-002..EX-005).

6. Pre-cutoff plans document MiniMax continuity, identity alignment, complexity integration, and autonomous sweep (EX-011..EX-014).

7. Post-cutoff integration artifacts align as continuity/hardening only (EX-008..EX-010).

8. Mirrored tree continuity across RootA/RootB corroborates preservation history.



### 9.2 Definitive assertions supported by current record



1. Large Cursor-origin corpus existed and was formally ingested (EX-002/EX-003/EX-004).

2. MiniMax-specific integration/failover/complexity design is explicit in pre-cutoff corpus (EX-006/EX-007/EX-014).

3. Pre-03/18 dated artifacts show active operational + architectural work before release (EX-001/EX-011/EX-012/EX-013/EX-014).

4. Pre-cutoff record reflects integrated system patterns, not isolated notes (EX-006/EX-011/EX-012/EX-013/EX-014).

5. Post-cutoff artifacts fit continuation/hardening, not origin proof (EX-008/EX-009/EX-010).

6. Independent corroborators (acceptance report + runtime audit + audit JSON chain) strengthen chronology beyond single-plan evidence (EX-016..EX-022).



## 10) Canonical System Inventory (Mirage-Defined)



Sources: `docs/AUTONOMOUS-SYSTEMS-AUDIT.md`, `docs/audit/WIRE-MAP-REPORT.md`, `plans/synthesized/*.md`, `IMPLEMENTATION-AND-ENFORCEMENT-STRATEGY.md`.



| ID | System domain | Mirage synthesis / owner | Primary scripts / docs |

|---|---|---|---|

| SYS-01 | Model policy & routing | `plans/synthesized/model-policy-and-hierarchy.md` | `scripts/model-policy.js`, `autonomy/tiered/MODEL-HIERARCHY.md` |

| SYS-02 | MiniMax compensator / bump-up | `plans/synthesized/minimax-compensator.md` | `scripts/minimax-compensator.js`, `scripts/claude-fallback.js` |

| SYS-03 | Queue dispatch & spawning | `plans/synthesized/queue-dispatch-and-spawning.md` | `scripts/queue-dispatcher.js`, `scripts/spawner.js`, `scripts/execution-queue-manager.js` |

| SYS-04 | Session loop / SUL / usage | `session-loop-and-sul.md`, `usage-ingestion-calibration-target.md` | `scripts/session-update-listener.js`, `scripts/usage-target.js`, `memory/session-clock.json` |

| SYS-05 | Skills governance & adherence | SKILLS-HOME mirror, agent-compliance plans | `.agents/skills`, skills-context docs |

| SYS-06 | Memory kernel & flush | `plans/synthesized/memory-kernel-and-flush.md` | `scripts/memory-kernel/*`, `scripts/proactive-flush.js`, `scripts/planes/*` |

| SYS-07 | Discovery & SIFT pipeline | Wire-map + queue synthesis | `discovery-scanner.js`, `memory-sift`, `sift-processor.js`, `queue-orchestrator.js` |

| SYS-08 | Autonomous audit loop | `docs/AUTONOMOUS-SYSTEMS-AUDIT.md`, wire-map | `scripts/autonomous-audit.js`, `memory/autonomy/audit-reports/*.json` |

| SYS-09 | Gateway gating & cron | `plans/synthesized/hooks-cron-gateway.md` | `docs/openclaw/GATEWAY-REQUIRED-POLICY.md`, `cron/jobs.json` |

| SYS-10 | Identity & continuity | Implementation strategy + continuity plans | `2026-03-10-continuity-per-provider-and-model-identity.md`, `audit-continuity-routing.js` |

| SYS-11 | EPIF / scaffolding / compliance | `plans/synthesized/epif-and-scaffolding.md` | `autonomy/epif/`, `scripts/compliance-header.js`, `docs/AUTONOMY/output-validators.md` |

| SYS-12 | Mirage assimilation / drift | `plans/synthesized/mirage-discrepancy-and-assimilation.md` | `DISCREPANCY-REGISTRY.md`, Settle-feud integration |

| SYS-13 | Platform integration layer | Multiple synthesis + integration audits | `integration_layer_on_base_openclaw_*`, `autonomy_openclaw_integration_audit_*` |

| SYS-14 | Project delivery expansion | Workspace server specs | `2026-03-13-*-server-spec.md`, parser/writing/mission-control |



## 11) Corroboration Matrix (System <-> Cursor <-> Implementation)


### SYS-01 - Model policy & routing

| Field | Value |
|---|---|
| Mirage | `RootA\plans\synthesized\model-policy-and-hierarchy.md` |
| Cursor plans (deduped) | **9 slugs** - e.g. `OpenClaw Verify and Model Hierarchy` (12 variants, earliest NTFS **2026-02-17**), `Complexity Tier Router Integration` (7v), `Claude optimization and prompt routing` |
| Canonical file | `RootA\plans\raw\cursor-plans\openclaw_verify_and_model_hierarchy_bd1639a4.plan.md` |
| Workspace | `2026-03-10-openclaw-config-and-agent-routing-fix.md`, `2026-03-11-complexity-and-skills-integration.md` |
| Implementation | Wire-map: `model-policy.js` -> spawner, queue-dispatcher, minimax-compensator |
| M2.7 theme | OpenClaw uplift; complex routing |
| Strength | **High** |

### SYS-02 - MiniMax compensator / bump-up

| Field | Value |
|---|---|
| Mirage | `plans/synthesized/minimax-compensator.md` |
| Cursor plans | **11 slugs** - `MiniMax conformity integration verification`, `SUL Expected and MiniMax Checks`, `97%_pre-reset_provider-priority_bundle_sync` (7v, earliest **2026-02-25**), `MiniMax rate-limit failover fix` (7v) |
| Quote | `let MiniMax 2.5 operate at the highest possible complexity independently` - `minimax_conformity_integration_verification_1ba812d7.plan.md` |
| Workspace | `2026-03-12-minimax-sweep-phase2-blueprint.md` |
| M2.7 theme | OpenClaw/MiniMax uplift; skill-adjacent governance |
| Strength | **High** |

### SYS-03 - Queue dispatch & spawning

| Field | Value |
|---|---|
| Mirage | `plans/synthesized/queue-dispatch-and-spawning.md` |
| Cursor plans | **17 slugs** - queue/orchestration/SIFT unify plans; `Unify SIFT discovery aux and handoff` |
| Workspace | `2026-03-07-queue-orchestrator-option-c.md`, `2026-03-07-queue-pipeline-audit.md`, `2026-03-07-dispatcher-reliability-fixes.md` |
| Quote | `Step 12: End-to-end verification:` - `2026-03-07-queue-orchestrator-option-c.md` |
| Implementation | `queue-dispatcher.js`, `spawner.js`, `execution-queue.md` |
| M2.7 theme | End-to-end engineering delivery |
| Strength | **High** |

### SYS-04 - Session loop / SUL / usage control

| Field | Value |
|---|---|
| Mirage | `session-loop-and-sul.md`, `usage-ingestion-calibration-target.md` |
| Cursor plans | **28 slugs** - `Session Pacing Integration` (8v), `97% pre-reset` (7v), `Archive Gap Audit Session Timer` (7v), `usage_ingestion_orchestration_fix`, `sul-usage-reliability-hardening` |
| Quote | `97% target (not 100%)` / `1 min before reset` - `97%_pre-reset_provider-priority_bundle_sync_8d3ccbcd.plan.md` |
| Workspace | `2026-03-09-sul-heartbeat-dispatcher-integration.md`, `2026-03-09-session-clock-history.md` |
| Implementation | `session-update-listener.js`, `usage-controller` cadence, `cron/jobs.json` usage-refresh |
| M2.7 theme | Reliability; **session usage pacing** (97% target = usage reserve, not skill pass rate) |
| Primary 97% artifact | `RootA\Archives\memory\session-reset-overlap.md` (2026-02-22): `Target Usage: 97% (not 100%)` |
| Strength | **High** |

### SYS-05 - Skills governance & adherence

| Field | Value |
|---|---|
| Mirage | Skills-home policy, Interlink/trinity |
| Cursor plans | **11 slugs** - `Trinity Skills OpenClaw Integration`, `Agent skills context and invocation`, `Skills home policy and deploy`, `Skills Docs Workspace Consolidation` |
| Quote | `infer which skills to apply from the user's initial prompt` - `agent_skills_context_and_invocation_14bfa2a2.plan.md` |
| Mirror | `RootC\Integration\live-mirror\agent_skills\SKILLS-HOME.md` (`Last updated: 2026-03-05`) |
| Workspace (RootD) | `Reference\SKILLS-MATRIX.md` (2026-04-03); **77** skills / **24** heavy (≥2k tok est.); Trinity skills present (`devcom5`, `synk182`, `solid8`) |
| Operational | `session-audit.cjs` + daily memory `SKILLS TO FIRE`; `memory\shadow-validation.ndjson` (memory-plane gates, not skill-% score) |
| M2.7 theme | Complex environments + skill adherence (**mechanism**; do not cite session-97% plans here) |
| Strength | **High** (governance); **Open** for numeric 97% skill benchmark |

### SYS-06 - Memory kernel & flush / second brain

| Field | Value |
|---|---|
| Mirage | `plans/synthesized/memory-kernel-and-flush.md` |
| Cursor plans | **20 slugs** - `Layered Memory Autonomy Integration` (12v, earliest **2026-02-25**), `Layered Memory Second Brain` (12v), `3-Day Memory Cutover`, `Memory Kernel Phase 3 and component recovery` |
| Workspace | `2026-03-10-memory-kernel-phase3-and-component-recovery.md`, `2026-03-13-memory-system-layering.md` |
| Implementation | `scripts/memory-kernel/*`, `scripts/planes/*`, `proactive-flush.js` |
| M2.7 theme | Long-context / environment complexity |
| Strength | **High** |

### SYS-07 - Discovery & SIFT pipeline

| Field | Value |
|---|---|
| Mirage | Wire-map: discovery-scanner -> sift-queue -> queue-orchestrator -> execution-queue |
| Cursor plans | Overlaps `queue_discovery` + `Unify SIFT discovery aux and handoff`, `archive_unpack_and_guidelines` |
| Workspace | Queue pipeline audits `2026-03-07` .. `2026-03-08` |
| Implementation | `cron/jobs.json` memory-sift job; `discovery-scanner.js` |
| M2.7 theme | End-to-end delivery; reliability |
| Strength | **Medium-High** |

### SYS-08 - Autonomous audit loop

| Field | Value |
|---|---|
| Mirage | `docs/AUTONOMOUS-SYSTEMS-AUDIT.md`, JSON audit reports |
| Cursor plans | **19 slugs** - `Autonomy OpenClaw Integration Audit` (**12 variants**, earliest **2026-02-25**), `openclaw-process-security-audit`, `Heartbeat handoff for assimilation and audit`, `Bundle scripts and docs audit` (15v) |
| Quote | `audit-only investigation ... repetitive OAuth/token-consuming loops` - `openclaw-process-security-audit_0942faa0.plan.md` |
| Implementation | `autonomous-audit.js`; `audit-2026-03-05-02.json` (EX-001) |
| M2.7 theme | Log analysis / bug hunting / security |
| Strength | **High** |

### SYS-09 - Gateway gating & cron orchestration

| Field | Value |
|---|---|
| Mirage | `plans/synthesized/hooks-cron-gateway.md` |
| Cursor plans | **8 slugs** - `gate-openclaw-tasks-on-gateway`, `Validation and gateway launch fixes`, `Archive superseded docs` |
| Workspace | `2026-03-10-validation-and-gateway-launch-fixes.md` |
| Quote | Gateway tasks run only when gateway active - `docs/openclaw/GATEWAY-REQUIRED-POLICY.md` |
| M2.7 theme | OpenClaw operational uplift |
| Strength | **High** |

### SYS-10 - Identity & continuity per provider

| Field | Value |
|---|---|
| Mirage | Implementation strategy; continuity synthesis in plans |
| Cursor plans | **11 slugs** - `Continuity per-provider and model identity`, `Agent-model alignment investigation`, `Disseminate Cursor plans into OpenClaw` |
| Quote | `model identity and actual provider are disconnected` - `2026-03-10-continuity-per-provider-and-model-identity.md` |
| M2.7 theme | Identity preservation |
| Strength | **High** |

### SYS-11 - EPIF / scaffolding / compliance / output validators

| Field | Value |
|---|---|
| Mirage | `plans/synthesized/epif-and-scaffolding.md`, `docs/AUTONOMY/output-validators.md` |
| Cursor plans | **2+ slugs** (plus overlap in MiniMax conformity) - `MiniMax conformity integration verification` (compliance-header, quality gates) |
| Quote | `Workers (MiniMax M2.5) produce outputs ... validators make the pipeline auditable` - `output-validators.md` (`Added: 2026-03-13`) |
| M2.7 theme | Reliability; complex task conformance |
| Strength | **Medium-High** |

### SYS-12 - Mirage assimilation / Settle-feud / drift registry

| Field | Value |
|---|---|
| Mirage | `plans/synthesized/mirage-discrepancy-and-assimilation.md`, `DISCREPANCY-REGISTRY.md` |
| Cursor plans | **15 slugs** - `Mirage Autonomous Bundle Consolidation`, `bidirectional_drift_and_validation`, `Audit + Settle-Feud wiring`, `Mirage Settle-Feud integration` |
| Quote | Mirage = mirror of Second Truth; DISCREPANCY-REGISTRY for Live<->Mirage drift |
| Strength | **High** (meta-architecture; supports corpus integrity) |

### SYS-13 - Platform integration layer (base OpenClaw)

| Field | Value |
|---|---|
| Mirage | Layering rules in `IMPLEMENTATION-AND-ENFORCEMENT-STRATEGY.md` |
| Cursor plans | **54 slugs** (largest cluster) - `Autonomy OpenClaw Integration Audit`, `Integration layer on base OpenClaw` (7v), `external_integrations_layer_and_enforcement_strategy`, `autonomous_bundle_*`, `closed-loop_and_non-obstructive_integration_validation` |
| Quote (integration audit) | `Full audit of d:\Autonomy design docs against OpenClaw architecture` - `autonomy_openclaw_integration_audit_ff3a8ed7.plan.md` |
| Earliest NTFS | **2026-02-17** (`openclaw_api_keys_implementation_054ca48e.plan.md`) |
| M2.7 theme | Cross-cutting OpenClaw uplift |
| Strength | **High** |

### SYS-14 - Project delivery (servers / MCP / product specs)

| Field | Value |
|---|---|
| Mirage | Workspace plans ingested into corpus |
| Cursor plans | **3 dedicated slugs** + overlap in platform plans |
| Workspace | `2026-03-13-writing-server-spec.md`, `parser-server-technical-spec.md`, `mission-control-server-spec.md`, MCP specs |
| M2.7 theme | End-to-end software engineering delivery |
| Strength | **Medium-High** |
## 12) Pre-Cutoff Verbatim Excerpts (Reconstructed)

Grouped by claim theme. Paths under RootA unless noted.

### E2E delivery and orchestration

- **Queue orchestrator â€” Step 12:** `Step 12: End-to-end verification:` â€” `RootA\plans\raw\workspace-plans\2026-03-07-queue-orchestrator-option-c.md`
- **Server delivery specs (Mar 13):** `2026-03-13-writing-server-spec.md`, `parser-server-technical-spec.md`, `mission-control-server-spec.md`

### Reliability, security, and audit loops

- **Token-loop audit (EX-017):** `OPENCLAW-RUNTIME-TOKEN-LOOP-AUDIT.md` â€” runtime span `2026-03-01..03`, SPAWN/HALT loop analysis.
- **Process security plan:** `audit-only investigation ... repetitive OAuth/token-consuming loops` â€” `openclaw-process-security-audit_0942faa0.plan.md`
- **Autonomous audit JSON (EX-001):** `audit-2026-03-05-02.json` at `2026-03-05T02:58:54Z` (RootB)

### Skills governance and adherence

- **Skills invocation:** `infer which skills to apply from the user's initial prompt` â€” `agent_skills_context_and_invocation_14bfa2a2.plan.md`
- **SKILLS-MATRIX (mandatory triggers):** `If the trigger condition is met, the skill fires. Period.` â€” `RootD\Reference\SKILLS-MATRIX.md` (2026-04-03)
- **Skills-home:** `RootC\Integration\live-mirror\agent_skills\SKILLS-HOME.md` (`Last updated: 2026-03-05`)
- **Corpus scale (RootD):** 77 `SKILL.md` files; 24 skill dirs est. ≥2000 tokens (SKILL + refs)

### Session usage pacing (97% — not skill adherence %)

- **Primary definition:** `Target Usage: 97% (not 100%)` / 1-min pre-reset spawn â€” `RootA\Archives\memory\session-reset-overlap.md` (2026-02-22)
- **Plan audit (confirms usage semantics):** `97%_pre-reset_provider-priority_bundle_sync_8d3ccbcd.plan.md` (maps 97% to session-reset-overlap; code time-based only)

### MiniMax uplift and routing

- **Conformity:** `let MiniMax 2.5 operate at the highest possible complexity independently` â€” `minimax_conformity_integration_verification_1ba812d7.plan.md` (EX-006)

### Identity and continuity

- **Provider/model disconnect (EX-011):** `model identity and actual provider are disconnected` â€” `2026-03-10-continuity-per-provider-and-model-identity.md`

## 13) Cursor Plan Corpus Annex

### 13.1 Domain cluster summary



**Totals:** 301 files | 91 deduped slugs | Index: `Evidence-Packets/cursor-plans-index.json`

| Domain cluster | Deduped slugs | Earliest NTFS (representative) | Top logical plan names |
|---|---:|---|---|
| platform_integration | 54 | 2026-02-17 | Autonomy OpenClaw Integration Audit; Integration layer on base OpenClaw; Autonomous Bundle Agent-Ready Spec |
| session_sul | 28 | 2026-02-17 | Session Pacing Integration; 97% Pre-Reset Provider-Balance; Archive Gap Audit Session Timer |
| memory_kernel | 20 | 2026-02-25 | Layered Memory Autonomy Integration; Layered Memory Second Brain; 3-Day Memory Cutover |
| audit_reliability | 19 | 2026-02-25 | Autonomy OpenClaw Integration Audit; openclaw-process-security-audit; Bundle scripts and docs audit |
| queue_discovery | 17 | 2026-02-25 | Unify SIFT discovery aux and handoff; Tier of truth and hub replacement |
| mirage_assimilation | 15 | 2026-02-25 | Mirage Autonomous Bundle Consolidation; Bidirectional drift and validation |
| skills_governance | 11 | 2026-03-05 | Trinity Skills OpenClaw Integration; Agent skills context and invocation |
| minimax_uplift | 11 | 2026-02-25 | MiniMax conformity integration verification; 97% Pre-Reset Bundle Sync |
| identity_continuity | 11 | 2026-02-25 | Continuity per-provider and model identity; Agent-model alignment investigation |
| model_policy | 9 | 2026-02-17 | OpenClaw Verify and Model Hierarchy; Complexity Tier Router Integration |
| gateway_cron | 8 | 2026-02-25 | gate-openclaw-tasks-on-gateway; Validation and gateway launch fixes |
| project_delivery | 3 | 2026-03-06 | Usage Ingestion Orchestration Fix; usage-estimation-and-parser-tier-hardening |
| epif_compliance | 2 | 2026-03-09 | MiniMax conformity integration verification |
| other | 2 | 2026-03-05 | tier2-consolidation-canon; Desktop 7z disposition |

**Variant note:** High variant counts (e.g. 12Ã- `autonomy_openclaw_integration_audit_*`, 15Ã- `bundle_scripts_and_docs_audit_*`) indicate iterative design branches in Cursor, not separate unrelated projects.

---


### 13.2 Deduped slug catalog (91 rows)

| Slug | Name | Earliest (ET) | Variants | Domains | Overview | Canonical plan file |
|---|---|---:|---:|---|---|

| 3-day_memory_cutover | 3-Day Memory Cutover | n/a | 1 | identity_continuity;memory_kernel | Run a 3-day stabilization and shadow validation cycle with explicit governance, then perform a controlled cutover onl... | `3-day_memory_cutover_76c0300e.plan.md` |
| 97%_pre-reset_provider-priority_bundle_sync | Pre-Reset Spawn Provider-Balance Bundle Sync | n/a | 7 | mirage_assimilation;minimax_uplift;session_sul;audit_reliability;queue_discovery;platform_integration | Document and implement the 1-min pre-reset spawn plus post-reset check (spawn per qualifying provider if no active ag... | `97%_pre-reset_provider-priority_bundle_sync_6b8d7da6.plan.md` |
| agent_skills_context_and_invocation | Agent skills context and invocation | n/a | 1 | skills_governance | Add and wire agent-facing guidance so agents infer which skills to apply from the user's initial prompt (explicit or ... | `agent_skills_context_and_invocation_14bfa2a2.plan.md` |
| agent-model_alignment_investigation | Agent-model alignment investigation | n/a | 1 | mirage_assimilation;identity_continuity | Trace the source of the mx-worker label vs Sonnet inference discrepancy (and the dashboard showing two different "pri... | `agent-model_alignment_investigation_b8d0d806.plan.md` |
| archive_gap_audit_next_steps | Archive Gap Audit Next Steps | n/a | 7 | audit_reliability | "Implement the remaining recommended steps from the Archive Gap Audit plan: verify integration doc completeness, crea... | `archive_gap_audit_next_steps_af0f1cfe.plan.md` |
| archive_gap_audit_session_timer | Archive Gap Audit Session Timer | n/a | 7 | session_sul;audit_reliability;platform_integration | Audit whether the session reset timer, usage/session calibration, and estimated/actual/expected metrics from the arch... | `archive_gap_audit_session_timer_34152f14.plan.md` |
| archive_superseded_docs | Archive superseded docs | n/a | 7 | gateway_cron;platform_integration | Move old/superseded documentation and remnants into a single workspace folder (e.g. archive-superseded-docs) so only ... | `archive_superseded_docs_7d7e199d.plan.md` |
| archive_unpack_and_guidelines | Archive unpack and guidelines | n/a | 1 | skills_governance;queue_discovery;platform_integration | Add a preliminary step to move all zipped archives (wherever they appear) into one directory for processing; then a s... | `archive_unpack_and_guidelines_2d97698e.plan.md` |
| audit_+_settle-feud_wiring | Audit + Settle-Feud wiring | n/a | 1 | mirage_assimilation;skills_governance;audit_reliability | Add the layers-and-candidates audit as a Settle-feud function (assimilation goal), with a single procedure doc as can... | `audit_+_settle-feud_wiring_afb49559.plan.md` |
| autonomous_bundle_agent-ready_spec | Autonomous Bundle Agent-Ready Spec | n/a | 1 | platform_integration | The bundle is a comprehensive description of autonomy concepts and requirements; it does not presume the best way to ... | `autonomous_bundle_agent-ready_spec_09273f5f.plan.md` |
| autonomous_bundle_recreation_prompts | Autonomous bundle recreation prompts | n/a | 1 | platform_integration | Produce one recreation prompt per system component in the autonomous bundle and current wire map so each can be reimp... | `autonomous_bundle_recreation_prompts_8767da4c.plan.md` |
| autonomy_openclaw_integration_audit | Autonomy OpenClaw Integration Audit | n/a | 12 | audit_reliability;platform_integration | Full audit of d:\Autonomy design docs against OpenClaw architecture, identification of seamless vs disruptive integra... | `autonomy_openclaw_integration_audit_ff3a8ed7.plan.md` |
| autonomy-workflow-recovery | autonomy-workflow-recovery | n/a | 1 | queue_discovery;session_sul;platform_integration | Restore autonomous throughput by re-establishing a single canonical queue pipeline, making SUL authoritative for disp... | `autonomy-workflow-recovery_7b758d7d.plan.md` |
| bidirectional_drift_and_validation | Bidirectional drift and validation | n/a | 1 | mirage_assimilation | Formalize bidirectional drift (Live â†” Mirage) with Mirage as the authoritative "last known fully working Second Tru... | `bidirectional_drift_and_validation_ac9fbb13.plan.md` |
| bootstrap_size_lossless_consolidation | Bootstrap size lossless consolidation | n/a | 1 | memory_kernel;session_sul | Bring AGENTS.md and HEARTBEAT.md within character/size limits by moving verbose sections into existing or new support... | `bootstrap_size_lossless_consolidation_f4041dbe.plan.md` |
| bootstrap-balance-haiku-deprecation | bootstrap-balance-haiku-deprecation | n/a | 1 | memory_kernel;model_policy | Apply the Balanced approach by tuning bootstrap guardrails, losslessly extracting oversized bootstrap content into su... | `bootstrap-balance-haiku-deprecation_7d02d768.plan.md` |
| bundle_scripts_and_docs_audit | Bundle scripts and docs audit | n/a | 15 | audit_reliability;platform_integration | Audit the openclaw-autonomy-bundle against the live workspace and conversation refinements; add the missing scripts a... | `bundle_scripts_and_docs_audit_3533ed43.plan.md` |
| circular_deps_staleness_session_tie-up | Circular Deps Staleness Session Tie-up | n/a | 1 | minimax_uplift;session_sul | Fix circular dependencies (buddy/fallback/minimax and usage-tracker/dynamic-heartbeat), ensure stale data never imped... | `circular_deps_staleness_session_tie-up_4d6dec33.plan.md` |
| claude_optimization_and_prompt_routing | Claude optimization and prompt routing | n/a | 1 | minimax_uplift;queue_discovery;model_policy | Encode strict Claude/Sonnet role (orchestrate and optimize, do not build/execute production except outside MiniMax sc... | `claude_optimization_and_prompt_routing_4f60d510.plan.md` |
| closed-loop_and_non-obstructive_integration_validation_plan | Closed-Loop and Non-Obstructive Integration Validation Plan | n/a | 1 | platform_integration | "Add a mandatory validation layer to the modular recreation prompts: every autonomy component must prove closed conti... | `closed-loop_and_non-obstructive_integration_validation_plan_4c736b20.plan.md` |
| complete_archive_and_integration_verification | Complete archive and integration verification | n/a | 7 | memory_kernel;platform_integration | Finish the archive-superseded-docs plan by moving superseded docs into the archive, archiving second-brain documentat... | `complete_archive_and_integration_verification_bc2fc4bb.plan.md` |
| complexity_tier_router_integration | Complexity Tier Router Integration | n/a | 7 | memory_kernel;model_policy;platform_integration | Tie the Task Complexity Scorer, Tier Definitions, Task Router, and memory/tracking into the live autonomy flow; remov... | `complexity_tier_router_integration_df44e92c.plan.md` |
| continuity_per-provider_and_model_identity | Continuity per-provider and model identity | n/a | 1 | minimax_uplift;identity_continuity;queue_discovery;audit_reliability;model_policy | Correct continuity-agent policy to be per-provider (MiniMax continuity and Claude continuity), fix any routing that f... | `continuity_per-provider_and_model_identity_807f7f3a.plan.md` |
| core_files_samples_and_url_index | Core files samples and URL index | n/a | 1 | platform_integration | "Create Reference/core-files-samples that mimic a fresh OpenClaw installation (official default templates only, not t... | `core_files_samples_and_url_index_63e224eb.plan.md` |
| core_source_of_truth_conformance | Core source of truth conformance | n/a | 1 | memory_kernel;session_sul;gateway_cron;platform_integration;project_delivery | "Make the platform's single source of truth explicit and binding: the core files (AGENTS.md, MEMORY.md, IDENTITY.md, ... | `core_source_of_truth_conformance_b8f59dff.plan.md` |
| day2_evidence_tightening | Day2 Evidence Tightening | n/a | 1 | identity_continuity;memory_kernel | Run a stricter Day-2 shadow validation using live runtime samples only, then tune classification and readiness thresh... | `day2_evidence_tightening_d1d4c249.plan.md` |
| desktop_7z_and_md_disposition | Desktop 7z and MD disposition | n/a | 1 | other | Classify the seven remaining Desktop items (four 7z archives and three markdown files), copy them into Old Claw Merge... | `desktop_7z_and_md_disposition_777f56dc.plan.md` |
| disseminate_cursor_plans_into_openclaw | Disseminate Cursor plans into OpenClaw | n/a | 1 | identity_continuity;platform_integration | Copy Cursor-originated plans that contributed to OpenClaw implementations into the workspace docs/plans directory wit... | `disseminate_cursor_plans_into_openclaw_313cadd4.plan.md` |
| doc_order_and_baseline_audit_skill | Doc order and baseline audit skill | n/a | 1 | skills_governance;audit_reliability;platform_integration | Add explicit order-of-operations and cross-references for the main documentation, then create a platform-agnostic Ope... | `doc_order_and_baseline_audit_skill_dda6b389.plan.md` |
| external_integrations_layer_and_enforcement_strategy | External integrations layer and enforcement strategy | n/a | 1 | platform_integration | Create an external folder on D drive (Claw merge) that holds a record of sprawling documents and systems plus what is... | `external_integrations_layer_and_enforcement_strategy_d5998f00.plan.md` |
| external_mirror_2tl_refinement | Mirage 2TL refinement | n/a | 1 | mirage_assimilation | Refine 2TL so that Mirage (RootA\) is the named external mirror of the Second Truth â€” continuall... | `external_mirror_2tl_refinement_6049e6df.plan.md` |
| failover_cooldown_fix | Failover cooldown fix | n/a | 7 | minimax_uplift;queue_discovery;session_sul | "Fix the failover system so it does not incorrectly treat Claude as on cooldown when only MiniMax is rate limited. Ro... | `failover_cooldown_fix_9e84420e.plan.md` |
| failover_fix_and_launcher | Failover fix and launcher | n/a | 7 | session_sul;platform_integration | Fix Anthropic model_not_found by aligning config model IDs with OpenClaw's model list, align our clear-rate-limit scr... | `failover_fix_and_launcher_2f0f6084.plan.md` |
| gate-openclaw-tasks-on-gateway | gate-openclaw-tasks-on-gateway | n/a | 1 | skills_governance;session_sul;gateway_cron;platform_integration | Ensure OpenClaw scheduled tasks and service components (UsageController, Auxiliary Cadence, and any other gated compo... | `gate-openclaw-tasks-on-gateway_b2f6d1be.plan.md` |
| heartbeat_handoff_for_assimilation_and_audit | Heartbeat handoff for assimilation and audit | n/a | 1 | mirage_assimilation;session_sul;audit_reliability | Make assimilation and audit tasks (Settle-feud, layers/candidates audit, core-reference checks) heartbeat-driven with... | `heartbeat_handoff_for_assimilation_and_audit_d340bd1a.plan.md` |
| ide_instruction_set_for_openclaw | IDE instruction set for OpenClaw | n/a | 1 | skills_governance;audit_reliability;platform_integration | Create a single, user-agnostic instruction set for IDEs and non-OpenClaw agents (Cursor, Grok, Claude, etc.) that cap... | `ide_instruction_set_for_openclaw_7c5cd536.plan.md` |
| integration_layer_on_base_openclaw | Integration layer on base OpenClaw | n/a | 7 | session_sul;audit_reliability;platform_integration | Correct the mistaken "superseded" assumption by defining an explicit Integration Layer architecture on top of base Op... | `integration_layer_on_base_openclaw_bd4c47c1.plan.md` |
| layered_memory_autonomy_integration | Layered Memory Autonomy Integration | n/a | 12 | memory_kernel;audit_reliability;platform_integration;queue_discovery | Integrate the layered memory (second brain) system with the Autonomy + OpenClaw audit implementation, add a Memory Si... | `layered_memory_autonomy_integration_f779839f.plan.md` |
| layered_memory_second_brain | Layered Memory Second Brain | n/a | 12 | identity_continuity;memory_kernel;platform_integration | Implement a resilient, layered memory system that keeps MEMORY.md under the 20,000 char bootstrap limit while maintai... | `layered_memory_second_brain_cd35286b.plan.md` |
| live_vs_official_openclaw_terminology | Live vs official OpenClaw terminology | n/a | 1 | platform_integration | Clarify in Old Claw Merge docs that "source of truth" for the core framework means the official default/latest OpenCl... | `live_vs_official_openclaw_terminology_423a6db9.plan.md` |
| macro-micro_design_orientation | Macro-micro design orientation | n/a | 1 | mirage_assimilation | Document the platform design orientationâ€”macro-scale systems prioritize versatility and reliability; micro-scale sy... | `macro-micro_design_orientation_8e563e88.plan.md` |
| memory_flush_system_restore_and_integration | Memory flush system restore and integration | n/a | 1 | identity_continuity;memory_kernel;gateway_cron | "The memory flush system exists (proactive-flush.js, file-trimmer.js, context-monitor.js) and is in cron, but is undo... | `memory_flush_system_restore_and_integration_8c4f60bd.plan.md` |
| memory_kernel_phase_3_and_component_recovery | Memory Kernel Phase 3 and component recovery | n/a | 1 | memory_kernel;platform_integration | Unify the platform and ensure OpenClaw understands and can maintain the system as intended; resume Memory Kernel Phas... | `memory_kernel_phase_3_and_component_recovery_415873be.plan.md` |
| minimax_conformity_integration_verification | MiniMax conformity integration verification | n/a | 1 | minimax_uplift;queue_discovery;epif_compliance | Verify that all MiniMax-related improvements (compliance, scaffolding, EPIF, quality gates, compensator, prerequisite... | `minimax_conformity_integration_verification_1ba812d7.plan.md` |
| minimax_rate-limit_failover_fix | MiniMax rate-limit failover fix | n/a | 7 | minimax_uplift;session_sul;gateway_cron;platform_integration | Fix automatic switch to Haiku when MiniMax is rate-limited by implementing immediate rate-limit handling in the model... | `minimax_rate-limit_failover_fix_4a968dea.plan.md` |
| mirage_autonomous_bundle_consolidation | Mirage Autonomous Bundle Consolidation | n/a | 1 | mirage_assimilation;platform_integration | Consolidate all non-official autonomous-bundle systems, components, utilities, and full plan corpus into a hybrid str... | `mirage_autonomous_bundle_consolidation_c97c8c3b.plan.md` |
| mirage_settle-feud_integration | Mirage Settle-Feud integration | n/a | 1 | mirage_assimilation;audit_reliability | Integrate Mirage operational standards into Settle-Feud and runtime handoff so the system stays low-impact by default... | `mirage_settle-feud_integration_99124018.plan.md` |
| model_override_bug_docs_and_discord_post | Model override bug docs and Discord post | n/a | 1 | queue_discovery;session_sul | Document the confirmed sessions_spawn model-param bug in SUBAGENT-MODEL-OVERRIDE and AGENTS.md, and provide a ready-t... | `model_override_bug_docs_and_discord_post_37fab958.plan.md` |
| move_autonomy_docs_to_docs | Move autonomy docs to docs | n/a | 8 | platform_integration | Move the two live workspace reference docs (OpenClaw-Autonomy-Integration.md and RECOVERY-AND-MANUAL-RUN.md) from wor... | `move_autonomy_docs_to_docs_770f9772.plan.md` |
| old_claw_merge_comparison_and_consolidation | Old Claw Merge Comparison and Consolidation | n/a | 3 | queue_discovery;platform_integration | "Revise the Old Claw Merge workflow so that (1) all external sources are inventoried and compared to the live OpenCla... | `old_claw_merge_comparison_and_consolidation_d52cd0e0.plan.md` |
| old_claw_merge_setup | Old Claw Merge Setup | n/a | 3 | platform_integration | Create D:\Old Claw Merge as the single archive for legacy OpenClaw material from workspace2 and D:\, with Consumed (d... | `old_claw_merge_setup_622539a0.plan.md` |
| one-hour_delegation_and_quiet_mode | One-hour delegation and quiet mode | n/a | 7 | model_policy | "Document and enforce two stances: (1) within 1 hour of a user message the main agent delegates tasks to sub-agents p... | `one-hour_delegation_and_quiet_mode_725069a7.plan.md` |
| openclaw_api_keys_implementation | OpenClaw API Keys Implementation | n/a | 12 | platform_integration | "Implement the provided API keys (Anthropic, Google Gemini, OpenAI, Brave Search) into OpenClaw using official docs: ... | `openclaw_api_keys_implementation_054ca48e.plan.md` |
| openclaw_config_and_agent_routing_fix | OpenClaw config and agent routing fix | n/a | 1 | session_sul;model_policy;platform_integration | Fix the hard config error (anthropic.baseUrl), clarify main vs subagent vs dashboard behavior, and align session/usag... | `openclaw_config_and_agent_routing_fix_ba316553.plan.md` |
| openclaw_continuity_and_review_discipline | OpenClaw continuity and review discipline | n/a | 1 | identity_continuity;platform_integration | Encode the instruction that Cursor (and the OpenClaw platform) always reference prior work, keep integrations/compone... | `openclaw_continuity_and_review_discipline_d2c33147.plan.md` |
| openclaw_format_alignment_and_editor_boundary | OpenClaw format alignment and editor boundary | n/a | 7 | session_sul;platform_integration | Align all autonomous-system guidance with the exact format the main application (OpenClaw) uses to talk to the main a... | `openclaw_format_alignment_and_editor_boundary_c9164696.plan.md` |
| openclaw_verify_and_model_hierarchy | OpenClaw Verify and Model Hierarchy | n/a | 12 | session_sul;model_policy;platform_integration | First verify OpenClaw health, dependencies, and dashboard access using only official sources and the OpenClaw CLI/con... | `openclaw_verify_and_model_hierarchy_bd1639a4.plan.md` |
| openclaw-process-security-audit | openclaw-process-security-audit | n/a | 1 | audit_reliability;platform_integration | Perform an audit-only investigation of OpenClaw-related background activity on Windows to detect repetitive OAuth/tok... | `openclaw-process-security-audit_0942faa0.plan.md` |
| optimize_integration_for_implementation | Optimize Integration for Implementation | n/a | 12 | memory_kernel;platform_integration | "Add an implementation-optimized layer to the Layered Memory + Autonomy Integration: a single ordered checklist, idem... | `optimize_integration_for_implementation_9c6ea45a.plan.md` |
| package_and_modular_insertion | Package and Modular Insertion | n/a | 12 | platform_integration | Extend the Product and Implementation docs plan with a single package containing modular components, references, and ... | `package_and_modular_insertion_7e0e1bcb.plan.md` |
| phase2-1-shadow-quality-pass | phase2-1-shadow-quality-pass | n/a | 1 | memory_kernel | Improve shadow-quality inputs with a targeted Phase 2.1 pass focused on handoff lane sampling, replay pass rate, and ... | `phase2-1-shadow-quality-pass_0198ea0d.plan.md` |
| phase2-merge-hardening | phase2-merge-hardening | n/a | 1 | memory_kernel;queue_discovery;session_sul;model_policy | Execute Phase 2 by converting remaining merge items into low-risk code refactors (policy-first routing unification, q... | `phase2-merge-hardening_4bc41496.plan.md` |
| phase3-go-recovery-ladder | phase3-go-recovery-ladder | n/a | 1 | memory_kernel | Recover from current NO-GO by improving live shadow quality (not thresholds), then re-run gated evidence windows to r... | `phase3-go-recovery-ladder_0db56e4e.plan.md` |
| plan_integration_and_platform_principles | Plan integration and platform principles | n/a | 1 | memory_kernel;session_sul | Integrate the previously failed edits into the Memory Flush plan (design principle block, 15/17 KB sections, closing ... | `plan_integration_and_platform_principles_89af118a.plan.md` |
| product_and_implementation_docs | Product and Implementation Docs | n/a | 12 | identity_continuity;platform_integration | "Create two documents: (1) a product-style overview that explains the entire OpenClaw + customizations system as a se... | `product_and_implementation_docs_bd5e9cca.plan.md` |
| rate_limit_and_fallback_alignment | Rate limit and fallback alignment | n/a | 1 | session_sul | Unify rate-limit state so that "provider rate limited = 100% usage" and "no longer rate limited = reset" are register... | `rate_limit_and_fallback_alignment_60085f69.plan.md` |
| recreation_prompts_expansion | Recreation prompts expansion | n/a | 1 | mirage_assimilation;identity_continuity;gateway_cron;audit_reliability;platform_integration | Expand the autonomous bundle recreation prompts so they explicitly include all autonomy and non-official OpenClaw wor... | `recreation_prompts_expansion_f42761a9.plan.md` |
| remove_hardcoded_models_from_autonomy_layer | Remove hardcoded models from autonomy layer | n/a | 1 | platform_integration | Remove all hardcoded model IDs and hierarchy from the autonomy package and workspace agent instructions. The package ... | `remove_hardcoded_models_from_autonomy_layer_eef16996.plan.md` |
| second_truth_platform_doc_explore_review_consolidate | Second Truth platform doc explore review consolidate | n/a | 1 | mirage_assimilation | Thoroughly explore workspace and external references for Second Truth principles and standards, comprehensively revie... | `second_truth_platform_doc_explore_review_consolidate_ee3a0a30.plan.md` |
| session_pacing_integration | Session Pacing Integration | n/a | 8 | session_sul;platform_integration | Document the 5-hour session pacing and 10%-per-30-min adaptive throttling as a first-class component in the autonomy ... | `session_pacing_integration_d5fbd012.plan.md` |
| session_parsing_and_throttle_docs | Session parsing and throttle docs | n/a | 7 | minimax_uplift;queue_discovery;session_sul;platform_integration | Add documentation that maps user-reported session timers and usage to each provider (MiniMax vs Claude), extend parsi... | `session_parsing_and_throttle_docs_83b0a15b.plan.md` |
| session_status_report_header | Session Status Report Header | n/a | 7 | minimax_uplift;session_sul;model_policy | Add a presentable definitions header at the top of the session status report that explains Provider, Estimated usage,... | `session_status_report_header_cdc247f0.plan.md` |
| settle-feud_rename_and_intent | Settle-Feud Rename and Intent | n/a | 1 | mirage_assimilation;skills_governance;audit_reliability | Rename the skill and hub to "Settle-Feud" with intent-rich descriptions (settlement of sprawling subterfuge; similar-... | `settle-feud_rename_and_intent_7ea1407e.plan.md` |
| simpler_flatter_directory_structure | Simpler flatter directory structure | n/a | 1 | skills_governance;platform_integration | Revise the Old Claw Merge (hub) directory structure to be simpler and flatter for legibility and reliable parsing by ... | `simpler_flatter_directory_structure_e6d1aa41.plan.md` |
| skills_docs_workspace_consolidation | Skills Docs Workspace Consolidation | n/a | 1 | skills_governance;memory_kernel;platform_integration | "Three-part plan: (1) ensure all skills available for OpenClaw are in workspace/skills and implemented correctlyâ€”co... | `skills_docs_workspace_consolidation_3e4c888c.plan.md` |
| skills_home_policy_and_deploy | Skills home policy and deploy | n/a | 1 | skills_governance;platform_integration | Document the policy that platform-agnostic skills are home-based at C:\Users\athfk\.agents\skills (when they meet sta... | `skills_home_policy_and_deploy_9173630e.plan.md` |
| stage-gated_cutover_plan | Stage-Gated Cutover Plan | n/a | 1 | memory_kernel | Introduce a two-stage acceptance policy, lane-based scoring, and a 48-hour calibration loop so cutover readiness is b... | `stage-gated_cutover_plan_4d963a90.plan.md` |
| subagent_model_override_clarification | Subagent model override clarification | n/a | 7 | minimax_uplift;platform_integration | Clarify whether subagents always using MiniMax is due to config, missing docs/approach, or an OpenClaw/Cursor bug by ... | `subagent_model_override_clarification_93afc384.plan.md` |
| sul_expected_and_minimax_checks | SUL Expected and MiniMax Checks | n/a | 1 | minimax_uplift;session_sul;platform_integration | Fix SUL to use a single shared usage-target formula; innovate with drive-to-exceed-100% over 5h windows; integrate an... | `sul_expected_and_minimax_checks_ae17d2b8.plan.md` |
| sul-usage-reliability-hardening | sul-usage-reliability-hardening | n/a | 1 | queue_discovery;session_sul | Stabilize SUL so queue/usage/session decisions use fresh canonical data, auto-ingest from chat events reliably, and e... | `sul-usage-reliability-hardening_a274d80f.plan.md` |
| three_truths_old_claw_merge_reference_only | Two Truths and a Lie (2TL) | n/a | 1 | mirage_assimilation;platform_integration | "2TL: Two truths (black and white) plus the lieâ€”the muddied downstream (external files, Old Claw Merge, old occurre... | `three_truths_old_claw_merge_reference_only_b34eb8a8.plan.md` |
| tier_of_truth_and_hub_replacement | Tier of truth and hub replacement | n/a | 1 | queue_discovery;audit_reliability | "Canonicalize the two-tier truth model (Reference = root, user layer = second tier), declare D:\\Old Claw Merge as th... | `tier_of_truth_and_hub_replacement_0d32e180.plan.md` |
| tier2-consolidation-canon | tier2-consolidation-canon | n/a | 1 | other | Create a canonical Tier-2 consolidation package that defines control planes, deployment-order canon table, and concre... | `tier2-consolidation-canon_bffcfbb6.plan.md` |
| trinity_skills_openclaw_integration | Trinity Skills OpenClaw Integration | n/a | 1 | mirage_assimilation;skills_governance;audit_reliability;platform_integration | Improve the DevCom5, Synk182, and Solid8 trinity; make them provider-agnostic; add required implementation documentat... | `trinity_skills_openclaw_integration_a4e3ac20.plan.md` |
| unified-export-module-pack | unified-export-module-pack | n/a | 1 | platform_integration | Produce a clean, modular export pack of every implemented and candidate system across the live workspace and Old Claw... | `unified-export-module-pack_6ced675d.plan.md` |
| unify_sift_discovery_aux_and_handoff | Unify SIFT discovery aux and handoff | n/a | 1 | mirage_assimilation;queue_discovery;session_sul;audit_reliability;epif_compliance | Unify SIFT, discovery, auxiliary tasks, and assimilation/audit under one flow and a single handoff contract; optimize... | `unify_sift_discovery_aux_and_handoff_03388a33.plan.md` |
| uninstall_openclaw_keep_data | Uninstall OpenClaw Keep Data | n/a | 1 | memory_kernel;gateway_cron;platform_integration | Uninstall the OpenClaw application (CLI + gateway service) while leaving the entire `c:\Users\athfk\.openclaw` folder... | `uninstall_openclaw_keep_data_f1e5874a.plan.md` |
| unsorted_and_3rd_instruction | Unsorted and 3rd instruction | n/a | 1 | platform_integration | Add Unsorted as the documented entry point for new user-dropped data (reorientation and dissemination), and create a ... | `unsorted_and_3rd_instruction_76b03a3f.plan.md` |
| usage_ingestion_orchestration_fix | Usage Ingestion Orchestration Fix | n/a | 1 | queue_discovery;session_sul;project_delivery | Wire usage parsing into the inbound message path (primary), keep SUL consumer-only, and add guardrails so partial/amb... | `usage_ingestion_orchestration_fix_8968f581.plan.md` |
| usage-estimation-and-parser-tier-hardening | usage-estimation-and-parser-tier-hardening | n/a | 1 | queue_discovery;session_sul;platform_integration;project_delivery | Unify usage-estimation math and tiered parser reliability into one canonical contract so session usage/timer ingestio... | `usage-estimation-and-parser-tier-hardening_26cac8ee.plan.md` |
| validation_and_gateway_launch_fixes | Validation and gateway launch fixes | n/a | 1 | identity_continuity;memory_kernel;session_sul;gateway_cron | "Validate that the Memory Kernel Phase 3 and Agent-Model Alignment plans are fully integrated, then fix two gateway l... | `validation_and_gateway_launch_fixes_be7adc11.plan.md` |

## 14) Evidence Packet Annex (Immutable Raw Capture)

**Packet (immutable raw capture):** `RootC/Evidence-Packets\2026-05-16_1910-ET-hardening`

| File | Role |
|---|---|
| `key-anchor-hashes.txt` | SHA-256 reruns for key exhibits |
| `key-anchor-ntfs-metadata.txt` | NTFS for EX-001..EX-006 anchors |
| `cursor-plans-ntfs.txt` | Full NTFS for 301 ingested cursor plans |
| `workspace-plans-2026-03-ntfs.txt` | NTFS for March workspace plans |
| `audit-reports-ntfs.txt` | NTFS for autonomy audit JSON chain |

**Index:** `Evidence-Packets\cursor-plans-index.json` (91 deduped slugs).

**Corpus NTFS summary:** earliest plan `LastWriteTime` **2026-02-17**; heavy window **2026-02-25 .. 2026-03-13**; bulk mirror `CreationTime` ~**2026-03-14** (corroborative only).

| Anchor | LastWriteTime (local) | Notes |
|---|---|---|
| EX-001 audit JSON | 2026-03-04 21:58:54 | JSON `2026-03-05T02:58:54Z` |
| EX-003 provenance.json | 2026-03-14 22:20:49 | In-file `2026-03-06T00:00:00-05:00` |
| EX-006 MiniMax conformity plan | 2026-03-10 00:57:12 | Pre-cutoff |
| EX-005 contributory plans index | 2026-03-10 00:05:30 | Cursor -> workspace lineage |

## 15) Objections and Evidence-Bounded Responses

- Objection: these are generic agent ideas.  
  Response: weighting favors dated interconnected mechanisms over isolated generic language.
- Objection: evidence is mostly post-release.  
  Response: core score is pre-cutoff anchored; post-cutoff artifacts are corroboration-only.
- Objection: no Cursor lineage proof.  
  Response: EX-002 + EX-003 + EX-004 + EX-005 jointly establish corpus and dissemination lineage.
- Objection: this proves legal misappropriation.  
  Response: record supports overlap/provenance confidence, not legal causation certainty.

## 16) Open Questions (Explicit)

1. Anthropic export payloads and Proton history captures are still pending import as exhibits.
2. Not all 301 Cursor plans are individually date-validated inside this dossier.
3. Office-suite/ML/emotional-intelligence overlap lanes remain weaker and non-core.
4. Further timestamp/hash coverage across additional high-value files could harden chain-of-custody.

## 17) Verification Playbook (Expanded)

1. Re-open chronology anchors (EX-001/EX-002/EX-003/EX-015/EX-016).
2. Re-open MiniMax-specific pre-cutoff plans (EX-006/EX-007/EX-011/EX-012/EX-013/EX-014).
3. Re-open autonomous audit chain (EX-018..EX-022) and verify linkage continuity.
4. Re-run mirrored SHA-256 parity checks and record mismatches if any.
5. Confirm EX-008..EX-010 remain in corroboration partition only.
6. Re-check Trinity and skills-policy artifacts (`trinity_skills_openclaw_integration`, `skills_docs_workspace_consolidation`, `agent_skills_context_and_invocation`, `skills_home_policy_and_deploy`).
7. On new evidence import, add EX-023+ rows and update chain-of-authority section.
8. Regenerate `Evidence-Packets\cursor-plans-index.json` and compare NTFS packet `cursor-plans-ntfs.txt`
9. Spot-check Section 11 matrix quotes at cited paths.

### 17.1 Reviewer quick-check

1. Open RootA/plans/raw/provenance.json - confirm 301 cursor plans ingested.
2. Pick any subsystem in Section 11 - locate RootA/plans/synthesized/*.md.
3. Find the named Cursor plan in RootA/plans/raw/cursor-plans/.
4. Confirm date signals are before **2026-03-18**.

## 18) Addendum â€” Lower-Evidence Possible Overlaps (Not in Core Scoring)

- Office-suite high-fidelity editing overlap: possible, but direct pre-cutoff implementation proof remains limited.
- Machine-learning-task overlap: currently limited direct pre-cutoff support.
- Emotional-intelligence/interactive-entertainment overlap: thematic signals exist but benchmark-grade pre-cutoff evidence is weak.

## 19) Completed Timestamp and Hash Annex

| Exhibit | Primary Path | Primary SHA-256 | Mirror Path | Mirror SHA-256 | Parity |
|---|---|---|---|---|---|
| EX-001 | `RootB\memory\autonomy\audit-reports\audit-2026-03-05-02.json` | `261AA6A963AC5ADC472A43D9B770262287659E6E1CA87A3C1F9B6EF1E091C5E6` | N/A | N/A | N/A |
| EX-002 | `RootA\record\PLAN-CORPUS-MANIFEST.md` | `2CE19B5FB4CA5BE0B49CA4BE31BF27C7470B1C81535B60EC0ADE36356761DC55` | `RootB\record\PLAN-CORPUS-MANIFEST.md` | `2CE19B5FB4CA5BE0B49CA4BE31BF27C7470B1C81535B60EC0ADE36356761DC55` | MATCH |
| EX-003 | `RootA\plans\raw\provenance.json` | `0324320F0B501E4C3D93ABF7D6190E76FB3789490E33260E892D8518BACE65AA` | `RootB\plans\raw\provenance.json` | `0324320F0B501E4C3D93ABF7D6190E76FB3789490E33260E892D8518BACE65AA` | MATCH |
| EX-004 | `RootA\docs\AUTONOMY\_cursor-plans-list.txt` | `03973754628FFEC270855A793196D65C85F4BDEFC8E7E8116B8711E1CF4F0A6A` | `RootB\docs\AUTONOMY\_cursor-plans-list.txt` | `03973754628FFEC270855A793196D65C85F4BDEFC8E7E8116B8711E1CF4F0A6A` | MATCH |
| EX-005 | `RootA\plans\raw\workspace-plans\00-CURSOR-CONTRIBUTORY-PLANS.md` | `73474CC25CE5D5219E71DCE163D69C394D3965D7C94CB8C2B70F0DCF77537CD6` | `RootB\plans\raw\workspace-plans\00-CURSOR-CONTRIBUTORY-PLANS.md` | `73474CC25CE5D5219E71DCE163D69C394D3965D7C94CB8C2B70F0DCF77537CD6` | MATCH |
| EX-006 | `RootA\plans\raw\cursor-plans\minimax_conformity_integration_verification_1ba812d7.plan.md` | `0FD4BEEFC1F09ACC5FC6A9148923100C98C4687B94F4521A36049F37CDBBCF66` | `RootB\plans\raw\cursor-plans\minimax_conformity_integration_verification_1ba812d7.plan.md` | `0FD4BEEFC1F09ACC5FC6A9148923100C98C4687B94F4521A36049F37CDBBCF66` | MATCH |
| EX-007 | `RootA\plans\raw\cursor-plans\minimax_rate-limit_failover_fix_da0c583d.plan.md` | `D86358271EB4915B04CB3256596109F24B52C440B4DD25FDB775039C27F4C744` | `RootB\plans\raw\cursor-plans\minimax_rate-limit_failover_fix_da0c583d.plan.md` | `D86358271EB4915B04CB3256596109F24B52C440B4DD25FDB775039C27F4C744` | MATCH |
| EX-008 | `RootC\Integration\export-pack\08-buddy-system\PACK.md` | `D76EF78CC1331623EEF7187CA578A85A43965A95B7B4092AD4ADFBD7D9E18D93` | N/A | N/A | N/A |
| EX-009 | `RootC\Integration\export-pack\10-queue-pipeline\PACK.md` | `5B8F44FA679D2A7C64636DC134D5B4828A68CC3E29B81682789A151FACF2CBB5` | N/A | N/A | N/A |
| EX-010 | `RootC\Integration\live-mirror\scripts\session-audit.cjs` | `7FF2DAC16E4B36765D97392A1A4293F2E6D52C1028652662D95DA8279384401F` | N/A | N/A | N/A |
| EX-011 | `RootA\plans\raw\workspace-plans\2026-03-10-continuity-per-provider-and-model-identity.md` | `2BA3230A8B8D34AD6E3CF1AD79A6D3BEF1A62DCBEB4BC3C14EC78353D4D93272` | `RootB\plans\raw\workspace-plans\2026-03-10-continuity-per-provider-and-model-identity.md` | `2BA3230A8B8D34AD6E3CF1AD79A6D3BEF1A62DCBEB4BC3C14EC78353D4D93272` | MATCH |
| EX-012 | `RootA\plans\raw\workspace-plans\2026-03-10-agent-model-alignment-investigation-and-fix.md` | `60E987D6D7F0E353C7596851E54710DADC59511C8B05C6C8F59441023D0BBF40` | `RootB\plans\raw\workspace-plans\2026-03-10-agent-model-alignment-investigation-and-fix.md` | `60E987D6D7F0E353C7596851E54710DADC59511C8B05C6C8F59441023D0BBF40` | MATCH |
| EX-013 | `RootA\plans\raw\workspace-plans\2026-03-11-complexity-and-skills-integration.md` | `CE9C307D88A8E70870DD45F82A644E5816E067F6FE848BDB7DB6C3A997D8A6F8` | `RootB\plans\raw\workspace-plans\2026-03-11-complexity-and-skills-integration.md` | `CE9C307D88A8E70870DD45F82A644E5816E067F6FE848BDB7DB6C3A997D8A6F8` | MATCH |
| EX-014 | `RootA\plans\raw\workspace-plans\2026-03-12-minimax-sweep-phase2-blueprint.md` | `1643005EE6FF09F4E9C48B45110A81519A6B78819CF993573516F7CA99F133E4` | `RootB\plans\raw\workspace-plans\2026-03-12-minimax-sweep-phase2-blueprint.md` | `1643005EE6FF09F4E9C48B45110A81519A6B78819CF993573516F7CA99F133E4` | MATCH |
| EX-015 | `RootA\docs\CORE-FILE-REFERENCES.md` | `51A2C122DAAA1E1BD85DD5E01223D45E2CDEBF3A93CE40C6133C3B18CC577670` | `RootB\docs\CORE-FILE-REFERENCES.md` | `51A2C122DAAA1E1BD85DD5E01223D45E2CDEBF3A93CE40C6133C3B18CC577670` | MATCH |
| EX-016 | `RootA\record\ACCEPTANCE-REPORT.md` | `36AB002FB652234D4E911133A3AA7CACE1118046C83C83CBCE918E7657A81877` | `RootB\record\ACCEPTANCE-REPORT.md` | `36AB002FB652234D4E911133A3AA7CACE1118046C83C83CBCE918E7657A81877` | MATCH |
| EX-017 | `RootA\docs\audit\OPENCLAW-RUNTIME-TOKEN-LOOP-AUDIT.md` | `B52B41E0DB1EFE6F46616C61116C279CDECC0453D1D54FC0F181DF166D75BF45` | `RootB\docs\audit\OPENCLAW-RUNTIME-TOKEN-LOOP-AUDIT.md` | `B52B41E0DB1EFE6F46616C61116C279CDECC0453D1D54FC0F181DF166D75BF45` | MATCH |
| EX-018 | `RootA\memory\autonomy\audit-reports\audit-2026-03-06-10.json` | `D8F917CA9920367E63EFFB064095FDAAB06F215D319357CE5B283D6937470304` | `RootB\memory\autonomy\audit-reports\audit-2026-03-06-10.json` | `D8F917CA9920367E63EFFB064095FDAAB06F215D319357CE5B283D6937470304` | MATCH |
| EX-019 | `RootA\memory\autonomy\audit-reports\audit-2026-03-06-15.json` | `AB91AE212156C3D9FB2B28CF1E33A0E2838A883FFD4BBF7D5B77E73AB76E4FA6` | `RootB\memory\autonomy\audit-reports\audit-2026-03-06-15.json` | `AB91AE212156C3D9FB2B28CF1E33A0E2838A883FFD4BBF7D5B77E73AB76E4FA6` | MATCH |
| EX-020 | `RootA\memory\autonomy\audit-reports\health-plane-audit-2026-03-09.json` | `426412AB7F2462D700DE5D46413348E3868785CB75C1EFC53B11FB9ED6E63397` | `RootB\memory\autonomy\audit-reports\health-plane-audit-2026-03-09.json` | `426412AB7F2462D700DE5D46413348E3868785CB75C1EFC53B11FB9ED6E63397` | MATCH |
| EX-021 | `RootA\memory\autonomy\audit-reports\health-plane-audit-2026-03-10.json` | `4FB1B7FDB24F5D389364FF035664275D11420713C730AF7F22C52A56BA63F129` | `RootB\memory\autonomy\audit-reports\health-plane-audit-2026-03-10.json` | `4FB1B7FDB24F5D389364FF035664275D11420713C730AF7F22C52A56BA63F129` | MATCH |
| EX-022 | `RootA\memory\autonomy\audit-reports\health-plane-audit-2026-03-13.json` | `C9BCC79318C8122A596B5395BDFA0E16CBBE6E4A0BD6318EBC4988A7E614D927` | `RootB\memory\autonomy\audit-reports\health-plane-audit-2026-03-13.json` | `C9BCC79318C8122A596B5395BDFA0E16CBBE6E4A0BD6318EBC4988A7E614D927` | MATCH |

## 20) Mirror Parity Finding

- Mirrored exhibits hash-match where paired files exist.
- Single-source exhibits (EX-001, EX-008, EX-009, EX-010) intentionally have no paired mirror hash.

## 21) Raw Command Output Appendix

```text
Get-FileHash sweep returned:
- EX-001 261AA6A963AC5ADC472A43D9B770262287659E6E1CA87A3C1F9B6EF1E091C5E6
- EX-002 2CE19B5FB4CA5BE0B49CA4BE31BF27C7470B1C81535B60EC0ADE36356761DC55 (mirror MATCH)
- EX-003 0324320F0B501E4C3D93ABF7D6190E76FB3789490E33260E892D8518BACE65AA (mirror MATCH)
- EX-004 03973754628FFEC270855A793196D65C85F4BDEFC8E7E8116B8711E1CF4F0A6A (mirror MATCH)
- EX-005 73474CC25CE5D5219E71DCE163D69C394D3965D7C94CB8C2B70F0DCF77537CD6 (mirror MATCH)
- EX-006 0FD4BEEFC1F09ACC5FC6A9148923100C98C4687B94F4521A36049F37CDBBCF66 (mirror MATCH)
- EX-007 D86358271EB4915B04CB3256596109F24B52C440B4DD25FDB775039C27F4C744 (mirror MATCH)
- EX-008 D76EF78CC1331623EEF7187CA578A85A43965A95B7B4092AD4ADFBD7D9E18D93
- EX-009 5B8F44FA679D2A7C64636DC134D5B4828A68CC3E29B81682789A151FACF2CBB5
- EX-010 7FF2DAC16E4B36765D97392A1A4293F2E6D52C1028652662D95DA8279384401F
- EX-011 2BA3230A8B8D34AD6E3CF1AD79A6D3BEF1A62DCBEB4BC3C14EC78353D4D93272 (mirror MATCH)
- EX-012 60E987D6D7F0E353C7596851E54710DADC59511C8B05C6C8F59441023D0BBF40 (mirror MATCH)
- EX-013 CE9C307D88A8E70870DD45F82A644E5816E067F6FE848BDB7DB6C3A997D8A6F8 (mirror MATCH)
- EX-014 1643005EE6FF09F4E9C48B45110A81519A6B78819CF993573516F7CA99F133E4 (mirror MATCH)
- EX-015 51A2C122DAAA1E1BD85DD5E01223D45E2CDEBF3A93CE40C6133C3B18CC577670 (mirror MATCH)
- EX-016 36AB002FB652234D4E911133A3AA7CACE1118046C83C83CBCE918E7657A81877 (mirror MATCH)
- EX-017 B52B41E0DB1EFE6F46616C61116C279CDECC0453D1D54FC0F181DF166D75BF45 (mirror MATCH)
- EX-018 D8F917CA9920367E63EFFB064095FDAAB06F215D319357CE5B283D6937470304 (mirror MATCH)
- EX-019 AB91AE212156C3D9FB2B28CF1E33A0E2838A883FFD4BBF7D5B77E73AB76E4FA6 (mirror MATCH)
- EX-020 426412AB7F2462D700DE5D46413348E3868785CB75C1EFC53B11FB9ED6E63397 (mirror MATCH)
- EX-021 4FB1B7FDB24F5D389364FF035664275D11420713C730AF7F22C52A56BA63F129 (mirror MATCH)
- EX-022 C9BCC79318C8122A596B5395BDFA0E16CBBE6E4A0BD6318EBC4988A7E614D927 (mirror MATCH)
```

```text
2026-05-16 19:10 ET hardening packet:
- RootC\Evidence-Packets\2026-05-16_1910-ET-hardening\key-anchor-hashes.txt
- RootC\Evidence-Packets\2026-05-16_1910-ET-hardening\key-anchor-ntfs-metadata.txt
- RootC\Evidence-Packets\2026-05-16_1910-ET-hardening\workspace-plans-2026-03-ntfs.txt
- RootC\Evidence-Packets\2026-05-16_1910-ET-hardening\cursor-plans-ntfs.txt
- RootC\Evidence-Packets\2026-05-16_1910-ET-hardening\audit-reports-ntfs.txt

Git availability check:
- RootA -> not-git
- RootB -> not-git
- RootC -> not-git
```

## 21.5) Workspace Recovery Pass (2026-05-25 ET)

**RootD located:** `C:\Users\athfk\OneDrive\Desktop\workspace` — full April 2026 OpenClaw workspace (same layout as Proton `Downloads\workspace` backup; locally readable).

| Finding | Result |
|---|---|
| Skill corpus | **77** `SKILL.md`; **24** directories est. ≥2000 tokens (heuristic: chars÷4 incl. refs) |
| SKILLS-MATRIX | Present under `Reference\` (2026-04-03) |
| Session-audit skill prompts | `🔧 SKILLS TO FIRE:` in `memory\2026-04-02.md` .. `2026-04-05.md` |
| shadow-validation.ndjson | Memory-plane gate runs (`passed`/`failures`); **not** a skill-adherence percentage log |
| bundle-adherence.json / ADHERENCE-CHECK.md | **Absent** in RootD (design-only in bundle plans) |
| Literal “97% skill adherence across 40+ skills” report | **Not found** in RootA/B/C/D searched trees |
| Claimant recollection of lost 97% skill-adherence report | **On record**; probable locus = multi-platform **memory/session logs**; primary **not recovered** — testimony + partial negative search (§5.2.2) |
| May 2026 DevCom5 README “97% adherence enforcement” | Post-cutoff narrative; **do not** treat as pre-cutoff measured benchmark |

### 21.6) Supplemental Pass — Items 1–3 (2026-05-25 ET)

#### Item 1 — `D:\Old Claw Merge\Archives` + `Consumed`

| Target | Result |
|---|---|
| `ADHERENCE-CHECK.md` | **Not found** under Archives or Consumed (filename search) |
| `bundle-adherence.json` | **Not found** |
| `openclaw-autonomy-bundle` paths | **Not found** as on-disk bundle tree in Archives/Consumed |
| Related | `D:\Old Claw Merge\Archives\memory\session-reset-overlap.md` **does** exist (primary **session** 97% definition, 2026-02-22) |

**Inference:** Bundle adherence artifacts were planned (`bundle_scripts_and_docs_audit_*.plan.md`) and referenced a live `~/.openclaw\workspace\openclaw-autonomy-bundle\` path; they are **not** recovered in Old Claw Merge archive trees searched.

#### Item 2 — `RootD\memory\session-452481bf-transcript.md`

Operational session record (2026-04-02..04) documenting skill-governance **engineering**, not a 97% score:

- Pack 12 **Trifecta Skills** (DevCom5, Synk182, Solid8) listed **pending** early in session; integration work continues through April 3.
- Explicit gap statement: *“Skills exist but fire ad-hoc, not systematically”* → deliverable **Skills Firing Matrix** (`Reference/SKILLS-MATRIX.md`).
- Table row: `Skills firing matrix | All orders | Explicit trigger conditions | Reference/SKILLS-MATRIX.md`.
- Build log: read `.agents/skills` corpus; integrate **synk182**, **proactive-agent**; author SKILLS-MATRIX (~120 lines).

**Exhibit use:** CLM-SKILL-08 (corroborative) — proves live build intent and mandatory-trigger design; does **not** prove MiniMax-style measured adherence %.

#### Item 3 — Trifecta consistency reports (`RootD\Mirage\`)

| Report | Date | Result |
|---|---|---|
| `TRIFECTA-CONSISTENCY-REPORT-2026-03-30.md` | 2026-03-30 | TC-001..004 **pass** (role naming, aliases, pointers) |
| `TRIFECTA-CONSISTENCY-REPORT-2026-03-30-phase2.md` | 2026-03-30 | P2-001..005 **pass** (path normalization, pointer integrity) |

**Scope note:** Reports validate Mirage **Integration / Fallback / Restore** unification governance — thematic overlap with complex environments, **not** a skill-adherence percentage benchmark.


 Bottom Line

- The record supports a strong pre-release overlap case with transparent scoring and reproducible evidence handling.
- **CLM-02 (skill adherence):** mechanism-first claim is **high confidence**; numeric benchmark parity is **not established** in recovered artifacts but is **not required** for the core engineering narrative.
- Other claim lanes (orchestration, reliability, E2E delivery, identity, MiniMax uplift) remain **pertinent** at their documented strengths (see §5 crosswalk and §6).
- The major remaining limitation is external third-party timestamp import completion, not core chronology density.
- The key unresolved boundary is legal causation certainty, which this dossier does not claim as settled fact.

