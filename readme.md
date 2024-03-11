# Phase-3-project
![Alt text](<water-780x470.jpg>)

## Moringa Phase 3 Project Submission

#### Student Project:
- Student name: Pete Njagi


Scheduled project review date/time: March 10th 2024

# Tanzania Water Wells AI Model Prediction Project
#### Important Project Files:

1. index.ipynb (Main Juypter document)
2. Presentation.pdf (Presentation)
3. TrainingSetValues.csv (Main Data) TestSetValues.csv
4. Optional Project Pdf

## Business Problem

# DrivenData-PumpItUp

This repository contains Python code for the [Pump it Up: Data Mining the Water Table](http://www.drivendata.org/competitions/7/) competition on [Driven Data](http://www.drivendata.org).

The data is provided by [Taarifa](http://taarifa.org) and the [Tanzanian Ministry of Water](http://maji.go.tz). The goal is to predict whether a water pump is functional, functional but needs repairs or non functional.

Sign up at Driven Data to download the following files:

* `SubmissionFormat.csv`
* `TestSetValues.csv`
* `TrainingSetLabels.csv`
* `TrainingSetValues.csv`

# Tanzania Water Wells Project

## Overview

The aim of this project is to deploy machine learning techniques to ascertain the functionality of water wells across Tanzania. The initiative is set to impact resource allocation for water well maintenance and guide the strategic planning for the establishment of new wells. We explore various factors, including geographic, hydrological, and infrastructural attributes, to predict the operational status of water pumps, classified into 'functional', 'non-functional', or 'functional needs repair'.

## Business Stakeholders

This project is crucial for the following stakeholders:

- **Blue Life NGO**: Concentrating on the maintenance and repair scheduling of water wells.
- **Government of Tanzania**: Enhancing the governance and administration of public water resources.
- **Local Communities**: Relying on consistent functionality of water wells for their daily needs.
- **International Aid Organizations**: Providing financial and logistical assistance for water infrastructure.
- **Public Health Authorities**: Monitoring the connection between water access and community health.
- **Environmental Conservationists**: Observing the effects of well placement and usage on the ecosystem.

## Business Objective

We are dedicated to:

- Developing a predictive model to anticipate the service status of water wells.
- Informing the selection of sites for constructing new wells grounded on historical data.
- Enabling stakeholders to make informed decisions bolstered by data analysis.
- Improving the efficiency and effectiveness of water well repair and maintenance.
- Elevating community health standards through improved water access.
- Fostering global partnership for sustainable water resource management.

## Hypotheses

We explore the following hypotheses:

i. **Water Quality vs. Well Functionality**:
   - H0: Water quality does not significantly affect well functionality.
   - H1: Wells with substandard water quality are likely to be non-functional.

ii. **Geographic Influence on Well Status**:
    - H0: There is no significant geographic impact on well functionality.
    - H1: Certain regions have a higher tendency of wells being non-functional or requiring repair.

iii. **Impact of Installation Entity on Well Longevity**:
    - H0: The installer's identity does not significantly affect well longevity.
    - H1: Wells installed by particular entities show higher rates of functionality.

## Data Understanding

The data for this analysis comes from two main datasets:

- **WaterPoint Data Exchange (WPDx)**: Housing detailed reports on the functionality of water wells in Tanzania.
- **Tanzania Ministry of Water**: Providing comprehensive data on water infrastructure and related services.

### Univariate Analysis

Focal points of our analysis:

- `water_quantity` and `water_quality`: Directly linked to the functionality classification.
- `funder` and `installer`: Offering potential insights into well success based on the installing entity.
- `basin`: Serving as a categorical variable that could influence the functionality.

## Regression Analysis

Utilizing the Random Forest model to understand the multifaceted influences on the likelihood of well failure, informing proactive maintenance and intelligent construction design.


### Data Visualizations
<img src="/images/1.png" alt="drawing" width="500"/>

<img src="/images/2.png" alt="drawing" width="500"/>

<img src="/images/3.png" alt="drawing" width="500"/>

<img src="/images/4.png" alt="drawing" width="500"/>

<img src="/images/5.png" alt="drawing" width="500"/>

<img src="/images/6.png" alt="drawing" width="500"/>

<img src="/images/7.png" alt="drawing" width="500"/>



## Setup for Jupyter Notebook

To set up a Jupyter Notebook for analyzing the data:

1. Install Anaconda which includes Jupyter Notebook, Python, and other data science packages. Visit [Anaconda's website](https://www.anaconda.com/products/distribution) and download the installer for your operating system.
2. After installation, launch Anaconda Navigator and start Jupyter Notebook, or open a terminal (or command prompt) and type `jupyter notebook` to start the Jupyter Notebook server.
3. Create a new Python notebook from the Jupyter dashboard.
4. Import the required libraries (e.g., pandas, matplotlib, seaborn, Statsmodels) at the beginning of your notebook.
5. Load your dataset using pandas, for example: `df = pd.read_csv('path_to_your_data.csv')`.
6. Proceed with your data analysis and visualization.

For more detailed instructions, you can refer to the [official Jupyter documentation](https://jupyter.readthedocs.io/en/latest/).


