# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The two exercises should not replicate the exact actions shown in your screencast. The goal of exercises is for learners to apply what was learned in the screencasts to new problems or situations. This is best pedagogical practice for retaining and building skills. For example, this can be done by using another dataset between screencasts and exercises or focusing on a different portion of the dataset.
- Power BI / Tableau specific: We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products. 
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/introduction-to-power-bi/getting-started-with-power-bi?ex=14) from Introduction to Power BI. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners.

## 1st VM Exercise

#### Dataset

- [ ] Add datasets used to the `datasets/` folder : Uploaded `Digital Marketing_SiteData.xlsx`

#### Files

- [ ] **Initial**: Added the .pbix file to the `exercises`/ folder with the name `ex-1-intial.pbix`. 
- [ ] **Solution**: Add file to the `exercises/`  folder with the name `ex-1-sol.pbix`.

#### Learning Objective

Upon completion of this exercise, learners should be able to effectively utilize drill-down and drillthrough features in Power BI Service to analyze and gain deeper insights

#### Context

Imagine you are a digital marketing analyst working with comprehensive Google Analytics data in Power BI Service. Your manager has asked you to investigate specific data points and trends to make informed decisions for the upcoming fiscal year on the digital marketing activities and promotions. 

In this exercise, you will use the _Drill-down_, _Drillthrough_ and _Analyze_ features to perform a detailed analysis and present actionable insights.

#### Steps to be executed by the student (max 6)

- In the _Power BI Service_, navigate to the workspace named `Digital Marketing`.
- Access the `Digital Marketing Trends` report and identify a visual that displays the _Sessions by Year and Quarter_.
- _Drill down_ into the visual to explore the Sessions distribution by individual months within the Quarter.
- Apply a filter to focus only on "New Visitor" information in the report.
- Right-click and _Drill-through_ in the visual from a specific month in the year 2023 where the number of sessions is the lowest.
- _Cross-filter_ between visuals and explore all the Social media platforms in which the bounce rate has been the highest.


#### Exercise question:

What is the bounce rate of "Facebook Reels" for March 2023? 
- 43.97%
- 40.00%
- 47.06% (Right answer)
- 55.34%

#### End goal:

![Digital Marketing Trend](https://raw.githubusercontent.com/deepeshx/sme-bi-course-application/master/exercises/ex-1-sol.png)

## 2nd VM Exercise

#### Dataset

- [ ] Add datasets used to the `datasets/` folder : `Uploaded Digital Marketing_SiteData.xlsx`.

#### Files

- [ ] **Initial**: Added the .pbix file to the `exercises`/ folder with the name `ex-2-intial.pbix`. 
- [ ] **Solution**: Add file to the `exercises/`  folder with the name `ex-2-sol.pbix`.

#### Learning Objective

learners should be able to effectively use the _Analyze_ feature in _Power BI Service_ to identify hidden trends and changes in numerical data. Learners will further use the _Slicers_ to filter and dive deeper into the data.

#### Context

As a digital marketing analyst, you are tasked with identifying trends and variations in monthly sales data. Your goal is to utilize the _Analyze_ and _Explain the Increase_ feature in Power BI Service to quickly analyze and present insights on the changes in sales figures over time and make required decisions based on that.

#### Steps to be executed by the student (max 6)

*Each bulleted instruction is a complete sentence that describes a specific task.*

- Open the Power BI Service and navigate to the `Digital Marketing Trends`  report in the `Monthly Trends` workspace.
- Identify a visual that displays month-over-month sessions data.
- Filter the report to show the data only for the last year and for the "Returning Visitor".
- Apply the _Analyze_ feature to identify the reason for the highest increase in the number of sessions for a month.
- Analyze the trends to understand which days or social media platforms are helping in increasing the traffic on the website and record this result.
- Click anywhere on the report again to close the analysis pop-up.


#### Exercise question:

Which days of the week accounted for the majority of the increase in sessions?
- Monday and Wednesday
- Thursday and Tuesday (Right Answer)
- Saturday and Sunday
- Friday and Saturday

#### End goal:

![Digital Marketing Trend](https://raw.githubusercontent.com/deepeshx/sme-bi-course-application/master/exercises/ex-2-sol.png)

