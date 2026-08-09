# Kinetra Data

## 1. Purpose

The `data/` directory contains the datasets used by the Kinetra Data Science project.

The data will be used for activities such as:

* Data understanding
* Data preparation
* Exploratory Data Analysis
* Statistical analysis
* Machine learning
* Model evaluation
* Development of personalized guidance

---

## 2. Data Organization

As the project develops, the data directory may be organized into different stages:

```text
data/
│
├── raw/
│   └── Original, unmodified data
│
├── processed/
│   └── Cleaned and transformed data
│
└── README.md
```

The exact organization may be adjusted depending on the dataset and project requirements.

---

## 3. Raw Data

The `raw/` directory is intended for the original dataset obtained from the selected data source.

Raw data should not be manually modified.

Keeping the original data unchanged helps maintain:

* Reproducibility
* Data provenance
* Transparency
* The ability to repeat the data-preparation process

---

## 4. Processed Data

The `processed/` directory is intended for data that has been cleaned and transformed for analysis or modeling.

Processing may include:

* Handling missing values
* Removing or handling duplicate records
* Correcting inconsistent values
* Encoding categorical variables
* Feature engineering
* Feature selection
* Scaling or transformation where appropriate

The exact processing steps will be documented as the project progresses.

---

## 5. Dataset Selection

The final dataset has not yet been selected.

Once a suitable dataset is identified, this README will be updated with relevant information such as:

* Dataset name
* Source
* Dataset description
* Number of observations
* Number of variables
* Data format
* License or usage conditions
* Relevant limitations

---

## 6. Data Privacy

Kinetra may involve information related to physical activity, pain, lifestyle, or other potentially sensitive areas.

Therefore:

* Unnecessary personally identifiable information should not be included.
* Data should be handled responsibly.
* Applicable privacy and data-protection requirements should be considered.
* Dataset licensing and usage conditions should be respected.

Where possible, datasets should be anonymized or appropriately de-identified.

---

## 7. Data Reproducibility

The project should preserve the relationship between the original data and the processed data.

Data-processing operations should preferably be performed through reproducible code rather than manual modification.

The objective is to ensure that:

```text
Raw Data
   ↓
Data Preparation
   ↓
Processed Data
   ↓
Analysis / Modeling
```

can be reproduced when required.

---

## 8. Current Status

At the current stage of the project, the final dataset has not yet been added.

This directory will be updated once the data source has been selected and the Data Science workflow progresses to the data-handling stage.
