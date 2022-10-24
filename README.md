## Data analysis for climate justice

Repo for HUMA2026 Data Environmentalism 'ExxonMobil's climate change communications: data analysis for climate justice'.

### Data

This repo contains two directories:

- one of 17 pdfs [James](https://www.southampton.ac.uk/people/5yrbp5/doctor-james-baker) found at The House of Commons Library page '[Climate change: an overview](https://commonslibrary.parliament.uk/research-briefings/cbp-8666/), published October 2021.
- a second of txt files created by James from those pdfs, totalling 65k words.
  - using the [bash command line](https://programminghistorian.org/en/lessons/intro-to-bash) script `for file in *.pdf; do pdftotext "$file" "${file%.*}.txt"; done`.

### Software Setup

We are using Topics Explorer to analyse this data.

#### Windows

Download and install 'dariah-topics-explorer-2.0.1-windows.zip' at [https://github.com/DARIAH-DE/TopicsExplorer/releases/tag/v2.0](https://github.com/DARIAH-DE/TopicsExplorer/releases/tag/v2.0).

#### Mac

Follow instructions at [https://github.com/DARIAH-DE/TopicsExplorer](https://github.com/DARIAH-DE/TopicsExplorer), specifically:

- Download [https://github.com/DARIAH-DE/TopicsExplorer/archive/refs/heads/master.zip](https://github.com/DARIAH-DE/TopicsExplorer/archive/refs/heads/master.zip)
- On your terminal, go to the your `Downloads` folder and do `unzip TopicsExplorer-master.zip`.
- Then `cd TopicsExplorer-master` to enter the application folder.
- `source $HOME/.poetry/env` then `poetry install` to install the application.
- And `poetry run python application.py` to run it, which will then be accessible in any browser at `localhost:5001`

### Licence

Documents in this repo are shared under an [Open Parliament Licence](https://www.parliament.uk/site-information/copyright-parliament/open-parliament-licence/).
