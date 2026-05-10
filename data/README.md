# Data

## Sources

Data are drawn from the August 2021--August 2023 National Health and Nutrition Examination Survey (NHANES), conducted by the National Center for Health Statistics (NCHS) at the Centers for Disease Control and Prevention (CDC). The survey uses a multi-year, stratified, clustered four-stage sample design representing the noninstitutionalized civilian population of the 50 U.S. states and the District of Columbia.

## Files

### NHANES_Military_Alcohol.csv

Raw merged NHANES data combining Demographic and Questionnaire sections, linked by unique respondent sequence number. Contains variables related to military service status, alcohol consumption, income, physical activity, education, and demographics.

### ProjectData.csv

Cleaned and processed dataset used for the final analysis. The sample is limited to adults aged 21--80 (n = 1,477). Key variables include:

- **Binge Drinker** (binary): Whether the respondent reported drinking more than 4/5 drinks in a 2-hour period 3--6 or more times in the past year (1 = yes, 0 = no).
- **Military Service** (binary): Whether the respondent has ever served on active duty in the U.S. Armed Forces, military Reserves, or National Guard (1 = yes, 0 = no).
- **Income**: Ratio of family income to poverty level (0--5, capped at 5).
- **Physical Activity Level** (categorical): Low, medium, or high, derived from self-reported frequency of moderate leisure-time physical activity.
- **Education Level** (binary): Less than high school vs. high school or above.
