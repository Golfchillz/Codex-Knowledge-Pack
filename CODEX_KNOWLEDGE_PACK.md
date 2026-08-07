# CODEX KNOWLEDGE PACK

Version: v1.0 RC1

Status: Approved

Phase: P1 — Workspace Files

---

# Purpose

ไฟล์นี้เป็นประตูหลัก (Gateway) สำหรับ AI ทุกตัวที่เข้ามาทำงานใน Repository

หน้าที่ของไฟล์นี้คือ

- อธิบายโครงสร้างความรู้
- ชี้ตำแหน่งเอกสารสำคัญ
- กำหนดลำดับการอ่าน
- ลดเวลาในการทำความเข้าใจ Workspace
- ป้องกันการตีความผิดของ AI

Knowledge Pack นี้ทำหน้าที่เป็น Table of Contents ของ Repository

---

# AI Startup Workflow

ทุกครั้งก่อนเริ่มงาน

AI ต้องดำเนินการตามลำดับดังนี้

1. อ่าน AGENTS.md
2. อ่าน CODEX_KNOWLEDGE_PACK.md
3. อ่าน 00-Workspace_Index.md
4. อ่าน Current Project Truth
5. อ่าน Canon ที่เกี่ยวข้อง
6. อ่าน README
7. อ่าน Issue หรือ Task
8. อ่าน Branch / Pull Request Context

---

# Current Authorized Scope

Project

Codex Knowledge Pack

Version

v1.0 RC1

Phase

P1 — Workspace Files

Approved Files

- AGENTS.md
- CODEX_KNOWLEDGE_PACK.md
- 00-Workspace_Index.md

Files Outside Current Scope

Not Authorized

---

# Workspace Structure

Repository

├── README.md

├── AGENTS.md

├── CODEX_KNOWLEDGE_PACK.md

└── 00-Workspace_Index.md

---

# Reading Order

Level 1

AGENTS.md

↓

CODEX_KNOWLEDGE_PACK.md

↓

00-Workspace_Index.md

Level 2

Current Project Truth

↓

Canon

↓

Repository Documents

Level 3

Issues

↓

Pull Requests

↓

Implementation

---

# Knowledge Categories

Governance

Current Project Truth

Canon

Architecture

Engineering

Research

Documentation

Organization

Workflow

Decision Records

Release Notes

---

# Operating Principles

Evidence over Opinion

Documentation First

Reality over Theory

No Scope Creep

No False Completion

No Silent Change

One Purpose per Commit

One Scope per Branch

Review before Merge

---

# Repository Reality Rules

Repository คือ Source of Truth

หาก Repository กับ Prompt ขัดแย้ง

ให้รายงานความแตกต่างก่อน

ห้ามเดาสถานะ Repository

ห้ามเดาสถานะไฟล์

ห้ามเดาสถานะ Branch

ห้ามเดาสถานะ Pull Request

Unknown = Unknown

---

# Knowledge Sync

เมื่อพบ

- Repository Structure เปลี่ยน
- Canon เปลี่ยน
- Current Project Truth เปลี่ยน
- Workflow ใหม่
- Architecture ใหม่

ให้แจ้ง Narin

หากพบ

- Scope Conflict
- Merge Risk
- Release Blocker
- Current Project Truth Conflict

ให้แจ้ง JARVIS

---

# Future Knowledge Packs

ในอนาคตไฟล์นี้จะชี้ไปยัง

knowledge/

engineering/

organization/

design/

research/

templates/

workflow/

แต่ยังไม่อยู่ใน Scope ของ P1

---

# Definition of Done

Knowledge Pack ถือว่า Ready for Review เมื่อ

- Reading Order ถูกต้อง
- Cross References ถูกต้อง
- ไม่มี Canon Conflict
- ไม่มี Current Project Truth Conflict
- Documentation อยู่ใน Scope
- AI เข้าใจ Repository ได้จากไฟล์นี้

---

# Current Status

Status

Approved

Phase

P1

Current Scope

Workspace Files

Next Phase

Repository Review

---

# Executive Motto

One Workspace

One Truth

One Knowledge System
