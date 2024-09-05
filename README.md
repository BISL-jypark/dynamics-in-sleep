# Dynamics-in-Sleep
The repository holds the code for the manuscript Park et al. (2024), "Dynamics in blood transcriptome networks reveal molecular signatures of homeostatic-circadian regulation".

## Abstract
Sleep regulation, essential for health and physiological function, is governed by sophisticated molecular network interactions within the human body. Our study utilizes time-series transcriptomic data from blood to explore dynamic topological features of gene co-expression networks, uncovering new dimensions of sleep regulation mechanisms. We categorize sleep regulation into two primary aspects: sleep homeostasis and circadian rhythm. In our analysis, network local connectivity reflects homeostatic effects, increasing with wakefulness and decreasing during sleep. Network robustness incorporates circadian influences, noting significant disruption and a decrease in amplitude among those with restricted sleep. A pivotal discovery in our study is the identification of the guanine nucleotide-binding protein (G protein) alpha-stimulating activity polypeptide 1 (GNAS) as a marker of sleep homeostasis. The activation of the G*a*s pathway, which promotes arousal in the early morning, is significantly disrupted in total sleep deprivation. This finding elucidates that the blood transcriptome can detect activities of sleep regulation similar to those in the brain and central nervous system. In addition, we found that arrestin-*b*2 (ARRB2) serves as a circadian marker and its relationship with arrestin-*b*1 (ARRB1) jointly controls melanopsin photoresponse, which weakens after chronic sleep restriction. These findings suggest that sleep loss impacts the structural relationships between genes in the blood, providing new insights into the mechanisms of sleep regulation. By exploring the dynamics within gene networks, we enhance our understanding of how sleep is regulated.

## Installation
To set up a local development environment, follow these steps:

```bash
# Clone the repository
git clone https://github.com/BISL-jypark/dynamics-in-sleep.git
cd dynamics-in-sleep

# Setup virtual environment (Optional but recommended)
python -m venv env
source env/bin/activate

# Install dependencies
pip install 
```

## Usage
To run the analysis and reproduce the results, follow these steps:

```python
# To analyze sleep deprivation data
jupyter notebook src/sleep-deprivation-study.ipynb

# To analyze sleep restriction data
jupyter notebook src/sleep-restriction-study.ipynb

# To validate sleep homeostasis study using C57BL/6J mice
jupyter notebook src/sleep-deprivation-validation.ipynb 

```

## Requirements
The code is written in Python (v3.8.5). 
- Pandas < 2.0.0
- NetworkX == 3.1



