# ATRA-AIVC-Engineering-Platform-2025-SYPHU-CHINA-iGEM
This repository provides an interactive web-based platform developed using `Streamlit` for visualizing and analyzing research related to **AIVC-Engineered Bacterial Systems** used in **Targeted Cancer Therapy**. The platform integrates **virtual cell simulation**, **engineering biology**, and **experimental validation** for a comprehensive assessment of synthetic biology applications in precision oncology.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Features](#features)
4. [Technical Overview](#technical-overview)
5. [Research Protocol](#research-protocol)
6. [Data Analysis](#data-analysis)
7. [Contributing](#contributing)
8. [Licenses and Acknowledgements](#licenses-and-acknowledgements)

## Installation

### Prerequisites

To run the project locally, ensure you have Python 3.7+ and the necessary libraries installed. You can use the following command to install the required dependencies:

```bash
pip install -r requirements.txt
```

Where the `requirements.txt` should include the following libraries:

- `streamlit`
- `pandas`
- `plotly`
- `numpy`
- `datetime`
- `json`
- `base64`

These libraries are essential for the functionality and visualization capabilities of the platform.

## Usage

To launch the platform locally, run the following command in your terminal:

```bash
streamlit run main.py
```

This will start the server, and you can access the platform by navigating to `http://localhost:8501` in your web browser.

### Features

1. **Interactive Web Interface**:
   - Dynamic content updates based on user input.
   - Multiple sections for research overview, methodology, results, and discussion.
   - Customizable data input for AIVC simulation and experimental conditions.

2. **Data Visualization**:
   - Graphical representations using `Plotly` for simulation outcomes and experimental data.
   - Radar charts, bar charts, time series, and heatmaps to analyze data from multiple perspectives.
   - Real-time interactive charts for parameter tuning.

3. **Progress Tracking**:
   - A visual progress bar and section tracker display the user's current section in the research process.
   - Each section provides detailed content and interactive forms to gather data and analyze results.

4. **Research Team Information**:
   - An input form to capture team affiliation and corresponding author information.
   - Live metrics display for ongoing assessments and activities.

5. **Model Simulation**:
   - Users can interact with parameters such as cell population size, temporal resolution, and spatial dimensions for AIVC simulations.
   - Visualizations show bacterial growth and metabolite concentration over time.

6. **Genetic Circuit Design**:
   - The platform allows users to explore genetic circuit components such as promoters, RBS, and terminators using scatter plots that show their complexity, stability, and size.

7. **Statistical Analysis**:
   - Users can calculate statistical power analysis based on experimental designs, adjusting parameters like sample size, α-level, and power.

8. **Experimental Validation**:
   - Simulated experimental data allows for real-time analysis of cell viability, apoptosis rates, and other metrics across different conditions.

## Technical Overview

### Libraries and Technologies Used:

- **Streamlit**: A Python library for creating interactive web apps, particularly for data science and machine learning models. It is used here to create the research portal interface.
- **Plotly**: A graphing library for creating interactive plots and visualizations. It is used to render dynamic charts such as radar charts, bar plots, and heatmaps.
- **Pandas**: For data manipulation and analysis, particularly for handling the experimental data used in visualizations.
- **Numpy**: For mathematical operations, especially in simulation calculations like bacterial growth and metabolite concentration.
- **Datetime**: For handling time-related data in the simulation.
- **JSON/Base64**: For encoding and managing data efficiently.

### Page Layout & Design:

The layout is divided into different sections representing various stages of the research:

1. **Header Section**: A dynamic header introduces the research project and provides quick links to important research themes.
2. **Sidebar**: Provides additional navigation, team information, and dynamic research metrics.
3. **Interactive Forms**: Used to collect data from users (e.g., research hypothesis, anticipated contributions, validation methods).
4. **Data Visualizations**: Multi-tab layouts with interactive graphs for users to explore results across multiple categories.

### Research Sections:

1. **Study Overview & Hypothesis**: The initial section provides context for the research, including the primary research gap and the central hypothesis. Users can select gaps and provide their hypothesis in an interactive form.
2. **Methodology & Technical Framework**: In this section, users can interact with parameters related to the AIVC simulation, genetic circuit design, and experimental validation. This section allows parameter tuning in real-time.
3. **Results & Data Analysis**: Here, users can explore the computational results and experimental validation data. Interactive visualizations such as bar charts and radar charts are used to present the findings.
4. **Discussion**: The final section where users can interpret findings, discuss limitations, and propose future directions. It concludes the assessment with a thank you note.

## Data Analysis

### Key Visualizations:

- **Growth and Metabolite Production**: Time series visualization to track bacterial growth and ATRA concentration over time.
- **Tumor Microenvironment**: A heatmap to show spatial distribution in a tumor model.
- **Therapeutic Efficacy**: Bar charts for comparing cell viability and apoptosis rates across experimental conditions.
- **Comparative Analysis**: Radar charts to compare the performance of different methods (e.g., AIVC-Optimized vs. Conventional vs. Random Mutagenesis).

## Contributing

We welcome contributions from the community to further enhance the platform's capabilities. If you are interested in contributing, please fork the repository, create a feature branch, and submit a pull request with clear documentation on the changes made.

## Licenses and Acknowledgements

This project is supported by computational resources from the Virtual Cell Consortium and synthetic biology facilities.

Suggested Citation:  
Research Team. (2025). "AIVC-Engineered Bacterial Systems for Targeted Cancer Therapy". *Nature Cell Systems*.

Acknowledgments:  
We thank the contributors to synthetic biology and computational tools that helped make this project possible.
