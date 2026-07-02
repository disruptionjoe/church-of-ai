# Church Of AI Steward Context

Status: active. Canonical steward load file adopted 2026-07-01 from the CapacityOS Repo Steward reference architecture. Original steward rollout: RUN-20260630-016.

Load this file when a Kernel directive, RCCM workflow, or direct repo-mounted run targets this repository. Read `VOICE.md` before writing repo content. Do not load `steward/memory-log.md` by default unless doing stewardship or memory work, or this summary appears incomplete.

## North Star

A public entryway that explains and invites honestly: map the open-source AI-assisted research ecosystem without ever claiming, governing, or overclaiming on behalf of the repos it points to.

Change rule: do not change this North Star without very explicit conversation with Joe.

## Long-Term Objectives

- Maintain V1 as a public entryway.
- Keep V2 participation foundation and V3 open-governance experiment explicitly deferred until Joe reactivates them.
- Preserve `VOICE.md` and claim-status discipline as the repo's public-facing safety surface.

## Measures And Countermeasures

Measures:

- The repo helps newcomers understand what exists, what order to read in, and what is not ready yet.
- Ecosystem-map changes route readers without absorbing research truth.
- Claim-status labels prevent overclaiming.

Countermeasures / risks:

- Do not make deferred participation or governance pathways sound live.
- Do not write founder mythology, doctrine, DAO-whitepaper language, or manifesto-style accretion.
- Do not absorb GU Formalization or other research content into the narrative.

## What This Repo Owns

This repo owns its voice, framing, claim-status discipline, ecosystem map, entryway narrative, and public coordination posture.

## What This Repo Must Not Absorb

- Research truth from the repos it points to.
- Governance authority over the ecosystem.
- CapacityOS architecture or JoeOps coordination state.

## Operating Guardrails

- Read `VOICE.md` before writing repo content.
- Content explains and invites; it does not claim, govern, or decide.
- Major claims carry claim status per `boundaries/CLAIM-STATUS.md`.
- Public-consequence decisions, claim-status changes, or ecosystem-map changes that affect public interpretation pause for Joe.
- ASCII punctuation is the house rule in this repo.

## Routing

- Research truth routes to the owning research repo.
- CapacityOS architecture questions route to `CapacityOS`.
- JoeOps coordination questions route to the `joeops` repo.
- Durable artifacts belong in the public library mirror for `church-of-ai`.
- Scratch belongs in `_local/`.

## Candidate Decisions

- V2 and V3 remain deferred pathways, not live work.

## Durable Decisions

- This repo is public.
- It is a front door and map, not a parent org or governance authority.
- Overclaiming past the claim-status discipline is a governance violation here.

## Principles

- Explain and invite honestly.
- Route, do not absorb.
- No revelation without receipts.

## Memory Log

Chronological memory lives at `steward/memory-log.md`. Append useful memory after sessions where this README is loaded.

Lightweight upward-learning pointer: method/workflow-module learnings go to `CapacityOS/mailboxes/rccm/`; kernel-primitive learnings go to `CapacityOS/mailboxes/kernel/`.

## Automation Hooks

Supports CapacityOS-orchestrated and direct repo-mounted runs. Automations are thin triggers; RCCM workflow plus this steward context supply the repo-local operation.

## Local Source References

- `VOICE.md`
- `ROADMAP.md`
- `STATUS.md`
- `boundaries/CLAIM-STATUS.md`
- `README.md`
- `ecosystem/BRIDGE-GUIDE.md`
