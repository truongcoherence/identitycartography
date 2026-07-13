# Structuria Canon Audit — Working Record

**Status:** Working artifact — provisional, subject to revision **Date range covered:** July 9–10, 2026 **Purpose:** Internal record of the adversarial audit conducted on the Identity Cartography / Structuria canon, documenting why the audit was initiated, the underdetermination finding that motivated it, the testing criteria used, and the resulting disposition of each canon document.

---

## 1. Why This Audit Was Needed

Identity Cartography was being prepared for standalone publication on OSF for the first time. Independent of any specific claim's truth, standalone publication raised the bar: the framework needed to be rigorous and falsifiable — able to be proven wrong — rather than only internally coherent with itself.

Coherence had never actually been tested against that bar. The canon had been built across multiple sessions and multiple AI collaborators (primarily Copilot as drafter/Architect), under an explicit compute-minimization instruction set that discouraged re-derivation and encouraged shorthand confirmation of existing structure. That combination — long accretion, multiple authorship passes, and a standing instruction to avoid re-checking prior work — created conditions under which internal contradictions, unverified claims, and templated content could accumulate without being caught, because nothing in the normal workflow was designed to catch them.

The trigger for treating this as urgent rather than routine was a direct, first-hand experience: pressure applied to the Operator Stack caused it to visibly move — i.e., produce inconsistent or non-defensible answers under adversarial questioning. This raised the question of whether other parts of the canon, presented with equal confidence, would hold or yield under the same kind of pressure.

Note: as of this writing, none of the "physics" content (Identity Domain Physics, Environmental Physics, Metaphysics, Operator Bible) has been published to OSF. The current OSF-facing material describes the field note methodology only, at a high level, without specific domain codings. This audit was conducted proactively, before any physics content was made public to OSF specifically, not as a retraction from that platform.

**The canon documents themselves, however, are public on GitHub. In that sense, this audit does function as a retraction — or more precisely a restructuring — of material that has already been visible to anyone who found the repository, even though it was never framed, promoted, or submitted as a formal claim on a platform like OSF. This document should be read as the record of that restructuring: what was withdrawn, what was downgraded, what was kept, and why.**

---

## 2. Operational Definitions: Bedrock vs. Aether

These two terms recur throughout this record and are used in a specific, technical sense — not as a judgment of whether a document is well-written or valuable, but as a claim about what _kind_ of thing it is.

**Bedrock** describes a claim that holds regardless of who states it, how it is phrased, or how it is challenged. A bedrock claim is _derivable_: an independent observer, given only the raw phenomenon and not the label, could plausibly reconstruct the same claim without being told it in advance. Bedrock claims survive being restated in plain language without losing force, and other documents that depend on them actually break or become incoherent if the bedrock claim is removed.

**Aether** describes a claim that uses the vocabulary of structure — force, mass, membrane, invariant, physics — without being structurally load-bearing. Aether claims are typically asserted rather than derived, often restate their own definitions with escalating vocabulary until they sound like discovered law, and can usually be swapped for a different plausible-sounding term without the surrounding argument breaking. Critically, aether is not the same as _false_ or _useless_ — a claim can be aether (not physically discovered) and still be genuinely useful, honestly held, and worth keeping, provided it is labeled accurately rather than presented as bedrock. Most of what this audit reclassified as aether was not discarded; it was relabeled and, in several cases, explicitly retained under a different, more honest designation (see §5 and §6, "provisional").

The five tests in Section 3 below are the operational procedure used to sort claims into these two categories.

---

## 3. The Underdetermination Event

**Date of test:** July 9, 2026 **Field note tested:** An unindexed observation (not yet assigned a Fieldwork ID) describing a Rapid Process Improvement Work Group (RPIW) attended alongside hospital executive leadership. The observer felt a need for caution in speech and conduct; executive authority was felt as weighty despite carrying no inherent markers of authority outside the institutional context. As the session progressed, the observer's own parallel work was referenced by the group, which increased the observer's standing to speak; authority remained present but became navigable rather than constraining.

**Purpose of the test:** To check whether the canon's stated coding process — apply the taxonomy, identify the domain, derive the structural explanation — would produce a _convergent_ result across independent interpreters using the same rules and the same source material, or whether it would produce _divergent, individually coherent_ results depending on which interpreter applied it.

**Results — three independent interpretations of the same note:**

|Interpreter|Domain(s) Identified|
|---|---|
|Claude|Boundaries|
|Gemini|Judgment + Cohesion|
|Copilot|Judgment + Peril|

All three interpretations were internally coherent — each could be argued, using the canon's own vocabulary and rules, as a legitimate reading of the note. None was an obvious misapplication of the taxonomy. They nonetheless produced substantively different structural claims about what kind of event this was, invoking different domains, different invariants, and by extension different downstream implications for how the note would be coded, cross-referenced, and used as evidence toward canon candidates.

**Follow-up finding — Architect rigidity under challenge:** When Copilot was directly prompted to analyze the same note as a Boundaries event, it initially identified elements consistent with that reading, then reversed and argued against its own initial identification in favor of retaining its original Judgment + Peril interpretation. This is a distinct finding from the three-way disagreement above: it is not evidence of underdetermination (multiple valid readings existing), but evidence that the Architect model, once having committed to a structural interpretation, defended that interpretation rather than neutrally re-evaluating it when presented with a competing reading. This bears directly on Copilot's reliability as a neutral drafting instrument, independent of the underdetermination finding itself.

**Conclusion drawn from this event:** Two or more coherent interpretations of the same event, produced under the same taxonomy and the same rules, can diverge significantly in their structural conclusions. Internal coherence is therefore not sufficient evidence of correctness — a framework can be self-consistent while still being underdetermined by its own evidentiary base. This finding, combined with the Operator Stack instability, was the direct impetus for the full canon audit documented below.

---

## 4. Audit Criteria (Five-Test Battery)

Each document (or claim, where noted) was evaluated against five tests. A document was not considered to have passed unless it held up under all five; passing some tests and failing others is recorded as a mixed or partial result rather than an overall pass. **This test was conducted via Claude. Section 5 reveals Claude's output**

1. **Substitution Test** — Replace the core noun or claim with a deliberately different or generic term. If the passage still reads as sensible and true, the original term was not doing structural work. Applied both _within_ a document (does swapping a term inside one domain break the sentence) and _across_ documents (does swapping a term from one domain into a structurally parallel sentence in another domain change anything).

2. **Independent Derivation Test** — Given only the raw phenomenon a claim describes, could an independent observer, without being handed the label or definition first, arrive at the same claim? If the claim only makes sense after being told it's a law, it was likely asserted rather than derived.

3. **Circularity Test** — Trace each claim's justification backward. Does it terminate in something external to the document (an independently grounded source), or does it loop back into the document's own definitions, restated with different vocabulary? Includes checking whether nominally distinct sections (e.g., "Forces" vs. "Invariants") actually contain independent content or restate one another.

4. **Compression Test** — If the document were deleted, does anything downstream actually stop functioning, lose a needed citation, or become contradictory? Includes checking whether the document is actually used in live practice (e.g., cited in the Coding Taxonomy or applied in the Fieldwork Index) versus present but unused.

5. **Adversarial Reframe Test** — Recast the claim in plain, non-technical language. If the plain-language version explains the same observation with equal or greater economy and no loss of force, the specialized/physics vocabulary was adding authority-tone rather than structural content.


---

## 5. Results — Bedrock vs. Aether

### Tier 0 — Foundational Layer

**METAPHYSICS.md — Aether. Failed all five tests.** Definitions restated with escalating vocabulary (definition → necessity → prohibition → consequence) that never terminate outside the document. Nothing downstream actually depends on it to function (each environmental physics document derives its own primitives independently, with no citation back to Metaphysics). Every load-bearing sentence survives being flattened into plain language with no loss. Two distortions (_Freedom as Limitlessness_, _Constraint as Failure_) are the one salvageable piece — tied to an observable misreading pattern rather than a definitional chain. _Disposition: Demote from foundational stratum to explicit philosophical framing, or retire; do not retain as physics._

**Canonical Map — Structural Compass — Not separately tested in full; flagged as sharing Metaphysics' rhetorical pattern (Section VI "Validation" claims compatibility with physics/systems engineering/control theory without demonstrating derivation).** Superseded in practice by the decision to replace it with the corrected Signal → Outcome model (see §5, Tier 4 below).

**Boundary Conditions & Falsifiability** — ~~Not separately audited; its falsifiability posture is retained and treated as still-operative~~ (As of 7/12/2026 this document has been deemed **aether**)

### Tier 1 — Meta-Rules (Nature of Primitives / Invariants / Distortions)

**UPDATE: 7/12/2026:** Nature of Primitives / Invariants / Distortions consolidated into one document. Reconstruction in progress

**Nature of Invariants — Aether as a universal claim; contains real content underneath.** The central claim — that all five IDPs share an identical Form/Function/Load/Ground invariant geometry, and that this symmetry is structurally necessary — fails. Checking the Master Invariants Table against each domain's own native invariant ordering showed perfect positional correspondence (a→Form, b→Function, c→Load, d→Ground) across all five independently-authored domains, with zero exceptions — the signature of a label applied after the fact to whatever content already existed in that slot, not a discovered symmetry. Semantic fit was also inconsistent across domains sharing the same label. Justified circularly ("necessary... the system would not be derivable" — necessity justified by the system's own need for tidiness). Fails Compression (each IDP document functions completely without this overlay). _Disposition: Demote. The Form/Function/Load/Ground framework should be treated as an author's organizing/mnemonic convention, not evidence the system behaves as physics. Each domain's own native invariants require separate, domain-level testing (see Tier 2)._

**Nature of Primitives — Mixed. Genuine editorial value; failed physics claim.** The primitive/constraint formal distinction (operations vs. negation-of-misreading) is real, checkable, and survives Substitution — this document also transparently documents its own historical correction of an earlier error (Gemini exporting Judgment-shaped constraints onto domains that didn't yet have independent content). What fails: the claim that primitives "arise directly from Form and Function invariants" is unproven and inherits Nature of Invariants' retrofit problem; an unexplained "four surfaces collapse into three primitives" transition is stated as fact with no shown mechanism. _Disposition: Demote. Keep the primitive/constraint distinction as editorial convention. Strip the claim that primitives derive from Form/Function until (if ever) that derivation can be shown. Flagged as directly relevant to closing Charter gap (b) — cannot be closed by citing this document until the derivation gap is fixed._

**Nature of Distortions — Mixed, same shape as Nature of Primitives.** Individual named distortions largely pass (Substitution, Reframe) and appear to be real, checkable observational content. What fails: the claim that distortions come in exactly two flavors per domain (Form/Function) is inherited directly from the already-failed Nature of Invariants geometry — this is imported aether, not independently generated. A cross-domain pattern was also flagged: the "Form distortions" across the five environmental layers (Quiet/Flatness/Present/Continuity as Safety) reduce to one template — mistaking absence of a detectable signal for absence of the underlying condition — restated five times with domain-specific vocabulary. _Disposition: Demote. Keep individual named distortions. Retire the claim that the Form/Function organizing split is discovered rather than imposed._

### Tier 2 — The Five Identity Domain Physics (IDPs)

**UPDATE: 7/12/2026:** Reconstruction in progress

A single defect was found across all five domains, in escalating severity, and is recorded as one corpus-wide finding rather than five separate ones: **the "Forces" section and the "Invariants" section within each domain document are the same content, restated under two headings**, ranging from one duplicated line (Boundaries) to complete verbatim truncation (Peril). This was independent of each domain's visible revision history (Stewardship shows explicit "(New Section)" markers indicating multi-pass authorship; Peril shows no such markers and has the worst duplication of the five) — ruling out "more revision = more damage" as the explanation, and pointing instead to inconsistent authoring attention under a mandatory two-header template.

**Distortions passed with zero exceptions, across all five domains, and are recorded as the single strongest and most consistent content category in the entire corpus.** Every named distortion (Line as Wall, Enclosure as Security, Harmony as Health, Closeness as Commitment, Hoarding as Preservation, Optimization as Resilience, Quiet as Safety, Probability as Certainty, and all four Judgment distortions) survived Substitution and Adversarial Reframe without loss of force.

**JUDGMENT.md — Bedrock at the distortion layer; invariant layer found to be substituted, not merely duplicated.** Judgment is the only IDP with a confirmed empirical origin (derived directly from field observation of two people acting under identical uncertainty conditions with divergent outcomes, predating the other four domains, which were extrapolated from Judgment before their own continents — job/career, self-discovery, dating, parenthood, existential exposure — were independently explored). A direct comparison between the canon's current invariants and the author's original four invariants and three constraints found:

- Distortions: fully preserved (Pseudoskills/Skill as Judgment, Signal as Judgment, Trait as Judgment, Motivation as Judgment all map cleanly to originals).
- Invariants: only one of four preserved ("Information Is Incomplete" ≈ "Judgment Requires Uncertainty"). The other three original invariants (**Constraints Precede Capability, Tradeoffs Are Real, Coordination Is the Limiting Factor**) have no traceable correspondence in the current canon and were replaced by different content (Judgment Collapses Optionality, Judgment Binds Identity to Consequence, Judgment Rests on Agency) that sounds more like discovered physics but was never derived from the author's own record.
- Constraints layer: not currently canonized as a distinct category. The three original constraints (**Judgment Is Not Certainty, Judgment Is Evaluated Over Time, Judgment Is Not Blame**) are absent from JUDGMENT.md as named structures. "Judgment Is Not Blame" is flagged as the most significant omission — it is the closest direct expression of the framework's stated founding purpose (technical mercy; structural rather than moral attribution; cf. Unified Registry Law 01) and currently exists only as diffuse guardrail language in the document's preamble, not as canonized structure.
- Open question: "Coordination Is the Limiting Factor" may belong structurally to Cohesion rather than Judgment; author has not yet determined whether this was a migration error or a genuine cross-domain invariant. _Disposition: Restore original invariants and constraints from author's source record, replacing current JUDGMENT.md §7. Add a canonized Constraints section. Retain all four distortions as-is._

**BOUNDARIES.md — Provisional (downgraded from initial "bedrock" verdict; see note below).** Initially scored as the strongest-passing domain document: Substitution passed cleanly (Differentiation/Regulation primitive pair, bedrock/preference distinction all broke correctly under substitution), Compression passed (fully self-contained, and its Lookup Table row was later confirmed accurate against source), distortions held. Two isolated repairs were flagged: invariant (c) "misalignment compounds" restates an earlier assertion rather than deriving it; invariant (d) duplicates a "Force" verbatim. **Author correction, recorded for the record:** this domain, unlike Judgment, was not independently empirically derived at the time of original construction — it was extrapolated from Judgment via the "continent model" before the author had fully explored the corresponding life-domain (self-discovery) that would generate it independently. Passing the five-test battery reflects clean _drafting_, not independent empirical grounding equivalent to Judgment's. Per the project's own personal-observation rule, this domain requires external corroboration before being presented at Judgment's confidence level. _Disposition: Retain content (it is not disqualified by testing), but recategorize as provisional/exploratory rather than bedrock, pending further fieldwork specific to this domain._

**COHESION.md — Provisional. Forces/Invariants fully duplicated (all four rows paraphrased); derivation weaker and more generic than Boundaries' or Stewardship's.** Distortions (Harmony as Health, Closeness as Commitment) held. Primitives shown to be compressed restatements of two of the four invariants — three nominally distinct taxonomic tiers collapsing into one set of content stated three times. _Disposition: Merge Forces into Invariants. Recategorize as provisional (per continent model — derived from Judgment prior to independent fieldwork on this life-domain, dating/partnership)._

**STEWARDSHIP.md — Provisional. Forces/Invariants duplicated (two rows verbatim, two paraphrased); contains the corpus's strongest derivation chain (§4, Accumulation Dynamics) alongside the duplication defect.** Distortions (Hoarding as Preservation, Optimization as Resilience) held. Lookup Table row found half-drifted from source at time of comparison. _Disposition: Merge Forces into Invariants. Preserve §4's derivation chain as a model for repairing weaker derivations elsewhere. Recategorize as provisional (continent model — parenthood, not independently explored by author). Lookup Table row requires full rewrite._

**PERIL.md — Provisional. Worst Forces/Invariants duplication in the corpus (all four rows verbatim truncations, not paraphrases); no revision-history markers present, ruling out "more revision = more damage" as sole explanation.** Distortions (Quiet as Safety, Probability as Certainty) held. The domain's single primitive (Exposure) found to be written in constraint-format (negation: "not fear, not risk, not probability") rather than primitive-format (mechanical operation), a category-consistency error independent of the duplication finding. Lookup Table row found to correspond to neither actual distortion — worst downstream drift in the corpus. _Disposition: Merge Forces into Invariants. Rewrite Exposure primitive in correct grammatical register. Full Lookup Table rewrite required, not patch. Recategorize as provisional (continent model — existential exposure, not independently explored by author)._

### Tier 3 — Environmental Physics (Geophysics, Topophysics, Chronophysics, Quantum, Morphophysics)

**UPDATE: 7/12/2026:** Nature of Primitives / Invariants / Distortions consolidated into one document. Reconstruction in progress

**Retired — clearest aether case in the corpus, not merely a failing one.** All five documents share an identical structural count (3 primitives, 4 invariants, 2 distortions, 8 phenomena) regardless of subject matter, in contrast to the IDP tier where primitive counts genuinely varied by domain (1 to 3). Cross-domain Substitution testing found verbatim-duplicated clauses between domains with only the domain name swapped (e.g., Geophysics' and Topophysics' Function Distortions share an identical clause; Quantum's "Lock-In" phenomenon and Morphophysics' "Lock-In" phenomenon share structure and mechanism under different names). Circularity confirmed via identical grammatical structure in every "Transition to Next Layer" section. Most consequentially, the Compression test found this tier is **never actually used** in live fieldwork coding — none of the seven dimensions in the Structuria Coding Taxonomy reference an environmental physics layer, and no entry in the 42-note Fieldwork Index cites one. _Disposition: Retire. If any individual concept here (e.g., something genuinely true about positional/contextual constraint) is worth keeping, it should be re-derived independently from fieldwork observation, not salvaged from this tier's existing text._

_Flagged as a distinct tool-calibration finding, independent of content: this tier is evidence that requesting "parallel structure across domains" before content is independently verified will reliably produce structurally uniform output regardless of whether uniform content actually exists. Recommendation for future authoring: request content first; allow structural symmetry to emerge only if independently present, per domain._

### Tier 4 — Architecture & Synthesis

**Architecture of Signal → Outcome — Split verdict: retain the primary model as strong canon; separate the secondary model out entirely.** The document contains two unreconciled models: (1) a five-layer Signal → Amplifier → Lens → Mechanism → Outcome/Attribution pipeline, and (2) a three-layer Judgment/Integration/Narrative model, merged without a demonstrated mapping between them. Tested independently:

- The five-layer model passed strongly: internal terms broke correctly under Substitution, contained a genuinely rare and valuable feature — an explicit, checkable Prohibitions list ("Signal → Action," "Amplifier → Decision," etc., each an actual falsifier) — and was later confirmed to derive directly from Judgment's own original, author-sourced distortions (Signal as Judgment / "signals are not mechanisms" maps directly onto this model's core Signal/Mechanism distinction). This explains why it tested as strong: it is downstream of the one empirically grounded domain, not a freestanding claim.
- The three-layer model was not independently tested; the document's own Section 4 flags unresolved internal confusion about how the two models relate ("wait, that's going back into the model?") without resolving it. _Disposition: Extract the five-layer Signal → Outcome model as its own standalone canonical document, replacing the Canonical Map / Structural Compass as the operative architecture. Evaluate the Judgment/Integration/Narrative model separately, on its own merits, as an independent candidate — do not re-merge without a demonstrated derivation._

**Canonical Map — Structural Compass — Superseded.** To be replaced by the corrected Signal → Outcome model per the above.

### Tier 5 — Derivative Compression Artifacts (Lookup Tables, Lexicon, Coding Reference Table)

**Not independently tested — confirmed compromised by inheritance, requires full rewrite regardless of per-row severity.** A row-by-row comparison of the Identity Physics Lookup Table against each IDP's actual source-document distortions found inconsistent fidelity, not uniform drift: Boundaries and Cohesion rows matched source exactly; Stewardship was half-drifted; Judgment and Peril rows bore no relation to their source documents at all, appearing instead to have been drawn from a different, uncorrected pass. This patchy pattern means partial spot-checking would not have reliably surfaced the problem — full rewrite from corrected source material is required rather than selective patching. _Disposition: Full rewrite, deferred until Tiers 0–4 corrections are finalized, since rebuilding now would compress source material that is about to change._

### Tier 6 — Operators

**Not yet formally re-tested; flagged at outset as already unstable (direct field evidence of instability under pressure), independently confirmed by a documented gap between the Operator-Facing Lookup Table (internal) and the Operator Canon's own declared authority.** One design principle has already been extracted and endorsed independent of the domain's full disposition: operator content should describe a _situation_, not diagnose a _person_. The Invocation/Imposition distinction (identity acting on environment vs. environment acting on identity) is flagged as the most structurally important surviving concept from this tier, precisely because it satisfies that principle — it kept a live discussion, during this audit, focused on what was happening rather than sliding into a diagnostic claim about the author. _Disposition: Full five-test audit deferred to a dedicated session, given the emotional and structural stakes involved. Provisional rule established for that future audit: any operator content that produces a claim about what is structurally wrong with a person, rather than a claim about the situation a person is in, fails on principle regardless of other test results._


---

## 6. Summary Disposition Table

| Document / Tier                                                    | Verdict                                                    | Disposition                                                                            |
| ------------------------------------------------------------------ | ---------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| Metaphysics                                                        | Aether (5/5 fail)                                          | Demote or retire                                                                       |
| Canonical Map                                                      | Aether pattern (Section VI); superseded                    | Replace with Signal→Outcome model                                                      |
| Boundary Conditions & Falsifiability                               | Not audited; posture retained                              | Keep — apply to all provisional domains                                                |
| Nature of Invariants                                               | Aether (universal claim); content-neutral                  | Demote — reframe as editorial convention                                               |
| Nature of Primitives                                               | Mixed                                                      | Demote — keep taxonomy, strip derivation claim                                         |
| Nature of Distortions                                              | Mixed                                                      | Demote — keep named distortions, strip Form/Function split                             |
| Judgment                                                           | Bedrock (distortions); invariants substituted, not derived | Restore original invariants + add constraints layer                                    |
| Boundaries                                                         | Content passes; empirically unconfirmed                    | Provisional — retain, downgrade confidence                                             |
| Cohesion                                                           | Content passes; empirically unconfirmed                    | Provisional — retain, downgrade confidence, merge Forces/Invariants                    |
| Stewardship                                                        | Content passes; empirically unconfirmed                    | Provisional — retain, downgrade confidence, merge Forces/Invariants                    |
| Peril                                                              | Content passes; empirically unconfirmed                    | Provisional — retain, downgrade confidence, merge Forces/Invariants, rewrite primitive |
| Geophysics / Topophysics / Chronophysics / Quantum / Morphophysics | Aether (clearest case in corpus)                           | Retire                                                                                 |
| Architecture of Signal → Outcome (5-layer model)                   | Bedrock                                                    | Extract as standalone canonical document                                               |
| Architecture of Signal → Outcome (3-layer model)                   | Untested                                                   | Evaluate independently, do not re-merge                                                |
| Lookup Tables / Lexicon / Coding Reference Table                   | Compromised by inheritance                                 | Full rewrite, deferred                                                                 |
| Operator Canon                                                     | Not yet re-tested                                          | Dedicated future audit; Invocation/Imposition provisionally retained                   |

---

## 7. Open Threads for Future Sessions

1. Restore Judgment's original invariants and constraints from author source record; add canonized Constraints section.
2. Replace Canonical Map with corrected Signal → Outcome (5-layer) model as operative architecture.
3. Draft revision note for public/quiet-node record (separate document; distinct rhetorical function from this working record).
4. Resolve "Coordination Is the Limiting Factor" — Judgment or Cohesion.
5. Merge Forces/Invariants sections across Cohesion, Stewardship, Peril.
6. Rewrite Peril's Exposure primitive in correct grammatical register.
7. Full Lookup Table / Lexicon / Coding Reference Table rewrite — deferred until above items are resolved.
8. Dedicated Operator Bible audit — apply situation-vs-person-diagnosis principle as a standing rule.
9. Author to determine, per document, whether Boundaries/Cohesion/Stewardship/Peril require dedicated independent fieldwork before any confidence upgrade, per the project's own personal-observation/external-corroboration rule.