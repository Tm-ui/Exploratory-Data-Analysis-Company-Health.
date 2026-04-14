# Exploratory-Data-Analysis-Company-Health.
Exploratory data analysis project involving handling survey response data, reindexing questions, filtering responses, visualizing distributions, and generating insights based on the analysis.
# Project Title: Response Distribution Analysis

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Data Structure](#data-structure)
- [Results](#results)
- [License](#license)

## Features
- Load and preprocess survey data.
- Analyze response distributions for survey questions.
- Generate visualizations to depict response counts for different categories.
- Filter out questions with too many missing values.

## Getting Started
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, etc.

### Installation
1. Clone the repository:
   ```bash
  git clone https://github.com/SamInMotion/company-health-survey-analysis.git
   cd company-health-survey-analysis
Dependencies
The project requires the following Python libraries:

pandas
numpy
matplotlib


Data Structure
Input Data
questions.csv: Contains the survey questions and their corresponding categories.

question_index: Index of the question
q_text: The full text of the question
q_khi: The category assigned to the question
responses.csv: Contains user responses to the survey questions.

user_id: Unique identifier for each user
Q1, Q2, ..., Qn: Responses to each question (e.g., '0', '1', '?')
Output
Visual representations of response distributions will be displayed using bar charts.
