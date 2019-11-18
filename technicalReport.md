#Airbnb Locations vs. Crime Rates
## How Seattle Crime Rates Affect a User's Decision to Book an Airbnb
Allison J Bennett, Nick M Hebert, Tushar Poddar, Mariella Gauvreau

Info-201: Technical Foundations of Informatics
The Information School
University of Washington
Autumn 2019

#### 1.0 Introduction
  **1.1** Problem Situation.
  Airbnb currently has over 150 million users worldwide, many of them booking in metropolitan areas like New York, Washington D.C, and Seattle. Every person booking through Airbnb wants to make the most of their vacation by finding a place to stay that meets all of their preferences and financial needs. Sometimes this means finding a place to stay with an optimal location to tourist attractions. This comes with safety risks in largely populated areas. It is important for users to know all of these safety risks when booking to ensure the quality of customer care given by Airbnb.

  **1.2** What is the problem?
  Airbnb users need to be informed of the crime rates in the locations in which they are looking to stay. They are susceptible to choosing a place to stay that is filled with crime without this information which may lead them to unforeseen danger. Because crime rates are higher in big cities, especially in areas where many tourist attractions are located, this becomes particularly relevant to Airbnb users.

  **1.3** Why does it matter?
  The growth of Airbnb since the company has first launched is astounding. As more people book with Airbnb, they need to be able to compare listings based on as much information as possible. The quality of someone's experience when booking with Airbnb is determined by their entire vacation, not just by their experience with booking. A vacation can turn unsafe if a person and their family are faced with crime. There is an ethical responsibility for these individuals to be as informed as possible about this possible crime so that they can be better prepared during their stay.

  **1.4** How it will be addressed?
  This problem will be addressed by creating a hub of information about Airbnb listings. At first, this will only include listings in Seattle and what the crime rates are in each listing's particular location. We will potentially include some other information about the listing’s location, like the proximity to popular attractions. This will allow users of Airbnb to have as much information as possible when booking so that they can weigh their options about which listing to book, potentially keeping them out of harms way during their travels.

#### 2.0 Research Questions
  **Research Question 1**
  Are people less likely to book an Airbnb if there is high crime activity in the location of the house?
  **Research Question 2**
  Is there less crime activity is locations with more Airbnb houses on the market?

#### 3.0 The data sets ****KEEP UPDATING***
  **Data Set 1**
  *Name:* Seattle Police Department 911 Incident Response
  *Link:* https://www.kaggle.com/sohier/seattle-police-department-911-incident-response
  *Number of Observations:* 1.4 million responses from 2009 onward
  *Number of Attributes:* 19 different attributes
  *Description:* This dataset is a record of all the police responses to 911 calls made in Seattle, Washington. This study looks at the incident location and type. This data will be used to see where there is a large amount of criminal activity in the Seattle region.

  **Data Set 2**
  *Name:* Seattle Airbnb Open data
  *Link:* https://www.kaggle.com/airbnb/seattle/
  *Number of Observations:* Over 1 million observations
  *Number of Attributes:* 92 different attributes
  *Description:* This dataset is a record of Airbnb activity in the Seattle region. The dataset includes information on listings, the score of the listing, reviews, location, price, listing id, etc. This data will be used to see popular locations in Seattle for Airbnb houses.

#### 4.0 Information Visualizations *****KEEP UPDATING****

#### Figure 1.
This visualization demonstrates the amount of crime that occurs in the Seattle area. We would like to make this easier to view up close and look at specific neighborhoods.
![wash_plot](pics/wash_plot.png)

#### Figure 2.
This plot shows the number of Airbnbs in Seattle by neighborhood. Our goal is to make this graph easier to read and add some color or other visual elements to make it easier to interpret.
![airbnb_plot](pics/airbnb_plot.png)

#### 5.0 Technical description of Shiny application  

#### 6.0 Conclusion  
(1) Strengths and weaknesses of the project  
(2) The main lessons that you learned
(3) The future work that you or someone else might pursue

#### Acknowledgements
(1) Acknowledge anyone who made a substantial contribution to your project

#### References
https://muchneeded.com/airbnb-statistics/
https://ipropertymanagement.com/airbnb-statistics/

#### Appendix 1: Data Dictionary  
Variable Name | Description | Data Type | Measurement Type  
--- | --- | --- | ---
Test | Test | Test | Test

#### Appendix 2: Reflections  
(1) each team member should write a personal reflection on the project (around 150 words)
- what you learned
- what you found satisfying/frustrating
- what you would do differently in the future
- how the project positioned you developed your identity for coder, thinker, innovator, etc.

#### Appendix 3: Use of Envisioning Cards  
(1) Include a brief description of how you used the envisioning cards