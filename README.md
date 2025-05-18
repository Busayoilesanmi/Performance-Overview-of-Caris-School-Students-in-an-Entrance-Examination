# Performance Overview of Caris School Students in an Entrance Examination

[Introduction](#Introduction)

[Objective](#Objective)

[Story of Data](#StoryofData)

[Data Splitting and Preprocessing](#DataSplittingandPreprocessing)

[Pre-Analysis](#Pre-Analysi)

[In-Analysis](#In-Analysis)

[Post-Analysis and Insights](#Post-AnalysisandInsights)

[Data Visualizations & Charts](#DataVisualizations&Charts)

[Recommendations and Observations](#RecommendationsandObservations)

[Conclusion](#Conclusion)

[References & Appendices](#References&Appendices)

## Introduction

This project aims to analyze the academic performance of students from Caris School in a standardized entrance examination. Using Excel dashboards, the data is examined across different variables including gender, caste, class 10 background, study habits, and coaching attendance. The primary goal is to identify which factors contribute positively to entrance exam performance and which may be hindering it. These insights are intended to inform academic planning and intervention strategies.

### Objective of the Project

To evaluate student performance in an entrance examination and understand how various demographic and academic factors affect outcomes.

### Problem Being Addressed

Identifying key drivers of high performance and barriers to success among students to inform better educational strategies. The problem addressed are:

1. How does performance vary by gender?
   
2. Which caste group has the highest exam performance?
   
3. Is coaching and Medium linked to better exam performance?
   
4.Which Class 10 education board shows the best results?

5. How does Class 12 board influence performance outcomes?
   
6. What is the performance distribution by medium of instruction?
   
7. Does parental occupation influence student performance? (Father)
   
9. What is the trend of performance based on mother's occupation?
    
10. Does study time correlate with higher performance?
    
11. Are students with excellent Class X results more likely to perform well?
    
12. Does Class XII percentage relate to final entrance performance

## Key Datasets and Methodologies:

### Datasets

Student Performance on an Entrance Examination on kaggle.com (https://www.kaggle.com/datasets/adilshamim8/student-performance-on-an-entrance-examination)

Dataset includes variables such as gender, caste, medium of instruction, mother's occupation, coaching attendance, and prior academic performance.

### Methodologies:

Microsoft Excel tools: pivot tables, bar and pie charts, line graphs for trend analysis.

## Story of Data

### Data Source

The data is sourced secondarily on kaggle.com and the dataset is Student Performance on an Entrance Examination

### Data Collection Process

Student data was collected during the entrance examination and admissions process, through academic documentation such as; coaching records, demographic information, and surveys with academic transcripts.

### Data Structure:

Rows: Each row represents one student.

Columns: Gender, caste, entrance exam result, coaching status, mother’s occupation, language medium, board of education, class 10 performance, and study time.

### Important Features and Their Significance

- Caste Group: General (299), OBC (154), ST (103), SC (66) – essential for tracking equity and representation.

- Gender: Male (288), Female (334) – identifies gender-specific patterns.

- Study Time: 2 hours (339), 1 hour (185), 3 hours (85), 4 hours (11), 5 hours (1), 7 hours (1) – to assess ideal preparation time.

- Coaching: WA (413), NO (144), OA (65) – quantifies the impact of coaching.

- Language Medium: English (495), Others (71), Assamese (56) – determines the influence of instruction language.

- Class 10 Board: SEBA (375), CBSE (226), Others (21) – identifies performance trends by board.

- Mother’s Occupation: Housewife (407), School Teacher (104), Others (68), College Teacher (19), Doctor (13) – gauges socioeconomic effects.

### Data Limitations or Biases:

* Overrepresentation of students taught in English medium.

* Unequal caste representation.

* Limited sample in higher study durations (e.g., only 1 student studied for 7 hours).

* Coaching effects may be confounded with socioeconomic status.

## Data Splitting and Preprocessing

### Data Cleaning

* Removed duplicate records.

* Standardized categorical values (e.g., gender: Male/Female, caste groups).

* Verified numerical values for consistency.

### Handling Missing Values

Minimal missing data; where applicable, values were inferred using median imputation or Excel formulas like IFERROR and AVERAGEIFS.

### Data Transformations

* Study time grouped into buckets (e.g., TWO, ONE, THREE, etc.).

* Pivot tables used to segment performance data by caste, gender, and coaching.

### Data Splitting

Dependent Variable: Entrance Exam Performance.

Independent Variables: Gender, caste, mother’s occupation, study time, medium of instruction, class 10 performance, coaching status.

### Industry Context

The education sector in India is undergoing rapid transformation through data-driven decision-making. With increased competition for college admissions and standardized tests, schools are focusing more on analyzing student performance trends to enhance academic success. Entrance examinations serve as a major filter for student selection into higher education and scholarships, making it imperative for institutions to understand the variables influencing performance.

This project aligns with the broader shift towards Education Analytics, where institutions use insights from demographic, academic, and behavioral data to:

- Tailor student support services

- Personalize learning strategies

- Optimize resource allocation

- Identify systemic biases or inefficiencies

The use of tools like Microsoft Excel to create interactive dashboards enables school administrators to visualize performance trends at scale, with minimal investment in advanced technology.
  
### Stakeholders

This analysis serves a diverse group of stakeholders within the education ecosystem, each deriving specific value from the insights provided.

- School management stands to gain a strategic overview of how students from different demographic and academic backgrounds are performing. This allows them to make data-driven decisions on curriculum planning, faculty training, and resource allocation.

- Academic coordinators benefit from understanding the influence of variables such as study time, coaching, and previous academic records. With this knowledge, they can implement targeted interventions and academic programs tailored to the needs of different student segments.

- Teachers play a critical role in translating these insights into classroom practice. By identifying patterns in student performance—such as the effectiveness of specific study durations or the impact of language medium—they can adapt their instructional strategies to support both high performers and students at risk.

- Parents gain a clearer understanding of the factors that contribute to student success. This enables them to provide better support at home, especially in areas like time management, emotional encouragement, or access to coaching.

- Policymakers and education boards can use this analysis to assess inclusivity in academic outcomes, especially across caste and language groups. It provides an evidence base for designing equitable educational policies and initiatives that address gaps in performance.

- coaching institutes—an influential part of the exam preparation landscape—can evaluate the effectiveness of their programs based on actual performance outcomes. This could inform the design of more impactful coaching methods and help them cater to diverse student needs more effectively.
  
### Value to the Industry

This analytical approach offers significant value to the education industry, especially secondary and higher-secondary institutions:

- Equity Monitoring: Tracks how different social groups (e.g., caste, gender) perform, allowing for inclusive program design.
  
- Curriculum Evaluation: Compares the performance of students from different boards (CBSE vs. SEBA), guiding improvements.

- Behavioral Insights: Correlates study time and coaching with outcomes, informing time management and tutoring plans.

- Admission Strategy: Enables schools to refine entrance criteria by identifying high-performing groups.

- Resource Allocation: Helps target financial and academic support to students with the greatest need or potential.
  
## Pre-Analysis

### Identify Key Trends

- English medium students (495) significantly outperform others.

- Female students (334) slightly outperform male students (288).

- The General caste category has the highest count of high performers (299).

### Potential Correlations

- Higher study time (2 hours) is linked to better results (339 students).

- Coaching attendance (WA = 413) is positively correlated with better performance.

## Initial Insights

- Students with mothers who are housewives form the largest performance group (407).

- SEBA board students (375) outperform CBSE (226) and other boards (21).

## n-Analysis

### Unconfirmed Insights

- Students coached under WA consistently perform better (413 vs. 144 NO).

- Housewife mother background correlates with strong performance, but socioeconomic confounders need analysis.

### Recommendations

- Encourage optimal study duration (2 hours), as seen in highest performing group (339).

- Expand English medium resources since 495 top performers came from English instruction.

- Reinforce coaching programs due to positive association.

### Analysis Techniques Used in Excel

- PivotTables: For aggregating performance by caste, gender, etc.

- Charts: Column, line, and pie charts to display categorical performance.

- Conditional Formatting: Highlight performance clusters.

- Slicers: Used for dynamic filtering of performance categories.

## Post-Analysis and Insights

### Key Findings

- Top Caste Performance: General (299 students)

- Best Study Time: 2 hours (339 students)

- Top Gender: Female (334 students)

- Most Common Language: English (495 students)

- Coaching Impact: WA coaching produced 413 high performers

- Top Class 10 Board: SEBA (375 students)

- Top Mother's Occupation: Housewife (407 students)

### Comparison with Initial Findings

- Initial assumptions regarding coaching benefits and language medium were validated.

- Surprising performance from SEBA board, typically seen as less rigorous than CBSE.

## Data Visualizations & Charts

![Dashboard8](https://github.com/user-attachments/assets/bced8283-8a27-4826-b5d7-20a393189c7a)

### Link to the Excel file

https://docs.google.com/spreadsheets/d/130tD5JCmwkROZYu9-fUFlxiJxtCy3IRJ/edit?usp=drive_link&ouid=104478848167416604596&rtpof=true&sd=true

### Dashboard Visualizations

- Bar Charts: Caste group performance, coaching impact, class 10 board comparison.

- Line Chart: Study time vs. performance.

- Pie Chart: Gender-wise performance.

- Column Charts: Medium of instruction and mother's occupation.
  
### Dashboard Explanations

1. Caste vs. Performance (Bar Chart)
   
Description: Shows the number of students from each caste group who performed well.

Data Values:

General: 299

OBC: 154

ST: 103

SC: 66

Insight: Students in the General category have the highest performance. The representation drops significantly in SC and ST groups, possibly indicating disparities in access or resources.

Recommendation: Introduce remedial programs or scholarships for SC/ST students.

2. Coaching Type vs. Performance (Bar Chart)
   
Description: Analyzes the effect of coaching types on performance.

Data Values:

WA (With Assistance): 413

NO (No Coaching): 144

OA (Other Assistance): 65

Insight: Students with structured coaching (WA) significantly outperform others, showing coaching has a strong positive effect.

Recommendation: Encourage coaching support for underperforming students.

3. Study Time vs. Performance (Line Chart)
   
Description: Shows how different durations of study correlate with performance.

Data Values:

2 Hours: 339 students

1 Hour: 185 students

3 Hours: 85 students

4 Hours: 11 students

5 Hours: 1 student

7 Hours: 1 student

Insight: Optimal study time is 2 hours. Performance declines after that, suggesting overstudying doesn’t guarantee better results.

Recommendation: Promote focused 2-hour daily study plans.

4. Gender-wise Performance (Pie Chart)
   
Description: Compares male vs. female student performance.

Data Values:

Female: 334 students

Male: 288 students

Insight: Females slightly outperform males, indicating balanced gender performance with a tilt towards female students.

Recommendation: Continue supporting female education programs.

5. Medium of Instruction vs. Performance (Bar Chart)
   
Description: Displays the influence of language medium on exam results.

Data Values:

English: 495 students

Others: 71 students

Assamese: 56 students

Insight: Students taught in English dominate performance outcomes. Those from vernacular mediums perform less.

Recommendation: Provide language support or transition assistance for non-English students.

6. Class 10 Board vs. Performance (Bar Chart)
   
Description: Analyzes student performance based on their class 10 board of education.

Data Values:

SEBA: 375 students

CBSE: 226 students

Others: 21 students

Insight: SEBA students outperform CBSE, which is surprising given CBSE’s reputation.

Recommendation: Review SEBA curriculum alignment with the entrance exam; encourage confidence in local boards.

7. Mother’s Occupation vs. Performance (Bar Chart)
   
Description: Relates academic success to mother’s job background.

Data Values:

Housewife: 407

School Teacher: 104

Others: 68

College Teacher: 19

Doctor: 13

Insight: Students with housewives as mothers perform best. This may relate to availability of support at home.

Recommendation: Provide working parents with tips or school support to balance engagement.

## Recommendations and Observations

### Actionable Insights

- Promote 2-hour daily study schedules for optimized outcomes.

- Invest in structured coaching programs.

- Expand English medium instruction where feasible.

- Provide academic support to underperforming caste categories (ST, SC).

- Encourage female student support programs given their high performance.

### Optimizations or Business Decisions

- Review admission or resource allocation criteria based on performance by background (e.g., class 10 board, caste).

- Design intervention programs for students from Assamese or other non-English mediums.

### Unexpected Outcomes

- SEBA board outperforming CBSE suggests need for reviewing internal curriculum alignment.

- Very low returns beyond 3 hours of study suggest study quality is greater than quantity.

## Conclusion

### Key Learnings

- Gender, caste, and class 10 background strongly correlate with entrance exam success.

- Coaching and English instruction are major contributors to performance.

- Optimal study time is 2 hours, excessive study does not equate to better results.

### Limitations

- Uneven caste group sizes and coaching definitions may skew insights.

- Limited sample sizes for long study hours.

- Only performance quantity, not quality, was measured.

### Future Research

- Deep dive into score distributions and subject-wise analysis.

- Include income, attendance, and psychological factors.

- Longitudinal tracking of performance over time.

## References & Appendices

### References

Student Performance on an Entrance Examination on Kaggle.com: https://www.kaggle.com/datasets/adilshamim8/student-performance-on-an-entrance-examination

Excel Documentation: https://docs.google.com/spreadsheets/d/130tD5JCmwkROZYu9-fUFlxiJxtCy3IRJ/edit?usp=drive_link&ouid=104478848167416604596&rtpof=true&sd=true

Screenshots: https://drive.google.com/file/d/11xBVYOFCygUrccpes4ajgUYrr1RVCw7e/view?usp=drive_link

### Appendices

Raw Pivot Tables

Filtered Slicer Dashboards

Full Chart Data Tables
