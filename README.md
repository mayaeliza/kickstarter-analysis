# Kickstarting with Excel

## Overview of Project

### Purpose
Kickstarter campaign data will be used to analyze trends.  The data will delve into trends found between outcomes based on the launch date of a kickstarter campaign and outcomes based on the funding goal of the kickstarter campaign. Note that the kickstarter campaign data has been restricted to the "Theatre" parent category and "plays" subcategory. By analyzing the data were are able to advise clients, like Louise, on when it would best to launch a campaign for a play. We are also able to provide information on the best funding goal for a favorable outcome.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date\
<img width="362" alt="Theatre_Outcomes_vs_Launch" src="https://user-images.githubusercontent.com/72039212/95038864-c7af1a00-0694-11eb-8db9-f154c978da4a.png">
For succesful campaigns there is a distinct maximum in May and a distinct minimum in December. 
For failed and cancelled campaigns the results do not indicate a clear maximum or minimum value.

### Analysis of Outcomes Based on Goals\
<img width="668" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/72039212/95038846-c2ea6600-0694-11eb-8f4c-312402642207.png">
For succesful campaigns there is a negative correlation between percentage succesful and funding goals as funding goals increase.
For failed campaigns there is a positive correlation between percentage failed and funding goals as funding goals increase.
For cancelled campaigns there are no positive or negative trends to note. 

### Challenges and Difficulties Encountered
Using filters to make the dataset more manageable and formatting the data sheets proved to be the easiest task. While initially tedious, using the COUNTIF() function helped in making this process much easier. The most difficult task proved to be formatting the Pivot Charts to match the desired outcome. There are formatting tricks to help, but finding the right tricks proved to be time consuming. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?\
Campaigns that failed, failed consistently over time. There is not indication that launch date and failed campaigns are related and there must be another reason for their failure. Comparing successful campaigns, the most successful campaigns launched in late spring while the least successful campaigns launched in the winter months. These trends could be dependent on seasonal spending trends of consumers. 
- What can you conclude about the Outcomes based on Goals?\
Overall, higher funding goals correlate to higher failure of campaigns. While the most successful campaigns have the lowest funding goals.
- What are some limitations of this dataset?\
The data is restricted to both a specific parent category and subcategory. These restrictions only allow for a narrow window of data to be scrutinized. This could lead to a generalized trend mistakenly being accepted when it is not representative of the entire data set.

- What are some other possible tables and/or graphs that we could create?\
There is a need for tables comparing the outcomes and launch date and outcomes and funding goals and to other subcategories within the "Theatre" parent category. This will allow for a better scope of the "Theatre" parent category and help to minimize potential bias/error of trend generalizations from a small amount of data. These results should then be illustrated in a Pivot Chart like the stacked bar chart. 

