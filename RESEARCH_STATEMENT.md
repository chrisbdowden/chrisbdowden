# Research Statement

## Computational Biology Explorer: Challenging Feature Selection Paradigms

I'm building novel methodologies that question conventional approaches to biomarker discovery. My work centers on a fundamental observation: **established feature selection methods (LASSO, ElasticNet, Random Forest) were designed for prediction, not interpretation. Biomarkers require both.**

---

## The Problem

Current biomarker discovery pipelines rely on three problematic assumptions:

### 1. Hyperparameter Tuning is Harmless
**Reality:** Inner-loop hyperparameter optimization leaks information from training data into feature selection, violating information barriers.

**Consequence:** Selected features are brittle, non-generalizable, and performance estimates are optimistically biased.

### 2. Multivariate Black-Box Methods are Superior
**Reality:** LASSO, ElasticNet, and RF importance obscure biological relationships. You get a prediction score, not an interpretation.

**Consequence:** Clinicians can't explain why a patient is high-risk. Researchers can't validate mechanistically.

### 3. One-Size-Fits-All Tuning Across Domains
**Reality:** Different diseases, tissues, and modalities require cohort-specific hyperparameter modifications.

**Consequence:** Methodologies that work on lung cancer don't work on Alzheimer's without retuning. They're not truly generalizable.

---

## My Approach: Biomarker Probability Fusion (BPF)

BPF inverts the conventional paradigm:

1. **Univariate AUC Ranking** — Each feature scored independently against outcome
   - No hyperparameters to tune
   - Fully interpretable (direction + strength of association)
   - Information barrier: feature ranking sees only training labels

2. **Adaptive Selection** — Predefined thresholds (AUC ≥ 0.55, p < 0.05, max panel size)
   - Declared before validation
   - No cohort-specific modifications
   - Transparent decision rules

3. **Weighted Probability Fusion** — AUC-weighted z-score composition with direction correction
   - Deterministic (seed = 42)
   - Interpretable (each feature's contribution weighted by discriminative power)
   - Probabilistic output (confidence-scored risk)

---

## Validation: Disease-Agnostic Generalizability

I've validated BPF on **57 independent datasets across 3 disease domains** without any domain-specific modifications:

### Oncology (Phase 1)
- **39 TCGA cohorts** | 16,958 patients
- Mean AUC: **0.8077** (95% CI: 0.7722–0.8430)
- 21 of 39 cohorts (54%) achieve GOLD tier (AUC ≥ 0.80)
- Benchmark vs. LASSO/ElasticNet/RF: BPF wins 10/15 comparisons

### Alzheimer's Disease (Phase 2)
- **ADNI transcriptomics/genomics/methylation** | 262–1,216 patients
- DNA methylation peak: **AUC 0.948** (100 CpG panel)
- Transcriptomics: **AUC 0.879** (biomarker discovery challenge)
- Multi-omic fusion: **AUC 0.818** (robust across modalities)

### Parkinson's Disease (Phase 3)
- **PPMI prodromal detection** | 365–710 patients
- **Prodromal vs HC: AUC 0.766** — earliest clinical win in PD detection
- 36-gene mitochondrial panel enriched for stress-response pathways
- Permutation p ≤ 0.001 — signal confirmed label-dependent

**All three domains. Same methodology. No retuning. This is generalizability.**

---

## Why This Matters for Medicine

### For Clinicians
- **Interpretable:** You know which biomarkers drive risk and in which direction
- **Stable:** Scores don't change with cohort demographics or technical batches
- **Validated:** Same algorithm works across cancer types, neurodegenerative diseases, modalities

### For Researchers
- **Reproducible:** Deterministic, seed-locked, fully disclosed thresholds
- **Discoverable:** Univariate biomarkers remain scientifically actionable (not buried in black boxes)
- **Generalizable:** Methodologies trained on one disease validate on another without retuning

### For Patients
- **Early Detection:** Prodromal PD detection (AUC 0.766) enables pre-motor intervention
- **Risk Stratification:** Confidence-scored risk scores, not point estimates
- **Mechanistic Understanding:** Pathway enrichment explains *why* biomarkers matter

---

## Intellectual Property

All work is protected by four provisional patents filed Dec 2025–Feb 2026:

- **US 63/942,422** — BPF core methodology
- **US 63/978,445** — AD/neurodegeneration application
- **US 63/979,043** — PD extension
- **US 63/984,186** — CBAE/reproducibility governance

IP is held by **Far Rockaway Ventures IP LLC** and exclusively licensed to **PulseLogic Biosciences Inc.**

---

## Current Focus

### Publications
- **Bioinformatics (submitted):** BPF methodology paper — BIOINF-2026-0795
- **GigaScience (submitted):** CBAE reproducibility framework — GIGA-D-26-00097
- **Nature Methods (planned):** Multi-domain validation capstone

### Partnerships
Actively seeking collaborations with computational biology labs doing biomarker discovery in:
- Precision oncology
- Neurodegenerative disease (AD/PD/FTD)
- Other high-dimensional omics applications

### Funding
- **NCI SBIR Phase I (April 5, 2026):** 7-document package submitted for evaluation

---

## Open Questions

1. **How does BPF perform on single-cell RNA-seq data?** (High-dimensional, sparse)
2. **Can fusion synthesis extend to multi-modal imaging + genomics?** (Spatial omics)
3. **What's the optimal panel size for clinical deployment?** (Cost vs. accuracy tradeoff)
4. **Can prodromal PD detection translate to prospective clinical trials?** (Next frontier)

---

## Let's Collaborate

If you're working on biomarker discovery and want to explore:
- BPF validation on your cohorts
- Custom fusion strategies for multi-modal data
- Reproducibility frameworks for your ML pipelines

**Reach out:** [ceo@pulselogic.bio](mailto:ceo@pulselogic.bio)

---

*Last updated: April 1, 2026*  
*ORCID: [0009-0008-5690-3723](https://orcid.org/0009-0008-5690-3723)*
