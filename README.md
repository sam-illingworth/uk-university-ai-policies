# UK University AI Policies: Open Data and Analysis

The first systematic analysis of how UK universities frame artificial intelligence in institutional policy.

This repository contains the complete data, method, and findings from a study of 97 AI policies across 163 UK higher education institutions. The study combines computational keyword analysis with qualitative coding of a stratified sample of 20 policies.

## Key findings

- **86.6% of policies were computationally classified as education-dominant.** Qualitative analysis tells a different story. Most policies adopt the vocabulary of learning while structurally functioning as compliance instruments.
- **Three mechanisms reproduce the deficit model** independently of surface vocabulary: performative education framing, conditional trust, and structural location within misconduct frameworks.
- **40.5% of UK institutions have no publicly accessible AI policy.** A policy nobody can find serves the institution, not the student.

## Read the analysis

- **Substack post:** [UK Universities Say They Support Students With AI. The Evidence Says Otherwise.](https://theslowai.substack.com/p/uk-university-ai-policies)
- **Supplementary material:** [`paper/supplementary-material.md`](paper/supplementary-material.md)

## Repository structure

```
paper/
  supplementary-material.md    Supplements A-D (keyword vocabularies, coding framework detail)

data/
  uk_universities.csv          163 institutions with type and nation
  urls.csv                     Policy URLs for all institutions
  corpus.csv                   97 policies with full text
  keyword-vocabularies.csv     31 detection + 37 education terms with rationale

analysis/
  framing_analysis.csv         Framing ratios and keyword counts for all 97 policies
  coding-framework.md          28 codes across 6 categories with definitions
  coded-sample.md              20 policies fully coded at paragraph level

figures/
  framing_distribution.png     Distribution of framing ratios across 97 policies
  framing_ratio_by_type.png    Framing ratios by institution type
  framing_by_nation.png        Framing ratios by UK nation
  framing_scatter.png          Scatter plot of detection vs education keywords
  keyword_comparison.png       Keyword frequency comparison
  top_keywords.png             Most frequent keywords across the corpus
```

## How to cite

Illingworth, S. (2026). The Deficit Model in Practice: How UK Universities Frame Artificial Intelligence in Institutional Policy. Working paper. Available at: https://github.com/sam-illingworth/uk-university-ai-policies

## Run this study in your country

The method is transferable. Everything you need is in this repository:

1. **Keyword vocabularies** (`data/keyword-vocabularies.csv`): adapt detection and education terms for local terminology and regulatory language
2. **Coding framework** (`analysis/coding-framework.md`): 28 codes across student-centredness, trust, relevance, agency, deficit indicators, and structural features. Works across national contexts
3. **Scraping approach**: the hardest part is finding the policy URLs, which is itself a finding

If you run a parallel study, please open an issue or get in touch. I will link to it from this repository, co-author where appropriate, or amplify it. The aim is to test whether the deficit model is as pervasive globally as it appears to be in the UK.

## Author

**Sam Illingworth**
Professor of Creative Pedagogies, Edinburgh Napier University
ORCID: [0000-0003-2551-0675](https://orcid.org/0000-0003-2551-0675)

## Licence

This work is licensed under a [Creative Commons Attribution 4.0 International Licence](https://creativecommons.org/licenses/by/4.0/).

You are free to share and adapt this material for any purpose, including commercial, provided you give appropriate credit.
