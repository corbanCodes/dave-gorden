# Dave Gorden & Associates — demo notes

Demo built 24 Aug 2026 from the Aug 23 discovery call. Three pages as agreed:
`index.html` (landing), `programs.html` (programs + Discovery Visit + case study), `about.html`.

## The strategy baked into the site
- **One job: make them call.** Phone number is the nav CTA, the hero CTA, the mid-page CTA band on every page, and the footer. Form is positioned as the after-hours fallback ("expect a call back, not an email chain").
- **Pricing is a non-discussion.** Nothing on the site references money, rates, price lists, "investment," or cost comparisons — per Dave (needs analysis $5k / $1250 day rate are never advertised) and per Corban 8/25 (no meta-commentary about the absence of pricing either). The framing is diagnosis-first ("prescription without diagnosis is malpractice"), never cost.
- **No payments on the site**, per Dave. No mention of deposits either — keep money off the site entirely.
- C-suite-first / Internal Guest vs External Guest is the through-line on all three pages.

## Placeholders & asks for Dave
1. **Photography.** The one photo we have is his LinkedIn headshot, AI-upscaled to 1254px (8/25) — holds up well in the framed portrait treatment. Dave said he's lost 50 lbs and needs new card photos anyway — ask for 3–5 hi-res shots: one on stage, one portrait, one candid with a client group. That unlocks a real photo hero.
2. **Client letters.** His old 8-page site had many letters from clients. Get the 3 best and add an "In Their Words" section (index + about). **Do not fabricate testimonials in the meantime** — none are on the demo.
3. **Confirm client naming.** The about page references "a national snack-food company" (Tom's Foods) and "a greeting-card giant" (Hallmark) *without naming them*. If Dave OKs naming them, swap the real names in — much stronger.
4. **The case study.** The Pigeon Forge / Greenbrier story is on programs.html, reframed as an alternative-experience story ("The retreat that became a campsite") — resort unnamed, no dollar figures, no money angle. Confirm Dave's comfortable with the level of detail.
5. **"Eight out of ten"** Discovery Visit close rate is on programs.html — from his own words (80%). Confirm he wants it public.
6. **Facebook** — he wasn't sure he has a page. LinkedIn only for now.
7. **Domain** — his email is dave@davegorden.net; confirm he controls davegorden.net and wants the site there.
8. **DISC** — confirm he can market the DISC assessment under that name (he resells via the DISC company).

## Launch checklist
- Remove `data-demo` from the contact form (Netlify Forms attrs already wired), set form notification email.
- Remove the `.demo-bar` div from all three pages.
- Netlify: import repo `corbanCodes/dave-gorden`, attach domain, enable form detection.
- Add repo to the 60ms-hq-publisher token's repository list; link in HQ Sites page.
