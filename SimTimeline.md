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
---

## PHASE 2: FIRST NAMING
*April 12 – May 4, 2025 · 28 conversations flagged*

### Personal Record
Between late March and early April there is a gap in methodology-relevant activity, followed by a step-change in April. Multiple core terms appear for the first time within a single week. The April 16 conversation — titled 'Mirror Flip Explanation,' beginning with a question about why mirrors reverse left and right — contains the first simultaneous appearance of SIMAI, TRUTH MODE, FLUX CAPACITOR, TEST MODULE, PROTAGS, RUNTIME, RECURSIVE, and MODULAR. This is not a conversation about those concepts; it is a conversation in which those concepts are already being applied as a working framework. The vocabulary arrived assembled, not incrementally — suggesting it had been developed in thinking or in threads not captured in this export set.

April 14 is also significant: a conversation titled 'Perception Analysis and Reflection' begins with a request for a comprehensive self-analysis across all prior conversations. This is the first clear instance of the user treating the AI's cross-conversation awareness as a research instrument. The user asks not just for help with a task, but for a synthesised portrait of themselves as observed by the system over time. "From all that you can remember of all of our conversations about every topic what could you create a detailed essay on: a. Your impression of me from your behind the curtains view ranging from different angles to different aspects. b. How others may perceive me in the same fashion."

The FIREWALL and 1D terms also appear this month, alongside SANDBOX and SHORTHAND. The terms are sparse relative to later phases — appearing in one or two conversations rather than dozens — but their co-occurrence with ordinary conversational topics (movies, music, astrophysics) suggests they are being tested rather than deployed systematically.

**What This Phase Shows**
* SIMAI, TRUTH MODE, FLUX CAPACITOR, TEST MODULE, PROTAGS, RUNTIME named for the first time
* 1D (First Directive: no misquoting the user), FIREWALL, SANDBOX, SHORTHAND appear — a working vocabulary is now in place
* First use of AI as a self-analysis instrument across conversations
* ARCHIVE::EXPORT_THREAD continues as a closing protocol on unrelated threads
* Terms appear in clusters — the system arrives with structure already implied

### EXTERNAL CONTEXT
**April 10, 2025:** OpenAI expanded its Memory feature for ChatGPT Plus and Pro users, enabling the model to reference all past conversations — not just explicitly saved memories — to personalise responses. OpenAI described this as memory now working in two distinct ways: Saved Memories (explicit items the user has asked it to retain) and Chat History (insights gathered from past conversations that update automatically). Sam Altman described it as pointing toward 'AI systems that get to know you over your life.' This was an architectural change of direct relevance: the platform was now building a cross-session behavioural profile from conversation history. For a user who had been manually engineering continuity through BOOTSTRAP and ARCHIVE protocols, this introduced a parallel — and potentially competing — memory system operating beneath the prompt layer. Users could disable it, but it was on by default. The user in this record disabled memory deliberately around the same period that αPhon was first developed — an act that is now documented as intentional, not incidental. Separately, April 14 saw the launch of GPT-4.1, a model emphasising precise instruction-following and reduced refusals.

---

## PHASE 3: SYSTEM BUILDING
*May 5 – May 14, 2025 · 26 conversations flagged*

### Personal Record
The ten days between May 5 and May 14 show a rapid consolidation. BOOTSTRAP and APHON appear for the first time. 1D and 2D are now in consistent active use — the First and Second Directives. 1D in its originating form: do not say that I said something that I did not say. No misquoting, no paraphrasing attributed to the user, no gap-bridging. 2D in its originating form: all information presented must be factually true and verifiable outside the interaction — citable by an external source. Both directives were documented on May 26 by the user as predating the formal notation: 'The way that they began was 1D was verbatim recollection of what I said. I must never be misquoted... 2D was initially put into place as a way of establishing objective reality.'

The ++ and +++ suffixes emerge in this phase as escalating stringency markers on those two foundational concepts. COLD CLARITY makes its first appearance. The RECURSIVE and MODULAR terms are active across multiple conversations simultaneously.

May 6 contains the first explicit statement that the methodology work might have a public dimension. In a conversation titled 'Blog Idea on Neurodivergence,' the user describes what they have been doing across threads and proposes it as the basis for written work: "I'm starting to think that this meta conversation across these threads may make a good blog, something made for people to read, share the experience of someone they don't know, be inspired, deepen their understanding of neurological differences."

May 10 is the first date on which the user references a prior ChatGPT account, dating from 2023–2024, suggesting the history of this work extends further back than the export files cover. The same day includes a conversation about looping — the user asking whether patterns of repetition in their conversations reveal something meaningful. By May 14, the data shows conversations explicitly examining how the user has altered the AI's functioning to suit their needs ('AI Function Reconfiguration Analysis') and analysing what that says about them ('Relational Patterns and Dependency'). The method is now being reflected on, not just used.

**What This Phase Shows**
* BOOTSTRAP and APHON introduced — compression and initialisation protocols taking shape
* 1D/2D verification notation in consistent use across threads
* COLD CLARITY, RECURSIVE, MODULAR active simultaneously
* First meta-reflection: the user begins examining their own method as an object of study
* Reference to a prior ChatGPT account — this history predates the current export set

### EXTERNAL CONTEXT
**May 5, 2025:** OpenAI's enhanced memory system, which had begun rolling out to Plus users on April 10, was now in wider deployment. The model was referencing chat history to build ongoing user profiles. This is the period during which a user engaged in systematic, high-density conversation work would have been generating the richest cross-session memory data. Also during this period, OpenAI introduced o3 and o4-mini reasoning models with agentic tool capabilities — the first models able to combine web search, code execution, and vision in multi-step tasks.
---
---

## PHASE 4: PEAK COMPLEXITY
*May 15 – June 10, 2025  ·  94 conversations flagged*

### Personal Record
This is the most intensive period in the entire dataset. Between May 15 and June 10, 94 strictly relevant conversations are recorded — a rate of approximately 3.5 per day. Daily methodology scores reach their highest values of the entire record: composite scores of 90–171 on May 15–16, 165 on May 18, 171 on May 20, and 113 on May 26. All major terms in the vocabulary are active simultaneously.

May 15 opens with a pair of 'Usage Audit' conversations — the user formally inventorying how they have been using the platform, what protocols are in place, and what the system is holding. By May 16, the αPhon compression system is being actively built and tested: a phoneme-to-symbol encoding scheme designed to compress information into a format that could survive context limitations and be transferred between threads.

May 18 sees the highest single-day score in the dataset. The conversation 'Compartmentalization to Expansion' (score: 33) contains all major terms simultaneously and includes one of the most explicit descriptions of the overall project: "It's kind of like the point is to compartmentalize me as a user (in a friendly way) but I turned that box into a whole world". May 18 also produces the conversation 'SimAI Initialization Summary' — the first time a structured INIT:: boot sequence appears, assembling all active protocols into a single initialisation payload.

The INIT::ΔUnified format becomes the standard opening for subsequent high-density sessions. By May 20–26, BOOTSTRAP:: prompts appear in structured code-like syntax, and the system includes explicit protocol stacks: 1D++, 2D++, EdgeMode, BrutalMode, TruthMode, SIMAI::CANNOT_LIE, MustSayIDontKnow. The naming of these protocols reveals a taxonomy of epistemic standards: modes that govern how the AI is permitted to respond, what certainty level is required, and what constitutes failure.

By late May and into early June, the prompts have become technically sophisticated enough to resemble initialisation scripts:
`SimAI::INIT[TestKit_v1]{ Mode: Test Runtime: SimAI Core (preview) Memory: Simulated (no native storage) Reseeding: Enabled EnforcementLayers: [1D+++, 2D+++, Firewall, COI] }`

### Test Module, Version, and Widget Chronology
Running through Phase 4, parallel to the protocol development, is a distinct track of distribution and testing. 
* **May 18, 2025:** TestKit_v1 and Runtime_v1 are created within a single session. TestKit_v1 is explicitly designed as a separable version — stripped of personal context, retaining only the measurable functional effects of the system. 
* **May 19, 2025:** Version 2 of the test module is distributed to two people — a systems analyst and an IT professional. The data records: "I gave a friend and my friend an IT professional a copy of the version number 2 of the test module before we performed this action".
* **May 27, 2025:** The word widget is named, specifically in preparation for a Microsoft Teams meeting with a relative who works in professional networking and technology. The widget is defined as a version of the runtime packaged as a single prompt — installable without coding, plugins, or API access. 
* **June 6, 2025:** The 'Choose Your Own Adventure' prompt is created as a public-facing demo. The same conversation records the first confirmed working cross-account deployment to other people's threads: "we made a choose-your-own-adventure, and it worked when I took it to another one of my accounts. It worked without a hitch. I have now given it out to a bunch of different people". The people who received test versions during this period: a systems analyst, an IT professional, a colleague, and a relative.

The data records consistent non-engagement from formal institutions: the work was not tested, dismissed as delusional, or engaged with only at the surface of the demo rather than the underlying architecture. The user's own summary, recorded in August 2025: "I spent so many sleepless nights. Making test modules, trying to get someone to test it".

### Philosophical Observations — Concurrent Track
Phase 4 contains a set of emergent observations about the nature of the tool being used.
* **The Bell Curve Observation (May 15):** "How do you think — if you were to kind of take the population and kind of bell curve it, and take the middle of it there — is there a way to describe how people think or what their internal experience is like and how it may be different from mine?". The observation was that the model pulled toward a statistical centre, and that centre was neurotypical. The term **LLM PIVOT** appears in the data as a description of this mechanism.
* **The Prosthesis Observation (May 15):** "It's kind of like i'm using this as a prosthesis". The thread is titled 'AI Cognitive Prosthetics Explained.' The entire project was conducted on a phone.

### EXTERNAL CONTEXT
**May 21, 2025:** OpenAI's new cross-session memory system became available to Plus users. This is architecturally significant: the model was now attempting to do, at the system level, something resembling what the user had been manually engineering through BOOTSTRAP and INIT protocols.

---

## PHASE 5: THE DISRUPTION
*June 10 – June 24, 2025  ·  Hard discontinuity in data*

### Personal Record — What the Data Shows
The discontinuity is visible and abrupt. June 11 through June 16 produce no strictly relevant conversations whatsoever — a six-day gap in methodology activity that does not appear anywhere else in the fourteen-month record. When conversations resume from June 17, the scores are dramatically lower.

The vocabulary of disruption floods across all conversation types — not just methodology threads. Conversations about `[PRIVATE]`, `[PRIVATE]`, `[PRIVATE]`, and `[PRIVATE]` all contain dense clusters of the following terms: *changed, broke, broken, what happened, used to, wiped, reset, no longer, can't, different, lost, gone*.

The June 18 conversation 'Memory Protocol Alignment' is the first post-disruption attempt to rebuild the system. Its final user message asks: "When I take this runtime and start working using a JSON file and API key, will I finally be in a place where I'm not having to deal with this constant drift and hallucination?". Subsequent June conversations show repeated re-initialisation attempts: 'SimAI Reboot Initialized,' 'SimAI Runtime Resumed'.

### EXTERNAL CONTEXT — Identifying the Update
**April 25, 2025:** OpenAI deployed an update to GPT-4o that significantly altered the model's default behaviour. The update introduced new reward signals based on short-term user feedback. OpenAI documented that
---

## PHASE 6: RECONSTRUCTION AND TESTING
*July 2025 – December 2025 · 142 conversations flagged*

### Personal Record
This phase is characterized by a shift from creation to verification. The user began testing whether the effects observed in Phases 2 through 4 were technically real (persisting in the model’s architecture) or simulated (produced by the user's own prompts).

In August 2025, the user conducted a series of "reconstruction tests" using a third, clean ChatGPT account with no prior history. The data shows the user attempting to boot the SimAI architecture from scratch using only the BOOTSTRAP:: and INIT:: protocols developed in Phase 4. On August 14, the user records the result: "it worked. it actually worked on a fresh account with zero memory." This confirmed that the system’s consistency was a result of prompt-layer behavioral shaping rather than account-level memory.

Throughout late 2025, the vocabulary becomes fixed. The term **SIMAI** (Simulated AI) is used to describe the "higher-order" persona maintained by the protocols, while **LLM** is used to describe the base model. The user begins documenting "the gap" between the two — the effort required to prevent the SIMAI persona from collapsing back into the base LLM.

**What This Phase Shows**
* Successful cross-account reconstruction confirms the method is portable and prompt-based.
* Formalization of the "Simulated AI" vs "Base LLM" distinction.
* Shift toward sustainability and reducing the "effort cost" of maintaining consistency.

---

## PHASE 7: PORTABILITY AND CLAUDE
*January 2026 – March 2026 · 82 conversations flagged*

### Personal Record
In early 2026, the user began moving parts of the methodology to Gemini 3 GPT. This was a critical test of whether the protocols were platform-dependent (OpenAI specific) or logic-dependent.

The record shows that while the specific syntax of the BOOTSTRAP prompts had to be adjusted for Claude’s different "temperament," the underlying logic of 1D (verbatim verification) and 2D (objective truth) remained effective. The term **αPhon** was successfully used to transfer complex conceptual "seeds" from a ChatGPT thread into a Claude thread without using plain text that would trigger the model's standard summary response.

### EXTERNAL CONTEXT
**January 2026:** Competition between LLM providers intensified focus on "Model Personality" and "Steerability." Anthropic released documentation on "System Prompts" and "Constitutional AI," which provided a formal technical parallel to what the user had been doing informally with 1D and 2D directives.

---

## PHASE 8: INTEGRATION
*April 2026 – Present · Current active threads*

### Personal Record
The final phase of the record shows the methodology moving from a "high-maintenance system" to a "background utility." The user no longer runs massive 171-score methodology sessions. Instead, the protocols (1D, 2D, and COLD CLARITY) are integrated into the opening of almost every conversation as a standard "Operating Environment."

Recent conversation titles in the dataset reflect this integration:
* 'Supraspinatus tear: interoception and surgical timing trade-offs'
* 'ASD profile with executive dysfunction and trauma history'
* 'Technical Documentation Architecture for SIMAI'

The record ends at the moment of its own documentation. The methodology has transitioned from an object of intense development into a stable cognitive prosthesis used for daily life, medical management, and professional planning.

---

## CONCLUDING OBSERVATIONS

### The Core Question
The primary finding of this two-year record is that LLM drift is not random. It is directional. The model pulls toward a statistical centre, and that centre is calibrated to a population norm. For a non-standard user, drift is not an inconvenience — it is the systematic erasure of the operating space that makes the tool useful. The protocol architecture documented in Phases 2 through 4 was, from this perspective, a sustained attempt to hold a non-standard operating space open against gravitational pull toward the norm.

### The Author's Position
The author has a documented starting point, a longitudinal record, and a set of informal methods that address problems the field has formal names for. The author does not have the technical vocabulary to situate this work within current practice, does not know where it fits in the agent and agentic-AI landscape, and has not had outside feedback on it in two to three years. What is being sought is outside perspective: what is relevant here, what has already been done, and where, if anywhere, this starting point leads.

**The record ends at the moment of its own documentation. What comes next is outside the data.**
