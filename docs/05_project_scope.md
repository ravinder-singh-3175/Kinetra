# Project Scope

## 5.1 Overview

The **Mental Wellness & Nutrition Project** is a Data Science-based college student wellness project focused primarily on understanding **mental wellness** and its relationships with nutrition, physical activity/mobility, and other relevant lifestyle factors.

The project uses primary survey data collected from college students and will progressively evolve as concepts from the Fundamentals of Data Science course are introduced.

The scope is intentionally broad enough to support future statistical analysis, machine learning, pattern discovery, recommendation techniques, and application development while remaining centered on one coherent problem.

---

## 5.2 Target Population

The target population for the project is:

> **College students**

The project does not currently impose a specific age range.

The initial dataset consists of responses collected through a questionnaire distributed among college students.

Any conclusions drawn from the dataset will consider the characteristics and limitations of the actual sample rather than automatically generalizing findings to all college students.

---

## 5.3 Core Areas of Investigation

The project currently focuses on three major domains.

### 5.3.1 Mental Wellness

Mental wellness is the **primary area of interest**.

The project aims to investigate patterns in students' self-reported mental-wellness information and examine how these patterns relate to other lifestyle characteristics.

Mental-wellness variables will be treated as indicators available within the collected survey data rather than as clinical diagnoses.

---

### 5.3.2 Nutrition Intake

Nutrition is a major lifestyle domain within the project.

The project may investigate:

* Dietary habits
* Meal-related patterns
* Food choices
* Hydration-related behaviour
* Other nutrition-related variables available in the survey

Nutrition information may be analyzed independently and in relation to mental wellness, physical activity, sleep, and other lifestyle characteristics.

The project will not diagnose nutritional deficiencies or prescribe clinical diets.

---

### 5.3.3 Physical Activity and Mobility

Physical activity and mobility form another important lifestyle domain.

The project may investigate:

* Physical activity levels
* Exercise habits
* Movement-related behaviour
* Sedentary behaviour
* Mobility-related information represented in the dataset

These characteristics may be studied in relation to mental wellness, nutrition, and other lifestyle factors.

---

## 5.4 Supporting Lifestyle and Contextual Factors

Additional variables may contribute to the overall analysis where they are available in the collected dataset.

Examples may include:

* Sleep
* Daily routine
* Academic or lifestyle characteristics
* Relevant demographic information
* Other contextual factors represented in the questionnaire

These factors are not necessarily independent project modules.

Instead, they may provide additional context for understanding relationships among mental wellness, nutrition, and physical activity.

---

## 5.5 Data Scope

The initial project dataset consists of **primary survey responses collected from college students**.

Approximately 100 responses have currently been collected.

The project will progressively address:

* Data understanding
* Variable documentation
* Data quality
* Missing information
* Data cleaning
* Data transformation
* Data exploration
* Data versioning
* Feature management
* Analysis-ready dataset creation

A formal data dictionary will be created after the dataset is inspected.

Raw data will be preserved separately from cleaned and processed data.

Additional data sources may be considered later if they provide a meaningful and justified contribution to the project.

---

## 5.6 Analytical Scope

The project is intended to support multiple levels of Data Science analysis.

### Descriptive Analysis

Understand the characteristics and distributions present in the student survey data.

### Diagnostic Analysis

Investigate relationships and associations among mental wellness, nutrition, physical activity, and other relevant variables.

### Statistical Analysis

Apply appropriate probability and statistical techniques as they are introduced in the course.

### Predictive Analysis

Explore meaningful prediction tasks if suitable target variables can be identified.

### Pattern and Profile Discovery

Investigate whether meaningful student wellness or lifestyle profiles can be discovered using appropriate analytical or unsupervised-learning techniques.

### Prescriptive Analysis

Explore how validated analytical findings may eventually support personalized general wellness insights.

---

## 5.7 Data Science and Machine Learning Scope

As the project progresses, appropriate Data Science and machine-learning techniques may be explored.

Potential areas include:

* Probability and statistics
* Correlation and covariance
* Sampling and estimation
* Hypothesis testing
* ANOVA
* Data visualization
* Feature extraction
* Feature construction
* Feature selection
* Dimensionality reduction
* Regression
* Classification
* Decision Trees
* Random Forest
* Support Vector Machines
* k-Nearest Neighbors
* Clustering
* Principal Component Analysis
* t-SNE
* Association rule mining
* Anomaly detection
* Model evaluation
* Recommendation techniques

These techniques are **within the learning and experimental scope of the project**.

However, inclusion in this section does not mean that every technique must become part of the final application.

Each technique will be evaluated for its suitability to the available data and analytical problem.

---

## 5.8 Data Engineering Scope

As relevant concepts are introduced, the project may progressively include:

* Data extraction
* Data ingestion
* Data cleaning
* Data exploration
* Data wrangling
* Data transformation
* Dataset versioning
* Feature management
* Data pipeline design
* Data cataloging concepts
* Relational database usage
* Batch-processing concepts
* Streaming-ingestion concepts
* Data warehouse, data lake, and cloud concepts

Some of these topics may be implemented directly where appropriate.

Others may be represented through architectural analysis or scalability considerations if implementing them would not be meaningful for the size and nature of the project.

The project will not artificially create unnecessary infrastructure simply to claim that a technology was used.

---

## 5.9 Personalized Wellness Guidance

A future objective of the project is to explore personalized and explainable **general wellness guidance**.

Potential guidance may relate to:

* Nutrition and dietary habits
* Physical activity
* Sleep and routine
* General lifestyle behaviours associated with wellness

The recommendation mechanism has not yet been finalized.

It may eventually incorporate analytical findings, student profiles, recommendation techniques, and carefully selected external wellness knowledge.

Any external guidance source used by the system should be documented and appropriately credible.

Recommendations will remain educational and general wellness-oriented.

---

## 5.10 Application Scope

Later stages of the project may integrate the analytical components into an interactive application.

A future application may allow students to:

* Provide relevant wellness and lifestyle information
* Receive an understandable representation of their profile
* View relevant patterns or analytical findings
* Understand factors contributing to generated results
* Receive personalized general wellness insights

The exact interface, software architecture, deployment platform, and technology stack have not yet been finalized.

The application will be designed around the Data Science components rather than determining the analysis based on a predetermined application design.

---

## 5.11 Explainability Scope

Explainability is considered an important project requirement.

Where appropriate, the system should communicate:

* What was observed
* Which variables were involved
* Which factors contributed to an analytical result
* How reliable or uncertain a result may be
* Why a particular insight or recommendation is being presented
* What limitations apply

This is especially important because the project involves mental-wellness and lifestyle information.

---

## 5.12 DataOps and MLOps Scope

DataOps and introductory MLOps concepts may progressively support project organization and reproducibility.

Potential practices include:

* Structured repository organization
* Dataset versioning
* Reproducible preprocessing
* Reusable source code
* Experiment documentation
* Model versioning
* Evaluation tracking
* Reproducible analytical workflows

The level of implementation will remain appropriate to the scale of the project.

---

## 5.13 R and Data Analysis Tools

The project may use **R** for appropriate statistical and data-analysis tasks as the relevant course unit is introduced.

R-based analysis may complement analysis performed using other tools.

The objective is to demonstrate meaningful application of the course material rather than duplicate every analysis unnecessarily across multiple programming languages.

---

## 5.14 Current Core Scope

At the present stage, the immediate scope is limited to:

1. Finalizing the revised project foundation.
2. Documenting the survey and collected variables.
3. Understanding the approximately 100 collected responses.
4. Creating a data dictionary.
5. Identifying data-quality issues.
6. Preparing for future cleaning and analysis.

Advanced statistical analysis, machine learning, recommendation systems, and application development remain **future stages**.

---

## 5.15 Future Expansion

The project architecture is intentionally designed to allow expansion as the course progresses.

Potential future capabilities include:

```text id="53xdwa"
Student Input
      ↓
Wellness Profile
      ↓
Mental Wellness Analysis
      +
Nutrition Analysis
      +
Physical Activity Analysis
      ↓
Cross-Domain Pattern Analysis
      ↓
Predictive / Profile Analysis
      ↓
Explainable Insights
      ↓
Personalized General Wellness Guidance
```

Additional features may be introduced if they strengthen the central project objective and can be supported by appropriate data and methods.

---

## 5.16 Out-of-Scope Areas

The project is **not intended to**:

* Diagnose mental-health disorders
* Diagnose depression, anxiety, eating disorders, or other clinical conditions
* Diagnose nutritional deficiencies
* Provide psychological or psychiatric treatment
* Prescribe medication
* Provide medical nutrition therapy
* Prescribe therapeutic diets
* Replace qualified medical, mental-health, or nutrition professionals
* Make unsupported causal claims from observational data
* Present machine-learning predictions as clinical diagnoses

The project will remain within **Data Science, educational analysis, and general wellness-support boundaries**.

---

## 5.17 Scope Management Principle

New technologies or techniques should not be added simply because they appear impressive.

A proposed addition should answer at least one of the following questions:

> **Does it help us understand the collected student data?**

> **Does it help us investigate the relationship between lifestyle and mental wellness?**

> **Does it improve the quality, reliability, explainability, or reproducibility of our analysis?**

> **Does it meaningfully improve the eventual student wellness experience?**

> **Does it allow us to appropriately demonstrate an important FDS concept?**

If the answer to all of these is no, the feature should probably not be added.

---

## 5.18 Summary

The project scope can currently be summarized as:

> **Collect college-student wellness data → understand and prepare the data → analyze mental wellness and its relationships with nutrition, physical activity, and lifestyle → discover meaningful patterns → progressively apply Data Science techniques → generate explainable insights → eventually support personalized general wellness guidance.**

This scope provides enough flexibility for the project to grow throughout the semester while maintaining a consistent central objective.
