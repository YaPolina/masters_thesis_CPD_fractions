# Using Speech Transcripts of the First Congress of People's Deputies of the USSR to Automatically Classify Deputies according to Fractions

## Overview

This project focuses on the **automatic classification of deputies of the First Congress of People's Deputies of the USSR** into factions based on the analysis of their speeches. The aim of the research is to understand the division among deputies by analyzing transcripts from the Congress sessions using machine learning techniques.

## Research Conclusion

The First Congress of People's Deputies of the USSR was marked by a division of deputies into two opposing groups from the very beginning of its work. Historical narratives often emphasize the existence of a conservative majority aligned with the authorities and a dissenting minority, which formed the first internal opposition in the USSR: Interregional Deputy Group.

Through machine learning analysis of speeches delivered by 375 deputies who spoke at the Congress and were included in the training dataset, the following results were obtained:

- Approximately **30-118 deputies** were identified as belonging to the faction of Supporters of the Communist Party of the Soviet Union (CPSU).
- Approximately **257-345 deputies** were classified as members of the Interregional Deputy Group.

The proportion of deputies among the analyzed set is as follows:
- **8-31%** of deputies were classified as CSPU_Officials
- **69-92%** were classified as members of the Inter_regional_Deputies_Group.

The results suggest that, at least among those who delivered speeches, the majority of deputies followed the discourse of the Interregional Deputy Group. This faction shaped the dominant voice during the Congress sessions, which captured the attention of the Soviet population.

## Results

The machine learning models identified distinct patterns in the speech transcripts that aligned with the known factions. The classification results reflect the significant influence of the Interregional Deputy Group in shaping the discourse of the Congress.

## Repository Structure

- `CPD_fractions_ML/`: Machine learning code implemented using **scikit-learn** for classifying the deputies.
- `parsing_pdf/`: Scripts for extracting and parsing data from PDF transcripts of speeches.
- `cleaning_text_data/`: Data pre-processing scripts, including text cleaning and formatting for analysis.
- `data/`:
  - `train.csv`: The training dataset used for machine learning, containing labeled deputies and their speeches.
  - `fractions.csv`: The output results from the machine learning model, showing the predicted factions for each deputy.

