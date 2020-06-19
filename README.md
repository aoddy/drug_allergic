# Drug Allergic
The prediction model for drug allergic by using logistic regression.

# Problem introduction
- All doctors want to avoid prescribing drugs that maybe allergic to the patients
- Enzyme-linked immunospot (ELISpot) is a laboratory technique that tests whether the patient's immune cells will respond to particular drugs. This allows doctor to screen whether a drug is likely to be safe for the patient.
- As with any test, ELISpot is not perfect. Drugs that the patient is allergic to sometimes do not elicit any response in ELISpot test (False Negative) and vice versa.
- Hence, we want to develop a prediction model for drug allergy based on patient information, drug information, and ELISpot result.

# The dataset
- Here, we have put together an anonymized dataset of ELISpot test results for ~800 patient and drug combinations.
- Ground truth drug allergy labels (last column) are available for only 14% of the dataset (115 patient and drug combinations). This is because the only way to obtain ground truth for drug allergy is to re-challenge the patients with the suspected drugs.
- There are also some missing feature values. This is because some information is not available for some patients.

# The tasks
- Develop and present a prediction model for drug allergy.
- Address the issue of missing feature values in some way.
- Make use of data points with missing ground truth labels.

# Acknowledgements

We would like to thank Assoc. Prof. Jettanong Klaewsongkram and Dr. Yuda Chongpison for collecting and sharing the dataset. 

# License

All information contained in this dataset is confidential and should not be shared outside of Chulalongkorn University's AI Academy staff and examinees.
** I am not sharing the dataset but I need to share my python model.
