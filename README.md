# Hi, I'm Christopher Dowden 👋

**Founder & CEO @ [PulseLogic Biosciences](https://pulselogic.bio)**

I'm a computational biology explorer challenging established paradigms in biomarker discovery. I build novel methodologies that question conventional approaches to feature selection and risk stratification.

---

## What I'm Working On

### [Biomarker Probability Fusion (BPF)](https://github.com/pulselogicbio/pulselogic-bpf)
A deterministic biomarker discovery framework with locked, dataset-independent parameters. Validated on 39 oncology cohorts (16,958 patients, mean AUC 0.8077) and benchmarked against properly-tuned LASSO, ElasticNet, and Random Forest on a 15-cohort independent comparator set (5,654 patients). Validated disease-agnostic across oncology, Alzheimer's disease, and Parkinson's disease without domain-specific modifications.

**Key innovation:** Univariate AUC ranking + adaptive selection + AUC-derived weighting + probabilistic fusion via sigmoid transformation — applied with locked parameters across all cohorts and disease domains.

### [Computational Bio-AI Engineering (CBAE)](https://github.com/pulselogicbio/cbae-compliance-algorithm)
A reproducibility framework with 18-assertion deterministic evaluation for biological ML pipelines. Built to enforce audit trails, reproducibility, and bounded deployment envelopes.

### Three-Domain Validation Platform
- **[Oncology (Phase 1)](https://github.com/pulselogicbio/pulselogic-platform):** 39 TCGA, GDC, and CGCI cohorts, 16,958 patients, mean AUC 0.8077
- **[Alzheimer's Disease (Phase 2)](https://github.com/pulselogicbio/pulselogic-alzheimers):** ADNI transcriptomics/genomics/methylation, peak AUC 0.948
- **[Parkinson's Disease (Phase 3)](https://github.com/pulselogicbio/pulselogic-parkinsons):** PPMI prodromal detection, AUC 0.766 for pre-motor PD

---

## Current Projects

### 🔥 Prodromal Parkinson's Detection (HIGH PRIORITY)
**Status:** Completed analysis; seeking prospective validation partners  
**Result:** AUC 0.766 for pre-motor PD detection from blood RNA-seq  
**Next:** Design multi-site validation protocol + engage clinical researchers  
**Timeline:** Prospective trial design by Q3 2026

### 🔬 Multi-Modal Omics Fusion (MEDIUM PRIORITY)
**Status:** Pilot phase (ADNI 3-way: genomics + transcriptomics + methylation)  
**Result:** AUC 0.818 on combined modalities  
**Next:** Expand to cancer precision medicine (genomic + imaging + proteomics)  
**Timeline:** Preliminary results by Q2 2026

### 🧬 Single-Cell & Spatial Omics (EXPLORATORY)
**Status:** Theoretical framework; empirical validation pending  
**Research Q:** Can BPF scale to 20K+ genes × 100K+ cells without overfitting?  
**Next:** Pilot on publicly available single-cell data  
**Timeline:** Feasibility study by Q3 2026

---

## Why This Matters

Established feature selection methods (LASSO, ElasticNet) typically require:
- Per-dataset hyperparameter tuning
- Multivariate fitting that obscures per-feature contribution
- Cohort-specific tuning choices that affect cross-cohort comparison

**BPF takes a different approach** — locked, dataset-independent parameters with univariate per-gene scoring. The result: deterministic outputs that are directly comparable across cohorts and diseases.

---

## Research & Publications

### Active Manuscripts

Multiple manuscripts in preparation, under revision, or pending submission across BPF methodology, CBAE reproducibility framework, and disease-specific validation. Citable Zenodo software releases are available in advance of journal publication (see Resources below).

**Current publication status:** [PUBLICATIONS.md](PUBLICATIONS.md)

Contact for current submission status of specific manuscripts.

---

## Get Involved

### Collaboration Opportunities
I'm actively seeking partnerships with labs doing:
- **Precision oncology:** Multi-modal biomarker discovery
- **Neurodegenerative disease:** Early detection signals (especially PD/AD)
- **Reproducible ML:** Infrastructure for audit-ready pipelines

**Models available:**
1. **Co-author partnership** — You provide data, we provide analysis (no cost)
2. **Formal research collaboration** — Multi-paper effort with structured agreement
3. **Service/consulting** — Fee-based for immediate timelines

**Interested?** See [COLLABORATIONS.md](COLLABORATIONS.md) for details

### Resources
- **GitHub Organization:** [@pulselogicbio](https://github.com/pulselogicbio)
- **BPF software:** [pulselogic-bpf](https://github.com/pulselogicbio/pulselogic-bpf) — Zenodo DOI: [10.5281/zenodo.19342790](https://doi.org/10.5281/zenodo.19342790)
- **CBAE reproducibility toolkit:** [cbae-compliance-algorithm](https://github.com/pulselogicbio/cbae-compliance-algorithm) — Zenodo DOI: [10.5281/zenodo.19412560](https://doi.org/10.5281/zenodo.19412560)
- **Platform Results:** [pulselogic-platform](https://github.com/pulselogicbio/pulselogic-platform) — All three domains with DOI-versioned artifacts

---

## Research Identity

- **ORCID:** [0009-0008-5690-3723](https://orcid.org/0009-0008-5690-3723)
- **Website:** [christopherdowden.com](https://www.christopherdowden.com/)
- **Company:** [pulselogic.bio](https://pulselogic.bio)
- **Email:** [ceo@pulselogic.bio](mailto:ceo@pulselogic.bio)

---

## Extended Profiles

For deeper context:
- **[Research Statement](RESEARCH_STATEMENT.md)** — My philosophy on biomarker discovery
- **[Publications & Manuscripts](PUBLICATIONS.md)** — Full submission status + datasets
- **[Collaboration Framework](COLLABORATIONS.md)** — How to work together
- **[Research Roadmap](ROADMAP.md)** — Projects, priorities, open questions

---

## Provisional Patents

- **US 63/942,422** — BPF core methodology (Dec 2025)
- **US 63/978,445** — AD/neurodegeneration extension (Feb 2026)
- **US 63/979,043** — PD extension (Feb 2026)
- **US 63/984,186** — CBAE/CEBIS governance (Feb 2026)

IP held by **Far Rockaway Ventures IP LLC** (exclusive license to PulseLogic Biosciences Inc.)

---

## Open Questions

1. **Prodromal Detection:** Can we validate pre-motor PD detection in a prospective trial?
2. **Multi-Modal Fusion:** How do we design domain-agnostic fusion for 5+ data types?
3. **Single-Cell Scaling:** Can BPF maintain stability at 20K genes × 100K cells?
4. **Clinical Utility:** How do we measure real impact on patient outcomes?
5. **Generalization:** Will biomarkers trained on US cohorts work globally?

If you have data, ideas, or collaborations for any of these — let's talk.

---

**Let's push boundaries in computational biology together.** If you're working on biomarker discovery and want to explore BPF validation, reach out: [ceo@pulselogic.bio](mailto:ceo@pulselogic.bio)

---

*Last updated: April 27, 2026*  
*See also: [@pulselogicbio](https://github.com/pulselogicbio) — the research organization*
