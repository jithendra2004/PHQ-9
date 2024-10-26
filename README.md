# Title of the Project
DEPRESION PATTERN RECOGNITION FOR BIPOLAR DISORDERED PATIENTS USING K MEANS CLUSTERING
## About

- To detect factors strongly related to the diagnosis of depressive conditions.
- To aid in the outpatient screening process for potentially depressed patients.
- To assist in the development of personalized treatment plans for patients diagnosed with depression.

## Additional information about the PHQ-9

The [Patient Health Questionnaire-9 (PHQ-9)](https://www.mdcalc.com/calc/1725/phq9-patient-health-questionnaire9#next-steps) is a widely used tool for screening and assessing the severity of depression in patients. It consists of nine questions that ask about the presence and severity of common symptoms of depression, such as feelings of sadness or hopelessness, loss of interest in activities, sleep disturbance, changes in appetite or weight, fatigue, and difficulty concentrating.

Each question is scored from 0 to 3, with a total possible score of 27:

- 0 - 4 (Minimal or none): Monitoring, may not require treatment
- 5 - 9 (Mild): Use clinical judgment (duration of symptoms, functional impairment)
- 10 - 14 (Moderate): Same as mild
- 15 - 19 (Moderately severe): Active treatment with psychotherapy, medication, or combination is warranted
- 20 - 27 (Severe): Same as moderately severe


Ambulatory assessment (AA) refers to medical evaluations conducted outside of a hospital or clinical environment (q1-q4, q16, q46 and q47 instances). These evaluations are performed in an environment where the patient is free to carry out their daily activities, that is, they have not been admitted. In this study, AA was conducted using the "Moodpath" app. However, there was a significant amount of missing data over time, possibly due to patients being too sad or simply ignoring the app's reminders to answer the questions, as many of us do. It appears that the app has since been renamed "MindDoc: Your Companion" and now frequently prompts users to respond to the assessment questions every day.
From the analysis of the above graphs, we can see that:

Cluster 0: Mostly men under 35 years old who suffer from moderate/severe depression.

Cluster 1: Young women who suffer from moderate/severe depression.

Cluster 2: Elderly women who suffer from moderate/severe depression.

Cluster 3: Elderly men who have either mild or no depression symptoms.

Cluster 4: Young women who suffer from mild/moderate depression.
# System Architecture:
![ph9 drawio (3) drawio-1](https://github.com/user-attachments/assets/85e10e73-3514-40e2-ad21-fa85b867f17c)

Based on the provided cluster analysis of depression levels using PHQ-9, the following clusters should be considered for clinical analysis and medical follow-up: Cluster 0, 1 and 2. These clusters have higher levels of depression severity and may require further medical attention and treatment. It is important to note that cluster analysis is just one tool in the assessment of depression and a more comprehensive evaluation is required for individualized treatment plans.
## Output:
![image](https://github.com/user-attachments/assets/6268fe90-031f-4c4d-b11f-7f8c0098cec5)
![image](https://github.com/user-attachments/assets/b76a637d-81dc-4210-823d-9c337b2f2655)

The graph mention that the depression severity on the male and female .
According to the occurred happiness score we can say that the depression severity in women was high.
## Results:
The happiness score differs from the male,female,transgender this shows that the women took the test multiple times .
Thus women has high depression severity
## Articles published / References
Faurholt-Jepsen, M., Frost, M., Ritz, C., et al. (2019). Daily electronic self-monitoring in bipolar disorder using smartphones—The MONARCA trial: a randomized, controlled trial protocol. BMC Psychiatry, 19(1), 122. doi: 10.1186/s12888-019-2100-2.
 
Rohani, D. A., Faurholt-Jepsen, M., Kessing, L. V., & Bardram, J. E. (2018). Correlations between objective smartphone data and weekly mood ratings in bipolar disorder patients: a machine learning approach. IEEE Journal of Biomedical and Health Informatics, 22(1), 203-213. doi: 10.1109/JBHI.2017.2689019.




