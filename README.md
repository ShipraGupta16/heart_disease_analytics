### heart disease data analytics

Dataset taken from: https://archive.ics.uci.edu/dataset/45/heart+disease

#### Data Dictionary:
* Age: Age in years
* sex: 1 for male and 0 for female
* cp: chest pain type
	1: typical angina,
	2: atypical angina,
	3: non-anginal pain,
	4: asymptomatic.
* resting_blood_pressure: resting blood pressure in mm Hg while admitted to admitted. Above 130 is considered to be concerning
* serum_Choleresterol: in mg/dl
* fasting_blood_sugar>120: fasting blood sugar > 120 mg/dl (1 is True; 0 is False)
* restECG: resting electrocardiographic result where 0 is nothing to note, 1: ST-T wave abnormality with mild to severe problems, signal non-normal heart beat.
* maximum_heart_rate: Maximum heart rate achieved in beats per minute.
* exercise_induced_angina: 1 for yes; 0 for no
* oldpeak: ST depression induced by exercise relative to rest. Analyzes stress of heart during exercise.
* slope: slope of the peak exercise ST segment.
	1: upsloping: better heart rate with exercise (uncommon),
	2: Flatsloping: minimal change (typical healthy heart)
	3: Downsloping
* ca: Number of major vessels (0-3) colored by flouroscopy colored vessel indicate doctor can see the bloof passing through. The more blood movement, the better results (indicating no clots)
* thal: Thalium stress result.
	1,3 for normal;
	6 for fixed defect: used to be defect but fine now.
	7: reversable defect: no proper blood movement when exercising.
* Target: num or outcome variable for diagnosis of disease.


#### Tech stack: Python(Pandas, matplotlib, seaborn), MySQL, Tableau

#### Questions explored

* Finding the Average Cholesterol Level by Gender and Age Group.
* Find the Maximum, Minimum, and Average Heart Rate by Age Group.
* Find Patients with above average Resting Blood Pressure.
* Identify high risk patients for developing heart diseases.
* Identify the Average Heart Rate (Thalach) by Age Group.
* Identify any relationship between age and maximum heart rate (thalach).
* Identify which gender are more prone to developing heart diseases from this dataset.

#### Tableau Dashboard link to view Visualization Dashbaord: 
https://public.tableau.com/app/profile/shipra.vinod.gupta/viz/heart_disease_dashboard_17161870526720/HeartDiseaseDashboard?publish=yes




