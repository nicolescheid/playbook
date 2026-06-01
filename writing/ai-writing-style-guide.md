# Avoiding AI Writing Tells — A Practical Style Guide

*A portable, evidence-based reference for making copy read like a person wrote it — usable for hand-editing text and for steering language models. Application-agnostic; drop it into any project.*

Last reviewed: 2026-06. This is a moving target — see [Caveats](#caveats-read-these).

---

## The one principle

There is no single word or mark that proves text is AI-generated. The reliable signal is **density of "style words" plus a handful of structural habits**. One inflated word is coincidence; six in a paragraph, stacked with antithesis and tidy triplets, is the tell.

So don't hunt for banned words. Fix the **structure and the verbs**, lead with the point, and be concrete. That survives as the models change; word-lists don't.

---

## The checklist

### 1. Lexical — inflated words and verbs

**Excess "style words."** A small set spiked sharply after late-2022 and now reads as a marker. Flag on sight when they cluster: *delve, underscore, showcase, tapestry, testament, pivotal, intricate, meticulous, robust, seamless, vibrant, commendable, comprehensive, crucial, notably, navigate, landscape, realm, foster, elevate, unlock, journey, unpack, leverage, game-changing.*
> Density matters more than any single word. Treat these as smoke, not fire.

**Inflated verbs / dressed-up copulas** (the higher-leverage fix — ~two-thirds of tells are verbs). AI replaces plain `is / has / does` with marketing verbs: *serves as, boasts, features, offers, stands as, represents, leverages, empowers, fosters.*
- Before: *"Gallery 825 serves as the association's exhibition space."*
- After: *"Gallery 825 is the association's exhibition space."*

**Fix:** cut or swap for the plain word; reserve an elevated verb for when it carries real meaning. Substitute *plainness + specificity* (`seamless → smooth`; `exemplary → excellent`).

### 2. Syntactic — the structures that give it away

**Negative-parallelism / antithesis** — the single most stereotyped construction. *"Not just X, but Y." "It's not… it's…" "Not only… but also…"* It reads as if correcting a misconception nobody raised.
- Before: *"It's not just a notebook — it's a thinking tool."*
- After: *"It's a notebook for thinking things through."*

**Rule-of-three tricolons** — three balanced items in a row, used to make a thin point feel complete. *"A map, a librarian, and a guide."* Break them; keep one, or use an uneven number.

**Mechanical parallelism** — every sentence the same shape and length. Vary it. Let one sentence be short. Use a fragment.

### 3. Punctuation — the em-dash, in proportion

The em-dash (the "ChatGPT hyphen") is overused by models far beyond human frequency, so it has become a *perceived* tell.
**Fix:** replace decorative dashes with full stops, commas, or colons; keep the ones doing real work.
**Caveat:** em-dashes alone are **not** proof of AI — plenty of strong human writers love them, and removing them won't fool a detector. Rhythm is the deeper signal. Moderate, don't purge.

### 4. Phrase templates & signposting

Cut these on sight: *"In today's world / fast-paced world," "It's worth noting that," "In conclusion," "A testament to," "Navigating the landscape of," "Plays a pivotal role in," "Here's the thing," "Let's dive in," "When it comes to…"*

**Fix:** delete the warm-up and **lead with the essential information.** Delete hollow conclusions that just restate the body.
- Before: *"Oops! Unfortunately, it looks like something went wrong on our end."*
- After: *"That didn't save. Try again in a moment."*

### 5. Tone & abstraction

Vague abstraction and relentless positivity are core tells. So is reflexive both-sides hedging (*"on one hand… on the other…"*).

**Fix — the highest-leverage move of all: replace abstraction with specifics.** Real numbers, real dates, the person's own words.
- Before: *"Your deposit limit is reset on a monthly basis."*
- After: *"Until 31 January, you can deposit £400 more."*

---

## What human writing does that AI tends not to

- **Specificity** — concrete detail over category words. A particular Tuesday, not "recently."
- **Asymmetry** — uneven sentence lengths, the occasional fragment, a sentence that ends sooner than expected.
- **Restraint** — says one thing well and stops. Doesn't summarise itself.
- **Voice** — a point of view, mild opinion, the odd plain or blunt word.
- **Plainness** — trusts a simple word. "Use," not "utilise." "Is," not "serves as."

---

## The 60-second edit pass

1. **Verbs:** change every `serves as / leverages / fosters` to `is / uses / helps`.
2. **Antithesis:** find every "not just… but" and "it's not… it's…" — rewrite as one direct statement.
3. **Openers:** delete the first clause if it's a warm-up; start at the real point.
4. **Triplets & dashes:** break one rule-of-three; replace one decorative em-dash with a full stop.
5. **One specific:** swap the vaguest sentence for a concrete detail (a number, a name, a real example).

If you only do two, do **1 and 5** — plain verbs and specificity carry most of the effect.

---

## Drop-in prompt block (for steering an LLM)

Append to a system or task prompt. It **leads with a positive description**, then names what to avoid — because telling a model *only* what not to do was tested and found **not** to be a superior strategy (see Caveats).

### Compact version
```
Write like a thoughtful, plain-spoken person, not like AI or marketing copy.
Use plain words and short, varied sentences; let the rhythm be a little uneven.
Be concrete — use the specific details you were given, not general phrasing.
Prefer plain verbs (is, has, does, helps) over inflated ones (serves as, leverages, fosters).
Avoid: words like delve, underscore, showcase, tapestry, testament, pivotal, robust, seamless,
navigate, landscape, realm, foster, elevate; openers like "In today's world" or "It's worth noting that";
and the "not just X, but Y" / "it's not… it's…" construction.
Go easy on em dashes. Don't pad with rule-of-three lists or tidy summaries.
When unsure, be plainer and more specific.
```

### Expanded version (when you have room and want a defined voice)
```
VOICE
Write as one clear, grounded person talking to another. Warm but unsentimental.
Plain over clever. Say one thing well, then stop. A point of view is welcome; filler is not.
[Optional: British English. / A dry, literary register. / etc.]

DO
- Short, varied sentences. Fragments are fine. Let length be uneven.
- Concrete specifics: real names, numbers, dates, and the exact words the reader gave you.
- Plain verbs: is, has, does, helps, shows. Plain nouns over abstractions.
- Lead with the point. Cut the warm-up clause.

AVOID (these read as machine-written)
- Inflated verbs: serves as, boasts, leverages, empowers, fosters, represents.
- Excess "style words": delve, underscore, showcase, intricate, robust, seamless, tapestry,
  testament, pivotal, vibrant, navigate, landscape, realm, elevate, unlock, journey.
- The antithesis template: "not just X, but Y", "it's not… it's…", "not only… but also".
- Filler openers: "In today's world", "It's worth noting that", "Here's the thing", "Let's dive in".
- Rule-of-three triplets used for padding; relentless positivity; both-sides hedging.
- Em dashes beyond the occasional load-bearing one.

WHEN UNSURE
Be plainer and more specific. Trust the simple word.
```

---

## Caveats (read these)

- **Domain mismatch.** The strongest evidence (corpus studies of millions of texts) comes from **academic / biomedical writing**, not web or marketing copy. The word-overlap with everyday copy is exact, but the precise frequencies and the "two-thirds of tells are verbs" split are abstract-corpus findings. Treat statistics as indicative, the direction as sound.
- **It decays.** Word-lists date within months — "delve" surged, got named publicly, then dropped while other words rose. Any fixed banned-word list will rot. The durable signal is **density + structure**, so lean on those and refresh the word-list periodically.
- **Em-dashes are weak evidence.** Many excellent human writers use them. Moderating them improves *perception*; it isn't a forensic fix. Rhythm matters more.
- **Negative-only prompting is not superior.** The claim that telling a model purely what *not* to do ("no robotic phrasing, no passive voice") beats describing the voice you want was **tested and refuted**. Always pair a positive voice description with the avoid-list.
- **Tells are not proof.** Humans now borrow these patterns too; presence of tells marks an LLM-influenced *style*, not necessarily machine authorship. Use this to improve writing, not to accuse.

---

## Sources

- Kobak et al., *Delving into LLM-assisted writing in biomedical publications through excess diction*, **Science Advances** (2025), DOI 10.1126/sciadv.adt3813 — preprint: arxiv.org/abs/2406.07016. *(Peer-reviewed; 15M+ abstracts; the empirical backbone.)*
- *Monitoring AI-modified content at scale* / PubMed excess-vocabulary analyses — pmc.ncbi.nlm.nih.gov/articles/PMC12219543/
- **Wikipedia: Signs of AI writing** — en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing *(community editorial consensus; the syntactic/phrase tells).*
- Smashing Magazine, *How To Improve Microcopy* (June 2024) — the "lead with essential information" and specificity fixes.
- NPR (2025) and every.to — the em-dash as cultural tell, with the rhythm caveat.
- Grammarly, *Common AI words*; walterwrites.ai — corroborating word-lists and substitution fixes *(vendor sources; multiply corroborated, treat as indicative).*

*Confidence: high on the empirical foundation and the structural fixes; medium on exact word-lists (time-sensitive) and on transfer from academic to marketing register (informed inference).*
