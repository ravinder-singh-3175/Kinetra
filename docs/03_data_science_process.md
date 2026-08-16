# Data Science Process

## 3.1 Overview

The **Mental Wellness & Nutrition Project** will follow an iterative Data Science process to investigate wellness and lifestyle patterns among college students.

The project currently focuses on three major areas:

* Mental wellness
* Nutrition intake and dietary habits
* Physical activity and mobility

Additional lifestyle and contextual variables, such as sleep and daily routine, may also be considered where they are available in the collected data.

Rather than treating Data Science as a single sequence of analysis and modeling steps, the project will progressively move through problem understanding, data collection, data preparation, analysis, modeling, evaluation, and eventual application development.

The process is **iterative**. Findings at later stages may require earlier decisions to be reconsidered.

---

## 3.2 Problem Understanding

The first stage is to clearly define the problem being investigated.

The primary area of interest is **mental wellness among college students**.

Nutrition intake and physical activity/mobility are major lifestyle domains whose relationships with mental wellness will be investigated using collected data.

The central Data Science question is:

> **How can Data Science be used to analyze mental wellness, nutrition intake, physical activity, and related lifestyle characteristics among college students in order to identify meaningful patterns and support personalized wellness insights?**

At this stage, the project does not assume that one lifestyle factor directly causes another outcome.

Instead, relationships and patterns will be investigated using appropriate analytical methods.

---

## 3.3 Data Collection

The project uses **primary survey data collected from college students**.

A questionnaire has been developed containing questions related to areas such as:

* Mental wellness
* Nutrition and dietary habits
* Physical activity and mobility
* Sleep and daily routine
* Other relevant lifestyle or contextual characteristics

Approximately **100 responses** have currently been collected.

The survey responses represent the project's initial real-world dataset.

As development continues, the data-collection process will be documented, including:

* Questionnaire structure
* Variables collected
* Response formats
* Data types
* Data limitations
* Privacy considerations
* Potential sampling and response biases

---

## 3.4 Data Understanding

Before performing statistical analysis or machine learning, the collected dataset must first be understood.

This stage will involve examining:

* Number of observations
* Number of variables
* Meaning of each variable
* Variable data types
* Possible response categories
* Missing values
* Duplicate responses where relevant
* Unusual or inconsistent values
* Distribution of responses
* Representation of different wellness domains

A **data dictionary** will be developed to document each variable and its role.

Variables may be organized conceptually into:

```text id="r7ph1o"
Student Survey Data
        │
        ├── Context / Demographic Variables
        │
        ├── Mental Wellness Variables
        │
        ├── Nutrition Variables
        │
        ├── Physical Activity / Mobility Variables
        │
        └── Other Lifestyle Variables
```

The exact classification will be determined after formal inspection of the dataset.

---

## 3.5 Data Preparation

Raw survey responses may not be immediately suitable for analysis.

The data-preparation stage may include:

* Removing irrelevant technical fields where appropriate
* Handling missing information
* Checking duplicate or inconsistent records
* Standardizing response formats
* Encoding categorical responses
* Correcting data-type inconsistencies
* Detecting unusual values
* Transforming variables where justified
* Preparing analysis-ready datasets

The project will preserve the distinction between:

```text id="k5zdb3"
Raw Data
    ↓
Cleaned Data
    ↓
Processed / Analysis-Ready Data
```

Raw responses should remain unchanged so that data-processing steps can be reproduced and verified.

---

## 3.6 Exploratory Data Analysis

Exploratory Data Analysis will be used to understand the structure and characteristics of the collected dataset.

Potential analysis may include:

* Summary statistics
* Frequency distributions
* Histograms
* Bar charts
* Box plots
* Scatterplots
* Correlation analysis
* Comparison of relevant groups
* Examination of relationships among wellness variables

EDA may be performed separately for:

### Mental Wellness

To understand patterns in self-reported mental-wellness variables.

### Nutrition

To understand dietary and nutrition-related behaviours.

### Physical Activity and Mobility

To understand movement, activity, and mobility-related patterns.

### Cross-Domain Analysis

To explore possible relationships among mental wellness, nutrition, physical activity, sleep, and other relevant lifestyle characteristics.

Exploratory findings will guide later statistical and modeling decisions.

---

## 3.7 Statistical Analysis

As probability and statistics concepts are introduced in the course, appropriate methods will be applied to the collected dataset.

Potential areas include:

* Probability and distributions
* Measures of expectation and variation
* Covariance
* Correlation
* Sampling concepts
* Point and interval estimation
* Confidence intervals
* Hypothesis testing
* t-tests
* Chi-square tests
* Z-tests
* F-tests
* ANOVA

Statistical tests will only be used when their assumptions and the available data make them appropriate.

The project will distinguish between **statistical association and causal inference**.

---

## 3.8 Feature Engineering

After the original variables are understood, additional features may be constructed where they have meaningful interpretations.

Potential examples could include combined or derived representations of:

* Dietary behaviour
* Physical activity
* Sleep/routine
* Mental-wellness responses
* Broader lifestyle patterns

These are only conceptual possibilities at the current stage.

No composite wellness score or derived feature will be created simply for convenience. Its construction should have a clear analytical justification.

Feature extraction, construction, selection, learning, and dimensionality-reduction techniques will be explored as the relevant course concepts are introduced.

---

## 3.9 Modeling

Machine-learning models will be introduced only after the dataset has been prepared and an appropriate analytical problem has been identified.

Potential modeling tasks may include:

### Supervised Learning

If a meaningful target variable can be identified, supervised methods may be investigated for classification or regression.

Multiple suitable algorithms may be compared rather than selecting a model in advance.

### Unsupervised Learning

Clustering and related techniques may be used to investigate whether meaningful wellness or lifestyle profiles naturally occur among students.

### Dimensionality Reduction

Dimensionality-reduction methods may later be explored to understand complex relationships among multiple variables and support visualization or modeling.

### Association Analysis

Association-rule techniques may be explored where the representation of the data makes such analysis meaningful.

### Anomaly Detection

Anomaly-detection techniques may be investigated to identify unusual data patterns or observations where appropriate.

The exact modeling strategy will be determined by the data and project requirements.

---

## 3.10 Evaluation

Analytical methods and models will be evaluated using techniques appropriate to their purpose.

Evaluation may include:

* Statistical significance and uncertainty
* Model performance metrics
* Comparison between alternative models
* Clustering evaluation
* Interpretability
* Stability of results
* Practical usefulness
* Limitations and possible bias

A model will not be considered useful only because it produces a high numerical performance score.

Results must also be interpretable and appropriate for the project's wellness context.

---

## 3.11 Personalized Wellness Insights

Later stages of the project may use analytical findings, identified patterns, and student profiles to generate personalized **general wellness insights**.

Potential areas of guidance may include:

* Nutrition and dietary habits
* Physical activity
* Sleep and routine
* General lifestyle behaviours that may support mental wellness

The recommendation mechanism will only be designed after the relevant analytical foundations have been established.

Recommendations will remain:

* Educational
* Explainable
* General wellness-oriented
* Non-diagnostic
* Non-clinical

---

## 3.12 Application Development

Once the analytical components are sufficiently developed and evaluated, they may be integrated into an application.

A future application may allow a student to:

```text id="9md00p"
Provide Wellness Information
          ↓
Receive Profile Analysis
          ↓
View Relevant Patterns
          ↓
Understand Important Factors
          ↓
Receive General Wellness Insights
```

The exact application design and technology stack have not yet been finalized.

The Data Science analysis will be developed before committing to the final application architecture.

---

## 3.13 DataOps and MLOps Perspective

DataOps and introductory MLOps concepts provide a framework for thinking about how the project can remain organized and reproducible as it grows.

Relevant practices may eventually include:

* Dataset versioning
* Separation of raw and processed data
* Reproducible preprocessing
* Organized analytical notebooks
* Reusable source code
* Model versioning
* Experiment tracking
* Documentation of analytical decisions
* Reproducible evaluation
* Consistent project structure

These practices will be introduced progressively rather than implementing unnecessary infrastructure at the beginning of the project.

---

## 3.14 Iterative Nature of the Project

The Data Science process is not strictly linear.

For example:

```text id="h7wzt5"
Problem Understanding
        ↓
Data Collection
        ↓
Data Understanding
        ↓
Data Preparation
        ↓
Analysis
        ↓
Modeling
        ↓
Evaluation
        ↓
Insights / Application
        │
        └──────────────► Revisit Earlier Stages
```

Exploratory analysis may reveal problems with collected variables.

Statistical analysis may suggest new features.

Model evaluation may show that a target or feature is unsuitable.

Recommendation development may reveal the need for additional information.

Therefore, earlier stages may be revisited whenever justified.

---

## 3.15 Relationship with Data Science Methodologies

The project will use concepts from Data Science process methodologies taught in the course to guide its development.

**CRISP-DM** provides a useful general structure through problem understanding, data understanding, data preparation, modeling, evaluation, and eventual deployment.

**SEMMA** provides another perspective particularly relevant to sampling, exploration, modification, modeling, and assessment.

Other lifecycle methodologies introduced in the course will be studied and mapped to the project as they are covered.

The project will not treat these methodologies as competing checklists. Instead, their relevant ideas will be used to understand and organize the development process.

---

## 3.16 Current Project Stage

The project is currently transitioning from **problem understanding and data collection** into **data understanding**.

Completed or currently established:

* Revised project problem defined
* College students identified as the target population
* Mental wellness established as the primary area of interest
* Nutrition and physical activity/mobility established as major related lifestyle domains
* Survey questionnaire developed
* Approximately 100 responses collected
* Initial repository structure established

Not yet completed:

* Formal dataset inspection
* Data dictionary
* Data cleaning
* Exploratory Data Analysis
* Statistical analysis
* Feature engineering
* Machine-learning modeling
* Student profile discovery
* Recommendation system
* Final application

The immediate next Data Science task will be to formally inspect and document the collected survey dataset before beginning analysis.
