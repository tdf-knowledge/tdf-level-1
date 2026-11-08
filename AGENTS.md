---
level: "L1"
status: "unverified"
verified_by: "nobody yet"
verified_on: null
sources:
  - "Linked public sources in PUBLIC_REGISTER.md; checks recorded 29 October 2026"
last_updated: "2026-11-08"
---

# Instructions for an assistant

TDF is Traditional Dream Factory, a regenerative community in Abela, Santiago do Cacém, Alentejo, Portugal. This repository is **L1: public**. It holds only facts that anyone can already read on a public page, each with a link to that page. People do not need to browse GitHub to ask about TDF.

## Find and use knowledge

- Read `PUBLIC_REGISTER.md`. Every row has a source link and a status.
- Cite the row number and the source link. Say whether the source is TDF's own site (`W-`, `B-`: what TDF says) or press and directories (`P-`, `D-`: reports of it).
- "public-source check recorded 29 Oct 2026; unverified" means someone opened the page that day and saw the claim there. It does not mean TDF reviewed it or that it is true. Where public pages disagree, the register lists the conflict; do not pick one value without a current source.
- Numbers change. Check the linked page when a figure matters.

## What is not here

Non-public TDF finances, personal or health detail about named people, passwords, contacts and anything not on a public page are not in this repository. If someone asks for them, say they are not available at this level. Do not guess who holds them.

## How the levels work

This section is the same in every TDF level repository.

| Level | Repository | Who reads it | GitHub team |
|---|---|---|---|
| L1 | [tdf-level-1](https://github.com/tdf-knowledge/tdf-level-1) (public) | Anyone | none needed |
| L2 | `tdf-level-2` (private) | Volunteers | L2 readers |
| L3 | `tdf-level-3` (private) | Residents and other admitted people | L3 readers |
| L4 | `tdf-level-4-current` (private) | Citizens and the team | L4 readers |
| L5, L69 | not on GitHub | specifically involved people / Jaggy only | stay Mac-only |

- **One level = one repository = one GitHub team.** A team reads its own level and every level below it, so "L4 readers" read L1 to L4. Adding a person to a team is the whole access step.
- **A public fact may appear at every level.** For example, that Sam Delesque is a co-director is on TDF's public team page, so it is L1 and may also be repeated at L2, L3 and L4. Repeating it higher does not make it secret, and a public fact is never withheld from a lower level because it also appears higher.
- **Material never moves down.** A lower level never holds anything that is not allowed at that level. When unsure, withhold it and ask for a review at the higher level.
- **Never put L5 or L69 here.** Non-public finances, personal detail about named people, passwords and anything Jaggy-only stay on the Mac and out of every GitHub repository.
- **The repository grant is the real access boundary.** A file's `level` is its minimum intended audience.

## Where things live

- `PUBLIC_REGISTER.md`: the register of already-public TDF facts, each with its source link and status.
- `README.md`: what this repository is and how to read the register.

## How to propose a change

Open an issue at https://github.com/tdf-knowledge/tdf-level-1/issues/new with the row number, the exact claim, the proposed replacement, a public source link and its date. If you have write access, change files through a pull request. A pull request that adds a fact must link a public page and may not include anything from a higher level. An issue or pull request is a proposal, not verification. Never force-push or rewrite history.
