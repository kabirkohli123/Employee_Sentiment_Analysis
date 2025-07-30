# Employee Sentiment Analysis

## 📌 Objective
Analyze unlabeled employee messages to detect sentiment trends, rank employees, and identify potential flight risks.

## ✅ Summary of Results


This project analyzed employee email data to assess sentiment, engagement, and potential flight risks. Using natural language processing (NLP) and statistical analysis, we labeled message sentiment, calculated monthly scores for each employee, and built a predictive model to understand the drivers of sentiment.

This document highlights the key findings and provides actionable recommendations.

## Key Highlights
Top Employees by Sentiment (Sample from Latest Month)
To provide a recent snapshot, here are the employees with the highest and lowest sentiment scores from the last full month of data (August 2011):

## Top 3 Positive Employees (August 2011):

john.arnold@enron.com

lydia.delgado@enron.com

sally.beck@enron.com

## Top 3 Negative Employees (August 2011):

kayne.coulter@enron.com

rhonda.denton@enron.com

don.baughman@enron.com

## Employees Flagged as Flight Risks
The following employees were identified as potential flight risks based on sending 4 or more negative emails within a 30-day period:

bobette.riner@ipgdirect.com

johnny.palmer@enron.com

john.arnold@enron.com

## Key Insights and Recommendations
## Insights
Communication Frequency Matters: Our predictive model revealed that message_frequency is the strongest predictor of a positive sentiment score. Employees who communicate more often tend to have a higher positive sentiment.

Overall Sentiment is Positive: The majority of messages across the organization (58%) were classified as "Positive," indicating a generally healthy communication environment.

Specific Individuals are at Risk: A small, identifiable group of employees are showing signs of disengagement. It is notable that one employee (john.arnold@enron.com) appears on both the "Top Positive" list for a specific month and the overall "Flight Risk" list, suggesting fluctuating or complex sentiment patterns that may warrant a closer look.

## Recommendations
Engage with Flight Risks Immediately: HR and direct managers should discreetly and proactively engage with the flagged employees. The goal is to understand their concerns, offer support, and address any underlying issues before they decide to leave.

Recognize Positive Contributors: Acknowledge and reward employees who consistently demonstrate positive sentiment. This reinforces a positive culture and can motivate others.

Promote Open Communication Channels: Since higher communication frequency correlates with positive sentiment, the company should continue to foster an environment where employees feel comfortable sharing information and feedback.

Monitor Sentiment as a Key Metric: The methods used in this project can be deployed as an ongoing monitoring system. Tracking sentiment trends over time will allow leadership to measure the impact of organizational changes and proactively manage employee morale.

## 👤 Author
**Kabir Kohli**  
Email: kabir.kohli.work@email.com  
Submitted to: jbirch@glynac.ai
