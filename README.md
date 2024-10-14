Youth Mental Health Analysis Project
Project Overview
This project focuses on analyzing survey data related to mental health, particularly in the workplace context. The primary goal is to identify patterns and insights regarding mental health support, consequences, and treatment in the workplace. The dataset used for this analysis was collected from a survey and includes respondents' demographics, work-related details, and mental health experiences.

Dataset
The dataset contains 1,259 entries and 27 columns. Some of the key attributes include:

Age: Age of the respondents.
Gender: Gender identification of the respondents.
Country: The country where the respondent is located.
State: U.S. state of the respondent (if applicable).
Self-employed: Whether the respondent is self-employed.
Family history: Whether the respondent has a family history of mental illness.
Treatment: Whether the respondent is currently receiving mental health treatment.
Work interfere: How often mental health issues interfere with work.
No. of employees: Number of employees in the respondent's workplace.
Remote work: Whether the respondent works remotely.
Tech company: Whether the respondent works in a technology company.
Mental health consequences: Whether there are consequences for discussing mental health at work.
Physical health consequences: Whether there are consequences for discussing physical health at work.
Coworkers: Comfort level discussing mental health with coworkers.
Supervisor: Comfort level discussing mental health with the supervisor.
Mental vs. Physical health: Whether mental health is considered equal to physical health in importance.
Comments: Additional comments from respondents.
Missing Data
Several columns contain missing or incomplete data:

State: 744 non-null entries (missing data for non-US respondents).
Self-employed: 1,241 non-null entries.
Work interfere: 995 non-null entries.
Comments: 164 non-null entries (optional text field).
Project Structure
EDA Report: The exploratory data analysis (EDA) of this dataset has been performed in a Jupyter Notebook (eda-report-mental-health.ipynb). This notebook includes insights into the distribution of various attributes, correlations between variables, and visualizations highlighting significant patterns.
Key Insights
The dataset primarily consists of respondents from the technology sector, with a significant proportion working remotely.
There is a substantial correlation between company size and willingness to discuss mental health issues at work.
Individuals working in smaller companies or who are self-employed tend to report higher levels of mental health issues affecting their work performance.
Mental health treatment and seeking help are influenced by the company’s work culture, availability of benefits, and the presence of a wellness program.
How to Use the Code
Clone or download this repository.
Open the Jupyter Notebook (eda-report-mental-health.ipynb) to explore the analysis performed on the dataset.
Review the visualizations and interpretations provided within the notebook to understand patterns in mental health-related data.
Requirements
Python 3.x
Libraries:
pandas
matplotlib
seaborn
numpy
Future Work
Develop models to predict the impact of workplace factors on mental health issues.
Extend the analysis to include more demographic factors and perform more granular analyses based on location, age groups, and gender.
Consider enriching the dataset with external mental health and well-being datasets for comparative studies.
Acknowledgments
This project uses data collected via surveys focused on mental health in the workplace. The survey was conducted to improve understanding of mental health issues faced by employees, particularly in the technology sector.
