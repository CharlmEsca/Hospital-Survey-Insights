# Hospital-Survey-Insights

## The goal of this project is to investigate the factors that affect a hospital's satisfaction rating in order to formulate reccomendations that can possibly increase their satisfaction score in the future. 

## Dataset
The American 2022 Hospital Consumer Assessment of Hospital Providers and Systems (HCAHPS) Survey dataset and American 2020-21 hospital bed count dataset were merged to create a dataset compiling the HCAHPS Survey results for all American hospitals (smallest to largest). 

## Inisghts Summary
To figure out what affects a hospital's satisfaction rating, specific "top-box" questions from the HCAHPS Survey that ask a patient if a hospital "always" performs a good/valuable service is used to compare each hospital. 

Here are the key metrics used the compare each hospital:
- **Percentage of Patients Rating the Hospital 9-10**
- **Hospital Question Delta From Mean Cohort %**
- **Cohort Data Spread**

### Percentage of Patients Rating the Hospital 9-10
- Top performing hospitals receive a satisfaction score of 9 or 10 from 80-90% of its patients 
- Lower performing hospitals receive a satisfaction score of 9 or 10 from 50-60% of its patients 

### Hospital Question Delta From Mean Cohort
- Top performing hospitals receive better patient feedback for all/most top-box questions relative to the hospitals in their size and state cohort
- Lower performing hospitals receive worse patient feedback for all/most top-box questions relative to the hospitals in their size and state cohort
- Three notable questions seem to differentiate the top and lower performing hospitals:
    - *Patients "always" received bathroom help as soon as they wanted*
    - *Patients "always" received help as soon as they wanted*
    - *Patients "always received call button help as soon as they wanted*
- If a hospital peforms better than their cohort for these questions, they are usually a top performing hospital in their cohort and vice versa.

### Cohort Data Spread
- Top performing hospitals receive patient feedback that lie towards the right of the mean cohort for all/most top-box questions
- Lower performing hospitals receive patient feedback thatlie towards the left of the mean cohort for all/most top-box questions

## Recommendations
- Based on the three questions that largely influence a hospital's ranking relative to its cohort, it would be recommended for hospitals to improve the immediacy in which they provide assistance to their patients.
- The convenience of getting help to a patient seems to be the factor that greatly determines whether or not a hospital is satisfactory to patients.
- Thus, a hospital improving its efficiency in attending to its patients requests for assistance can possibly increase its satisfaction score.  

## Dashboard
This interactive dashboard is on [Tableau Public](https://public.tableau.com/app/profile/charlm.escalera/viz/HCAHPS_Survey_Dashboard/HCAHPSDashboard) and can be filtered by state and hospital size. It highlights the metrics mentioned prior of a hospital relative to its cohort when clicked. Other metrics such as a hospital's survey response rate and total number of surveys are also included.
<img width="1360" alt="Screenshot 2024-07-30 at 1 12 08 PM" src="https://github.com/user-attachments/assets/00804802-a539-485f-a9f7-9e6bccfa4a20">


