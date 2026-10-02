# Options and investment inside Intervention

Use this reference within stage 3 of the six-stage cycle. It supports choosing the intervention; it does not replace First principles, Constraint, Second-order effects, Feedback loops, or New constraint.

## Build credible alternatives

Compare a range of interventions only when they offer distinct, plausible value. Use the current approach as a comparison baseline; show it as a separate option only if there is a credible reason to choose it. Consider:

| Level | Typical changes | Decision to explain |
|---|---|---|
| Minimal process change | Clarify a decision, acceptance, ownership, input, or handoff using existing tools | What improves with little setup, and what stays manual or unresolved? |
| Targeted system improvement | Connect existing records, add rules, route exceptions, automate a proven handoff | What incremental benefit justifies setup and continued maintenance? |
| Broader redesign | Restructure data, workflow, authority, interfaces, and multiple integrations | What additional capability warrants greater cost, disruption, and dependency? |

These are comparison levels, not a mandatory ladder or three required builds. Merge redundant options, reject unsupported ones, or explain when a broader redesign would become justified. Do not make the broad option artificially attractive or present the smallest option as universally best.

Tie each option to the supplied SOP or observed failure, naming the changed steps, responsible people, tools, and checks. Separate intended tool behavior from verified capabilities. A broader option can change how work is accepted and scheduled without requiring a software rebuild. For each credible option cover: mechanism and workflow change; expected benefit and limits; direct cost or burden; implementation effort; operating effort; dependencies and readiness; reversibility; and material second-order effects. Consider data quality, authority, adoption, exceptions, source coverage, and who owns ongoing operation.

Name the capability before the product. Verify proposed capabilities are not already available and reliable. AI may interpret unstructured material; deterministic rules may better handle known statuses and routing. Neither substitutes for accepted decisions or available delivery capacity. Consider failed integrations, duplicate or stale records, manual overrides, and recovery when relevant to the proposed design, not as a universal checklist.

## Choose the mechanism and explain the paths

Distinguish the job each mechanism does:

- **Fixed-rule automation:** move structured records, match IDs, apply known conditions, calculate, schedule, or route work using explicit rules. Prefer it when the rules and inputs are stable.
- **AI:** interpret variable language, extract from inconsistent material, classify ambiguous requests, or draft content when interpretation adds value. Identify how uncertain results are handled and how error/review costs affect the choice.
- **Combined approach:** use AI only for the interpretation step and rules for known actions, checks, and routing. Do not add AI to every connected workflow.
- **Workflow redesign:** change decisions, responsibilities, capacity allocation, or handoffs when those are the constraint.

Explain whether options replace one another, build on a common foundation, or address different failure modes. Make that relationship visible in the comparison table as well as the prose; mark conditional additions and state their triggering evidence. Give concrete proposed decision rules when authority is part of the intervention, while keeping unapproved limits explicit. Use a conditional recommendation where helpful: **Start here** with the justified design; **add fixed-rule automation or AI if** a specific remaining problem merits it; **change the wider workflow if** evidence points to a different constraint. Adapt these labels to the case. Automation or AI may be the starting recommendation when supported; never impose manual process repair as a prerequisite by default.

Distinguish design fit from demonstrated results. “This addresses the missing handoff shown in the examples” is evidence-supported; the size of the benefit remains a forecast until measured. State why a recommended change is expected to help and what could change the choice.

Make review proportional to errors and consequences. Name which cases need review, by whom, and why; avoid requiring someone to approve every output without evidence that this control is needed. Consider a sample, rule-based checks, or exception-only review when appropriate. Include the new review work in total effort rather than counting a transfer of checking as savings.

## Compare investment honestly

Compare the incremental value of a larger option against the credible simpler alternative, not only against today’s inefficient process; do not credit automation for benefits the simpler process change already delivers. Separate implementation cost from recurring software, review, maintenance, and exception cost. Use provided figures or verified estimates, and label ranges and assumptions. Qualitative low/medium/high effort needs a concrete reason; it is not a quote or delivery promise. Do not invent hours or market prices to fill a table.

Use transparent scenario arithmetic when inputs support it:

- Net capacity released = current operating hours minus proposed operating hours, including review, maintenance, and exception handling. Keep implementation effort separate.
- Net monthly benefit = evidenced or explicitly assumed monetizable benefit minus incremental recurring costs. Do not count the same released time as both labor savings and extra revenue.
- Break-even months = one-time investment divided by positive net monthly benefit. If net benefit is zero or negative, there is no finite payback on those assumptions.

Keep time value distinct from realized cash savings. Additional revenue requires demand, conversion, and delivery capacity; use contribution rather than gross revenue when assessing incremental economic benefit. Do not monetize trust, quality, or risk reduction without a defensible basis; they can remain explicit nonfinancial decision criteria.

When numbers are absent, explain the investment condition: the option becomes worth considering if the value of reduced work, errors, delay, or enabled capacity exceeds setup and ongoing burden over the user's relevant horizon. Identify only the missing inputs needed to evaluate that condition. If the choice is sensitive to one assumption, show the threshold or alternate scenario rather than implying a precise ROI.

## Recommend with conditions

Tie the recommendation to the outcome and evidence. State why the cheaper option is sufficient or insufficient, what extra value a larger option buys, and what finding would change the choice. Readiness may justify a staged path; do not require a ceremonial pilot when the change is already understood and proportionate.

Distinguish the selected destination from the next step. A small validation action can precede a substantial build; a large vision does not authorize building everything now. Choose success and stop signals that actually test the claimed benefit, not just the system's ability to produce output.
