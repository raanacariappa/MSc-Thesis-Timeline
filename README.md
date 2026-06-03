# MSc Motorsport Engineering — Thesis Timeline

**Cranfield University | Individual Research Project A25**  
**Topic:** Telemetry-Driven Tyre Thermal & Cold Pressure Recommendation Model for GT3 Motorsport  
**Period:** 1 June 2026 → 31 August 2026

---

## 📅 Gantt Chart

```mermaid
%%{init: { 'logLevel': 'debug', 'theme': 'base', 'themeVariables': { 'fontSize': '16px', 'ganttBarHeight': 28, 'gridLineStartPadding': 35, 'sectionFontSize': '16px', 'numberSectionStyles': 5 }, 'gantt': {'barHeight': 28, 'barGap': 6, 'topPadding': 50, 'sidePadding': 75, 'displayMode': 'compact'} }}%%
gantt
    title MSc Thesis Timeline — June to August 2026
    dateFormat  YYYY-MM-DD
    axisFormat  %d %b

    section Research & Scope
    Refine aim & objectives          :done,    obj,   2026-06-01, 2026-06-07
    Literature review                :active,  lit,   2026-06-01, 2026-06-30
    Literature review chapter due    :crit,    litdue,2026-06-30, 1d

    section Data & Method
    Data audit & preprocessing       :         data,  2026-06-08, 2026-06-28
    Method formulation               :         meth,  2026-06-15, 2026-07-12

    section Implementation
    MATLAB / Simulink build          :         build, 2026-06-22, 2026-07-26
    Validation & sensitivity checks  :         val,   2026-07-13, 2026-08-09

    section Analysis & Writing
    Results analysis                 :         res,   2026-07-27, 2026-08-16
    Write thesis chapters            :         write, 2026-07-06, 2026-08-23

    section Final
    Final edits & formatting         :crit,    edit,  2026-08-24, 2026-08-31

    section Deadlines & Reviews
    Literature review chapter due    :crit, milestone, litmil, 2026-06-30, 0d
    Review 1 (TBC)                   :crit, milestone, r1,     2026-06-29, 0d
    Review 2 (TBC)                   :crit, milestone, r2,     2026-07-27, 0d
    Draft complete                   :milestone,       m2,     2026-08-10, 0d
    Submission deadline              :crit, milestone, m3,     2026-08-31, 0d
```

---

## 📋 Task Summary

| # | Task | Start | End | Duration | Section |
|---|------|-------|-----|----------|---------|
| 1 | Refine aim & objectives | 01 Jun | 07 Jun | 7 days | Research & Scope |
| 2 | Literature review | 01 Jun | 30 Jun | 30 days | Research & Scope |
| 3 | Data audit & preprocessing | 08 Jun | 28 Jun | 21 days | Data & Method |
| 4 | Method formulation | 15 Jun | 12 Jul | 28 days | Data & Method |
| 5 | MATLAB / Simulink build | 22 Jun | 26 Jul | 35 days | Implementation |
| 6 | Validation & sensitivity checks | 13 Jul | 09 Aug | 28 days | Implementation |
| 7 | Results analysis | 27 Jul | 16 Aug | 21 days | Analysis & Writing |
| 8 | Write thesis chapters | 06 Jul | 23 Aug | 49 days | Analysis & Writing |
| 9 | Final edits & formatting | 24 Aug | 31 Aug | 8 days | Final |

---

## 🔖 Key Deadlines & Reviews

| Event | Date | Notes |
|-------|------|-------|
| 🔴 Literature review chapter due | 30 Jun 2026 | Chapter submitted before end of June |
| 🟡 Review 1 | 29 Jun 2026 | TBC — supervisor progress check |
| 🟡 Review 2 | 27 Jul 2026 | TBC — 4 weeks after Review 1 |
| 🟠 Draft complete | 10 Aug 2026 | Full draft ready for supervisor review |
| 🔴 Submission deadline | 31 Aug 2026 | Final thesis submitted |

---

## 📁 Project Context

- **Vehicle:** Porsche 992.1 GT3 Cup
- **Tool:** MATLAB / Simulink tyre thermal model
- **Data source:** AiM RaceStudio 3 telemetry export (.mat)
- **Model:** Two-node tyre thermal model (tread + carcass) linked to gas-law pressure prediction
- **Output:** Four-corner cold tyre pressure recommendations (FL, FR, RL, RR)

---

*Last updated: June 2026*
