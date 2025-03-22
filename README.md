About Dataset
This dataset contains related to anxiety, depression, and mental health influences. It includes demographic details, lifestyle habits, mental health indicators, medical history, coping mechanisms, and stress factors. The dataset is designed for mental health analysis, predictive modeling, and research on the impact of various factors on mental well-being.

Features Included:
Demographics: Age, Gender, Education, Employment Status

Lifestyle Factors: Sleep Hours, Physical Activity, Social Support

Mental Health Metrics: Anxiety Score, Depression Score, Stress Level

Medical History: Family History of Mental Illness, Chronic Illnesses, Medication Use

Coping Strategies: Therapy, Meditation, Substance Use

Additional Factors: Financial Stress, Work Stress, Self-Esteem, Life Satisfaction, Loneliness

1: General View of Dataset;¶
-The dataset contains 1200 observations (rows) and 21 features (columns).

-No missing values, 1200 data in all columns.

-Types of variables:

-Numeric (int/float): 16 columns

-Categorical (object): 5 columns (Gender, Education_Level, Employment_Status, Drug_Use, Substance_Use)

2: Distributions of Numerical Variables¶
Age: Commonly between the ages of 20-70, mostly adults.

Anxiety_Score, Depression_Score, Stress_Level: Psychological scales are stuck in a certain range (probably around 0-20), may be skewed to the right or left.

Sleep_Hours and Physical_Activity_Hrs: Generally close to normal distribution, but may have outliers.

Financial_Stress and Work_Stress: Scores are mostly concentrated in the middle levels.


4: Correlation Analysis¶
Some relationships that stand out according to the correlation matrix:

There are positive and strong relationships between Anxiety_Score, Depression_Score, Stress_Level. These 3 variables are highly correlated with each other, which is expected.

With Self_Esteem_Score:

There is a negative correlation between Depression_Score, Anxiety_Score. In other words, these scores decrease as self-esteem increases.

With Life_Satisfaction_Score:

There is a negative relationship between Depression_Score and Anxiety_Score. Depression and anxiety are less in individuals with high life satisfaction.

There is a positive correlation between Loneliness_Score and depression and anxiety. These emotional states worsen as loneliness increases.

There are weak but negative relationships between Sleep_Hours and Physical_Activity_Hrs and psychological scores: more sleep and physical activity are generally associated with lower stress/depression/anxiety.
Self_Esteem_Score, Life_Satisfaction_Score, Loneliness_Score: Data on emotional well-being appear balanced, but their distributions may differ.

Anxiety_Score Grouping¶
Low: 0–6

Medium: 7–13

High: 14 and above

Analysis of Anxiety Levels According to Categorical Variables:
First, I showed the distribution according to the Gender variable (as a percentage). The results of other categorical variables are as follows:

Gender: High anxiety rate is higher in women with 37.4%.
This rate is lower in men (33.6%).

“Moderate” level anxiety is highest in non-binary individuals with 42%.

Education_Level: High anxiety is around 35-36% in undergraduate and high school graduates.
High anxiety is slightly lower in graduates (33%).

Employment_Status: High anxiety rate stands out in retired individuals with 37.9%.
Other groups are close to each other.

Medication_Use: High anxiety rate is higher in individuals who use medication regularly (37.8%).
This rate is 33.9% in those who never use medication.

Substance_Use: High anxiety in those who never use it is 36.1%.
This rate is lower in frequent users (29.0%).


Depression Level Distribution – Visualization¶
Notable points in the graphs:

Gender: High depression rates are higher in the Non-binary and Other groups.

Education_Level: As the level of education increases (especially in PhD), high depression rates decrease.

Medication_Use: High depression rates are significantly higher in individuals who use regular medication.

Substance_Use: “Moderate” and “High” depression levels are prominent in frequent substance users.

Employment_Status: The distribution is similar in all categories, but the “Low” depression rate is slightly higher in employed individuals.
