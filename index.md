---
layout: default
title: Neuroanatomical and transcriptomic underpinnings of functional aggression subtypes
---

<header class="paper-header">
  <p class="paper-label">Extended Data and Methods</p>
  <h1 class="paper-title">Neuroanatomical and transcriptomic underpinnings of functional aggression subtypes</h1>
  <p class="paper-authors">Alessio Giacomel<sup>1,2,3</sup>, Wiebke Hennig<sup>1,2</sup>, Caroline Gurr<sup>1,2</sup>, Afsheen Kumar<sup>1,2</sup>, Johanna Leyhausen<sup>1,2</sup>, Hanna Seelemeyer<sup>1,2</sup>, Bassem Hermila<sup>1,2</sup>, Alexandre Jeanne<sup>1,2</sup>, Franziska Müller<sup>1,2</sup>, FemNAT-CD Consortium, Stephane De Brito<sup>4,5,6,7</sup>, Graeme Fairchild<sup>8</sup>, Kerstin Konrad<sup>9,10</sup>, Ute Habel<sup>11</sup>, Andreas G. Chiocchetti<sup>2</sup>, Christine M. Freitag<sup>2</sup>, Christine Ecker<sup>1,2,12</sup></p>
  <div class="paper-affiliations">
    <p><sup>1</sup> Cooperative Brain Imaging Centre (COBIC), University Hospital, Goethe University, Frankfurt am Main, Germany</p>
    <p><sup>2</sup> Department of Child and Adolescent Psychiatry, University Hospital, Goethe University, Frankfurt am Main, Germany</p>
    <p><sup>3</sup> Centre for Neuroimaging Sciences (CNS), Institute of Psychiatry, Psychology and Neurosciences (IoPPN), King's College London, London, UK</p>
    <p><sup>4</sup> Centre for Human Brain Health, School of Psychology, University of Birmingham, Birmingham, United Kingdom</p>
    <p><sup>5</sup> Institute for Mental Health, School of Psychology, University of Birmingham, Birmingham, United Kingdom</p>
    <p><sup>6</sup> Centre for Developmental Science, School of Psychology, University of Birmingham, Birmingham, United Kingdom</p>
    <p><sup>7</sup> Birmingham Centre for Neurogenetics, University of Birmingham, Birmingham, United Kingdom</p>
    <p><sup>8</sup> Department of Psychology, University of Bath, Bath, United Kingdom</p>
    <p><sup>9</sup> Child Neuropsychology Section, Department of Child and Adolescent Psychiatry, Psychosomatics and Psychotherapy, University Hospital RWTH Aachen, Aachen, Germany</p>
    <p><sup>10</sup> JARA-Brain Institute II, Molecular Neuroscience and Neuroimaging, RWTH Aachen and Research Centre Jülich, Jülich, Germany</p>
    <p><sup>11</sup> Department of Psychiatry, Psychotherapy and Psychosomatics, Faculty of Medicine, RWTH Aachen University, Aachen, Germany</p>
    <p><sup>12</sup> Department of Forensic and Neurodevelopmental Sciences, Institute of Psychiatry, Psychology, and Neuroscience (IoPPN), King's College London, London, UK</p>
  </div>
</header>

<p class="paper-lede">This page expands the analyses summarized on the poster and gives readers a single place to find cohort information, processing details, statistical models, and interpretation workflows.</p>

<nav class="section-nav" aria-label="Page sections">
  <a href="#participants"><span>Participants</span><span class="section-nav__number">01</span></a>
  <a href="#mri-processing"><span>MRI Processing</span><span class="section-nav__number">02</span></a>
  <a href="#glm-analysis"><span>GLM Analysis</span><span class="section-nav__number">03</span></a>
  <a href="#neuroreceptor-similarity"><span>Neuroreceptor Similarity</span><span class="section-nav__number">04</span></a>
  <a href="#gene-decoding"><span>Gene Decoding</span><span class="section-nav__number">05</span></a>
  <a href="#functional-enrichment"><span>Functional Enrichment</span><span class="section-nav__number">06</span></a>
  <a href="#data-and-code-availability"><span>Data and Code Availability</span><span class="section-nav__number">07</span></a>
  <a href="#contact"><span>Contact</span><span class="section-nav__number">08</span></a>
</nav>

---

## Participants

Use this section for a compact but complete cohort description.

### Sample Overview

- Recruitment source:
- Final sample size:
- Age summary:
- Sex distribution:
- Key behavioral or clinical descriptors:

### Inclusion and Exclusion Criteria

- Inclusion criteria:
- Exclusion criteria:
- MRI quality-control exclusions:
- Analysis-specific exclusions:

### Recommended Supplementary Material

Add a concise demographics table here if the poster only reports `N`, age, or group counts.

## MRI Processing

Describe acquisition and preprocessing as one coherent workflow so readers can follow how raw MRI data became analysis-ready maps.

### MRI Acquisition

- Scanner and field strength:
- Structural sequence and resolution:
- Functional sequence and resolution:
- Additional modalities:

### Preprocessing Workflow

1. Raw data organization and BIDS conversion
2. Structural preprocessing
3. Functional preprocessing
4. Registration, normalization, and parcellation
5. Quality control and exclusion thresholds

### Outputs Used in Downstream Analyses

State which derived brain maps, regional measures, or subject-level summaries entered the GLM, neuroreceptor similarity, and transcriptomic analyses.

## GLM Analysis

Use this section for the main inferential model behind the poster results.

### Outcome, Predictors, and Covariates

- Primary outcome:
- Main predictor of interest:
- Covariates:
- Random effects or grouping variables, if applicable:

### Model Specification

Add the full model formula here so readers can reconstruct the analysis.

```text
outcome ~ aggression_score + age + sex + site
```

### Contrasts and Statistical Inference

- Primary contrasts or hypotheses:
- Effect size metric:
- Multiple-comparison correction:
- Sensitivity or robustness checks:

## Neuroreceptor Similarity

Describe how the statistical map was compared with neurotransmitter or receptor reference maps.

### Reference Maps

- Source atlas or dataset:
- Receptors or transporters tested:
- Spatial resolution or parcellation:
- Preprocessing or harmonization steps:

### Similarity Analysis

1. Match the GLM-derived map to the receptor-map space
2. Compute the similarity metric
3. Generate appropriate spatially constrained null models
4. Test significance and correct across receptors or tracers

### Reporting

Summarize how similarity strength, direction, and corrected significance are presented on the poster and on this page.

## Gene Decoding

Use this section to describe the transcriptomic interpretation of the imaging result.

### Transcriptomic Resource

- Gene-expression atlas:
- Donor handling and normalization:
- Regional matching strategy:
- Hemisphere or parcel restrictions, if any:

### Gene Association Analysis

- Imaging map used as input:
- Gene scoring or association method:
- Null model or permutation framework:
- Significance threshold or FDR rule:

### Reporting

Link the full ranked gene list or supplementary table here if only top hits are shown on the poster.

## Functional Enrichment

This section should explain how the decoded gene set was translated into biological interpretation.

### Input Gene Set

- Ranked list or thresholded genes:
- Positive and negative tails, if analyzed separately:
- Background gene set:

### Enrichment Framework

- Databases tested:
- Statistical test:
- Multiple-testing correction:
- Software or package used:

### Reporting

Include a short table of top enriched terms and provide a downloadable file with the full enrichment results.

---

## Data and Code Availability

- Code: [GitHub repository](https://github.com/YOURUSERNAME/Aggression_ohbm26_supplementary)
- Supplementary tables and figures: add links here
- Data access statement: add repository or access language here

## Contact

**Your Name**  
your.email@institution.edu
