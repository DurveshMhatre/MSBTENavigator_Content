# 📘 MSBTE Navigator — Content Management Guide

> **Prepared:** 28 June 2026  
> **For:** Newly Appointed Content Manager  
> **Website:** [https://msbtenavigator.com](https://msbtenavigator.com)  
> **Contact Owner:** If you face any difficulty or need access/permissions, contact the project owner immediately (Telegram: [@Durvesh1209](https://t.me/Durvesh1209))

---

## Table of Contents

1. [Understanding the Website](#1-understanding-the-website)
2. [Understanding the Local Resource Directory](#2-understanding-the-local-resource-directory)
3. [Scheme Priority & Relevance Guide](#3-scheme-priority--relevance-guide)
4. [Resource Categories — What to Upload](#4-resource-categories--what-to-upload)
5. [What NOT to Upload (Junk / Irrelevant Files)](#5-what-not-to-upload-junk--irrelevant-files)
6. [Step-by-Step Upload Workflow](#6-step-by-step-upload-workflow)
7. [Scheme-wise Content Inventory & Action Plan](#7-scheme-wise-content-inventory--action-plan)
8. [File Naming Conventions](#8-file-naming-conventions)
9. [Quality Checklist Before Uploading](#9-quality-checklist-before-uploading)
10. [Content Update Schedule](#10-content-update-schedule)
11. [Troubleshooting & Escalation](#11-troubleshooting--escalation)

---

## 1. Understanding the Website

### Website Flow (Navigation Hierarchy)

```
Homepage (msbtenavigator.com)
  └── Notes (/notes)
        ├── I Scheme (2017) → /notes/i
        ├── K Scheme (2023) → /notes/k  ← MOST STUDENTS — HIGHEST PRIORITY
        ├── F Scheme (2024-25) → /notes/f  ← Flexible Diploma for Working Professionals
              └── [Branch Selection]
                    └── [Semester Selection]
                          └── [Subject] → Resources (Notes, PYQs, Manuals, etc.)
```

### Website Pages & Sections

| Page | URL | Purpose |
|------|-----|---------|
| Home | `/` | Landing page, features showcase |
| Notes / Library | `/notes` | **Main resource library** — Scheme → Branch → Semester → Subject |
| Upload | `/upload` | Resource upload page (use this to upload content) |
| Marketplace | `/marketplace` | Premium resources marketplace |
| Community | `/community` | Student discussion & community |
| Mentors | `/mentors` | Mentor profiles |
| Pricing | `/pricing` | Pro plan (₹99/month) |
| Blog | `/blog` | Blog articles |
| Login | `/login` | User authentication (Sign in first before managing content) |

### Resource Types the Website Supports

The website provides these types of study materials:
- 📝 **Notes** — Chapter-wise / unit-wise study notes
- 📄 **Previous Year Questions (PYQs)** — Past MSBTE exam papers
- ✅ **Model Answers** — Official MSBTE model answers
- 📋 **Syllabus / Curriculum** — Subject syllabus & curriculum PDFs
- 🔬 **Lab Manuals** — Practical experiment manuals (blank & solved)
- 📊 **Question Banks** — Unit test & exam question banks

### Current Website Status (As of June 2026)

> **⚠️ IMPORTANT:** The website currently shows **0 resources** across all three schemes. The entire content library is empty and needs to be populated from the local directory. This is your primary job.

---

## 2. Understanding the Local Resource Directory

### Root Directory Structure

```
F:\MsbteNav Resource Upload\
├── 📁 K Scheme\              ← CURRENT ACTIVE SCHEME (2023–present)
│     ├── (AN) AI & Machine Learning\
│     ├── 1 and 2 sem books\    ← SHARED across all branches
│     ├── Automobile Engineering (AE)\
│     ├── Chemical Engineering (CH)\
│     ├── Civil Engineering (CE)\
│     ├── Computer Engineering (CO)\
│     ├── Electrical Engineering (EE)\
│     ├── Electronics & Tele-communication (EJ)\
│     ├── Information Technology (IF)\
│     ├── Mechanical Engineering (ME)\
│     ├── Production Engineering (PG)\
│     └── Travel and Tourism (TR)\
│
├── 📁 I Scheme [Last Batch]\ ← PREVIOUS SCHEME (2017–2023, phasing out)
│     ├── Sem II All Sub\
│     ├── Sem III All Sub\
│     ├── Sem IV All Sub\
│     ├── Sem V All Sub\
│     └── Sem VI All Sub\
│
└── 📁 F Scheme\              ← FLEXIBLE DIPLOMA SCHEME (2024–25 for Working Professionals)
      ├── Civil Engineering (PCE)\
      ├── Computer Department\
      │     ├── Computer Engineering (PCO)\
      │     ├── Computer Science and Engineering (PCW)\
      │     └── Information Technology (PIF)\
      ├── Electric Department\
      │     ├── Electrical Engineering (PEE)\
      │     └── Electrical Power System (PEP)\
      ├── Electronics & Tele Communication Engg (PEJ)\
      ├── Mechanical Engineering (PME)\
      └── Mining & Mine Surveying (PMS)\
```

### K Scheme — Branch & Semester Folder Code Pattern

K Scheme folders follow this pattern: **`{BranchCode}-{SemesterNumber}K`**

| Branch | Code | Semester Folders | Total Semesters |
|--------|------|-----------------|-----------------|
| Computer Engineering | CO | CO-1K through CO-6K | 6 |
| Information Technology | IF | IF-1K through IF-6K | 6 |
| Electrical Engineering | EE | EE-1K through EE-6K | 6 |
| Mechanical Engineering | ME | ME-1K through ME-6K | 6 |
| Civil Engineering | CE | CE-1K through CE-6K | 6 |
| Electronics & Telecomm | EJ | EJ-1K through EJ-6K | 6 |
| AI & Machine Learning | AN | AN-1K through AN-6K | 6 |
| Automobile Engineering | AE | AE-1K through AE-6K | 6 |
| Chemical Engineering | CH | CH-1K through CH-6K | 6 |
| Production Engineering | PG | PG-1K through PG-6K | 6 |
| Travel and Tourism | TR | TR-1K through TR-6K | 6 |

### F Scheme — Branch & Semester Folder Code Pattern

F Scheme folders follow: **`{BranchCode}-{SemesterNumber}F`**

| Branch | Code | Semester Folders |
|--------|------|-----------------|
| Computer Engineering | PCO | PCO-3F through PCO-6F |
| Computer Science & Engg | PCW | PCW-3F through PCW-6F |
| Information Technology | PIF | PIF-3F through PIF-6F |
| Civil Engineering | PCE | PCE-3F through PCE-6F |
| Mechanical Engineering | PME | PME-3F through PME-6F |
| Electrical Engineering | PEE | (Check sub-folders) |
| Electrical Power System | PEP | (Check sub-folders) |
| Electronics & Telecomm | PEJ | PEJ-3F through PEJ-6F |
| Mining & Mine Surveying | PMS | PMS-2F through PMS-6F |

### I Scheme Structure (DIFFERENT Layout!)

> **⚠️ WARNING:** I Scheme is organized differently — it is by **Semester** only (not by Branch first), because this is a legacy collection covering all subjects within each semester.

```
I Scheme [Last Batch]\
├── Sem II All Sub\   ← Contains subjects like PCI (C Language), WPD, BEC, Maths, CPH
├── Sem III All Sub\  ← Contains OOP (22316), DSU (22317), POD (22321), DCO (22322), DTM (22323), CGR
├── Sem IV All Sub\   ← Contains Java (22412), SE (22413), DBMS (22416), CN (22417), VB.Net
├── Sem V All Sub\    ← Contains OS (22516), Adv Java (22517), CSS (22519), EST, EDE
└── Sem VI All Sub\   ← Contains MAD (22617), ETI (22618), WBP (22619), NIS (22620), Python
```

---

## 3. Scheme Priority & Relevance Guide

### 🔴 Priority Matrix

| Priority | Scheme | Why | Action |
|----------|--------|-----|--------|
| 🔴 **HIGHEST** | **K Scheme (2023)** | Current active scheme. All newly admitted students (June 2023 onward) are on K Scheme. Largest and growing user base. | Upload ALL available content **FIRST** |
| 🟡 **MEDIUM** | **I Scheme (2017)** | Last batch students are finishing up. Very few students remaining by 2026 (backlog/ATKT students only). | Upload only PYQs & Model Answers for Sem 5-6. **Ask owner first.** |
| 🟡 **MEDIUM** | **F Scheme (2024-25)** | Flexible diploma scheme specifically for Working Professionals. | Upload Syllabus, Curriculum, and available course materials for working professional students. |

### K Scheme — Semester Priority Within K Scheme

| Priority | Semesters | Reason |
|----------|-----------|--------|
| 🔴 CRITICAL | Sem 3 & Sem 4 | Most students are currently in 2nd year |
| 🟡 HIGH | Sem 1 & Sem 2 | New admissions happen every June; freshers always need material |
| 🟠 MEDIUM | Sem 5 & Sem 6 | 3rd year students, smaller batch but still active |

---

## 4. Resource Categories — What to Upload

### ✅ UPLOAD THESE (Useful for Current Students)

| # | Category | File Types | Priority | Example Files from Directory |
|---|----------|-----------|----------|------------------------------|
| 1 | **Previous Year Questions (PYQs)** | PDF | 🔴 HIGHEST | `DSU S-25 313301.pdf`, `OOP W-24 313304.pdf` |
| 2 | **Model Answers** | PDF | 🔴 HIGHEST | `DSU S-19 Model Answer.pdf`, `OOP 22316 W-18 Model.pdf` |
| 3 | **Notes (Unit-wise)** | PDF preferred | 🟡 HIGH | `DSU Unit 01 Notes.doc`, `Unit-04-Stack Updated.pdf`, `1.Tree Notes_Part-1.pdf` |
| 4 | **Syllabus / Curriculum** | PDF | 🟡 HIGH | `CO-3K Curriculumn Syllabus.pdf`, `IF_CO-K Curriculumn.pdf` |
| 5 | **Question Banks** | PDF | 🟡 HIGH | Unit test question bank PDFs in `Question Banks\` folders |
| 6 | **Lab Manuals (Blank)** | PDF | 🟠 MEDIUM | Official MSBTE practical manuals |
| 7 | **Solved Manuals** | PDF | 🟠 MEDIUM | Completed lab manuals with answers |
| 8 | **Textbook-style Notes** | PDF | 🟠 MEDIUM | `Basic Mathematics MSBTE.pdf`, `Basic Science K Scheme Notes MSBTE.pdf` |

### Priority Upload Rule:
**PYQs > Model Answers > Notes > Syllabus > Question Banks > Manuals**

---

## 5. What NOT to Upload (Junk / Irrelevant Files)

### ❌ NEVER Upload These Files

| # | File Type | Reason | Examples Found in Directory |
|---|-----------|--------|-----------------------------|
| 1 | **Timetables** | Outdated, college-specific, changes every year | `TIMETABLE- EVEN 2021-22.pdf`, `TIMETABLE-ODD 2022-FINAL.pdf` |
| 2 | **Evaluation Sheets** | Internal college documents | `Evaluation sheet.pdf` |
| 3 | **Temporary Word files** | System-generated trash files | `~$llabus For All Subject...docx` (any file starting with `~$`) |
| 4 | **Duplicate files** | Same content repeated | `311305-physics (1).pdf` and `311305-physics.pdf` — upload only ONE |
| 5 | **ZIP archives** | Too large, not viewable on website | `Sem IV All Sub.zip` (253 MB!) |
| 6 | **Image timetables** | Low quality, outdated | `Time table.jfif` |
| 7 | **Mock exam links** | External links, not actual content | `Online Mock Exam Test Your Knowledge.pdf` |
| 8 | **Academic Calendar** | Year-specific, quickly outdated | `A.Y. 2024-25_AcademicCalendar...pdf` |
| 9 | **README files** | Internal notes, not study material | `README.txt`, `README.docx`, `README.pdf` |
| 10 | **DOCX when PDF exists** | Always upload PDF version; skip DOCX duplicate | Any `.docx` that has a matching `.pdf` file |
| 11 | **Micro Project templates** | Not directly exam-relevant | `22057_Micro_Projects_Industrial_Training...pdf` (75 MB!) |
| 12 | **Online Practice docs** | Just links to external sites | `Online Practice Exam.docx` |

### 🚩 Red Flags — Instant Skip Rules

Skip any file that:
1. **Filename starts with `~$`** → Temp MS Office file
2. **Is a `.zip` archive** → Not directly viewable
3. **Contains "timetable"** → College/year specific
4. **Contains "evaluation"** → Internal assessment
5. **Has `(1)` or `copy` in name** → Duplicate
6. **Is DOCX AND a PDF version exists** → Use PDF only
7. **Contains old year (2021-22, etc.) in timetable context** → Outdated
8. **Is an academic calendar** → Changes every year
9. **Is a personal README** → Not study material
10. **File size > 50MB** → Check with owner before uploading

---

## 6. Step-by-Step Upload Workflow

### Phase 1: K Scheme Content (Do This FIRST — Weeks 1-4)

#### Step 1: Login to the Website

1. Go to [https://msbtenavigator.com/login](https://msbtenavigator.com/login)
2. Sign in with the admin/manager credentials (get from owner if you don't have them)
3. Navigate to the Upload page: [https://msbtenavigator.com/upload](https://msbtenavigator.com/upload)

> **📞 Contact owner immediately if you don't have login credentials or upload access.**

#### Step 2: Start with Computer Engineering (CO) — It's the Most Content-Rich

Open this folder on your computer:
```
F:\MsbteNav Resource Upload\K Scheme\Computer Engineering (CO)\
```

#### Step 3: Process Each Semester Folder (CO-1K through CO-6K)

For each semester folder, follow this exact order:

```
1. Open the semester folder (e.g., CO-3K)
2. Look for these sub-folders & files:
   ├── PYQs\           → Upload ALL PYQ PDFs (highest priority)
   │   ├── Summer 2025\ → Upload all PDFs inside
   │   └── Winter 2024\ → Upload all PDFs inside
   ├── Model Answers\   → Upload ALL Model Answer PDFs
   │   ├── DSU\         → Upload all DSU model answers
   │   └── OOP\         → Upload all OOP model answers
   ├── Notes\           → Upload unit-wise notes (PDF preferred over DOCX)
   │   ├── DSU\         → Upload DSU notes
   │   └── OOP\         → Upload OOP notes
   ├── Question Banks\  → Upload question bank PDFs
   ├── Manuals\         → Upload blank/solved manual PDFs
   └── *.pdf (root)     → Check if it's syllabus/curriculum → Upload it
```

#### Step 4: Map Each File to the Correct Website Location

For each file you upload, select the correct path on the website:

```
Scheme: K Scheme
  → Branch: Computer Engineering
    → Semester: 3
      → Subject: DSU (313301)
        → Resource Type: PYQ / Notes / Model Answer / etc.
```

**Detailed Mapping Example — K Scheme CO Semester 3:**

| Local File Path | Website Selection | Resource Type |
|----------------|-------------------|---------------|
| `CO-3K\PYQs\Summer 2025\DSU S-25 313301.pdf` | K → CO → Sem 3 → DSU (313301) | PYQ |
| `CO-3K\PYQs\Summer 2025\DMS S-25 313302.pdf` | K → CO → Sem 3 → DMS (313302) | PYQ |
| `CO-3K\PYQs\Summer 2025\DTE S-25 313303.pdf` | K → CO → Sem 3 → DTE (313303) | PYQ |
| `CO-3K\PYQs\Summer 2025\OOP S-25 313304.pdf` | K → CO → Sem 3 → OOP (313304) | PYQ |
| `CO-3K\PYQs\Winter 2024\DSU W-24 313301.pdf` | K → CO → Sem 3 → DSU (313301) | PYQ |
| `CO-3K\PYQs\Winter 2024\OOP W-24 313304.pdf` | K → CO → Sem 3 → OOP (313304) | PYQ |
| `CO-3K\Model Answers\DSU\DSU S-19 Model Answer.pdf` | K → CO → Sem 3 → DSU (313301) | Model Answer |
| `CO-3K\Model Answers\DSU\DSU W-18 Model Answer.pdf` | K → CO → Sem 3 → DSU (313301) | Model Answer |
| `CO-3K\Model Answers\OOP\OOP 22316 S-19 Model.pdf` | K → CO → Sem 3 → OOP (313304) | Model Answer |
| `CO-3K\Notes\DSU\DSU Unit 01 Notes.doc` | K → CO → Sem 3 → DSU (313301) | Notes |
| `CO-3K\Notes\DSU\DSU Unit 02 Notes.pdf` | K → CO → Sem 3 → DSU (313301) | Notes |
| `CO-3K\Notes\DSU\Unit-03-Linked List.docx` | K → CO → Sem 3 → DSU (313301) | Notes |
| `CO-3K\Notes\DSU\Unit-04-Stack Updated.pdf` | K → CO → Sem 3 → DSU (313301) | Notes |
| `CO-3K\Notes\DSU\1.Tree Notes_Part-1.pdf` | K → CO → Sem 3 → DSU (313301) | Notes |
| `CO-3K\Manuals\313301 - DATA STRUCTURE USING C.pdf` | K → CO → Sem 3 → DSU (313301) | Lab Manual |
| `CO-3K\Manuals\313304 - OOP USING C++.pdf` | K → CO → Sem 3 → OOP (313304) | Lab Manual |
| `CO-3K\CO-3K Curriculumn Syllabus.pdf` | K → CO → Sem 3 | Syllabus |

**CO Semester 6 Syllabus Files (upload each under the correct subject):**

| Local File | Subject |
|-----------|---------|
| `CO-6K\315301-MANAGEMENT.pdf` | Management |
| `CO-6K\316313-EMERGING TRENDS IN CO AND IT.pdf` | Emerging Trends |
| `CO-6K\316314-SOFTWARE TESTING.pdf` | Software Testing |
| `CO-6K\316005-CLIENT SIDE SCRIPTING.pdf` | Client Side Scripting |
| `CO-6K\316006-MOBILE APPLICATION DEVELOPMENT.pdf` | MAD |
| `CO-6K\316004-CAPSTONE PROJECT.pdf` | Capstone Project |
| `CO-6K\316315-DIGITAL FORENSIC AND HACKING.pdf` | Digital Forensic |
| `CO-6K\316316-MACHINE LEARNING.pdf` | Machine Learning |
| `CO-6K\316317-NETWORK AND INFORMATION SECURITY.pdf` | NIS |

#### Step 5: Handle Shared Semester 1 & 2 Content

> **⚠️ IMPORTANT:** Semesters 1 and 2 have **common subjects across many branches** (Basic Maths, Physics, Chemistry, English). The folder `K Scheme\1 and 2 sem books\` contains shared material.
>
> Upload these under **each relevant branch** for Sem 1 and Sem 2, or ask the owner if the website has a "Common/Shared" subject area.

**Shared Sem 1-2 Resources Available:**

| Local Path | Content Type | Upload Under |
|-----------|-------------|-------------|
| `1 and 2 sem books\PYQs\English - 311303 2024.pdf` | PYQ | All branches → Sem 1 → English (311303) |
| `1 and 2 sem books\PYQs\Maths - 311302 2024.pdf` | PYQ | All branches → Sem 1 → Maths (311302) |
| `1 and 2 sem books\Question Banks\` (8 PDFs) | Question Banks | Respective subjects across branches |
| `1 and 2 sem books\Notes\` | Notes | Respective subjects across branches |
| `1 and 2 sem books\Model Answer\` | Model Answers | Respective subjects across branches |
| `1 and 2 sem books\Manual\` | Lab Manuals | Respective subjects across branches |
| `1 and 2 sem books\Solved manual\` | Solved Manuals | Respective subjects across branches |
| `1 and 2 sem books\Basic Mathematics MSBTE.pdf` | Textbook Notes | All branches → Sem 1 → Maths |
| `1 and 2 sem books\Basic Science K Scheme Notes MSBTE.pdf` | Textbook Notes | All branches → Sem 1 → Basic Science |

**Question Bank Files Available (Sem 1):**

| File | Subject |
|------|---------|
| `Communication_Skills_English-311303_Unit_Test-1_201123.pdf` | English (311303) UT-1 |
| `Communication_Skills_English-311303_Question_Bank-Unit_Test-2_201123.pdf` | English (311303) UT-2 |
| `QB_BMS-311302-_SEM-I_UT-1_111223.pdf` | Maths (311302) UT-1 |
| `QB_BMS-311302-_SEM-I_UT-2_111223.pdf` | Maths (311302) UT-2 |
| `311305-Basic_Physics-Unit_Test-1_050224.pdf` | Physics (311305) UT-1 |
| `311305_-_Basic_Physics_-_Unit_Test_-_2_030224.pdf` | Physics (311305) UT-2 |
| `UT-1_Basic_Chemistry_241123.pdf` | Chemistry UT-1 |
| `UT-2_Basic_Chemistry_241123.pdf` | Chemistry UT-2 |

#### Step 6: Process Remaining K Scheme Branches

After finishing Computer Engineering (CO), repeat the same process for each branch in this order:

1. **Information Technology (IF)** — Similar structure to CO (IF-1K through IF-6K)
2. **Electrical Engineering (EE)** — EE-1K through EE-6K
3. **Mechanical Engineering (ME)** — ME-1K through ME-6K
4. **Civil Engineering (CE)** — CE-1K through CE-6K
5. **Electronics & Telecomm (EJ)** — EJ-1K through EJ-6K
6. **AI & Machine Learning (AN)** — AN-1K through AN-6K
7. **Automobile Engineering (AE)** — AE-1K through AE-6K
8. **Chemical Engineering (CH)** — CH-1K through CH-6K
9. **Production Engineering (PG)** — PG-1K through PG-6K
10. **Travel and Tourism (TR)** — TR-1K through TR-6K

---

### Phase 2: I Scheme Content (Week 5 — SELECTIVE Upload Only)

> **⚠️ WARNING:** I Scheme is the **last batch** — most students have already graduated. Before uploading any I Scheme content, **confirm with the owner** which semesters still have active students.

#### Decision Table for I Scheme:

| Semester | Folder | Upload? | Reason |
|----------|--------|---------|--------|
| Sem II | `Sem II All Sub\` | ❌ **NO** | These students graduated years ago |
| Sem III | `Sem III All Sub\` | ❌ **NO** | No active students |
| Sem IV | `Sem IV All Sub\` | ❌ **NO** | No active students |
| Sem V | `Sem V All Sub\` | ⚠️ **ASK OWNER** | May have backlog/ATKT students |
| Sem VI | `Sem VI All Sub\` | ⚠️ **ASK OWNER** | May have backlog/ATKT students |

#### If Owner Approves I Scheme Upload, Priority Resources:

From Sem V & VI, upload ONLY:
1. **PYQs** (most useful for exam preparation)
2. **Model Answers** (official MSBTE answers)
3. **Notes** (PDF versions only, skip DOCX)

#### Key I Scheme Subject Codes (for Reference):

**Sem III Subjects:**
| Code | Subject Name | Short Name |
|------|-------------|------------|
| 22316 | Object Oriented Programming Using C++ | OOP |
| 22317 | Data Structure Using C | DSU |
| 22321 | Principles of Database | POD |
| 22322 | Data Communication | DCO |
| 22323 | Digital Techniques & Microprocessor | DTM |
| 22318 | Computer Graphics | CGR |
| 22024 | Applied Multimedia Techniques | — |

**Sem IV Subjects:**
| Code | Subject Name | Short Name |
|------|-------------|------------|
| 22412 | Java Programming | Java |
| 22413 | Software Engineering | SE |
| 22416 | Database Management | DBMS |
| 22417 | Computer Networks | CN |
| 22034 | GUI Application Development (VB.Net) | VB.Net |

**Sem V Subjects:**
| Code | Subject Name | Short Name |
|------|-------------|------------|
| 22516 | Operating Systems | OS |
| 22517 | Advanced Java Programming | AJP |
| 22519 | Client Side Scripting | CSS |
| 22447 | Environmental Studies | EST |
| 22032 | EDE | EDE |

**Sem VI Subjects:**
| Code | Subject Name | Short Name |
|------|-------------|------------|
| 22509 | Management | MGT |
| 22617 | Mobile Application Development | MAD |
| 22618 | Emerging Trends in IT | ETI |
| 22619 | Web Based Programming | WBP |
| 22620 | Network & Information Security | NIS |
| 22622 | Wireless Mobile & Network | WMN |

---

### Phase 3: F Scheme Content (Working Professionals — Flexible Diploma)

> **ℹ️ NOTE:** F Scheme is a flexible diploma program introduced by MSBTE in A.Y. 2024-25 specifically tailored for working professionals (part-time / working professional diploma).

#### What to Upload from F Scheme:

| Content Type | Upload? | Reason |
|-------------|---------|--------|
| Syllabus/Curriculum | ✅ **Yes** | Essential for working professionals to understand course structure |
| Course Materials/Notes | ✅ **Yes** | Crucial learning support for working students |
| PYQs & Sample Papers | ✅ **Yes** | Helps students prepare for flexible exam patterns |
| Manuals | ✅ **Yes** | Practical lab guidelines |

#### F Scheme Branches Available:

| Department | Branches | Semesters |
|-----------|----------|-----------|
| Computer Department | PCO (Computer Engg), PCW (CS&E), PIF (Info Tech) | Sem 3–6 each |
| Civil Engineering | PCE | Sem 3–6 |
| Mechanical Engineering | PME | Sem 3–6 |
| Electrical Department | PEE (Electrical), PEP (Power Systems) | Check folders |
| Electronics & Telecomm | PEJ | Sem 3–6 |
| Mining & Mine Surveying | PMS | Sem 2–6 |

**Example F Scheme Syllabus to Upload:**
- `F Scheme\Computer Department\Computer Engineering (PCO)\PCO-3F\PCO-3F Syllabus cum Curriculum.pdf`

---

## 7. Scheme-wise Content Inventory & Action Plan

### K Scheme — Computer Engineering (CO) Detailed Inventory

| Semester | PYQs | Model Answers | Notes | Question Banks | Manuals | Syllabus | Action |
|----------|------|---------------|-------|----------------|---------|----------|--------|
| **CO-1K** | ✅ 2 PYQ PDFs (English, Maths) | — | — | ✅ 8 QB PDFs (all subjects) | — | ✅ Curriculum PDF | 📤 Upload All |
| **CO-2K** | Check folder | ✅ Has folder | ✅ Has folder | — | ✅ Has folders | ✅ Syllabus PDF | 📤 Upload All |
| **CO-3K** | ✅ S-25 & W-24 (8 PDFs total) | ✅ DSU + OOP (6 PDFs) | ✅ DSU (6 files) | ✅ 2 UT folders | ✅ 3 manual PDFs | ✅ Curriculum PDF | 🔴 **RICHEST — Upload First!** |
| **CO-4K** | Check folder | — | — | ✅ Has folder | ✅ Blank Manuals | ✅ Curriculum PDF | 📤 Upload available |
| **CO-5K** | Check folder | — | — | ✅ Has folder | — | ✅ Curriculum PDF | 📤 Upload available |
| **CO-6K** | Check folder | — | — | ✅ Has folder | — | ✅ 10 subject syllabus PDFs | 📤 **Upload all syllabus PDFs** |

### K Scheme — Other Branches (Check Similar Pattern)

Most K Scheme branch folders follow the same sub-folder structure. For each `{Branch}-{Sem}K` folder:

```
Open folder → Look for:
├── PYQs\           → Upload if exists
├── Model Answers\   → Upload if exists
├── Notes\           → Upload if exists
├── Question Banks\  → Upload if exists
├── Manuals\         → Upload if exists (Blank or Solved)
└── Root *.pdf       → Likely syllabus/curriculum → Upload
```

> **💡 TIP:** Not every semester of every branch has every resource type. Just upload what's actually there. Empty folders = nothing to upload.

---

## 8. File Naming Conventions

### How MSBTE Names Files

Most files in the directory follow this pattern:
```
[SubjectShortName] [Session] [SubjectCode].pdf
```

**Examples:**
```
DSU S-25 313301.pdf       → DSU, Summer 2025, Subject Code 313301
OOP W-24 313304.pdf       → OOP, Winter 2024, Subject Code 313304
DMS W-24 313302.pdf       → DMS, Winter 2024, Subject Code 313302
DSU S-19 Model Answer.pdf → DSU Model Answer, Summer 2019
```

### Understanding MSBTE Subject Codes

| Scheme | Code Format | Example |
|--------|-------------|---------|
| **K Scheme** | 6 digits (31xxxx) | `313301` = Data Structure Using C |
| **I Scheme** | 5 digits (22xxx) | `22317` = Data Structure Using C |

#### K Scheme Subject Codes (Verified from Directory):
| Code | Subject | Short Name |
|------|---------|-----------|
| 311302 | Basic Mathematics | BMS |
| 311303 | Communication Skills English | CSE |
| 311305 | Basic Physics | BPH |
| 313301 | Data Structure Using C | DSU |
| 313302 | Database Management System | DMS |
| 313303 | Digital Techniques & Electronics | DTE |
| 313304 | Object Oriented Programming Using C++ | OOP |
| 315301 | Management | MGT |
| 316004 | Capstone Project | CPR |
| 316005 | Client Side Scripting | CSS |
| 316006 | Mobile Application Development | MAD |
| 316313 | Emerging Trends in CO & IT | ETI |
| 316314 | Software Testing | ST |
| 316315 | Digital Forensic & Hacking Techniques | DFH |
| 316316 | Machine Learning | ML |
| 316317 | Network & Information Security | NIS |

### MSBTE Exam Session Naming Convention

| Code | Full Name | Exam Months |
|------|-----------|------------|
| S-25 | Summer 2025 | May/June 2025 |
| W-24 | Winter 2024 | November/December 2024 |
| S-24 | Summer 2024 | May/June 2024 |
| W-23 | Winter 2023 | November/December 2023 |
| S-22 | Summer 2022 | May/June 2022 |
| W-19 | Winter 2019 | November/December 2019 |
| S-19 | Summer 2019 | May/June 2019 |

---

## 9. Quality Checklist Before Uploading

### ✅ Run Through This Checklist for EVERY File

| # | Check | Action if FAIL |
|---|-------|---------------|
| 1 | **File opens correctly** — Open the PDF and verify it's not corrupted | Skip the file, note it for owner |
| 2 | **Content is readable** — Text is clear, scans are not blurry | Skip if unreadable |
| 3 | **Correct subject** — Subject code in filename matches the folder | Re-check and correct before upload |
| 4 | **Correct scheme** — K Scheme material must go under K Scheme on website | Double-check code format (6 digits = K, 5 digits = I) |
| 5 | **Correct semester** — Verify semester number from folder name | Cross-check with syllabus document |
| 6 | **Not a duplicate** — Check if same content already uploaded | Skip if already on website |
| 7 | **PDF format preferred** — If DOCX and PDF both exist, upload only PDF | Skip DOCX |
| 8 | **Not a temp file** — Filename doesn't start with `~$` | DELETE or skip |
| 9 | **Content is relevant** — Not a timetable, evaluation sheet, or calendar | Skip if irrelevant |
| 10 | **File size reasonable** — Under 25MB ideally | Compress using [ilovepdf.com/compress_pdf](https://www.ilovepdf.com/compress_pdf) or ask owner |
| 11 | **Correct resource type** — Selecting the right type (Notes/PYQ/Model Answer etc.) | Double-check before confirming upload |

---

## 10. Content Update Schedule

### Initial Upload Timeline (5 Weeks)

| Week | Task | Details | Priority |
|------|------|---------|----------|
| **Week 1** | K Scheme → Computer Engg (CO) | All 6 semesters, all resource types | 🔴 CRITICAL |
| **Week 1** | K Scheme → Shared Sem 1-2 books | Upload under all relevant branches | 🔴 CRITICAL |
| **Week 2** | K Scheme → Info Tech (IF), Electrical (EE) | All 6 semesters each | 🟡 HIGH |
| **Week 3** | K Scheme → Mechanical (ME), Civil (CE), Electronics (EJ) | All 6 semesters each | 🟡 HIGH |
| **Week 3** | K Scheme → AI/ML (AN) | All 6 semesters | 🟠 MEDIUM |
| **Week 4** | K Scheme → Remaining (AE, CH, PG, TR) | All 6 semesters each | 🟠 MEDIUM |
| **Week 5** | I Scheme → Sem 5 & 6 (if approved) | PYQs & Model Answers only | 🟢 LOW |
| **Week 5** | F Scheme → Syllabus/Curriculum only | All branches, all semesters | 🟢 LOW |

### Ongoing Maintenance (After Initial Upload)

| When | What to Do | How |
|------|-----------|-----|
| **After every MSBTE exam** (June & December) | Collect and upload new PYQ papers | Get from MSBTE website or student submissions |
| **When model answers are released** (1-2 months post-exam) | Upload official model answers | Check MSBTE portal |
| **Start of new academic year** (July) | Check for syllabus/curriculum changes | Compare with previous year |
| **Quarterly** | Remove outdated or incorrect resources | Check user reports, if any |
| **Monthly** | Check for user-uploaded content quality | Review community uploads via `/upload` page |
| **When new K Scheme batches advance** | Ensure next-semester content is ready | Proactively source PYQs and notes |

---

## 11. Troubleshooting & Escalation

### Common Issues & Solutions

| # | Issue | Solution |
|---|-------|---------|
| 1 | Can't find upload/admin page | Go to `/upload`. If no access, ask owner for admin credentials. |
| 2 | Don't know which scheme a file belongs to | Check subject code: **6 digits (31xxxx) = K Scheme**, **5 digits (22xxx) = I Scheme** |
| 3 | File is too large to upload (>25MB) | Compress PDF at [ilovepdf.com/compress_pdf](https://www.ilovepdf.com/compress_pdf). If still too large, contact owner. |
| 4 | Not sure if a resource should be uploaded | **When in doubt, DON'T upload.** Ask the owner first. |
| 5 | Found duplicate files in directory | Compare file sizes. Upload only the original (without `(1)` in name). |
| 6 | Subject/branch not listed on website | The subject may not be configured yet. Contact owner to add it. |
| 7 | Can't determine semester for I Scheme files | I Scheme subject codes are semester-specific. Check the curriculum PDF in each semester folder. |
| 8 | Website shows errors during upload | Take a screenshot, note the error message, and contact owner. |
| 9 | Found Marathi-language content | There are folders like `Learning Material In Marathi-English` and `Marathi Books`. **Ask owner** if these should be uploaded (niche audience). |
| 10 | Found content not in the directory | If students submit new content, verify quality first, then upload. |

### 📞 When to Contact the Owner Immediately

Contact the owner if:

1. ❓ You don't have upload/admin access to the website
2. ❓ A branch or semester is missing from the website navigation
3. ❓ You find content that might be copyrighted (full textbook scans from publishers like Nirali/Technical Publications)
4. ❓ You're unsure whether I Scheme Sem 5/6 should still be uploaded
5. ❓ Files larger than 50MB that can't be compressed
6. ❓ You find resources for a branch/scheme not in the local directory
7. ❓ The website shows errors during upload
8. ❓ You need clarification on Marathi-language materials
9. ❓ Subject codes don't match between directory files and website listings
10. ❓ Students report incorrect content on the website

**Contact:** Telegram — [@Durvesh1209](https://t.me/Durvesh1209)

---

## Quick Reference Card

```
╔═══════════════════════════════════════════════════════════╗
║            MSBTE Navigator — Quick Reference              ║
╠═══════════════════════════════════════════════════════════╣
║                                                           ║
║  UPLOAD PRIORITY ORDER:                                   ║
║  1. K Scheme PYQs & Model Answers (ALL branches)          ║
║  2. K Scheme Notes & Question Banks                       ║
║  3. K Scheme Syllabus / Curriculum                        ║
║  4. K Scheme Lab Manuals (blank & solved)                 ║
║  5. I Scheme Sem 5-6 only (ask owner first!)              ║
║  6. F Scheme (Working Professionals flexible diploma)      ║
║                                                           ║
║  NEVER UPLOAD:                                            ║
║  ✗ Timetables           ✗ Evaluation sheets               ║
║  ✗ ~$ temp files         ✗ ZIP archives                   ║
║  ✗ Duplicate (1) files   ✗ Academic calendars             ║
║  ✗ DOCX when PDF exists  ✗ README files                   ║
║  ✗ Micro project docs    ✗ Mock exam link PDFs            ║
║                                                           ║
║  WEBSITE FLOW:                                            ║
║  /notes → Scheme (I/K/F) → Branch → Semester → Subject    ║
║                                                           ║
║  SUBJECT CODE FORMAT:                                     ║
║  K Scheme = 6 digits (e.g., 313301)                       ║
║  I Scheme = 5 digits (e.g., 22317)                        ║
║                                                           ║
║  KEY URLS:                                                ║
║  Website:  https://msbtenavigator.com                     ║
║  Library:  https://msbtenavigator.com/notes               ║
║  Upload:   https://msbtenavigator.com/upload              ║
║  Login:    https://msbtenavigator.com/login               ║
║                                                           ║
║  CONTACT OWNER: Telegram @Durvesh1209                     ║
╚═══════════════════════════════════════════════════════════╝
```

---

> **Document Version:** 1.0  
> **Last Updated:** 28 June 2026  
> **Next Review:** After first upload cycle is complete  
> **Author:** Auto-generated from website & directory analysis
