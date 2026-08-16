# Project Challenges

## 6.1 Overview

The **Mental Wellness & Nutrition Project** uses real survey data collected from college students to investigate relationships among mental wellness, nutrition, physical activity/mobility, and other lifestyle factors.

Working with real-world wellness data introduces several technical, statistical, ethical, and project-management challenges.

Recognizing these challenges early is important because the quality of the final analysis depends not only on the algorithms used, but also on the quality of the data, assumptions, methodology, and interpretation.

---

## 6.2 Sample Size

The project currently has approximately **100 survey responses**.

This provides an initial dataset for analysis, but the sample size may limit:

* Statistical power
* Reliability of subgroup comparisons
* Complexity of models that can be trained
* Generalizability of findings
* Stability of clustering or other pattern-discovery techniques

The suitability of the sample size will be considered separately for each analytical task.

Additional responses may be collected if required and feasible.

---

## 6.3 Sampling Bias

The survey is being distributed among college students, and the respondents may not represent the wider college-student population.

Potential sources of sampling bias may include:

* Students from particular courses or programs being overrepresented
* Unequal representation of demographic groups
* Responses being concentrated within a particular institution or social network
* Voluntary participation influencing who chooses to respond

Therefore, conclusions from the project should be interpreted primarily in the context of the surveyed sample.

---

## 6.4 Self-Reported Data

The project relies primarily on information reported by participants themselves.

Self-reported data can be affected by:

* Recall errors
* Different interpretations of questions
* Social desirability bias
* Inaccurate estimation of habits
* Unintentional incorrect responses
* Participants choosing responses they consider more socially acceptable

This is particularly relevant for questions involving mental wellness, nutrition, sleep, and physical activity.

The project will acknowledge these limitations when interpreting results.

---

## 6.5 Data Quality

Survey datasets may contain quality issues such as:

* Missing responses
* Duplicate records
* Inconsistent answers
* Unexpected values
* Incorrect data types
* Rare categories
* Ambiguous responses
* Outliers or unusual response combinations

A structured data-quality assessment will therefore be required before formal analysis.

Raw data will be preserved, while cleaning and transformation steps will be documented separately.

---

## 6.6 Questionnaire Limitations

The quality of the analysis depends partly on the questions included in the survey.

Potential limitations include:

* Important factors not being measured
* Questions being too broad
* Limited response options
* Different interpretations among respondents
* Multiple concepts being represented by a small number of questions
* Survey length affecting response quality

The project will analyze the data that has actually been collected and will avoid claiming that unmeasured characteristics have been assessed.

---

## 6.7 Mental-Wellness Interpretation

Mental wellness is the project's primary area of interest, but survey responses should not automatically be interpreted as clinical indicators.

A participant reporting particular experiences does not by itself establish the presence of:

* Depression
* Anxiety disorders
* Other psychological conditions

The project will therefore focus on **self-reported mental-wellness patterns** rather than clinical diagnosis.

Any scores or derived indicators created later must have a clear analytical justification and should not be presented as diagnostic instruments unless they originate from an appropriately validated methodology and are used correctly.

---

## 6.8 Nutrition Interpretation

Nutrition-related survey responses provide information about reported dietary behaviours but may not provide a complete assessment of nutritional status.

The dataset may not contain clinical information such as:

* Laboratory measurements
* Diagnosed deficiencies
* Detailed nutrient quantities
* Complete dietary records
* Medical dietary requirements

Therefore, the project should distinguish between:

> **Reported nutrition/dietary behaviour**

and

> **Clinical nutritional status**

The project will primarily analyze the former.

---

## 6.9 Missing Data

Some survey questions may contain missing or incomplete responses.

Different approaches may eventually be considered depending on the variable and amount of missingness, including:

* Retaining missing values
* Removing particular observations where justified
* Removing unsuitable variables
* Appropriate imputation techniques

No single missing-data strategy will automatically be applied to every variable.

The reason for each major treatment decision should be documented.

---

## 6.10 Outliers and Unusual Responses

Some responses may appear substantially different from the majority of observations.

However, an unusual value is not automatically an error.

The project will distinguish between:

* Data-entry errors
* Impossible values
* Valid but uncommon observations
* Potentially interesting unusual patterns

Outliers will therefore be investigated before being removed or transformed.

Later in the project, anomaly-detection techniques may also be explored where appropriate.

---

## 6.11 Feature Selection and Construction

The questionnaire may contain multiple variables describing related aspects of wellness and lifestyle.

Challenges may include:

* Redundant variables
* Highly related features
* Irrelevant variables
* Categorical encoding
* Selecting useful predictors
* Constructing meaningful derived features

Any composite indicator or wellness-related score created from multiple responses should have a clear rationale.

Features will not be combined arbitrarily merely to simplify modeling.

---

## 6.12 Association vs Causation

A major analytical challenge is avoiding unsupported causal interpretation.

Because the initial dataset is primarily observational and survey-based, relationships found between variables generally represent **associations**.

For example:

> A relationship between dietary behaviour and mental wellness does not automatically prove that the dietary behaviour caused the observed mental-wellness difference.

Other variables may contribute to the relationship, and the direction of influence may not be identifiable from the available data.

The project will clearly distinguish between:

* Correlation
* Association
* Prediction
* Causation

---

## 6.13 Confounding Factors

Mental wellness and lifestyle behaviours may be influenced by many factors.

Potential confounding or contextual variables could include factors represented in the dataset such as:

* Sleep
* Academic routine
* Demographic characteristics
* Physical activity
* Other lifestyle behaviours

There may also be important factors that were not measured by the questionnaire.

This limitation must be considered when interpreting observed relationships.

---

## 6.14 Statistical Assumptions

Different statistical methods rely on different assumptions.

Before applying a statistical test or model, the project should consider factors such as:

* Variable type
* Distribution
* Independence
* Sample size
* Variance
* Group sizes
* Other method-specific assumptions

A statistical technique should not be used simply because it appears in the syllabus.

The available data and analytical question must justify its use.

---

## 6.15 Multiple Comparisons

As the number of variables increases, the number of possible relationships that can be tested also increases.

Testing many relationships can increase the probability of finding apparently significant results by chance.

Therefore, later statistical analysis should:

* Begin with meaningful research questions
* Avoid unnecessary hypothesis testing
* Interpret p-values carefully
* Consider appropriate multiple-comparison procedures where required

---

## 6.16 Model Selection

The course introduces multiple machine-learning algorithms.

A major challenge will be selecting models appropriate to:

* The available sample size
* Feature types
* Target variable
* Analytical objective
* Interpretability requirements

Multiple algorithms may be experimentally compared where appropriate.

The final system does not need to contain every algorithm tested during the project.

---

## 6.17 Overfitting and Data Leakage

With a relatively small dataset, complex models may learn patterns specific to the collected sample rather than generalizable relationships.

Potential risks include:

* Overfitting
* Improper train/test separation
* Feature leakage
* Target leakage
* Performing preprocessing using information from evaluation data
* Excessive model tuning on a small test set

Proper evaluation procedures will be required once modeling begins.

---

## 6.18 Class Imbalance

If a future classification target is created or selected, its categories may not contain similar numbers of observations.

Class imbalance can affect model training and evaluation.

If this issue occurs, appropriate techniques and evaluation metrics will be considered.

Class balance will not be assumed before the actual target variable is identified.

---

## 6.19 Clustering and Profile Interpretation

Unsupervised-learning techniques may later be used to investigate possible student wellness profiles.

However, clusters produced by an algorithm do not automatically represent meaningful real-world groups.

Challenges include:

* Selecting appropriate features
* Choosing the number of clusters
* Scaling variables
* Comparing clustering techniques
* Evaluating cluster quality
* Interpreting discovered groups responsibly

Any identified cluster will be treated as a **data-derived pattern**, not a medical or psychological category.

---

## 6.20 Recommendation Safety

A future version of the project may provide personalized general wellness insights.

This introduces additional responsibility.

Recommendations should:

* Remain within general wellness boundaries
* Be explainable
* Avoid diagnosis
* Avoid medical treatment advice
* Avoid therapeutic dietary prescriptions
* Avoid unsupported claims
* Use appropriate and credible knowledge sources where external guidance is required

The recommendation system should also be capable of acknowledging when the available data is insufficient to provide a meaningful personalized suggestion.

---

## 6.21 Privacy and Data Protection

The dataset contains information related to student wellness and lifestyle.

Even if the dataset does not contain direct identifiers, combinations of variables may potentially reveal information about individuals.

The project should therefore follow principles such as:

* Collect only information relevant to the project
* Avoid unnecessary personal identifiers
* Store raw data responsibly
* Avoid publishing identifiable individual responses
* Use anonymized or appropriately de-identified data for analysis where possible
* Restrict unnecessary exposure of sensitive responses

Public GitHub repositories require particular caution.

**Raw identifiable or sensitive survey responses should not be uploaded publicly.**

---

## 6.22 Ethical Interpretation

Mental-wellness and nutrition data can easily be oversimplified or stigmatized.

The project should avoid language that labels students as:

* "Mentally unhealthy"
* "Bad eaters"
* "Unfit"
* "Problem students"

Analytical outputs should use neutral and descriptive terminology.

The goal is to understand patterns and support wellness awareness, not to judge participants.

---

## 6.23 Reproducibility

As the project becomes more complex, analyses must remain reproducible.

Potential challenges include:

* Different dataset versions
* Manual preprocessing
* Undocumented transformations
* Changing feature definitions
* Multiple experimental models
* Inconsistent notebook execution

DataOps and MLOps practices will progressively be introduced to improve reproducibility and organization.

---

## 6.24 Scope Management

The FDS syllabus contains a broad range of topics.

There is a risk of turning the project into a collection of unrelated demonstrations simply to use every technique.

The project will instead attempt to connect each relevant concept to the central analytical story:

> **Understanding college-student mental wellness and its relationships with nutrition, physical activity, and lifestyle through Data Science.**

Techniques that are useful experimentally but unsuitable for the final system may still be studied and documented without being forced into the application.

---

## 6.25 Current Challenges

At the present stage, the most immediate challenges are:

1. Formally understanding the collected survey dataset.
2. Documenting each variable.
3. Assessing the quality of approximately 100 collected responses.
4. Protecting participant privacy.
5. Determining how well the questionnaire represents the intended project domains.
6. Avoiding premature conclusions about nutrition and mental wellness.
7. Preparing the project for future statistical analysis.

These challenges will be addressed progressively as the project moves into the data-understanding and data-preparation stages.
