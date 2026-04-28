# DEVELOPING A PERSONAL AI CONSISTENCY METHOD
## A Chronological Record
*Based on 1,028 unique ChatGPT and Claude conversations · March 2023 – April 2026*

**SOURCE NOTE:** All data in the PERSONAL RECORD sections is drawn from: 9 ChatGPT export JSON files from the primary account (`[REDACTED EMAIL]`); 2 ChatGPT export files from an older account (`[REDACTED EMAIL]`); 1 ChatGPT export from a third account used exclusively for reconstruction testing (`[REDACTED EMAIL]`); and 40 conversations from a Claude export (`[REDACTED EMAIL]`, March-April 2026). Total unique conversations after deduplication: 1,028. No external sources, memory systems, or connected accounts were consulted for that track. The EXTERNAL CONTEXT sections are clearly labelled and sourced from publicly available OpenAI documentation and news reporting.

---

## ABOUT THIS RECORD
This document is a personal record, not a research paper. It was not produced within an institution, does not follow a formal methodology, and has not been reviewed by anyone outside the conversation from which it emerged. It is being presented for the first time to people with relevant technical and community context. The record is presented as-is, with its limitations stated explicitly, because the data underneath it is real and the questions it raises may be worth examining.

### The Author
`[NAME REDACTED]`. Born `[YEAR]`. Diagnosed ASD Level 1 and ADHD in adulthood. IQ approximately `[REDACTED]` with significant executive function impairment — a gap between demonstrated intellectual capacity and functional throughput that has been consistently misread by standard assessment frameworks.

No technical background. No coding environment. No API access during the primary development period documented here. The entire project was conducted on a phone.

The neurodivergent profile is not incidental to the work. It is the reason the work exists and the reason it took the shape it did. A cognitive style that is recursive, pattern-dense, ontological, and resistant to standard social and communicative forms found, in the AI environment, a space where that style could operate without the compression and translation costs that characterise most other contexts.

The methodology developed here was an attempt to maintain that space against the model's tendency to return to a statistical norm. This work was conducted without outside feedback for approximately two to three years. What follows is the first external presentation of the record.

### What This Document Is
A chronological record of informal methodology development: the emergence, naming, elaboration, collapse, reconstruction, and integration of a set of personal techniques for maintaining consistency and epistemic stability in long AI conversations. The data source is 1,028 unique conversations extracted from ChatGPT and Claude exports, spanning March 2023 to April 2026. The record contains two parallel tracks throughout: a PERSONAL RECORD drawn exclusively from that conversation data, and an EXTERNAL CONTEXT track drawn from publicly available documentation of concurrent AI platform developments.

### What the Data Supports Claiming
* Pattern recognition across a large, self-generated, longitudinal dataset — consistent and largely accurate.
* Ability to build and iterate on structured systems under significant constraint.
* Sustained engagement with a technical problem over an extended period without institutional support or formal training.
* Capacity to identify, name, and document abstract behavioral phenomena in real time.
* Ability to distinguish between simulated and actual effects within the system being built — and to make that distinction explicit.
* The methodology produced real behavioral changes in model output. It also simulated effects that were not technically real — persistent memory, cross-thread state, autonomous process loops.
* The distinction between what was real and what was simulated was tested directly, documented in the record, and is addressed in the Phase 6 section of this document.

### What This Document Does Not Claim
* That the system as built is reproducible without significant context.
* That the syntax is portable as-is to other users without adaptation.
* That the observations about model behavior constitute validated findings beyond this single case.
* That the work represents a formal framework in the technical sense.
* That the author has the technical vocabulary to situate this work within current field practice — that situating is part of what outside perspective is being sought for.

### Why It Is Being Presented
The methodology documented here addresses problems the field has formal names for: context persistence, drift mitigation, behavioral conditioning, prompt engineering for consistency under extended use. It arrived at those problems from a completely different angle — user-side, constraint-driven, idiosyncratic in vocabulary and approach — and produced a two-year longitudinal record in the process. That record may be of interest to people working on agentic AI, neurodivergent user experience, or prompt-layer behavioral shaping. It is presented here to find out.

---

## PROLOGUE: BEFORE THE METHOD
*March 2023 – July 2024 · 90 conversations · older account*

### Personal Record
The dataset includes a second ChatGPT account predating the main export by nearly two years. It contains 90 unique conversations spanning March 2023 to July 2024, followed by a gap of 193 days before the main account's record begins in January 2025. These conversations contain none of the methodology vocabulary that develops later — not DRIFT, not SIMAI, not BOOTSTRAP, not any of the 27 terms in the personal lexicon. They are not early versions of the method. They are what existed before the method had been conceived.

The content of this earlier period is concentrated almost entirely on three subject areas: `[PRIVATE]`, `[PRIVATE]`, and emotional regulation. The most active month in the entire pre-2025 record is June 2023, with 23 conversations — more than any other single month before the methodology work begins. The longest single conversation in this period runs to 49 messages, working through stoicism, fairness, and the ethics of relationship.

The earliest conversation in the entire dataset, dated March 16, 2023, is titled '`[PRIVATE]`'. By March 25, 2023, a second conversation is already a letter: written in the voice of a male with `[PRIVATE]`, addressed to a `[PRIVATE]`. The subject matter that will recur throughout the methodology years — `[PRIVATE]`, `[PRIVATE]`, `[PRIVATE]`, autism, the difficulty of being understood — is present from the very first session.

Activity is dense through mid-2023, then tapers. After September 2023 there are only 13 conversations across the remaining ten months of the pre-2025 record, and none after July 15, 2024. The 193-day silence that follows — ending when the main account begins in January 2025 — is the largest gap in the entire dataset.

**What This Period Establishes**
* The user was engaging with AI as a thinking tool from at least March 2023 — nearly two years before the method develops.
* The subject matter is consistent throughout: `[PRIVATE]`, emotional regulation, self-understanding.
* No methodology terms appear — this is genuine prehistory, not early-stage method work.
* The 193-day gap (July 2024 – January 2025) is not accounted for in the data.
* When the main account opens in January 2025, the user arrives with nearly two years of prior context.

### EXTERNAL CONTEXT
**March 2023:** ChatGPT was running on GPT-3.5 Turbo as its default model, with GPT-4 available to Plus subscribers from March 14, 2023. These were stateless models with no persistent memory whatsoever — every conversation began from scratch with no cross-session recall, no user profiling, and no memory features of any kind. A user returning to a new conversation had to re-establish all context manually. This is the baseline condition against which the later methodology work should be understood: the problem the user eventually tried to solve was built into the architecture from the very first session.

---

## PHASE 1: PRE-VERBAL NOTICING
*January 25 – March 31, 2025 · 20 conversations flagged*

### Personal Record
The main account opens on January 25, 2025, after the 193-day gap. The earliest conversations cover personal and scientific topics. Methodology terms do not appear until February 14. During this six-week window the only term from the later vocabulary that appears is DRIFT — a word used in its ordinary English sense to describe a felt experience: the sense that an AI conversation was moving away from an intended direction without any mechanism to correct it. No named system exists yet. The problem is being noticed but not yet labelled.

Conversations span astrophysics, personal relationships, and practical questions. Several threads in this period end with an unusual closing command that suggests early experimentation with archival:

`ARCHIVE::EXPORT_THREAD[ Mode=Verbatim, Include=FullThread, Target=SchrodingerBox, Catalog=True, Confirm=ParseOnReturn ]`

This command appears appended to otherwise unrelated conversations — about black holes, text-to-speech, and galaxy formation — suggesting the user was already attempting to impose a consistent structure on how conversations ended, even before a vocabulary for that structure had developed. The term SchrodingerBox appears here for the first time, as a target location for archived threads — its meaning not yet formalised but clearly functioning as a named container.

**What This Phase Shows**
* DRIFT identified as a problem before any solution vocabulary exists.
* ARCHIVE::EXPORT_THREAD appears as an early structural protocol across unrelated topics.
* SCHRODINGER'S BOX named as an archival target, weeks before it becomes part of the formal system.
* No high-density methodology conversations — the work is pre-linguistic.

### EXTERNAL CONTEXT
**February–March 2025:** GPT-4o was OpenAI's default model for paid ChatGPT users. The model had a 128,000-token context window but no persistent cross-session memory unless the user had explicitly enabled the Memory feature (which was still rolling out). Each new conversation thread started from scratch. For users doing extended, multi-session work — particularly those relying on continuity across threads — this was a significant structural limitation. The model had no native mechanism to carry state between conversations.
