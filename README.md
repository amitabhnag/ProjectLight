
# ProjectLight
<img src="/kerosene-lamp-1202277_1920.jpg" width="250">

Author: Amitabh Nag, amnag@uw.edu

Program/Course: University of Washington - Masters in Data Science - Data 512 - Human Centered Data Science

Revision: 1.0

## Abstract:
>“Project Light” throws light upon factors affecting student performance in India

These factors will bring focus to the work of nonprofit, government and Industry. This research finds answer to the question: What are the factors that affect student's performance as measured by reading, writing and math skills in India? Hypothesis is that the two most significant factors affecting student performance in India are: 
   * School type - Government vs private school 
   * Parents wealth

Based on a dataset from ICPSR/IHDS and using Lasso regression, following factors are identified to have a correlation with student performance:  
* Interesting factors - these are the factors that are not in the hypothesis, however are interesting as they can help inform the work of nonprofit, government and Industry 
    * (-) No toilet
    * (+) Good school environment
    * (+) Household education, including the education level of 21+ female
    * (+) No Mid day meal

* Confirmed Hypothesis - these factors are a part of the research hypothesis and are indeed confirmed by Lasso regression
    * (+) Parents wealth 
    * (+) Attend private school vs public school

* Directly correlated - these factors relate to student's educational achievement and hence correlate directly with the student performance
    * (+) Educational achievement 

(+/-) indicate a positive or negative correlation with the student performance.

Acronyms:
* IHDS - India Human Development Survey
* ICPSR - Inter-university Consortium for Political and Social Research

## Licensing
* ICPSR/IHDS 2005 data is available under following [terms of use](http://www.icpsr.umich.edu/icpsrweb/ICPSR/studies/22626/terms) 
* CC0 - Project Light image from [pixabay](https://pixabay.com/en/kerosene-lamp-old-replacement-lamp-1202277)
* CC0 - Toilet image from [pixabay](https://pixabay.com/en/privy-toilet-mobile-wc-474588)

## References
* ICPSR/IHDS 2005 [data and documentation](https://doi.org/10.3886/ICPSR22626.v11). This is the data used in this research
* Project Light image from [pixabay](https://pixabay.com/en/kerosene-lamp-old-replacement-lamp-1202277)
* Toilet image from [pixabay](https://pixabay.com/en/privy-toilet-mobile-wc-474588)
* Harvard Dataverse - Pratham Information Project - Read India [data source](https://dataverse.harvard.edu/dataset.xhtml?persistentId=hdl:1902.1/13084&version=1.0)
* Lasso regression [model](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Lasso.html)
