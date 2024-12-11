# Exercise 2: CRISP-DM Analysis of Movies Dataset

## Overview

This analysis applies the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology to explore collaboration patterns among actors in the Movies dataset. The goal is to identify communities of actors who frequently collaborate with each other in the same movies. The analysis is based on a graph representation of actors and their collaborations.

## CRISP-DM Phases

### 1. Business Understanding
The primary goal of this analysis is to detect collaboration patterns among actors. By identifying communities of frequently collaborating actors, insights can be drawn for casting decisions, recommendation systems, and marketing strategies in the film industry.

### 2. Data Understanding
The dataset contains the following:
- **10 nodes** representing entities such as actors and movies.
- **10 relationships** representing collaborations between actors through shared movies.

A schema visualization of the dataset was created to ensure that the relationships accurately reflect the "ACTED_IN" association, confirming the dataset's suitability for community analysis.

### 3. Data Preparation
The dataset was verified for completeness, and it was confirmed that:
- 10 nodes (representing actors and movies) were correctly loaded.
- 10 relationships (representing collaborations) were correctly structured.

### 4. Modeling
A Cypher query was used to detect communities by grouping actors based on shared movie collaborations. The results revealed clusters of actors who frequently collaborated with one another. For example:
- **Actor A** frequently collaborated with **Actor B** and **Actor C**, forming a community.

### 5. Evaluation
The detected communities provide valuable insights into collaboration patterns, helping to identify actors who work together most often. This can be useful for:
- **Casting decisions**: Suggesting actors who could be paired in future films.
- **Recommendation systems**: Suggesting movies featuring actors who frequently collaborate.

### 6. Deployment
The insights from this analysis can be applied in various real-world AI contexts, including:
- **Recommendation Systems**: Suggesting actors for future collaborations based on detected communities.
- **Content Analysis**: Identifying trends in actor collaborations for targeted marketing or casting.

## Conclusion

This report demonstrates the effectiveness of graph-based methods in uncovering meaningful patterns in actor collaborations. The insights derived from the Movies dataset can help optimize casting decisions and enhance recommendation systems in the entertainment industry.

## Technologies Used

- Python (for data analysis)
- Neo4j and Cypher (for graph analysis and community detection)
- NetworkX (for graph-related calculations)
- Pandas (for dataset manipulation)
- Matplotlib (for visualization)

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/DBEST-EZRA/Crisp_Dm_Analysis.git
