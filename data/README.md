# Data Directory

## Overview

This directory is intended to contain datasets used by the **Mental Wellness & Nutrition Project**.

The project currently uses **primary survey data collected from college students**. Approximately 100 responses have been collected so far.

The questionnaire contains information related to areas such as:

* Mental wellness
* Nutrition and dietary habits
* Physical activity and mobility
* Sleep and daily routine
* Other relevant lifestyle or contextual characteristics

The exact variables and their analytical roles will be documented after formal inspection of the collected dataset.

---

## Planned Data Organization

As the project develops, the data directory may be organized into separate stages such as:

```text id="3plwpc"
data/
│
├── raw/
├── processed/
└── README.md
```

### `raw/`

Contains the original collected data before analytical modifications.

Raw data should remain unchanged so that all preprocessing steps can be reproduced.

### `processed/`

Contains cleaned, transformed, encoded, or otherwise analysis-ready versions of the dataset.

Processed datasets should be generated through documented and reproducible data-preparation steps whenever possible.

---

## Data Dictionary

A data dictionary will be created after the survey dataset is formally inspected.

It will document information such as:

* Variable name
* Original survey question
* Wellness domain
* Description
* Data type
* Possible values or categories
* Missing-value representation
* Intended analytical role
* Transformations or encoding applied
* Relevant limitations

Variables may be grouped into categories such as:

```text id="9i3cv2"
Context / Demographic
Mental Wellness
Nutrition
Physical Activity / Mobility
Other Lifestyle Factors
```

The final grouping will depend on the actual questionnaire and collected dataset.

---

## Data Preparation

Future data-preparation work may include:

* Data-quality assessment
* Missing-value analysis
* Duplicate checking
* Data-type correction
* Category standardization
* Outlier investigation
* Categorical encoding
* Data transformation
* Feature construction
* Dataset versioning

No cleaning or transformation should overwrite the original raw dataset.

---

## Privacy and Repository Policy

The survey contains student wellness and lifestyle information.

Therefore, participant privacy must be considered before any dataset is published.

**Raw identifiable or potentially sensitive survey responses should not be uploaded to the public GitHub repository.**

Before publishing any dataset, the project should check for:

* Names
* Email addresses
* Student identifiers
* Contact information
* Automatically collected identifying metadata
* Free-text responses containing identifying information
* Combinations of variables that could unnecessarily expose individual participants

Where appropriate, data should be anonymized or de-identified before being shared publicly.

The Git repository may therefore contain documentation and processing code without containing the private raw dataset itself.

---

## Current Status

Current data status:

* Survey questionnaire created
* Approximately 100 responses collected
* Primary dataset available
* Formal dataset inspection not yet completed
* Data dictionary not yet created
* Data cleaning not yet performed
* Processed dataset not yet created
* Exploratory Data Analysis not yet performed

The next data-related stage will be to inspect the collected survey dataset, document its variables, and assess its quality before beginning formal analysis.
