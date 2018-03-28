# Analysis_on_Racial_Discrimination_in_US_Job_Market

## Background

Racial discrimination continues to be pervasive in cultures throughout the world. Researchers examined the level of racial discrimination in the United States labor market by randomly assigning identical résumés to black-sounding or white-sounding names and observing the impact on requests for interviews from employers.

## Data

In the dataset provided, each row represents a resume. The 'race' column has two values, 'b' and 'w', indicating black-sounding and white-sounding. The column 'call' has two values, 1 and 0, indicating whether the resume received a call from employers or not.
Note that the 'b' and 'w' values in race are assigned randomly to the resumes when presented to the employer.

## Conclusion

We have concluded that the rate of callbacks per resume depends on race. This was checked via frequentist statistical approaches and bootstrap approach. Both methods gave a value of low p (almost zero) with 95% confidence interval between .01642 and .04722 (rate) that w-sounding name will get called back more than b-sounding name.
