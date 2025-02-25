# Mini Research Project: Dictionary Generation Pipeline

## Overview
This project focuses on building a simple pipeline for dictionary generation using a chosen text corpus. The goal is to track specific vocabulary types and analyze their distributions across different metadata sub-groups. The pipeline follows a structured process, including data collection, cleaning, methodology development, implementation, and analysis.

## Project Steps

### Part 1: Getting Main Text Data
1. **Select a Corpus**: Choose a dataset that covers diverse topics. Possible sources include class corpora, Kaggle, Google Books, or web-scraped text.
2. **Clean and Explore the Data**: Preprocess the text and understand its structure. Summarize the text metadata (e.g., by category, over time) and display sample text.

### Part 2: Develop Methodology
3. **Understand Dictionary Methods**: Utilize techniques like Tf-idf to generate dictionaries, referring to works like Gentzkow and Shapiro (2010) and Hassan et al. (2019).
4. **Define Content Categories**: Identify at least two distinct text types to generate dictionaries. Avoid predefined labels (e.g., political parties) and instead categorize by text type.
5. **Set Research Questions**: Define why tracking the selected vocabulary matters and what insights it can provide.

### Part 3: Implementation
6. **Generate Dictionaries**: Construct vocabulary lists and present them in a structured table. Justify why they align with the intended categorization.
7. **Analyze Dictionary Distributions**: Visualize dictionary counts across the corpus and by metadata sub-groups.
8. **Answer Research Questions**: Use dictionary counts to extract meaningful insights and validate initial expectations.

## Requirements
- Python (recommended: Jupyter Notebook for analysis)
- Libraries: `pandas`, `numpy`, `nltk`, `scikit-learn`, `matplotlib`, `seaborn`

## Usage
1. Obtain and preprocess the dataset.
2. Define dictionary categories and generate word lists using statistical methods.
3. Perform analysis and visualize results.
4. Interpret findings and answer research questions.

## Notes
- The complexity of the analysis can be adjusted based on time constraints.
- If results are not as expected, document the challenges and possible refinements.

## References
- Gentzkow, M., & Shapiro, J. M. (2010). Measuring Media Bias.
- Hassan, T. A., et al. (2019). The Information Environment and the Stock Market.
- Garcia-Uribe, D. (2024). Text Analysis in Economics and Social Sciences.