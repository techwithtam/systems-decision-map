# Worked output and anti-patterns

Use this as a quality reference, not a template to copy facts or recommendations from. The example is synthetic. Its recommendations depend on its supplied facts. Another case may justify AI or broader redesign first.

## Example input

A training company wants less work sending renewal reminders. Its subscription app exports stable IDs, dates, status, and contact flags. An administrator runs an exactly-30-days filter once a week, copies structured fields into a fixed approved Gmail template, and logs sent messages. Missing contacts go to account owners in Slack. A four-week record shows 18 hours of routine work plus two hours fixing contacts; some reminders were duplicated or late. Causes are not fully known. The subscription app can retrieve current status by ID; native reminders, current permission access, limits, and recovery are unverified. An unverified connection quote is $1,800 plus $40/month. Internal time value is assumed to be $40/hour; no staff reduction is planned.

## Example output

### 1. First principles

The outcome is that the right customers receive one accurate renewal reminder at the agreed time, with less staff work.

For that to happen, the company needs current contact permission and subscription details, a rule that finds every eligible renewal, a reliable record of what was sent, and a way to handle exceptions. AI is one possible method, not the outcome. The fixed template does not currently require interpretation or new writing.

### 2. Constraint

Routine filtering, copying, sending, and logging took 18 hours in the four-week record. That supports targeting repetitive handling. The weekly exactly-30-days filter also cannot cover every renewal date. The duplicates and reported reruns suggest a need to check what happens when sending and logging do not finish together, but the cause of each error remains unproven.

The problem appears to be selection and reliable processing, rather than unclear ownership: account owners already handle replies and missing contacts. The timing rule needs clarification before either option below can work reliably.

### 3. Intervention

| Option | What changes | Effort | Cost and value |
|---|---|---|---|
| Fallback: repair manual processing | Cover unsent renewals in an agreed window; check uncertain sends before retrying | Update the instructions and log; recurring copying remains | No new software proposed, but staff time remains a cost |
| Start here if checks pass: fixed-rule reminders | Find eligible records, send the existing template, and record results automatically | Verify native features first; otherwise connect and test the tools | Unverified quote: $1,800 plus $40/month; support scope needs checking |

**Manual fallback**

- **Operations lead:** sets the reminder window and rules for missed runs.
- **Administrator:** compares eligible subscription IDs with the sent log, checks current details in the subscription app, and sends through Gmail.
- **If an earlier send is uncertain:** the administrator checks Gmail before trying again.
- **Account owner:** receives missing-contact cases through Slack and resolves the details.

**Proposed automated path**

- **Scheduled process:** checks which subscriptions qualify and whether contact is permitted, then uses the approved template.
- **After sending:** the process records the Gmail result against the subscription and renewal date.
- **Administrator:** resolves failed or uncertain sends; ordinary messages do not need individual approval.
- **Before setup:** the operations lead verifies native reminders, current data access, duplicate prevention, sending limits, and recovery from a stopped run.

**Recommendation:** assess fixed-rule reminders first, with repaired manual processing as the fallback. AI adds no demonstrated value to this structured task. Broader redesign is not justified by the available evidence. The expected immediate effect is less routine handling, not a proven rise in renewals.

At the stated time value, the quoted connection must release more than 4.75 net hours per month over a year to exceed its supplier cost. Count ongoing checking and maintenance; extra setup cost raises the threshold. Compare against the repaired manual process. Released time is not payroll savings.

### 4. Second-order effects

If reminders become reliable and timely, administrator time may become available for other work. More customers could reply in the same period, increasing the account owners' workload. A bad sending rule could also reach many customers before someone notices. Watch total handling time, reply backlog, missing reminders, duplicates, and messages sent despite a contact restriction. Improved renewal rates remain unproven.

### 5. Feedback loops

A possible helpful loop is reliable sending records → staff trust the record → fewer unnecessary batch reruns → fewer duplicate messages → greater trust in the record. This depends on records being complete and staff using the recovery procedure.

The reverse could undermine it: uncertain records → staff rerun batches → more duplicates and confusion → less trust → more manual overrides. Track overrides and uncertain sends to see whether either pattern actually develops. Metrics reveal the loop; they are not the loop itself.

### 6. New constraint

If repetitive sending is reduced, missing contact details or handling customer replies may become the next limit. Watch unresolved contact cases and reply age before adding work or building more software. If those grow, return to the outcome and diagnose that constraint rather than adding AI by default.

**Next step:** have the operations lead obtain a capability-and-cost assessment covering native reminders and safe recovery. It should identify a feasible route; written claims still need validation before live sending.

Ask me to expand an option, check the costs, or walk through a feedback loop.

## Anti-patterns and repairs

| Anti-pattern | Why it fails | Better behavior |
|---|---|---|
| Start with “you need AI” or a recommendation | Skips the outcome and constraint | Establish stages 1–2 before choosing an intervention |
| Put “use our current app” under first principles | Confuses a method with a necessary condition | State the required result independently of the tool |
| Treat every annoying step as the bottleneck | May improve local effort without improving the outcome | Identify supporting evidence and plausible alternatives |
| “Improve communication / connect tools / rebuild” | Names categories rather than designs | Name people, changed steps, records, decisions, and remaining work |
| Require manual fixes before every automation | Turns a useful option into a ritual | Let the evidence justify which intervention comes first |
| Treat time saved as cash or guaranteed sales | Overstates economic and causal evidence | Show conditions and distinguish released capacity from realized benefit |
| Call “more sales → more onboarding” a feedback loop | It is a downstream chain with no return link | Explain how later behavior changes future operation, or keep it in stage 4 |
| Call “review a dashboard weekly” a feedback loop | Monitoring alone does not establish causal feedback | Name the observed change, response, and effect back on the system |
| Invent a loop to fill the heading | Adds unsupported certainty | Mark a plausible hypothesis or explain what remains unknown |
| Treat “reinforcing” as good and “balancing” as bad | Confuses loop structure with desirability | Show how either can help or harm this outcome |
| Prebuild the next bottleneck | Converts a forecast into unnecessary scope | Identify a signal and revisit diagnosis when it appears |
| Hide several actors and handoffs in one paragraph | Makes the reader reconstruct who does what | Use role-led bullets in workflow order |
| Present conditional additions as equal alternatives | Obscures which change addresses the evidence | Label the starting path and the condition for each addition in the comparison |
| Say “define authority” without an example | Leaves the business decision abstract | Give a proposed rule, its decision owner, and limits still needing agreement |
| Measure client waiting time to diagnose staff response capacity | The signal measures a different cause | Identify who is waiting for whom and the start/end events |
| End with a tiny tip instead of the six-stage assessment | Loses the user's understanding of the whole system | Complete the cycle, then give one action supporting it |

## Review before delivering

Are all six stages present in order? Is the recommendation inside Intervention? Are options tied to the source, forecasts conditional, and the feedback return path explicit? Is the new constraint a hypothesis with a signal, not another authorized project? Keep the language concrete and the full assessment within the agreed length.
