# Alembic: refine the process, then share the method

A finished piece can leave behind more than a published URL. It can show which
part of your process made the work better, which part merely kept you busy, and
which safeguard stopped a mistake. Alembic turns that residue into a reviewed,
reusable method.

Use it after a substantial collaborative run, an operator-requested skills audit,
or a failure that should be cheaper next time. It is a process for improving
skills and templates, not a substitute for editorial or publication approval.

## The loop

```
RECOVER → DISTILL → REFINE → INDEPENDENT AUDIT → MERGE → GENERALIZE → PUBLISH
```

1. **Recover the evidence.** Read the accepted edits, review comments, actual
   gate decisions, verification output and final artifact. Distinguish human
   decisions from the assistant's claims about them.
2. **Distill the lesson.** Keep repeatable behavior, concrete before/after
   examples and the evidence boundary. Put one-off subject matter in the work
   record, not the shared guide.
3. **Refine the local skill.** Put operative rules near the behavior they change.
   Remove duplicated case history only when the rule survives in shorter form or
   a clearly linked reference. Preserve security, trust, provenance and
   verification floors.
4. **Audit the exact change independently.** A reviewer who did not make the edit
   checks the complete before/after artifact, deleted safeguards, broken paths,
   factual claims and completion criteria. A smaller file is not proof of a
   better process. Address findings and rerun checks against the final snapshot.
5. **Merge only after the audit and existing checks pass.** Record the real PR
   and merge state. Editing a local skill is not a shared contribution.
6. **Generalize the method.** Remove private names, handles, paths, credentials,
   unreleased plans and other particulars. Preserve the mechanism and its
   limitations. A public artifact should not depend on private context to make
   sense.
7. **Publish through the destination's own review flow.** Preview, verify the
   rendered artifact, obtain the required approval and publish. Only then share
   its live URL. Do not claim publication from a branch, draft or intended path.

## Acceptance contract

A refinement is ready for review when:

- the trigger says when to use it, and when not to;
- each step has a checkable completion condition;
- every deleted safeguard is either retained elsewhere or explicitly retired by
  the responsible human;
- source quotations and before/after examples match the actual artifacts;
- paths and references resolve in the environment where the guide will be used;
- no new universal rule is inferred from one person's single edit;
- an independent reviewer can reconstruct why this change exists without reading
  the whole original incident.

## What to record

| Field | Contents |
| --- | --- |
| Evidence | accepted edits, reviewer words, gate decisions, verification output |
| Behavior | the action a future run should take differently |
| Boundary | what this method does not authorize or prove |
| Snapshot | exact files, branch or commit reviewed |
| Independent audit | findings, fixes and final verdict |
| Contribution | PR, checks, merge state and live artifact URL |

Keep the incident log for provenance. Keep the skill short enough to be used.
The formal taste ledger carries the operator's exact edits and verbatim reasons;
a summary of them is not a substitute for that diff.

## Common failure modes

- **Compaction by amnesia.** Deleting the rule with the anecdote that carried it.
- **Process laundering.** Turning a near-miss into a polished success story that
  hides the actual correction.
- **Self-approved review.** Calling your own reread an independent audit.
- **Premature completion.** Reporting a local edit, opened PR or approval as a
  merged or publicly live artifact.
- **Genericity by subtraction.** Removing every concrete example and leaving only
  advice such as “be clear” or “verify carefully.” Retain an anonymized
  before/after that makes the behavior testable.
- **Ceremony accumulation.** Adding a checklist whose completion does not change
  the next action. Remove or shorten it.

## Minimal worked example

**Residue:** a reviewer asks for the same explanation three times in one piece.

**Weak rule:** “Avoid repetition.”

**Useful refinement:** “After an example has established the point, delete the
next sentence that merely labels its significance. Replace it only when the
reader needs a new fact, limitation or action.”

**Independent check:** find the repeated explanation in the before/after artifact
and verify that the final text retains the example and the required permission
boundary.

**Contribution:** keep the human's exact correction and diff in the private taste
ledger; publish the generalized rule without their private thread or project
details.

## License

This guide is released under the repository's [CC BY-SA 4.0 license](../LICENSE.md).
