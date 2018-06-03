# Project Light

[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.svg?v=103)](https://opensource.org/licenses/mit-license.php)
[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)


<img src="/kerosene-lamp-1202277_1920.jpg" width="250">
Author: Amitabh Nag, amnag@uw.edu

Program/Course: University of Washington - Masters in Data Science - Data 512 - Human Centered Data Science

Revision: 1.0

## Abstract
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

Lasso regression identified "No mid day meal" factor to have a positive correlation with student performance. Mid day meal program was launched in India ["with a view to enhancing enrollment, retention and attendance and simultaneously improving nutritional levels among children"](http://mdm.nic.in). Result found by this study is not consistent with the Mid day meal goal and needs to be investigated as a next step. 

Acronyms:
* IHDS - India Human Development Survey
* ICPSR - Inter-university Consortium for Political and Social Research

## Quick start guide
* Download and extract below two zip files containing data and documentation. Note that based on ICPSR/IHDS terms of service data is not attached with this repository. Please note you have to sign in ICPSR and agree to [terms of use](http://www.icpsr.umich.edu/icpsrweb/ICPSR/studies/22626/terms), before you can download the data  
    * [DS1: Individual](http://www.icpsr.umich.edu/cgi-bin/bob/zipcart2?path=DSDR&study=22626&bundle=all&ds=1&dups=yes)
    * [DS2: Household](http://www.icpsr.umich.edu/cgi-bin/bob/terms2?study=22626&ds=2&bundle=&path=DSDR)
* Ensure you have Anaconda Python 3.6 with Jupyter notebook installed from [here](https://www.anaconda.com/download/)
* Ensure you have pandas, numpy, and scikit-learn packages installed on your computer. You can check if these packages are installed using Anaconda navigator
* Run the code step by step from ProjectLight.ipynb. Ensure to update the path related variables to your computer paths in step 3 of the notebook 

## Licensing
* ICPSR/IHDS 2005 data and documentation is available under following [terms of use](http://www.icpsr.umich.edu/icpsrweb/ICPSR/studies/22626/terms) 
* CC0 - Project Light image from [pixabay](https://pixabay.com/en/kerosene-lamp-old-replacement-lamp-1202277)
* CC0 - Toilet image from [pixabay](https://pixabay.com/en/privy-toilet-mobile-wc-474588)
* MIT - Code for Project Light is available under MIT license. License file is available with the repository

## References
* ICPSR/IHDS 2005 [data and documentation](https://doi.org/10.3886/ICPSR22626.v11). This is the data used in this research
* Project Light image from [pixabay](https://pixabay.com/en/kerosene-lamp-old-replacement-lamp-1202277)
* Toilet image from [pixabay](https://pixabay.com/en/privy-toilet-mobile-wc-474588)
* Harvard Dataverse - Pratham Information Project - Read India [data source](https://dataverse.harvard.edu/dataset.xhtml?persistentId=hdl:1902.1/13084&version=1.0)
* Lasso regression [model](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Lasso.html)
