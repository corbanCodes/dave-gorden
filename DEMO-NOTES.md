# Dave Gorden & Associates — demo notes

Demo built 24 Aug 2026 from the Aug 23 discovery call. Three pages as agreed:
`index.html` (landing), `programs.html` (programs + Discovery Visit + case study), `about.html`.

## The strategy baked into the site
- **One job: make them call.** Phone number is the nav CTA, the hero CTA, the mid-page CTA band on every page, and the footer. Form is positioned as the after-hours fallback ("expect a call back, not an email chain").
- **Pricing is a non-discussion.** Nothing on the site references money, rates, price lists, "investment," or cost comparisons — per Dave (needs analysis $5k / $1250 day rate are never advertised) and per Corban 8/25 (no meta-commentary about the absence of pricing either). The framing is diagnosis-first ("prescription without diagnosis is malpractice"), never cost.
- **No payments on the site**, per Dave. No mention of deposits either — keep money off the site entirely.
- C-suite-first / Internal Guest vs External Guest is the through-line on all three pages.

## Concept A / B (added 25 Aug)

Two homepage concepts, same content strategy and the same interior pages
(`programs.html`, `about.html` are shared). A fixed **Concept A | B** pill (bottom-left,
demo only) flips between them live on the call.

| | **A — `index.html`** | **B — `b.html`** |
|---|---|---|
| Feel | Dark, atmospheric, "private club" | Light, editorial, "author / authority" |
| Palette | Deep pine + brass + cream | Bone + ink + oxblood (pulled from his tie) |
| Type | Cormorant Garamond (delicate, high-contrast) | Source Serif 4 (sturdy, HBR-ish) |
| His photo | 238px medallion in an arch frame | 380px portrait panel, face is the hero |
| Content blocks | Icon cards (3-up grids) | Numbered editorial rows + hairline rules |
| Mobile CTA | In-page buttons | **Sticky bottom call bar**, always visible |

**Why B exists:** on A the client's own face is a small ornament, and the page is built from
card grids — competent but template-flavored. Speaker sites sell the *speaker*; B leads with
a big, warm, mid-story photo of Dave and treats the copy like a magazine feature. B also adds
the persistent mobile call bar, which matters a lot for a site whose only job is phone calls.

**If Dave picks B**, the interior pages should be restyled to match (currently they carry A's
pine/brass). Budget ~an hour for that.

## What the category actually does (competitive research, 25 Aug)

Reviewed Shep Hyken, Scott McKain, Jay Baer, Dan Gingiss, Brittany Hodak, Ryan Estis,
Jon Gordon, Simon Sinek. Dave's closest comps are Hyken / Baer / Gingiss / Hodak —
customer-service and CX speakers, not celebrity mega-brands.

**We already match the pattern on:**
- Booking CTA pinned in the header as the only filled button (6 of 7 comps do exactly this)
- A phone number in the chrome — event planners work on deadlines and they call
- Headline is a claim about the buyer's business, not a job title. Zero comps lead with
  "Keynote Speaker & Author"; ours leads with the astonishment claim
- A named, ownable framework. **"Guest Astonishment" is Dave's biggest asset** — comps
  trademark theirs (*Beyond Distinction*, *Superfans*, *The Experience Maker*) because
  packaged IP is what justifies a speaking fee
- Big face above the fold (after the 25 Aug fix — see below)

**The three gaps, in priority order:**
1. **A "Trusted by" logo wall or client list.** Every single comp puts social proof within
   one scroll of the hero; several put a press bar *inside* the hero. We have none because
   we have no assets. This is the highest-value ask on the call — even a text list of
   industries-plus-client-types would work if logos need permission.
2. **A "For Meeting Planners" page.** Hyken, Gingiss, Hodak and Gordon all have one:
   downloadable bio, A/V requirements, intro script, headshots, pre-program questionnaire.
   It is the cheapest credibility signal in the category and it is *the* speaker-specific
   page type. Strong candidate for page four.
3. **A speaking reel.** Universally the second CTA, always styled weaker than the booking
   button (ghost outline or text link). Dave has no video — worth asking whether any client
   has recorded him.

**Photo finding:** for CX/service speakers a large, energetic, mid-gesture face above the
fold is the norm (Hyken, Baer, Gingiss, Hodak). A static corporate portrait reads
*consultant*, not *keynoter*. Our arch medallion was the most conservative photo treatment
of any site reviewed, so on 25 Aug A's portrait was enlarged from 238px to 360px and
re-cropped tighter on his face. Both concepts now lead with the face.

**Palette finding:** the premium-feeling comps are all dark above the fold (navy, near-black,
deep green) with a single ruthless accent. That favors **A**. B answers with the other
half of the pattern — the Jay Baer move of a serif display face and a big cutout, which is
rare in this category and reads upmarket. Worth showing Dave both and letting him react.

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
- **Pick a concept**, delete the loser (and its stylesheet), rename the winner to `index.html`.
- Remove the `.ab-toggle` div from every page.
- Remove `data-demo` from the contact form (Netlify Forms attrs already wired), set form notification email.
- Remove the `.demo-bar` div from all pages.
- Netlify: import repo `corbanCodes/dave-gorden`, attach domain, enable form detection.
- Add repo to the 60ms-hq-publisher token's repository list; link in HQ Sites page.
