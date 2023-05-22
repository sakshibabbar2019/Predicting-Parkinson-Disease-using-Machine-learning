# Predicting-Parkinson-Disease-using-Machine-learning
This project addresses problem of early detection of Parkinson disease using Machine learning techniques
mptom progression often uses the Unified Parkinson’s Disease Rating Scale (UPDRS), which requires the patient's presence in clinic, 
and time-consuming physical examinations by trained medical staff. It makes early detection of disease difficult. However, in recent studies
remote replication of UPDRS has appeared as an alternative approach to predict this disease. Wherein, range of biomedical voice measurements were captured 
using telemonitoring deive installed at patient's home. These biomedical voice measurements meaures the remote symptom progression.


Researchers Athanasios Tsanas and Max Little of the University of Oxford, in collaboration with 10 medical centers in the US and Intel Corporation
developed the telemonitoring device to record the speech signals and presented it in a form of data set for analysis purpose. The data set is available on UCI 
repository weblink https://archive.ics.uci.edu/ml/datasets/Parkinsons+Telemonitoring . The data set is composed of a range of biomedical voice measurements from 
42 people with early-stage Parkinson's disease recruited to a six-month trial of a telemonitoring device. It has 5875 cases represented in 20 features.

The details of features are as below:

1. age - Subject age

2. sex - Subject gender '0' - male, '1' - female

3. test_time - Time since recruitment into the trial. The integer part is the number of days since recruitment

4. motor_UPDRS - Clinician's motor UPDRS score, linearly interpolated

5. total_UPDRS - Clinician's total UPDRS score, linearly interpolated

6. Jitter(%)

7. Jitter(Abs)

8. Jitter:RAP

9. Jitter:PPQ5

10. Jitter:DDP - Several measures of variation in fundamental frequency

11. Shimmer

12. Shimmer(dB)

13. Shimmer:APQ3

14. Shimmer:APQ5

15. Shimmer:APQ11

16. Shimmer:DDA - Several measures of variation in amplitude

17. NHR

18. HNR - Two measures of ratio of noise to tonal components in the voice

19. RPDE - A nonlinear dynamical complexity measure

20. DFA - Signal fractal scaling exponent

21. PPE - A nonlinear measure of fundamental frequency variation

Given this medical data set, the objectives of this project is to:

1. Predict total_UPDRS score given voice measurements as features

2. Identify important features that influence total_UPDRS score

3. Relational strength between total_UPDRS score and other features present in the data set

4. Discover if the diease is age specific
