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

## ⚠ NOT VERIFIED — 4 of 8 research agents died on a session limit (resets 11:00 UTC)
1. ⭐ **Precedent accounts and their real numbers** — the format already exists ("real or AI",
   "spot the AI"). **No data on whether it's growing or already burnt out.** Biggest hole; the whole
   brief is a rules analysis and says nothing about whether the audience still cares. **Re-run first.**
2. FB CM payout rates for this content; whether Meta demotes AI-labelled content (TikTok says it doesn't).
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
