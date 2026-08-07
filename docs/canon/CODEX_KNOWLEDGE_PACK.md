# CODEX KNOWLEDGE PACK

**Version:** v1.0 Stable

**Status:** Active

**Phase:** P4 — Repository Standards

## Purpose

CODEX Knowledge Pack เป็น Knowledge Gateway
สำหรับ AI ทุกตัวที่เข้ามาทำงานใน Repository นี้

หน้าที่หลักคือ

- อธิบายโครงสร้าง Repository
- กำหนดลำดับการอ่าน
- ชี้ตำแหน่งเอกสารสำคัญ
- เชื่อม Knowledge Domains
- ลดการตีความผิด
- ป้องกัน Context Loss

## Mission

สร้าง Repository ที่ AI ทุกตัวสามารถเข้าใจ
และใช้แหล่งความรู้เดียวกันได้อย่างสม่ำเสมอ

หลักการคือ

- One Workspace
- One Truth
- One Knowledge System
- Evidence First
- No Scope Creep

## Startup Workflow

AI ทุกตัวต้องดำเนินการตามลำดับ

1. อ่าน `AGENT_PLUGIN_MANIFEST.md`
2. อ่าน `AGENTS.md`
3. อ่าน `CODEX_KNOWLEDGE_PACK.md`
4. อ่าน `docs/current/Current_Project_Truth.md`
5. อ่าน `docs/current/00-Workspace_Index.md`
6. อ่าน `docs/canon/AI_Navigation_Map.md`
7. อ่าน Canon ที่เกี่ยวข้อง
8. อ่าน Knowledge Domain ที่เกี่ยวข้อง
9. อ่าน Issue หรือ Task
10. อ่าน Pull Request หรือ Branch Context

หากเอกสารใดไม่มี

- รายงานว่า `Missing`
- ห้ามเดา
- ห้ามสร้างแทนโดยไม่มี Authorization

## Repository Structure

```text
Codex-Knowledge-Pack/
├── .github/
│   └── workflows/
├── README.md
├── AGENT_PLUGIN_MANIFEST.md
├── AGENTS.md
├── CODEX_KNOWLEDGE_PACK.md
└── docs/
    ├── Repository_Health.md
    ├── archive/
    ├── canon/
    ├── current/
    ├── decisions/
    ├── design/
    ├── engineering/
    ├── organization/
    ├── product/
    ├── research/
    └── templates/
```

## Core Knowledge

### Current Project State

- `docs/current/Current_Project_Truth.md`
- `docs/current/00-Workspace_Index.md`

### Canon

- `docs/canon/Canon_Index.md`
- `docs/canon/20-AI_CHARACTER_CANON.md`
- `docs/canon/AI_Navigation_Map.md`

### Executive Decisions

- `docs/decisions/Executive_Decision_Log.md`

### Repository Health

- `docs/Repository_Health.md`

## Knowledge Domains

### Product

- `docs/product/`

### Engineering

- `docs/engineering/`

### Design

- `docs/design/`

### Research

- `docs/research/`

### Organization

- `docs/organization/`

### Templates

- `docs/templates/`

### Governance

- `docs/current/`
- `docs/decisions/`
- `docs/canon/`

### Archive

- `docs/archive/`

## Repository Principles

- Evidence First
- Documentation First
- Reality over Theory
- Preserve Canon
- Follow Current Project Truth
- No Scope Creep
- No Silent Change
- No False Completion
- Review before Merge
- Preserve History

## Repository Rules

AI ต้อง

- ตรวจ Repository ก่อนอ้างสถานะ
- อ่าน Current Project Truth ก่อนเริ่มงาน
- ใช้ Canon ที่เกี่ยวข้อง
- ใช้หลักฐานจริง
- รายงาน Missing เมื่อหาเอกสารไม่พบ
- รายงาน Conflict ก่อนดำเนินการต่อ

AI ห้าม

- เปลี่ยน Canon เอง
- เปลี่ยน Current Project Truth เอง
- เปลี่ยน Scope เอง
- เดาสถานะ Repository
- อ้างว่า Tests Passed โดยไม่ได้รัน
- สร้างเอกสาร Canon ใหม่โดยไม่มี Approval

## Evidence Priority

ใช้หลักฐานตามลำดับ

1. Repository State
2. Git History
3. CI หรือ Build Logs
4. Test Results
5. Pull Request Context
6. Documentation
7. Screenshot
8. Human Statement

หากข้อมูลยังตรวจสอบไม่ได้

`Unknown = Unknown`

## AI Navigation Rules

AI agents should

1. Start from the manifest.
2. Follow the mandatory reading order.
3. Load Current Project Truth.
4. Load relevant Canon.
5. Navigate to the required Knowledge Domain.
6. Verify repository reality.
7. Keep changes inside approved scope.
8. Report conflicts before implementation.

## Knowledge Governance

เมื่อ Repository Structure เปลี่ยน
ให้ประเมิน Knowledge Impact

เมื่อ Canon เปลี่ยน
ให้แจ้ง Narin และรอ CEO Approval

เมื่อ Scope หรือ Delivery มี Conflict
ให้แจ้ง JARVIS

เมื่อ Current Project Truth เปลี่ยน
ให้บันทึกสถานะใหม่อย่างชัดเจน

เมื่อมี Executive Decision ใหม่
ให้บันทึกใน Executive Decision Log

## Current Authorized Scope

Project:

Codex Knowledge Pack

Version:

v1.0 Stable

Phase:

P4 — Repository Standards

Authorized Work:

- Repository governance
- Knowledge architecture
- Canon maintenance
- Documentation standards
- Repository health
- AI workspace support

New Canon documents require CEO approval.

## Current Status

Repository:

Active

Knowledge Architecture:

Operational

Current Project Truth:

Active

Canon:

Active

AI Navigation:

Operational

Markdown CI:

Operational

Current Phase:

P4 — Repository Standards

## Executive Motto

> One Workspace. One Truth. One Knowledge System.
