# Framework and causal reasoning

## Distinguish the concepts

| Concept | Meaning in this framework | Application |
|---|---|---|
| Business outcome | The valuable change sought by a person or business | Define an observable result and preserve quality, not just speed. |
| First principles | Necessary conditions and well-supported facts from which to rebuild the approach | Ask what must remain true if current tools and steps disappear. Treat disputed premises as assumptions. |
| Constraint | A factor currently limiting the desired outcome | Locate it in actual work; a frustrating step is not automatically the system bottleneck. |
| Intervention | A deliberate change intended to address that constraint | State how the change should improve the outcome and what it requires. |
| First-order effect | A direct consequence of the intervention | Estimate or measure the immediate change, including adverse effects. |
| Second-order effect | A consequence mediated by the first effect, changed behavior, or other system responses | Trace a causal chain and the conditions needed for each link. Include benefits and costs. |
| Feedback loop | An effect changes behavior that returns to influence future operation of the system | Trace the closed causal path; distinguish the loop from metrics used to observe it. |
| New constraint | The next limiting factor after the intervention relieves the present one | Name the evidence that would reveal it and reopen diagnosis rather than presuming another build. |

First principles are not synonymous with root causes, objectives, or existing process steps. “We use a spreadsheet” describes the current method. “The recipient needs accurate, approved scope and pricing” may be a necessary requirement. Legal or contractual requirements can be hard constraints, but verify their applicability when they matter; do not invent them.

## The six-stage cycle

First principles → Constraint → Intervention → Second-order effects → Feedback loops → New constraint → renewed diagnosis. Outcome and fundamental requirements live in First principles. Options, economics, the conditional recommendation, and immediate effects live in Intervention. The assessment must complete the later stages before the user acts; their implications can change the preferred intervention.

## Feedback is a causal return path

A list of risks is not a loop. Neither is “review results every week.” Explain how behavior feeds back: people trust reliable task status → update it more consistently → status becomes more reliable → trust increases. Conversely, inaccurate alerts → people ignore them → issues stay unresolved and records become less useful → trust and updating fall further. These are hypothetical reinforcing loops, one helpful and one harmful.

A stabilizing loop could be backlog increases → the team limits new commitments → incoming work falls → backlog decreases. Its usefulness depends on business goals, timing, and whether the team can act on the signal. Delayed responses may worsen the problem before correction occurs. Do not infer that all loops are beneficial or that the mere presence of monitoring creates feedback.

Show the return link explicitly and label assumptions. If there is insufficient evidence, state the plausible behavior to investigate rather than declaring a loop established.

## Ground the diagnosis

Choose a boundary wide enough to include the input and the receiving handoff, but do not map the entire company without need. Identify trigger, input, key decisions, work, output, recipient, and owner. Look for queues, missing data, rework, approvals, demand variability, and incentives as well as manual effort.

Use one recent case before requesting a large data exercise. Compare normal and exception cases if variability could change the design. Keep documented procedure and reported actual behavior separate. Repeated symptoms or a plausible story alone do not establish causation. Check what existing tools already do, then follow the output into acceptance, prioritization, action, and completion. Do not prescribe extraction because the initial input is unstructured when reliable extraction already exists. A single case can illustrate a failure; it cannot establish prevalence or eliminate other causes.

A local speed improvement may save labor without increasing total throughput. Distinguish capacity released, elapsed time reduced, quality improved, and revenue realized. Time saved is not cash saved unless spending falls or the capacity has a productive use. Consider setup, review, maintenance, and exception work in the net benefit.

## Choose an intervention

Compare only credible alternatives. Consider doing nothing, removing unnecessary work, simplifying inputs, standardizing decisions, assigning ownership, improving handoffs, and automation. These are options rather than a mandatory maturity ladder.

Judge options by expected outcome, evidence, effort, operating burden, readiness, reversibility, and consequences. Avoid arbitrary scoring that pretends to be objective. Prefer the smallest change that meaningfully addresses the constraint, not the smallest task regardless of value.

For AI-supported work, identify what can be drafted versus what needs authoritative data, explicit rules, or human judgment. Identify the owner, review point, and path for incomplete or uncertain inputs. Do not assume a prompt resolves missing business decisions.

## Trace effects without inventing inevitability

For each material consequence, name: the causal mechanism, conditions, time horizon, who is affected, and an observable signal. Quantify only when supported; otherwise label the forecast qualitative. Consider both desirable and adverse consequences, behavioral adaptation, shifted workload, feedback loops, and delays.

Pursue additional causal steps only while they could change today's choice. Distinguish safeguards needed before the pilot from conditions to monitor later. A possible future bottleneck does not automatically justify building a new system now.

## Worked example: proposals

Reported problem: proposals take four hours; desired target is thirty minutes. These are a reported baseline and a target, not demonstrated results. Establish whether they refer to hands-on effort or turnaround, and whether accuracy and approval quality must remain unchanged.

Necessary requirements might include verified client needs, agreed scope, approved pricing, exclusions, and a usable client-facing document. Transcript extraction and benefit-led writing are possible methods; a transcript may not contain all required decisions.

If extraction and drafting dominate the effort, a candidate intervention is structured extraction with source references, missing-information flags, a standard proposal draft, and owner review. If the delay is pricing approval, drafting automation may leave the actual turnaround constraint intact.

Direct effects could include less drafting effort and new checking work. Further effects could include earlier delivery of proposals; better conversion is conditional on responsiveness affecting buyer decisions. More accepted proposals could increase onboarding demand only if sales volume actually rises. Monitor signed work and onboarding backlog before creating a larger project management system.

An illustrative pilot is to compare the current and proposed method on a small set of representative historical proposals, including an incomplete-input case. Count setup and review effort, omissions, unsupported claims, and necessary corrections. Agree sample size and acceptance thresholds with the owner; a small pilot is a feasibility signal, not statistical proof. If there is no reliable baseline, observing the next proposal may be the better first step.

In the proposal example, a possible feedback loop is faster drafting → sales submits more marginal opportunities → review/rework increases → less attention per proposal → more errors and rework. That depends on actual sales behavior; it is not inevitable. A next constraint might be pricing approval, onboarding, or delivery capacity, depending on what the measured results show. Revisit the outcome and current constraint when that evidence arrives.
