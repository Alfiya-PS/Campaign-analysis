# Campaign and Admission performance Analysis

## Table of contents

### Project Overview
The objective of this project was to analyze the campaign and admission performance of Deployad and Primus across various regions and courses. Deployad campaigns were conducted in Malappuram (specifically Mancheri, Perinthalmanna, and Nilambur), Kozhikode, Hyderabad, and the UAE, targeting courses such as Data Analytics, Data Science, HR, SAP, Digital Marketing, Diploma, and others. Primus focused mainly on SAP-related courses including FICO and MM. The analysis evaluated campaign effectiveness, course-wise performance, counselor efficiency, and regional trends. The project also highlighted the best-performing counselors, admission sources, and regions, offering data-driven recommendations to optimize future marketing strategies and improve return on investment.

### Data Sources
This project is based on two key datasets:

1. Campaign Data – Contains detailed information on marketing campaigns conducted by Deployad and Primus across various regions. It includes data such as campaign type, course targeted, region, status (active/inactive), campaign spend, and performance metrics like conversion rates and cost per result.

2. Admission Data – Includes course-wise and counselor-wise admission records, admission sources (e.g., leads, calls, WhatsApp), fee collected, and region-wise distribution. This dataset was used to evaluate the effectiveness of campaigns in terms of actual enrollment and revenue generation.

Together, these datasets enabled a comprehensive analysis of marketing effectiveness, course performance, counselor contributions, and region-specific trends.

### Tools
* Microsoft Excel – Used for organizing, cleaning, and exploring raw campaign and admission datasets. Pivot tables and basic formulas were used for initial summaries and data transformation.

* Power BI – Utilized for visualizing key metrics through interactive dashboards, including region-wise and course-wise performance, counselor analysis, and campaign ROI insights.

* Microsoft PowerPoint – Used to present insights, key findings, and recommendations through structured slides for stakeholders.

### Data cleaning/preparation

* Consolidated campaign and admission data from multiple Excel and report files into structured tables.

* Appended and merged campaign and admission datasets using queries to create a unified view of campaign performance against actual admissions and revenue.

* Removed duplicates and filtered out irrelevant records such as inactive/test campaigns or incomplete admissions.

* Standardized column values for consistency, including course names, regions, counselor names, and source categories.

* Handled missing values by imputing logical defaults or excluding non-critical records with excessive nulls.

* Created calculated fields such as:

     * ROI 

     * Cost per Result, Conversion Rate, Revenue per Admission, etc.

* Filtered the final dataset by region, week, and campaign status (active/inactive) to enable focused performance analysis.

### Data Analysis

* Campaign Performance Analysis: Evaluated the effectiveness of campaigns by region, course, and channel using metrics such as conversion rate, cost per result, and ROI.

* Course-Level Analysis: Identified top- and low-performing courses based on number of admissions and total revenue.

* Counselor Performance: Measured admissions and revenue contributions by each counselor to highlight key performers.

* Source Effectiveness: Analyzed which lead sources (e.g., WhatsApp, Leads, My Operator, ADDOX) generated the most admissions and revenue.

* Region & Branch Analysis: Compared performance across regions (e.g., Mancheri, Nilambur, UAE) to identify high-ROI areas and areas for improvement.

* Temporal Trends: Assessed performance by week and by day to identify peak periods for admissions and campaign success.

### FIndings - Deployad 

* Total admissions : 111
* Total fee : 2.79M
* Total amount spend : 216.65K
* Total ROI : 2.57M


#### Branch wise campaign performance

Among Malappuram region
* Manjeri had the highest count of campaigns (10), top in results and conversion rate.
* Nilambur followed with 3 campaigns, good results in Awareness & Office Admin.
* Perinthalmanna had 2 campaigns, best performance in HR course.
  
Among other branches
* Calicut achieved the highest results (551) but has the lowest conversion rate (0.2)
* UAE had slightly fewer results (441) but showed the best conversion rate (0.4), good results in SAP
* HYD had the lowest results (81), with a moderate conversion rate (0.3), HR shows great results than Power BI

#### Campaign wise performance

Among Malappuram regions
* Top performing campaigns: Deployad | Awareness | malappuram |14/12/24 
                            Deployad Nilambur | Awareness |Nilambur| Brand recall lif|27/2/25, 
                            Deployad | Awareness | Brand recall lift|18/2/25
* Moderate performing campaigns : Deployad Nilambur | sales |Office administration|28/2/25, 
                                Deployad | whatsapp | Hr course sreeja|17/12/24, 
                                Deployad| whatsapp | malappuram | data analytics farsana campaign|1/2/25,                                                       
                                Deployad|whatsapp|DM new Nusriya campaign|11/1/25
* Low performing campaigns : Deployad|whatsapp|sruthy diploma accounting| malappuram|5/2/25, 
                           Deployad | whatsapp | SAP farsana campaign| 1/2/25, 
                           Deployad | Whatsapp | malappuram | Data analytics new campaign | 28/1/25

Among Other regions
* Top performing campaigns : DA-KL-Dm-12-02-25, 
                             Deployad SAP|KL|lead campaign 4/2/25, 
                             SAP |GCC | Lead Gen | 16 01 -25 
* Moderate performing campaigns : GCC data analytics lead, 
                                  Power BI UAE lead gen, 
                                  Power BI KL lead gen  
* Low performing campaigns : Digital marketing-KL-26-02-25,
                             Diploma in accounting-22-11-24,
                             Deployad | DA|Lead campaign 27/02/25

#### Region wise highlights

* Manjeri : Best results in Awareness campaigns.
            Also performs moderately in digital marketing and data analytics
* Nilambur : Strong in Awareness and Office administration.
             CAP performs moderately
* Perinthalmanna : HR campaign had highest results.
                   Data science showed moderate performance
* Calicut : Best results in Power BI campaigns.
            Performs moderately in SAP and data analytics.
            Least performing for the course Digital marketing and Diploma
* UAE : Power BI campaigns are the best performers.
        Moderate performance in SAP and data analytics
* HYD : Best results in HR campaigns. 
        Moderately performs for the course Power BI

#### Course wise performance

By Revenue
* Top performer : Data analytics
* Low performer : Excel and Power BI

By number of admissions
* Top performer : Data analytics
* Low performer : Excel and Power BI

#### Councillor wise performance

Best performers for each course,
* HR – Safna
* CAP – Athira V, Sreeja
* CMA – Rayees
* Data analytics – Swarna and Rayees.
* Data science – Sreeja
* Digital marketing – Sulai husna and Sruthi.
* Excel – Swarna
* Power BI – Sini
* SAP – Remya and Sreenandana
* Expand X – Aswin and Arjun Raj

Best performers for each week,
* Week 1 - Sreenandana, Safna
* Week 2 - Rayees
* Week 3 - Safna
* Week 4 - Swarna
* Week 5 - Rayees

By revenue,
* Top perfomers : Rayees, Safna and Swarna
* Low perfomers : Sneha, Arjun Raj and Anupama

By number of admissions,
* Top perfomers : Safna and Swarna
* Low perfomers : Anupama, Arjun Raj, Sneha and Vidya

#### Admission reference category performance

* LEADS is the top performer in both number of admissions (25) and total fees.
* REFERENCE and CALL are also highly effective categories.
* ADDOX, QIX, and WHATSAPP show solid performance with over ₹2 lakh in fee collections each.
* INSTA and OTHER brought moderate results with fewer admissions and lower total fees.
* FB, WALK IN  and CAMPAIGN had very low admissions but relatively good fee generation for their volume.

















