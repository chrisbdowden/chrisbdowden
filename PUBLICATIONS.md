# Publications & Manuscripts

## Under Review

### Primary Submissions

#### 1. Bioinformatics: BPF Methodology Paper
**Title:** A Stability-Governed, Tuning-Free Framework for Feature Selection in High-Dimensional Transcriptomic Biomarker Discovery

**Manuscript ID:** BIOINF-2026-0795  
**Status:** Under Review (submitted Mar 25, 2026)  
**Expected Decision:** ~June 1, 2026 (60–90 day typical review window)  
**Key Results:**
- 23 independent cancer cohorts (19,038 patients)
- BPF outperforms LASSO/ElasticNet/RF on 10/15 pairwise comparisons (p=0.011)
- Mean AUC advantage: +0.030 (BPF 0.8077 vs LASSO 0.7777)
- Runtime: 5.4 min (BPF) vs 5.7 hrs (LASSO) — 63× speedup
- Stability (Jaccard): 0.272 (BPF) vs 0.153 (LASSO) — 1.8× improvement

**Repository:** https://github.com/pulselogicbio/pulselogic-bpf (DOI: [10.5281/zenodo.19342790](https://doi.org/10.5281/zenodo.19342790))

---

#### 2. GigaScience: CBAE Reproducibility Framework
**Title:** CBAE: A Deterministic Reproducibility Evaluation Algorithm and Toolkit for Biological Machine Learning Pipelines

**Manuscript ID:** GIGA-D-26-00097  
**Status:** Under Review (submitted Mar 25, 2026)  
**Expected Decision:** ~May 15, 2026  
**Key Innovation:**
- 18-assertion deterministic evaluation framework
- 5 evaluation dimensions: Explicitness, Data Provenance, Reproducibility, Stability, Bounded Envelope
- Fully synthetic demo (no patient data required)
- SHA-256 evidence artifact registry

**Repository:** https://github.com/pulselogicbio/cbae-compliance-algorithm (DOI: [10.5281/zenodo.19213057](https://doi.org/10.5281/zenodo.19213057))

---

### Secondary Submissions (Triggered on Primary Acceptance)

#### 3. Paper 3: Cross-Domain Validation & Downstream Analysis
**Title:** [Pending primary acceptance]  
**Status:** **LOCKED & READY** (full manuscript drafted, publication-quality figures, all analyses complete)  
**Trigger:** Upon acceptance of BIOINF-2026-0795 or GIGA-D-26-00097  
**Target Journals:** Nature Methods, Nature Biotechnology (Tier 1)

**Contents:**
- Full downstream analysis pipeline (7 scripts, real computed outputs)
- 122 significant pathway enrichments (FDR q < 0.05)
- Threshold robustness analysis (event-rate ratio 4.30×)
- Ablation studies (direction-corrected weighting critical component)
- 6 publication-quality figures

---

## Preprints

### bioRxiv (Planned)
**Status:** Not yet submitted (holding for journal decision strategy)  
**Plan:** Post BPF manuscript to bioRxiv upon Bioinformatics rejection or major revisions (expected early June 2026)

---

## Validation Datasets (Peer-Reviewed Repositories)

All datasets are publicly available and DOI-versioned:

### Oncology Validation (Phase 1)
- **Source:** UCSC Xena Browser
- **Cohorts:** 39 TCGA + GEO cohorts
- **Patients:** 16,958
- **External AUC:** 0.8029 (41 independent cohorts, 14,498 patients, 6+ sources, 8+ countries)

### Alzheimer's Disease Validation (Phase 2)
- **Source:** ADNI (Alzheimer's Disease Neuroimaging Initiative)
- **Modalities:** Transcriptomics, genomics, DNA methylation, multi-omic fusion
- **Patients:** 262–1,216 (task-dependent)
- **External AUC:** 0.818 mean (GEO datasets, 8 independent sources, 2,972 patients)
- **Peak Performance:** DNA methylation AUC 0.948

### Parkinson's Disease Validation (Phase 3)
- **Source:** PPMI (Parkinson's Progression Markers Initiative) + GP2
- **Modalities:** RNA-seq, genotype, multi-modal
- **Patients:** 365–710 (task-dependent)
- **Prodromal AUC:** 0.766 (pre-motor PD detection)
- **External AUC:** 0.793 mean (GEO datasets, 8 independent sources, 753 patients)

---

## Provisional Patents

All IP filed under **Far Rockaway Ventures IP LLC** (exclusive license to PulseLogic Biosciences Inc.)

| Patent | Title | Filing Date | Status |
|--------|-------|-------------|--------|
| US 63/942,422 | Biomarker Probability Fusion (BPF) Core Methodology | Dec 2025 | Provisional |
| US 63/978,445 | BPF Application to Alzheimer's Disease & Neurodegeneration | Feb 2026 | Provisional |
| US 63/979,043 | BPF Application to Parkinson's Disease | Feb 2026 | Provisional |
| US 63/984,186 | CBAE/CEBIS Reproducibility Governance Framework | Feb 2026 | Provisional |

---

## Funding

### Current Applications

#### NCI SBIR Phase I (Small Business Innovation Research)
**Deadline:** April 5, 2026 (post-reauthorization, S. 3971 passed House Mar 17, 2026)  
**Status:** 7-document package complete and ready for submission  
**PI:** Christopher B. Dowden (CHRISBDOWDEN, Person ID: 80673984)  
**Award Amount:** ~$150K–$200K (Phase I typical)  
**Budget:** PI salary $125K/year @ 50% effort; 26% de minimis indirect rate  
**Research Location:** 755 Hempstead Tpke, Uniondale, NY 11553

---

## Speaking & Presentations

*None scheduled yet — open to conference invitations in computational biology / biomarker discovery*

---

## Collaboration Interests

**Currently seeking partnerships with labs doing:**
- Precision oncology biomarker discovery
- Alzheimer's/Parkinson's disease computational research
- Multi-modal omics integration
- Reproducibility/governance in ML pipelines

**Contact:** [ceo@pulselogic.bio](mailto:ceo@pulselogic.bio)

---

*Last updated: April 1, 2026*  
*Follow publication status: [@pulselogicbio](https://github.com/pulselogicbio) on GitHub*
