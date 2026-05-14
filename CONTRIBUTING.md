# Contributing to maanas.fyi

> The workflow that runs this project. If you're picking up work — yours, mine, or a future Claude instance's — this is where to look first.

---

## What kind of project this is

maanas.fyi is a living library, not a static portfolio. It grows over time and compounds. Work happens in small batches: an issue gets opened, a branch gets cut, a PR is reviewed on its Vercel preview, the branch merges to `main`, Vercel auto-deploys to the live site. The project itself is part of the proof — how it's run matters as much as what it ships.

---

## Where to look first

Five surfaces. Each answers a different question:

| Surface | Answers | Visibility |
|---|---|---|
| `now.md` | What am I doing *today*? Capped at 3 items. | Private |
| GitHub open issues | What's actively in the queue? | Public |
| GitHub milestones | What's the next shippable chunk? | Public |
| `future-roadmap.md` | What's queued for later, with explicit triggers? | Private |
| `decisions.md` | What did we decide, and why? | Private |

If you're picking up work and don't know where to start: check the pinned issue and the v1.x milestones on this repo. Those are the active public surfaces.

---

## The graduation protocol

The roadmap holds two kinds of items: **active** and **trigger-based**.

- **Active items** live as GitHub issues, assigned to a milestone, labeled, and worked.
- **Trigger-based items** stay in the private roadmap with an explicit condition (e.g., *"5 essays published"*, *"Vercel Analytics shows blind spots"*). They are *queued, not abandoned, and not active*.

When a trigger fires, an item graduates: a new GitHub issue is opened with the trigger condition restated in the body, it's assigned to a milestone, and the roadmap entry is marked activated (not deleted — the trigger note becomes the breadcrumb).

The discipline this enforces: items don't start before their trigger. The empty backlog where they *could be* is the feature.

---

## What goes where

- **Public** (issues, milestones, `ROADMAP.md`, `CONTRIBUTING.md`, code): site architecture, principles, active backlog, milestone direction, anti-features.
- **Private** (operating vault): pricing detail, trigger conditions, dated decisions, personal context, self-knowledge caveats.

The public lens shows the work and the direction. The private layer holds the discipline behind it.

---

## Working conventions

- **Branches:** feature branches off `main`, named by intent (`restructure-home-evidence`, `essay-21-in-21`).
- **PRs:** opened against `main`. Vercel auto-builds a preview URL on every push. Review on the preview, not in diffs.
- **Commits:** `<verb>: <one-line summary>` (`ship: portfolio v1`, `add: MMB case study`). Reference the issue: `closes #N` or `refs #N`.
- **Issues:** every issue closes via a commit or PR that references it. No silent closes.
- **Releases:** tagged at meaningful chunks (typically when a milestone closes). Each release links back to the milestone scope.

---

## Principles this project holds itself to

- **Library, not destination.** Every page is a future writing surface.
- **Role → Project → Story.** Three depths for three readers.
- **No build step.** Static HTML, vanilla CSS/JS. Add complexity only when the content model demands it.
- **Outcomes lead, process supports.** Case studies start with numbers.
- **Cadence over completeness.** Empty future slots are a feature.
- **Calm-confident voice.** Observational, scale-anchored, specific.

See [ROADMAP.md](./ROADMAP.md) for shipping direction and architecture detail.

---

## A note on the tools

This repo is co-maintained with Claude Code. A separate operating-context vault holds longer-form discipline that future Claude instances read at session start. The continuity helps — but every PR is still reviewed in human eyes via Vercel preview before it merges to `main`. The discipline lives on people, not on the tools.
