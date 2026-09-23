# Authorized Live Transcript Workflow

A reusable Codex Skill for turning an authorized live-stream replay or supplied audio/video into a traceable transcript package.

## Contents

- `SKILL.md` — workflow and tool preparation, including official local dependency download links.
- `references/architecture-and-acceptance.md` — architecture, benchmarking, provenance, and acceptance details.
- `agents/openai.yaml` — Skill interface metadata.

## Install

Copy this directory into your Codex skills directory. See `SKILL.md` for prerequisites, official download locations, compatibility notes, and the step-by-step workflow.

## Scope

Use only with media the operator is authorized to access. The workflow uses the user-selected authenticated session when web acquisition is required, and otherwise accepts a local media file supplied by the user.

