# 3. Data Science Process

## 3.1 Overview

Kinetra will follow a structured Data Science process to progress from understanding the problem to developing and evaluating a data-driven solution.

The project will follow the major stages of the Data Science workflow and will be developed incrementally throughout the semester.

The process can be represented as:

```text
Business / Problem Understanding
              ↓
       Data Understanding
              ↓
        Data Preparation
              ↓
           Modeling
              ↓
          Evaluation
              ↓
         Deployment
```

These stages are not necessarily strictly linear. Findings from later stages may require returning to earlier stages and refining the problem, data, or approach.

---

## 3.2 Stage 1 — Business / Problem Understanding

The first stage is to understand the real-world problem and define what the project is intended to accomplish.

### Application to Kinetra

Kinetra focuses on the problem of providing more personalized movement and wellness guidance to individuals whose needs may differ from generic exercise recommendations.

At this stage, the project focuses on:

* Understanding the problem
* Identifying the target users
* Defining project objectives
* Identifying the expected outcomes
* Establishing project boundaries and limitations

The outcome of this stage is a clearly defined Data Science problem.

---

## 3.3 Stage 2 — Data Understanding

Once the problem has been defined, the next stage is to determine what data is required to address it.

### Application to Kinetra

Potential data may include information related to:

* Individual characteristics
* Pain characteristics
* Physical activity
* Exercise habits
* Sleep and recovery
* Lifestyle factors
* Functional limitations
* Exercise-related information

The project will investigate available data sources and determine which variables are relevant.

This stage will also involve examining:

* Data structure
* Variable types
* Data distributions
* Missing values
* Potential inconsistencies
* Possible relationships between variables

---

## 3.4 Stage 3 — Data Preparation

Raw data may not be directly suitable for analysis or machine learning.

The data preparation stage will therefore involve activities such as:

* Data cleaning
* Handling missing values
* Identifying inconsistencies
* Handling relevant outliers
* Data transformation
* Encoding categorical variables where required
* Feature construction
* Feature selection
* Preparing appropriate datasets for analysis and modeling

The exact preparation techniques will depend on the characteristics of the selected dataset.

---

## 3.5 Stage 4 — Modeling

After the data has been prepared, appropriate analytical and machine-learning techniques can be explored.

Depending on the problem and available data, Kinetra may investigate:

### Statistical approaches

* Descriptive statistics
* Correlation analysis
* Hypothesis testing
* Other appropriate statistical methods

### Supervised learning

* Regression
* Classification
* Decision Trees
* Random Forest
* Support Vector Machines
* k-Nearest Neighbors

### Unsupervised learning

* K-Means
* Hierarchical Clustering
* DBSCAN
* Other appropriate clustering approaches

### Additional techniques

* Dimensionality reduction
* Association rule mining
* Anomaly detection
* Recommendation techniques

Not every technique will necessarily be used in the same part of the system. Each technique will be evaluated according to its relevance to the available data and project objective.

---

## 3.6 Stage 5 — Evaluation

The results produced by analytical and machine-learning approaches need to be evaluated before being used in the final system.

Evaluation may include:

* Model performance
* Prediction quality
* Comparison between different approaches
* Clustering evaluation
* Recommendation quality
* Interpretability
* Robustness
* Limitations and potential sources of error

The evaluation criteria will be selected according to the specific task being evaluated.

For example, a classification model and a clustering model require different evaluation approaches.

---

## 3.7 Stage 6 — Deployment

The final stage is to integrate the validated Data Science components into a usable application.

The planned system may eventually provide:

```text
User Input
    ↓
Assessment
    ↓
Data Processing
    ↓
Analysis / Prediction
    ↓
Personalized Recommendation
    ↓
User-facing Guidance
```

Deployment may also involve applying appropriate DataOps and introductory MLOps practices as the project develops.

---

## 3.8 Iterative Nature of the Process

The Data Science process is expected to be iterative rather than strictly one-directional.

For example:

```text
Problem Understanding
        ↓
Data Understanding
        ↓
Data Preparation
        ↓
Modeling
        ↓
Evaluation
        │
        └───────────────┐
                        ↓
               Refine Earlier Stage
                        │
                        ↓
                  New Evaluation
```

A model may reveal that additional data is required. Data exploration may reveal that the original problem definition needs refinement. Evaluation may show that a particular modeling approach is unsuitable.

Therefore, Kinetra will be refined continuously as new findings are obtained.

---

## 3.9 Connection with Project Development

The project will progressively move through these stages as the relevant concepts are covered in the Fundamentals of Data Science course.

### Current Stage — Week 1

The project is currently focused on:

* Problem understanding
* Project objectives
* Initial scope
* Analytics framework
* Data Science process
* Initial challenges and limitations

Future stages will be documented and implemented as the project progresses.
