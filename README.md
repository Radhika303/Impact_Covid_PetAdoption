# Impact of Covid on Pet Adoption

A team project with Mabel Alamu, Jen Johansson, JB Kinlacheeny, Radhika Sagar to analyze the impact of COVID-19 on pet adoption rates in Norfolk, VA and Dallas, TX.

We take a look at available COVID data (documented, positive test results) and cross-reference it with publicly available data related to pet adoptions to determine if there is an increase in pet adoptions as the pandemic continues.


__Null Hypothesis:__

     -There is no correlation between COVID positive cases and pet adoption rates.

__Alternative Hypothesis:__

     -There is a positive correlation between adoption rates in 2020 (after March) due to more individuals staying at home (as indicated by COVID cases).
       
       
__Research Questions:__ 

    -What is the baseline adoption rate by month/year? 
    -Is there an increase in adoption rates after the pandemic hit the US (ie after March 2020)? 
    -If there is a change in adoption rates, does it correlate to documented COVID cases?
    -Extend the analysis to multiple cities. Do correlations to COVID differ between cities?
    
__Data Sources:__

    -Norfolk, VA COVID dataset: https://data.virginia.gov/resource/bre9-aqqr.json
    -Norfolk, VA adoption data: https://data.norfolk.gov/Government/Norfolk-Animal-Care-and-Adoption-Center-NACC-/vfm4-5wv6 
    -Dallas, TX COVID dataset: https://www.kaggle.com/sudalairajkumar/covid19-in-usa
    -Dallas, TX adoption data: https://www.dallasopendata.com/City-Services/FY2020-Dallas-Animal-Shelter-Data/7h2m-3um5


__Definitions:__

    -COVID cases: confirmed positive COVID cases
    -Adoption: pets adopted
    -Location: Dallas County, TX and Norfolk, VA
    -Timeframe: March – December 2020, and use historical data to baseline

    
__Summary and Conclusions:__

_Norfolk_

In comparing pet adoption in 2018 through 2020, it appears that pet adoption rates increase over the summer months and pet adoptions are lower in 2020 than in 2018 and 2019. In 2020, there was a sharp decrease in adoptions in March, right after the pandemic started and nationwide lockdown announcement. 

  ![](Images/Norfolk%20Adoption%20Rates%20by%20Year.png)
  
  
  
We did not find a correlation between COVID cases and pet adoptions; the Pearson correlation coefficient was .05, which indicates there is no or a very weak correlation between COVID cases and pet adoptions in Norfolk
  ![](Images/Linear%20Regression%2C%20Norfolk.png)
  
_Dallas_

Pet adoption drops drastically in March 2020(which correlates with the lockdown announcements). There was no data available for years 2018 and 2019, so we are unable to compare adoption rates between the three years
  
 ![](Images/Dallas%20Adoption%20Rates%20by%20Year.png)

We did find a  correlation between COVID cases and pet adoptions; the Pearson correlation coefficient was -.53, which indicates there is a negative moderate correlation between COVID cases and pet adoptions in Dallas.
  ![](Images/Linear%20Regression%20Dallas.png)
    
   
    
__Inferences/Conclusions:__
Analysis indicated that pet adoption rates actually were not correlated to COVID cases in Norfolk, and that they were inversely related in Dallas.  There could be many reasons for the difference between reality and perception which would make interesting follow-on research topics.  

Some reasons include: there are fewer adoptable pets (intakes) because people are staying home,  there are fewer relocations, therefore the number of adoptable pets has decreased. Pets are being picked up by rescue organizations and therefore adoptions are not recorded in  the public dataset. It is important to add that the adoption dataset for both cities is small, which impacts the analysis and test results.
