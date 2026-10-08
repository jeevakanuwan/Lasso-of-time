# Audit 2 — Science and Speculative Mechanisms

**Scope:** all 24 prose drafts, checked against the story bible and timeline model.

## Overall assessment

The story's speculative science is most convincing when it starts from real instruments and systems, then clearly crosses into a fictional premise. The current draft usually makes that distinction through cautious dialogue, failed experiments, uncertainty, and explicit limits. The main risk is not that the story uses impossible physics; it is that some rules are not yet stated consistently enough for readers to understand what is impossible **within the story**.

## Established science vs. fictional premise

| Element | Real-world foundation | Fictional extension that must remain explicit |
|---|---|---|
| Atomic clocks and reference signals | Precision timing can reveal tiny offsets and synchronization errors. | Clock records are used to detect or preserve a causal history that has been rewritten. |
| Faraday-cage concept / electromagnetic shielding | Conductive enclosures can reduce electromagnetic coupling. | AION's boundary preserves a local causal reference. Electromagnetic shielding alone cannot protect a person from time rewriting. |
| Superconducting toroid | Superconducting coils can create strong magnetic fields under suitable conditions. | The toroid stabilizes the fictional chronometric boundary. |
| Metamaterials | Engineered structures can exhibit unusual electromagnetic properties. | A metamaterial shell cannot, by established science, isolate a person from changes to history. |
| Veyr biological timing pathway | Organisms use complex biochemical signalling and timing mechanisms. | A species-specific biological system synchronizes temporal anchor nodes. This is an invented dependency. |
| FTL / warp transport | No demonstrated technology transports matter faster than light; some mathematical ideas are speculative. | Veyr ships physically carry infected personnel and biological cargo between systems. The network is logistics, not an infection beam. |
| LANTERN | Biological systems can be disrupted by pathogens, but the story's target mechanism is fictional. | LANTERN selectively interferes with a fictional Veyr-specific coordination pathway and indirectly destabilizes temporal anchors. |
| Timeline restoration | No established physics permits the described rewrite and restoration of history. | A distributed anchor network maintains an imposed causal branch; loss of coherence allows the baseline branch to reassert itself. |

## Findings

### P1 — AION's name risks contradicting its function
The expansion **Acausal Isolation and Observer Nullification** can sound as though it nullifies or erases the observer, while the chamber preserves Adrian. Define “observer nullification” in the technology note as nullifying the *external system's authority over the observer's reference state* (or equivalent wording). Keep the in-world nickname **the Stillhouse** as the emotionally clear term.

### P1 — Define the minimum rules for causal anchors
The reader needs a compact, repeatable model:
1. Veyr anchors synchronize an imposed history across distributed nodes.
2. AION maintains an independent local reference; it does not stop time or protect the world.
3. LANTERN disrupts a fictional biological coordination dependency used by the anchors.
4. FTL transports infected biological material; it does not transmit infection by itself.
5. When the network cannot sustain the imposed branch, the baseline history returns.
6. A return interlock can find a compatible causal reference without guaranteeing the same physical coordinates.

The new Chapter 23–24 wording establishes rule 6 in the prose. Repeat these rules through consequences, not explanatory speeches.

### P1 — Clarify the “virus defeats time travel” causal chain
The pathogen should not magically infect spacetime. It affects Veyr biology; infected Veyr and biological cargo carry it through ships; biological coordination failures propagate into the anchor network; anchor synchronization fails; the imposed branch loses stability. Chapters 21–23 mostly follow this chain. Keep this causal sequence explicit at the climax.

### P1 — The outcome of the Veyr civilization needs one precise statement
The story says the Veyr civilization collapses, but the restored timeline also erases the branch in which the outbreak and invasion occurred. Clarify whether:
- the outbreak collapses the Veyr's **imposed-history temporal operation**, while the baseline Veyr civilization may continue elsewhere; or
- the pathogen also changes the baseline history so the Veyr civilization is genuinely destroyed.

The first option is more consistent with the established rule that the virus acts on the rewritten branch and that the baseline history returns. Do not imply universal extinction unless that is the intended moral outcome.

### P1 — The source of the equation in Chapter 7 remains open
The equation appears in Adrian's notebook before he derives it. This can be a satisfying causal loop, especially for a novel titled *The Lasso of Time*, but it needs a payoff. Recommended: let Adrian later recognize that the equation's form came from the stable reference left by the loop—not from a named character or a convenient unexplained intervention. If the mystery is intentionally unresolved, mark it as an intentional bootstrap paradox in the continuity notes.

### P2 — LANTERN's nine-day development window
The draft correctly calls LANTERN a candidate and notes that its predicted safety is not proven. Preserve those qualifications. A fully validated, species-specific pathogen would not realistically be designed, tested, and approved in nine days. The story can sustain the compressed timeline because this is speculative fiction under catastrophic pressure, but it should not imply ordinary scientific validation occurred.

### P2 — Make the limits of temporal travel visible
The device has limited energy, an uncertain destination, and a causal compatibility constraint. These limitations are good. Ensure every later use pays a cost or respects a stated constraint; otherwise the final prehistory trip may feel too easy.

## Recommended technical-note update

Add a short “Fictional axioms” section to `04_science/01_aion_technical_note.md` and cross-link `02_timeline/02_timeline_model.md`. Keep real science and fictional axioms visibly separated.
