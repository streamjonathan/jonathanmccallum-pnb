# AGENTS.md — jonathanmccallum-pnb (Western Punjabi (Shahmukhi) mirror of jonathanmccallum.com)

Western Punjabi (Shahmukhi) mirror site. Same theme and design as the main site (Paper Light),
content translated into Western Punjabi (Shahmukhi), meaning-first. Repo: streamjonathan/jonathanmccallum-pnb.
Live (when approved): pnb.jonathanmccallum.com. Proof: jonathanmccallum-pnb.pages.dev.

## Mission

Mirror jonathanmccallum.com in Western Punjabi (Shahmukhi) — every article translated for meaning,
not word for word, in Jonathan's voice: plain short sentences, friendly, positive,
never preachy. An average person interested in Jesus, not an expert or theologian.

## Roles

- **Bobby (Muse) is the lead builder.** He coordinates, builds, pushes to GitHub
  and deploys to Cloudflare. He is the ONLY one who pushes or deploys.
- **Claude advises and reviews** translation quality. He does not push or deploy.
- **Helper Muses translate** one article at a time, drafts only.

## The one rule above all

**Never publish or alter live production assets without Jonathan's clear
permission.** The Western Punjabi (Shahmukhi) site goes live on pnb.jonathanmccallum.com only when
he says so, after reading the pilot article(s). Drafts stay drafts until he
approves them. Work on a branch, never straight on main. Give Bobby a preview URL.

## Translation rules

- English repo (streamjonathan.github.io) is the source of truth. Articles are
  translated from the English Markdown, keeping the same date, slug, source_video
  and shareImage. Only the title and body are translated.
- Script: Shahmukhi, right-to-left. Distinct from Eastern Punjabi (pa, Gurmukhi,
  LTR) — never mix the two scripts.
- Register: warm, plain, short sentences, no preaching. Reader addressed as
  "تُسی" (respectful; chosen over familiar "تُوں" — Jonathan to confirm).
- Names (never vary): یسوع, خدا, مسیح, پطرس, آدم تے حوا, اصلان, نارنیا,
  لوسی, ڈگری, ٹیرین. Book titles are transliterated — no published Punjabi
  titles were found (دی کرونیکلز آف نارنیا, دی میجیشنز نیفیو, دی گریٹ ڈیوورس,
  دی سپیس ٹرالوجی, دی لاسٹ بیٹل) — flagged for Jonathan.
- Bible verses: no direct verse quotations appear in these 5 articles. The
  bread/water of life lines are Jonathan's paraphrase (John 6:35 / 4:14) —
  زندگی دی روٹی / زندگی دا پاݨی — never quoted as Scripture. No public-domain
  Punjabi Bible in Shahmukhi script was verified; if a direct verse is ever
  wanted, its exact wording must be sourced first — never invented.
- No emojis, no newsletter form, no links the English article does not have.
- Never invent facts, dates, links or details.

## Site facts

- Eleventy 3, Cloudflare Pages, Paper Light theme (Fraunces + Newsreader).
- No Ask chat and no note Worker on this site yet — search (Pagefind) works,
  Ask and notes come later. The Ask floating button and ask.js are removed.
- CSS is preloaded, not inlined (CSP blocks inline style). Bump the `?v=` query
  on any CSS/JS file you change.
