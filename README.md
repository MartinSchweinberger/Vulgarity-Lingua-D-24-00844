# Vulgarity in Online Discourse around the English Speaking World (LINGUA-D-24-00844)

This repository accompanies the article *Vulgarity in Online Discourse around the English-Speaking World* (LINGUA-D-24-00844) by Martin Schweinberger and Kate Burridge, which analyzes the use of vulgar language across 20 English-speaking regions using the **GloWbE** corpus (*Global Web-Based English*) (see Schweinberger & Burridge, 2025).

The resources in this repository allow for the replication and inspection of the data extraction, cleaning, processing, and analysis procedures described in the paper.

---

## Repository Contents

This repository includes the following key files:

- **`Vulgarity_LinguaD2400844_Part1.Rmd`**  
  R Markdown notebook for **data extraction and initial processing**.

- **`Vulgarity_LinguaD2400844_Part1.pdf`**  
  PDF rendering of Part 1.

- **`Vulgarity_LinguaD2400844_Part2.Rmd`**  
  R Markdown notebook for **data preparation**.

- **`Vulgarity_LinguaD2400844_Part2.pdf`**  
  PDF rendering of Part 2.

- **`Vulgarity_LinguaD2400844_Part3.Rmd`**  
  R Markdown notebook for **data analysis and visualization**.

- **`Vulgarity_LinguaD2400844_Part3.pdf`**  
  PDF rendering of Part 3.

- **`List of Regular Expressions - Vulgarity Detection`**  
  Contains the regular expressions used to identify potentially vulgar expressions. The resulting matches were semi-automatically cleaned and manually validated.

- **`glowbe_table.rda`**  
  Metadata for the GloWbE files used (file names, regions, token counts). Required to reproduce the analysis in Part 3.

- **`kwic_results_clean.rda`**  
  The manually cleaned keyword-in-context (KWIC) table containing instances of vulgarity identified in the GloWbE corpus.

---

## Corpus Information

The data for this analysis is based on the **offline** version of the *GloWbE* corpus (Global Web-Based English).  
- The **online** version of GloWbE is available [here](https://www.english-corpora.org/glowbe/).  
- For a detailed description of the corpus, see Davies & Fuchs (2015), listed below.

---

## References

- Schweinberger, M., & Burridge, K. (2025). *Vulgarity in Online Discourse around the English-Speaking World*. *Lingua*.  
- Davies, M., & Fuchs, R. (2015). Expanding horizons in the study of World Englishes with the 1.9 billion word Global Web-based English Corpus (GloWbE). *English World-Wide, 36*(1), 1–28.
