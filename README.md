# BA820_Team11_MLProject
This repository contains our BA820 team project focused on applying unsupervised machine learning techniques to uncover hidden patterns within U.S. federal grant data. Rather than beginning with predefined labels, our goal is to identify natural groupings that provide insight into how agencies structure funding, allocate resources, and support programs.

## Current Project Status
Phase 4 - Individual Refinement

After our team integrated our first attempts at clustering in M3, we are now conducting individual work to attempt different methods and changes to ensure that our unuspervised ML clusters are robust, make sense, and are improved upon.

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

## M4 Refinement & Validation

In Phase 4, team members refined their individual analyses to strengthen the reliability, interpretability, and credibility of the project’s findings. This included testing robustness across model choices and parameters, comparing alternative methods, and evaluating whether the patterns identified in earlier milestones remained consistent under different analytical assumptions. These refinements helped confirm that the clusters and archetypes reflect meaningful structure rather than artifacts of specific modeling decisions.

Across agency strategy profiles, eligibility patterns, temporal eras, and topic groupings, the results remained broadly consistent while also revealing important nuances — such as potential sub-types within larger groups and areas where boundaries are less distinct. Together, these refinements improve confidence in the project’s conclusions and highlight opportunities for future exploration.

