# **Kickstarting with Excel**

## **Play Campaign Outcomes**

This report is to provide Louise a written analysis, with charts, of the outcomes of different campaigns by their launch dates and funding goals

## **Analysis and Challenges**

Using excel pivot tables to filter the kick_starter data, and creating goal ranges with countifs statements I was able to create 2 graphs that visualize the outcomes of various funding campaigns.

### *Analysis of Outcomes Based on Launch Date*

    * ![This is the Outcomes Based on Launch Date Graph](https://github.com/Juanamct/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png)  

### *Analysis of Outcomes Based on Goals*

    * ![This is the Outcomes Based on Goals Graph](https://github.com/Juanamct/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)

### *Challenges and Difficulties Encountered*

#### Outcomes Based on Launch Date

     * Extracting the Year for the "Date Created Conversion" slowed me down
     * Sorting the pivot table so successful is first also called for a review

#### Outcomes Based on Goals

     * Completing the "countifs" function took a few tries

#### Readme file

     * The Readme file has proven to be the most challenging for me

## **Results**

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  * On first review it would appear that May is a good month to launch a campaign.
  * Failed and Successful campaigns follow similar trend over the months.  May and October are both the highest outcome for successful campaigns and worst months for failed campaigns.  Not sure this graph is enough to determine success of campaigns 

- What can you conclude about the Outcomes based on Goals?

  * Percentage failed are the exact inverse of the percentage successful.  The campaigns that were most successful were in the < 1000 range and, 35,000 to 44,999 range.  The least successful campaigns were in the 25,000 to 34,999 and, 45,000 to 49,999 range

- What are some limitations of this dataset?

  * The dataset appears to have a large spread which requires more standardizing of the data to account for outliers

- What are some other possible tables and/or graphs that we could create?

  * Filtering the launch date to recent full years

  * A graph of successful and failed campaigns by average donation and/or # of backers using ranges to group

  * Checking and adjusting for outliers
