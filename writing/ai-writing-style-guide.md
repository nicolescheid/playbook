# Avoiding AI Writing Tells — A Practical Style Guide

*A portable, evidence-based reference for making copy read like a person wrote it — usable for hand-editing text and for steering language models. Application-agnostic; drop it into any project.*

Last reviewed: 2026-09. This is a moving target — see [Caveats](#caveats-read-these).

---

## The one principle

There is no single word or mark that proves text is AI-generated. The reliable signal is **density of "style words" plus a handful of structural habits**. One inflated word is coincidence; six in a paragraph, stacked with antithesis and tidy triplets, is the tell.

So don't hunt for banned words. Fix the **structure and the verbs**, lead with the point, and be concrete. That survives as the models change; word-lists don't.

---

## The checklist

### 1. Negative parallelism / antithesis — check this first

*"Not just X, but Y." "It's not… it's…" "Not only… but also…"* The highest-frequency, highest-value fix on this list. It reads as if correcting a misconception nobody raised — and it's a voice issue, not just a detection one; more on that further down.

- Before: *"It's not just a notebook — it's a thinking tool."*
- After: *"It's a notebook for thinking things through."*

### 2. Lexical — inflated words and verbs

**Excess "style words."** A small set spiked sharply after late-2022 and now reads as a marker. Flag on sight when they cluster: *delve, underscore, showcase, tapestry, testament, pivotal, intricate, meticulous, robust, seamless, vibrant, commendable, comprehensive, crucial, notably, navigate, landscape, realm, foster, elevate, unlock, journey, unpack, leverage, game-changing.*
> Density matters more than any single word. Treat these as smoke, not fire.

**Inflated verbs / dressed-up copulas** (the higher-leverage fix — ~two-thirds of tells are verbs). AI replaces plain `is / has / does` with marketing verbs: *serves as, boasts, features, offers, stands as, represents, leverages, empowers, fosters.*
- Before: *"Gallery 825 serves as the association's exhibition space."*
- After: *"Gallery 825 is the association's exhibition space."*

**Fix:** cut or swap for the plain word; reserve an elevated verb for when it carries real meaning. Substitute *plainness + specificity* (`seamless → smooth`; `exemplary → excellent`).

### 3. Syntactic — the rest of the structures that give it away

**Rule-of-three tricolons** — three balanced items in a row, used to make a thin point feel complete. *"A map, a librarian, and a guide."* Break them; keep one, or use an uneven number.

**Mechanical parallelism** — every sentence the same shape and length. Vary it. Let one sentence be short. Use a fragment.

### 4. Punctuation — the em-dash, in proportion

The em-dash (the "ChatGPT hyphen") is overused by models far beyond human frequency, so it has become a *perceived* tell.
**Fix:** replace decorative dashes with full stops, commas, or colons; keep the ones doing real work.
**Caveat:** em-dashes alone are **not** proof of AI — plenty of strong human writers love them, and removing them won't fool a detector. Rhythm is the deeper signal. Moderate, don't purge.

### 5. Phrase templates & signposting

Cut these on sight: *"In today's world / fast-paced world," "It's worth noting that," "In conclusion," "A testament to," "Navigating the landscape of," "Plays a pivotal role in," "Here's the thing," "Let's dive in," "When it comes to…"*

**Fix:** delete the warm-up and **lead with the essential information.** Delete hollow conclusions that just restate the body.
- Before: *"Oops! Unfortunately, it looks like something went wrong on our end."*
- After: *"That didn't save. Try again in a moment."*

### 6. Tone & abstraction

Vague abstraction and relentless positivity are core tells. So is reflexive both-sides hedging (*"on one hand… on the other…"*).

**Fix — the highest-leverage move of all: replace abstraction with specifics.** Real numbers, real dates, the person's own words.
- Before: *"Your deposit limit is reset on a monthly basis."*
- After: *"Until 31 January, you can deposit £400 more."*

### 7. Formatting and Claude-specific tells

**Bold-first bullets** — every list item opening with a bolded phrase; almost nobody formats by hand this way. **Wh- headers**, *"What we do differently," "Where the market is stuck."* **Title Case Headings** instead of sentence case. **Unicode decoration** — smart quotes, → arrows, and other characters nobody types by hand. **Signposted conclusions** — *"In conclusion," "To sum up."*

Worth extra vigilance if the draft came from Claude specifically: em-dash frequency past the general caveat above, the → arrow more than other models produce it, **"we" for "I"** in material that's clearly one person's voice, and forced figurative language that repurposes a word from the prompt as an unrelated metaphor.

---

## What human writing does that AI tends not to

- **Specificity** — concrete detail over category words. A particular Tuesday, not "recently."
- **Asymmetry** — uneven sentence lengths, the occasional fragment, a sentence that ends sooner than expected.
- **Restraint** — says one thing well and stops. Doesn't summarise itself.
- **Voice** — a point of view, mild opinion, the odd plain or blunt word.
- **Plainness** — trusts a simple word. "Use," not "utilise." "Is," not "serves as."

---

## Mirroring, not stripping

The patterns above aren't broken as moves — contrast, reveal, understatement are real rhetorical tools. A model reaches for the clean, symmetrical, empty version instead of paying for the effect with something specific. Cutting a tell outright often just goes flat. Keeping the effect while changing what carries it usually works better.

Break the symmetry instead of matching the pair — an idiom flip or a real specific question in place of the second half reads as considered, not templated. Or swap an adverb for a concrete image: "quietly" becomes what unnoticed actually looked like.

The test either way: does this sentence say something a slightly different sentence wouldn't? If the "Y" alone would say the same thing, the setup was decoration.

## The antithesis rule is really a voice rule

The usual reason to cut "not X, but Y" is that it reads as machine-written. There is a stronger reason underneath.

The construction carries a stance. It positions the writer as correcting the reader, and it makes its point by pushing against something instead of standing on its own. For a writer who is temperamentally optimistic, that stance is borrowed, and every instance moves the copy a little further from how they actually think. The tell is the symptom. The imported stance is the problem.

That reframing changes the fix:

- Cutting the negative half is the minimum. It removes the tell.
- Rebuilding the sentence in the affirmative is the real fix. It restores the stance.

Worked examples, all from live copy:

| Machine-shaped | Affirmative |
|---|---|
| sensitivities are instincts, not a checklist | those sensitivities are instinctual to me |
| safety is part of the process, not an afterthought | safety is part of the process |
| usage numbers are activity, not value | usage numbers measure activity, and value needs a different lens |
| the second dip isn't a bad sign, it's the sign you're attempting something real | the second dip is the sign you're attempting something real |
| speed and rigour aren't opposites, they're integrated | speed and rigour are integrated |
| it isn't only the message but the medium | it's both the message and the medium |
| a capability failure, not a model one | a capability story: the models worked, the enablement had not caught up |
| the job isn't getting people to use AI, it's getting the output to hold up | the job is getting the output to hold up |

The last row is the pattern in miniature. The affirmative version is shorter, says the same thing, and sounds like someone with a view rather than someone issuing a correction.

Extend it past sentence shape. If you genuinely see problems as the work ahead, write them that way.

## Keep a carve-out list

A blanket rule will strip phrases that are genuinely yours. Some contrasts are the whole idea, and some are established brand.

Before applying the antithesis rule to a body of work, write down the phrases that stay, and name them explicitly wherever the rule is stated, so anyone or anything editing on your behalf leaves them alone.

A carve-out earns its place when:

- The comparison is the actual content, and dropping half of it loses information.
- The phrase is established: a title, a tagline, a term people already associate with you.
- You say it out loud, in that shape, and it sounds like you.

Everything outside the list states the thing once, in the affirmative. `voice-spec-template.md` has a place to write it down.

## Let the facts speak

After stating a fact or piece of evidence, don't follow it with a sentence
that tells the reader what to conclude from it. State the fact. Stop.

This shows up as two patterns to cut on sight:

- **Thesis-first framing** — announcing the point before the evidence that
  proves it. ("I am the kind of person who does X: [evidence].") Cut the
  announcement; let the evidence open the paragraph.
- **Restating the implication** — a closing sentence that says the same
  thing the prior sentence already showed, just more explicitly, or spells
  out a connection the reader would make unprompted.

Test: read the sentence in isolation. If it contains no new information,
only a verdict on the information before it, cut it.

Example (cover letter):
- Before: "I built the components a capability strategy depends on: a
  practitioner forum, training pathways, a livestream, coaching. What I'd
  bring to this role is that same pattern, systematised: defining the
  framework end to end, not assembling it component by component after
  the fact."
- After: "I built the components a capability strategy depends on: a
  practitioner forum, training pathways, a livestream, coaching."
  (The reader draws the conclusion. The second sentence added nothing but
  volume.)

Applies to cover letters, CVs, and any persuasive writing. Does not apply
to genuinely new information delivered as a short, direct statement,
only to sentences whose sole job is telling the reader how to feel about
a sentence that already did the work.

---

## The 60-second edit pass

1. **Verbs:** change every `serves as / leverages / fosters` to `is / uses / helps`.
2. **Antithesis:** find every "not just… but" and "it's not… it's…" — rewrite as one direct statement.
3. **Openers:** delete the first clause if it's a warm-up; start at the real point.
4. **Triplets & dashes:** break one rule-of-three; replace one decorative em-dash with a full stop.
5. **One specific:** swap the vaguest sentence for a concrete detail (a number, a name, a real example).
6. **Verdicts:** after each piece of evidence, cut the sentence that tells the reader what to conclude from it.

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
State what something is and stop. Say it in the affirmative rather than defining it
against what it isn't.
Give the evidence and stop. Don't add a sentence telling the reader what to conclude from it.
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
- State what something is and stop, in the affirmative, rather than defining it against
  what it isn't.
- Give the evidence and stop. Don't announce the point before the evidence, and don't
  follow the evidence with a sentence telling the reader what to conclude from it.

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

### Making it stick

A rule the model was only pointed at is weaker than one sitting in its context. Put it in the prompt, not behind a link.

In a long system prompt, a style rule near the top competes with everything after it. Restate the two or three that matter most near the end, where recency helps — a prompt that grew from roughly 3,500 to 9,000 tokens needed its brevity and voice rules repeated there to hold. Name the carve-out list inside the prompt too, or the model over-applies the rule and strips real voice along with the tell.

None of this replaces review. Reading this guide in full before writing did not reliably prevent the tells in practice — treat the prompt block as reducing the rate, not eliminating it, and keep a human pass.

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
- tropes.fyi (ossama.is) — the formatting and Claude-specific tells, marketing/LinkedIn/CV register.

*Confidence: high on the empirical foundation and the structural fixes; medium on exact word-lists (time-sensitive) and on transfer from academic to marketing register (informed inference). The positive-voice and carve-out material is applied editing practice, not corpus study — a working method, tested once, not a measured finding.*
