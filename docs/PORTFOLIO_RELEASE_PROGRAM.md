# Groundstate portfolio release program

This program turns the current green prototype baseline into installable, testable products. Each repository remains standalone. Groundstate ecosystem connections are optional adapters, never login requirements.

## Delivery order

| Wave | Product | Exit condition |
|---|---|---|
| 1 | BonePile | Inventory import drives inventory, Maker Center, chemistry, matching, and safe update behavior |
| 2 | TradeRoot, WiXness, SignalWall | Account flow, media/feed flow, and session recovery work through real user journeys |
| 3 | GhostMap, EchoWalk, CareGrid, StaffRoot | Offline operation, device lifecycle, persistence, backups, and sensitive-data handling are tested |
| 4 | ThothScript, Ouiji Chat, IuPetra | Primary workflows, import/export, network failure handling, and packaging are tested |
| 5 | Website and shared configuration | Product status, screenshots, downloads, release feed, and contributor entry points are consistent |

## Portfolio requirements

1. Every product runs without Groundstate Admin Center.
2. Integrations use an explicit opt-in connector boundary.
3. Personal data and local databases are never committed.
4. Each supported platform has a documented launcher or packaged build.
5. CI exercises the packaged application or real primary flow where practical.
6. Networked features cache useful results and degrade cleanly offline.
7. User-visible versions and release notes match the distributed artifact.

## Product targets

- **BonePile:** resilient CSV/XLSX/ODS import, normalized inventory, duplicate review, readiness scoring, maker-source cache, chemistry compatibility, safe packaged updates.
- **TradeRoot:** create-account/sign-in recovery, roles, durable inventory and sales, backup/restore.
- **WiXness:** account creation, uploads, feed/reactions, batched notifications, moderation and privacy controls.
- **SignalWall:** livestream adapters, transcript capture, snap layout, saved sessions and clear unsupported-source handling.
- **GhostMap:** unified offline tactical planning and opt-in online map/logistics layers.
- **EchoWalk:** hardware calibration, permission onboarding, foreground/background safety, accessible controls.
- **CareGrid:** import integrity, append-only clinical audit, backup validation and explicitly non-clinical demo mode.
- **StaffRoot:** credential migration, encrypted sensitive fields, payroll validation, employee/admin separation.
- **ThothScript:** project persistence, safe execution boundaries, export and recovery.
- **Ouiji Chat:** standalone/local identity, reconnect behavior, message persistence and moderation.
- **IuPetra:** reproducible analysis runs, evidence provenance, export and error reporting.
- **Website:** accurate product status, install links, release feed, BonePile demo and contributor routes.
- **Shared configuration:** common security, contribution, issue, release and ownership conventions.

## Merge policy

Each product remains one independently reviewable pull request. Merge only after its existing CI, update-health gate, release checklist, and manual smoke test pass.
