Are You Smarter Than a 5th Grader in Stocks?

README Overview

Project Summary

This project explores the comparison between 5th graders and adults in understanding stock market trends during the COVID-19 pandemic. The analysis aims to uncover reasons behind adults' hesitancy to invest and proposes solutions to overcome these fears.

Goals

Highlight differences in stock market knowledge between 5th graders and adults.

Identify reasons for adults' reluctance to invest.

Offer solutions to empower confidence in investing.

Data Overview

Data Sources

Survey data comparing knowledge of 5th graders and adults.

Market trends during the COVID-19 pandemic.

GitHub Repository for Graphs and Data.

Data Cleanup Steps

Remove incomplete responses and outliers.

Standardize numerical values (e.g., income brackets, investment amounts).

Use Python libraries Pandas to clean and organize the data.

Create exploratory visualizations

Tools and Libraries

Python: Pandas, NumPy, Matplotlib, Seaborn

Notebook for tracking exploration steps.

Analysis and Key Findings

Insights on 5th Graders vs. Adults

5th Graders

Showed curiosity about the stock market.

More willing to "experiment" with virtual investments in simulations.

Adults

Hesitant due to fear of financial loss.

Concerns about lack of knowledge and making mistakes.

Common Concerns of Adults

"What if I lose my money?"

"How do I know what I’m doing?"

"I don’t want to make a mistake."

Visualizations

Bar chart: Confidence levels between 5th graders and adults.

Pie chart: Reasons adults avoided investing during COVID-19.

Line graph: Stock market trends during the pandemic.

Script for Team Presentation

"During the pandemic, many adults faced unprecedented challenges and uncertainties. Financial fears were at the forefront of their minds.

Fear of Financial Loss: Adults often asked, ‘What if I lose my money?’

Lack of Knowledge: Many adults admitted, ‘I don’t know where to start.’

Fear of Mistakes: The idea of making the wrong investment paralyzed many individuals.

Despite these concerns, education and accessible tools can transform fear into confidence. We hope to show that investing doesn’t have to be scary."

Python Code for Graphs

import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Load data
data = pd.read_csv('survey_data.csv')

# Bar chart for confidence levels
sns.barplot(x='Group', y='Confidence', data=data)
plt.title('Confidence in Stock Knowledge: 5th Graders vs Adults')
plt.xlabel('Group')
plt.ylabel('Confidence Level')
plt.savefig('confidence_chart.png')
plt.show()

Save graphs (e.g., confidence_chart.png) to include in slides.

Conclusion

Summary

5th graders showed curiosity and openness to learning about stocks.

Adults were hindered by fear and lack of confidence.

Education and tools can bridge this gap, empowering adults to invest wisely.

Next Steps

Expand research to explore additional factors influencing stock market confidence.

Develop educational resources tailored for beginner investors.

Repository Structure

Title Slide: Include project title and team member names.

Executive Summary: Overview of goals and relevance.

Data Collection & Cleanup: Process and tools used.

Key Findings: Graphs and insights.

Adult Hesitation Script: Address reasons for reluctance.

Tools & Code: Highlight process and showcase Python code.

Conclusion: Summarize findings and next steps.

Ensure all code and visualizations are properly committed to our GitHub repository for collaboration and grading!

