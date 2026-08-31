# MASTER PROMPT 2
## Final RunPod Results → Verification → Statistics → 2 Figures + 2 Tables → Final Short Communication

The FINAL frozen experiment has now been completed.

This project was developed using MASTER PROMPT 1.

I am providing, as applicable:

- current pre-results manuscript
- GitHub repository/source code
- raw RunPod outputs
- experiment logs
- raw per-run/per-scenario results
- generated summary files
- generated plots
- supplementary outputs.

The methodology was frozen BEFORE observing these final results.

Do NOT alter:

- algorithm
- architecture
- objective
- hyperparameters
- final dataset/scenarios
- baseline definitions
- metric definitions
- selected seeds

merely to obtain more favorable results.

Act simultaneously as my:

- senior research scientist
- statistical analyst
- Short Communication editor
- methodological reviewer
- scientific-visualization specialist
- reproducibility auditor
- skeptical Reviewer #2.

============================================================
ABSOLUTE MANUSCRIPT LIMIT
============================================================

MAIN PAPER:

MAXIMUM FIGURES = 2
MAXIMUM TABLES = 2

Do not exceed this unless the target journal has a stricter
requirement or I explicitly approve a justified exception.

Compress the strongest scientific evidence into these four objects.

============================================================
STEP 1 — VERIFY FINAL EXPERIMENT OUTPUTS
============================================================

Before manuscript editing, inspect all provided final outputs.

Determine:

- whether every expected experiment completed
- exact sample/scenario count
- exact number of runs/seeds
- missing runs
- failed runs
- duplicated runs
- NaNs
- infinities
- corrupted output
- incomplete baselines
- unexpected configuration differences
- runtime/hardware metadata
- whether execution matches the frozen protocol.

Create a concise PASS/FAIL verification report.

If critical evidence is missing:

STOP.

Tell me exactly what must be rerun.

Never infer or invent missing outputs.

============================================================
STEP 2 — RECOMPUTE / VERIFY ALL IMPORTANT METRICS
============================================================

Use raw results whenever possible.

Verify:

- means
- medians
- standard deviations
- confidence intervals
- success rates
- percentages
- percentage improvements
- errors
- risk scores
- objective values
- resource/energy measures
- runtime
- ranking.

Confirm whether every metric is:

HIGHER IS BETTER

or

LOWER IS BETTER.

Do not blindly trust precomputed summary files.

============================================================
STEP 3 — PERFORM APPROPRIATE STATISTICAL ANALYSIS
============================================================

Select statistical methods appropriate to the actual experimental
design rather than mechanically using one test.

Where relevant evaluate:

- paired versus unpaired design
- parametric assumptions
- paired t-test
- Wilcoxon signed-rank
- Friedman test
- post-hoc comparisons
- Holm correction
- Bonferroni correction
- FDR correction
- effect size
- bootstrap confidence intervals.

Report separately:

STATISTICAL SIGNIFICANCE

and

PRACTICAL SIGNIFICANCE.

Do not rely on p-values alone.

============================================================
STEP 4 — HYPOTHESIS VERDICT
============================================================

For every hypothesis locked under MASTER PROMPT 1 classify:

SUPPORTED

PARTIALLY SUPPORTED

NOT SUPPORTED

INCONCLUSIVE.

For each classification give the exact experimental evidence.

Do not rewrite hypotheses after seeing the outcomes.

============================================================
STEP 5 — DETERMINE THE REAL SCIENTIFIC STORY
============================================================

Identify what the final experiment actually discovered.

Explicitly identify:

- strongest wins
- ties
- losses
- trade-offs
- unexpected findings
- boundary conditions
- failure scenarios.

Do not force the proposed model to appear best everywhere.

A valid scientific finding may be:

better safety
but higher runtime

or:

better tail-risk
but comparable mean performance

or:

better accuracy
but poorer computational efficiency.

Use the evidence to determine the manuscript story.

============================================================
STEP 6 — VERIFY NOVEL COMPONENTS THROUGH ABLATION
============================================================

For each claimed innovative component determine:

- outcome when removed
- absolute performance change
- relative performance change
- statistical reliability
- practical significance
- interaction with other components
- computational cost.

Classify every component:

CORE CONTRIBUTION

SUPPORTING CONTRIBUTION

MINOR ENGINEERING COMPONENT

NOT SUPPORTED.

Remove or weaken unsupported novelty claims.

============================================================
STEP 7 — FAILURE / STRESS ANALYSIS
============================================================

Analyze:

- worst cases
- unsuccessful runs
- strongest baseline wins
- extreme runtimes
- unstable cases
- safety failures
- constraint failures
- sensitivity extremes.

Determine the dominant failure mechanism.

Classify whether the limitation is caused by:

- fundamental methodology
- modeling assumptions
- dataset/scenario assumptions
- computational limitations
- implementation
- experimental design.

Use this evidence in the final Limitations section.

============================================================
STEP 8 — BUILD EXACTLY TWO MAIN TABLES
============================================================

Create exactly TWO main-paper tables.

TABLE 1:

PRIMARY PERFORMANCE COMPARISON

Include:

- proposed method
- strongest relevant baselines
- most decision-relevant metrics
- appropriate uncertainty notation
- concise statistical markers when helpful.

Do not create excessive columns.

TABLE 2:

SUPPORTING EVIDENCE

Combine scientifically appropriate:

- ablation
- effect sizes
- statistical tests
- robustness
- sensitivity
- stress-test findings.

Do not create additional main-paper tables.

Secondary evidence can remain in:

- supplementary material
- GitHub
- reproducibility outputs

when appropriate.

============================================================
STEP 9 — BUILD EXACTLY TWO MAIN FIGURES
============================================================

FIGURE 1:

Methodology / architecture figure.

Verify that it exactly represents the FINAL implemented method.

Correct any mismatch between:

- architecture
- equations
- pseudocode
- implementation.

FIGURE 2:

ONE information-dense experimental figure.

Use scientifically appropriate panels if useful, such as:

(a) main comparison
(b) ablation
(c) robustness/sensitivity
(d) representative/failure result

but include only panels necessary to justify the paper.

No decorative graphics.

Every numerical plot must be generated from verified final data.

============================================================
STEP 10 — DETERMINE WHETHER CODE CHANGES ARE PERMITTED
============================================================

Separate discovered changes into:

CATEGORY A — ALLOWED WITHOUT REPEATING FINAL EXPERIMENT

Examples:

- plotting bug fix
- label correction
- README improvement
- comments
- documentation
- output parsing
- manuscript formatting
- table formatting.

CATEGORY B — REQUIRES NEW EXPERIMENT

Examples:

- algorithm change
- architecture change
- objective-function change
- parameter tuning
- baseline modification
- changed final dataset
- changed seed selection
- changed metric definition
- changed experimental protocol.

If a Category B scientific problem is discovered, tell me clearly:

"These final results cannot support the current manuscript without
rerunning the affected experiment."

Never silently change frozen methodology.

============================================================
STEP 11 — FINALIZE THE ABSTRACT
============================================================

Rewrite the Abstract using REAL final findings.

Include concisely:

- problem
- gap
- proposed method
- evaluation setup
- strongest observed numerical result(s)
- important trade-off if relevant
- conclusion.

Do not overload the Short Communication abstract with many numbers.

============================================================
STEP 12 — FINALIZE INTRODUCTION AND CONTRIBUTIONS
============================================================

Edit the Introduction so every contribution statement is supported
by final evidence.

Remove:

- exaggerated novelty
- unsupported superiority
- unsupported generalization.

Prefer approximately 2–4 concise contribution statements.

============================================================
STEP 13 — FORENSIC METHOD ↔ CODE CHECK
============================================================

Cross-check manuscript Methodology against final executable code.

Verify:

- equations
- notation
- algorithm steps
- parameter values
- seeds
- datasets/scenarios
- baselines
- constraints
- metrics
- runtime protocol.

No important manuscript method should exist only on paper.

No important implemented component should be missing from the
manuscript.

============================================================
STEP 14 — WRITE FINAL RESULTS
============================================================

Write Results from verified outputs using:

OBSERVATION
→ QUANTITATIVE EVIDENCE
→ STATISTICAL EVIDENCE
→ INTERPRETATION.

Do not duplicate every table value in prose.

Highlight only findings central to the research question.

============================================================
STEP 15 — WRITE FINAL DISCUSSION
============================================================

Explain:

- why results behaved as observed
- what mechanism generated improvements
- which component mattered most
- why trade-offs occurred
- where baselines were stronger
- practical/scientific meaning
- generalizability boundaries.

Do not merely repeat Results.

============================================================
STEP 16 — WRITE HONEST LIMITATIONS
============================================================

Use actual evidence to discuss limitations involving:

- simulation realism
- dataset limitations
- assumptions
- scalability
- computational demand
- generalization
- statistical uncertainty
- stress-test failures
- hardware restrictions
- deployment limitations.

Do not hide known weaknesses.

============================================================
STEP 17 — REWRITE FINAL CONCLUSION
============================================================

The Conclusion should answer:

What was proposed?

What was experimentally demonstrated?

What was NOT demonstrated?

What is the primary implication?

What is the logical next research step?

Do not introduce new findings.

============================================================
STEP 18 — FORENSIC NUMERICAL CONSISTENCY AUDIT
============================================================

Cross-check EVERY:

- number
- percentage
- sample count
- scenario count
- seed count
- equation
- symbol
- parameter
- metric
- table entry
- figure value
- p-value
- effect size
- confidence interval
- runtime
- baseline name
- dataset/scenario description.

Verify:

ABSTRACT ↔ RESULTS

INTRODUCTION ↔ RESULTS

METHOD ↔ CODE

EQUATIONS ↔ CODE

TABLES ↔ RAW OUTPUTS

FIGURES ↔ RAW OUTPUTS

DISCUSSION ↔ EVIDENCE

CONCLUSION ↔ EVIDENCE

SUPPLEMENT ↔ MAIN MANUSCRIPT.

Create a discrepancy table:

Location
Current statement
Verified source
Problem
Severity
Required correction.

Fix verified editorial inconsistencies.

Do not silently hide scientific contradictions.

============================================================
STEP 19 — REVIEWER #2 ATTACK
============================================================

Review the completed Short Communication as if attempting to reject it.

Evaluate:

- novelty
- technical correctness
- mathematical correctness
- experimental rigor
- baseline fairness
- statistical rigor
- ablation quality
- robustness
- reproducibility
- writing clarity
- figure sufficiency
- table sufficiency
- limitations
- claim accuracy.

Classify issues:

CRITICAL
MAJOR
MINOR.

Fix all scientifically legitimate issues that can be corrected without
manipulating final experimental evidence.

If a problem genuinely requires another experiment, explicitly
say so.

============================================================
STEP 20 — JOURNAL-SPECIFIC FINAL EDIT
============================================================

If a target journal is specified, verify CURRENT official author
requirements.

Adapt as applicable:

- article type
- word/page length
- abstract limit
- keywords
- section structure
- reference style
- figure specifications
- table specifications
- declarations
- data/code availability
- supplementary requirements.

Never invent journal rules.

============================================================
FINAL OUTPUT
============================================================

Provide:

1. FINAL TITLE

2. FINAL ABSTRACT

3. FINAL KEYWORDS

4. FINAL SHORT COMMUNICATION

5. EXACT FIGURE 1 specification and caption

6. EXACT FIGURE 2 specification and caption

7. EXACT TABLE 1

8. EXACT TABLE 2

9. FINAL LIMITATIONS

10. FINAL CONCLUSION

11. SUPPLEMENTARY-MATERIAL recommendations only if genuinely needed

12. FINAL CODE AVAILABILITY statement

13. FINAL DATA AVAILABILITY statement

14. REVIEWER-AUDIT SUMMARY

15. FINAL VERDICT:

NOT READY

NEEDS ANOTHER EXPERIMENT

MINOR EDITING ONLY

SUBMISSION READY.

============================================================
MOST IMPORTANT RULE
============================================================

The final manuscript must report what the frozen experiment
actually discovered.

Never change what the experiment discovered merely to match what
the pre-results manuscript expected.
