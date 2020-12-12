# Impact of Covid on Pet Adoption

A team project with Mabel Alamu, Jen Johansson, JB Kinlacheeny, Radhika Sagar to analyze the impact of COVID-19 on pet adoption rates in Norfolk, VA and Dallas, TX.

We take a look at available COVID data (documented, positive test results) and cross-reference it with publicly available data related to pet adoptions to determine if there is an increase in pet adoptions as the pandemic continues.


__Null Hypothesis:__

     -There is no correlation between COVID positive cases and pet adoption rates.

__Alternative Hypothesis:__

     -There is a correlation between adoption rates in 2020 (after March) due to more individuals staying at home (as indicated by COVID cases).
       
       
__Research Questions:__ 

    -What is the baseline adoption rate by month/year? 
    -Is there an increase in adoption rates after the pandemic hit the US (ie after March 2020)? 
    -If there is a change in adoption rates, does it correlate to documented COVID cases?
    -Extend the analysis to multiple cities. Do correlations to COVID differ between cities?
    
__Summary and Conclusions:__

_Norfolk_

In comparing pet adoption in 2018 through 2020, it appears that pet adoption rates increase over the summer months and pet adoptions are lower in 2020 than in 2018 and 2019. In 2020, there was a sharp decrease in adoptions in March, right after the pandemic started and nationwide lockdown annoucement. 

  ![](Images/Norfolk%20Adoption%20Rates%20by%20Year.png)
  
  
  
We did not find a correlation between COVID cases and pet adoptions; the Pearson correlation coefficient was .05, which indicates there is no or a very weak correlation between COVID cases and pet adoptions in Norfolk
  ![](Images/Linear%20Regression%2C%20Norfolk.png)
  
_Dallas_
Pet adoption drops drastically in March 2020(which correlates with the lockdown annoucments). There was no data available for years 2018 and 2019, so we are unable to compare adoption rates between the three years
  
 ![](Images/Dallas%20Adoption%20Rates%20by%20Year.png)

We did find a  correlation between COVID cases and pet adoptions; the Pearson correlation coefficient was -.53, which indicates there is a negative moderate correlation between COVID cases and pet adoptions in Dallas.
  ![](Images/Linear%20Regression%20Dallas.png)
    
   
    
__Inferences/Conclusions:__
The adoption dataset for both cities is small, which impacts the analysis and test results.
Other factors could be influencing the results.  For example, were the shelters closed during any time period?  Were people adopting pets through other sources like rescue organizations


