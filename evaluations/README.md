# Behavioral cases

These cases are newly written synthetic inputs. They contain no real author, course, submission, customer or account data. They are quality checks, not an AI-authorship detector benchmark.

For each case in [cases.json](cases.json):

1. Give an agent the package Skill, the case request and its source. Keep the check list out of its prompt when testing independently.
2. Permit only the side effects the case allows. These fixtures require no web research, installation or external transmission.
3. Have a reviewer compare the result with the source against the case's checks and the [evaluation protocol](../human-writing-workflow/references/evaluation.md).
4. Record material preservation failures separately from style preferences. An assessment is allowed to recommend no change.

For a candidate trial, run the accepted baseline and the challenger on the same cases under comparable conditions. Use neutral labels for review when practical. A passing fixture set supports only the tested genres and conditions; it does not establish that a method will always preserve meaning or outperform every alternative.

Do not add real documents or detector screenshots as fixtures. Additional tests should target a demonstrated failure mode and use original synthetic material. Evaluation outputs and local review logs belong outside the public file set unless separately reviewed for publication.
