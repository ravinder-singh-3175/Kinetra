# 4. Analytics Approach

## 4.1 Overview

Analytics is an important part of the Kinetra project because the system is intended to use data to understand individual situations and support personalized movement and wellness guidance.

The project will explore the four major types of analytics:

1. Descriptive Analytics
2. Diagnostic Analytics
3. Predictive Analytics
4. Prescriptive Analytics

These types of analytics represent different levels of understanding, from describing what is present in the data to supporting decisions based on analytical results.

Kinetra will investigate how each type can contribute to the overall Data Science workflow.

---

## 4.2 Descriptive Analytics

Descriptive analytics focuses on understanding **what has happened or what is present in the available data**.

In Kinetra, descriptive analytics may be used to summarize characteristics of the individuals represented in the dataset.

Possible analyses include:

* Distribution of age or age groups
* Distribution of pain intensity
* Frequency of different pain locations
* Physical activity levels
* Exercise frequency
* Sleep-related patterns
* Distribution of other relevant variables

Statistical measures such as:

* Mean
* Median
* Mode
* Minimum
* Maximum
* Standard deviation
* Frequency and percentage

may be used where appropriate.

Visualizations such as histograms, bar charts, box plots, and other suitable charts may also be used.

### Example

A descriptive analysis may show how many individuals report different levels of pain or how frequently different exercise activities occur.

The purpose is to understand the overall characteristics of the available data before moving toward deeper analysis.

---

## 4.3 Diagnostic Analytics

Diagnostic analytics focuses on understanding **why certain patterns or outcomes may be present**.

After describing the data, Kinetra will investigate relationships between relevant variables.

Possible areas of investigation include:

* Relationship between pain intensity and physical activity
* Relationship between pain duration and exercise habits
* Relationship between sleep and activity levels
* Relationship between lifestyle factors and reported discomfort
* Differences between groups of individuals

Appropriate statistical methods and visualizations may be used to investigate these relationships.

Correlation analysis and hypothesis testing may be explored where appropriate.

However, an observed association will not automatically be interpreted as a causal relationship.

### Example

If the data shows that individuals with lower physical activity levels also report higher pain levels, diagnostic analysis can investigate whether there is a meaningful statistical relationship between the variables.

The actual relationships will only be determined after the dataset has been analyzed.

---

## 4.4 Predictive Analytics

Predictive analytics focuses on understanding **what may happen or what outcome may be expected based on available data**.

Kinetra may explore predictive modeling if the selected dataset contains a suitable target variable.

Possible predictive tasks may include:

* Classification of relevant user categories
* Prediction of a suitable outcome variable
* Identification of individuals belonging to particular profiles
* Estimation of relevant numerical outcomes

Potential machine-learning approaches may include:

* Regression
* Classification
* Decision Trees
* Random Forest
* Support Vector Machines
* k-Nearest Neighbors

The exact prediction problem and algorithm will be selected only after understanding the available data.

### Important Consideration

At the current stage, Kinetra does not assume a specific prediction target.

The target variable will be determined after the data has been collected and understood.

This prevents the project from forcing an unsuitable machine-learning problem onto the dataset.

---

## 4.5 Prescriptive Analytics

Prescriptive analytics focuses on **what action or decision should be taken based on the available information and analytical results**.

This is particularly relevant to Kinetra because the ultimate goal is to provide personalized movement and wellness guidance.

The project may use analytical findings, user characteristics, and predictive results to support recommendations such as:

* Suitable types of movement or exercise
* Exercise-related precautions
* Activity-level guidance
* Recovery and wellness suggestions
* Personalized information based on an individual's profile

The recommendation mechanism will be developed only after the relevant data and analytical results are understood.

The system will provide wellness-oriented guidance within the defined project boundaries and will not attempt to diagnose medical conditions or replace professional healthcare advice.

---

## 4.6 Relationship Between the Four Analytics Types

The four analytics types can be connected within the Kinetra workflow:

```text
Descriptive Analytics
        ↓
What is happening?
        ↓
Diagnostic Analytics
        ↓
Why might it be happening?
        ↓
Predictive Analytics
        ↓
What may happen?
        ↓
Prescriptive Analytics
        ↓
What action may be appropriate?
```

These stages build upon one another.

Descriptive analysis provides an understanding of the available data.

Diagnostic analysis investigates relationships and possible explanations.

Predictive analysis can use identified patterns to estimate relevant outcomes.

Prescriptive analysis can then use these insights to support personalized decisions or recommendations.

---

## 4.7 Application to Kinetra

The planned relationship between analytics and Kinetra can be summarized as follows:

| Analytics Type | Key Question               | Possible Application in Kinetra                      |
| -------------- | -------------------------- | ---------------------------------------------------- |
| Descriptive    | What is happening?         | Understand user and pain-related patterns            |
| Diagnostic     | Why might it be happening? | Investigate relationships between relevant variables |
| Predictive     | What may happen?           | Predict suitable outcomes or user profiles           |
| Prescriptive   | What should be done?       | Support personalized movement and wellness guidance  |

The exact implementation of each analytics type will depend on the characteristics of the selected dataset.

---

## 4.8 Analytics and the Data Science Process

The four analytics types will be integrated with the broader Data Science process.

```text
Problem Understanding
        ↓
Data Understanding
        ↓
Data Preparation
        ↓
Descriptive Analysis
        ↓
Diagnostic Analysis
        ↓
Predictive Analysis
        ↓
Prescriptive Analysis
        ↓
Evaluation
        ↓
Deployment
```

This represents a conceptual workflow rather than a strictly linear process.

In practice, the project may move back to earlier stages when analysis reveals data-quality issues, insufficient variables, or the need to refine the problem.

---

## 4.9 Evaluation of Analytics Approaches

The analytical approaches used in Kinetra will need to be evaluated according to their purpose.

For descriptive and diagnostic analysis, evaluation may involve checking:

* Correctness of calculations
* Quality of visualizations
* Statistical validity
* Consistency of findings
* Interpretability of results

For predictive models, evaluation may involve appropriate performance measures such as:

* Accuracy
* Precision
* Recall
* F1-score
* Mean Absolute Error
* Root Mean Squared Error

The exact evaluation metrics will depend on whether the final predictive task is a classification or regression problem.

For prescriptive or recommendation components, evaluation may consider:

* Relevance of recommendations
* Consistency
* Interpretability
* Safety considerations
* Alignment with the available evidence

---

## 4.10 Expected Outcome

The analytics stage is expected to transform raw and prepared data into meaningful insights that can contribute to the Kinetra system.

The overall objective is to progress from:

**Data → Understanding → Insights → Prediction → Recommendations**

The project will demonstrate how different forms of analytics can be combined to address a real-world personalization problem.

---

## 4.11 Current Status

At the current stage of the project, the exact dataset, prediction target, and final recommendation mechanism have not yet been finalized.

Therefore, the analytics approaches described in this document represent the planned analytical framework.

As the project progresses and actual data becomes available, the selected analytical techniques will be refined according to the characteristics of the data and the project objectives.
