# is-this-ai — verdict on the "Is This AI?" social-brand idea

**Started + delivered 2026-08-05.** Bob's idea: claim the handle **"Is This AI ?"** on every social
platform, post AI-generated video (MiniMax H3 lane), and put an **overlay text on each clip asking
viewers whether it's AI** so the comments fill with argument. Asked "how is the idea?" + /deep-research.

**LIVE: https://oliveroliver10816.github.io/is-this-ai/** (repo oliveroliver10816/is-this-ai, public,
noindex). QA: 200, noindex in served HTML, all 4 load-bearing quotes present, console clean,
0 contrast failures (composited-alpha walker, desktop+mobile), tables scroll inside `.scroller`
while the document does not.

## VERDICT: build it — but the question must be a REVEAL, not a POLL.

Keep the name and the hook. Change the second half of every clip: hold "Is this AI?" for ~3s,
then **answer it and show the tell** (hands, physics, reflection, melting text, audio seam).
That one change converts the format from prohibited to qualifying on every platform at once.

## The four findings

1. **The platform answers the question for you.** TikTok's AI label appears *"below your caption in
   the video"* and *"you cannot edit or remove the label after posting"* (creator-academy
   `ai-generated-content-label`, pub. 2026-04-30). Detection is via C2PA + *"invisible watermarks…
   that only we can read"* — not a choice you make. Not labelling is worse: *"TikTok may take down
   AI-generated content that's not labeled"*, unlabelled realistic AIGC is **FYF-ineligible**, and
   FYF-ineligible ⇒ **not Creator-Rewards-eligible**.
   ⭐ But the label itself is **free**: *"Applying the label will not have an impact on the engagement
   with your content"* / *"will not be demoted or restricted solely because the AI-generated content
   setting is enabled."* So the label is an answer key — fatal to a guessing game, harmless to a
   teaching one.

2. ⭐ **Meta names the exact format as unmonetizable — on 4 independent axes.** Content Monetization
   Policies (`facebook.com/business/help/1348682518563619`), prohibited **formats**: *"**Static image
   polls** — Content posted for the sole purpose of increasing engagement by asking people to react to
   questions posed by the content"* and *"**Text montages** — Content that primarily displays still or
   moving images with overlaid text."* Prohibited **behaviour**: *"**Engagement bait**…"*. And
   original-content guidelines (`…/help/262834734651607`) list *"**Adding only an on-screen text
   caption or title**"* as insufficient minor editorialization.
   ⚠ This is Bob's proven earner. ⚠ FCM is still **invite-only**, no published rate — a new page
   can't enrol; only published route in is Creator Fast Track at **100k+ elsewhere**.
   ⭐ Meta also writes the way through: *"Remixes or overlays that feature your own on-screen presence
   as the focus… and also add new information, commentary, or storyline improvements beyond simply
   narrating what happens."*

3. ⚠ **MiniMax H3 output cannot carry a global brand.** §V.4 forbids distributing/displaying
   **Outputs** outside the Applicable Territory, which **excludes US/EU/UK/KR**. A social account
   publishes to all four by default — there is no per-geo posting switch. Bob already accepted
   India-only for H3 (2026-08-04). ⇒ **H3 = design lab; Wan 2.2 TI2V-5B = the production engine**
   (genuine Apache 2.0, verified from raw LICENSE.txt, zero territorial/output clause; silent, so
   audio is added). Hunyuan 1.5 is a worse licence for no gain.

4. **EU AI Act Article 50 started applying 2026-08-02 — three days before this brief.** Deployers
   (= the poster) *"shall disclose that the content has been artificially generated or manipulated."*
   ⭐ The creative/satirical carve-out is limited to *"disclosure… **in an appropriate manner that
   does not hamper the display or enjoyment**"* — which is a **reveal at the end of the clip**, exactly
   the format change recommended. The law points the same way the monetisation policies do.

## ⭐ The platform ranking INVERTS

| Platform | "comment your guess" CTA | Originality escape | Rank |
|---|---|---|---|
| **YouTube** | **explicitly OK** — *"It's okay to ask viewers to like, comment, or subscribe"* | written route: creator visible **or** *"explains how the creator added to the content"* | **START HERE** |
| TikTok | **no rule** — "engagement bait" = 0 hits in the guidelines | "low quality"/"unoriginal" bite on **form**; ⚠ **5 ineligible videos / 30 days → disqualified** | second |
| Meta | **prohibited** — demoted *and* unmonetizable | on-screen presence + new info; all 3 gates must clear | last |

Nothing bans AI content anywhere. All three ban **unoriginal**. AI is never the trigger; sameness is.

⭐ **Named buyer for the literacy framing:** TikTok's **$2M AI-literacy fund** (Newsroom 2025-11-19)
pays creators making FYF content that *"teaches people about AI literacy and safety."*
⚠ Counterweight: TikTok is testing a viewer-side **"Manage topics" AIGC control** — a dial to see
*less* AI content. A self-declared AI brand opts into being filtered.

## Name space (checked 2026-08-05)
- **All registered** (RDAP): isthisai.com · isthisaiornot.com · realorai.com · isitai.com · aiornot.com
- **X**: `@isthisai` and `@isitai` resolve (taken); `@isthisai_`, `@isthisaiornot`, `@realorai` → 404.
- ⚠ **TikTok / Instagram / YouTube handle checks INCONCLUSIVE from this box** — they return 200/302
  for every string, taken or not. Needs a real browser before committing to a name.
  (Per [[absence-needs-positive-controls]] — do not report these as free.)

## ⭐ THE RERUN — 2026-08-05, same day (101 agents, 19 sources, 25 claims verified, **13 killed**)

Bob: *"RERUN that Check!! find as much info as you can"* → `/deep-research`. This closed the
brief's biggest hole. **Verdict UNCHANGED — reveal, not poll — and now it has account evidence.**

⭐ **The split is clean: the teaching variant has a live winner, the guess variant has none.**
- **@jeremyfindsai** (Jeremy Carrasco, co-founder riddance.ai) — reveal/teaching format on all 4
  platforms. **TikTok 391,655 followers · 15.46M likes · 370 videos · verified** (bio: "AI video &
  media literacy"); **Instagram 497K / 332 posts**; **YouTube opened 29 May 2025**, still uploading
  31 Jul 2026; Facebook a dead ~814-like satellite (**0.2% of his TikTok** — FB is not where this
  format lives). Press: NPR, The Verge, WSJ, BBC, Axios, Oct 2025–Jun 2026.
- **Reach NOT decaying.** Recent Shorts (YouTube's own RSS `media:statistics`, primary):
  40,580 / 81,953 / 223,554 / 286,964 / 294,093 / 346,578. TikTok Jun-2025→Jul-2026 sample:
  57.2K · 7.7M · 160K · 241.4K · 62.2K · **1.1M (newest = 2nd highest)**.
  ⚠ Those six were **search-surfaced = winner-biased**; read the median (~57K–241K), not the 7.7M.
- **Guess format: ZERO live accounts found.** Only `@AIorREAL` (YT) — 157 subs, 94 videos, **last
  upload 12 Dec 2023**, dead 32 months. ⚠ Weak evidence: hobby channel, and it died **20 months
  BEFORE** the Sora 2/Veo 3/H3 wave. **Not proof the format is burnt out.**

⚠ **n = 2. This is not a survey.** No hashtag/handle sweep was run, so "we found no guess account"
may be coverage failure, not absence. And Carrasco is not a cold start (media background + national
press). Do not let this page claim "the format is growing".

🛑 **NULL RESULT — demand direction is STILL unknown and is now the biggest hole.** Every Trends
series, hashtag count, subreddit-growth figure and academic source was **refuted**. 🛑 **DO NOT
REVIVE these numbers** (all from arXiv 2605.24287 + a JCR TikTok-disclosure paper, refuted 0-3 ×4
and 1-2 ×1): r/RealOrAI 7,945 posts / 92.4% in final 12 months / 288,277 comments · the 6:1
help-vs-guess ratio · the 7–8% AIGC-disclosure engagement penalty over 1,135,817 posts · the
parasocial mechanism · the effort-signal mitigation. Also refuted: **0.84 subs per 1,000 views**
derived from @AIorREAL. Google Trends stays uncapturable from this box → needs a human browser.

**Facts that MOVED (page updated):**
- TikTok literacy fund **$2M at launch → "more than $4M committed to date" + 200M+ views**
  (10 Jul 2026; NAMLE, Raspberry Pi Foundation, Henry Ajder joined). ⚠ **No open application route
  for individual creators** — platform posture, not a cheque. ~10M views/partner = modest.
- **YouTube says the label is free, twice**: help centre *"Disclosing AI content won't limit a
  video's audience or impact its eligibility to earn money"* + newsroom 27 May 2026 *"a disclosure
  label alone does not change how a video is recommended"*. ⚠ Self-report; no independent test survived.
- ⚠ **YouTube moved the label to where viewers see it (May 2026)**: directly below the player, and
  on **Shorts as an OVERLAY ON THE VIDEO**. Auto-applied from GenAI tools / C2PA / internal
  detection; **creator cannot remove** the first two. The platform answers the guess, harder than before.
- **Sprout Social Q1-2026** (n=2,250 US/UK/AUS, 5–9 Feb 2026): "posting AI-generated content without
  labels" **#1 (28%)**, "engagement-bait tactics" **#2 (23%)**. ⚠ Forced choice among 6, about
  **brands** not creators — a ranking of annoyances, not a measured engagement effect.

⚠ **NEW RISK, and it hits the format we recommended:** Carrasco himself posted *"AI photos are
(mostly) undetectable now… Your old tricks probably don't work anymore."* A "spot the tells" show
has a **shrinking half-life** → the durable version drifts to **provenance** (C2PA, labels, source
verification), which is a different show. Settle this before building a content system.

**Corrections to our own earlier write-up (already applied to index.html):**
- *"Adding only an on-screen text caption or title"* is **NOT** on Meta's Content Monetization
  Policies page (word-boundary sweep of its full text: AI 0 · synthetic 0 · label 0 · original 0 ·
  caption 0 · editorial 0). It lives in Partner Monetization Policies / the **13 Mar 2026 originality
  announcement**. The page cited the right separate help ID; the **workspace CLAUDE.md attributed it
  to the CMP and has been fixed**.
- **"Text montages" refuted 1-2** as catching a moving clip on format grounds alone — the
  **engagement-bait behaviour clause** is what bites, and it bites on the **explicit ask**, which is
  precisely what the reveal deletes.
- **All 4 Meta findings came in 2-1** — dissent on scope/enforcement, never on the quoted text.
  Read as "textually in scope", not "will be enforced".
- **Downgraded:** TikTok "Manage topics" AIGC dial (1-2) and the invisible-watermark line (0-3)
  could not be re-confirmed from the Jul-2026 newsroom post. The creator-academy watermark quote in
  Finding 01 stands on its own source; the viewer-side dial is now marked unconfirmed.

⚠ **Time sensitivity is one-directional:** every platform trend runs toward MORE automatic labelling
and MORE visible provenance — eroding a guessing hook with each release, strengthening a teaching
one. Re-verify all four platform positions immediately before launch.

## ⚠ STILL NOT VERIFIED
1. 🛑 **Is demand rising or falling?** — the new biggest hole (above). Needs a human browser.
2. 🛑 **A real hashtag sweep** (#realorai / #isthisai / #aiornot / #spottheai on TikTok + IG,
   handles/followers/views) — the test that turns "we found none" into "there are none".
3. **@jeremyfindsai's true median + cadence** — TikTok's profile payload carries no post list.
4. FB CM payout rates for this content; whether Meta demotes AI-labelled content. **No independent
   measured test of "does the label cost reach" survived on ANY platform.**
3. Trademark search on IS THIS AI / AI OR NOT / REAL OR AI. ⚠ "AI or Not" is believed to be a live
   AI-detection product — **unverified**, agent died.
4. US state law (CA AB 3211 / AB 853) + India IT-rules on synthetic-media labelling.

## Status
**NOTHING BUILT. No accounts created, no domains bought, $0 spent.** Awaiting Bob's call on:
reveal-vs-poll, which platform first, and whether "Is This AI?" is the brand or the first series
inside a broader AI-literacy brand that can outlive the gimmick.

## Method notes
- Meta's help centre is client-rendered and returns a login shell to any non-browser fetch → quotes
  came from **timestamped Wayback captures**.
- TikTok guidelines are URL-encoded JSON inside the page source, not readable HTML.
- TikTok FAQ API that works: `www.tiktok.com/feedback/1/faq_detail_by_id/?faq_id=<id>&app_id=1284&app_key=tiktok-web&lang=en`
  — ⚠ param is `faq_id` not `id` (`id=` returns 200 + a silent empty record), trailing slash is
  mandatory, and no `/api/` prefix. Creator Academy needs a different route: `"articleData"` JSON
  inside a `<script>`.
