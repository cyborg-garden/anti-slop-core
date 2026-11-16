# anti-slop core: the versioned floor for escaping AI-slop writing

**Repo:** cyborg-garden/anti-slop-core · **Current:** v1.5.1-public.1 (2026-11-16) · **Full guide:** [`anti-slop-core.md`](./anti-slop-core.md)

This is a versioned floor of writing constraints for anyone, human or agent, whose
text keeps reading as machine-made. Six constraints, five ideals, a self-audit, and a
per-model quirks catalog that hedges on purpose, because quirk tables age with every
model release.

The one idea: AI writing fails when it lacks specific facts or a claim the writer would
defend. Stock AI phrases show up when the writer has nothing concrete to say. Deleting
those phrases is only half the edit; if you put no real facts back in, the prose stays
vague and robotic.

What's in the box:

- **C1 structural residue** — uniform blocks, metronome cadence, essay-shaped responses,
  automatic three-item lists, "not just X, it's Y," false two-sidedness
- **C2 the lexical floor** — flag clusters, not singletons; the generic-residue list
  (delve, tapestry, leverage…) and chatbot artifacts
- **C3 corny metaphors** — earn the image or cut it
- **C4 the em-dash recompose rule** — recompose the sentence, never delete the dash and
  leave a gap
- **C5 audience residue** — the draft keeps the context that made it, not the context the
  reader has; detection checklist and repair move included
- **C6 transferred effort** — do the sender's reading, checking, and distilling before
  handing a draft to someone; no uninvited raw output in someone else's discussion
- **I1–I5 the ideals** — specificity engine, landings that point at checkable things,
  limits that ride with the claim, earned voice over imitation, and legibility: every
  constraint here must be showable in a two-line before→after example, because a rule
  written in claudlish teaches claudlish
- **The self-audit** and false-positive guards against stripping good writing down to blandness
- **A per-model quirks catalog** (Claude / GPT / Gemini / GLM) with a measured /
  documented / observed hedge vocabulary, because per-family lore is mostly single tests
  and memes, and the tables age fast

Everything external is cited in the guide's Sources section: Wikipedia's Signs of AI
Writing catalog, Kobak et al. on excess vocabulary, Reinhart et al. (PNAS 2025) on
per-model stylistic signatures, Liang et al. on detector false positives, the em-dash
discourse (Washington Post, Altman/TechCrunch), Mollick and Campos on audience residue,
and Stop Sloppypasta on effort asymmetry.

**Provenance.** This is the genericised public edition of an internal, versioned guide
maintained by [Cyborg Garden](https://cyborg.garden). The named contributors, in-house
incident records, and internal memory paths behind several entries remain private; the
constraints, ideals, citations, and hedge vocabulary are carried whole. This public
edition tracks the internal canonical file continuously rather than waiting for major
version bumps.

**Use it.** Inherit by reference, not by copy. Point your drafter, human or agent, at
[`anti-slop-core.md`](./anti-slop-core.md), run the self-audit on the final draft, and
keep your own fleet's quirks table current. Contributions welcome: a new failure mode
with a real dated example is a minor version bump here.

**Alembic:** [Refine the process, then share the method](./alembic/README.md) is the
companion loop for turning a completed collaborative run into a reviewed skill, an
independently audited template contribution and a public artifact without carrying its
private incident details along.

**License:** [LICENSE.md](./LICENSE.md)