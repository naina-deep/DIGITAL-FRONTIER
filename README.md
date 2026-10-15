# 🌐 DIGITAL FRONTIER
### 📊 Measuring Digital Development Across Economies

**An Interactive Business Analytics Project Using Microsoft Power BI and the ICT Development Index (IDI) 2026**

<p align="center">
  <strong>Exploring digital connectivity, regional disparities, and the relationship between income and digital development.</strong>
</p>

---

## 📖 About the Project

In an increasingly connected world, access to digital technologies plays an important role in communication, education, economic participation, and access to information. However, the benefits of digital development are not distributed equally across the world.

**DIGITAL FRONTIER** is a data analytics and visualisation project that examines differences in digital development across economies using the **ICT Development Index (IDI) 2026**, published by the International Telecommunication Union (ITU).

The project transforms structured ICT data into an interactive Power BI dashboard, enabling users to explore regional performance, compare income groups, and examine differences in digital connectivity.

Through descriptive analytics and data storytelling, the project aims to make complex data easier to understand and turn numerical comparisons into meaningful observations.

> 🎯 **Core Objective:** To analyse digital-development disparities across economies and communicate the findings through interactive, data-driven visualisations.

## 🎯 Project Objectives

The project focuses on the following objectives:

- 🌍 **Regional Analysis:** Compare average IDI scores across six geographical regions.
- 💰 **Income-Based Comparison:** Examine differences in digital development across income classifications.
- 📈 **Performance Measurement:** Summarise key indicators using dashboard KPI cards.
- 🔎 **Disparity Identification:** Highlight differences in digital-development outcomes between groups.
- 🔗 **Relationship Exploration:** Investigate the association between income classification and IDI scores.
- 📊 **Interactive Visualisation:** Present the findings through a structured Power BI dashboard.
- 💡 **Data Storytelling:** Translate analytical results into clear, accessible insights.

## ❓ Research Questions

The analysis is guided by the following questions:

1. What is the overall level of digital development represented in the project dataset?
2. How do average IDI scores differ across geographical regions?
3. How does digital development vary among income groups?
4. Which regions record the highest and lowest average IDI scores?
5. What patterns can be observed between income classification and digital development?
6. How can data visualisation make these differences easier to interpret?

## 📂 Dataset Overview

The project uses a cleaned dataset derived from the International Telecommunication Union's ICT Development Index 2026 resources.

| Dataset Detail | Description |
|---|---|
| 📌 Dataset | `IDI2026_Clean.csv` |
| 🌍 Economies Analysed | 158 |
| 🗺️ Geographical Groups | 6 ITU regions |
| 💰 Income Classification | 4 income groups |
| 📊 Analysis Type | Descriptive analytics |
| 📈 Visualisation Tool | Microsoft Power BI |

**Note:** The 158 economies represent the dataset used in this project, not necessarily the full coverage of the official ITU publication.

### 🔑 Key Variables

The dataset includes information relating to:

| Category | Variables and Indicators |
|---|---|
| 🌍 Economy Information | Economy name, ISO3 code, ITU region |
| 💰 Economic Classification | World Bank income group |
| 🌐 Internet Access | Internet users and household internet access |
| 📱 Mobile Connectivity | Mobile phone ownership and mobile broadband subscriptions |
| 📶 Network Infrastructure | 3G and 4G/LTE coverage |
| 📊 Data Usage | Mobile and fixed broadband traffic |
| 💵 Affordability | Broadband affordability indicators |
| 🔗 Connectivity Measures | Universal Connectivity and Meaningful Connectivity pillar scores |
| 🏆 Development Outcomes | ICT Development Index score and rank |

Some indicator variables contain missing observations. These are important to consider when interpreting the results of individual analyses.

### 🔗 Official Data Source

**International Telecommunication Union (ITU)**

The ITU publishes the ICT Development Index as a tool for assessing and comparing digital development across economies.

- 📚 [Official ICT Development Index 2026 Report](https://www.itu.int/itu-d/reports/statistics/IDI2026/)
- 🌐 [International Telecommunication Union](https://www.itu.int/)

## 🛠️ Tools and Technologies

| Tool | Application in the Project |
|---|---|
| 📊 Microsoft Power BI | Dashboard creation, visual analytics, and presentation of findings |
| 📑 Microsoft Excel | Data inspection and preparation |
| 🗃️ CSV | Storage and exchange of the cleaned dataset |
| 🐙 GitHub | Project hosting, documentation, and version control |

## ⚙️ Project Methodology

The project follows a structured workflow to convert the source data into meaningful analytical outputs.

### 1. 📥 Data Collection

The project uses ICT Development Index resources published by the International Telecommunication Union.

### 2. 🧹 Data Preparation

The dataset is inspected to identify relevant variables for regional, income-group, and connectivity analysis.

### 3. 🔧 Data Cleaning

Relevant columns are selected, unnecessary fields are removed where appropriate, and the data is prepared for analysis. Missing observations in indicator variables are considered when interpreting results.

### 4. 🔍 Exploratory Data Analysis

The prepared data is examined to understand the distribution of IDI scores and identify differences across regions and income classifications.

### 5. 📊 Dashboard Development

Microsoft Power BI is used to present the analysis through KPI cards, comparative charts, a regional distribution pie chart, and other dashboard elements.

### 6. 💡 Insight Generation

The visualisations are interpreted to identify key patterns, compare group-level performance, and communicate digital-development disparities.

### 7. 📢 Presentation and Documentation

The findings are documented in the project presentation and GitHub repository to make the analytical workflow and results accessible.

## 📊 Power BI Dashboard

The **DIGITAL FRONTIER dashboard** presents a consolidated view of digital development across the economies included in the analysis.

### 📌 1. Key Performance Indicators

KPI cards provide a high-level overview of the analysis, including:

- Average IDI score
- Highest observed IDI score
- Lowest-score indicator, subject to validation against the prepared dataset
- Number of economies analysed

These indicators allow viewers to understand the overall dataset before exploring individual comparisons.

### 🌍 2. Regional Performance Analysis

The regional comparison examines average IDI scores across six ITU regions.

It helps identify which regions have higher or lower average scores and quantify the differences between them.

### 💰 3. Income Group Analysis

The income-group comparison examines average IDI scores across high-income, upper-middle-income, lower-middle-income, and low-income economies.

It provides a structured way to explore how digital-development outcomes differ across income classifications.

### 🥧 4. Regional Sample Distribution

The pie chart illustrates how the 158 economies are distributed across the six regions.

It represents the **composition of the dataset**, rather than the digital-development performance of each region.

### 🔗 5. Correlation Analysis

The dashboard explores the association between income classification and IDI scores.

Correlation can help describe a statistical relationship between variables, but it does not establish causation. Any reported coefficient should be interpreted according to the variables, encoding, and observations used in its calculation.

### 🎛️ 6. Interactive Exploration

Dashboard filters, where implemented, allow users to focus on selected categories and explore the data from different perspectives.

## 🔍 Key Findings

The following findings are based on the project's analysis-ready dataset.

### 🌐 1. Overall Digital Development

The average IDI score across the 158 economies analysed is approximately **62.62**.

This provides an overall summary of the scores represented in the project dataset. However, the global average alone cannot explain how digital development varies between individual economies.

### 🌍 2. Regional Comparison

| Region | Average IDI Score |
|---|---:|
| 🇪🇺 Europe | 76.81 |
| 🌏 Asia-Pacific | 67.82 |
| 🌐 CIS | 65.75 |
| 🌎 Americas | 57.45 |
| 🕌 Arab States | 56.36 |
| 🌍 Africa | 45.45 |

**Key Insight:** Europe records the highest regional average at **76.81**, while Africa records the lowest at **45.45**.

The difference between these two averages is **31.36 points**, indicating a substantial gap in regional average performance.

These are group averages; they do not imply that every economy within one region performs better than every economy in another.

### 💰 3. Income Group Comparison

| Income Group | Average IDI Score |
|---|---:|
| High income | 80.55 |
| Upper-middle income | 64.66 |
| Lower-middle income | 47.60 |
| Low income | 28.38 |

**Key Insight:** High-income economies record an average score of **80.55**, compared with **28.38** for low-income economies.

The difference is approximately **52.17 points**.

The pattern suggests an association between income classification and digital development. However, the descriptive comparison does not establish that income alone causes higher digital-development scores.

### 🗺️ 4. Regional Representation

The project dataset contains economies from six ITU regions.

| Region | Number of Economies | Share of Dataset |
|---|---:|---:|
| Europe | 43 | 27.2% |
| Africa | 32 | 20.3% |
| Asia-Pacific | 31 | 19.6% |
| Americas | 26 | 16.5% |
| Arab States | 18 | 11.4% |
| CIS | 8 | 5.1% |
| **Total** | **158** | **100%** |

**Key Insight:** Europe contributes the largest number of economies, while CIS contributes the smallest number.

The number of observations differs between regions, which is relevant when interpreting regional comparisons and understanding the composition of the dataset.

## 💡 Why These Findings Matter

The analysis highlights several important observations:

- 🌍 **Digital development is uneven:** Regional averages differ considerably.
- 💰 **Income groups show different outcomes:** Average IDI scores vary substantially across income classifications.
- 📊 **Context matters:** A global average does not capture all regional and economic differences.
- 🔎 **Visualisation improves interpretation:** Comparative charts make differences easier to identify.
- ⚖️ **Results require careful interpretation:** Group averages, missing values, and sample composition influence how findings should be understood.

These observations describe patterns in the prepared dataset; they should not be treated as proof of causal relationships.

## ⚠️ Limitations of the Analysis

Every analytical project has limitations. The following considerations apply to DIGITAL FRONTIER:

- **Dataset coverage:** The project analyses 158 economies, which should not be confused with the full coverage of the official ITU publication.
- **Missing observations:** Some indicator variables contain missing values.
- **Group-level comparisons:** Regional and income-group averages can conceal differences between individual economies.
- **Descriptive approach:** The analysis identifies patterns but does not establish causal relationships.
- **Correlation interpretation:** Results depend on the selected variables, encoding, and paired observations.
- **Sample composition:** Unequal regional representation should be considered when interpreting the comparisons.
- **Indicator definitions:** The findings depend on the definitions and coverage of the source data.

Acknowledging these limitations helps ensure that the findings are interpreted responsibly.

## 📁 Repository Structure

The repository contains the following project files:

| File | Description |
|---|---|
| `DIGITAL FRONTIERS.pbix` | Interactive Power BI dashboard |
| `DIGITAL FRONTIERS.png` | Dashboard preview image |
| `DIGITAL FRONTIERS PPTX.pptx` | Project presentation |
| `IDI2026_Clean.csv` | Cleaned dataset used in the analysis |
| `README.md` | Project overview and documentation |

## 🚀 How to Explore the Project

1. 📥 Download or clone this repository.
2. 📊 Open `DIGITAL FRONTIERS.pbix` using Microsoft Power BI Desktop.
3. 🗃️ If prompted, connect the report to `IDI2026_Clean.csv` and verify the data source path.
4. 🎛️ Explore the dashboard visuals and available filters.
5. 📈 Review the project presentation for additional explanations and interpretations.

**Note:** The dashboard may require its data-source path to be updated on another computer.

## 🏁 Conclusion

**DIGITAL FRONTIER** demonstrates the practical application of descriptive analytics and data visualisation to the study of digital development across economies.

By examining average IDI scores across geographical regions and income groups, the project identifies substantial differences in digital-development outcomes. The analysis also demonstrates why regional representation, missing observations, and the distinction between correlation and causation matter when interpreting results.

Through Microsoft Power BI, the project transforms a structured dataset into a visual and accessible analytical resource. Through GitHub, the project documents its dataset, methodology, findings, and supporting files in one repository.

Overall, the project brings together data preparation, exploratory analysis, visualisation, interpretation, and technical documentation within a Business Analytics workflow.

## 👩‍💻 Author

**Nainadeep Kaur**  
🎓 BBA in Business Analytics  
🏛️ Babu Banarasi Das University

## 🙏 Acknowledgements

This project uses resources published by the **International Telecommunication Union (ITU)** for the ICT Development Index 2026.

Thank you to the organisations and data publishers whose work supports research and learning in digital development and connectivity.

## 📜 Disclaimer

This repository presents an academic Business Analytics project. The findings are based on the prepared dataset and the analyses performed for this project. They should not be interpreted as official rankings, endorsements, or conclusions issued by the International Telecommunication Union.

---

<p align="center">
  <strong> DIGITAL FRONTIER | Data • Connectivity • Insights </strong>
  <br>
  <em>Turning digital-development data into meaningful insights.</em>
</p>
