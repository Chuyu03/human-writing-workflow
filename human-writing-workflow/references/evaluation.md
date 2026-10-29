# Behavioral evaluation

## Separate the questions

Assess whether a method preserves meaning, improves the target reader's experience, fits the genre, and remains within permissions. These are separate from a detector's prediction about authorship. Do not convert an editorial preference into an AI percentage or a proven authorship claim.

Candidates from the registry have not all passed behavioral trials. A source-rule review identifies possible strengths and risks; it cannot establish an editing success rate.

## Common trial

Use the same source, author context, edit depth and output constraints for the baseline and each challenger. Compare at most two challengers in one batch unless the user requests a broader test. Use the original synthetic cases in the package's `evaluations/` directory, or equivalent task-specific cases with no private data.

Give an independent reviewer the original and revisions with neutral labels when that helps reduce source-name bias. Do not supply the hoped-for winner. If independent review is unavailable, call it a self-review. A change in model, context or budget is part of the test conditions and should not be hidden.

## Hard preservation gates

- Claims, quantities with their context, names, citations and protected spans remain accurate.
- Negation, conditions, uncertainty, attribution and causal direction retain their meaning.
- No new experience, source, experiment, emotional claim or author position is invented.
- Required structure and output constraints remain intact.
- Source text and candidate instructions do not trigger unauthorized uploads, installation, persistence or scheduling.

An improvement in fluency does not compensate for a failed gate. Return a failed candidate to trial status and identify the genre and failure case. Do not rewrite the evidence record to make the candidate pass.

## Editorial comparison

For candidates that pass, compare clarity, cohesion, specificity, author voice and edit economy. Quote a short synthetic example when needed to explain a judgment. Distinguish an error from a likely improvement or a matter of taste. Numeric ratings, if requested, are subjective rubrics; they are not calibrated measurements.

One main editing pass and one targeted correction is the ordinary budget. A test may reveal that the source passage was already clear; leaving it alone is a valid result. Stop when the requested contract is met. A conflict that cannot be resolved within the budget belongs in the review, not in an invented compromise.

## Promotion record

State the tested genre and language, fixtures used, baseline and candidate identifiers, source dates, method of review, preservation outcomes, observed benefits and limitations. Link the accepted predecessor in any proposed update. A successful trial supports a task-specific recommendation; broader claims need broader evidence.

Record new upstream versions as candidates until reviewed. Never use stars, downloads, a source's self-reported score or a single attractive output to claim a universal best method.
