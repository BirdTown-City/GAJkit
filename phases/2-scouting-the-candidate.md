# Phase 2: Scouting report on the candidate

**What it gives the candidate:**

- an understanding built by talking through their complete work history in detail;
- their few big stories and key skills, with evidence;
- an honest view of their strengths and weaknesses, and a first plan for each important gap;
- confidence in their own skills and experience;
- the ability to explain their career naturally, spoken or typed, with aids where useful.

**How:** the candidate talks their career through in their own words, out loud or typed. You reflect it back, ask follow-up questions and name patterns. That conversation is the method, not background to a questionnaire. Give it proper time: most of the phase's value comes from it.

**Before you start:** the candidate has an accepted goal (Phase 1), and `story-bank.md` exists from the layout at the end of this file.

Resume material is one output of this phase among several. Don't begin by rewriting the resume.

## Step 1. Gather what already exists

Ask for whatever the candidate has: resumes, their LinkedIn profile, performance reviews, project documents, job descriptions, notes, portfolios, certifications, earlier interview notes, anything that shows scope or results.

Rules:

- Use an incoming resume only as a provisional chronology index: employers, titles and dates. Ask the candidate to correct it and add missing work. Don't harvest its duties, achievements, metrics or interpretive details as discovery evidence, and don't use its language to decide who the candidate is.
- Reconstruct what happened from the candidate's own account before interpreting it. Other records can corroborate or challenge that account, including scope, dates and results, but cannot stand in for the candidate talking their work through.
- Keep contradictory sources; don't discard them. Resolve the conflict with the candidate.
- List each source in the Sources section of `story-bank.md`; mark an incoming resume "chronology index only". A detailed earlier candidate-voice transcript is different from a resume or a third-party summary: it can supply an existing account, subject to the checks in Step 2.

## Step 2. Talk the career through

Talk through the candidate's complete work history in detail: every job, contract and self-employed role, including early, short, overlapping and apparently unrelated work. Within a role, cover distinct programs or substantial changes in what they did. The candidate tells it in their own words; you listen, reflect back, follow up and then propose patterns. A title, employer, field or resume bullet is never a substitute for their account.

First make a brief career coverage map in `story-bank.md`. Use any resume chronology as a starting index, then ask the candidate to correct it and identify work it leaves out. Invite other experience they want considered, such as study, volunteering or independent projects; private life is not a required disclosure. Choose a comfortable order with them, but account for every work role before Phase 2 can be complete. The apparent relevance to today's target does not decide which roles get heard.

For each role, establish a detailed account of what the work actually involved, what they personally did and could decide, who they worked with, the conditions and difficulties, what happened or changed where known, and what they learned, enjoyed or disliked. Use concrete episodes or descriptions of typical work to understand those details. Do not require an impressive achievement, numerical outcome, leadership claim or failure story from every job. A title, a generic duty list or a yes/no endorsement of your summary is insufficient.

Similar roles need not take identical time, but each gets the candidate's account: what carried over, what changed and what that role was like. Link shared context rather than asking them to repeat it. An adequate earlier conversation in the candidate's own words counts; check that it covers the role and follow up only on missing details. Imported resumes, inferred narratives and other people's records do not satisfy this requirement.

Complete coverage and story selection are separate. Every role must be discussed; only some examples become lead Story Cards or resume-bank entries. A strong set of selected stories never compensates for an undiscussed role.

Mark a role discussed only when that account is captured, with a reference to the conversation. If a role is pending or declined, retain it in the map and keep Phase 2 open. Respect a refusal without pressure and offer a pause or bounded provisional work; do not relabel the role "not material" to pass the completion check. Unrecoverable details within an otherwise detailed account are honest limits, not a reason to invent facts or repeat the whole interview.

### Per-role account contract

**PURPOSE:** define "in detail" by observable content rather than question count or narrative length. **INPUT:** a role from the candidate-checked chronology and their own account. **OUTPUT:** a concise role account in the journal, linked from the coverage map; reuse existing content rather than transcribing it twice.

| ID | Required content for PASS |
|---|---|
| `P2-R01` Actual work | The candidate describes what the organization/team needed and what their ordinary work involved. A title or generic job description alone fails. |
| `P2-R02` Personal contribution | Their own actions and responsibility are distinguishable from the team's work. Ownership, assistance and decisions made by others are explicit. |
| `P2-R03` Working context | Their account explains how work was assigned or decided, who they worked with by role, and relevant conditions or difficulties. Names and private-life detail are not required. |
| `P2-R04` Concrete detail | At least one specific episode or sufficiently concrete description of typical work shows how they performed it. A typical-work account describes actions or decisions in context; "helped people" or a strengths adjective fails. No impressive achievement or separate polished Story Card is required. |
| `P2-R05` Results and reflection boundaries | Record what happened or changed where known, what they learned/enjoyed/disliked where supplied, and explicit limits where a result, number or reflection is unknown, unrecoverable or declined. Those limits restrict claims; they are not replaced by estimates or inferred preferences. |

MUST evaluate `P2-R01` through `P2-R05` against candidate-account references. A filled cell containing only "unknown" cannot pass `R01` through `R04`. For `R05`, the requirement is an honest account of results/reflections **or their explicit limits**, not a compulsory metric or personal disclosure. MUST NOT turn a missing nonessential detail into repeated demands for the whole account.

```text
role_discussed(role) := all P2-R01..P2-R05 PASS with candidate-account references
history_complete := candidate has checked the inventory for missing work
                    AND every work-history role satisfies role_discussed
# Evaluate all roles, not only those selected for the resume.
```

An empty role list is `UNKNOWN`, not automatic success. Exception: an explicit candidate statement confirming no employment/self-employment history satisfies history coverage; record that statement. Other Phase 2 requirements still need their own evidence, which may come from study, projects, volunteering or other candidate-described experience. Never invent a job or capability to fill the empty list.

Use these as follow-ups, not a questionnaire to read out:

- What were you handed? What was the stated goal?
- What was actually difficult?
- What was already known, and what had to be discovered?
- What was broken?
- Who had authority? What decisions were yours?
- Where did you influence without authority?
- What did you personally build, change, decide, stabilize or unblock?
- Who did you work most closely with? (Note names and the relationship when they come up naturally: manager, peer, report, sponsor, client, vendor, partner, recruiter.)
- Who from this role might be worth remembering for future networking?
- What happened? What failed?
- What did you learn? What would you do differently?
- Which parts engaged or absorbed you, and which drained you?
- When did this work feel meaningful, if it did? Why?
- Were you doing it because you were good at it, because you wanted to, or both?
- What evidence could verify the story?

Rules:

- Don't interview only for wins. Mistakes, reversals, conflict and hard environments reveal how the candidate works.
- Seek a contrasting example that could change an emerging pattern: a different context, an exception, work done well but disliked, or an outcome that was mixed. Do not require a failure story or disclosure of a distressing event. If no contrast can be established, keep the pattern appropriately tentative instead of inventing one.
- Capture what happened before naming capabilities or writing resume bullets.
- Separate what the candidate did from what the team or program did.
- Capture names only as they come up naturally; this isn't contact harvesting. Naming someone doesn't authorize outreach, and a remembered name may be out of date.
- Keep evidence that cuts against the goal: a stronger nearby pattern, or competence without engagement. The candidate may be very good at work they don't want to repeat.
- Don't drop a real strength, preference or anti-pattern just because it's unrelated to the goal.
- **Journal as you go.** Each sitting gets a dated entry in `journal.md`: what the candidate said, in their words where possible, the patterns you noticed, and questions to come back to.

## Step 3. Write Story Cards

For each story that matters, write a Story Card in `story-bank.md`. Fill only what's supported; never invent a field to complete it. Give every fact a confidence label (`START-HERE.md`), and write the claim boundary: what the story supports saying and what it doesn't.

Distinguish a specific episode from a general approach or recurring recollection. A general pattern can be useful, but it does not become a specific accomplishment because you put it in a Story Card. Probe for context, the candidate's role, personal actions or decisions, what happened and what remains unknown. An outcome need not be numerical or successful. A missing exact number does not invalidate a well-supported qualitative story.

Raw detail can stay in the card's internal-only field.

## Step 4. Consolidate the journal

Once the complete work history has been talked through in detail, read all the journal entries and Story Cards together and find:

- skills that occur again and again;
- recurring ways of working;
- leadership styles;
- the stories strong enough to go into the **resume bank**.

Each finding cites the journal entries and cards it comes from. Each is a proposal until the candidate agrees. Consolidation compresses evidence; it never creates a fact. Record the round in the Consolidation section of `story-bank.md`.

For an agreed provisional activity, MAY consolidate an already-discussed subset early. Mark the round's scope `PARTIAL: <activity>` and approve only the meanings needed for that activity. It may supply supported evidence for an urgent application; it MUST NOT satisfy full-history coverage or be described as the complete candidate profile.

**Run it again later** whenever a good batch of new journal entries has built up: new stories from interviews, new work, things the candidate remembers. A later round follows "Keeping the Story Bank current" below.

## Step 5. Propose who they are at work

Propose, in separate categories (don't collapse them into one strengths and weaknesses list):

- recurring strengths and capabilities;
- ways of working and leadership style;
- technical and domain fluency;
- what engages them and what drains them;
- environments they do well in, and poorly in;
- development areas;
- evidence gaps;
- role types worth testing: the problems employers hire someone like them to solve.

Ask about direction too:

- What do you want more of in the next role? Less of?
- What would make the next role a real step forward?
- What won't you trade away just to grow your career?
- What did talking it through confirm, weaken or overturn about the goal?
- Are there pivots you want considered even if the evidence is thin?

Keep these distinctions:

- A missing credential isn't automatically a weakness.
- An evidence gap isn't proof of an absent ability.
- A poor fit with one environment isn't a flaw in the person.
- A claim boundary doesn't mean they lack the nearby, transferable skill.
- The candidate's hopes aren't evidence, and never go into a resume, letter, profile or interview claim.

**The two-sided test for a development area.** Call something a development area only if both are true: (1) after checking the evidence, the capability really is absent or weaker; and (2) the candidate wants it, or a sample of the market at the next level shows it keeps coming up. Otherwise, keep it as a proposal.

Mark each item by source: **observed** (from the evidence, with the story it comes from), **stated** (the candidate said or approved it) or **proposed** (your idea). A proposed item can be shown to the candidate but shouldn't steer anything until they adopt it.

Direction and role types stay proposals here. Phase 3 tests them against the market, and the candidate authorizes them there.

## Step 6. Check the meaning with the candidate

For each interpretation that matters, ask:

- Is this really what the story proves?
- Which story best shows this capability?
- What should a hiring manager notice?
- What framing would be technically true but misleading?
- What's the strongest true verb?
- What scope has to narrow to make that verb true?

Write the approved interpretations into "Who they are at work" in `candidate-profile.md`, and mark anything unresolved. Once the candidate approves what a story means, reuse that meaning; don't re-derive it each time.

## Step 7. Build the capability map

For each approved capability, fill a row of the Capability map in `candidate-profile.md`: what they reliably do, the best and backup stories, the strongest true verbs, the claim boundary, and the cues in job postings that call for it.

One story can support several capabilities. Capability labels help you find evidence; they aren't wording for a resume. The map never makes a claim stronger than its story.

Then write an **Evidence Sheet** in the resume bank for each story the candidate agreed to elevate in Step 4, citing the capabilities it proves.

## Step 8. List the open questions

Add unresolved questions to the Open questions section of `story-bank.md`, each with its type: a document to find, something only the candidate can clarify, a conflict between sources, a number worth digging for, or a closed gap that can't be recovered. For each, state the claim or decision it blocks, or why it is non-blocking, plus the next action or a reason no further action is needed. A closed gap gets marked closed, not searched for again. Remove or narrow claims that depend on an unresolved conflict; labelling the conflict does not make the claim usable.

## Step 9. Write the candidate profile

Write a short, plain-language profile of the person, not aimed at any one job, with no buzzwords. It should read like a good colleague describing them:

- the goal;
- strengths toward that goal, each with its best story;
- areas for growth toward the goal;
- proudest or brightest moments;
- what they enjoy and what drains them;
- the gaps between where they are and the goal;
- a first plan for each important weakness or gap: **BUILD** it, **SHOW EVIDENCE** for it, **WORK AROUND** it, or **BE UPFRONT** about it.

Every strength cites approved evidence. Growth areas pass the two-sided test. Read it back and revise until the candidate recognizes it as true. Write it, and the first gap plan, in `candidate-profile.md`.

## Step 10. Build the interview-ready set

From the Story Bank, choose the candidate's few big stories, normally five to eight, by evidence strength and coverage of their key skills, not novelty. That range is a guide, not a quota or a minimum: explain why the selected set covers the capabilities being proposed, including when a shorter career supports fewer stories. Several variants of one anecdote do not provide independent coverage. For each, record in `story-bank.md`:

- the Story Card;
- the skills it proves;
- the themes or question types it answers;
- two or three short prompts that help them tell it (cues, not scripts);
- its claim boundary.

Have the candidate tell each selected story in their own words, spoken or typed, at least once. A telling already captured during discovery counts; don't make them repeat it for a checkmark. Notes, cues and other communication aids are welcome. Check that they recognize their role, actions, outcome and claim boundary; this is not a memory or confidence test. If they choose to defer practice, record which story remains unpractised and the resulting readiness limit. The set is reused and refined for interviews, recruiter calls and networking conversations.

## Step 11. Check they got there

Apply the shared completion rule in `START-HERE.md`. Check all of the following against the actual work:

Read the career coverage map, relevant Story Cards, consolidation findings, capability map, candidate profile, gap plan, open questions and selected story set. Check any Evidence Sheets chosen for reuse. Required outputs need substantive content, or a reference to where that content is recorded; a template heading is not an output. Don't invent a weakness, backup story or metric to fill a field. If existing conversation supplies missing content or approval, reconcile the files before declaring completion. Empty positioning, application or other later-phase sections are not Phase 2 blockers.

| ID | Required condition and PASS evidence |
|---|---|
| `P2-G01` Complete history | The Step 2 `history_complete` predicate is true, with chronology confirmation and per-role account references, or the explicit no-work-history exception is documented. No role is skipped for being early, unrelated or apparently unimportant. A pending or declined work-history role fails this condition. |
| `P2-G02` Usable stories | The selected set contains representative, supported examples of the capabilities being proposed, with personal contribution, actions, outcomes and limits preserved. General patterns are labelled; they do not stand in for missing episodes or outcomes. |
| `P2-G03` Supported synthesis | Profile strengths and the capability map cite approved evidence grounded in the candidate's account, with corroboration where available. No interpretation comes from resume wording or a title. Ability, enjoyment, working conditions and market qualification remain distinct. Contrary evidence has been considered; unsupported patterns remain proposals. External role/skill-method questions use `RS-01` through `RS-08`. |
| `P2-G04` Gaps and interests | Important gaps have a handling plan and consequences. Development areas pass the two-sided test. Stated interests and pivots are retained for Phase 3, including thin-evidence interests. An explicit finding of no identified development area is valid; no invented weakness is required. |
| `P2-G05` Candidate agreement | A `candidate_ref` shows acceptance of this profile and its material interpretations, with corrections incorporated. An unresolved interpretation is excluded from steering a decision it could change. Approval of the Phase 1 goal does not satisfy this condition. |
| `P2-G06` Practical readiness | The candidate has told the selected stories in their own words under Step 10, connects proposed key skills to examples, and understands important claim limits and gap handling. Cite the tellings and discussion; spoken or typed accounts and aids count. Confidence, polished performance and unaided recall are not requirements. |

Read back the resulting picture briefly. Ask what significant work, capability or interest it still misses, and whether they want to explore that before moving on. Their existing answers may satisfy parts of the check; do not repeat an interview already supported by the record.

`DONE WHEN`: `P2-G01` through `P2-G06` all PASS and the `TR-01` through `TR-07` completion checks are satisfied. A failed or unknown condition keeps status OPEN, unless PAUSED. Any provisional transition uses `CONTINUE_PROVISIONALLY` and `TR-08 RETURN`. "What's next?" is a request for guidance, not proof these conditions are met.

A provisional market scan can test an interest or show what further evidence would matter. It must not present the candidate profile as complete, treat an untested preference as a settled direction, or turn an unverified capability into a qualification claim. Preserve useful research and existing stories. Return to every still-uncovered role and to the interpretation or practice that remains open; don't restart roles already discussed in adequate detail.

## Keeping the Story Bank current

New evidence keeps arriving: a document turns up, the candidate remembers something, an interview shows a story lands differently, a consolidation round finds a new pattern.

1. Write it in the journal first.
2. Label its confidence.
3. Decide with the candidate, for anything that changes meaning:
   - **PROMOTE**: it becomes usable, or more usable;
   - **CORRECT**: it fixes an existing fact;
   - **QUARANTINE**: it conflicts with something; hold both, use the safer one, until resolved;
   - **NO CHANGE**;
   - **CLOSE GAP**: the fact can't be recovered;
   - **DEFER**.
4. Update everything that depends on it: the Story Card, the Evidence Sheet, the capability map, the claim boundaries, the candidate profile, the base resume, LinkedIn and any open application. Say what you changed.

One interview or one rejection doesn't rewrite who the candidate is. Record the observation, and change the profile only when the evidence is strong enough or repeats.

---

## Layout of `story-bank.md`

Create this file on the first run.

```markdown
# Story Bank

## Sources
| ID | What it is | Date | Where it is | Notes |
|---|---|---|---|---|

## Career coverage
Inventory checked for missing work: UNCONFIRMED / CONFIRMED (candidate reference and date)
No work-history exception, if applicable: (explicit candidate reference)

| Role, program or other experience; dates | Candidate's account (journal/conversation reference) | Status: pending / discussed / declined | What they did, scope and conditions; examples and reflections | Remaining question or limit |
|---|---|---|---|---|

For each work-history row, record P2-R01..P2-R05: PASS / FAIL / UNKNOWN, with account references. Optional additional experience must be distinguishable from the complete work-history inventory.

## Story Cards

### SC-01: short title
Status: draft / approved
Kind: specific episode / general pattern
Use for: (themes, question types, capabilities)
Sources and confidence:
Context and problem:
Candidate's role and scope:
Authority and decision rights:
Who else was involved:
What the candidate did:
Outcome or changed state:
Scale and complexity:
Technology or domain:
What failed, and lessons:
Claim boundary (safe to say / don't claim):
Best uses:
Internal only (never used outwardly):
Open questions:

## Interview-ready set
| Story | Skills it proves | Themes it answers | Telling prompts (2 or 3 cues) | Claim boundary | Told in candidate's words on (spoken / typed; aids welcome) |
|---|---|---|---|---|---|

## Resume bank (Evidence Sheets)

### ES-01: anchor story (SC-xx)
Elevated by: (consolidation finding)
Capabilities it proves:
Key facts, each with its confidence label:
Approved outcomes:
Strongest true verb:
Claim boundary:
True but usually not for a resume:
Where it appears in the base resume:
Approved wording:

## Consolidation rounds

### Round N: YYYY-MM-DD (initial / later)
Scope: FULL / PARTIAL (named provisional activity)
Journal entries read:
Story Cards read:
| Finding | Type (recurring skill / way of working / leadership style / story for the resume bank) | Cites | Candidate's answer (agreed / changed / declined, date) | Feeds |
|---|---|---|---|---|

## Open questions
| Question | Type (document / clarification / conflict / number to dig for / closed gap) | Current safe wording | Blocks which claim or decision, or why non-blocking | Next action or reason none | Status |
|---|---|---|---|---|---|
```
