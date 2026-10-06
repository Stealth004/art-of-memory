# Memory Engrams & Optogenetics — Key Primary Papers

Annotated bibliography for the Art of Memory research collection. All citations
verified against PubMed / publisher records on 2026-10-05. Context: the 2026 Nobel
Prize in Physiology or Medicine (Deisseroth, Hegemann, Nagel — optogenetics) is
covered separately in
`~/workspace/research_notes/human-optimization/scans/2026-10-05-nobel-optogenetics-note.md`;
this file covers the primary science only.

**A note on access:** six of these eight papers are open-access (five via PubMed
Central, one via PNAS). Their PDFs could not be mirrored here programmatically —
PubMed Central's current viewer, MIT DSpace, and pnas.org all require a
JavaScript-capable browser or human-verification step that automated download
cannot legitimately pass — so each entry links the canonical free source for
one-click download in a browser instead. No paywall was bypassed. One paper
(Roy et al. 2017) was retrieved as a local PDF from a public web archive of the
publisher's open-access file; it sits in `pdfs/`.

---

## 1. Liu et al. 2012 — first optogenetic reactivation of a defined engram

**Citation:** Liu X, Ramirez S, Pang PT, Puryear CB, Govindarajan A, Deisseroth K,
Tonegawa S. "Optogenetic stimulation of a hippocampal engram activates fear
memory recall." *Nature*. 2012;484(7394):381–385.
**DOI:** [10.1038/nature11028](https://doi.org/10.1038/nature11028) ·
**PubMed:** 22441246 · **PMCID:** [PMC3331914](https://pmc.ncbi.nlm.nih.gov/articles/PMC3331914/)
(**open access** — free full text at the PMCID link)

**What was shown:** Using a c-fos–driven tagging system, the Tonegawa lab labeled
only the dentate gyrus neurons that were active while mice formed a fear memory,
and made just those cells light-sensitive (channelrhodopsin). Days later, shining
light to reactivate *only* the tagged neurons — while the mouse stood in a
completely different, safe chamber — made it freeze as though recalling the fear.
Artificially switching on the experimentally defined "engram" cell population was
sufficient to drive recall behavior. This is the paper that turned the century-old
engram concept into something you can point a laser at.

## 2. Ramirez et al. 2013 — implanting a false memory

**Citation:** Ramirez S, Liu X, Lin P-A, Suh J, Pignatelli M, Redondo RL, Ryan TJ,
Tonegawa S. "Creating a false memory in the hippocampus." *Science*.
2013;341(6144):387–391.
**DOI:** [10.1126/science.1239073](https://doi.org/10.1126/science.1239073) ·
**PubMed:** 23888038
(**journal paywalled**; author's final manuscript freely available at
[MIT DSpace](https://dspace.mit.edu/entities/publication/325069c3-5503-4559-abaa-eed464b3c969),
posted under the publisher's manuscript policy)

**What was shown:** Dentate gyrus neurons active while a mouse explored a safe
context were tagged as light-sensitive. The next day, experimenters reactivated
those same neurons with light *while* the mouse received foot shocks in a
different context. Afterwards the mouse froze in the original safe context — where
it had never been shocked. A false associative fear memory had been created by
stitching a real place representation to an unrelated aversive event. Doing the
same labeling in CA1 instead of the dentate gyrus did not work, pointing to the DG
as the site where the false association formed.

## 3. Redondo et al. 2014 — flipping a memory's emotional valence

**Citation:** Redondo RL, Kim J, Arons AL, Ramirez S, Liu X, Tonegawa S.
"Bidirectional switch of the valence associated with a hippocampal contextual
memory engram." *Nature*. 2014;513(7518):426–430.
**DOI:** [10.1038/nature13725](https://doi.org/10.1038/nature13725) ·
**PubMed:** 25162525 · **PMCID:** [PMC4169316](https://pmc.ncbi.nlm.nih.gov/articles/PMC4169316/)
(**open access** — free full text at the PMCID link)

**What was shown:** By reactivating a dentate gyrus contextual engram while the
animal experienced something rewarding or something aversive, the researchers
rewrote the emotional meaning attached to that memory — negative to positive and
back again — by rewiring the connections from hippocampus to the basolateral
amygdala. The valence of a memory turned out to be malleable and stored in the
hippocampus→amygdala wiring pattern, not hard-fixed inside amygdala cells. (The
corresponding amygdala cells, by contrast, kept their fixed positive/negative
identity.)

## 4. Ryan et al. 2015 — the engram survives amnesia (storage vs. retrieval)

**Citation:** Ryan TJ, Roy DS, Pignatelli M, Arons A, Tonegawa S. "Engram cells
retain memory under retrograde amnesia." *Science*. 2015;348(6238):1007–1013.
**DOI:** [10.1126/science.aaa5542](https://doi.org/10.1126/science.aaa5542) ·
**PubMed:** 26023136 · **PMCID:** [PMC5583719](https://pmc.ncbi.nlm.nih.gov/articles/PMC5583719/)
(**open access** — free full text at the PMCID link)

**What was shown:** Mice given a protein-synthesis inhibitor right after learning
developed retrograde amnesia: the usual cues no longer triggered recall. But
directly reactivating the dentate gyrus engram cells with light still produced the
learned freezing response — the memory trace was physically intact; only natural
*retrieval* was broken. Optogenetic stimulation could even restore the
cue-driven recall. This cleanly separated memory *storage* (engram cells persist)
from memory *retrieval* (access can fail while storage survives).

## 5. Rashid et al. 2016 — engrams compete; timing decides linking vs. separation

**Citation:** Rashid AJ, Yan C, Mercaldo V, Hsiang H-L, Park S, Cole CJ,
De Cristofaro A, Yu J, Ramakrishnan C, Lee SY, Deisseroth K, Frankland PW,
Josselyn SA. "Competition between engrams influences fear memory formation and
recall." *Science*. 2016;353(6297):383–387.
**DOI:** [10.1126/science.aaf0594](https://doi.org/10.1126/science.aaf0594) ·
**PubMed:** 27463673 · **PMCID:** [PMC6737336](https://pmc.ncbi.nlm.nih.gov/articles/PMC6737336/)
(**open access** — free full text at the PMCID link)

**What was shown:** Building on the allocation work below, this cross-lab study
showed engrams compete through neuronal excitability: two events experienced
close together in time get assigned to *overlapping* neuron populations (linking
the memories), while events spaced far apart recruit *separate* populations
(keeping them distinct). Crucially, both directions were causally manipulable —
raising or lowering excitability with optogenetics could force linking or force
separation. A candidate mechanism for how the brain decides which experiences get
filed together and which stay apart.

## 6. Roy et al. 2017 — "silent engrams" as the basis of retrograde amnesia

**Citation:** Roy DS, Muralidhar S, Smith LM, Tonegawa S. "Silent memory engrams
as the basis for retrograde amnesia." *Proc Natl Acad Sci USA*.
2017;114(46):E9972–E9979.
**DOI:** [10.1073/pnas.1714248114](https://doi.org/10.1073/pnas.1714248114) ·
**PMCID:** [PMC5699085](https://pmc.ncbi.nlm.nih.gov/articles/PMC5699085/)
(**open access** — local copy in `pdfs/roy-2017-pnas-silent-memory-engrams.pdf`;
also free at the PMCID link)

**What was shown:** Formalized the "silent engram": a memory trace that still
exists physically but cannot be retrieved by natural cues — the proposed
explanation for retrograde amnesia after disrupted consolidation. Driving synaptic
strengthening in the engram cells (via PAK1-induced spine growth) converted
silent engrams back into active ones and restored natural recall. Amnesia, in this
model, is not erasure — it is an engram gone quiet that can, in principle, be
re-awakened.

## 7. Han et al. 2007 — CREB and competitive allocation to the engram

**Citation:** Han J-H, Kushner SA, Yiu AP, Cole CJ, Matynia A, Brown RA, Neve RL,
Guzowski JF, Silva AJ, Josselyn SA. "Neuronal competition and selection during
memory formation." *Science*. 2007;316(5823):457–460.
**DOI:** [10.1126/science.1139438](https://doi.org/10.1126/science.1139438)
(**citation only** — journal paywalled; no open-access copy located; abstract
verified at the DOI link)

**What was shown:** The Josselyn lab's allocation classic. In the lateral
amygdala, neurons with relatively higher CREB activity at the moment of learning
outcompeted neighboring neurons for membership in the fear memory trace.
Engram membership is not random and not "every active cell" — it is competitive,
and the winners are biased by their excitability state when the event occurs.
This is the mechanistic root of the competition results in Rashid et al. (2016).

## 8. Josselyn & Tonegawa 2020 — the anchor review

**Citation:** Josselyn SA, Tonegawa S. "Memory engrams: Recalling the past and
imagining the future." *Science*. 2020;367(6473):eaaw4325.
**DOI:** [10.1126/science.aaw4325](https://doi.org/10.1126/science.aaw4325) ·
**PubMed:** 31896692 · **PMCID:** [PMC7577560](https://pmc.ncbi.nlm.nih.gov/articles/PMC7577560/)
(**open access** — free full text at the PMCID link)

**What was shown (review):** Traces the engram idea from Semon's 1904 formulation
through a century of skepticism to the optogenetic evidence base above, and makes
the case that the engram — the enduring physical ensemble of neurons holding a
given memory — is the basic unit of memory. Covers how excitability and synaptic
plasticity govern which cells are recruited, how engrams are stored and
retrieved, and why the same machinery that recalls the past is implicated in
imagining the future. The single best entry point to the field; read this first.
(Note: some listings miscategorize this as *Nature Reviews Neuroscience* — it is
a *Science* review.)

---

## Connection to this research

The classical art of memory (method of loci, vivid imagery, structured
retrieval) is a *behavioral technology* for encoding and recall discovered
thousands of years before anyone knew what a neuron was. Engram science is its
modern mechanistic counterpart: it asks what the loci method is actually doing
to the brain — which cells get recruited (allocation, papers 5 & 7), how a trace
persists when it can't be recalled (papers 4 & 6), and what makes reactivation of
a trace sufficient for recall (paper 1). The through-line for this collection:
vivid, distinctive, well-organized encoding plausibly works *because* it biases
the competitive allocation process and builds richer, more retrievable engrams —
a hypothesis, not a proven fact, and worth stating as one.

Two guardrails, kept deliberately:

1. **Optogenetics is an animal-model tool, not a human enhancement method.**
   Every causal result above comes from mice with virally expressed
   light-sensitive proteins and implanted fiber optics. Nothing here transfers
   to human memory improvement, and this folder should never be cited to imply
   otherwise.
2. **No super-soldier narrative.** The standing finding of the human-optimization
   scans holds: there is no verified operational program for memory enhancement
   in humans. These papers describe basic neuroscience. Keep them filed as
   science, not as capability claims.
