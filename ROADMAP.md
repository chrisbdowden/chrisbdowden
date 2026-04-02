# Research Roadmap & Current Projects

## Immediate Priorities (April–June 2026)

### 1. Publication Decision Points
**Bioinformatics (BIOINF-2026-0795)**
- **Expected:** Decision by June 1, 2026
- **If accepted:** Fast-track Paper 3 to Nature Methods; publish domain papers in parallel
- **If major revisions:** Address + resubmit within 3 weeks; activate alternative submission pipeline (Genome Biology, Briefings in Bioinformatics)
- **If rejected:** Resubmit to Nature Methods immediately + launch strategic lab outreach for co-author partnerships

**GigaScience (GIGA-D-26-00097)**
- **Expected:** Decision by May 15, 2026
- **Status:** Secondary priority; resubmit only if Bioinformatics decision clears methodology questions
- **Contingency:** If rejected, refocus CBAE as reproducibility methods paper for *Briefings in Bioinformatics* or *Patterns*

### 2. NCI SBIR Phase I Submission
- **Deadline:** April 5, 2026 (post-reauthorization, awaiting NOFO)
- **Status:** 7-document package complete; ready for submission within 24 hours of NOFO drop
- **Next step:** Monitor grants.nih.gov for Phase I SBIR NOFO announcement

### 3. Institutional Partnerships (Active Outreach)
- **Target:** 5–8 labs in AD/PD/oncology computational biology
- **Strategy:** Personalized outreach + offer BPF validation co-authorship
- **Goal:** 2–3 partnerships active by June 30, 2026
- **Deliverable:** Co-authored manuscripts in progress

---

## Current Projects (In Progress)

### Project A: Prodromal Parkinson's Detection (HIGH PRIORITY)
**Status:** Completed analysis (AUC 0.766), ready for prospective validation  
**Next Steps:**
1. Design prospective validation protocol (PPMI follow-up cohort or GP2)
2. Power analysis for clinical trial readiness
3. Engage with PD clinical researchers for validation partnership
4. Target publication: *Lancet Neurology* or *Brain* (clinical validation focus)

**Collaboration Opportunity:** Seeking labs with **longitudinal PD cohorts** who can validate this early detection signal

---

### Project B: Multi-Modal Omics Fusion (MEDIUM PRIORITY)
**Status:** Pilot phase (ADNI + synthetic data)  
**Current Results:**
- 3-way fusion (genomics + transcriptomics + methylation): AUC 0.818
- Individual modality performance benchmarked

**Next Steps:**
1. Expand to imaging + fluid biomarkers (expand beyond genomics)
2. Test on **cancer precision medicine** datasets (genomics + imaging + proteomics)
3. Design adaptive thresholds per modality type
4. Target publication: *Nature Biomedical Engineering* (fusion architecture)

**Collaboration Opportunity:** Seeking **precision oncology labs** with multi-modal datasets (genomic + imaging)

---

### Project C: Single-Cell & Spatial Omics Application (EXPLORATORY)
**Status:** Theoretical framework designed; no empirical validation yet  
**Research Questions:**
- How does BPF scale to 20K+ genes × 100K+ cells?
- Can univariate AUC ranking handle dropout/sparsity?
- What panel sizes emerge from spatial transcriptomics?

**Next Steps:**
1. Pilot on publicly available single-cell data (PBMC, tumor microenvironment)
2. Compare BPF vs. Seurat/Scanpy best practices
3. Benchmark on cell type discovery (known clusters)
4. Target publication: *Nature Methods* (if novel; else *Genome Biology*)

**Collaboration Opportunity:** Seeking **single-cell genomics labs** for co-development

---

## Mid-Term Projects (July–December 2026)

### Project D: Clinical Trial Design Support
**Goal:** Translate prodromal PD detection into prospective validation trial  
**Deliverable:** Protocol design + power analysis + regulatory readiness assessment  
**Partner Target:** Movement Disorder Societies, Parkinson's Foundation, MJFF

**Timeline:** 6 months (June–Dec 2026)

---

### Project E: Paper 4–5: Disease-Specific Deep Dives
**Paper 4 (AD focus):** "Multimodal biomarker fusion for Alzheimer's disease risk stratification: AUC 0.948 on DNA methylation"
- **Target Journal:** *Alzheimer's & Dementia*
- **Status:** Data ready; manuscript draft in progress
- **Timeline:** Submit by July 2026

**Paper 5 (PD focus):** "Pre-motor Parkinson's detection via expression biomarkers: towards early intervention in the prodromal phase"
- **Target Journal:** *Movement Disorders* or *Parkinson's Disease*
- **Status:** Data ready; requires prospective validation partnership first
- **Timeline:** Submit by September 2026 (dependent on partnership)

---

### Project F: Nature Methods/Nature Biotech Capstone
**Goal:** Comprehensive methodological review + cross-domain meta-analysis  
**Paper 3 (already drafted):** Full downstream analysis across all 3 domains  
**Status:** LOCKED & READY; triggered on primary publication acceptance  
**Target:** Nature Methods or Nature Biotechnology (Tier 1)  
**Timeline:** Submit by August 2026 (if primary manuscripts accepted by June)

---

## Long-Term Vision (2027+)

### Research Direction 1: Precision Medicine Platform
Build **BPF-powered precision medicine SaaS platform** for labs/clinics:
- Upload cohort data
- Automated BPF analysis
- Biomarker discovery + risk stratification
- Regulatory-grade outputs (CEBIS compliance)

**Status:** Conceptual; feasibility study planned for Q4 2026

---

### Research Direction 2: Disease-Specific Biomarker Libraries
Create **open-source biomarker libraries** for common diseases:
- Oncology: cancer type–specific panels (120+ cancer types)
- Neurodegenerative: AD/PD/FTD staging biomarkers
- Rare disease: ultra-sparse datasets requiring novel fusion strategies

**Status:** Post-publication roadmap

---

### Research Direction 3: Computational Biology Education
Launch **educational resources** on reproducible biomarker discovery:
- Course materials (Python notebooks)
- Methodology papers
- Comparison frameworks (BPF vs. LASSO vs. ElasticNet)
- Open-source implementations

**Status:** Post-publication roadmap

---

## Open Research Questions

These are the problems keeping me up at night. **If you have ideas or data, let's explore together:**

### Q1: Can we design domain-agnostic fusion architectures?
Currently BPF uses **univariate AUC ranking** as the foundation. What if we generalized to any univariate metric (mutual information, correlation, Gini)?

### Q2: What's the theoretical basis for stable biomarker selection under distribution shift?
Prodromal PD detection works on PPMI. Will it generalize to African-ancestry populations? Non-Western cohorts? How do we design robust panels?

### Q3: Can we integrate prior biological knowledge into feature selection without overfitting?
Pathway knowledge exists (KEGG, Reactome). Can we weight univariate rankings by biological relevance *without* data leakage?

### Q4: How do we validate clinical utility in an era of liquid biopsy commodification?
Biomarkers are only valuable if they change treatment. Can we measure real clinical impact?

### Q5: Is there a principled way to choose panel size for deployment?
Trade-off: 10 genes (cheap, simple) vs. 100 genes (robust, complex). How do we optimize for clinical utility?

---

## Funding & Support

**Current Stage:** Pre-revenue founder at extended care facility  
**Seeking:**
- SBIR funding (NCI Phase I, April 2026)
- Research partnerships (cost-sharing or academic)
- Potential investment (Series Seed, 2027+)

**Not Seeking:** Acquisition, quick exits, or short-term consulting engagements

---

## Success Metrics (Next 12 Months)

| Metric | Target | Status |
|--------|--------|--------|
| **Publications** | 2 accepted (Bioinformatics + GigaScience) | 2 under review |
| **Partnerships** | 3 active institutional collaborations | 2 in exploratory stage |
| **Patents** | 4 provisional → 2 full utility filing | 4 provisional filed |
| **Funding** | NCI SBIR Phase I award | Pending NOFO |
| **Talks/Presentations** | 2 conference presentations | 0 (seeking invitations) |
| **GitHub Impact** | 100+ stars across org | 0 (new public repos) |
| **ORCID Citation Count** | 50+ citations to preprints | 10+ (growing) |

---

## How You Can Help

**If you're interested in any of these projects:**

1. **Have relevant data?** Let's collaborate via co-authorship partnership (Model 1, no cost)
2. **Working on similar problems?** Let's design a research collaboration (Model 2, formal agreement)
3. **Want to fund this work?** Let's discuss SBIR or Series Seed (Model 3, investment/grant)
4. **Know relevant labs?** Introduce us — I'm actively seeking partnerships in AD/PD/oncology

**Contact:** [ceo@pulselogic.bio](mailto:ceo@pulselogic.bio)

---

*Last updated: April 1, 2026*  
*GitHub: [@pulselogicbio](https://github.com/pulselogicbio)*  
*ORCID: [0009-0008-5690-3723](https://orcid.org/0009-0008-5690-3723)*  
*Website: [pulselogic.bio](https://pulselogic.bio)*
