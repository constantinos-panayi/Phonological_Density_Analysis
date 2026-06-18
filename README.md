# Computational Analysis of Poetic Phonological Density

### An Exploratory Comparative Analysis of the Phonological Characteristics of Shakespeare, Dickinson, and Browning

## Overview

This repository presents an **exploratory computational analysis of poetic phonological density** across selected works by **William Shakespeare**, **Emily Dickinson**, and **Elizabeth Barrett Browning**.

Situated within a **Digital Humanities** framework, the project combines **Computational Linguistics**, **Natural Language Processing (NLP)**, and **phonological feature extraction** to investigate whether quantitative sound-based measures can reveal meaningful stylistic differences between poetic corpora.

The study focuses on phonological density and rhythmic structure through syllable- and stress-based metrics derived from the **CMU Pronouncing Dictionary**, offering a computational perspective on poetic style and auditory complexity.

This project constitutes the **first assignment for the Data Analysis for Humanities with Python course** of the **MSc Digital Humanities programme**, jointly offered by the National and Kapodistrian University of Athens, the University of Cyprus, and the ATHENA Research Centre.

---

## Research Objectives

The project addresses the following research questions:

* Are there measurable differences in phonological density among the examined poets?
* Do Shakespeare, Dickinson, and Browning exhibit distinct rhythmic characteristics?
* Which poet demonstrates the highest phonological density?
* Which poet exhibits greater variability in phonological organisation?
* Can computational phonological measures provide meaningful insights into poetic style?

---

## Dataset Description

The corpus consists of poetic texts authored by:

* William Shakespeare
* Emily Dickinson
* Elizabeth Barrett Browning

The texts were provided as part of the course material and serve as representative samples of each poet's work for exploratory phonological analysis.

---

## Methodology

### Data Preprocessing

Prior to analysis, a preprocessing pipeline was applied to prepare the corpus for phonological feature extraction.

Preprocessing procedures included:

* Lowercasing
* Punctuation removal
* Line segmentation
* Tokenisation

Phonological information was subsequently retrieved using the **Carnegie Mellon University (CMU) Pronouncing Dictionary**, which provides phonetic transcriptions and stress patterns for English words.

---

### Phonological Feature Extraction

Two complementary phonological measures were extracted:

#### Average Syllables per Line (ASL)

Measures the average number of syllables contained in each poetic line.

ASL serves as an indicator of:

* Phonological density
* Rhythmic complexity
* Poetic flow and pacing

#### Average Stresses per Line (AStL)

Measures the average number of primary stresses occurring within each poetic line.

AStL captures aspects of:

* Rhythmic structure
* Metrical organisation
* Stress regularity

Together, these features provide a quantitative representation of the sound structure of poetry.

---

## Statistical Analysis and Visualisation

### Descriptive Statistics

For each poet and phonological feature:

* Measures of central tendency
* Measures of dispersion
* Distributional summaries

were calculated.

### Visualisation

The following visualisations were employed:

#### Boxplots

* Distribution comparison across poets
* Outlier detection
* Variability assessment

#### Histograms

* Feature distribution analysis
* Density and concentration patterns
* Rhythmic profile exploration

---

## Key Findings

### Phonological Density

* Elizabeth Barrett Browning exhibits the highest overall phonological density.
* Shakespeare follows closely with similarly elevated syllable and stress counts.
* Dickinson demonstrates a more compact phonological profile with lower overall values.

### Rhythmic Structure

* Browning and Shakespeare display denser and more metrically structured poetic styles.
* Dickinson's poetry tends toward shorter lines and reduced stress frequency.

### Variability

* Dickinson exhibits the greatest variability, particularly in syllable counts.
* Browning demonstrates the most consistent phonological distributions.
* Shakespeare occupies an intermediate position between the two.

### Comparative Interpretation

* Shakespeare and Browning show broadly similar phonological characteristics.
* Dickinson is distinguished by lower phonological density and greater variation.
* Computational phonological measures successfully reveal stylistic differences among the examined poets.

---

## Conclusions

The findings demonstrate that computational phonological analysis can effectively identify meaningful differences in poetic style through quantitative measures of sound structure and rhythm.

Although exploratory in scope, the study highlights the potential of phonological feature extraction for Digital Humanities research and provides a foundation for future investigations incorporating additional dimensions such as:

* Rhyme frequency
* Alliteration patterns
* Assonance
* Meter detection
* Prosodic complexity

---

## Repository Structure

├── CODE_Phonological_Density_Analysis.ipynb

├── REPORT_Phonological_Density_Analysis.pdf

├── README.md

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* NLTK
* CMU Pronouncing Dictionary
* Natural Language Processing (NLP)

---

## License

**Academic Use – Coursework License**

This repository contains coursework developed within the MSc Digital Humanities programme.

The material is intended exclusively for academic, educational, and research purposes. Commercial use, redistribution, or modification without explicit permission from the author is prohibited.

---

## Author

**Constantinos Panayi**

Postgraduate Student, MSc Digital Humanities

National and Kapodistrian University of Athens • University of Cyprus • ATHENA Research Centre
