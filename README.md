# DIGITAL-FRONTIER
Power BI project analysing the ICT Development Index (IDI) 2026 to explore digital development gaps across economies, regions, and income groups through interactive data visualisation.


# DIGITAL FRONTIER
### Measuring Digital Development Across Economies

**A Business Analytics Project Using Power BI and the ICT Development Index (IDI) 2026**

## Project Overview

Digital connectivity has become an important factor in economic participation, access to information, and technological development. However, the level of digital development varies across economies due to differences in infrastructure, affordability, internet access, and socioeconomic conditions.

**DIGITAL FRONTIER** is a data analytics and visualisation project that examines digital development across economies using the ICT Development Index (IDI) 2026. The project uses data analysis and interactive Power BI visualisations to explore regional disparities, compare income groups, and identify patterns in digital connectivity.

The objective is to transform a complex dataset into meaningful insights that support a clearer understanding of global digital development.

## Project Objectives

- Analyse ICT Development Index scores across economies.
- Compare digital development across geographical regions.
- Examine differences in IDI performance among World Bank income groups.
- Identify disparities in digital connectivity and development.
- Present key findings through an interactive Power BI dashboard.
- Communicate analytical results using data visualisation and descriptive statistics.

## Dataset

The project uses a cleaned dataset derived from the International Telecommunication Union's ICT Development Index 2026 resources.

The analysis-ready dataset used in this project contains **158 economies**.

### Key Variables

The dataset includes variables relating to:

- Economy and ISO country codes
- ITU geographical regions
- World Bank income groups
- Internet usage and household internet access
- Mobile phone ownership
- Mobile broadband subscriptions
- 3G and 4G/LTE network coverage
- Mobile and fixed broadband traffic
- Broadband affordability indicators
- Universal Connectivity Pillar Score
- Meaningful Connectivity Pillar Score
- ICT Development Index score and rank

Some indicator fields may contain missing observations. The analysis should therefore be interpreted in the context of the available data.

### Data Source

International Telecommunication Union (ITU)

[ICT Development Index 2026 — Official Source](https://www.itu.int/itu-d/reports/statistics/IDI2026/)

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI | Dashboard development and data visualisation |
| Microsoft Excel | Data inspection and preparation |
| CSV | Storage and exchange of the cleaned dataset |
| GitHub | Project documentation, file organisation, and version control |

## Methodology

The project follows a structured descriptive analytics workflow.

1. **Data Collection:** Obtain the relevant ICT Development Index dataset from the ITU's published resources.
2. **Data Preparation:** Inspect the dataset, select relevant variables, and prepare the data for analysis.
3. **Data Cleaning:** Review missing values, remove unnecessary fields where appropriate, and organise the dataset for visualisation.
4. **Exploratory Analysis:** Examine IDI scores across geographical regions and income classifications.
5. **Dashboard Development:** Build a Power BI dashboard using summary indicators and comparative visualisations.
6. **Interpretation:** Identify patterns and disparities while considering the limitations of the dataset.

## Dashboard and Visualisations

The Power BI dashboard presents an overview of digital development across the economies included in the analysis.

The dashboard incorporates the following analytical elements:

- **KPI Cards:** Summarise key indicators, including the average and highest observed IDI scores and the number of economies analysed.
- **Regional Comparison:** Compare average IDI scores across ITU geographical regions.
- **Income Group Analysis:** Examine differences in average IDI scores across income classifications.
- **Pie Chart:** Illustrate the distribution of economies across the geographical regions represented in the dataset.
- **Correlation Analysis:** Explore the association between income classification and digital development.
- **Interactive Filters:** Support focused exploration of the available categories, where implemented in the dashboard.

Each visualisation serves a distinct analytical purpose, from summarising overall performance to examining differences between groups.

## Key Findings

The following findings are based on the project's analysis-ready dataset.

### 1. Overall Digital Development

The average ICT Development Index score across the 158 economies in the project dataset is approximately **62.62**. This provides a summary of the digital development represented in the sample.

### 2. Regional Differences

The regional averages indicate substantial differences in digital development.

| Region | Average IDI Score |
|---|---:|
| Europe | 76.81 |
| Asia-Pacific | 67.82 |
| CIS | 65.75 |
| Americas | 57.45 |
| Arab States | 56.36 |
| Africa | 45.45 |

Europe records the highest regional average, while Africa records the lowest. The difference between these averages is 31.36 points.

### 3. Income Group Differences

| Income Group | Average IDI Score |
|---|---:|
| High income | 80.55 |
| Upper-middle income | 64.66 |
| Lower-middle income | 47.60 |
| Low income | 28.38 |

The analysis shows a substantial difference between high-income and low-income groups. Their average scores differ by approximately 52.17 points.

These group-level results indicate an association between income classification and digital development. They do not, by themselves, establish a causal relationship.

### 4. Regional Sample Distribution

The dataset contains economies from six ITU geographical regions. Europe contributes the largest number of observations, while the CIS region contributes the smallest number.

This distribution is relevant when interpreting regional comparisons because the number of economies represented differs between regions.

## Limitations

- The project analyses 158 economies in its prepared dataset; this should not be confused with the total coverage of the official ITU publication.
- Some indicator variables contain missing observations.
- Regional and income-group averages can conceal substantial differences between individual economies.
- The analysis is descriptive and does not establish causal relationships.
- Correlation results depend on the variables, encoding, and observations included in the calculation.
- The findings reflect the available dataset and its definitions.

## Repository Contents

| File | Description |
|---|---|
| `DIGITAL FRONTIERS.pbix` | Power BI dashboard file |
| `DIGITAL FRONTIERS.png` | Dashboard preview image |
| `DIGITAL FRONTIERS PPTX.pptx` | Project presentation |
| `IDI2026_Clean.csv` | Cleaned dataset used for analysis |
| `README.md` | Project overview, methodology, findings, and documentation |

## Conclusion

DIGITAL FRONTIER demonstrates how descriptive analytics and data visualisation can be used to examine differences in digital development across economies.

By comparing regional averages, income groups, and connectivity-related indicators, the project highlights disparities that may be overlooked when considering only a global summary.

The Power BI dashboard provides a structured and accessible way to explore the dataset and communicate its findings. The project also demonstrates the practical application of data preparation, analytical reasoning, visualisation, and documentation within a Business Analytics workflow.

## Author

**Nainadeep Kaur**  
BBA in Business Analytics  
Babu Banarasi Das University

## Acknowledgements

The project uses ICT Development Index resources published by the International Telecommunication Union (ITU).

**Disclaimer:** This project is an academic analytics exercise. The findings represent an analysis of the prepared dataset and should not be interpreted as official rankings or conclusions published by the author on behalf of the ITU.
