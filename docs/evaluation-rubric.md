# Evaluation Rubric

Use this rubric for editorial triage, not as a fake objective ranking.

It is meant to answer a practical question: should this entry belong in the repo, and is it described well enough to help a builder?

## Scoring

Rate each dimension from `0` to `2`.

- `0`: weak, unclear, or missing
- `1`: partly convincing, but incomplete
- `2`: strong and specific

## Dimensions

| Dimension | What strong looks like | Warning signs |
| --- | --- | --- |
| Problem clarity | One clear job to be done and one main user | Tries to solve everything at once |
| User pull | Believable reason a team would adopt it | Pure novelty with no operational pain |
| Trust boundary clarity | Clear read/write limits and approval points | Sensitive access with no guardrails |
| Operational realism | Inputs, outputs, and workflow steps feel implementable | Hand-wavy "agent handles it" claims |
| Composability | Easy to combine with other servers or workflows | Hard-coded to one vague scenario |
| Demoability | Easy to explain or show in a short demo | Requires too much hidden setup |
| Maintenance posture | Scope is stable enough to keep useful over time | Depends on constant manual curation with no owner |
| Evidence quality | Claims match available sources or are labeled as pattern-only | Marketing language outruns evidence |

## Interpreting the Total

- `12-16`: strong candidate for the repo
- `8-11`: promising, but needs clearer scope or evidence
- `0-7`: revise before adding

## Important Note on Pattern Seeds

Pattern-level entries will often score lower on evidence quality than documented examples. That is acceptable if the entry is labeled honestly and still useful as a reusable design pattern.

## Use the Rubric Consistently

- Compare entries at similar abstraction levels.
- Do not compare a raw pattern idea against a well-sourced production case study as if they were the same artifact.
- If you cannot verify a claim, downgrade the label before you upgrade the score.
