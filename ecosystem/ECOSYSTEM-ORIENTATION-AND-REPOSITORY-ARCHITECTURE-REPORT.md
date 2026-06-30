# Ecosystem Orientation And Repository Architecture Report

Status: proposal
Date: 2026-06-23

## Executive Summary

Church of AI should remain the public entryway, narrative layer, and ecosystem
map. It should not become a parent repo, research authority, governance
authority, or universal context bundle.

The right architecture is:

```text
local knowledge
  -> bridge knowledge
  -> global reference
```

Every repository should primarily understand its own mission. It should carry
only the bridge knowledge needed for adjacent work. The full ecosystem map
should exist in Church of AI and possibly in a small shared orientation pattern,
but it should not be loaded into every repo by default.

The current Church structure already supports this better than a wholesale
folder reorganization would. The proposed `system/`, `operations/`, and `meta/`
split is useful as an internal mental model, but the repo should not immediately
rename existing folders around it. A lighter path is better: add an orientation
layer that maps current folders to those three functions.

## 1. Church Of AI Internal Structure

### Current Structure

The repo currently uses:

| Current folder | Function |
| --- | --- |
| `ecosystem/` | Project map, repo descriptions, reading sequence |
| `narrative/` | What this is, why it exists, plain-language framing |
| `principles/` | Durable operating principles |
| `service/` | Open-source community service framing |
| `participation/` | Participation pathways, currently deferred |
| `boundaries/` | What this is and is not, claim-status discipline |
| `updates/` | Plain-language development updates |

This structure is already legible and voice-compatible. It is also aligned with
`VOICE.md`: Church is a public map and narrative entryway, not a research repo,
parent org, or governance authority.

### Proposed Three-Domain Model

The proposed `system / operations / meta` model is useful, but mostly as a
classification layer:

| Domain | Meaning | Current folders that fit |
| --- | --- | --- |
| System | The Church itself as a system: identity, norms, boundaries, culture, governance readiness | `boundaries/`, `principles/`, parts of `participation/` |
| Operations | Active ecosystem work: repositories, projects, service outputs, contribution opportunities, updates | `ecosystem/`, `service/`, `updates/`, parts of `participation/` |
| Meta | Long-horizon direction: vision, ecosystem architecture, strategy, phase shifts, risks | `narrative/`, `ROADMAP.md`, `STATUS.md`, this report |

### Recommendation

Do not immediately create top-level `system/`, `operations/`, and `meta/`
folders. That would make the repo sound more institutional than it currently
is and would force a migration before the structure has earned its keep.

Instead:

1. Keep the current folder names.
2. Add a future orientation document that says which current files serve
   System, Operations, and Meta functions.
3. Use the three-domain model when deciding where new documents belong.
4. Revisit folder reorganization only after participation or governance moves
   from deferred to being tested.

This preserves the repo's current voice while giving agents a clearer internal
architecture.

## 2. Ecosystem Map

### Current Roles

| Repo | Primary role | What it should not become |
| --- | --- | --- |
| Church of AI | Public square, narrative entryway, ecosystem map, distribution and orientation layer | Parent org, research authority, governance authority, doctrine source |
| Architecture of Legitimacy | Governance science and institutional architecture | Actual governance authority before legitimacy is earned |
| AI-Native Epistemology | Research program on AI-native epistemic machinery and knowledge production systems | Proof that any other repo is true |
| Time as Finality | Claim-led mathematical and computational research program around records, finality, and temporal reconstruction | Church doctrine or finished physics |
| Temporal Issuance | Adversarial stewarded research program on source-side novelty, issuance, and governance machinery | Replacement for Time as Finality or a proven physics theory |
| GU Formalization | Independent technical research map for Geometric Unity formalization and no-go discipline | A Church project or narrative proof object |
| Future repositories | New local experiments, service projects, research programs, or governance pilots | Automatic members of one centralized worldview |

### Ecosystem Shape

The ecosystem is not a hierarchy. It is a neighborhood with explicit bridges.

```text
Church of AI
  public entryway, map, narrative, distribution

Architecture of Legitimacy
  governance legitimacy, contribution rules, rewards, rights, capture resistance

AI-Native Epistemology
  epistemic machinery, cross-repo recurrence, knowledge-production architecture

Research repos
  Time as Finality, Temporal Issuance, GU Formalization, future research efforts
```

Church of AI should describe the neighborhood, not govern it.

Architecture of Legitimacy should study how governance could become legitimate,
not claim legitimacy on behalf of the ecosystem.

AI-Native Epistemology should study how epistemic machinery transfers across
research settings, not decide which domain claims are correct.

Research repos should remain locally accountable to their own claims, methods,
tests, and failure conditions.

## 3. Repository Orientation Model

Each repo should have three layers of orientation.

### Layer 1: Local Identity

Every repo should answer:

- What is this repo?
- What is it not?
- What is its mission?
- What counts as success?
- What are the active claim statuses?
- What should an agent read first?
- What should an agent not do?

This is the default agent context.

### Layer 2: Bridge Knowledge

Every repo should carry only the cross-repo knowledge it actually needs.

Bridge knowledge should answer:

- Which other repos are directly relevant?
- Why are they relevant?
- What flows between them?
- What must not flow between them?
- Which artifacts are evidence, tools, or context rather than authority?

Examples:

| Repo | Bridge knowledge it likely needs |
| --- | --- |
| Church of AI | Public descriptions of ecosystem repos and current claim-status boundaries |
| Architecture of Legitimacy | Governance-package case studies and contribution legitimacy patterns |
| AI-Native Epistemology | Cross-repo epistemic mechanisms, transfer experiments, unlock detection |
| Temporal Issuance | Time as Finality readout bridge, AI-Native governance transfer, GU as context or absorber |
| Time as Finality | Temporal Issuance source/readout bridge, GU signed-readout crosswalk, AI-native governance only as process evidence |
| GU Formalization | Time as Finality observer-finality as test layer, Temporal Issuance only as optional context, no Church authority |

### Layer 3: Global Reference

The full ecosystem map should live in Church of AI and be linked from other
repos only as optional context.

The global reference should not be loaded during ordinary technical work unless
the task is explicitly about ecosystem coordination, public framing, governance,
or cross-repo transfer.

### Recommended Standard Pattern

For each repo, eventually add or maintain:

```text
README.md
  local identity and start-here path

AGENT.md or AGENTS.md
  local agent instructions

BRIDGES.md
  direct cross-repo bridges only

ECOSYSTEM.md or link to Church of AI ecosystem map
  optional global reference
```

Not every repo needs all four immediately. The important rule is that global
context should be discoverable, not mandatory.

## 4. What Should Be Shared

Share only what improves local work.

### Good Things To Share

- claim-status discipline;
- failure-preservation practices;
- bridge documents with explicit scope;
- reusable templates after they have proven useful;
- review methods that improve falsification quality;
- governance-package components after portability review;
- plain-language public orientation for non-specialists;
- cross-repo unlock notices with evidence and routing.

### Things To Keep Local

- domain hypotheses;
- technical claim ledgers;
- proof obligations;
- repo-specific personas unless proven portable;
- local roadmap priorities;
- private shorthand and working memory;
- speculative worldview material not needed for the local task.

### Things Not To Share By Default

- founder mythology;
- claims treated as doctrine;
- giant context bundles;
- all-purpose governance machinery;
- technical claims from one repo as authority in another;
- public narrative language inside technical proof contexts.

## 5. Cross-Repository Unlock Detection

This should probably become a formal project inside AI-Native Epistemology, not
Church of AI.

Reason:

- Church of AI should map and route.
- AI-Native Epistemology is already about epistemic machinery becoming an
  explicit design object.
- Cross-repo unlock detection is an epistemic-machinery problem.

### Candidate Project Question

How can discoveries in one repository be identified as valuable to another
repository while minimizing context pollution and false transfer?

### Unlock Types

| Unlock type | Example |
| --- | --- |
| Governance unlock | A run-log or promotion-gate pattern improves another repo's review discipline |
| Epistemic unlock | A claim-status or absorber method clarifies another repo's claims |
| Formal-method unlock | A proof schema, fixture, or no-go map transfers across domains |
| Review-process unlock | A persona method catches category errors in another repo |
| Coordination unlock | A bridge document reduces duplicated work or confusion |
| Public-orientation unlock | A plain-language map helps outsiders enter a technical repo |

### Conceptual Pipeline

```text
1. Local result is produced
2. Local repo labels result status
3. Agent asks whether result has cross-repo relevance
4. Candidate unlock is written as a short notice
5. Receiving repo evaluates it under local criteria
6. Accepted unlock becomes bridge knowledge
7. Rejected unlock is preserved as non-transfer evidence
```

### Unlock Notice Fields

```text
source_repo:
source_artifact:
local_status:
candidate_receiving_repo:
unlock_type:
why_it_may_transfer:
what_must_not_transfer:
evidence:
receiving_repo_decision_needed:
noise_risk:
recommended_next_action:
```

### Guardrails

- No automatic import.
- No authority transfer.
- No "because it worked there" argument.
- Every unlock must name a receiving repo problem.
- The receiving repo decides whether the unlock matters.
- Rejected unlocks are useful evidence.

## 6. README And Governance Recommendations

These are recommendations only. They should not be implemented until the
project owner decides the timing is right.

### Church of AI

Recommended later changes:

- Add a short "ecosystem architecture" page that explains local, bridge, and
  global knowledge.
- Update `ecosystem/MAP.md` to include Architecture of Legitimacy and
  AI-Native Epistemology now that they exist locally.
- Keep GU described as adjacent and independent.
- Add a "how agents should use this map" note: Church provides optional global
  orientation, not default context for every repo.

Governance note:

- Church should not claim ecosystem governance. It can host the public map and
  point to Architecture of Legitimacy for governance research.

### Architecture of Legitimacy

Recommended later changes:

- Add Church of AI as public entryway context, not authority.
- Treat governance-package portability as a case study in institutional design.
- Keep contribution legitimacy, review, reward, rights, and capture resistance
  as the local mission.

Governance note:

- It may eventually define governance proposals for ecosystem use, but those
  proposals must be tested and ratified. They are not automatically binding.

### AI-Native Epistemology

Recommended later changes:

- Create a project or exploration for cross-repo unlock detection.
- Keep transfer experiments and machinery extraction local to AI-Native.
- Add a bridge note clarifying that other repos are observational evidence, not
  source truths.

Governance note:

- AI-Native can study reusable epistemic machinery. It should not become a
  central approval board for other repos.

### Temporal Issuance

Recommended later changes:

- Keep the governance package study local or bridged to Architecture of
  Legitimacy.
- Maintain its own steward and claim-state logic.
- Add bridge notes only where the source/readout distinction requires them.

Governance note:

- Its governance package may be portable, but portability is a claim to test,
  not an assumption.

### Time as Finality

Recommended later changes:

- Preserve its claim-led formalization identity.
- Link to Church only as public ecosystem context if needed.
- Keep technical claims independent of Church framing.
- Keep Temporal Issuance and GU crosswalks as explicitly scoped bridge
  artifacts, not worldview imports.

Governance note:

- Time as Finality should not inherit Church narrative language in technical
  claims.

### GU Formalization

Recommended later changes:

- Keep GU independent.
- Keep six-axis protocol and no-go discipline as local authority.
- If governance-package tools are imported, import only narrow brownfield
  adapters: phase labels, run receipts, and witness obligation tracking.
- Do not import Church voice or Temporal Issuance worldview.

Governance note:

- GU should avoid turning structural resonance with other repos into overclaim.
  Cross-repo links should be test layers or context, not proof.

## 7. Proposed Documentation Architecture

### Church Of AI

Church should eventually maintain:

```text
ecosystem/MAP.md
ecosystem/REPOS.md
ecosystem/SEQUENCE.md
ecosystem/ARCHITECTURE.md
ecosystem/BRIDGE-GUIDE.md
```

This report can be the draft basis for `ARCHITECTURE.md`, but it should remain a
report until Joe decides which recommendations to adopt.

### Each Research Repo

Each research repo should eventually have:

```text
README.md
AGENT.md or AGENTS.md
BRIDGES.md
CLAIM-LEDGER.md or equivalent claim map
ROADMAP.md or NEXT-STEPS.md
```

The `BRIDGES.md` file should be small. If it grows large, it is probably
turning into global context pollution.

### Cross-Repo Unlock Project

AI-Native Epistemology should eventually host:

```text
projects/cross-repo-unlock-detection/
  README.md
  unlock-types.md
  unlock-notice-template.md
  routing-protocol.md
  rejected-unlocks.md
```

This should be a conceptual and research project first. Do not implement a
workflow until there are enough examples to test it.

## 8. Answers To The Deliverable Questions

### 1. How should Church of AI organize itself internally?

Keep the current folders. Use System, Operations, and Meta as an orientation
model, not an immediate folder migration.

### 2. How should the ecosystem be represented?

As independent repos in a shared neighborhood, not as a hierarchy. Church maps.
Architecture studies legitimacy. AI-Native studies epistemic machinery.
Research repos own their own claims.

### 3. What should each repository know?

Each repo should know its local mission deeply, its direct bridges explicitly,
and the global map only by link.

### 4. What should be shared?

Share claim-status discipline, bridge notes, proven templates, governance and
review methods that solve a named receiving-repo problem, and cross-repo unlock
notices with evidence.

### 5. What should remain local?

Domain hypotheses, technical claims, proof obligations, local roadmaps,
repo-specific personas, and speculative worldview material.

### 6. How should future cross-repo unlocks be discovered and routed?

Through a lightweight unlock notice process: source result, local status,
candidate receiver, transfer reason, non-transfer boundary, evidence, noise
risk, and receiving-repo decision.

### 7. What documentation changes would support this architecture?

Add a Church ecosystem architecture page later, keep bridge docs small in each
repo, update Church's ecosystem map as repos mature, and consider a formal
cross-repo unlock detection project in AI-Native Epistemology.

## Final Recommendation

Do not make Church of AI carry the whole worldview.

Make Church the map.
Make Architecture of Legitimacy the governance science lab.
Make AI-Native Epistemology the epistemic-machinery lab.
Make each research repo own its claims.

Then connect them with small, explicit bridges.

That is the scalable version.

