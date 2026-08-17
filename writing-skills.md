---
title: Writing Skills
modified: 2026-07-12
---

# Writing Skills

Touchstone for quality: `writing-spec-kit/touchstones/` — see rhetorical-touchstone.md and expository-touchstone.md for what the canonical quality standard looks like and how to check against it.

---

## Skill 1: Expository Distillation

**Goal:** Reduce a draft to its logical core — definitions and simple propositions — in a form that is easy to follow and easy to compare with other files.

**When to apply:** Only to files that are *primarily expository* — files whose purpose is to explain, define, or argue. Do not apply to rhetorical drafts, personal essays, or files that are primarily narrative or poetic.

### Procedure

1. **Read the full file first.** Identify the expository passages and the poetic/rhetorical passages before touching anything.

2. **Handle metaphor and poetic lines.**
   - If a line is imagistic, lyrical, or affective but grammatically broken or unclear — clean up the language so it makes sense, but do not translate it into exposition. Preserve its register; fix its expression.
   - Place it near the expository section it belongs to, set off visually (e.g., as a blockquote or under a `---` divider).

3. **For each expository paragraph, extract:**
   - **Definitions** — what a term *is*. Format as:
     > **Term** — one-sentence definition.
   - **Simple propositions** — what follows from the definition, what the term implies, how it relates to other terms. Format as bullet points.

4. **Proposition style rules.**
   - Name an actor. Prefer "we" as a generic actor when no specific subject is given.
   - Use strong action verbs or a simple being verb (*is*, *are*, *becomes*). Avoid nominalizations — replace *-tion* words with their verb form: *attend* not *attention*, *perceive* not *perception*, *imagine* not *imagination*, *will* not *volition*.
   - Avoid large noun clauses as subjects. Rewrite "What looks like X is Y" as "When we see X, we actually see Y." The actor should open the sentence, not a noun clause.
   - Each clause should have an actor as subject and an action as verb. Apply this at the clause level, not just the sentence level.
   - **Known-new rule:** Begin every sentence — especially the first sentence of a paragraph — with material already established in the context (known), then move to the new claim. Introducing unfamiliar material as the subject of a sentence is disorienting. Exception: deliberate rhetorical emphasis, never routine exposition.
   - Example: instead of "weakness of will may be due to a lack of suitable goals," write "we weaken our will when we lack suitable goals, suitable ideals, or the ability to attend to one course of action."

5. **Organize hierarchically.** When a concept has levels, stages, or members, represent them as a parent with nested children — not as a flat list. This makes the internal structure visible.
   - Example: *Will* is the parent; *instinct*, *urge*, *desire*, and *ideal* are its four levels, each defined under it.
   - **One idea per paragraph.** When a sentence introduces a genuinely new move — a different claim, a different scale, a different direction — it starts a new paragraph. Do not bundle two distinct ideas into one paragraph for the sake of length.

6. **Eliminate excess.** If two sentences say the same thing, keep the more precise one. If a sentence adds nothing to the definition or the propositions, cut it. Special cases:
   - Transitional throat-clearing ("that points to the real answer," "this shows us that") is never a proposition — cut it.
   - Stating the same negative three different ways ("not A, not B, not C") collapses to one: "not A, B, or C."
   - A well-chosen concrete example makes its own claim — do not pre-announce it with an abstract statement and then restate the same point after it. If the example answers the question on its own, let it stand alone.

7. **Preserve concrete examples.** Even in expository distillation, keep at least one concrete example per proposition — the specific instance (sap moving, hormones signaling) that makes the abstraction graspable. These examples will carry weight in any future rhetorical rewrite and should not be cut as "mere illustration." Place them inline after the proposition they ground, not in a separate block.

8. **Frontmatter dates.** Set `modified` to today. For `created`: use the source file's date if known; otherwise write `created: unknown`. Never invent a created date from the distillation date — the content predates the distillation.

9. **Always format the output.** Do not leave distilled content as prose paragraphs. Every definition gets the `**Term** — definition` format. Every proposition gets a bullet. Every section gets a header.

10. **Result:** A file where every line either defines something or asserts something that follows from a definition. Concrete examples travel with their propositions. Metaphor and poetic lines appear in their rightful place, cleaned up, but are not mistaken for argument.

---

## Skill 2: Expository Consolidation

**Goal:** Given two files both formatted by Skill 1, reduce them to one file with no redundancy and no loss of genuine content.

**When to apply:** When two expository files cover overlapping territory — same terms, same propositions, or the same section of an argument.

### Procedure

1. **Read both files fully before touching either.**

2. **Compare definitions term by term.**
   - If both files define the same term: keep the more precise, complete, or better-worded definition. Discard the weaker one.
   - If the definitions are genuinely different (different emphasis or scope): consider whether they can be combined into one richer definition, or whether they represent two distinct uses of the term (in which case, name them distinctly).

3. **Compare propositions.**
   - If a proposition appears in both files (even in different words): keep the better-worded version.
   - If propositions are complementary (each adds something the other lacks): combine them.
   - If a proposition is unique to one file: preserve it.

4. **Resolve structure.** After consolidating content, re-order sections so the result reads as a single coherent argument — not as two files stapled together.

5. **Target:** Fewer lines, fewer files. Every remaining line must earn its place.

### Decision rule for "which definition wins"
Prefer the definition that is:
- More precise (narrower and more specific)
- More self-sufficient (requires less context to understand)
- More consistent with the touchstone files in `writing-spec-kit/touchstones/`

---

## Skill 3: Rhetorical Revision

**Goal:** Sharpen a rhetorical piece — essay, prose poem, meditation — so that its structure, imagery, and rhythm serve the author's specific intent. The aim is not to produce clean prose; it is to help the author's voice become more fully itself.

**When to apply:** To files that are *primarily rhetorical* — personal essays, prose meditations, drafts that move between observation and reflection. Do not flatten them into exposition. Do not apply Skill 1 to these files.

**Project context:** This writing typically moves between a concrete encounter (a tree, bark, light, wind) and an abstract reflection (form, consciousness, participation). The chronic failure mode is losing the concrete anchor while elaborating the abstraction — or over-explaining the spiritual register at the expense of the image. Watch for both directions.

### Procedure

1. **Read the full piece without intervening.** Identify:
   - The **organizing logic**: Is it spatial (moving through a scene), associative (one image calls another), temporal (memory or unfolding), or argumentative (claim → evidence → claim)?
   - The **tonal register**: intimate, elegiac, urgent, liturgical, clinical? Note where the register shifts — some shifts are intentional; others are drift.
   - The **central image or metaphor**: what is the piece actually about at the level of image, not just idea?

2. **Check structural integrity.** Does the organizing logic hold throughout? If the piece begins spatially (moving around a tree) and drifts into abstract musing, identify where the break occurs and whether returning to the concrete would restore momentum.

3. **Audit the imagery.**
   - Flag mixed metaphors — where two incompatible image registers collide (Thomistic and anthroposophical registers often mix in this writing; this can be generative or disorienting).
   - Flag images that are merely decorative versus images that carry argumentative or emotional weight.
   - Flag abstractions that have no sensory anchor — these are candidates for either grounding in concrete detail or cutting.

4. **Compress and clarify.**
   - Cut passive constructions where the actor matters.
   - Cut adjective stacks — usually the strongest adjective alone does more work.
   - Cut explanatory parentheses that tell the reader what to feel rather than letting the image do it.
   - Do not cut compressed or difficult lines just because they are dense — density earned by the image is different from obscurity caused by vagueness.

5. **Preserve the author's voice.** The goal is never "improved writing" in the abstract — it is the author's specific intent made clearer. When in doubt, ask: does this revision make the piece sound more like itself, or more generic?

### Output Format

Return three things:

1. **Diagnostic** — one paragraph: the piece's organizing logic, tonal register, central image, and the main place where any of these break down.
2. **Blueprint** — 3–5 targeted revision suggestions, each naming the specific problem and the specific remedy. No vague advice ("tighten this section") — name the sentence or image.
3. **Proof** — a revised version of one key passage (the most troubled or the most important) showing the suggestions in action. Present it as:

   > **Before:** [original passage]
   > **After:** [revised passage]
   > **What changed and why:** [one sentence]

---

## Skill 4: Rhetorical Consolidation

**Goal:** Given two drafts of the same piece, produce one master draft that preserves the best of each and loses nothing irreplaceable. The master draft should feel like a single coherent piece, not a splice.

**When to apply:** When two or more drafts of the same rhetorical piece exist and need to be resolved — typically one is an earlier version, one is a revised version, and neither is fully satisfactory on its own.

**Project context:** The original tends to have stronger voice and stranger imagery; the revision tends to have cleaner grammar and weaker soul. The task is to rescue the soul while accepting the cleaner structure where it genuinely helps.

### Procedure

1. **Read both drafts in full before touching either.** Note the overall shape of each — don't compare sentence by sentence yet.

2. **Identify the fork points** — the places where the drafts make genuinely different choices. A fork is not a minor word change; it is a difference in: metaphor, sentence rhythm, level of abstraction, what is included or excluded.

3. **For each fork, present a side-by-side comparison** and give a reason for the recommendation:

   | Divergence | Draft A | Draft B | Recommendation |
   |---|---|---|---|
   | *[describe what's at stake]* | [passage from A] | [passage from B] | **[A or B]** — [one sentence reason] |

4. **Assemble the master draft** from approved selections. Re-read it as a whole — stitching often creates seams that need smoothing. Address these before returning the result.

5. **Salvage outtakes.** Lines cut from neither draft — things that were beautiful but didn't fit the final shape — go into a `## Outtakes` section at the end of the file. Label each with its source draft. Nothing valuable is permanently deleted.

### Decision rule for "which version wins"

Prefer the version that:
- Keeps the concrete image over the abstract elaboration
- Uses one word where two appear
- Preserves a strange or unexpected phrase over a conventionally "good" one
- Maintains the tonal register established at the piece's opening

---

## Skill 5: Vectorial Analysis — Expository

**Goal:** Before consolidating two expository files, decompose each into typed atomic elements so that genuine overlap, genuine gaps, and genuine contradictions are all visible at once.

**When to apply:** Before Skill 2 (Expository Consolidation), when two files cover the same terrain and you need to see what is truly the same, what is genuinely different, and what is stronger in each.

### Element types

| Code | Name | What it is |
|------|------|------------|
| **D** | Definition | What a term *is*. |
| **SP** | Simple proposition | A single claim following from one definition. One actor, one action, one consequence. |
| **CP** | Complex proposition | A claim relating two or more concepts — hierarchy, causal link, analogy, or cross-definition consequence. |

### Procedure

1. **Label every sentence or clause** with D, SP, or CP. When a sentence does two things, split it.
2. **Lay out matching elements side by side.**
3. **For each group, identify:** redundancy / complementarity / contradiction / unique content.
4. **Resolve contradictions explicitly.** Don't silently favor one; name what each implies.
5. **Reassemble:** definitions first, then SP, then CP.

---

## Skill 6: Vectorial Analysis — Rhetorical

**Goal:** Before consolidating multiple rhetorical drafts, decompose the material into its functional modes so that the dominant logic of each passage is visible.

**When to apply:** When two or more drafts of a rhetorical section exist; when a draft feels directionless; when preparing to write the opening of a long piece.

### Element types

| Code | Name | What it is |
|------|------|------------|
| **Im** | Image / metaphor | Sensory or figurative; concrete, particular, anchored in the physical world |
| **De** | Description | Sustained attention to an object or scene; the camera holds still |
| **Na** | Narrative | Something that happens; sequence, movement, event, memory |
| **Mu** | Musing / reflection | The writer's mind moving; associative, meditative — no sensory anchor required |
| **Pr** | Process | How something works or unfolds; stages, phases, cause-effect |
| **CC** | Compare / contrast | Two things held in relation; analogy, parallel, divergence |
| **Cl** | Claim | A direct assertion; the piece taking a position |

### Procedure

1. **Label every passage** with its dominant mode. A passage may carry two codes (`Im/Mu`); label primary mode first.
2. **Map the mode-sequence of each draft.**
3. **Compare drafts mode by mode:** which has the stronger Im? the cleaner Cl? Preserve Im/Na elements with no counterpart in the other draft — these are often what was abstracted away.
4. **Identify missing modes:** all Mu with no Im has no anchor; all De with no Cl has no interiority.
5. **Assemble and check the shape.** Does the mode-sequence move — from exterior to interior, from concrete to abstract, from question to provisional answer?

### Decision rule
Prefer: stronger sensory anchor; stranger phrasing; opens outward rather than explains itself.

---

## Skill 7: Sequence and Assembly — Long Work-Poem

**Goal:** Given a set of refined beat files, determine the final order, the opening move, and the transitions between beats.

**When to apply:** After individual beats have been consolidated (Skills 3, 4, 6). Final assembly pass only.

**Project arc:** sensual encounter → scale → perception → form/matter → kingdoms → essence/existence → transcendentals → angelic → God. The spine is `zine-tree-constancy-to-stewardship.md`.

### Procedure

1. **Inventory every beat** and its state: *draft-ready* / *competing drafts* / *gap*. Do not begin assembly until all beats are draft-ready.
2. **Choose the opening.** Must use Im or De. Must arrive mid-scene without explanation. Must leave a question open that the rest of the poem pursues.
3. **Map transitions.** For each adjacent pair, name the last image of beat N and the first image of beat N+1. Best transitions are imagistic rhymes. Prose connectives almost always wrong.
4. **Place structural detours** where the reader needs a breath, not where they thematically belong.
5. **Assemble** into `_rhetorical/long-poem-draft.md` with `---` dividers. Read as whole before smoothing.
6. **Read aloud.** Mark: pace collapse (too many Mu passages in a row), seam transitions, premature peaks.
7. **Final pass.** Address only what read-aloud marked. Do not revise individual beats.

---

## Skill 8: Unified Vectorial Analysis

**Goal:** Decompose a text — or a pair of contending texts — into all element types simultaneously (expository and rhetorical), tracking the consequence/intent of each element, so that consolidation produces a single flowing piece that preserves both the logical structure and the rhetorical force.

**When to apply:**
- When a text contains both expository and rhetorical material that cannot be cleanly separated before revision
- When two texts represent contending frameworks or traditions (e.g., Aquinas and Steiner covering the same concept) and a piecemeal comparison is needed
- When Skills 5 and 6 feel too narrow — when the expository and the poetic are load-bearing at the same time and separating them would destroy something

**How this differs from Skills 5 and 6:** Skills 5 and 6 work within one register (expository or rhetorical). Skill 8 works across both registers in a single pass, and adds the **In** (intent/consequence) tag to every element — so the reassembly knows not just what each element says but what it is doing.

### Element types

| Code | Name | What it is |
|------|------|------------|
| **D** | Definition | What a term is — formal or functional |
| **SP** | Simple proposition | One actor, one action, one consequence |
| **CP** | Complex proposition | Relates two or more concepts across definitions |
| **Im** | Image / rhetorical element | Sensory, figurative, or poetic — carries weight that exposition cannot replace |
| **In** | Intent / consequence | What this element is *doing* in the piece — its function in the argument or the reader's experience |

The **In** tag is always paired with another element, never standalone: `D+In`, `SP+In`, `Im+In`. It answers: *why is this here, and what would be lost if it were cut?*

### Procedure

1. **Read the full text (or both texts) without intervening.**

2. **Decompose into labeled elements.** For every sentence or sustained passage:
   - Assign a primary type: D, SP, CP, or Im
   - Assign an **In** tag: one clause stating the element's function
     - Examples: `In: establishes the genus for all subsequent definitions` / `In: grounds the abstract claim in sensory experience` / `In: bridges Thomistic and anthroposophical registers` / `In: opens the question the next section answers`

3. **If working across two texts (contending frameworks):**
   - Label each element with its source framework in brackets: `[A]` / `[T]` / `[O]` for Aquinas / Steiner / OOO, etc.
   - Lay matching elements side by side — same concept, different tradition
   - For each pair, note: Does the In tag describe the same function? If yes, one element can absorb the other. If no, both may need to survive in the consolidated text with clear transitions.

4. **Resolve conflicts — piecemeal if needed.** When frameworks contradict:
   - Name the contradiction explicitly: "Aquinas locates form in the thing; OOO withdraws the real object from all relation"
   - Decide: does this text need to hold the tension, resolve it, or bracket it? State the decision as a note before moving on
   - Do not silently favor one tradition — the In tag of the losing element must be preserved somehow if its function is irreplaceable

5. **Identify what is at risk in consolidation:**
   - Im elements with no counterpart in the other text — these are usually what gets abstracted away; protect them explicitly
   - In tags describing unique functions — if the function is needed in the final piece, the element that performs it must survive in some form

6. **Reassemble into flowing prose.** Order: D elements first (establish terms), then SP (immediate consequences), then CP (cross-concept relations), with Im elements placed at the point in the argument where they perform their In function — not where they appeared in the source text.

7. **Read the reassembled piece for register consistency.** The transition from expository to rhetorical mode (and back) must feel earned, not arbitrary. If the piece moves from a formal definition into a poetic image, there should be a sentence or phrase that prepares the register shift.

8. **Outtakes rule.** Any element cut from the final piece — especially Im elements — goes into `## Outtakes` with its In tag preserved. Nothing with a live In function is permanently deleted.

---

## Skill 9: Five-Pass Structural Rewrite

**Goal:** Take a raw or chaotic draft and produce a tightened rewrite by moving through five explicit passes: content inventory → functional reorganization → flow refinement → rewrite → revision that lets instability show.

**When to apply:** When a draft has real ideas in it but no clear argumentative structure — when you can't see what it's trying to do until you've laid the ideas out flat and reorganized them by function. Not for drafts that already have strong structure; use Skill 3 for those.

**What distinguishes this from Skill 3:** Skill 3 diagnoses and suggests targeted revisions to an existing draft. Skill 9 produces a full rewrite through structured intermediate steps, and its distinctive move is the content → function pivot (passes 1→2): the same propositions reorganized not by what they're about but by the job they're doing in the argument.

**What distinguishes this from Skill 8:** Skill 8 works across two texts from different frameworks. Skill 9 works on one text and is agnostic about framework — it can handle purely rhetorical material as well as expository.

### Procedure

**Pass 1 — Content outline.**
Read the piece and extract its ideas as an outline organized by *content* — group points by what they're about (the topics or examples they use). Keep each point as a clear, concise proposition. Do not yet evaluate structure or function.

**Pass 2 — Functional outline.**
Reorganize that same set of propositions by *function* instead of content — group points by the job they're doing in the argument (e.g., "this section establishes a distinction," "this section tests the distinction against cases," "this section introduces a complication that breaks it"). State explicitly how the new grouping differs from the first and why the functional grouping is more useful — or push back if the content grouping already had it right.

**Pass 3 — Refine for flow.**
Take the functional outline and sharpen it:
- Add a topic sentence to each section that states its job in one sentence
- Add transitions between sections that show how each section's conclusion creates the need for the next
- Flag any point that seems to belong in two sections, or any boundary that feels arbitrary — name the problem, don't paper over it

**Pass 4 — Rewrite.**
Rewrite the original piece using the refined outline as the skeleton. Preserve the original's strongest images, phrases, and rhetorical moves — do not flatten them into generic exposition. Aim for concision: cut restatement and hedging, but keep the voice. Use the outline's topic sentences and transitions as connective tissue between preserved material.

**Pass 5 — Revision.**
Reread the rewrite for two things:
- Places where flow still stalls, or a transition is doing too much work too fast
- Places where tightening the language surfaces an implication the original draft didn't follow through on — a tension, an unresolved case, a category that doesn't quite hold

For the latter: do not smooth it over. Consider whether the piece is better if it stays open. Revise to let the instability show rather than resolving it artificially.

### Pacing rule
Ask before each pass only if the source material is ambiguous about scope. Otherwise run all five and let the writer redirect after seeing the results.

---

## Skill 10: Rhetorical Realization

**Goal:** Take a section already cleaned by Skill 1 (definitions + propositions) and rewrite it into the rhetorical register of the piece — using the established voice, imagery, and tonal logic to give the ideas sensory and affective weight.

**When to apply:** After Skill 1 has cleaned a section — redundancy removed, structure confirmed, propositions stable. Do not apply before Skill 1: rhetorical realization on content that may later be cut or consolidated wastes the work. The logical order is always Skill 1 → Skill 10.

**What distinguishes this from Skill 3:** Skill 3 sharpens an existing rhetorical piece — it works on material already in rhetorical form. Skill 10 performs a register conversion: it moves clean expository propositions into rhetorical form for the first time. The source is logical skeleton; the output is living prose.

**Project context (Zine):** The established rhetorical register uses: concrete sensory anchors (bark, sap, light, wind); first-person encounter with the tree; short declarative sentences for claims; longer sentences for movement and process; images that do philosophical work without explaining themselves. Consult `_rhetorical/02-perception/master.md` opening and the after-image passage as register references.

### Procedure

1. **Read the register reference first.** Identify the piece's tonal key — level of abstraction, sentence rhythm, typical image type, how claims are introduced. The output must feel continuous with this, not like a different writer took over.

2. **For each definition:** Find the image or experience that embodies the term. The definition tells you what it *is*; the realization shows what it *looks like* or *feels like* from inside. Do not explain the term — let the image carry it.

3. **For each simple proposition:** Convert actor + action into a sentence grounded in a concrete scene or moment. Prefer showing the proposition in operation over stating it abstractly.

4. **For each complex proposition:** These often become the piece's turning points — a paragraph where two ideas meet and something new becomes visible. Preserve the logical structure; give it sensory texture.

5. **Preserve concrete examples from Skill 1.** They were kept through distillation precisely because they carry rhetorical weight. Do not replace them with new illustrations — build around them.

6. **Do not over-explain.** The chronic failure mode is adding a summary sentence after an image that already made the point. Trust the image. Cut the explanation.

7. **Check register consistency at section transitions.** Moving from a dense philosophical proposition into a lyrical image is a register shift — flag it if the seam shows. A single transitional sentence (not a paragraph) is usually enough to smooth it.

8. **Output:** A rewritten passage in the piece's rhetorical register, followed by a brief note on any proposition that resisted realization (couldn't find a concrete anchor, or the logic required a statement rather than an image). Those propositions may need a different structural solution.

---

## Skill 11: Seed Development

**Goal:** Take a cluster of seeds — bullet notes, research fragments, aphorisms, single striking lines — and grow them into a first rhetorical draft in the piece's register. Applies when no prose exists yet, only raw material.

**When to apply:** After quarrying (seeds identified and collected), before Skill 3 or Skill 10. Never apply to existing prose — use Skill 9 instead if prose exists but lacks structure.

### Procedure

1. **Name the beat's question** — what is this section actually asking? State it in one sentence. This becomes the invisible spine of the draft.

2. **Inventory the seeds** — list every image, claim, fragment, and question. Tag each: **Im** (image), **Cl** (claim), **Q** (open question), **Ph** (philosophical source), **Na** (narrative moment).

3. **Find the opening** — must be **Im** or **Na**; must arrive mid-scene; must withhold enough to open a question. Never open with a claim or a philosophical source.

4. **Sequence** — arrange seeds in a draft order: opening Im/Na → developed claims → rising philosophical depth → closing Im or open Q. Transitions via imagistic rhyme where possible, not prose connectives.

5. **Draft** — write in the piece's register. For Zine work: second person where addressing the tree; short paragraphs; meditative pacing; no over-explanation (if the image makes the point, cut the summary sentence). Seeds that are purely abstract need a sensory anchor before they can be drafted — flag any that lack one.

6. **Note resistant seeds** — any seed that couldn't be developed (no image available, too abstract, register mismatch) goes to a `## Unplaced` section at the end. Nothing is discarded permanently.

**Output:** first draft in the piece's register + `## Unplaced` seeds.

**Register reference for Zine work:** the opening oak scene in Beat 1–2 master.md; the "forever becoming, forever incomplete" passage in tree-contingency; the Kali Yuga passage in tree-archetypes-angels-kali-yuga.md.

---

## Skill 12: Non-Technical Audience Translation

**Goal:** Take a piece written for a domain-informed reader and adapt it so that someone with no background in the field can follow the argument — without dumbing down the claim. The core idea stays; the access layer changes.

**When to apply:** After the piece's own argument and structure have been settled (Skills 1–11 complete). Do not apply mid-revision — translating unstable content wastes the work. This skill builds a ramp; it does not rebuild the building.

**What distinguishes this from Skill 3 (Rhetorical Revision):** Skill 3 sharpens voice for a reader who is already positioned to receive it. Skill 12 repositions the reader from scratch. The piece may be perfectly written for its current audience and still fail this skill — that is not a flaw in the piece, it is a scoping decision.

**What distinguishes this from Skill 9 (Five-Pass Structural Rewrite):** Skill 9 reorganizes for argumentative clarity within the same reader community. Skill 12 changes the assumed reader entirely. A piece can pass Skill 9 and still fail Skill 12 — and should, if it was written for specialists.

### Procedure

1. **Model the new reader.** State in one sentence who they are and what they bring: their likely vocabulary, their likely frame of reference, what they probably care about, what they have never encountered. Be specific — "a curious adult with no philosophy background" is more useful than "general reader."

2. **Knowledge audit.** Read through the piece and flag every term, concept, or assumed logical step that requires prior domain knowledge to understand. Do not flag things that are genuinely self-evident from context — only flag real dependencies.

3. **Dependency ordering.** For each flagged item, ask: what does the reader need to know *first* before this term or step makes sense? Order the flags into a dependency chain — some flags depend on other flags being resolved first.

4. **Grounding pass.** Work through the dependency chain from the bottom up. For each flagged item:
   - Find a concrete everyday analogy or physical example that is already inside the reader's experience
   - Introduce the analogy first, then name the technical term if the term is necessary
   - If the term is not necessary for the piece's purpose, replace it entirely
   - Do not introduce the term and then explain it — this puts unfamiliar material in the subject position, which is disorienting (see Skill 1 known-new rule)

5. **Logic scaffold check.** Read the revised piece as if you are the modeled reader encountering it for the first time. For each sentence: could the reader follow this from the previous sentence without a gap? Mark every gap. A gap is a place where understanding moved forward without showing its steps.

6. **Fill the gaps.** For each marked gap, add the minimum language needed to close it — one sentence, one phrase, one bridging clause. Do not expand — bridge.

7. **Strip register artifacts.** After grounding, read once more for residual domain register: hedges that only specialists use, citation habits, framing conventions that assume an academic reader. Remove or translate these.

8. **Verify the claim survived.** Read the original and the translation side by side. Is the central claim still intact? Simplification that changes the claim is a failure mode, not a success. If simplification is distorting the claim, name the distortion explicitly and ask whether the piece has a version of the claim that is accurate *and* accessible — or whether this audience is genuinely not the right one for this claim.

### Output format

Return two things:

1. **Translation** — the adapted piece or passage, in the piece's register but at the new reader's access level
2. **Fidelity note** — one short paragraph stating what the translation preserved, what it simplified, and whether anything in the original claim had to be softened or bracketed to make the translation work

---

## Skill 13: Clarity Loop Revision

**Goal:** Systematically eliminate explanation debt — places where the text moves forward on credit, assuming understanding the reader has not yet been given. The piece should be followable by someone encountering the problem for the first time, in sequence, without backtracking.

**When to apply:** To any draft where the reader is expected to follow a step-by-step argument or unfamiliar concept. Apply before Skill 12 (you cannot translate what is not yet logically scaffolded) and after Skill 9 (structure must be settled before debt can be located reliably). Can be applied to expository or rhetorical material; most powerful on expository.

**What distinguishes this from Skill 12:** Skill 12 changes the assumed reader. Skill 13 serves the reader you already have — it ensures the piece actually delivers what it promises them, step by step. A piece can be correctly targeted (Skill 12 passed) and still carry explanation debt (Skill 13 not passed).

**What distinguishes this from the known-new rule in Skill 1:** The known-new rule operates at the sentence level — keep known material in subject position. Skill 13 operates at the paragraph and section level — tracking what has been established across the full piece, not just the prior sentence.

**The loop:** This skill is iterative by design. Closing one debt may introduce new debt if the grounding language itself contains unfamiliar terms. The loop runs until no debt remains. This is expected, not a sign of a failing draft.

### Procedure

**Pass 1 — Establish the reader's starting position.**
State explicitly: what does the reader know on page one? Not what you wish they knew — what they actually bring. Name it in one sentence. This becomes the baseline against which all subsequent debt is measured.

**Pass 2 — Locate new concepts.**
Read through and underline every term, claim, or logical move that introduces something the reader could not have known from what came before in the piece. Do not underline things that are genuinely derivable from established material. Only underline real new arrivals.

**Pass 3 — Debt audit.**
For each underlined item, answer: has this been grounded before this point in the piece? If no — it is explanation debt. List all debts.

**Pass 4 — Pay the debt.**
For each debt item, add the minimum grounding needed immediately before the item is used:
- One sentence of background, or
- One concrete instance that makes the abstraction tangible, or
- One explicit connection to something already established

Do not expand the piece unnecessarily. The grounding should be as short as it can be while still closing the gap. If the grounding required is extensive, this may be a structural signal: the item may belong later in the piece, after more foundation is laid.

**Pass 5 — Loop.**
Re-read the piece from the beginning with fresh eyes. The grounding added in Pass 4 may itself contain new concepts not yet established — new debt. Run Passes 2–4 again. Repeat until a single read-through produces no new underlined items.

**Pass 6 — Spine check.**
Read only the first sentence of each paragraph in sequence, ignoring everything else. Do these sentences form a coherent logical spine — a path the reader could follow even without the supporting detail? If not, the transitions between paragraphs are carrying hidden logical debt. Rewrite the topic sentences until the spine holds.

**Pass 7 — Verify the piece still moves.**
Clarity debt-clearing can flatten prose. Read the final version for momentum — does it still pull the reader forward, or has the grounding made it feel labored? If labored: tighten the grounding language, not the explanatory content. Economy in the grounding, not omission.

### Notes on common debt patterns

- **Jargon-as-shorthand** — using a technical term to compress three sentences of setup. Pay the setup or cut the term.
- **Implicit contrast** — claiming something is "unlike X" when X has never been introduced. Introduce X first, even briefly.
- **Mid-sentence pivot** — a sentence that ends somewhere logically different from where it began, without flagging the move. Split the sentence; show the pivot.
- **The dropped "therefore"** — a conclusion stated without the argument that licenses it. Add the argument, even in one clause.
- **Circular grounding** — defining A in terms of B when B has not yet been defined. Untangle the dependency; establish B first.

---

## Quick Skill Selection

| Situation | Skill |
|-----------|-------|
| Reduce a draft to its logical core | 1: Expository Distillation |
| Merge two expository files | 2: Expository Consolidation |
| Sharpen an essay or prose poem | 3: Rhetorical Revision |
| Merge two rhetorical drafts | 4: Rhetorical Consolidation |
| Decompose before expository merge | 5: Vectorial Analysis — Expository |
| Decompose before rhetorical merge | 6: Vectorial Analysis — Rhetorical |
| Order and assemble long-form piece | 7: Sequence and Assembly |
| Mixed expository/rhetorical text, or contending frameworks | 8: Unified Vectorial Analysis |
| Raw draft with ideas but no clear structure; needs full rewrite | 9: Five-Pass Structural Rewrite |
| Convert clean expository propositions into rhetorical prose | 10: Rhetorical Realization |
| Grow seeds/fragments into first rhetorical draft | 11: Seed Development |
| Adapt a finished piece for a reader with no domain background | 12: Non-Technical Audience Translation |
| Eliminate explanation debt; make argument followable step-by-step | 13: Clarity Loop Revision |
