# Faceless YouTube channel — planning repo

Working repo for a faceless, long-form YouTube channel: **business post-mortems** delivered through a SaaS/product-dashboard visual frame, animated in Remotion.

---

# ▶ WHERE WE LEFT OFF

**If you were just told "continue" — read this section, then [notes/channel-bible.md](notes/channel-bible.md), then pick up at "Next action" below.**

**Last worked on:** 2026-07-25

### Status
Planning is **complete and locked**. Nothing has been produced yet. **No YouTube channel exists**, no recording has been done, no Remotion project has been set up. The next step is the first build task.

### Decided — do not relitigate these
| Decision | Value |
|---|---|
| **Premise** | Every business/economy/institution is a product. When one breaks, we run the post-mortem. |
| **Purple cow type** | Alternative context — the frame *is* the analysis (not decoration) |
| **Niche** | Business / economics failure analysis, professional audience (high RPM) |
| **Format** | Faceless, long-form, 15–25 min · **episode 001 is 10–12 min (~1,600 words)** |
| **Narration** | **Record own voice directly.** Voice cloning was tried and failed — it collapsed a Lebanese English accent toward Indian English. Do NOT use stock TTS: this audience calls out AI narration in comments. |
| **Visuals** | Remotion, SaaS/dashboard aesthetic, 40–60 visual states per 20 min |
| **Series** | **The Graveyard** — numbered archive, `POST-MORTEM #001` on every thumbnail |
| **Episode 001** | **Chegg** — chosen because every claim traces to SEC filings, so it's legally safe for a channel with no standing yet |

### Still open — needs the user's call
- **Channel name.** Recommendation: **Root Cause**, `@rootcausehq`. Alternatives: Post-Mortem, SEV-1, The Incident Report.
- **Upload cadence.** Model is low volume, high value — Modern MBA ships 76 videos in 5 years.

### ▶ Next action
Two tracks, either order. Remotion is the longer lead time.

1. **Set up Remotion** — Node.js + Remotion in this repo (say yes to skills). Build the incident-report components: `StatusHeader`, `SeverityBadge`, `Timeline`, `RootCauseTree`, `MetricsDashboard`, `TerminalLog`, `Callout`. They must **hold and evolve over 15–30 seconds** (sequential reveal, highlight-on-cue, slow push) — not one-shot cards.
2. **Session zero** — recording setup and calibration, ~90 minutes, no script. Full procedure in [notes/narration-guide.md §2](notes/narration-guide.md). Buy list is ~$150–250; the mic is a Samson Q2U.

Then: research and write episode 001 (Chegg), verifying every number against primary filings.

### Practical state
- **vidIQ credits: 113.** Renewable pool refills **3 Aug 2026**. Each search costs 5, so ~22 queries available.
- No channel authenticated with vidIQ, so AI-coach personalisation is unavailable. Keyword-driven search still works.
- Git identity is set **locally in this repo only** as `Aysar06 / aisar@goempros.com`.

---

## Start here

| File | What it is |
|---|---|
| **[notes/channel-bible.md](notes/channel-bible.md)** | ⭐ The locked plan — premise, avatar, promise, title system, episode template, visual system, risks |
| [notes/episode-slate.md](notes/episode-slate.md) | First 10 episodes, ranked, with the outlier data behind them |
| [notes/narration-guide.md](notes/narration-guide.md) | How to record the voiceover — setup, delivery, non-native clarity, time budget |
| [notes/narration-research-sources.md](notes/narration-research-sources.md) | 172 references behind the narration guide |
| [notes/monetization-safety.md](notes/monetization-safety.md) | Risk register and production rules |
| [notes/niche-research-2026-07-25.md](notes/niche-research-2026-07-25.md) | vidIQ data behind the niche choice |
| [notes/vidiq-playbook.md](notes/vidiq-playbook.md) | Rules extracted from 7 vidIQ transcripts, with cross-transcript synthesis |
| [transcripts/](transcripts/) | The 7 source transcripts, cleaned |

---

## The plan in one page

**Premise.** Every business, economy and institution is a product. When one breaks, we run the post-mortem — severity, timeline, root cause, contributing factors, resolution.

**Promise.** *Subscribe because every video takes something that failed and runs the post-mortem it never got — with receipts, on the record.*

**Viewer.** Operations/middle management, has sat in the meeting where the obviously wrong decision got approved. Not cynical — **unheard**. Built from real comment mining, not demographics.

**Why this works.** Faceless business explainers are saturated *in one specific format* — whiteboard animation — and that format doesn't pay: 166K subs and 425 videos earning $331/month. The differentiated slot in the same niche pays roughly 19× per video (Primate Economics: 564K subs from 26 videos). The incident-report frame is unoccupied and native to the chosen aesthetic.

**The doctrine underneath everything:** non-interchangeability at every altitude — premise, channel, promise, packaging, edit — compounded by consistency over time.

---

## Working rules

- **Idea → packaging → edit.** Never inverted.
- **Copy the idea, never the execution.**
- **The lens test.** *"This topic without the incident-report frame is just ___."* If the answer is "the same video, uglier," kill the episode.
- Script length is arithmetic: `target minutes × 150 words`. Record at 140–150 WPM.
- **No claim ships unsourced.** Attribute anything contested, on screen. This is simultaneously the differentiator, the defamation defence, and the advertiser-suitability fix.
- **Never generate synthetic footage or audio of a real person or event.** Charts and diagrams only. This keeps us permanently outside YouTube's AI disclosure requirement.
- Avoid **"bankrupt"** and **"rise and fall"** in titles and tags — those phrasings sit in a semantic neighbourhood dominated by AI drama farms.
- **Low volume, high value.** Do not try to out-publish the content farms — that is the $331/month strategy.
