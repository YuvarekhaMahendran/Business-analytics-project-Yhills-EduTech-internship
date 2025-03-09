# Business-analytics-project

1)New York City Taxi Fare Prediction:

Dataset Description

File descriptions

train.csv - Input features and target fare_amount values for the training set (about 55M rows).

test.csv - Input features for the test set (about 10K rows). Your goal is to predict fare_amount for each row.

sample_submission.csv - a sample submission file in the correct format (columns key and fare_amount). This file 'predicts' fare_amount to be $11.35 for all rows, which is the mean fare_amount from the training set.

Data fields

ID

key - Unique string identifying each row in both the training and test sets. Comprised of pickup_datetime plus a unique integer, but this doesn't matter, it should just be used as a unique ID field.
Required in your submission CSV. Not necessarily needed in the training set, but could be useful to simulate a 'submission file' while doing cross-validation within the training set.
Features

pickup_datetime - timestamp value indicating when the taxi ride started.

pickup_longitude - float for longitude coordinate of where the taxi ride started.

pickup_latitude - float for latitude coordinate of where the taxi ride started.

dropoff_longitude - float for longitude coordinate of where the taxi ride ended.

dropoff_latitude - float for latitude coordinate of where the taxi ride ended.

passenger_count - integer indicating the number of passengers in the taxi ride.

Target

fare_amount - float dollar amount of the cost of the taxi ride. This value is only in the training set; this is what you are predicting in the test set and it is required in your submission CSV.

2)H1N1 Vaccination:

Dataset Description

File descriptions

train.csv - the training set

train_labels.csv - the labels (vacc_h1n1_f, vacc_seas_f) for the training set

test.csv - the test set

submission.csv - a sample submission file in the correct format

Data fields

targets

vacc_h1n1_f - Whether respondent received H1N1 flu vaccine. (This is the target you need to predict for the competition)

vacc_seas_f - Whether respondent received seasonal flu vaccine.

features

For all binary variables: 0 = No; 1 = Yes.

h1n1_concern - Level of concern about the H1N1 flu.

0 = Not at all concerned; 1 = Not very concerned; 2 = Somewhat concerned; 3 = Very concerned.
h1n1_knowledge - Level of knowledge about H1N1 flu.

0 = No knowledge; 1 = A little knowledge; 2 = A lot of knowledge.
behavioral_antiviral_meds - Has taken antiviral medications. (binary)

behavioral_avoidance - Has avoided close contact with others with flu-like symptoms. (binary)

behavioral_face_mask - Has bought a face mask. (binary)

behavioral_wash_hands - Has frequently washed hands or used hand sanitizer. (binary)

behavioral_large_gatherings - Has reduced time at large gatherings. (binary)

behavioral_outside_home - Has reduced contact with people outside of own household. (binary)

behavioral_touch_face - Has avoided touching eyes, nose, or mouth. (binary)

doctor_recc_h1n1 - H1N1 flu vaccine was recommended by doctor. (binary)

doctor_recc_seasonal - Seasonal flu vaccine was recommended by doctor. (binary)

chronic_med_condition - Has any of the following chronic medical conditions: asthma or an other lung condition, diabetes, a heart condition, a kidney condition, sickle cell anemia or other anemia, a neurological or neuromuscular condition, a liver condition, or a weakened immune system caused by a chronic illness or by medicines taken for a chronic illness. (binary)

child_under_6_months - Has regular close contact with a child under the age of six months. (binary)

health_insurance - Has health insurance. (binary)

health_worker - Is a healthcare worker. (binary)

opinion_h1n1_vacc_effective - Respondent's opinion about H1N1 vaccine effectiveness.
Not at all effective; Not very effective; Don't know; Somewhat effective; Very effective

opinion_h1n1_risk - Respondent's opinion about risk of getting sick with H1N1 flu without vaccine.
Very Low; Somewhat low; Don't know; Somewhat high; Very high

opinion_h1n1_sick_from_vacc - Respondent's worry of getting sick from taking H1N1 vaccine.
Not at all worried; Not very worried; Don't know; Somewhat worried; Very worried

opinion_seas_vacc_effective - Respondent's opinion about seasonal flu vaccine effectiveness.
Not at all effective; Not very effective; Don't know; Somewhat effective; Very effective

opinion_seas_risk - Respondent's opinion about risk of getting sick with seasonal flu without vaccine.
Very Low; Somewhat low; Don't know; Somewhat high; Very high

opinion_seas_sick_from_vacc - Respondent's worry of getting sick from taking seasonal flu vaccine.
Not at all worried; Not very worried; Don't know; Somewhat worried; Very worried

agegrp - Age group of respondent.
6 Months - 9 Years; 10 - 17 Years; 18 - 34 Years; 35 - 44 Years; 45 - 54 Years; 55 - 64 Years; 65+ Years

education_comp - Self-reported education level.

1 = < 12 Years; 2 = 12 Years; 3 = Some College; 4 = College Graduate
raceeth4_i - Race of respondent.

1 = Hispanic; 2 = Non-Hispanic, Black Only; 3 = Non-Hispanic, White Only; 4 = Non-Hispanic, Other or Multiple Races
sex_i - Sex of respondent.

1 = Male; 2 = Female 2
inc_pov - Household annual income of respondent with respect to 2008 Census poverty thresholds.

1 = > $75,000; 2 = <= $75,000; 3 = Below Poverty; 4 = Unknown
marital - Marital status of respondent.

1 = Married; 2 = Not Married
rent_own_r - Housing situation of respondent.

1 = Home is Owned; 2 = Home is Rented or Other Arrangement
employment_status - Employment status of respondent.

Employed; Not in Labor Force; Unemployed
census_region - True census region of residence (1=northeast; 2=midwest; 3=south; 4=west)

census_msa - Respondent's residence within metropolitan statistical areas (MSA) as defined by the U.S. Census.

n_adult_r - Number of other adults in household.

household_children - Number of children in household.

n_people_r - Number of adults in the household.

employment_industry - Type of industry respondent is employed in.

employment_occupation - Type of occupation of respondent. Values are represented as short random character strings.

hhs_region - HHS surveillance region number

Region 1: CT,ME,MA,NH,RI,VT

Region 2: NJ,NY

Region 3: DE,DC,MD,PA,VA,WV

Region 4: AL,FL,GA,KY,MS,NC,SC,TN

Region 5: IL,IN,MI,MN,OH,WI

Region 6: AR,LA,NM,OK,TX

Region 7: IA,KS,MO,NE

Region 8: CO,MT,ND,SD,UT,WY

Region 9: AZ,CA,HI,NV

Region 10: AK,ID,OR,WA

state - State of residence
