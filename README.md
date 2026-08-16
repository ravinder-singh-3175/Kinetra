# Mental Wellness & Nutrition Project

### Data-Driven Wellness Analysis for College Students

> **Temporary Project Name** — The final project name will be decided as the project develops.

---

## 1. Project Overview

The **Mental Wellness & Nutrition Project** is a semester-long Fundamentals of Data Science project focused on understanding wellness patterns among **college students**.

The project primarily investigates **mental wellness** and its relationships with important lifestyle factors, particularly:

* Nutrition and dietary habits
* Physical activity and mobility
* Sleep and daily routine
* Other relevant lifestyle and contextual factors available in the collected data

The project uses **primary survey data collected from college students**. Approximately 100 responses have currently been collected, providing an initial real-world dataset for analysis.

Rather than beginning with predetermined conclusions, the project will use Data Science and statistical techniques to investigate what patterns, relationships, and associations are actually supported by the collected data.

---

## 2. Problem Statement

College students often experience variations in mental wellness due to a combination of academic, social, behavioural, nutritional, and lifestyle factors.

Nutrition and physical activity are particularly important areas of interest because they form part of students' everyday lifestyles and may be associated with differences in mental wellness.

However, these relationships are complex and cannot be understood reliably through assumptions alone.

The central problem addressed by this project is therefore:

> **How can Data Science be used to analyze college students' mental wellness, nutrition intake, physical activity, and related lifestyle factors to discover meaningful patterns and support personalized wellness insights?**

The project will investigate associations present in the data without automatically interpreting those associations as causal relationships.

---

## 3. Core Project Domains

The project is organized around three closely connected domains.

### Mental Wellness

Mental wellness is the primary area of interest.

The project will analyze available self-reported wellness-related information to understand patterns and differences among college students.

The system is **not intended to diagnose mental-health disorders**.

### Nutrition Intake

Nutrition-related information will be analyzed to understand dietary behaviours and their relationships with mental wellness and other lifestyle characteristics.

The project may investigate patterns such as meal habits, dietary choices, hydration, and other nutrition-related factors represented in the collected survey data.

### Physical Activity and Mobility

Physical activity and mobility-related information will be used to understand students' movement and activity patterns and how they relate to mental wellness and nutrition.

---

## 4. Current Data Source

The initial dataset is being created through a questionnaire distributed among college students.

At present, approximately **100 responses** have been collected.

The survey contains questions related to areas such as:

* Mental wellness
* Nutrition and dietary habits
* Physical activity and mobility
* Lifestyle and routine
* Relevant demographic or contextual information

The exact variables, data types, and analytical roles of individual questions will be documented after the survey dataset is formally inspected and prepared.

Raw survey responses will be preserved separately from cleaned and processed versions of the dataset.

---

## 5. Data Science Approach

The project will progressively evolve alongside the **Fundamentals of Data Science** course.

Relevant concepts will be applied when they become appropriate to the project's current development stage.

The project is expected to explore areas including:

* Data Science methodologies and processes
* Data collection and data quality
* Probability and statistics
* Sampling and estimation
* Correlation and covariance
* Hypothesis testing
* ANOVA
* Data cleaning and preprocessing
* Exploratory Data Analysis
* Data visualization
* Data pipelines and transformation
* Feature engineering
* Supervised machine learning
* Unsupervised machine learning
* Clustering
* Dimensionality reduction
* Association rule mining
* Anomaly detection
* Model evaluation
* Recommendation systems
* DataOps and introductory MLOps concepts
* Statistical analysis using R

Not every technique will automatically become part of the final application. Multiple techniques may instead be experimentally compared and evaluated where appropriate.

---

## 6. Analytics Framework

The project will progressively demonstrate the four major types of analytics.

### Descriptive Analytics

**What is happening in the collected student data?**

Examples may include:

* Distribution of wellness-related responses
* Nutrition and dietary patterns
* Physical activity patterns
* Sleep and lifestyle characteristics
* Differences among groups represented in the dataset

### Diagnostic Analytics

**What factors or patterns are associated with the observations?**

Potential investigations may include:

* Nutrition habits and mental wellness
* Physical activity and mental wellness
* Sleep and mental wellness
* Relationships among nutrition, activity, and lifestyle characteristics

Observed associations will **not automatically be interpreted as causal relationships**.

### Predictive Analytics

**What meaningful outcomes can be predicted using the available information?**

Potential predictive targets will only be selected after the dataset has been explored and an appropriate problem has been identified.

The project will not prematurely select a machine-learning algorithm or prediction target.

### Prescriptive Analytics

**How can analytical findings eventually support useful wellness guidance?**

Later stages of the project may explore a recommendation mechanism that converts relevant analytical findings and user profiles into understandable, personalized general wellness insights.

---

## 7. Proposed High-Level System

```text
Student Wellness Information
          │
          ▼
Data Validation & Preparation
          │
          ▼
 ┌────────┼─────────┐
 ▼        ▼         ▼
Mental   Nutrition  Physical Activity
Wellness  Profile   / Mobility Profile
Profile
 └────────┼─────────┘
          ▼
Integrated Wellness Analysis
          │
          ▼
Statistical & Data Science Analysis
          │
          ▼
Pattern / Profile Identification
          │
          ▼
Explainable Wellness Insights
          │
          ▼
Personalized General Wellness Guidance
```

This architecture represents the current project direction and may evolve as additional Data Science concepts are learned and the dataset is better understood.

---

## 8. Planned Development

The project will be developed progressively throughout the semester.

```text
Project Redefinition
        ↓
Survey & Data Understanding
        ↓
Data Documentation
        ↓
Data Cleaning and Preparation
        ↓
Exploratory Data Analysis
        ↓
Probability & Statistical Analysis
        ↓
Data Engineering
        ↓
Feature Engineering
        ↓
Machine Learning Experiments
        ↓
Clustering & Profile Discovery
        ↓
Advanced Data Analysis
        ↓
Recommendation System
        ↓
Application Development
        ↓
Evaluation & Final Documentation
```

The project's GitHub history will reflect this progression rather than presenting the final system as if it were developed all at once.

---

## 9. Current Status

### Project Redefinition & Data Collection Stage

The project has recently evolved from its original movement/pain-oriented concept into a broader college-student wellness project centered on:

* Mental wellness
* Nutrition intake
* Physical activity and mobility

Current progress includes:

* Revised problem domain identified
* College students selected as the target population
* Survey questionnaire prepared
* Approximately 100 responses collected
* Initial Data Science project structure established
* Future development aligned with the FDS course progression

The collected dataset has **not yet been formally cleaned, analyzed, modeled, or used to generate conclusions**.

No machine-learning results are being claimed at this stage.

---

## 10. Safety and Ethical Boundaries

This project is being developed as an **educational Data Science and general wellness project**.

It is not intended to:

* Diagnose depression, anxiety, or other mental-health conditions
* Diagnose nutritional deficiencies or eating disorders
* Provide psychological or psychiatric treatment
* Prescribe medication
* Provide medical nutrition therapy or therapeutic diets
* Replace qualified healthcare or mental-health professionals
* Treat statistical associations as proof of causation
* Present machine-learning predictions as medical diagnoses

Survey data should be handled responsibly, with appropriate attention to privacy, anonymization, and ethical use.

Any future recommendations will be limited to **general educational and wellness-oriented guidance**.

---

## 11. Repository Structure

```text
Mental-Wellness-Nutrition-Project/
│
├── README.md
│
├── docs/
│   ├── 01_problem_definition.md
│   ├── 02_project_objectives.md
│   ├── 03_data_science_process.md
│   ├── 04_analytics_approach.md
│   ├── 05_project_scope.md
│   └── 06_challenges.md
│
├── data/
│   └── README.md
│
├── notebooks/
│   └── README.md
│
├── src/
│   └── README.md
│
└── .gitignore
```

The repository structure will expand progressively as data preparation, analysis, modeling, recommendation, and application-development stages begin.

---

## 12. Project Philosophy

The project will remain technically honest throughout its development.

The following principles will guide the work:

* Use real collected data wherever possible
* Do not invent results or analytical conclusions
* Do not select algorithms simply to claim that they were used
* Apply course concepts where they have meaningful roles
* Compare alternative techniques where appropriate
* Clearly document limitations
* Distinguish association from causation
* Keep analytical conclusions explainable
* Maintain responsible boundaries around mental wellness and nutrition
* Allow the project architecture to evolve as understanding of the data improves

---

**Current Phase:** Project Redefinition & Initial Data Collection
