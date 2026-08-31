# Master Prompts

A curated repository of advanced research and academic master prompts for rigorous, reproducible, publication-oriented research workflows.

The repository currently contains dedicated workflows for:

- IEEE Conference Papers
- Short Communications / Mini Research Articles

---

## 1. IEEE Conference Papers

Directory:

`ieee-conference/`

This directory contains a universal master prompt for developing rigorous IEEE conference papers from a research topic/title and an IEEE conference template.

### Core Design Principles

The IEEE Conference workflow emphasizes:

- concise IEEE paper design
- maximum 2 figures
- maximum 2 tables
- verified references
- research-gap validation
- novelty falsification
- protocol locking
- domain-adaptive research methodology
- reproducible experiments
- citation verification
- data-leakage prevention
- statistical and methodological validation
- IEEE template preservation
- PDF validation
- critical pass/fail quality gates
- final manuscript audit

The framework can be adapted across AI, data science, engineering, cybersecurity, healthcare, optimization, quantum computing, business analytics, autonomous systems, and related research domains.

---

## 2. Short Communications / Mini Research Articles

Directory:

`short-mini-article/`

This directory contains a two-prompt research workflow for developing concise, technically rigorous Short Communications and Mini Research Articles.

### Prompt 1 — Research Design → Code → RunPod

File:

`MASTER_PROMPT_1_PreResults_Code_RunPod.md`

Prompt 1 covers the complete pre-results workflow:

1. Research-problem definition
2. Novelty and literature audit
3. Research-gap locking
4. Research Contract
5. Mathematical and algorithmic formulation
6. Experimental design
7. Two-figure design
8. Two-table design
9. Pre-results manuscript preparation
10. Paper-to-code traceability
11. Pre-code adversarial audit
12. Concise publication-grade code generation
13. Step-by-step GitHub setup
14. Small scientific sanity testing
15. Development testing and methodology freeze
16. Final RunPod preparation and execution

The workflow intentionally keeps research repositories simple, typically using only one or two primary Python files whenever the methodology permits.

Code is designed to be transferred and executed transparently through terminal commands rather than hidden inside ZIP archives.

### Prompt 2 — Final Results → Final Manuscript

File:

`MASTER_PROMPT_2_PostResults_Finalization.md`

Prompt 2 begins only after the frozen final experiment has completed.

It covers:

- raw-output verification
- metric recomputation
- statistical analysis
- hypothesis testing
- ablation verification
- practical-significance analysis
- failure/stress analysis
- final two-table construction
- final two-figure construction
- manuscript rewriting from observed evidence
- method-to-code consistency checking
- limitations
- journal-specific editing
- Reviewer #2 adversarial review
- forensic numerical consistency checking
- final submission-readiness verdict

### Short/Mini Article Main-Manuscript Limits

The default workflow enforces:

- **Maximum 2 figures**
- **Maximum 2 tables**
- concise Short Communication structure
- no fabricated experimental outcomes
- no retrospective tuning using final test results
- reproducible code and experiments
- statistically justified claims
- mandatory 2024–present literature verification
- manuscript references restricted by default to IEEE Xplore,
  Elsevier/ScienceDirect, and MDPI
- publisher-level DOI and bibliographic verification
- claim-to-citation traceability
- five-pass citation validation
- mandatory 100/100 Reference Integrity Gate
- transparent reporting of negative results and trade-offs

The central research principle is:

**Research Question → Method → Experiment → Evidence → Claim**

and never:

**Desired Claim → Manipulated Experiment → Desired Result**

---

## Repository Philosophy

These prompts are designed to help transform a research idea into a technically defensible, reproducible publication workflow.

The methodology may vary by domain, but the scientific principles remain consistent:

- verify novelty before implementation
- define experiments before final coding
- separate development from final evaluation
- freeze methodology before observing final test outcomes
- generate claims from evidence
- preserve negative results and trade-offs
- maintain direct traceability between manuscript equations, code, raw results, tables, and figures
- never fabricate citations, results, datasets, benchmarks, or journal requirements
- verify every Short/Mini Article reference at the publisher level
- prefer recent, directly relevant literature rather than citation padding
- preserve exact traceability from literature claim → citation and
  manuscript claim → code → raw output → table/figure

