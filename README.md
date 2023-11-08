## Data analysis for climate justice

Repo for HUMA2026 Data Environmentalism 'ExxonMobil's climate change communications: data analysis for climate justice'.

### Data

This repo contains two directories:

- one containing 17 pdfs [James](https://www.southampton.ac.uk/people/5yrbp5/doctor-james-baker) found at The House of Commons Library page '[Climate change: an overview](https://commonslibrary.parliament.uk/research-briefings/cbp-8666/), published October 2021.
- a second of txt files created by James from those pdfs, totalling 65k words.
  - using the [bash command line](https://programminghistorian.org/en/lessons/intro-to-bash) script `for file in *.pdf; do pdftotext "$file" "${file%.*}.txt"; done`.
  - then combined into one file (with a little descriptive detail at the start of each line) and made into a spreadsheet.

### Analysis

1. Download [UK-climate-docs_for-LDA_v4.xlsx](https://github.com/Southampton-Digital-Humanities/HUMA2026_data-analysis/raw/main/txt/UK-climate-docs_for-LDA_v4.xlsx).
2. Upload this document to your Google Drive account, open it, select 'File' and then 'Save as Google Sheets'
3. Go to **[Topic Modeling for HUMA2026 wk7 (data analytics for climate justice)](https://colab.research.google.com/drive/1eSxIMh2-WFTE-_-lC_96cO9Betrmnsnq?usp=sharing)** [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1eSxIMh2-WFTE-_-lC_96cO9Betrmnsnq?usp=sharing) on Google Colab, hit 'File' and 'Save a Copy in Drive', then start analysing!

### Licence

Documents in this repo are shared under an [Open Parliament Licence](https://www.parliament.uk/site-information/copyright-parliament/open-parliament-licence/).
