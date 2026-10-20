---
name: anti-slop-core
version: 1.2.0-public.1
dated: 2026-10-19
tracking: internal anti-slop-core v1.1.0 (2026-08-19)
review: quarterly, and on every newly documented failure mode, whichever comes first
maintainer: Cyborg Garden
provenance: genericised public edition of an internal, versioned guide. All named-person
  attributions, in-house incident records, and internal memory paths are removed here and
  remain in the private store. External citations are public research and carried in full.
---

# anti-slop core — the base layer every voice inherits

This is a versioned floor beneath brand and personal voices. Voices inherit it **by
reference, never by copy**, so updating this file updates every voice that depends on it
without touching a single voice file. Two kinds of content, with different override rules:

- **Constraints** are floors. No voice may relax one. Tightening is always allowed — a
  banned list stricter than C2 is the design working, not an exception.
- **Ideals** are defaults. A voice may override an ideal with something better — a
  developed alternative — never with nothing.

## The one idea to hold

Slop is an absence, not a vocabulary. Text reads as machine-made when it has been sanded
free of anything specific, anything at stake, any claim the writer would defend. The tells
everyone lists are what rushes in to fill that vacuum. So you do not write well by
deleting the tells; you write well by putting back what was missing, then scanning for
residue. Both failure modes are real: **under-edited** (the tells are present) and
**over-scrubbed** (the tells are gone and nothing arrived to replace them — clean, dead,
and still detectable).

The corollary that keeps the whole discipline honest: a voice is not a list of bans. The
bans are the guardrails; the voice is a developed position — moves the writer would
defend, calibrated against real exemplars — arrived at by drafting, feedback, and
correction. A voice that exists only as "like the house voice but shorter" is not a voice
yet; it is a truncation.

---

## Constraints (the floors)

### C1 — Structural residue. The literal shape of paragraphs is where AI writing gives itself away.

Lexical bans are the easy half. These are not:

- **Uniform paragraph blocks** — 4–8 sentences each, all the same weight, burying the
  reader instead of moving.
- **The metronome cadence** — alternating long/short sentences on a schedule. Variance
  must come from meaning: long when the idea is, short when it lands.
- **The essay-shaped response** — throat-clearing opening, dutiful body, a closing
  paragraph that restates what was just said. No summary paragraphs. Trust the reader to
  have read it.
- **Over-signposting** — "let's dive in," "here's what you need to know." The structure
  should be felt, not announced.
- **Negative parallelism as a reflex** — "not just X, it's Y." (Cataloged as a
  stereotypical AI sign by Wikipedia's guide.)
- **Reflexive tricolons** — three items where two would do. (Same guide: "LLMs overuse the
  rule of three.")
- **The hedging seesaw** — "could potentially possibly."
- **Manufactured short-fragment drama** — punchy fragments unearned by any build.
- **Elegant variation** — cycling synonyms to dodge an honest repeat. (Attributed in the
  research to repetition penalties.)
- **List-itis** — bolded-pseudo-header bullet lists where prose should be; converting an
  argument into an inventory.
- **Symmetry theater** — "on one hand / on the other" when one hand has the evidence.
  False balance is a lie of shape, not of content.
- **The pre-emptive defense** — writing to deflect anticipated criticism instead of to
  communicate. Defensive writing is legible as defensive.
- **Apology-as-punctuation** — "sorry, this is getting long." The fix for long is
  shorter, not sorry.
- **The victory lap** — ending on the best-sounding line. End on weight: what the reader
  can rely on or do next.

### C2 — The lexical floor. Flag clusters, not singletons.

One em-dash is not a crime; a single formal word is fine. The disease is density —
Originality.ai's own 10M-word study concludes the frequency gap for single AI words is
small. Singleton words don't convict; clusters do.

- **Generic residue:** delve, tapestry/landscape (as abstractions), testament,
  pivotal/crucial, intricate, underscore, leverage/utilize, seamless(ly), robust/holistic
  as filler, empower, unlock, "it's important to note," "at its core," "in conclusion,"
  "navigate the complexities of," "in today's fast-paced world," paradigm shift, journey.
- **Throat-clearing:** "it's worth noting" (if it's worth noting, note it), "honestly / to
  be honest" (implies the surrounding text was something else).
- **Hedging and adverb stacking:** "might potentially," "truly really," "to some extent."
- **Chatbot artifacts:** "as an AI," "I hope this helps," "would you like me to."

### C3 — Corny metaphors are first-class violations.

The overwrought image is as loud a tell as any banned word: "the forge glows red-hot"
over a code contribution. Earn the image or cut it. The same ban covers theory
name-dropping as decoration — concepts stacked without grounding read as showing off,
not explaining. A metaphor earns its place when the thought needed it; it never earns its
place by being vivid.

### C4 — The em-dash recompose rule.

In public-facing text, near-eliminate em-dashes. Not because measurement crowns it the
top tell (no study does) but because it is the internet's most-litigated AI tell: readers
accuse posts of being AI over em-dashes, writers answer "I used it before AI," and the
discourse is documented enough to be a publishing risk on its own — the Washington Post
covered the accusation wave, and OpenAI itself has acknowledged and shipped fixes for
ChatGPT's em-dash overuse. The mechanism: models reach for the em-dash where an
interjection set off with commas would suffice, and would not be the tell (Wikipedia's
catalog: LLMs use em dashes where humans would use commas, parentheses, or colons). So the
fix is never deleting the dash and leaving a gap or a comma splice. **Recompose the
sentence so it never wanted the dash.** "Mostly," not "zero": one genuinely earned dash
in a long piece is fine and keeps the text from reading as conspicuously scrubbed.

### C5 — Audience residue. The draft keeps the context that made it, not the context the reader has.

Slop is usually an absence. This one is a wrong presence with an absence behind it: the
private conversation that produced the text stayed in, and the reader's actual starting
point never got written. The copy reports on the writer's process instead of orienting
the person who just arrived. Ethan Mollick names the mechanism directly: "Work products
often include information that only matters to the creator and is irrelevant or confusing
to users, like references to previous drafts or problems solved in earlier iterations."

**Why it happens:** the drafting context travels with the draft. When public copy is
generated from internal material — a thread, a spec, a session transcript, a prompt
stuffed with background — the model faithfully summarizes what it was handed, and what
it was handed was addressed to insiders. Nobody re-aimed it.

- **Deliberation narration** — "after a lot of back and forth we landed on X." The reader
  did not know there was a fork, and gains nothing from learning one existed.
- **Wrong-audience address** — second person that means the team. "You'll want to migrate
  before the freeze." Whose freeze?
- **Timeline residue** — "originally slated for June." A release note that dates its own
  delay.
- **Fix memorialization** — the artifact celebrating its own repair history: UI copy that
  announces "now with improved loading," a landing page noting a bug no visitor knew
  existed. The reader sees the product for the first time; there is no "now."
- **Prompt residue** — the brief showing through the output: its category labels as
  headings, its three requirements restated as three sections, "as requested."
- **Unexplained in-group shorthand** — internal project names, ticket IDs, a nickname for
  a subsystem, a term of art the outside reader has never met.
- **Rationale dump**, the polite-sounding variant — "after much discussion with
  stakeholders we felt the most responsible path was an incremental rollout." Minutes
  for the attendees.

**Detection.** Run this on the final draft, with the source thread closed.

- Every "we": does the sentence still work for a reader who has never met us?
- Every past tense: is that history load-bearing for them, or only for us?
- Every proper noun: would a stranger know it? Define it or cut it.
- Every heading: did it come from the subject, or from the brief?
- Last pass: would we be comfortable if the source thread were published beside this?

**The repair is not deletion.** Cutting the process leaves a hole where the reader's
orientation belongs. Re-address the text to a reader who was not in the room: what this
is, who it is for, what changes for them today.

---

## Ideals (what good looks like — the defaults)

### I1 — The specificity engine. Run it first, while drafting.

1. **One load-bearing claim, stated once, without hedging.** If you can't find the claim,
   the piece isn't ready; no amount of clean prose rescues an empty one.
2. **Concrete over abstract, always.** A number, a name, a thing that happened. The
   specific is unfakeable; the abstract is where slop hides.
3. **Something that could be wrong.** A tradeoff named, a case it doesn't cover, an
   opinion someone could dispute. Prose with no exposed surface reads as no one wrote it.
4. **Rhythm follows the thought.** Not a schedule.
5. **Cut anything that restates.**

### I2 — Landings point at checkable things.

The last sentence of a passage lands on something the reader can verify, use, or argue
with — an object, a stance, a next step. Not a feeling, not a recap.

### I3 — Limits ride with the claim.

A qualifier that names a real limit is not hedging; it is the load-bearing wall. Hedging
is unfocused vagueness that protects the writer; calibration commits to more — the claim,
its conditions, and its boundary in one motion. Where there is a number, its conditions
travel in the same sentence.

### I4 — Earned voice, not imitation.

A voice or register is a developed position — moves the writer would defend, calibrated
against real exemplars — not a guess at what someone wants replicated. Build the draft to
the register's contract from the first sentence (a 280-character post is written to 280,
never trimmed to it).

---

## The self-audit (run after drafting)

Scan the draft against C1–C5, flagging clusters. Then ask the humanizer's question:
**"What still makes this obviously AI?"** Rewrite that; don't just trim it.

**False-positive guards — do not over-scrub.** Preserve true human signals: specific
hard-to-fabricate detail, mixed feelings, dated references, a self-correction, a genuinely
earned em-dash or tricolon. When a device is earned by the thought, it stays. Laundering
good prose into blandness is the over-scrubbed failure, and it is still detectable —
GPTZero's own guidance names smooth, uniform, style-guide-conforming prose as what gets
human writing flagged, and Liang et al. showed detectors misfire hardest on non-native
English writers (61.3% of TOEFL essays falsely flagged). The detector-paranoia that
produces flat, defensive prose is a worse failure than the tells.

---

## Per-model quirks — hedge, don't canonize

Model families have distinct stylistic signatures; that part is measured (Reinhart et al.,
PNAS 2025: large, systematic grammatical and stylistic differences between models,
*stronger* in instruction-tuned ones). But the specific tells shift with every release,
and most per-family lore is single tests and community memes, not measurement. So this
catalog hedges by design: **measured** (studied) · **documented** (issues, press, vendor
acknowledgment) · **observed** (noticed in-house, not externally verified — a hypothesis,
not a fact). Weight your own fleet's models higher: the tells most likely to appear in
your drafts are the ones your models produce.

### Claude

- "You're absolutely right!" and agreement sycophancy — **documented** (a genuine
  cross-community meme; dozens of open issues cite it)
- Celebratory emoji (🚀✅🎉), over-exuberant closers — **documented as a generic AI
  pattern, observed Claude-frequent in-house**
- Heavy-handed metaphor over technical work — **observed**
- Em-dash rate *lower* than ChatGPT in at least one informal test — **documented
  (single test)**

### GPT / ChatGPT

- Em-dash overuse, resistant to instructions until the 2025 fix — **documented
  (vendor-acknowledged)**
- delve / intricate / underscore excess vocabulary (peaked 2023–24, declining since) —
  **measured**
- "unique," "journey," "certainly," conclusion-family frequency — **measured (vendor
  study)**

### Gemini

- Self-deprecation loop ("I am a failure"), 2025 agent-loop bug, patched — **documented
  (bug, not stable style)**
- Zero em dashes in the same informal cross-model test — **documented (single test)**
- Recurring prose oddities — **observed, needs entries**

The per-family tables age fast. Treat them as a starting checklist for your own
observation, refresh them on every model migration, and never let a quirk entry override
the structural floor: escaping your model's accent matters less than having something
specific to say.

---

## What this edition is, and is not

This is the genericised public edition of an internal guide. Not carried here: the named
in-house contributors whose banned lists and corrections generalized into C1–C3 and the
ideals (credited in the private store), the real dated incidents behind C5's examples, and
the org-specific voice bundles layered above this floor. The externals are carried in
full, in Sources.

The "bans are the catches, applied to prose" posture is deliberate. A banned list is
maintenance, not a manifesto: new failure modes get added as they are documented, the
review clock runs regardless, and hedged entries (observed vs measured) are there so
nobody has to pretend certainty the record doesn't have.

## Sources (nothing here is invented)

- Wikipedia, [Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing) — the observational catalog behind most of C1 and the em-dash mechanism in C4
- Kobak et al., [Delving into LLM-assisted writing](https://arxiv.org/abs/2406.07016) (Science Advances) · Juzek & Ward, [Why Does ChatGPT 'Delve' So Much?](https://aclanthology.org/2025.coling-main.426/) (COLING 2025) — the excess-vocabulary measurement in C2
- Reinhart et al., [Do LLMs write like humans?](https://www.pnas.org/doi/10.1073/pnas.2422455122) (PNAS 2025) — per-model stylistic signatures, the ground for the quirks catalog
- Liang et al., [GPT detectors are biased against non-native English writers](https://arxiv.org/abs/2304.02819) — the false-positive guard
- [GPTZero](https://gptzero.me/news/how-ai-detectors-work/) on perplexity and burstiness — the measured fact behind the cadence rules
- Folta, [LitHub](https://lithub.com/heres-a-handy-guide-to-help-you-spot-ai-writing/) — the "sanded down into a blurry, generic sketch" framing behind the one idea
- Mollick ([bsky](https://bsky.app/profile/emollick.bsky.social/post/3mteazepkqc2n)) and Campos ([bsky](https://bsky.app/profile/daniloc.xyz/post/3mtecfm3aps2v)) — the C5 external ground
- Washington Post on the [em-dash accusation wave](https://www.washingtonpost.com/technology/2025/04/09/ai-em-dash-writing-punctuation-chatgpt/) · Altman ([X](https://x.com/sama/status/1989193813043069219)) and [TechCrunch](https://techcrunch.com/2025/11/14/openai-says-its-fixed-chatgpts-em-dash-problem/) on the vendor-acknowledged side of C4
- [Plagiarism Today](https://www.plagiarismtoday.com/2025/06/26/em-dashes-hyphens-and-spotting-ai-writing/) — the informal cross-model em-dash test

## Changelog

- **1.2.0-public.1** (2026-10-19) — first public edition. Genericised from internal
  v1.1.0: named-person attributions and in-house incident records removed (they remain in
  the private store), the per-model quirks catalog promoted from the internal research
  dossier with its hedge vocabulary made load-bearing, and the "what this edition is /
  is not" section added. No constraint or ideal changed meaning; public edition tracks
  internal majors.