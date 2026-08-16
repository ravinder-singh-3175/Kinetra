# Problem Definition

## 1.1 Background

College life introduces students to significant changes in routine, academic workload, independence, dietary habits, sleep patterns, social environment, and physical activity.

These factors can influence students' overall well-being and may also be associated with differences in their mental wellness.

Among these factors, **nutrition and physical activity are particularly important lifestyle components**. Irregular eating habits, inadequate dietary patterns, reduced physical activity, poor sleep, and other lifestyle behaviours may occur together with variations in students' self-reported mental wellness.

However, these relationships are complex and should not be assumed without examining actual data.

The **Mental Wellness & Nutrition Project** aims to use Data Science to study these relationships using primary survey data collected from college students.

---

## 1.2 Problem Statement

The central problem addressed by this project is:

> **How can Data Science be used to analyze mental wellness, nutrition intake, physical activity, and related lifestyle characteristics among college students in order to identify meaningful patterns and support personalized wellness insights?**

The project will investigate how different lifestyle characteristics are associated with students' self-reported mental wellness.

Particular attention will be given to:

* Mental wellness indicators
* Nutrition and dietary habits
* Physical activity and mobility
* Sleep and daily routine
* Other relevant lifestyle or contextual variables available in the collected dataset

The project will focus on identifying relationships supported by the collected data rather than beginning with predetermined conclusions.

---

## 1.3 Existing Gap

Students receive large amounts of general wellness advice regarding nutrition, exercise, sleep, stress management, and healthy routines.

However, such advice is often presented independently rather than considering how different aspects of a student's lifestyle may interact.

For example, two students may report similar mental-wellness experiences while having very different:

* Dietary habits
* Physical activity levels
* Sleep patterns
* Daily routines
* Lifestyle behaviours

Similarly, students with comparable nutrition or activity patterns may still report different wellness outcomes.

This creates an opportunity to use Data Science to examine multiple wellness-related factors together and identify patterns that may not be obvious when each factor is considered separately.

---

## 1.4 Proposed Approach

The project will use primary survey data collected from college students.

The current conceptual workflow is:

```text
College Student Survey Data
            │
            ▼
      Data Understanding
            │
            ▼
 Data Cleaning & Preparation
            │
            ▼
 ┌──────────┼──────────┐
 ▼          ▼          ▼
Mental   Nutrition   Physical
Wellness   Intake    Activity
            │
            ▼
    Integrated Analysis
            │
            ▼
 Statistical & Data Science
          Methods
            │
            ▼
 Patterns / Relationships /
     Student Profiles
            │
            ▼
 Explainable Wellness Insights
            │
            ▼
 Personalized General
   Wellness Guidance
```

The exact statistical techniques, predictive targets, machine-learning algorithms, and recommendation methods will be selected progressively as the dataset is explored and relevant concepts are learned in the Fundamentals of Data Science course.

---

## 1.5 Primary Area of Interest

Although the project includes multiple wellness-related domains, **mental wellness is the primary area of interest**.

Nutrition intake and physical activity are treated as important lifestyle domains that may have meaningful relationships with mental wellness.

Other variables such as sleep, routine, and contextual factors may also be considered where they are available in the dataset.

The project therefore does not treat mental wellness, nutrition, and physical activity as completely independent components.

Instead, it aims to investigate their possible **interrelationships within the overall lifestyle and wellness profile of college students**.

---

## 1.6 Data-Driven Investigation

A key principle of the project is that conclusions should emerge from analysis rather than assumptions.

For example, the project may investigate questions such as:

* Are particular dietary habits associated with differences in self-reported mental wellness?
* Are physical activity levels associated with mental-wellness indicators?
* Are sleep patterns related to mental wellness or dietary behaviour?
* Are certain combinations of lifestyle behaviours frequently observed together?
* Do naturally occurring wellness profiles exist among the surveyed students?
* Which variables appear to be most informative when studying particular wellness outcomes?

These are **research questions**, not predetermined conclusions.

The collected data will determine whether meaningful relationships exist.

---

## 1.7 Association and Causation

The project primarily uses observational, self-reported survey data.

Therefore, an important analytical boundary is:

> **Association does not automatically imply causation.**

For example, if a relationship is observed between dietary habits and mental wellness, this does not by itself prove that one variable directly caused changes in the other.

The project will clearly distinguish between:

* Observed patterns
* Statistical associations
* Predictive relationships
* Causal claims

Causal claims will not be made unless they are supported by an appropriate research design and evidence.

---

## 1.8 Real-World Relevance

College students frequently experience changes in eating habits, physical activity, sleep, routine, academic workload, and general well-being.

Understanding how these factors appear together within a student population may provide useful insights into student lifestyle and wellness patterns.

A Data Science-based approach can help:

* Summarize wellness characteristics within the surveyed population
* Discover relationships between lifestyle variables
* Compare groups where appropriate
* Identify recurring behavioural patterns
* Explore student wellness profiles
* Evaluate predictive relationships where justified
* Eventually support understandable and personalized general wellness insights

This makes the project suitable for progressively applying statistical and Data Science concepts to a real-world dataset.

---

## 1.9 Project Boundaries

The **Mental Wellness & Nutrition Project** is an educational Data Science and general wellness project.

It is **not intended to**:

* Diagnose depression, anxiety, or other mental-health disorders
* Diagnose nutritional deficiencies
* Diagnose eating disorders
* Provide psychological or psychiatric treatment
* Prescribe medication
* Provide individualized medical nutrition therapy
* Prescribe therapeutic or medically restricted diets
* Replace doctors, psychologists, psychiatrists, dietitians, nutrition professionals, or other qualified healthcare professionals
* Treat statistical associations as proof of causation
* Present machine-learning predictions as medical diagnoses

The project will instead focus on:

* Data analysis
* Statistical investigation
* Pattern discovery
* Lifestyle and wellness profiling
* Explainable analytical insights
* General educational wellness guidance

Any future personalized recommendations will remain within appropriate **general wellness and educational boundaries**.

---

## 1.10 Current Stage

The project is currently in its **problem redefinition and initial data-understanding stage**.

At present:

* The target population has been defined as college students.
* The primary area of interest is mental wellness.
* Nutrition intake and physical activity/mobility are major lifestyle domains being investigated.
* A survey questionnaire has already been created.
* Approximately 100 responses have been collected.
* The dataset has not yet been formally cleaned or analyzed.
* No statistical or machine-learning conclusions are currently being claimed.

The project will evolve progressively as the Fundamentals of Data Science course advances and the collected dataset is better understood.
