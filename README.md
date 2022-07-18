# Tellus_JrML_Challenge
Use heart and respiration rate to determine if patient needs a check-in.

# Overview
* Utilize heart and respiration rates of patients in a nursing home facility to determine if they need a staff member to check-in.
    * Check-ins will be classified by emergency, non-emergency, and doctor's visit.
* Please see further analysis here: [Analysis, Nursing Home Patients](https://github.com/jpetoskey/Tellus_JrML_Challenge/blob/main/code/Analysis%2C%20Nursing%20Home%20Patients.ipynb)

# Sources
* [Normal Heart Rate for Elderly Adults](https://www.griswoldhomecare.com/blog/2021/september/normal-heart-rate-for-elderly-adults/)
* [Raised respiratory rate in elderly patients: a valuable physical sign](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1496225/)
* [Cardiopulmonary Resuscitation in Adults Over 80: Outcome and the Perception of Appropriateness by Clinicians](https://agsjournals.onlinelibrary.wiley.com/doi/full/10.1111/jgs.16270)

# Visualization
![Emergency Check-In Situation](https://github.com/jpetoskey/TellusYouCare_JuniorMLChallenge/blob/main/images/Emergency_check_in.png)

# Conclusion
* Patients who exhibit abnormal heart rate or respiratory rate, but not both simultaneously, can be monitored with less intensity and true emergency situations can be identified more accurately.
    * Measurements of heart and respiratory rate, when measured together allow us to address potential emergency situations, including resuscitation.
 
 <br>
* Measurements of respiratory rate over a day allow us to recommend doctor visits for patients with increased likelihood of having or developing an infection.  
    * Common infections for nursing home patients include lower respiratory and urinary tract infections.
        * Urinary tract infections typically cause lower respiratory rates and lower respiratory infections typically cause higher respiratory rates.
        * See this source for more information: [Cardiopulmonary Resuscitation in Adults Over 80: Outcome and the Perception of Appropriateness by Clinicians](https://agsjournals.onlinelibrary.wiley.com/doi/full/10.1111/jgs.16270)
        
# Future Work

## Awake at night Indicators:
* Determine if these indicators can tell us when a person is awake at night, then recommend a check-in if they aren't sleeping for more than 30 minutes between 10 pm and 5 am.

## Understanding Repititious Data
* Need to know why there are periods of many minutes with the same measurement for both heart and respiratory rate at concerning levels.

## Improve Visualizations
* Include plots with red, yellow, and orange indicator bars.