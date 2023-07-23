# Expository Adult Data Analysis using Pandas

## Introducation
This project is an assignment issued by www.kaggle.com at the end of their comprehensive Pandas tutorial.

## The Data Set
The dataset can be found at the root of this repository as adult.data.csv. It has the following columns.
- age -> type int and continuous
- workclass -> type str
- fnlwgt -> type int
- education -> type str
- education-num -> type int
- marital-status -> type str
- occupation -> type str
- relationship -> type str
- race -> type str
- sex -> type str (Male or Female)
- capital-gain
- capital-loss
- hours-per-week -> type int
- native-country -> type str
- salary -> type str (>50K or <=50K)

## Questions
The following questions were answered from the data set.
1. How many men and women (sex feature) are represented in this dataset?
2. What is the average age (age features) of women?
3. What is percentage of German citizen (native-country feature)?
4 - 5. What are the mean and standard deviation of age for those who earn more than 50k per years (salary feature) and those who earn less than 50k per year?
6. Is it true that people who earn more than 50k have at least high school education? (education - Bachelor, Prof-school, Assoc-acdm, Assoc-voc, Masters or Doctorate feature)
7. Display age statistics for each race (race feature) and each gender (sex feature). Use groupby and describe(). Find the maximum age of men of Amer-Indian-Eskimo race
8. Among whom is the proportion of those earn a lot (>50k) greater: married or single men (marital-status feature)? Consider as married those who have marital-status starting with Married (Married-civ-spouse, Married-spouse-absent or Married-AF-Spouse), the rest are considered bachelors.
9. What us the maximum number of hours a person works per week (hours-per-week feature)? How many people work such a number of hours, and what is the percentage of those who earn a lot (>50k) among them?
10. Calculate the average time of work (hours-per-week) for those who earn a little and a lot salary for each country (native-country). What will these be for Japan?

## Author
Chekwube Onyeka Utomi

## Acknowledgement
www.kaggle.com