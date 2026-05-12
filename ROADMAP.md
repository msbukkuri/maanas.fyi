# Roadmap

> Where this project is, where it's going, and the principles that drive what gets built next.

---

## Where this is now

**v1.0 — Portfolio shipped.** Live at [maanas.fyi](https://maanas.fyi). Single-page home plus the first depth pages: full `/experience/` index, `/experience/ep/` role page, and `/experience/ep/mmb/` flagship case study. Static HTML on Vercel; no build step.

See the [v1.0 release notes](https://github.com/msbukkuri/maanas.fyi/releases/tag/v1.0) for what shipped.

---

## What's shipping next

The work is grouped into scope-bound milestones (no dates — cadence over deadlines):

### [v1.1 — Polish & infra](https://github.com/msbukkuri/maanas.fyi/milestone/1)

Tighten the foundation before adding more content. Vercel Analytics, missing logos, og-image for social shares, Lighthouse audit, custom 404, sitemap and SEO basics.

### [v1.2 — Depth content](https://github.com/msbukkuri/maanas.fyi/milestone/2)

The first Field Notes essay and the second wave of EP case studies (SmartID, Claude Enterprise rollout). The home page's Selected Work cards point at this work; v1.2 is where the promises become real artifacts.

### [v1.3 — Library expansion](https://github.com/msbukkuri/maanas.fyi/milestone/3)

The remaining `/experience/` role pages — Chirp, GUESS, HYFN, Appriss Retail, and the earlier engineering era — plus the `/research/` tree where the DBA thesis frame lives in depth. After v1.3, the site is the queryable career library the architecture has intended from day one.

---

## Architecture principles

These are the rules the site holds itself to. They're load-bearing decisions, not preferences.

- **Library, not destination.** Every page is a future writing surface. Every story can be excerpted with a backlink. The site grows over time and compounds; it isn't a single artifact polished once.

- **Role → Project → Story.** Three depths for three readers — recruiter, hiring manager, peer. Same content surfaces at the right level for who's reading. `/experience/[role]/` for recruiter skim, `/experience/[role]/[project]/` for hiring-manager depth, story subsections and `/writing/` for peer-level vetting.

- **No build step.** Static HTML, vanilla CSS, vanilla JS. One `styles.css`, one `app.js`, shared across all pages. Add complexity only when the content model demands it — and that bar is high.

- **Outcomes lead, process supports.** Case study pages start with numbers and what shipped. Process documentation comes after, because the question on the table is "did the work land," not "how was the work done."

- **Cadence over completeness.** The empty future slots are a feature. Consistent shipping is the only portfolio that compounds. Coming-soon cards with specific dates beat exhaustively-documented finished sites.

- **Calm-confident voice.** Observational, scale-anchored, specific. No manifestos, no "and you don't" framing, no productivity-blog-coach vibes.

---

## What's beyond v1.3 (trigger-based, not scheduled)

Some directions are clearly in scope but explicitly *not* on a near-term schedule. Each waits on a trigger — a real condition that suggests the time has come.

- **Cross-platform syndication (POSSE pattern).** Publish on Own Site, Syndicate Elsewhere. Stories on this site get excerpted to LinkedIn (and eventually X/Substack) with a link back to the canonical source. **Trigger:** five Field Notes essays live.

- **Services layer.** A page or two surfacing coaching, fractional, and advisory offerings. **Trigger:** the live site is generating inbound interest from people who've read a story and want to talk.

- **Newsletter.** A weekly or biweekly digest of recent thinking. **Trigger:** 10+ essays live and a clear voice/cadence has emerged. Starting one without sustainable content velocity is a known failure pattern.

- **DBA thesis-to-essay pipeline.** As dissertation chapters reach quality worth showing, they get adapted into Field Notes. **Trigger:** an active dissertation section reaches "interesting in public" quality.

- **Prompt library + community contributions.** Searchable index of prompts and skills mentioned across essays. **Trigger:** enough prompts across articles to warrant a dedicated index, and validated demand for community contribution.

- **Course / LMS.** A separate application at `/courses` for structured product-management content. **Trigger:** explicit prioritization as a revenue or brand-building stream.

If any of those triggers fire — open an issue and let it become real work. Until then, the file's a reference, not an action list.

---

## What this project deliberately isn't

Half of operating discipline is what you refuse to build. The following directions are explicitly off-list — not "we'll consider it," but *no, not on this project*:

- **A custom CMS.** Markdown files in the repo are the CMS. The day that breaks is the day to consider an alternative; until then, no.
- **A framework migration (Next.js, Astro, SvelteKit, etc.).** The site is static HTML. It stays static unless the content model fundamentally changes — and "fundamentally" means more than "I read a blog post about Next.js."
- **A/B testing infrastructure.** Premature for this level of traffic. A site that doesn't have 10k monthly visitors doesn't need experimentation tooling.
- **Multi-language support.** Not relevant to the target audience.
- **A native mobile app.** Mobile-responsive web is sufficient.
- **Forum or community features.** This isn't a community platform. The repo is the only "community" surface, and it's open by design.

If any of these surface again in conversation, the default response is: *not now, possibly never, capture the conversation, move on.*

---

## Why this is here

The site argues "VP Product who builds, in the AI-augmented era." A public roadmap is part of the argument. Anyone landing on this repo sees a project being run — versioned releases, scoped milestones, open issues, the principles driving the choices — instead of a static one-shot deliverable.

The roadmap is itself a working artifact: it gets updated when a milestone closes, when a trigger fires, or when a principle changes. If something here goes stale for too long, that's a signal to revisit.

---

## How to engage

- Browse the [open milestones](https://github.com/msbukkuri/maanas.fyi/milestones) for what's shipping next.
- Browse [open issues](https://github.com/msbukkuri/maanas.fyi/issues) for the active backlog.
- Have a thought, a correction, or a request? [Open an issue](https://github.com/msbukkuri/maanas.fyi/issues/new) or reach out via [maanas.fyi/#contact](https://maanas.fyi/#contact).
