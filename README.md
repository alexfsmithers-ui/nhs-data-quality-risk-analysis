#### **Project overview**



This project explores a publicly available NHS dataset on Community Health Services waiting times. The aim was not to build a predictive model, but to understand how reporting gaps appear in real-world operational data and how easily such data could be misinterpreted if used carelessly.



#### **Data used**



The data comes from an official NHS publication covering the period April 2025 to March 2026. The Excel file contains multiple tables and explanatory sheets. I focused on Table 1, which records the number of organisations that did not submit data, broken down by organisation type and month.



A key early step was distinguishing metadata and explanatory material from the actual data table, and identifying the correct row to use as column headers.



#### **Question explored**



I asked a simple accountability-focused question:



Which NHS regions had the highest number of missing data submissions over the reporting period so far?



This question was chosen because missing data itself can be a risk signal, especially if it is unevenly distributed across regions.

#### 

#### **Findings**



After filtering the data to regional-level rows and summing missed submissions across months, one region (North West) stood out with substantially more missing submissions than others. Several regions showed occasional gaps, while at least one region showed no missing submissions during the period covered.



This result suggests uneven reporting patterns across regions.

#### 

#### **Important limitations**



These findings should be interpreted cautiously. The data does not explain why submissions were missed. Possible explanations include reporting system issues, organisational capacity constraints, or delays rather than service performance problems.



The dataset also represents a partial reporting period, with later months containing missing values because data has not yet been collected.



#### **What I would examine next**



To deepen this analysis responsibly, I would:



* examine trends month by month to see whether missing submissions are persistent or episodic
* compare regional patterns with provider-level data where available
* review accompanying documentation to understand reporting requirements and known data quality issues
* Before drawing conclusions, I would also want qualitative context from those involved in data collection.
