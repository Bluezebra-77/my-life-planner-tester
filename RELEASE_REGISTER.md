# My Life Planner — Release Register

| Release | Channel | Built from | Status | Date | Notes |
|---|---|---|---|---|---|
| v54bj | Confirmed baseline | v54bi + Home/Lists repair | Frozen | 2026-09-23 | User-confirmed working baseline. Keep unchanged. |
| Tester 1.0 | Tester / Stable | v54bj | Superseded by Tester 1.1 | 2026-09-23 | Sanitised new-install defaults; no silent Development updates. |
| Tester 1.1 | Tester / Stable | Tester 1.0 + accepted v54bl documentation | Current tester release | 2026-09-24 | First Use HTML guide, refreshed Help Centre, Return-to-Planner navigation; planner logic unchanged. |
| Development v54bk | Development | v54bj | Active | 2026-09-23 | Private branch for ongoing amendments. |

## Rules
- Never develop directly on a Tester/Stable release.
- Development builds can advance through any number of versions.
- A future Tester release is a complete package promoted from one accepted Development build; testers do not need intermediate builds.
- Before promotion, run the protected regression checks and verify upgrade/data preservation from the previous Tester release.
- Tester releases must not contain personal seeded planner data.
