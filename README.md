# UBCSecure Upload Speed Analysis

This project investigates the performance of the UBCSecure wireless network by measuring upload speeds across various locations and 
conditions. The experiment was designed as a full factorial 34 study to identify which factors most significantly impact internet quality for 
students at the University of British Columbia.

## Experimental Variables

The study tracked four primary factors to determine their effect on upload speeds, measured in Mbps:
- Location: Library, Nest, and Residence
- Time of Day: Morning, Afternoon, and Evening
- Device: iPhone, iPad, and MacBook
- Day of the Week: Wednesday, Thursday, and Friday

## Key Findings
We utilized a linear regression model and ANOVA testing to analyze 81 distinct observations. 
The statistical analysis revealed that device type and the day of the week were found to be the most significant factors 
affecting speed at a 1% significance level. 

The MacBook consistently outperformed other devices, and we are 95% confident that switching to a MacBook from an iPad or iPhone 
increases upload speeds by an average of 29.5 Mbps. Performance also varied by location synergy, as the MacBook works best in the Nest, while the 
iPhone and iPad see higher speeds in the Library or Residence. 

Regarding timing, the results contradicted initial expectations that Friday would be the fastest day. 
Instead, Wednesday was the best performing day, while Friday recorded the slowest overall speeds. For the Time factor, a large difference exists between the Morning and the rest of the day, 
but there is very little difference between Afternoon and Evening.

## Recomendation

Based on the results of the experiment and the analysis, to optimize upload speeds we recommend using a MacBook in a Residence building on a Wednesday morning. 
This specific combination has an expected upload speed of approximately 221.97 Mbps, with a 90% confidence interval between 125.10 and 318.85 Mbps.
