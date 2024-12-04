# Foetal-health-Analysis
## Introduction

Fetal health classification is a crucial area of medical research, aimed at early detection of potential health risks during pregnancy. The fetal period is a critical stage of development, where complications such as fetal distress, congenital abnormalities, or other health conditions can have long-lasting impacts on both the mother and child. Monitoring fetal health through various medical techniques—such as cardiotocography (CTG), ultrasound, and other diagnostic tests—enables healthcare providers to intervene early, ensuring better outcomes for both the fetus and mother.

Using features extracted from Cardiotocogram exams, this project focuses on using advanced machine learning techniques to classify fetal health as either, Normal,Suspect or Pathological.

## Problem Definition

Our Task is to :

1.  Conduct an in-depth analysis of vital fetal indicators, focusing on various features and their interconnected relationships.

2.  Classify fetal health to prevent child and maternal mortality (build a predictive model to classify the observations into their respective fetal health category, i.e., Normal or Suspect or Pathological).

## Metrics of Success

The success of the fetal health classification model will be measured using various performance metrics such as accuracy, precision, confusion matrix.

## Data Description

The attached dataset consists of measurements of fetal heart rate (FHR) and uterine contraction (UC) features on CTGs classified by expert obstetricians. There are a total of 22 Variables in the fetal health dataset. Predictor variables are 21 (20 numeric and 1 categorical). The response variable (fetal_health) has 3 categories: Normal, Suspect and Pathological.

**Features**:

-   baseline value - Baseline Fetal Heart Rate (FHR) (beats per minute)
-   accelerations - Number of accelerations per second
-   fetal_movement - Number of fetal movements per second
-   uterine_contractions - Number of uterine contractions per second
-   light_decelerations - Number of light decelerations per second
-   severe_decelerations - Number of severe decelerations per second
-   prolongued_decelerations - Number of prolonged decelerations per second
-   abnormal_short_term_variability - Percentage of time with abnormal short-term variability
-   mean_value_of_short_term_variability - Mean value of short-term variability
-   percentage_of_time_with_abnormal_long_term_variability - Percentage of time with abnormal long-term variability
-   mean_value_of_long_term_variability - Mean value of long-term variability
-   histogram_width - Width of FHR histogram (generated from exam)
-   histogram_min - Minimum of FHR histogram (generated from exam)
-   histogram_max - Maximum of FHR histogram (generated from exam)
-   histogram_number_of_peaks - Number of FHR histogram peaks (generated from exam)
-   histogram_number_of_zeroes - Number of FHR histogram zeroes (generated from exam)
-   histogram_mode - Mode of FHR histogram (generated from exam)
-   histogram_mean - Mean of FHR histogram (generated from exam)
-   histogram_median - Median of FHR histogram (generated from exam)
-   histogram_variance - Variance of FHR histogram (generated from exam)
-   histogram_tendency - Tendency of FHR histogram (generated from exam)

**Target**:

-   fetal_health - Fetal health as assessed by expert obstetrician. 1 - Normal, 2 - Suspect, 3 - Pathological
