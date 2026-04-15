---
layout: default
title: Neuroanatomical and transcriptomic underpinnings of functional aggression subtypes
---

<section class="hero">
  <div class="hero__copy">
    <p class="hero__eyebrow">Poster Companion</p>
    <p class="hero__subtitle">Extended Data and Methods</p>
    <h1 class="hero__title">Neuroanatomical and transcriptomic underpinnings of functional aggression subtypes</h1>
    <p class="hero__lede">This site expands the analyses summarized on the poster and gives readers a fast, navigable overview of cohort information, MRI processing, statistical models, and downstream biological interpretation.</p>
    <div class="hero__chips">
      <span>Participants</span>
      <span>MRI Processing</span>
      <span>GLM Analysis</span>
      <span>Neuroreceptor Similarity</span>
      <span>Gene Decoding</span>
      <span>Functional Enrichment</span>
    </div>
  </div>

  <aside class="hero__panel">
    <p class="hero__panel-label">Author Team</p>
    <p class="hero__authors">Alessio Giacomel<sup>1,2,3</sup>, Wiebke Hennig<sup>1,2</sup>, Caroline Gurr<sup>1,2</sup>, Afsheen Kumar<sup>1,2</sup>, Johanna Leyhausen<sup>1,2</sup>, Hanna Seelemeyer<sup>1,2</sup>, Bassem Hermila<sup>1,2</sup>, Alexandre Jeanne<sup>1,2</sup>, Franziska Müller<sup>1,2</sup>, FemNAT-CD Consortium, Stephane De Brito<sup>4,5,6,7</sup>, Graeme Fairchild<sup>8</sup>, Kerstin Konrad<sup>9,10</sup>, Ute Habel<sup>11</sup>, Andreas G. Chiocchetti<sup>2</sup>, Christine M. Freitag<sup>2</sup>, Christine Ecker<sup>1,2,12</sup></p>
    <details class="hero__details">
      <summary>View affiliations</summary>
      <div class="hero__affiliations">
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
    </details>
  </aside>
</section>

<nav class="section-nav" aria-label="Page sections">
  <a href="#participants"><span>Participants</span><span class="section-nav__number">01</span></a>
  <a href="#mri-processing"><span>MRI Processing</span><span class="section-nav__number">02</span></a>
  <a href="#glm-analysis"><span>GLM Analysis</span><span class="section-nav__number">03</span></a>
  <a href="#neuroreceptor-similarity"><span>Neuroreceptor Similarity</span><span class="section-nav__number">04</span></a>
  <a href="#gene-decoding"><span>Gene Decoding</span><span class="section-nav__number">05</span></a>
  <a href="#functional-enrichment"><span>Functional Enrichment</span><span class="section-nav__number">06</span></a>
  <a href="#data-and-code-availability"><span>Data and Code Availability</span><span class="section-nav__number">07</span></a>
  <a href="#acknowledgments"><span>Acknowledgments</span><span class="section-nav__number">08</span></a>
  <a href="#contact"><span>Contact</span><span class="section-nav__number">09</span></a>
</nav>

<section class="section-card" id="participants" markdown="1">
  <div class="section-card__top">
    <span class="section-card__index">01</span>
    <div>
      <h2>Participants</h2>
      <p class="section-card__intro">Participants from the FemNAT-CD cohort included in the current study.</p>
    </div>
  </div>

### Sample Overview
All subject data used in this study were obtained from the FemNAT-CD study, a multicenter study aimed at investigating sex differences in Conduct Disorders (CD).
Of the full sample, participants were included in the present study if 1) they had completed an MRI scan; 2) had available ancillary information for the analysis (i.e., age, biological sex), and 3) behavioral measures for full-scale intelligence quotient (FSIQ), measured with the Wechsler Abbreviated Scale of Intelligence 2nd edition (WASI-II), and aggressive behaviors.

Aggressive behaviors were assessed using the Reactive–Proactive Aggression Questionnaire (RPQ)11, a validated 23-item self-report instrument designed to distinguish between reactive and proactive aggression. The scale comprises two subscales, with items assessing impulsive, retaliatory aggression (reactive aggression - RA) and deliberate, goal-directed aggression (proactive aggression - PA). Participants rated each item on a three-point Likert scale ranging from 0 (never) to 2 (often). Individual items in each subscale were summed to obtain an RA and PA subscale score for each participant.

| Characteristic | Overall N = 670<sup>&dagger;</sup> | CD N = 279<sup>&dagger;</sup> | HC N = 391<sup>&dagger;</sup> | Test statistic | p-value<sup>2</sup> |
| --- | --- | --- | --- | --- | --- |
| **Demographics** |  |  |  |  |  |
| Age (years) | 14.21 &plusmn; 2.49<br>[9-18] | 14.25 &plusmn; 2.41<br>[9-18] | 14.18 &plusmn; 2.55<br>[9-18] | W = 54906.00 | 0.883 |
| Sex |  |  |  | chi<sup>2</sup> = 7.24, df = 1 | 0.006 |
| F | 345 (51%) | 126 (45%) | 219 (56%) |  |  |
| M | 325 (49%) | 153 (55%) | 172 (44%) |  |  |
| FSIQ | 100 &plusmn; 13<br>[68-138] | 95 &plusmn; 12<br>[68-128] | 104 &plusmn; 12<br>[70-138] | W = 32914.50 | &lt;0.001 |
| **Neuroimaging** |  |  |  |  |  |
| Acquisition Site |  |  |  | chi<sup>2</sup> = 3.62, df = 4 | 0.459 |
| Aachen | 160 (24%) | 75 (27%) | 85 (22%) |  |  |
| Basel | 71 (11%) | 27 (9.7%) | 44 (11%) |  |  |
| Birmingham | 177 (26%) | 66 (24%) | 111 (28%) |  |  |
| Frankfurt | 139 (21%) | 59 (21%) | 80 (20%) |  |  |
| Southampton | 123 (18%) | 52 (19%) | 71 (18%) |  |  |
| Mean CT (mm) | 2.51 &plusmn; 0.10<br>[2.19-2.84] | 2.50 &plusmn; 0.10<br>[2.19-2.82] | 2.51 &plusmn; 0.10<br>[2.19-2.84] | W = 53207.50 | 0.588 |
| **RPQ Subscales** |  |  |  |  |  |
| PA Subscale | 2.21 &plusmn; 3.40<br>[0-19] | 4.01 &plusmn; 4.27<br>[0-19] | 0.93 &plusmn; 1.70<br>[0-11] | W = 82819.00 | &lt;0.001 |
| RA Subscale | 7.9 &plusmn; 5.1<br>[0-22] | 11.3 &plusmn; 5.1<br>[0-22] | 5.5 &plusmn; 3.6<br>[0-20] | W = 88920.50 | &lt;0.001 |

*Note:* Values are expressed as mean &plusmn; SD [range] or n (%). FSIQ = Full-Scale Intelligence Quotient Score; CT = Cortical Thickness; RPQ = Reactive Proactive Aggression Questionnaire; RA = Reactive Aggression; PA = Proactive Aggression. <sup>&dagger;</sup> n (%); mean &plusmn; SD [range]. <sup>2</sup> Pearson's chi-squared test; Wilcoxon rank sum test.

</section>

<section class="section-card" id="mri-processing" markdown="1">
  <div class="section-card__top">
    <span class="section-card__index">02</span>
    <div>
      <h2>MRI Processing</h2>
      <p class="section-card__intro">MRI acquisition and preprocessing procedures used to derive cortical-thickness measures for downstream analyses.</p>
    </div>
  </div>

### MRI Acquisition

All participants underwent MRI scanning at one of five sites across Europe: Frankfurt, Basel, Birmingham, Aachen, and Southampton. Structural T1-weighted scans were acquired using either Siemens 3-Tesla MRI systems (Tim-Trio and Prisma) or a Philips 3-Tesla MRI system (Achieva) with magnetization-prepared rapid acquisition gradient-echo sequences. Scans were acquired with a 256 mm field of view and 1.1 x 1.1 x 1.1 mm resolution. Additional details on acquisition parameters and quality assessment procedures are reported in previous consortium publications 35-37.

### Preprocessing Workflow

Structural scans were processed with [FreeSurfer 6.0.0](http://surfer.nmr.mgh.harvard.edu/) to reconstruct cortical surfaces. The standard automated pipeline included intensity normalization, skull stripping, and reconstruction of the gray/white matter boundary and pial surface. Cortical thickness (CT) was computed at each cortical vertex as the average distance between the white matter surface and the closest point on the pial surface, and the resulting vertex-wise CT maps were smoothed with a 15 mm full width at half maximum (FWHM) Gaussian kernel. In addition, mean cortical thickness (CT<sub>0</sub>) across both hemispheres was computed for each participant.

</section>

<section class="section-card" id="glm-analysis" markdown="1">
  <div class="section-card__top">
    <span class="section-card__index">03</span>
    <div>
      <h2>GLM Analysis</h2>
      <p class="section-card__intro">Vertex-wise general linear modeling framework used to test associations between cortical thickness and aggressive behavior.</p>
    </div>
  </div>

### Model Overview

Vertex-wise generalized linear models (GLMs) were estimated with the BrainStat Python toolbox using cortical thickness data as the outcome measure. The model included linear and quadratic age terms to capture potential nonlinear developmental effects, sex, full-scale intelligence quotient (FSIQ), reactive aggression (RA), proactive aggression (PA), sex-by-RA and sex-by-PA interaction terms, acquisition site, and global mean cortical thickness (CT<sub>0</sub>).

$$
\begin{aligned}
\mathrm{CT} \sim\ & \beta_0 + \beta_1 \mathrm{age} + \beta_2 \mathrm{age}^2 + \beta_3 \mathrm{sex} + \beta_4 \mathrm{FSIQ} \\
& + \beta_5 \mathrm{RA} + \beta_6 (\mathrm{RA} \times \mathrm{sex}) + \beta_7 \mathrm{PA} + \beta_8 (\mathrm{PA} \times \mathrm{sex}) \\
& + \beta_9 \mathrm{site} + \beta_{10} \mathrm{CT}_0 + \varepsilon
\end{aligned}
$$

Aggression measures were derived from the Reactive-Proactive Aggression Questionnaire (RPQ). Site was included to account for systematic differences in data acquisition across imaging centers, and CT<sub>0</sub> was included to control for overall individual differences in cortical thickness. To account for multiple comparisons across vertices, statistical maps were thresholded using random-field-theory-based cluster analysis for nonisotropic images, with a two-tailed cluster-level significance threshold of p<sub>clust</sub> &lt; 0.05.

</section>

<section class="section-card" id="neuroreceptor-similarity" markdown="1">
  <div class="section-card__top">
    <span class="section-card__index">04</span>
    <div>
      <h2>Neuroreceptor Similarity</h2>
      <p class="section-card__intro">Describe how the statistical map was compared with neurotransmitter or receptor reference maps.</p>
    </div>
  </div>

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
</section>

<section class="section-card" id="gene-decoding" markdown="1">
  <div class="section-card__top">
    <span class="section-card__index">05</span>
    <div>
      <h2>Gene Decoding</h2>
      <p class="section-card__intro">Use this section to describe the transcriptomic interpretation of the imaging result.</p>
    </div>
  </div>

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
</section>

<section class="section-card" id="functional-enrichment" markdown="1">
  <div class="section-card__top">
    <span class="section-card__index">06</span>
    <div>
      <h2>Functional Enrichment</h2>
      <p class="section-card__intro">This section should explain how the decoded gene set was translated into biological interpretation.</p>
    </div>
  </div>

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
</section>

<section class="section-card" id="data-and-code-availability" markdown="1">
  <div class="section-card__top">
    <span class="section-card__index">07</span>
    <div>
      <h2>Data and Code Availability</h2>
      <p class="section-card__intro"></p>
    </div>
  </div>

- Extended data [GitHub repository](https://github.com/alegiac95/Aggression_ohbm26_supplementary).
- Data access statement: No new data were generated or analyzed in support of this research. Data supporting this study are not publicly available but can be requested from the FemNAT-CD Steering Committee, which is chaired by Professor Christine Freitag and can be requested at: C.Freitag@em.unifrankfurt.de.
- Code used for analysis and generation of the figures will be made available upon publication.
</section>

<section class="section-card" id="acknowledgments" markdown="1">
  <div class="section-card__top">
    <span class="section-card__index">08</span>
    <div>
      <h2>Acknowledgments</h2>
      <p class="section-card__intro">Funding support for the study.</p>
    </div>
  </div>

This study was funded by the German Research Foundation (DFG) - Project number 512007073 - TRR 379.
</section>

<section class="section-card" id="contact" markdown="1">
  <div class="section-card__top">
    <span class="section-card__index">09</span>
    <div>
      <h2>Contact</h2>
      <p class="section-card__intro">For more information about this research contact:</p>
    </div>
  </div>

**Alessio Giacomel**  
giacomel@med.uni-frankfurt.de
</section>
