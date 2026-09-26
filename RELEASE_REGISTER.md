# My Life Planner Release Register

| Release | Channel | Based on | Status | Date | Notes |
|---|---|---|---|---|---|
| v54bj | Development | — | Frozen confirmed baseline | 2026-09 | Protected historical baseline. |
| Tester 1.0 | Tester | v54bj | Superseded | 2026-09-23 | First clean-install tester release. |
| Tester 1.1 | Tester | Tester 1.0 + Help refresh | Superseded | 2026-09-24 | Added First Use / Quick Start and refreshed Help navigation. |
| Development v54br | Development | v54bq | Confirmed in normal iPhone use | 2026-09-26 | Correct version display; Brain Inbox attachment save/persistence confirmed. |
| Development v54bs | Development | v54br | Promotion source | 2026-09-26 | Backup compatibility repair: automatic recovery snapshots include attachment bytes. |
| Tester 1.2 | Tester | Development v54bs | Ready for owner verification | 2026-09-26 | Timeline Schedule, Brain Inbox IndexedDB storage, self-contained manual/automatic backups, Help/Quick Start retained. |

## Release rules
- Never develop directly on Tester or Stable.
- Tester releases are complete packages promoted from accepted Development behaviour.
- Tester must start blank with no personal seeded planner information.
- Tester update behaviour must remain isolated from Development.
- Before issue, verify version display/references everywhere, JavaScript syntax, JSON validity, package completeness, backup compatibility and accepted regression behaviours.
