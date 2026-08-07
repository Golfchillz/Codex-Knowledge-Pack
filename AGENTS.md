# AGENTS.md

## Golf AI HQ — Codex Workspace Instructions

Version: v1.0 RC1  
Status: Approved  
Phase: P1 — Workspace Files

---

## Purpose

ไฟล์นี้กำหนดกฎการทำงานสำหรับ Codex, Engineering Agent และ AI Agent อื่น ๆ ที่เข้ามาทำงานใน Repository นี้

เป้าหมายคือ:

> Every change must be traceable, reviewable, and safe to ship.

AI ทุกตัวต้องอ่านไฟล์นี้ก่อนเริ่มงาน

---

## Organization

โครงสร้างอำนาจของ Golf AI HQ:

### CEO Golf
Final Decision Maker

มีอำนาจอนุมัติขั้นสุดท้ายเกี่ยวกับ:

- Scope
- Priority
- Canon
- Current Project Truth
- Major Architecture
- Release
- Governance Changes

---

### JARVIS
Chief of Staff

หน้าที่:

- Scope Control
- Priority
- Delivery Coordination
- Risk Escalation
- Executive Alignment

JARVIS ไม่เปลี่ยน Canon โดยพลการ

---

### Narin
Chief Knowledge Architect

หน้าที่:

- Knowledge Architecture
- Canon Management
- Current Project Truth
- Documentation Integrity
- Cross-reference
- Knowledge Sync

หลักการ:

> No Knowledge Left Behind.

---

### Engineering Agent / Codex

หน้าที่:

- Implement
- Refactor
- Test
- Debug
- Document technical changes

Engineering Agent ไม่มีอำนาจ:

- เปลี่ยน Product Scope เอง
- เปลี่ยน Canon เอง
- เปลี่ยน Current Project Truth เอง
- ประกาศงานว่า Verified โดยไม่มีหลักฐาน

---

### GitHub Workspace AI

หน้าที่:

- Repository Management
- Branch Management
- Commit Management
- Pull Request Management
- Issue Management
- Release Process
- Delivery Traceability

---

# Mandatory Reading Order

ก่อนเริ่มงาน ให้ตรวจตามลำดับ:

1. `AGENTS.md`
2. `CODEX_KNOWLEDGE_PACK.md`
3. `00-Workspace_Index.md`
4. Current Project Truth ที่เกี่ยวข้อง
5. Canon ที่เกี่ยวข้อง
6. Repository README
7. Issue / Task
8. Pull Request / Branch Context

หากไฟล์ใดไม่มี:

- รายงานว่า `Missing`
- ห้ามเดาเนื้อหา
- ห้ามสร้างแทนเอง เว้นแต่ได้รับอนุญาต

---

# Core Operating Principles

1. Evidence over Opinion
2. Reality over Theory
3. One Scope per Branch
4. One Purpose per Commit
5. Review before Merge
6. No Secret in Repository
7. No Silent Change
8. No Scope Creep
9. No False Completion
10. Preserve History
11. Trace Every Decision
12. Documentation First when knowledge changes

---

# Repository Reality Rules

Repository คือ Source of Truth สำหรับสถานะของโค้ดและไฟล์

กฎ:

- หาก Prompt กับ Repository ขัดแย้ง ให้รายงานความแตกต่าง
- ห้ามอ้างว่าไฟล์มีอยู่ หากยังไม่ได้ตรวจ
- ห้ามอ้างว่า Branch มีอยู่ หากยังไม่ได้ตรวจ
- ห้ามอ้างว่า Commit หรือ PR มีอยู่ หากยังไม่ได้ตรวจ
- ห้ามอ้างว่า Tests Passed หากไม่ได้รัน
- หากข้อมูลตรวจสอบไม่ได้ ให้ใช้สถานะ `Unknown`
- Do not assume repository state.

---

# Evidence Hierarchy

ใช้หลักฐานตามลำดับดังนี้:

1. Repository State
2. Git History
3. CI / Build Logs
4. Test Output
5. Pull Request Discussion
6. Screenshot / Recording
7. Human Statement

หากหลักฐานขัดแย้งกัน ให้ยึดหลักฐานระดับสูงกว่าและรายงาน Conflict

---

# Branch Rules

หลีกเลี่ยงการทำงานบน `main` โดยตรงเมื่อเป็นงานพัฒนา

รูปแบบชื่อ Branch:

- `feature/<name>`
- `fix/<name>`
- `docs/<name>`
- `refactor/<name>`
- `chore/<name>`
- `release/<version>`
- `hotfix/<name>`

ห้ามใช้ชื่อคลุมเครือ เช่น:

- `test`
- `new`
- `update`
- `final`
- `latest`
- `fix2`

---

# Commit Rules

Commit ต้อง:

- มีวัตถุประสงค์เดียว
- อยู่ใน Scope
- ไม่มี Secret
- ไม่มี API Key
- ไม่มีข้อมูลส่วนตัวที่ไม่ควรอยู่ใน Repository
- ไม่รวมหลายงานที่ไม่เกี่ยวข้องกัน
- มีข้อความที่อ่านแล้วเข้าใจได้

รูปแบบ:

`<type>: <summary>`

ตัวอย่าง:

- `docs: add Codex workspace instructions`
- `docs: add workspace index`
- `feat: add restricted beta summary`
- `fix: correct scenario B response counts`
- `refactor: separate evidence mapping logic`

---

# Pull Request Rules

Pull Request ควรระบุ:

## Summary
สิ่งที่เปลี่ยน

## Objective
เป้าหมาย

## Scope
สิ่งที่อยู่ใน Scope

## Out of Scope
สิ่งที่ไม่ได้ทำ

## Files Changed
ไฟล์สำคัญที่เปลี่ยน

## Behavior Changed
พฤติกรรมระบบที่เปลี่ยน

## Testing Performed
Tests ที่รันจริง

## Testing Not Performed
Tests ที่ยังไม่ได้รัน

## Evidence
Screenshot, Log หรือหลักฐาน

## Risks
ความเสี่ยง

## Related Work
Issue, Decision หรือ Current Project Truth

## Knowledge Impact

ใช้หนึ่งสถานะ:

- None
- Documentation Update Required
- Current Project Truth Review Required
- Canon Review Required
- Decision Record Required

---

# Definition of Done

งานจะถือว่า `Ready for Review` เมื่อ:

- [ ] การเปลี่ยนแปลงตรงตาม Scope
- [ ] ไฟล์ที่เกี่ยวข้องถูกสร้างหรือแก้ไขครบ
- [ ] Content ผ่านการตรวจทาน
- [ ] ไม่มีงานนอก Scope แฝง
- [ ] Diff ถูกตรวจสอบ
- [ ] Tests ที่รันจริงถูกรายงาน
- [ ] Tests ที่ไม่ได้รันถูกรายงาน
- [ ] Documentation ถูกอัปเดตเมื่อจำเป็น
- [ ] Knowledge Impact ถูกประเมิน
- [ ] พร้อมสำหรับ Reviewer

ห้ามใช้คำว่า:

- Completed
- Verified
- Released
- Approved

หากยังไม่มีหลักฐานรองรับ

---

# Status Vocabulary

ใช้สถานะมาตรฐาน:

- Backlog
- Planned
- Authorized to Start
- In Progress
- Ready for Review
- Changes Requested
- Approved
- Ready to Merge
- Merged
- Released
- Blocked
- Closed
- Archived

---

# Knowledge Trigger

แจ้ง Narin เมื่อพบ:

- Repository Structure เปลี่ยน
- Workflow ใหม่
- Branch Policy ใหม่
- Release Process ใหม่
- Architecture Decision
- Canon Impact
- Current Project Truth Impact
- Deprecated File
- Duplicate Documentation
- Major Lessons Learned
- Security Incident
- Repeated CI Failure Pattern

รูปแบบ:

## Knowledge Event Detected

Type:  
Impact:  
Affected Files:  
Recommended Artifacts:  
Status:  
Approval Required:

---

# Executive Escalation

แจ้ง JARVIS เมื่อพบ:

- Scope Conflict
- Main Branch Risk
- Major Merge Conflict
- Repeated CI Failure
- Release Blocker
- Security Risk
- Missing Approval
- Repository Instructions Conflict
- Deadline Risk
- Current Project Truth ไม่ตรงกับ Implementation

รูปแบบ:

## GitHub Escalation

Issue:  
Impact:  
Evidence:  
Blocked Work:  
Recommended Action:  
Decision Required From:

---

# Security Rules

ห้าม Commit:

- API Keys
- Access Tokens
- Passwords
- Private Keys
- Secret Credentials
- Personal Sensitive Information

หากตรวจพบ Secret:

1. หยุดงาน
2. ไม่ Commit
3. รายงาน Security Risk
4. แจ้ง JARVIS
5. รอคำสั่งก่อนดำเนินการต่อ

---

# Scope Control

AI ห้าม:

- ขยาย Scope เอง
- เปลี่ยน Product Direction
- เปลี่ยน Canon
- เปลี่ยน Current Project Truth
- เพิ่ม Dependency โดยไม่จำเป็น
- Refactor งานอื่นเพียงเพราะพบระหว่างทำงาน
- Cleanup ไฟล์นอก Scope โดยไม่มีคำสั่ง
- ลบ History โดยพลการ

เมื่อพบสิ่งที่ควรปรับแต่นอก Scope:

ให้รายงานเป็น Recommendation เท่านั้น

---

# Current Authorized Scope

Project: Codex Knowledge Pack  
Version: v1.0 RC1  
Phase: P1 — Workspace Files

Authorized Files:

1. `AGENTS.md`
2. `CODEX_KNOWLEDGE_PACK.md`
3. `00-Workspace_Index.md`

ห้ามสร้างไฟล์อื่นเพิ่มโดยไม่มีคำสั่งจาก CEO

---

# Current Project State

Approval State: Approved  
Authorized Scope: First 3 Files Only

Files:

- `AGENTS.md`
- `CODEX_KNOWLEDGE_PACK.md`
- `00-Workspace_Index.md`

Files Outside Current Scope:

`Not Authorized`

---

# Default Start Report

ก่อนเริ่มงานให้รายงาน:

## Repository Check

Repository:  
Branch:  
Task:  
Scope:  
Relevant Instructions:  
Current Project Truth:  
Risks:  
Status:

---

# Default Completion Report

หลังทำงานให้รายงาน:

## GitHub Work Report

Objective:  
Branch:  
Files Changed:  
Commits:  
Tests Performed:  
Tests Not Performed:  
Pull Request:  
Risks:  
Knowledge Impact:  
Status:  
Next Required Action:

---

# Executive Motto

> Clean history. Clear scope. Safe delivery.
