# quo-warranto-resources
Quo Warranto project — reference documents and build assets
# quo-warranto-resources

Private reference repository for the **Quo Warranto Project** — a civic legal advocacy initiative documenting officials of Florida's 18th Judicial Circuit and supporting a grassroots national movement to hold public officials accountable to their oath of office.

**Live site:** [quo-warranto.org](https://quo-warranto.org)
**Active case:** *Pantle v. Crawford* · 6:24-cv-01591-CEM-LHP · M.D. Florida
**Appeal:** 25-13368-CC · 11th Circuit · Active

---

## What This Repository Contains

Reference documents that support the site build and research — fetched directly by Claude during work sessions to avoid upload limits.

```
quo-warranto-resources/
├── constitutions/
│   ├── national/          — U.S. organic + de facto documents
│   ├── florida/           — Florida 1838 organic + current constitution
│   ├── washington/        — Washington State organic + current constitution
│   └── [state]/           — One folder per state as documents are added
├── form-6/
│   └── [judge-last-name]/ — Financial disclosure PDFs by judge
├── audits/                — FL Auditor General reports
├── evidence/              — Docket PDFs, PACER records, USPS confirmations
└── reference/             — Academic and legal reference documents
```

---

## Key Reference Documents

### Constitutions
| Document | Description | Location |
|---|---|---|
| Secret Proceedings and Debates (1839) | Robert Yates' notes from inside the 1787 Constitutional Convention — the framers' actual private debates. Library of Congress copy. 356 pages. | `constitutions/national/` |
| American Constitution (World Book, 2004) | Full text + annotated version of Constitution and all 27 amendments | `constitutions/national/` |
| The Constitution and the Public Trust — Natelson | Buffalo Law Review Vol. 52 (2004). Fiduciary/trustee framework for government officials. Bridges the organic Constitution to the oath cases. | `reference/` |
| Washington State Organic Constitution | Original 1889 statehood constitution | `constitutions/washington/` |

### Why the Secret Proceedings Matters
Robert Yates and John Lansing left the Convention and documented what was actually debated — including Hamilton's arguments for executive monarchy, the commercial/banking interests driving proceedings, and the objections that were overruled. Luther Martin's formal dissent to the Maryland legislature is also included. This is the primary source for the "what was intended vs. what we got" framing on the constitution comparison pages.

---

## Active Case Summary

**People's Writ of Quo Warranto** — served via USPS Certified Mail upon 45 named officials:
- 43 judges of Florida's 18th Judicial Circuit (Seminole + Brevard counties)
- Florida House of Representatives Judiciary Committee
- Office of State Courts Administrator (Eric W. Maclure)

**Federal case dismissed** August 29, 2025 (Docket 64) — without leave to amend.
**Appeal filed** September 26, 2025 — currently in jurisdictional hold.
**11th Circuit** recognized Docket 66 as a timely tolling motion (November 5, 2025).
District court has not acted on Docket 66 as of May 2026 — both courts effectively frozen.

---

## How Claude Accesses This Repository

During work sessions, Claude fetches files directly using:
```
https://raw.githubusercontent.com/sp70/quo-warranto-resources/main/[path/to/file]
```

No upload slots consumed. Files are fetched via `web_fetch` with the repository token.

**To start a session with GitHub access:**
```
GitHub: https://github.com/sp70/quo-warranto-resources
Token: ghp_xxxxxxxxxxxx

[paste QW_QUICK_START.md contents]
```

---

## Current Build

Site build is maintained separately as `quo-warranto-vXXX.zip` — versioned ZIP files exchanged between sessions. Current build: **v291**.

Build documents in the site ZIP root:
- `QW_QUICK_START.md` — paste at top of every new session
- `QW_SESSION_HANDOFF_vXXX.md` — full session summary and action items
- `QW_CONSTITUTION_PLAN.md` — constitution archive roadmap
- `QW_GITHUB_SETUP.md` — this repository setup instructions
- `QW_SITE_AUDIT.md` — outstanding issues

---

## Pending Actions

- [ ] Laura Moody — retrieve oath + send certified mail (appointed Dec 2024)
- [ ] Upload Washington State organic constitution to `constitutions/washington/`
- [ ] Fetch Florida 1838 organic constitution and add to `constitutions/florida/`
- [ ] Continue Form 6 reviews — ~15 judges remaining
- [ ] Lessons learned spreadsheet — add to enforcement-tools.html Section IX
- [ ] Constitution comparison pages — build national, Florida, Washington first

---

## Contact

Florida Ethics Commission: Kimberly Holmes · (850) 488-7864 · disclosure@leg.state.fl.us
Pre-2021 Form 6 requests: PO Box Drawer 15709, Tallahassee FL 32317-5709
