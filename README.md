# Healthcare-Diabetes-Analysis
I explored the causes, effects, and management strategies of diabetes through data analysis. This project was not just a learning experience but a chance to uncover key insights about the factors driving the alarming rise in diabetes across various age groups.
[Download this](https://www.linkedin.com/posts/adebusola-akanni-b20668246_the-multifaceted-nature-of-diabetes-insights-activity-7286335576591466496--cuX?utm_source=share&utm_medium=member_desktop&rcm=ACoAADz3SkgBsxrRBql8jV7Nlttz1xCJ8pIoMf4)
## Diabetes, a Global Health Challenge
Diabetes mellitus, commonly referred to as diabetes, is more than a single condition — it’s a complex illness with varying forms and impacts. Affecting millions of people worldwide, diabetes is far-reaching and multifaceted, often misunderstood in its scope and implications.
![Image](https://github.com/user-attachments/assets/6175501a-0218-410d-a597-520728fcbdba)
This article delves into the intricate web of factors influencing diabetes, sheds light on emerging research patterns, and discusses actionable insights for patients, healthcare professionals, and researchers alike.
### What Is Diabetes?
At its core, diabetes occurs when blood glucose levels are consistently too high. This happens due to:
-  Insufficient insulin production: The pancreas does not produce enough insulin.
-  Ineffective insulin use: The body cannot effectively use the insulin it produces.
-  No insulin production: In some cases, the pancreas fails to produce insulin entirely.
Left unmanaged, diabetes can lead to severe complications, including:
-  Eye damage (diabetic retinopathy)
-  Kidney issues (nephropathy Nerve damage (neuropathy)
-  Cardiovascular diseases
-  ### About the Project - Dataset
-  ![image](https://github.com/user-attachments/assets/3fde0467-feb6-4ef0-8438-dc64423506ef)
The dataset comprises 2,768 observations and provides summary statistics for various health-related attributes, including Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age, and the Outcome. The evaluation criteria are also provided for Glucose, BMI, and Age, classifying individuals into categories such as “Diabetes”, “Obese”, or “Young Adult.” Below is an analysis of the most critical observations:

### Descriptive Statistics
-  Pregnancies
Mean: 3.74, with a median of 3 pregnancies.
Range: 0 to 17 pregnancies.
Skewness: 0.96 indicates a right-skewed distribution (more individuals with fewer pregnancies).
-  Glucose
Mean: 121.1 mg/dL, with a median of 117.
Range: 0 to 199, though glucose levels below 70 are typically considered hypoglycemic.
Skewness: 0.16 suggests a slightly right-skewed distribution.
Evaluation Criteria: Glucose levels are classified as:
A) Normal: No health concerns.
B) Prediabetes: Higher risk of developing diabetes.
C) Diabetes: Indicates a confirmed diagnosis.
-  Blood Pressure
Mean: 72.25 mmHg, with a median of 72.
Range: 24 to 122, indicating outliers on the lower end.
Skewness: 0.23 shows near-symmetry.
-  Skin Thickness
Mean: 27.47 mm, with a median of 23.
Range: 7 to 110 mm, with noticeable variance.
Skewness: 1.51, indicating significant right skewness (many individuals have low values).
-  Insulin
Mean: 97.91 µU/mL, with a median of 37.
Range: 14 to 846, showing extreme variability.
Skewness: 2.57 suggests significant right skewness (many individuals have low insulin levels).
-  BMI
Mean: 32.59, indicating the average is in the Obese range.
Range: 18.2 to 80.6.
Skewness: 0.85 suggests mild right skewness.
Evaluation Criteria: Individuals are classified as:
Normal: Healthy BMI.
Overweight: At risk of complications.
Obese: Indicates higher risk.
-  Diabetes Pedigree Function
Mean: 0.47, with a range of 0.078 to 2.42
Skewness: 1.84 indicates significant right skewness, suggesting most values are low.
-  Age
Mean: 33.13 years, with a median of 29.
Range: 21 to 81 years.
Skewness: 1.17 indicates a slight right skew (more young individuals in the dataset).
Evaluation Criteria:
Young Adult: Younger individuals.
Middle Adult: Mid-life group.
Old Adult: Older individuals.
-  Outcome
Mean: 0.34 indicates around 34% of individuals are diabetic.
Distribution:
0: Non-diabetic.
1: Diabetic.
### Key Factors Influencing Diabetes Outcome
![Image](https://github.com/user-attachments/assets/17cb988e-3a61-454f-8980-7e3c54d5e99f)
Recent analyses have uncovered intriguing patterns between specific variables and diabetes outcomes:

### Strong Positive Correlations
A) Glucose levels
![Image](https://github.com/user-attachments/assets/ddf78409-42c5-406d-9680-b94a9502b8da)
![Image](https://github.com/user-attachments/assets/702c7332-7819-4e9a-90bd-e66644cdf3e0)
![Image](https://github.com/user-attachments/assets/816c9809-4f4a-4ea0-bd40-47b168292443)
![image](https://github.com/user-attachments/assets/d117ea4d-a9b6-40cb-ba94-807a8c865b6f)

