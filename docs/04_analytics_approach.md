# Analytics Approach

## 4.1 Overview

The **Mental Wellness & Nutrition Project** will use the four major types of Data Analytics introduced in the Fundamentals of Data Science course:

1. Descriptive Analytics
2. Diagnostic Analytics
3. Predictive Analytics
4. Prescriptive Analytics

These analytics types represent different levels of understanding that can progressively be developed from the collected college-student wellness data.

The project currently focuses on **mental wellness as the primary area of interest**, while nutrition intake, physical activity/mobility, sleep, and other available lifestyle characteristics are investigated as related factors.

The general progression is:

```text
Collected Student Data
          ↓
Descriptive Analytics
"What is happening?"
          ↓
Diagnostic Analytics
"What patterns and relationships exist?"
          ↓
Predictive Analytics
"What can reasonably be predicted?"
          ↓
Prescriptive Analytics
"What useful wellness guidance can be provided?"
```

The project is currently at an early stage. Therefore, these sections describe the intended analytical framework rather than claiming that all analyses have already been performed.

---

## 4.2 Descriptive Analytics

### Question

> **What is happening in the collected student wellness data?**

Descriptive Analytics will be used to summarize and understand the characteristics of the surveyed college students.

Potential analysis may include:

### Mental Wellness

* Distribution of mental-wellness-related responses
* Frequency of different self-reported wellness experiences
* Variation in relevant wellness indicators

### Nutrition

* Dietary habits
* Meal patterns
* Food-related behaviours
* Hydration-related patterns, where available

### Physical Activity and Mobility

* Physical activity levels
* Exercise or movement frequency
* Sedentary behaviour
* Mobility-related characteristics represented in the dataset

### Lifestyle and Context

Where available, additional analysis may examine:

* Sleep patterns
* Daily routine
* Academic or lifestyle characteristics
* Relevant demographic/contextual variables

Potential techniques may include:

* Frequency tables
* Percentages
* Measures of central tendency
* Measures of variability
* Summary statistics
* Histograms
* Bar charts
* Box plots
* Other appropriate visualizations

The exact descriptive analysis will be determined after the survey dataset is formally inspected.

---

## 4.3 Diagnostic Analytics

### Question

> **What patterns, relationships, or factors are associated with what we observe?**

Diagnostic Analytics will investigate relationships among the collected variables.

This is particularly important because the project aims to understand how nutrition, physical activity, and other lifestyle characteristics may be associated with mental wellness.

Potential questions include:

* Are particular dietary habits associated with differences in self-reported mental wellness?
* Is physical activity associated with mental-wellness indicators?
* Are sleep patterns associated with mental wellness?
* Are nutrition habits associated with physical activity patterns?
* Do particular lifestyle behaviours frequently appear together?
* Do different groups of students show different wellness patterns?

Potential analytical methods may eventually include:

* Cross-tabulation
* Correlation analysis
* Covariance
* Group comparisons
* Statistical hypothesis testing
* Appropriate visual analysis
* Association analysis

The specific techniques used will depend on:

* Variable types
* Data distributions
* Sample characteristics
* Statistical assumptions
* Questions being investigated

### Important Analytical Boundary

> **Association does not automatically imply causation.**

For example, if students reporting a particular dietary behaviour also report different mental-wellness outcomes, the project cannot automatically conclude that the dietary behaviour caused the difference.

The result should instead be described as an observed relationship or statistical association unless an appropriate research design supports causal inference.

---

## 4.4 Predictive Analytics

### Question

> **What meaningful outcome can be predicted from the available data?**

Predictive Analytics may later be used to investigate whether combinations of student lifestyle characteristics contain useful information for predicting an appropriate outcome.

A conceptual pipeline could be:

```text
Student Characteristics
        ↓
Selected / Engineered Features
        ↓
Predictive Model
        ↓
Predicted Outcome
        ↓
Model Evaluation
```

Potential predictor domains may include:

* Nutrition-related variables
* Physical activity variables
* Sleep and routine
* Other lifestyle characteristics
* Relevant contextual variables

However, the **final prediction target has not yet been selected**.

The project will first:

1. Understand and clean the dataset.
2. Perform Exploratory Data Analysis.
3. Investigate statistical relationships.
4. Determine whether an appropriate prediction problem exists.
5. Select suitable features and target variables.
6. Compare appropriate models.
7. Evaluate their performance and limitations.

The project will therefore **not select a machine-learning algorithm or target variable in advance simply to create a predictive model**.

Any predictive output related to mental wellness will remain non-diagnostic and will not be presented as a clinical assessment.

---

## 4.5 Prescriptive Analytics

### Question

> **What useful action or general wellness guidance may be suggested based on the analysis?**

Prescriptive Analytics represents a later stage of the project.

The eventual goal is to explore whether analytical findings, identified patterns, and student wellness profiles can support personalized and understandable **general wellness guidance**.

A conceptual pipeline may be:

```text
Student Information
        ↓
Data Analysis / Profile
        ↓
Relevant Patterns
        ↓
Recommendation Logic
        ↓
Explainable General Wellness Guidance
```

Potential guidance may relate to:

* Nutrition and dietary habits
* Physical activity
* Sleep and routine
* General lifestyle behaviours that may support wellness

The recommendation mechanism has **not yet been finalized**.

It may eventually use a combination of:

* Statistical findings
* Identified student profiles
* Data-driven patterns
* Recommendation techniques
* Carefully selected general wellness knowledge

Any external knowledge used for recommendations will need to come from appropriate and credible sources.

Recommendations will remain educational and wellness-oriented rather than medical or clinical.

---

## 4.6 Relationship Between the Four Analytics Types

The four analytics types are connected rather than independent.

For example:

```text
DESCRIPTIVE
Students show different nutrition,
activity and wellness patterns.
        ↓
DIAGNOSTIC
Certain lifestyle variables appear
associated with particular wellness patterns.
        ↓
PREDICTIVE
Selected variables may contain useful
information for predicting an appropriate
non-clinical outcome.
        ↓
PRESCRIPTIVE
The resulting analysis may help generate
personalized general wellness insights.
```

Each stage depends on the quality and validity of the previous stages.

Prescriptive recommendations should therefore not be developed before the underlying data and analytical relationships have been adequately understood.

---

## 4.7 Cross-Domain Analysis

An important characteristic of this project is that mental wellness, nutrition, and physical activity will not be studied only as isolated topics.

The project will also investigate their possible relationships.

Conceptually:

```text
                 Mental Wellness
                   /          \
                  /            \
                 /              \
          Nutrition ---------- Physical
            Intake             Activity
                  \            /
                   \          /
                 Lifestyle /
               Contextual Factors
```

This integrated perspective may allow the project to identify patterns that would not be visible when each domain is analyzed independently.

The exact relationships investigated will depend on the variables available in the collected dataset.

---

## 4.8 Student Wellness Profiles

As the project progresses, analytics may also be used to explore broader student wellness profiles.

Rather than reducing every student to a simple label such as "healthy" or "unhealthy," the project may eventually represent students across multiple dimensions.

For example, a profile could conceptually contain information about:

```text
Mental Wellness
Nutrition
Physical Activity
Sleep / Routine
Other Relevant Lifestyle Factors
```

Statistical and unsupervised-learning techniques may later help investigate whether meaningful groups or patterns naturally emerge from these characteristics.

These profiles would represent **data patterns**, not medical or psychological diagnoses.

---

## 4.9 Explainability

Analytical results should be understandable.

Where possible, the project should explain:

* What was observed
* Which variables were involved
* How strong or reliable the relationship appears to be
* Which factors contributed to a prediction or profile
* What limitations apply
* Why a particular wellness insight or recommendation is being shown

This is especially important because the project involves mental wellness and lifestyle information.

---

## 4.10 Current Analytics Status

At the current stage:

### Established

* The four analytics types have been mapped conceptually to the project.
* Mental wellness is the primary area of interest.
* Nutrition and physical activity/mobility are major related domains.
* Primary survey data has been collected from approximately 100 college students.

### Not Yet Performed

* Formal Descriptive Analytics
* Diagnostic Analytics
* Statistical hypothesis testing
* Predictive modeling
* Student profile discovery
* Prescriptive recommendation development

These analyses will begin only after the collected survey dataset has been formally inspected, documented, and prepared.

---

## 4.11 Summary

The project's analytics framework can be summarized as:

> **Describe the student population → investigate relationships → explore meaningful predictions → transform validated findings into understandable general wellness insights.**

This framework allows the project to progressively apply Data Science techniques while keeping mental wellness, nutrition, physical activity, and related lifestyle factors within one coherent analytical system.
