# Heart-Failure-Analysis-and-visualization :stethoscope:
* Heart Failure Analysis and visualization of 12 clinical features for predicting death events.
* The 12 clinical features include: age, anaemia, creatinine_phosphokinase, diabetes, ejection_fraction, high_blood_pressure, platelets, serum_creatinine, serum_sodium, sex, smoking, and time. 

# About Dataset 
Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worlwide.
Heart failure is a common event caused by CVDs and this dataset contains 12 features that can be used to predict mortality by heart failure.

Most cardiovascular diseases can be prevented by addressing behavioural risk factors such as tobacco use, unhealthy diet and obesity, physical inactivity and harmful use of alcohol using population-wide strategies.

People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.

# :dart: Analysis Goal 
## Find out the following :->

1. **Is there a relationship between gender and heart failure ?** 

2. **Is there a relationship between Age with heart failure ?** 

3. **Is there a relationship between Diabetes with heart failure ?**

# :toolbox: libraries used
1. pandas
2. matplotlib
3. seaborn


# Repository Map
1. :ballot_box_with_check: heart_failure_clinical_records_dataset.csv - the dataset used in the analysis
2. :ballot_box_with_check: Heart-Failure-Analysis-and-visualization.ipynb - the jupyter notebook containing all the code, all analysis and visualization. 
3. :ballot_box_with_check: README.md

# Inspiration
**Why this analysis ?**

Coronary Heart Diseases is not a new occurrence in Kenya Today.
According to the latest WHO data published in 2020 Coronary Heart Disease Deaths in Kenya reached 11,972 or 4.54% of total deaths. The age adjusted Death Rate is 72.70 per 100,000 of population ranks Kenya #144 in the world.

However, There has been an increasing rate of Coronary Heart Disease in Kenya ever since 2018. This motivated me to understanding the causes of the increase in Coronary Heart Diseases and death rate in Kenya.

During my analysis I found out that tobacco use and exposure to tobacco smoke is a major cause of raised blood pressure and other forms of CVDs including heart attack and stroke that eventually result to high death-rates  


# Data analyis goals Findings and chart
1. **Is there a relationship between gender and heart failure ?** YES! From the data, it is observed that the male have more death count compared to women and hence are more likely to succumb to heart failure.
## chart
![gender and heart failure Linechart](https://george.m.ndichu.ltd.co.ke/media/github/gender-death-rel%20count%20plot.png "Relationship between gender and heart failure Linechart")

2. **Is there a relationship between Age with heart failure ?** YES! From the data, it is observed that Older people compared to the young are prone to succumbing to heart failure
## chart
![Age and heart failure Lineplot](https://george.m.ndichu.ltd.co.ke/media/github/age-heart-failure-lineplot.png "Relationship between age and heart failure Line plot")

3. **Is there a relationship between Diabetes with heart failure ?** NO! From the data, it is observed that there is little to no relationship between diabetes and heart failure
## chart 1
![Diabetes and heart failure Countplot](https://george.m.ndichu.ltd.co.ke/media/github/diabetes-heart-failure-countplot.png "Relationship between Diabetes and heart failure Count plot")
 ## chart 2
![Diabetes and heart failure Line plot](https://george.m.ndichu.ltd.co.ke/media/github/diabetes-heart-failure-lineplot.png "Relationship between Diabetes and heart failure Line plot")

# Research Findings
1. **Awareness** is paramount in the control of Coronary Heart Diseases in Kenya.

2. **Smoking** and **exposure to smoke** (Especially smoking tobacco and exposure to tobacco) is a major cause of raised blood pressure and other forms of CVDs including heart attack and stroke.

3. **Educating the public** on **adopting healthy lifestyles** is also key in the control of Coronary Heart Diseases in Kenya. More than half (56%) of the adult population has never had their blood pressure measured yet almost 1 in 4 Kenyans is living with hypertension and with just about a quarter of them being on medication.

4. About 11.6% (2.5 Million) of adult Kenyans and 9.9 % of youth aged between 13 -15 years use tobacco products; while 86.1% of adults are exposed to **second-hand tobacco smoke** in bars and night clubs and 24.8% of youth being exposed at home. This demonstrates that a high number of Kenyans are prone to tobacco-related NCDs such as hypertension and other CVDs

# :black_nib: Acknowledgements
## Citation
-Davide Chicco, Giuseppe Jurman: Machine learning can predict survival of patients with heart failure from serum creatinine and ejection fraction alone. BMC Medical Informatics and Decision Making 20, 16 (2020). (link)

# Provenance
## SOURCES

[VIEW SOURCE ](https://archive.ics.uci.edu/ml/datasets/Heart+failure+clinical+records) or <https://archive.ics.uci.edu/ml/datasets/Heart+failure+clinical+records>

## COLLECTION METHODOLOGY
Please refer to source.

## License
**Attribution 4.0 International (CC BY 4.0)**
