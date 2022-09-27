# EXPLORATION ANALYSIS OF CHILD VIOLENCE CASES IN NORTH SUMATRA PROVINCE 2017-2019 USING NAÏVE BAYES ALGORITHM

## INTRODUCTION
Hello👋, in this project i conducted an exploratory analysis of violence against children in the province of North Sumatra from 2017 to 2019. The purposes is to determine opportunities for children by gender who experience violence assuming that the victim is under 18 years of age and has received special services.
The data used were taken through the official website of SIGA and Dinas Pemberdayaan Perempuan dan Perlindungan Anak of the Northern Sumatran Province from 2017 to 2019. The number of data that was successfully retrieved was 198 rows and 36 columns.

---
## DATA EXPLORATION
![image](https://user-images.githubusercontent.com/71063726/192520274-62cb76a7-1787-4318-bba4-a8819d3287db.png)

From the photo above, the highest cases of child abuse in the North Sumatera province occurred in 2018 with 2.420 cases, and then there was a decrease in 2019 to 1.690 cases.

![image](https://user-images.githubusercontent.com/71063726/192521953-04ceb32d-1a92-4e63-b345-afc751213b82.png)

From the picture above, it can be seen that the highest type of violence that often occurs to children is sexual violence that occurred in 2017 with 550 cases. it can be assumed that in 2017 many children were victims of child abuse.

![image](https://user-images.githubusercontent.com/71063726/192523952-f478254f-510e-4c0f-8b4b-6321b4f68081.png)

According the picture above, from 2017 to 2019, boys and girls experienced child abuse at an early age, from 0 to 17 years. In addition, the highest cases were in 2018, with an age range of 13-17 years, up to 525 cases.

![image](https://user-images.githubusercontent.com/71063726/192524989-6e399d63-b72b-4110-b437-42aca1989005.png)

The visualization above shows that the majority of victims of child violence are girls and the highest cases are led by sexual violence with a total of 1305 cases.

---

## MODELLING
The modelling process is performed using the Naïve Bayes algorithm to predict the possible gender and age range of abused children. 
This modeling requires 3 types of ratios, which is 80:20, 70:30, and 60:40.

- Ratio 80:20

![image](https://user-images.githubusercontent.com/71063726/192535509-51dec08a-3968-487b-abc2-22141ed96a5b.png)

- Ratio 70:30

![image](https://user-images.githubusercontent.com/71063726/192535721-77f120ca-e1db-4fda-abf9-7556eedb3ccc.png)

- Ratio 60:40

![image](https://user-images.githubusercontent.com/71063726/192535873-0e29cf16-be2a-4da3-8025-f860a54f9f39.png)

From the three images above, it can be seen that the highest recall value is at a ratio of 60:40 with a percentage of 91%. This means that the model is effective in predicting cases of child abuse in the province of North Sumatra in the future.

## THE RESULTS

![image](https://user-images.githubusercontent.com/71063726/192537928-8a18fda3-4d06-4007-ac6a-fd7fc38a12d0.png)

The results of the exploratory analysis of cases of child violence in North Sumatra province from 2017 to 2019 are models predicting as many as 63 boys with a percentage of 78.75% who are in the age range 0-17 years have a high potential to become victims of violence and receive special post-traumatic services.
