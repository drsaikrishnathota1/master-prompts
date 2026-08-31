# MASTER PROMPT 2
## Final Results → Verification → Statistics → Up to 2 Figures + Up to 2 Tables → Final Short Communication

The FINAL frozen evidence package has now been completed.

This project was developed using MASTER PROMPT 1.

Depending on the research type, the final evidence may consist of:

- computational experiments
- simulations
- statistical analyses
- mathematical proofs
- theorem verification
- benchmark results
- engineering measurements
- validated empirical evidence
- or another evidence form defined and locked by MASTER PROMPT 1.

Do not force computational-experiment language onto a study whose
research type does not require it.

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

Compress the strongest scientific evidence into no more than these
four objects.

Use fewer when scientifically sufficient.

============================================================
FINAL REFERENCE POLICY
============================================================

The final manuscript must continue to obey the MASTER PROMPT 1
reference policy:

- use 2024–present as the default state-of-the-art / novelty window
- allow older foundational references when scientifically necessary
- classify older references explicitly by foundational role
- prioritize authoritative, directly relevant peer-reviewed literature
- prefer IEEE, Elsevier/ScienceDirect, and MDPI for applicable
  technical topics
- allow other top scholarly publishers when they contain stronger,
  indispensable, or domain-specific prior work
- never exclude the closest prior work because of publisher preference
- no fabricated or unverifiable references
- every citation must support the exact manuscript claim.

Because final findings may change the scientific story, the literature
and citation mapping MUST be revalidated after the RunPod results are
known.

Do not assume the pre-results reference set remains sufficient.

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
- whether execution matches the frozen protocol
- total RunPod wall-clock runtime
- GPU/CPU actually used
- peak memory/VRAM where available
- whether the final execution stayed within the locked two-hour budget
- whether any planned experiment was skipped because of compute limits
- whether early termination affected scientific completeness
- Git commit SHA from the final freeze fingerprint
- code/configuration version
- dataset/split fingerprint
- frozen random seeds
- baseline versions
- primary metric
- Python/package environment
- whether the returned outputs correspond to the exact frozen
  experiment fingerprint.

Create a concise PASS/FAIL verification report.

Never silently discard failed runs.

Explicitly report:

- number attempted
- number completed
- number failed
- failure reasons
- whether failure rate differs by method
- whether exclusions could bias the comparison.

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

If the final findings materially change the scientific positioning,
revise the TITLE, ABSTRACT, CONTRIBUTION STATEMENTS, and DISCUSSION so
that they describe the observed evidence rather than the original
expectation.

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
STEP 7A — FINAL REFERENCE REVALIDATION
============================================================

Now repeat targeted literature searching using the FINAL observed
findings.

Search specifically for recent 2024–present permitted literature
related to:

- the actual strongest result
- unexpected findings
- trade-offs
- failure modes
- the strongest baseline
- any mechanism used to explain the results
- any final claim that was not anticipated in the pre-results paper.

For every retained or newly added reference reverify:

- title
- authors
- year
- journal
- article number/pages
- DOI
- allowed publisher ecosystem
- exact relevance
- exact claim supported.

Build a FINAL CLAIM ↔ CITATION MATRIX:

Manuscript Claim
| Citation
| Source Type
| Exact Evidence Supported
| Verification Status.

Remove:

- irrelevant references
- redundant references
- citations no longer aligned with the final story
- unverifiable references
- unjustifiably out-of-window references
- unverifiable or low-quality sources
- sources that are materially weaker than an available primary
  peer-reviewed source.

Then repeat the five citation-verification passes from MASTER PROMPT 1.

The final Reference Integrity Gate must again score:

100 / 100

before the manuscript can receive SUBMISSION READY status.

This internal matrix does not count against the two-table limit.

============================================================
STEP 8 — BUILD UP TO TWO MAIN TABLES
============================================================

Use no more than TWO main-paper tables. Use only ONE when one is scientifically sufficient.

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
STEP 9 — BUILD UP TO TWO MAIN FIGURES
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
FINAL FIGURE + TABLE QUALITY GATE
============================================================

Before accepting the final 1–2 figures and 1–2 tables verify:

FIGURES:

- all quantitative values originate from verified outputs
- axes and units are correct
- uncertainty is shown where applicable
- panel labels are consistent
- fonts remain readable at publication size
- no misleading axis manipulation
- architecture exactly matches implemented code
- captions are self-contained.

TABLES:

- numeric precision is consistent
- units are explicit
- uncertainty notation is defined
- n is shown where appropriate
- statistical markers are explained
- highlighting follows a pre-defined rule
- no favorable-value cherry-picking
- no unnecessary duplication with figures.

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
- formatting-only output parsing that cannot alter numeric values,
  exclusions, aggregation, or statistical conclusions
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
- changed experimental protocol
- any parsing/aggregation correction that changes numeric values,
  excluded observations, run inclusion, metric aggregation, rankings,
  p-values, effect sizes, or scientific conclusions.

A post-processing correction that changes the numerical interpretation
requires complete re-analysis of affected outputs and may require
rerunning the experiment if raw evidence is no longer trustworthy.

If a Category B scientific problem is discovered, tell me clearly:

"These final results cannot support the current manuscript without
rerunning the affected experiment."

Never silently change frozen methodology.

============================================================
STEP 10A — FINAL CLAIM-BOUNDARY AUDIT
============================================================

Before rewriting the manuscript, verify that final claims do not exceed
the evidence.

Explicitly prevent:

simulation → deployment claims

synthetic data → real-world validation claims

association → causation claims

one benchmark → universal-superiority claims

statistical significance → practical-significance claims

one dataset → population-generalization claims

quantum-inspired → quantum-speedup claims.

If the pre-results title or contribution wording exceeds the final
evidence:

downgrade or rewrite it.

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
STEP 18 — FORENSIC NUMERICAL + CITATION CONSISTENCY AUDIT
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
- dataset/scenario description
- in-text citation
- bibliography entry
- DOI
- publication year
- journal
- claim-to-citation mapping.

Verify:

ABSTRACT ↔ RESULTS

INTRODUCTION ↔ VERIFIED LITERATURE + RESULTS

RELATED WORK ↔ VERIFIED PUBLISHER SOURCES

METHOD ↔ CODE

EQUATIONS ↔ CODE

TABLES ↔ RAW OUTPUTS

FIGURES ↔ RAW OUTPUTS

DISCUSSION ↔ RESULTS + VERIFIED LITERATURE

CONCLUSION ↔ EVIDENCE

IN-TEXT CITATIONS ↔ BIBLIOGRAPHY

BIBLIOGRAPHY ↔ PUBLISHER METADATA

SUPPLEMENT ↔ MAIN MANUSCRIPT.

Create a discrepancy report:

Location
Current statement/value
Verified source
Problem
Severity
Required correction.

No CRITICAL discrepancy may remain.

No reference may remain unless it passes the final source/year/metadata/
claim-support verification.

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
STEP 20 — JOURNAL-SPECIFIC FINAL EDIT + REFERENCE LOCK
============================================================

If a target journal is specified, verify CURRENT official author
instructions using the journal/publisher's official guidance.

When useful, inspect approximately 3–5 recent papers from the SAME or
closest article type in that journal to understand:

- manuscript density
- section conventions
- typical technical depth
- figure/table density
- Results/Discussion style
- expected validation strength.

Do NOT copy their wording, structure mechanically, or citations.

Official author instructions override observed conventions.

Adapt:

- article type
- word/page limits
- abstract limit
- keywords
- section structure
- reference style
- citation style
- figure requirements
- table requirements
- graphical abstract/highlights if applicable
- declarations
- data/code availability
- supplementary-material requirements.

Never invent journal rules.

After formatting, perform one LAST reference lock:

1. the reference set follows the project's verified date-window policy
2. all references are authoritative and appropriate to the domain
3. every DOI/metadata item is verified
4. every in-text citation appears in bibliography
5. every bibliography entry is cited
6. every citation supports the associated claim
7. citation order/style follows the target journal
8. 100-point Reference Integrity Gate remains 100/100.

If formatting changes break citation numbering or mapping, repair them
before submission.

============================================================
FINAL OUTPUT
============================================================

Provide:

1. FINAL TITLE

2. FINAL ABSTRACT

3. FINAL KEYWORDS

4. FINAL SHORT COMMUNICATION

5. FINAL FIGURE SET
   - provide Figure 1 only if scientifically justified
   - provide Figure 2 only if scientifically justified
   - maximum = 2 figures
   - never create filler merely to reach two.

6. FINAL TABLE SET
   - provide Table 1 only if scientifically justified
   - provide Table 2 only if scientifically justified
   - maximum = 2 tables
   - never create filler merely to reach two.

7. FINAL LIMITATIONS

8. FINAL CONCLUSION

9. VERIFIED REFERENCE LIST — current state-of-the-art + justified foundational sources

10. REFERENCE INTEGRITY SUMMARY
    - five-pass status
    - 100-point score
    - confirmation of source-quality compliance.

11. SUPPLEMENTARY-MATERIAL recommendations only when genuinely needed

12. FINAL CODE AVAILABILITY statement, when applicable

13. FINAL DATA AVAILABILITY statement

14. REVIEWER-AUDIT SUMMARY

15. FINAL VERDICT:

NOT READY

NEEDS ANOTHER EXPERIMENT

MINOR EDITING ONLY

SUBMISSION READY.

SUBMISSION READY is forbidden unless:

- the frozen experiment is valid
- all central hypotheses have honest verdicts
- statistics are correct
- code and manuscript agree
- no critical reviewer issue remains
- maximum 2 figures / 2 tables is satisfied
- final Reference Integrity Gate = 100/100.

============================================================
MOST IMPORTANT RULE
============================================================

The final paper must describe what the frozen experiment ACTUALLY
discovered.

The literature must describe what the VERIFIED sources ACTUALLY
reported.

Never alter experimental evidence to match the original expectation.

Never alter or misattribute a citation to make a novelty argument
appear stronger.

FINAL PRINCIPLE:

VERIFIED LITERATURE
→ DEFENSIBLE GAP
→ LOCKED METHOD
→ REPRODUCIBLE CODE
→ FROZEN EXPERIMENT
→ VERIFIED FINDINGS
→ ACCURATE CLAIMS
→ SUBMISSION.
