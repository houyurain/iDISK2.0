# iDISK 2.0 - Integrated Dietary Supplement Knowledgebase 2.0

Welcome to the official data-sharing repository for **iDISK 2.0**, the Integrated Dietary Supplement Knowledgebase. This repository provides access to the comprehensive dataset collected and processed for iDISK 2.0, which integrates dietary supplement information from various trusted sources.

## Overview

**iDISK 2.0** is a structured knowledgebase designed to offer detailed, up-to-date dietary supplement (DS) information. It integrates data from multiple sources, creating a reliable resource for researchers, healthcare providers, and professionals seeking accurate dietary supplement data. The data files available in this repository include structured entities and their relationships, formatted for easy access and further analysis.

### Key Features
- Integration of data from **DSLD**, **LNHPD**, and **MSKCC**. <!--, and **NMCD**. -->
- Comprehensive dataset covering **dietary supplement ingredients (DSI)**, **products (DSP)**, **diseases**, **drugs**, **symptoms**, and related relationships.
- Data cleaning and normalization for consistency.
- Files are provided in CSV format for easy use.

## Data Structure

The iDISK 2.0 data includes the following key entity types:
- **Dietary Supplement Products (DSP)**
- **Dietary Supplement Ingredients (DSI)**
- **Diseases**
- **Drugs**
- **Symptoms**
<!-- - **Therapeutic Classes (TC)** -->
<!-- - - **System Organ Classes (SOC)** -->

### File Descriptions:
- `dsi.csv`: Contains data on dietary supplement ingredients, including names, source materials, safety information, and related diseases, drugs, and symptoms.
- `dsp.csv`: Includes dietary supplement product names, company information, and related ingredients.
- `disease.csv`: Information on diseases linked to various supplements and their effectiveness.
- `drug.csv`: Data on drug interactions with dietary supplements.
- `symptom.csv`: Links between dietary supplements and the symptoms they aim to address.
- `relationships.csv`: Includes the relationships between all entities (e.g., DSI-Disease, DSI-Drug).

## Citation
```
@article{hou2025improving,
  title={Improving dietary supplement information retrieval: Development of a retrieval-augmented generation system with large language models},
  author={Hou, Yu and Bishop, Jeffrey R and Liu, Hongfang and Zhang, Rui},
  journal={Journal of medical Internet research},
  volume={27},
  pages={e67677},
  year={2025},
  publisher={JMIR Publications Toronto, Canada}
}
```
