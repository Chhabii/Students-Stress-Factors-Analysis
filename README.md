Project Overview
## Student Stress Analysis: Exploring Factors and Relationships

This project aims to analyze the Student Stress Dataset and identify key factors contributing to student stress levels. By examining various psychological, physiological, environmental, academic, and social factors, we hope to gain insights into student well-being and potential areas for intervention.

### Methodology

1. **Data Preprocessing:** We loaded the "Student Stress Factors - A Comprehensive Analysis" dataset from Kaggle using Pandas.
2. **Descriptive Statistics:** Descriptive statistics were calculated to understand the overall distribution of factors like anxiety, sleep quality, and academic performance. 
3. **Negative Experience Analysis:** The number of students reporting negative experiences for each factor was computed using thresholds or binary classifications. 
4. **Visualization and Correlation:** Bar charts, scatterplots, heatmaps, and box plots were created to visualize relationships and trends between different factors. 
5. **Feature Importance Analysis:** Random Forest Regressor and SelectFromModel were used to assess the influence of individual features within each factor on stress levels.

### Results

**Key Findings:**

* The dataset includes **1100** students.
* Average anxiety level is **11** on the **Hamilton Anxiety Rating Scale (HAM-A)**.
* **(Factor: Psychology-> Feature: self-esteem, Factor: Physiological-> Feature: sleep_quality,Factor: Environmental-> Feature: basic_needs,Factor: Academic-> Feature: academic_performance,Factor: Social-> Feature: bullying )** have the highest impact on stress.

**Visualizations:**
![image](https://github.com/Chhabii/Students-Stress-Factors-Analysis/assets/60286478/82c1061a-50c2-4d46-89c0-189b2490c6b2)
![image](https://github.com/Chhabii/Students-Stress-Factors-Analysis/assets/60286478/44ab166b-6701-4689-8f98-e7976f21d6fc)
![image](https://github.com/Chhabii/Students-Stress-Factors-Analysis/assets/60286478/94fc9ed7-ff83-4bc9-ae17-9afb454e983b)
![image](https://github.com/Chhabii/Students-Stress-Factors-Analysis/assets/60286478/33e0c9a4-0902-43c2-a613-b0a407eae1f6)
![image](https://github.com/Chhabii/Students-Stress-Factors-Analysis/assets/60286478/96e02484-50f9-48d6-be13-dd9390e876fe)
![image](https://github.com/Chhabii/Students-Stress-Factors-Analysis/assets/60286478/cad93728-51ee-4a61-a5cf-547aa05c2367)
![image](https://github.com/Chhabii/Students-Stress-Factors-Analysis/assets/60286478/91c3db54-f4b4-4dee-a86e-5cca1478dd63)
![image](https://github.com/Chhabii/Students-Stress-Factors-Analysis/assets/60286478/1b608938-1ada-440f-adfa-e57e2681efba)
![image](https://github.com/Chhabii/Students-Stress-Factors-Analysis/assets/60286478/e9a0f4a4-7887-4e30-85c1-05fb9f63e577)
![image](https://github.com/Chhabii/Students-Stress-Factors-Analysis/assets/60286478/0bcd5283-6dfd-4085-a56b-d74c18427471)

**Limitations:**

* The chosen dataset might not represent the entire student population.
* Further research is needed to explore causal relationships and intervention strategies.

### Code and Resources

The analysis code can be found in the [`Notebook`](https://github.com/Chhabii/Students-Stress-Factors-Analysis/blob/master/student-stress-factors.ipynb). The dataset was sourced from Kaggle: [`Dataset`](https://www.kaggle.com/datasets/rxnach/student-stress-factors-a-comprehensive-analysis).

### Future Directions

* Apply machine learning models for stress prediction based on various factors.
* Investigate the effectiveness of specific interventions for stress reduction.
* Analyze data from diverse student populations.

### Important Papers
* [MANUAL OF STUDENT STRESS INVENTORY (SSI) Development, Validity And Reliability of Student Stress Inventory (SSI)](https://www.researchgate.net/publication/316662054_MANUAL_OF_STUDENT_STRESS_INVENTORY_SSI_Development_Validity_And_Reliability_of_Student_Stress_Inventory_SSI)
* [Evaluation of the Student Life-stress Inventory-Revised](https://www.researchgate.net/publication/286926169_Evaluation_of_the_Student_Life-stress_Inventory-Revised)

We hope this analysis provides valuable insights into student stress and motivates further research in this crucial area.

