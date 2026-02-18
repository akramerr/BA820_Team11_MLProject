# BA820_Team11_MLProject
This repository contains our BA820 team project focused on applying unsupervised machine learning techniques to uncover hidden patterns within U.S. federal grant data. Rather than beginning with predefined labels, our goal is to identify natural groupings that provide insight into how agencies structure funding, allocate resources, and support programs.

## Current Project Status
Phase 3 - Integration & Synthesis

Our team has completed individual clustering analyses and is now integrating findings to reveal cross-cutting patterns. Integration work demonstrates how agency funding strategies, eligibility requirements, temporal eras, and topic distributions interact to shape the federal grant landscape.

## Dataset
U.S. Government Grant Opportunities (2004–2023)

The dataset captures funding amounts, award counts, opportunity volume, reporting behavior, eligibility requirements, grant descriptions, and temporal patterns across federal agencies.

## Analytical Direction
Each team member investigated a distinct dimension of the dataset to surface emerging patterns:

1. Identification of agency funding strategy profiles (Allison) - K-Means clustering revealed four distinct agency archetypes based on funding scale, opportunity volume, and award distribution
2. Detection of eligibility and program archetypes (Sambisha) - K-Modes clustering identified three eligibility patterns: broad institutional, minimal/unspecified, and fully unrestricted
3. Exploration of temporal shifts in federal grant activity (Anna) - K-Prototypes clustering uncovered distinct policy eras reflecting modern science/environment expansion, established health programs, and pre-2018 baseline patterns
4. Text-based similarity analysis across grant descriptions (Maggie) - Sentence transformer embeddings + K-Means revealed meaningful sub-topics within broad categories like health, science, and education
Together, these analyses aim to build a multi-dimensional understanding of how federal funding is structured.

## M3 Integration Insights

- High Opportunity Agencies declined from 84% to 74% post-2018, revealing a shift from broad distribution toward concentrated investment
- Volume focused agencies allow 9.04 eligibility types on average versus 1.48 for concentrated funders, demonstrating that broad access pairs with high grant volume
- High Funding Agencies concentrate on defense and infrastructure while High Opportunity Agencies prioritize health and education
- Clinical trials surged in 2020 and dominated by 2022, while climate change grants maintained continuous presence (2004–2023)
- Temporal eras, agency strategies, eligibility requirements, and topic distributions co-evolved rather than operating independently

Together, these analyses build a multi-dimensional understanding of how federal funding is structured across time, topic, agency behavior, and applicant accessibility.

