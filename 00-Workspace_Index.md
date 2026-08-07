# 00 — Workspace Index

**Version:** v1.0 RC1  
**Status:** Approved  
**Phase:** P1 — Workspace Files

---

# Purpose

ไฟล์นี้เป็นแผนที่หลัก (Workspace Map) ของ Repository

มีหน้าที่ช่วยให้ AI ทุกตัวเข้าใจโครงสร้างของ Workspace ได้อย่างรวดเร็ว และรู้ว่าควรเริ่มอ่านเอกสารจากจุดใด

เป้าหมายคือ

> **Fast Orientation • Clear Truth • No Lost Context**

---

# Current Project

| Item | Value |
|------|-------|
| Project | Codex Knowledge Pack |
| Version | v1.0 RC1 |
| Phase | P1 — Workspace Files |
| Approval | Approved |

---

# Current Authorized Scope

ไฟล์ที่ได้รับอนุมัติใน Phase นี้

- `AGENTS.md`
- `CODEX_KNOWLEDGE_PACK.md`
- `00-Workspace_Index.md`

ไฟล์อื่นทั้งหมด

**Status:** Not Authorized

---

# Mandatory Reading Order

AI ทุกตัวต้องอ่านตามลำดับนี้

1. AGENTS.md
2. CODEX_KNOWLEDGE_PACK.md
3. 00-Workspace_Index.md
4. Current Project Truth
5. Canon
6. README.md
7. Issue / Task
8. Pull Request / Branch Context

หากไฟล์ใดไม่มี

- Report: **Missing**
- Do not assume
- Do not generate replacement without approval

---

# Repository Structure

Current

```text
Codex-Knowledge-Pack/
├── README.md
├── AGENTS.md
├── CODEX_KNOWLEDGE_PACK.md
└── 00-Workspace_Index.md
```

Future (Planned Only)

```text
Codex-Knowledge-Pack/
├── README.md
├── AGENTS.md
├── CODEX_KNOWLEDGE_PACK.md
├── 00-Workspace_Index.md
├── knowledge/
├── organization/
├── engineering/
├── design/
├── research/
├── workflow/
├── templates/
└── decisions/
```

> Future folders are **Planned** and are **not authorized** in P1.

---

# Organization

| Role | Responsibility |
|------|----------------|
| CEO Golf | Final Decision Maker |
| JARVIS | Scope, Priority, Delivery |
| Narin | Canon, Current Project Truth, Knowledge |
| Engineering Agent | Implementation, Testing |
| GitHub Workspace AI | Repository, Branch, PR, Release |

---

# Source of Truth

เมื่อข้อมูลขัดแย้งกัน ให้ยึดตามลำดับนี้

1. Repository State
2. Current Project Truth
3. Canon
4. Executive Decision
5. Git History
6. Test / CI Evidence
7. Documentation
8. Human Statement

หากยังสรุปไม่ได้

**Status = Unknown**

---

# Current Priority

Current Phase

**P1 — Workspace Files**

Current Goal

- Complete Workspace Files
- Review
- Open Pull Request
- Merge after Approval

---

# Workspace Health Checklist

- [ ] AGENTS.md exists
- [ ] CODEX_KNOWLEDGE_PACK.md exists
- [ ] 00-Workspace_Index.md exists
- [ ] Reading Order verified
- [ ] Scope verified
- [ ] Cross References verified
- [ ] No Canon Conflict
- [ ] No Current Project Truth Conflict

---

# Definition of Ready

Workspace ถือว่า Ready for Review เมื่อ

- Workspace Files ครบ
- Reading Order ถูกต้อง
- Cross References ถูกต้อง
- Scope ถูกต้อง
- Repository ตรวจสอบแล้ว

---

# Next Phase

หลัง P1 ผ่านแล้ว

Repository จะขยายไปยัง

- Knowledge
- Canon
- Current Project Truth
- Architecture
- Decision Records
- Workflow
- Templates

ทั้งหมดนี้ **ยังไม่อยู่ใน Scope ปัจจุบัน**

---

# Executive Motto

> Clean History. Clear Scope. Safe Delivery.
