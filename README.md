# Xernian Army Defection Risk Predictor - Innov8: IIT Delhi PS

## Table of Contents
- [Xernian Army Defection Risk Predictor](#xernian-army-defection-risk-predictor)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Problem Statement](#problem-statement)
  - [Current Approaches to Traitor Detection](#current-approaches-to-traitor-detection)
  - [Our Solution](#our-solution)
  - [Pipeline Overview](#pipeline-overview)
  - [Key Features](#key-features)
  - [Notebook Structure](#notebook-structure)

## Introduction

In the ongoing conflict between the Xernians and the Phrygians, internal betrayal poses a significant threat to the Xernian army. This project aims to develop a sophisticated system for predicting and mitigating the risk of troop defection to the enemy side.

## Problem Statement

As the Xernian army prepares for an inevitable confrontation with the Phrygians, it faces a critical internal challenge: the potential betrayal of its soldiers. Historically, Phrygians have successfully lured Xernian troops with promises of wealth and power, leading to defections that have weakened the Xernian forces. The primary objective is to design and implement a decision-making system capable of:

1. Analyzing various factors that might influence a soldier's likelihood of betrayal
2. Predicting which soldiers are at the highest risk of defection
3. Providing actionable insights to prevent potential betrayals

## Current Approaches to Traitor Detection

Traditional methods of identifying potential traitors in military settings have often relied on:

1. **Background Checks**: Extensive investigations into a soldier's history, connections, and loyalties.
2. **Psychological Evaluations**: Regular assessments to gauge a soldier's mental state and commitment to the cause.
3. **Surveillance**: Monitoring of communications and activities, especially for high-risk individuals.
4. **Loyalty Tests**: Staged scenarios to test a soldier's reactions and decisions under pressure.
5. **Incentive Alignment**: Ensuring that soldiers' personal interests align with the army's goals.

However, these methods have limitations:
- They can be resource-intensive and time-consuming.
- They may not capture the dynamic nature of loyalty and risk.
- They often fail to consider the complex social dynamics within military units.
- They can create an atmosphere of distrust, potentially harming morale.

## Our Solution

Our approach addresses the limitations of traditional methods by implementing a multi-stage, data-driven risk assessment model. Key aspects of our solution include:

1. **Comprehensive Data Utilization**: We consider a wide range of factors, including personal attributes, social connections, and peer perceptions.

2. **Dynamic Risk Assessment**: Our model updates risk scores based on changing circumstances and social influences.

3. **Social Network Analysis**: We incorporate graph-based modeling to capture the impact of relationships on loyalty.

4. **Sentiment Analysis**: We use peer opinions to refine risk assessments, capturing subtle indicators of potential defection.

5. **Scalability**: Our system is designed to handle armies of various sizes efficiently.

6. **Ethical Considerations**: We've built in safeguards to ensure fair and unbiased assessments.

## Pipeline Overview

Our defection risk prediction pipeline consists of three main stages:

1. **Initial Risk Assessment**
   - Evaluates quantifiable attributes of each soldier
   - Generates an initial risk score based on personal and environmental factors

2. **Social Network Influence**
   - Models the army's social structure as a graph
   - Adjusts risk scores based on social connections and influences

3. **Peer Sentiment Analysis**
   - Incorporates opinions and sentiments expressed by fellow soldiers
   - Refines risk scores based on peer perceptions

## Key Features

- **Synthetic Data Generation**: Creates realistic soldier profiles and social networks
- **Multi-factor Risk Calculation**: Considers age, rank, salary, family ties, and more
- **Graph-based Social Modeling**: Captures complex relationships and hierarchies
- **Opinion Generation and Sentiment Analysis**: Simulates and analyzes peer perceptions
- **Visualization Tools**: Provides insights through various plots and network graphs
- **Scalable Architecture**: Efficiently handles large datasets with optimized algorithms
- **Adaptable Framework**: Allows for easy updates and additions to the risk model

## Notebook Structure

The entire project is contained within a single Jupyter notebook (`Xernian_Defection_Predictor.ipynb`). The notebook is structured into several key sections:

1. **Setup and Imports**: Initial cell(s) for importing necessary libraries and setting up the environment.

2. **Data Generation**:
   - Soldier profile creation
   - Social network generation

3. **Initial Risk Assessment**:
   - Feature engineering
   - Risk score calculation

4. **Social Network Influence**:
   - Graph creation and analysis
   - Risk score refinement based on social connections

5. **Peer Sentiment Analysis**:
   - Opinion generation
   - Sentiment-based risk adjustment

6. **Visualization and Analysis**:
   - Risk distribution plots
   - Network visualizations
   - Correlation analyses

7. **Model Evaluation and Insights**:
   - Performance metrics
   - Key findings and interpretations

8. **Conclusion and Future Work**:
   - Summary of results
   - Potential improvements and extensions

Each section contains detailed markdown explanations alongside the code, ensuring clarity and reproducibility.
