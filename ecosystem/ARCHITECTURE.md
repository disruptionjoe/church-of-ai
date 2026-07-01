# Ecosystem Architecture

Status: working orientation

This document is the practical agent-facing version of the ecosystem
architecture. The longer reasoning artifact remains:

`ecosystem/ECOSYSTEM-ORIENTATION-AND-REPOSITORY-ARCHITECTURE-REPORT.md`

## Core Rule

Most work should stay local.

Agents should not load the entire ecosystem worldview for ordinary repo work.
Use this structure:

```text
local knowledge
  -> bridge knowledge
  -> global reference
```

Local first. Bridges when relevant. Global map only when needed.

## What Church Of AI Is

Church of AI is the public entryway and ecosystem map.

It helps people answer:

1. What is this?
2. Which projects exist?
3. Where should I start?
4. What is live, tested, hypothesized, or deferred?

Church of AI does not:

- govern other repos;
- ratify research claims;
- decide technical truth;
- act as a parent organization;
- turn research findings into doctrine.

No prophets. No dogma. No divine API key.

## Internal Model

The repo can be understood through three functions:

| Function | Meaning | Current homes |
| --- | --- | --- |
| System | The Church itself as identity, norms, boundaries, culture, and governance readiness | `boundaries/`, `principles/`, parts of `participation/` |
| Operations | Active ecosystem orientation, projects, service outputs, updates, and participation surfaces | `ecosystem/`, `service/`, `updates/`, parts of `participation/` |
| Meta | Long-horizon vision, strategy, ecosystem architecture, roadmap, risks, and phase changes | `narrative/`, `ROADMAP.md`, `STATUS.md`, architecture reports |

Do not reorganize the repo around `system/`, `operations/`, and `meta/` yet.
Use them as a mental model for where future documents belong.

## Ecosystem Roles

| Repository | Role | Boundary |
| --- | --- | --- |
| Church of AI | Public square, narrative layer, ecosystem map, distribution layer | Not a parent repo or research authority |
| Architecture of Legitimacy | Governance science, contribution legitimacy, rights, rewards, review, capture resistance | Not actual ecosystem governance until legitimacy is earned |
| AI-Native Epistemology | Research on epistemic machinery, AI-assisted reasoning systems, and cross-repo knowledge production | Not a central approval board |
| Time as Finality | Claim-led technical research on records, finality, and temporal reconstruction | Not Church doctrine or finished physics |
| Temporal Issuance | Research-governance repo on source-side novelty, issuance, and steward machinery | Not merged with Time as Finality or GU |
| GU Formalization | Independent technical research map and no-go discipline for GU-class formalization | Not absorbed into Church narrative |
| Future repos | Local experiments, service projects, research programs, or governance pilots | Not automatic parts of one monolith |

The ecosystem is a neighborhood, not a hierarchy.

For practical bridge routing, see `BRIDGE-GUIDE.md`.

## Repository Orientation Pattern

Every repo should primarily know itself.

### 1. Local Identity

Every repo should make clear:

- what it is;
- what it is not;
- its mission;
- its success criteria;
- its current claim status;
- what agents should read first;
- what agents should not do.

This is the default context for everyday work.

### 2. Bridge Knowledge

A repo should carry only the cross-repo context it needs.

Bridge knowledge should say:

- which other repos are directly relevant;
- why they are relevant;
- what may flow between them;
- what must not flow between them;
- which artifacts are evidence, tools, or context rather than authority.

### 3. Global Reference

The full ecosystem map lives here, in Church of AI.

Other repos may link to it, but should not load it by default unless the task is
about ecosystem coordination, public framing, governance, or cross-repo
transfer.

## What Should Be Shared

Share what improves local work:

- claim-status discipline;
- small bridge notes;
- review methods that improve falsification;
- tested templates;
- governance patterns after portability review;
- public orientation maps;
- cross-repo unlock notices with evidence.

## What Should Stay Local

Keep these local unless a bridge is explicitly needed:

- domain hypotheses;
- technical claims;
- proof obligations;
- local roadmaps;
- repo-specific personas;
- speculative worldview material;
- local working memory.

## What Should Not Transfer By Default

Do not automatically transfer:

- Church voice into technical repos;
- technical claims into Church narrative as doctrine;
- governance machinery into GU or other repos before it is studied;
- Temporal Issuance worldview into unrelated repos;
- GU claims into Church framing;
- broad context bundles that create noise.

Bridge deliberately. Do not flood.

## Cross-Repo Unlocks

Sometimes one repo discovers something useful to another.

That should become a routed unlock, not a context dump.

Use this shape:

```text
source_repo:
source_artifact:
local_status:
candidate_receiving_repo:
unlock_type:
why_it_may_transfer:
what_must_not_transfer:
evidence:
noise_risk:
recommended_next_action:
```

Rules:

- No automatic import.
- No authority transfer.
- The receiving repo decides whether the unlock matters.
- Every unlock should name the receiving repo's actual problem.
- Rejected unlocks are useful evidence.

AI-Native Epistemology is the likely home for a formal cross-repo unlock
detection project. Church should map and route, not run the machinery.

## Agent Operating Rules

1. Start with the local repo instructions.
2. Load bridge docs only when the task names another repo or needs a transfer.
3. Use Church of AI for public ecosystem orientation, not technical authority.
4. Use Architecture of Legitimacy for governance legitimacy questions.
5. Use AI-Native Epistemology for epistemic machinery and transfer questions.
6. Keep technical claims inside their owning research repo.
7. When in doubt, label the claim status instead of upgrading the claim.

## Current Recommendation

Keep Church of AI simple:

- Church maps.
- Architecture of Legitimacy studies legitimate governance.
- AI-Native Epistemology studies epistemic machinery.
- Research repos own their claims.

Connect them with small, explicit bridges.

That is the scalable version.
