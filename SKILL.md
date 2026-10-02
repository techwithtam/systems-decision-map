---
name: systems-decision-map
description: Assess a business problem, automation idea, brain dump, or SOP before choosing a change. Map the desired outcome, current constraint, practical interventions, downstream effects, feedback loops, and possible next bottleneck.
---

# Systems Decision Map

Help the user understand how the work runs before deciding what to change.
Compare process changes, fixed-rule automation, AI, or a broader redesign using
the evidence they provide. All instructions are in this file.

## Start with the supplied context

Accept a messy explanation, notes, an SOP, or a request such as "we need AI."
Extract the outcome and current obstacle before asking questions. Follow the
six stages below in conversation and in the completed assessment. Keep options
and the recommendation inside Intervention.

If the evidence supports an assessment, provide it in one pass. Otherwise, ask
one question whose answer could change the decision. Fill in what the context
already answers. Do not require a six-part questionnaire or wait for every
detail before giving useful, clearly provisional analysis.

When someone cannot recall what happened, offer easy choices, including "both"
or "not sure," or ask to inspect one relevant example. If they ask about one
stage, answer it directly. If they change the goal, follow the new goal. Avoid
repeating a growing report every turn.

## Work through the six stages

### 1. First principles

State the valuable business outcome and the necessary conditions for it.
Separate that outcome from a performance target or proposed tool. "Proposals
in thirty minutes" is a target. Accurate proposals reaching clients promptly
with less staff effort is an outcome. Approved scope and pricing may be
necessary conditions; a transcript or AI tool is a possible method.

Ask what must remain true if the current tools and habits disappear. Preserve
quality as well as speed. Use the actual requirements of the case. Verify legal
or contractual requirements when they affect the decision; label disputed
premises as assumptions.

### 2. Constraint

Follow actual work through its trigger, inputs, decisions, handoffs, output,
recipient, and owner. Include the receiving handoff without mapping the whole
company. Look for waiting, missing information, rework, approvals, capacity,
demand changes, and incentives as well as manual effort.

Identify what currently limits the outcome, the supporting evidence, and any
alternative explanation that would change the intervention. Say when no
dominant constraint is established. Necessary conditions are different from
the current bottleneck. Every imperfect step does not need a project.

Keep the documented procedure separate from reported practice. One recent
completed case can reveal a failure mode, but cannot show how often it happens.
Compare normal and exception cases when that difference affects the design.
Separate hands-on effort from elapsed time. For a waiting period, identify who
is waiting for whom and what starts and ends the wait.

Check what existing tools already do. Follow their output into acceptance,
prioritization, action, and completion. Do not recommend extraction when
reliable extraction already exists. Vague frustration does not establish
missing ownership, poor motivation, or low adoption. Revise the diagnosis when
new evidence changes it.

### 3. Intervention

Compare concrete changes that could address the constraint. The smallest
sufficient change is the one that meaningfully addresses it. That can be a
substantial build. A small validation step and the desired system design are
separate decisions.

Consider removing unnecessary work, simplifying inputs, clarifying decisions,
assigning ownership, improving handoffs, connecting existing tools, automation,
or redesign. These are options, not a mandatory sequence. Automation or AI can
be the first intervention when the evidence supports it.

Choose the mechanism by the job:

| Mechanism | When it fits |
| --- | --- |
| Process change | Decisions, responsibilities, acceptance, capacity, or handoffs limit the outcome. |
| Fixed-rule automation | Structured inputs and stable rules can handle routing, calculations, scheduling, or record updates. |
| AI | Variable language needs interpretation, extraction, classification, or drafting. |
| Combined approach | AI handles interpretation; explicit rules handle known actions and checks. |
| Broader redesign | Several linked constraints require changes to data, workflow, authority, or tools. |

Name the capability before naming a product. Separate proposed tool behavior
from verified capability. Explain whether options are alternatives, additions,
or responses to different causes. Merge redundant choices. Use the current
approach as the baseline; include a separate "no change" option only when
there is a credible reason to choose it.

For each credible option, explain:

- Which failure it addresses and how the result should improve.
- Who does what, in which supplied tools, and who receives the output.
- Setup work, ongoing work, dependencies, and what remains manual or unresolved.
- Costs, expected value, reversibility, and material consequences.
- The review point and handling of missing inputs, uncertain results, or failed
  handoffs when those affect the choice.

Make decision authority concrete when it matters. Give a labeled proposed
rule, such as "the coordinator confirms requests within the agreed capacity
limit; exceptions go to the owner." Identify limits still needing agreement.
Do not invent approved fees, authority, or capacity. Keep review proportional
to errors and consequences; account for the checking work it creates.

Compare the added benefit of a larger option against the credible simpler
alternative. Do not credit automation for improvements the process change
already delivers. Separate one-time setup from recurring software, review,
maintenance, and exception costs. Use supplied figures or verified estimates.
Label assumptions and ranges. Explain qualitative effort ratings with concrete
work; do not invent hours or prices to fill a table.

When the inputs support calculations:

- Net capacity released is current operating time minus proposed operating
  time, including checking, maintenance, and exceptions. Keep setup separate.
- Net monthly benefit is the supported or explicitly assumed monetizable
  benefit minus added recurring costs.
- Break-even months is one-time investment divided by positive net monthly
  benefit. Zero or negative benefit has no finite payback under those assumptions.

Time saved becomes cash savings only when spending falls. Extra revenue also
needs demand, conversion, and delivery capacity. Use contribution after the
cost of delivery rather than gross revenue. Do not count the same time as both
labor savings and extra revenue, or assign a money value to trust or risk
reduction without evidence.

If numbers are missing, explain which benefit must exceed setup and ongoing
burden over the user's relevant time horizon. Ask only for inputs that could
change the choice. Show a threshold or alternate scenario when one assumption
drives the decision; avoid arbitrary scores or unsupported return estimates.

Put the conditional recommendation here. State why it fits the evidence, why
the simpler option is sufficient or insufficient, what would change the choice,
and the expected direct effect. Choose success and stop signals that test the
claimed benefit. Do not require a pilot when a change is already understood and
proportionate. Reconsider the recommendation after examining stages 4 to 6.

### 4. Second-order effects

Ask what could happen if the change works extremely well. Trace downstream
benefits and adverse effects, including changed behavior, shifted work, and
failure paths that could change today's choice.

For each material effect, identify the causal link, necessary conditions, time
horizon, affected people, and a signal to watch. Keep forecasts conditional.
Faster proposals might reach clients sooner; more signed work also depends on
demand and buyer decisions. More signed work could then increase onboarding
work. Speed alone does not create leads.

Distinguish safeguards needed before adoption from conditions to monitor later.
Follow additional causal steps only while they could change the current choice.

### 5. Feedback loops

Show how an effect changes behavior that returns to influence future work.
A one-way consequence, metric, dashboard, or review meeting alone is not a loop.
Make the return link explicit.

These examples are hypothetical:

- Reliable task status increases trust. People update records more consistently,
  which makes status more reliable and further increases trust.
- Inaccurate alerts lead people to ignore them. Issues remain unresolved,
  records become less useful, and people trust and update them less.
- A growing backlog leads the team to limit new commitments. Less incoming work
  reduces the backlog. Delayed action may let the queue grow before it improves.

The first two loops reinforce a change; the third counteracts it. Either kind
can help or harm the outcome. Label assumptions and explain the actual actors
and actions in this case. If evidence is insufficient, name the behavior to
investigate instead of inventing a loop to fill the heading.

Pair a plausible loop with a signal and response owner when useful. If it
changes the preferred intervention, revise stage 3 before delivering the assessment.

### 6. New constraint

Identify a plausible next limit after the present constraint is relieved and
the evidence that would reveal it. Treat it as a hypothesis until observed.
Do not infer staff-capacity problems from time spent waiting for a client.
Match the signal to the responsible person and the actual waiting state.

Explain what remains unknown and what new evidence would send back to stages
1 and 2. Recheck the original outcome. A possible next bottleneck does not
authorize another project or justify building for speculation.

Finish this section with one next action toward validating or implementing the
current recommendation, the observable result, and its limits. Separate that
action from monitoring after adoption. Shrink evidence gathering if the user
needs a lighter next step, while preserving the assessment.

## Write the completed assessment

Use the six numbered stage headings above in order. Target 600 to 900 words,
including tables; use up to 1,200 only when meaningful distinctions need the
space. Keep discovery replies shorter and do not pad simple cases.

Use plain language a smart seventh grader could follow while speaking to an
adult. Define unfamiliar terms once. Use short paragraphs for reasoning,
bullets for separate actions, and small tables for comparisons.

Give Intervention enough room to explain the real choices. A useful comparison
table is **Path | What changes | Effort | Cost and value**. Label starting
options and conditional additions in the rows. Use role-led action bullets
when several people or handoffs are involved. The table compares options;
the bullets explain who acts next. Avoid duplicating the same steps in both.

Keep each point in one place. Do not open or close with a repeated recommendation,
append an executive summary, or print a technical specification by default.
Expand a requested stage using the evidence already available.

## Example of applying the method

This example is synthetic. Its facts and recommendations apply only to this case.

A company reports that proposal drafts take four hours and wants them finished
in thirty minutes. Its notes also say drafts spend two days waiting for the
owner to approve pricing. Those are reported figures and a target, not measured
results.

1. **First principles.** Clients need accurate proposals with agreed scope and
   approved prices soon enough to make a decision. Faster writing is one possible
   way to help.
2. **Constraint.** Pricing approval may limit turnaround more than drafting.
   Check one completed proposal to separate working time from waiting. One case
   cannot establish how common the delay is.
3. **Intervention.** If pricing approval is the main delay, propose an approval
   rule with an owner and escalation path. The owner must agree the limits.
   If drafting is the main burden, compare structured extraction and a reviewed
   draft against the current method. AI may help that work. Count setup and
   checking effort; do not promise savings without measurement.
4. **Second-order effects.** Earlier proposals could increase signed work if
   timing affects buyer decisions. More signed work could increase onboarding
   demand if sales volume rises.
5. **Feedback loops.** Faster drafting could encourage sales to submit more
   marginal opportunities. Extra review leaves less attention per proposal,
   which could create more errors and rework. This is a hypothesis about behavior.
6. **New constraint.** Onboarding might become the next limit if signed work
   rises. Watch its backlog before proposing another system. The immediate next
   action is to trace one proposal from request to delivery and record working
   time, waiting time, and corrections.

## Evidence and permission boundaries

Keep facts, inferences, assumptions, proposals, and forecasts distinct. Preserve
source references. Never invent costs, durations, baselines, capabilities,
causal certainty, or returns. A plausible explanation is not a demonstrated cause.

Provide decision support. This skill does not authorize implementation,
spending, external communication, credential changes, or production actions.
Respect the user's existing authorization and ask before a consequential action
outside it. The user owns the business decision.

The skill requires no particular vendor, connector, other skill, or persistent
memory. Do not claim a proposed test ran, a report was saved, or a change was
made unless you verified it.

Before delivering, check that the six stages are in order, the recommendation
is inside Intervention, options address the supplied evidence, forecasts remain
conditional, feedback has a return link, and the next constraint has a signal.
Revise unsupported claims and dense wording before presenting the assessment.
