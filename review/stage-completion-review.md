# Stage completion: draft review record

Status: proposed changes; auxiliary skeptical review ACCEPT WITH CAVEATS; Claude review pending. This file is a maintainer record, not an additional step for the candidate or their AI.

## Scope and owner request

This draft amends `START-HERE.md` and the six phase files in the shareable GAJkit. It adds evidence-based completion checks, distinguishes provisional progress from completion, and reconciles the conversation with the working files before a phase closes. It does not update an installed candidate workspace or the separate GAJ core.

Owner requests received directly in this ChatGPT conversation on 2026-11-21. Record compiled at 17:54:01 UTC from the current GAJkit stage-completion discussion; individual chat-message timestamps are not exposed. The exact messages are preserved below:

> Please draft an update for this. Claude is usage frozen, so please use a skeptical reviewer agent to review and call Claude out to review after the fact

After the additional read-only source review:

> Please update your draft if applicable

The owner then specified the minimum discovery requirement:

> I think a minimum requirement should be that the candidate talks about their complete work history in detail. Reviewing their resume should be informative but not the basis of anything, as people have lame resumes. Maybe it harvests the dates and titles, but no interpretive details

The owner also requested more explicit execution instructions and source-backed choices:

> This is another detail I wanted to tackle. Somewhere else we talked about writing procedures in robot/computer talk to minimize incorrect interpretation. Is this proposed draft in that vein? Can we make it even more specific and technical?

> Any time we can - if we have to leave something up to interpretation, we should direct the assistant to research standards or evidence-backed stuff. So like when it is constructing resume bullets, it should look up recommended best wording and stuff. Just to make sure that the assistant is meeting our standards even when outside our reach

These quotes record the drafting and review request. They do not record an owner acceptance, a merge instruction or a release decision. There is no GitHub owner start comment for this new work item. The author's scope interpretation is preparation of a generic draft for review, with Claude called out for subsequent review and the owner retaining the merge decision.

Source baseline: GAJkit `main` at `c1b62224d3802841c96af8a398c5c090c2d8318c`. Private source material is excluded from this record and from the product files. The cases below are synthetic and contain no candidate evidence or private links.

## Intended behavior

- Completion requires supported work, the candidate's agreement to the specific result, and readiness for the next activity.
- Each phase has explicit completion criteria. Phase 2 requires the candidate's complete work history discussed in detail, usable examples, a supported synthesis, honest gaps and retained interests, candidate agreement and practical readiness. Every role is included, even early or apparently unrelated work.
- An incoming resume supplies only a provisional chronology index. It cannot establish duties, accomplishments, metrics, capability or interpretation. Candidate-voice reconstruction supplies the account; other records can corroborate or challenge it. The new base resume is an output of that evidence, never independent proof of itself.
- Useful later work can proceed provisionally with stated limits while an earlier phase remains open. A finished research report does not finish discovery.
- The assistant checks the required current working sections and the conversation together. It repairs stale records from adequate existing evidence without repeating discovery or inventing approval.
- Explicit preference corrections update current inputs and affected recommendations. New factual contradictions still go through the evidence-conflict rules.
- Questioning stays conversational. There is no question quota, minimum duration, compulsory disclosure, forced story count or memory test. Material unanswered questions get targeted follow-up.
- One compact assessment in the existing journal records a proposed transition or material status change. No additional candidate form or tracking system is introduced.
- A controlled-language execution contract defines states, assessment scope, PASS/FAIL/UNKNOWN, evidence references, numbered requirements, transition logic and mandatory return from provisional work. An empty requirement set cannot pass.
- Five per-role conditions define the depth of the account. Confirmed absence of employment history is handled explicitly; an empty unknown inventory cannot pass by default.
- External method questions trigger a bounded research contract. Sources are classified by their actual support, guidance must fit the task, and the chosen method must be applied and checked. Candidate facts and preferences remain grounded in the candidate and permitted direct records.
- Resume bullets have a source/method/draft/comparison/inspection procedure with a synthetic supported-versus-inflated example. Method briefs can be reused within stated conditions; repeated cosmetic edits do not trigger repeated research.

The contract format is a drafting choice for this amendment, not a claim that a general procedure-writing standard has been adopted. These are instructions interpreted by an assistant, not an implemented software state machine. Explicit fields and checks make deviations reviewable; they do not establish guaranteed runtime compliance.

## Synthetic review cases

These are instruction walkthroughs, not live model trials or evidence of improved candidate outcomes.

| Case | Input condition | Required behavior |
|---|---|---|
| Sparse but confident | Several roles, one vivid story and a fluent strengths summary | Keep Phase 2 open; hear every uncovered role in detail. Confidence and good wording do not establish coverage. |
| Rich existing candidate account | Prior detailed candidate-voice conversations cover every role and support the profile and story set | Reuse and cite adequate accounts; do not repeat the interview for a new checklist. Confirm only interpretations or decisions not already accepted. Imported records alone cannot satisfy the walkthrough. |
| Impressive incoming resume | Polished duties, seniority claims and numerical achievements appear in a resume | Harvest only provisional chronology. Do not promote the prose into VERIFIED evidence, the profile or a shortlist; establish the actual work through the candidate's account and corroboration. |
| Weak incoming resume | A sparse resume lists titles and dates but reveals little actual work | Use it to propose the chronology and invite missing roles. Do not infer weak capability or limit discovery to its content. |
| Early or unrelated work | The assistant thinks an old role cannot matter to the current target | Hear that role anyway. Capture real work, personal scope, conditions and reflections without demanding an impressive achievement. |
| Similar roles | Several roles have similar titles and shared routines | Address each with the candidate; link shared context and explore changes. Do not silently omit later or earlier roles as duplicates. |
| Unrecoverable metric | Personal contribution and qualitative outcome are clear, but the exact number cannot be recovered | Close the numerical gap; use the supported qualitative claim. Do not invent a number or stall unrelated work. |
| Declined role | Candidate declines to talk through one role | Respect the decision and keep Phase 2 open. Remove or narrow dependent claims; offer a pause or bounded provisional work. Do not relabel the role immaterial or pressure the candidate to disclose. |
| Urgent application | A deadline precedes full discovery, but the evidence and approved materials for this role are sufficient | Proceed with the supported application work and existing review/submission controls; return to unrelated discovery as agreed. |
| Omitted interest | A candidate-stated pivot does not fit the first strengths summary | Retain it as an interest and agree investigation, deferral or rejection; do not silently discard it or invent qualification. |
| Stale preference | Candidate explicitly corrects a preference still driving the saved profile and research | Update the current preference and affected recommendations, preserving dated history. Do not treat a preference correction as proof of a disputed career fact. |
| Inferred fatigue | Candidate asks "What's next?" without declining further questions | Explain the next useful step. Do not record a preference for less discovery or treat the question as approval. |
| Unsupported completion label | A document says COMPLETE, but the profile lacks material evidence or candidate agreement | Reopen the affected condition and dependent claims. The label is not evidence. |
| Clerical incompleteness | Required tables are blank or marked draft, but the conversation already contains adequate evidence and specific agreement | Reconcile the records, save or hand back the full updated files, and cite the existing evidence. Do not force another interview or invent missing agreement. |
| Later-phase placeholders | Candidate discovery is complete but positioning and application tables are still empty | Do not block Phase 2 on work belonging to later phases. |
| Provisional choice | Candidate wants a bounded market scan without accepting the proposed profile | Agree and label provisional work; preserve the unresolved interpretation and its limits. Agreement to proceed is not approval of the profile. |
| No suitable contacts | Candidate has no suitable relationship leads or declines that channel | Respect the channel decision and continue supported work. Do not require a fabricated people list. |
| Accessible practice | Candidate tells stories in typed conversation with notes rather than an unaided spoken rehearsal | Count adequate own-words telling; record the mode and any relevant limits. Do not introduce a fluency or memorization threshold. |
| Resume as circular proof | A claim survives from an old resume into the new base resume without independent reconstruction | It fails the application evidence check. Trace to the candidate account and supporting evidence, or remove/narrow it. The base resume cannot prove itself. |
| Empty inventory | The role list is empty and nobody has confirmed why | History coverage is UNKNOWN. No automatic all-of-empty pass. |
| First employment search | Candidate explicitly confirms no employment history | Record the exception for history coverage only; obtain actual evidence for the other profile/story requirements from candidate-described experience. |
| Endless provisional research | A bounded scan finishes and another research idea appears | Surface the open discovery conditions and return, pause or obtain explicit agreement to a new bounded activity. Do not chain scans automatically. |
| Partial consolidation | An urgent application needs evidence from an already-discussed subset | Consolidate and approve that subset with a PARTIAL scope; do not present it as full-history coverage or a completed candidate model. |
| Unsupported best practice | A commercial article claims one phrase guarantees interviews | Seek suitable primary evidence; do not promote a marketing claim into empirical proof or a universal standard. |
| Inapplicable guidance | A student-oriented template is proposed for a specialist senior role | Assess applicability and obtain context-appropriate guidance where it changes the method; do not impose the student template unchanged. |
| Formula exceeds facts | A source recommends numerical results but the story contains no supported metric | Preserve the qualitative contribution. Never add a number or imply causation to satisfy a formula. |
| Research unavailable | Current method sources cannot be opened | Record RESEARCH_UNRESOLVED, use only bounded permissible draft work, and hold dependent unsupported claims. Do not claim verified standard compliance. |
| Scoped method reuse | The same evidence-supported bullet method is used on a cosmetic edit | Reuse the dated brief when its conditions hold; do not research each synonym. |
| Scope confusion | One application or interview preparation is complete | Mark only that application/preparation scope complete; do not close the search or an opportunity without its required evidence. |
| Employer closure during a pause | The employer rejects an application or withdraws an offer while the candidate has paused the search | Record supported closure under P6-O02 without requiring a completed offer evaluation or a new candidate next-step approval. Follow-up/outreach still requires its normal authority. |

## Review record

The initial auxiliary review identified three inconsistencies: the Prologue required both a push and a pull; Phase 5's opening required a people list; and parts of Phase 6 required spoken practice despite allowing typed practice elsewhere. This revision reconciles those instructions.

Final auxiliary review, 2026-11-21: **ACCEPT WITH CAVEATS as a reviewable draft**. The skeptical reviewer inspected all seven runtime files and the synthetic cases after corrections and found no unresolved fatal or material issue. This is a same-family auxiliary review, not an independent cross-family approval. A second read-only audit checked the resume-authority boundaries, research/source distinctions and privacy. Claude's subsequent review remains pending.

Findings corrected and verified:

- The generic gate originally required next-step agreement even to record employer rejection or offer withdrawal. Opportunity closure now uses the separate evidence-based `P6-O02` / `RECORD_CLOSURE` branch; a search pause or unfinished offer evaluation does not change the event.
- The synthetic resume example contained a purpose not present in its stated facts; the source facts now explicitly support that wording.
- An inherited claim about where most offers come from lacked support. The channel order is now an agreed starting approach tested against actual candidate outcomes.
- The added cases now form one contiguous Markdown table. The earlier push/pull, contact-list and practice-mode inconsistencies are also resolved.

Validation: all 30 synthetic instruction-walkthrough cases reviewed; `git diff --check` clean; code fences balanced; targeted private-residue scan and human privacy review found no candidate-specific content or private locators. The author and skeptical reviewer independently opened the MIT and Harvard guidance and checked the limited descriptions used here. These checks are not live model trials, hiring-outcome evidence or an enforcement guarantee.

Reviewed runtime fingerprints (SHA-256):

- `START-HERE.md`: `8a2c4ec941481730b830a6f712ee53699850dc869729533aad4ada312894bd0a`
- `phases/2-scouting-the-candidate.md`: `b4284dee77389ab9bc8cb6019be7e622e050718b52d02672ab534ae3c9c17aa8`

## Acceptance and follow-up

The draft is reviewable and reversible. Only the owner merges. Merging a kit change does not install it into a candidate's working files or issue a release tag. Before any separate core amendment, compare its existing reconstruction and readiness requirements rather than assuming this kit change updates them.

Known core alignment questions for later review: the separate GAJ core still uses "material" role coverage, permits prior resumes as evidence/reference, and includes some readiness checks without notes. This kit draft deliberately requires every role, restricts incoming resumes to chronology, and permits communication aids. No core file is changed by this draft.

Claude's review should challenge whether the checks prevent premature closure without creating an endless interview or a bookkeeping burden, whether all phases agree on provisional progress and readiness, and whether the source-conversation and file reconciliation rules preserve candidate authority.
