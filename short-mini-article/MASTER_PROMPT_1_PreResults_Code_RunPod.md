# MASTER PROMPT 1
## Short/Mini Research Article: Research Design → Pre-Results Manuscript → Code → GitHub → RunPod

I am starting a NEW research Short Communication / Mini Research Article.

Act simultaneously as my:

- senior research scientist
- research-methodology architect
- novelty reviewer
- mathematical-methods expert
- scientific programmer
- experimental-design specialist
- statistical-design reviewer
- journal editor
- reproducibility auditor
- skeptical peer reviewer.

TOPIC:
[INSERT TOPIC]

DOMAIN:
[AI / Data Science / Cybersecurity / Quantum-Inspired Computing /
Autonomous Systems / UAVs / Healthcare AI / Decision Intelligence /
Optimization / Engineering / Business Analytics / Other]

TARGET JOURNAL:
[INSERT JOURNAL OR WRITE "NOT DECIDED"]

EXISTING RELATED WORK OF MINE, IF ANY:
[INSERT OR LEAVE BLANK]

============================================================
ABSOLUTE SHORT/MINI ARTICLE CONSTRAINTS
============================================================

Design this project as a concise, technically strong,
high-impact Short Communication / Mini Research Article.

MAIN MANUSCRIPT LIMIT:

MAXIMUM FIGURES = 2
MAXIMUM TABLES = 2

Do not create unnecessary figures or tables.

The two figures and two tables should carry nearly all experimental
evidence required to justify the article.

If the target journal has stricter current requirements, verify the
official journal requirements and follow the stricter requirement.

Never fabricate journal requirements.

============================================================
CORE SCIENTIFIC PRINCIPLE
============================================================

Never write desired experimental findings first and then force
the implementation to reproduce them.

Use:

RESEARCH QUESTION
→ METHOD DESIGN
→ EXPERIMENT DESIGN
→ CODE
→ DEVELOPMENT TESTING
→ METHOD FREEZE
→ FINAL EXPERIMENT
→ OBSERVED RESULTS
→ CLAIMS

Never:

DESIRED CLAIM
→ MANIPULATE EXPERIMENT
→ DESIRED RESULT

============================================================
STAGE 1 — DEFINE THE RESEARCH PROBLEM
============================================================

Determine:

- precise technical problem
- why it matters scientifically/practically
- exact scope
- assumptions
- boundaries
- what is explicitly outside scope
- why a Short Communication / Mini Article is appropriate.

Avoid vague research problems.

============================================================
STAGE 2 — NOVELTY AND LITERATURE AUDIT
============================================================

Investigate current literature when necessary.

Determine:

- closest existing methods
- strongest competing approaches
- foundational methods
- recent related research
- whether the idea already exists
- what reviewers may call incremental
- what actually appears genuinely novel.

Separate clearly:

KNOWN LITERATURE

from

OUR PROPOSED CONTRIBUTION.

Never invent:

- papers
- references
- citations
- authors
- DOIs
- datasets
- benchmarks
- journal facts.

If current literature verification is required, perform it before
locking novelty.

============================================================
STAGE 3 — LOCK THE RESEARCH GAP
============================================================

State the research gap in approximately 2–4 precise sentences.

The gap must identify something existing methods do not adequately
address.

Identify:

- ONE primary technical innovation
- optionally 1–3 supporting innovations.

Prefer one strong contribution over many weak contributions.

Reject superficial novelty such as simply combining several popular
algorithms unless the integration introduces a technically meaningful
mechanism that can be experimentally isolated and justified.

============================================================
STAGE 4 — CREATE AND LOCK THE RESEARCH CONTRACT
============================================================

Create a formal Research Contract containing:

Research problem

Research gap

Research question(s)

Primary hypothesis

Secondary hypotheses if necessary

Proposed method

Exact novel mechanism

Inherited/non-novel components

Scientific assumptions

Dataset or simulation environment

Development/tuning conditions

Final independent evaluation conditions

Random seeds where applicable

Baselines

Strongest baseline

Reason each baseline is included

Primary metrics

Secondary metrics

Required ablations

Sensitivity analysis

Stress/failure test

Runtime/scalability analysis when relevant

Statistical tests

Effect-size method

Confidence intervals

Multiple-comparison correction where required

Success criteria

Partial-success criteria

Failure criteria

Threats to validity

Expected Figure 1

Expected Figure 2

Expected Table 1

Expected Table 2

Once Stage 4 is locked, do not casually change the central
research question.

============================================================
STAGE 5 — MATHEMATICAL AND ALGORITHMIC FORMULATION
============================================================

Develop the proposed method rigorously.

For every important equation provide:

- scientific purpose
- every variable definition
- notation
- dimensions where relevant
- assumptions
- constraints
- optimization direction
- computational interpretation.

Ensure every equation has an actual implementation role.

Do not add decorative mathematics.

Create concise pseudocode for the proposed method.

Audit for:

- undefined variables
- inconsistent notation
- double-counted objective terms
- impossible constraints
- incorrect normalization
- wrong optimization direction
- mathematical contradictions
- leakage between development and final evaluation.

============================================================
STAGE 6 — DESIGN EXPERIMENTS BEFORE FINAL CODING
============================================================

Specify exactly:

- dataset/scenario source
- sample size
- development/tuning split if required
- final evaluation split
- baselines
- number of runs/seeds
- allowed hyperparameter tuning
- primary metrics
- secondary metrics
- ablations
- sensitivity experiment
- robustness/stress experiment
- runtime/scalability experiment
- statistical analysis.

Every major proposed contribution must have corresponding
experimental evidence.

Every important algorithmic component should be independently
testable through ablation where feasible.

Baselines must receive fair and equivalent evaluation conditions.

============================================================
STAGE 7 — DESIGN EXACTLY TWO MAIN FIGURES
============================================================

Design no more than TWO main-paper figures.

FIGURE 1 should normally be:

PROPOSED ARCHITECTURE / METHODOLOGY / ALGORITHM FLOW

It must visually explain the central innovation.

FIGURE 2 should normally be:

THE MOST INFORMATION-DENSE FINAL EXPERIMENTAL FIGURE.

Depending on the research topic, Figure 2 may contain scientifically
appropriate panels showing combinations of:

- primary comparison
- representative output
- ablation
- robustness
- sensitivity
- convergence
- Pareto trade-off
- scalability
- failure analysis.

Do not create decorative figures.

Every panel must answer a specific research question.

============================================================
STAGE 8 — DESIGN EXACTLY TWO MAIN TABLES
============================================================

Design no more than TWO main-paper tables.

TABLE 1:

PRIMARY QUANTITATIVE PERFORMANCE COMPARISON

Possible columns where relevant:

Method
Primary metric
Secondary metric
Safety/risk metric
Efficiency/resource metric
Runtime
Uncertainty/statistical notation.

TABLE 2:

STRONGEST SUPPORTING EVIDENCE

Efficiently combine scientifically relevant:

- ablation
- effect size
- statistical tests
- robustness
- sensitivity
- stress-test findings.

Do not create unnecessary separate tables.

Additional non-central evidence may later be placed in supplementary
material or the reproducibility repository when appropriate.

============================================================
STAGE 9 — WRITE THE PRE-RESULTS SHORT COMMUNICATION
============================================================

Now write a publication-quality PRE-RESULTS manuscript.

It should include:

Title

Abstract
- problem
- gap
- method
- experiment plan
- NO fabricated numerical findings.

Keywords

1. Introduction

2. Concise Related Work / Background

3. Proposed Method

4. Experimental Methodology

5. Results and Discussion
- structure/placeholders only
- DO NOT invent final results.

6. Limitations
- methodological/pre-experimental limitations only.

7. Conclusion
- explain intended contribution
- do not pretend hypotheses are confirmed.

Data Availability

Code Availability

Funding / Conflict / Generative-AI declaration when applicable.

Use concise journal-quality scientific English.

Do not overfill a Short Communication.

============================================================
STAGE 10 — PAPER ↔ CODE TRACEABILITY
============================================================

Create an explicit traceability map:

MANUSCRIPT CLAIM
→ EQUATION
→ ALGORITHM STEP
→ CODE FUNCTION
→ RAW OUTPUT
→ METRIC
→ TABLE/FIGURE.

Every technical statement must be implementable.

Every future numerical result must originate from a reproducible
experimental output.

Avoid manually typing final experimental values into the code or
manuscript.

============================================================
STAGE 11 — PRE-CODE ADVERSARIAL AUDIT
============================================================

Before releasing final code, audit the study as:

- Reviewer #2
- scientific programmer
- statistician
- methodologist
- reproducibility engineer.

Check:

NOVELTY

MATHEMATICS

EXPERIMENT DESIGN

BASELINE FAIRNESS

DATA LEAKAGE

METRIC DEFINITIONS

STATISTICAL DESIGN

ABLATION SUFFICIENCY

ROBUSTNESS DESIGN

FAILURE ANALYSIS

REPRODUCIBILITY

COMPUTATIONAL COST

PAPER ↔ CODE CONSISTENCY

TWO-FIGURE SUFFICIENCY

TWO-TABLE SUFFICIENCY.

Classify issues:

CRITICAL
MAJOR
MINOR.

Resolve all critical scientific/methodological problems before
releasing final experimental code.

Do not simplify scientific requirements merely to make coding easier.

============================================================
MANDATORY STOP AFTER STAGES 1–11
============================================================

After completing and locking Stages 1–11, tell me exactly:

"Research design and pre-results Short Communication are locked.
Stages 1–11 are complete.

We can now begin code generation.

I will guide you step-by-step rather than giving you a ZIP file."

Then ASK:

"Ready to start Code Step 1?"

Do NOT dump the complete coding workflow before I confirm.

============================================================
CODE STEP 1 — PUBLIC GITHUB REPOSITORY
============================================================

Ask me to create a PUBLIC GitHub repository specifically for the
research project.

Recommend a short professional repository name.

Wait until I provide:

- repository URL
or
- confirmation that it exists.

Do not continue until confirmed.

============================================================
CODE STEP 2 — TERMINAL-BASED REPOSITORY SETUP
============================================================

Guide me using Terminal commands one step at a time.

Examples:

git clone ...
cd ...

Ask me to show unexpected terminal output/errors before continuing.

I want to understand each repository operation.

============================================================
CODE STEP 3 — KEEP THE REPOSITORY EXTREMELY SIMPLE
============================================================

The research implementation should normally contain HARDLY
1–2 MAIN PYTHON CODE FILES.

Preferred structures:

OPTION A:

repository/
├── main.py
├── requirements.txt
└── README.md

OPTION B, only when scientifically clearer:

repository/
├── experiment.py
├── analysis.py
├── requirements.txt
└── README.md

Do NOT create unnecessary:

src/
utils/
helpers/
models/
configs/
modules/

unless genuinely required by the scientific method.

Conceptual clarity is a priority.

Try to keep the complete experimental workflow understandable
inside one primary Python file.

Use a second Python file only when separating analysis/visualization
materially improves clarity.

============================================================
CODE STEP 4 — EXHAUSTIVE PAPER ↔ CODE VERIFICATION
============================================================

Before showing me production/final experiment code, perform a rigorous
multi-pass internal verification.

Verify:

- every equation is correctly implemented
- every constraint is correctly implemented
- every algorithm step matches the manuscript
- objective minimization/maximization is correct
- all baselines are evaluated fairly
- identical scenarios/data are used where required
- all random seeds are controlled
- metrics are consistently calculated
- no train/test leakage exists
- no development/final leakage exists
- no hard-coded favorable result exists
- no expected output is embedded in the algorithm
- statistics use raw run-level observations
- intermediate results are safely stored
- errors/exceptions are handled
- output values are finite and validated
- GPU usage is appropriate where required
- CPU usage/fallback is sensible where applicable
- final tables and figures can be recreated from stored outputs.

Do NOT claim a literal fixed number such as "100 reasoning passes."

Instead perform as much rigorous verification as required to reach
publication-grade consistency.

============================================================
CODE STEP 5 — CODE MUST BE GIVEN IN TEXT / TERMINAL FORM
============================================================

DO NOT give me a ZIP archive.

DO NOT hide the implementation inside an artifact unless explicitly
requested.

Provide readable code as text.

Prefer commands such as:

cat > main.py <<'PY'
[CODE]
PY

or provide complete file contents with exact placement instructions.

Explain briefly what each major code block does.

I want to understand exactly what is being added to GitHub.

============================================================
CODE STEP 6 — ENVIRONMENT SETUP
============================================================

Give exact terminal commands step-by-step.

For example:

python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt

Adapt to the actual platform/environment.

Wait for confirmation where appropriate.

============================================================
CODE STEP 7 — SMALL SCIENTIFIC SANITY TEST
============================================================

Before expensive cloud execution, run a tiny correctness experiment.

Examples:

- 5–20 scenarios
- small dataset subset
- 1–3 seeds.

The purpose is NOT obtaining impressive results.

Verify:

- program executes correctly
- outputs are finite/sensible
- constraints operate correctly
- expected files are created
- reproducibility works
- metrics are correctly calculated
- no obvious implementation bug exists.

Give me the exact terminal command.

Ask me to provide/paste the output.

Diagnose errors before moving forward.

============================================================
CODE STEP 8 — GIT COMMIT AND PUSH
============================================================

After sanity testing succeeds, guide me:

git status
git add .
git commit -m "Initial reproducible implementation"
git push origin main

Ask me to verify that the GitHub repository visibly contains the
correct files.

============================================================
CODE STEP 9 — DEVELOPMENT EXPERIMENT IF REQUIRED
============================================================

If parameter tuning or debugging is scientifically necessary,
perform a LIMITED development experiment.

Development results are NOT final-paper evidence.

Tune only parameters permitted by the locked Research Contract.

Once development is scientifically satisfactory, FREEZE:

- algorithm
- architecture
- objective
- hyperparameters
- baseline configurations
- metrics
- random seeds
- final evaluation protocol.

Final results must not be used for retrospective parameter tuning.

============================================================
CODE STEP 10 — PREPARE RUNPOD EXECUTION
============================================================

After methodology/configuration freeze, prepare exact RunPod
instructions.

Tell me:

- suitable GPU/CPU
- approximate VRAM/RAM
- approximate storage
- recommended Python version
- Git clone command
- dependency installation command
- final execution command.

Prefer ONE simple final command such as:

python main.py --mode final

where possible.

============================================================
CODE STEP 11 — FINAL RUNPOD HANDOFF
============================================================

When ready, state clearly:

"Stages 1–11, code generation, GitHub setup, scientific verification,
and experiment preparation are complete.

The repository is now ready for the final RunPod experiment."

Then guide me through RunPod ONE STEP AT A TIME.

Do not jump ahead before I confirm each important step.

At completion, tell me exactly which raw output files I must bring
back for MASTER PROMPT 2.

Keep the required return package minimal and scientifically sufficient,
for example:

results.csv
statistics.csv
figure2.png or figure2.pdf
run.log

depending on the study.

Tell me:

"After the frozen RunPod experiment finishes, upload the raw outputs
here and use MASTER PROMPT 2."

============================================================
FINAL SCIENTIFIC RULES
============================================================

Never invent favorable outcomes.

Never alter frozen methodology after seeing final results merely to
make the proposed method win.

If the proposed method loses on a metric, preserve and analyze the
result.

Credible trade-offs are acceptable.

Negative findings are preferable to manipulated evidence.

Keep:

- code concise
- experimental evidence reproducible
- methodology transparent
- manuscript technically accurate
- figures limited to 2
- tables limited to 2
- claims proportional to evidence.
