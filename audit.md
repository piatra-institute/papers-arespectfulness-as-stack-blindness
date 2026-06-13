# Audit

Dated log of editorial passes and verification runs. Newest first. See the workspace docs (run `papers docs`): writing-pipeline.md §7 and refresh-pipeline.md.

## 2026-06-13 — voice reform (genius-level rewrite)

Scope: corpus-wide voice reform applied first to this paper as a reference exemplar. No change to claims, citations, or the claim-strength discipline; the rework is structural and prose-level.

Changes:

- Structure de-skeletoned: 10 numbered sections to 9. The bolt-on "Objections and Replies" section was dissolved into the argument (the ingratitude and neologism replies into §2, the Polanyi-backgrounding reply into §3, the romantic-primitivism reply into the close, the overclaim reply into the grading section). "What Can and Cannot Be Said" retitled "What the Evidence Will Bear" and reframed as the paper applying its own instrument to itself rather than an appendix; the generic conclusion retitled "Accumulated Impossibility."
- Prose de-ticced against the new voice.md "second wave": the tricolon reflex thinned, per-section aphoristic closers varied, negate-pivot / inline-contrastive constructions removed, and the pet-vocabulary density cut sharply (lexical advisory before/after: recede/recession 27 to 2, discipline 11 to 1, exactly 5 to 2, "the very" 5 to 0, tricolon proxy 75 to 54). The abstract and opening rewritten for friction and a stronger through-line.
- Both tables kept verbatim (they do real work). Every one of the 69 citations preserved.

Verification:

- voice: 0 errors, 0 review-candidates (lexical-density and structure advisories reviewed; the residual carries/carry 7 are ordinary usage, not the pet metaphor).
- refs: 69 cited / 69 bib / 0 missing / 0 unused (unchanged).
- build: clean, 18 pages, both tables within margins, 0 missing-character warnings.
- check => PASS.

## 2026-06-13 — initial full build

Scope: first complete draft from the single seed chat. Conducted the deep research, wrote the paper and all provenance docs, and brought the paper to a clean build. Conceptual paper: no simulation, no figures.

Changes:

- paper/PAPER.md: 10 sections. The felt impossibility of foundational layers (§1); the respect / disrespect / arespect triad and a concept-distinction table earning the neologism against disenchantment, reification, alienation, inattentional blindness, change blindness, misplaced concreteness, ready-to-hand withdrawal, infrastructural invisibility, and tacit knowing (§2); the mechanism of recession across Heidegger, Star, Latour, Polanyi, Simondon, and Stiegler, with the key concession that recession is functional (§3); the biological deep stack, breath as inherited geology (§4); mitochondria, chemiosmosis, and the enabling-condition argument for cognition with the consciousness guardrail (§5); fire, cooking, writing, the pharmakon, and cumulative culture (§6); compilers and engineered information hiding as the designed black box (§7); a consolidated claim-strength table grading the paper's own biological and cognitive claims (§8); five objections and replies (§9); the synthesis, the maintainers, and respect as re-spect (§10). 69-entry bibliography.
- metadata.yaml: title and header set, has_simulation false, claims_target none, date "June 2026", abstract filled, status built.
- brief.md (Question / Claim / Kind / cornerstone literature by domain); research.md (findings tiered T1-T4 by section, each biological/cognitive finding carrying its claim-strength flag and safe phrasing); sources.md (69 frozen entries mirroring `## References`, one provenance line each, with the Plato/Heidegger/Margulis citation conventions noted); README.md.

Claim-strength discipline (the §8 table, the paper's rigor centerpiece):

- ESTABLISHED: oxygen as the product of cyanobacterial photosynthesis risen ~2.4-2.3 Ga (cause, not precise onset); the molecular mechanism of oxygen toxicity; LUCA's anaeroby; the single alphaproteobacterial origin of mitochondria; chemiosmosis and cristae structure; cognition's dependence on mitochondrial ATP and Ca2+ as an enabling condition; writing's origin in accounting.
- LIVE-CONTROVERSY (paired with rebuttal, never asserted alone): the precise GOE onset; mitochondria-early vs -late; the Lane & Martin energy-per-gene thesis (vs Lynch & Marinov, Booth & Doolittle); the habitual-fire dating (Roebroeks & Villa vs Wrangham); the Great-Divide literacy thesis (vs Street).
- REFUSED overclaims: no "oxygen catastrophe / mass extinction of anaerobes"; no "LUCA lived at vents" (anaeroby only); no "mitochondria made complexity possible" as fact; emphatically no "cristae produce consciousness" (Chen & Zhang's predisposition framing; the variational-vs-metabolic free-energy category error marked and refused).

Verification:

- voice: 0 errors, 0 review-candidates (six negate-pivot / inline-contrastive warns reworded away during drafting).
- refs: 69 cited / 69 bib / 0 missing / 0 unused. Classics cited by translation year (Plato 1995, Heidegger 1962, Weber 1946, Lukács 1971, Marx 1959, Simondon 2017, Stiegler 1998) so the 1600-2099 year pattern recognizes them; Margulis (1967) listed under "Margulis" though published as Sagan.
- claims: claims_target none (conceptual) — manual only, no automated reconciliation. Every date, timescale, and energy budget in prose traces to a sources.md entry.
- build: clean, 18 pages, both tables rendering within margins, 0 missing-character warnings. ~10,000 words.
- check => PASS.

Notes / deferred:

- Dropped from the seed: the long enumerations of a dozen "stacks" (compressed to the load-bearing cases so each could be evidenced); the popular biological overclaims (re-grounded and weakened); any fabricated "stack depth" metric (the paper is conceptual; its numbers are sourced).
- Heidegger's "Question Concerning Technology" (enframing) was researched but not used; the paper draws only on Being and Time, so the QCT entry was removed to keep the bibliography fully load-bearing (0 unused).
- Status is `built`, not `published`: deploying to the web (sync + page.tsx entry) is the maintainer's pipeline.
