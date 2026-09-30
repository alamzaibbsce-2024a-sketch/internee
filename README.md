# Skill Gap Analysis Tool

## Overview

This project is a basic Skill Gap Analysis Tool created as part of my DecodeLabs internship.

The tool analyzes an internee's current skills and compares them with the skills required for a target job role. It uses a sample industry skills database and a job description to identify matching skills and skill gaps.

The project also demonstrates basic Natural Language Processing (NLP) and K-Means clustering.

## Objective

The main objective of this project is to:

* Analyze an internee's current skills
* Identify skills required for a target job role
* Extract required skills from a job description
* Compare current skills with required skills
* Identify missing skills
* Calculate the skill match percentage
* Group industry skills using K-Means clustering

## Features

* Internee skill profile
* Sample industry skills database
* Job description processing
* Basic NLP preprocessing
* Skill extraction from job descriptions
* K-Means clustering of industry skills
* Matching skill identification
* Skill gap identification
* Skill match percentage
* Final skill gap analysis report

## Workflow

The project follows this workflow:

```text
Internee Profile
       +
Industry Skills Database
       +
Job Description
       ↓
NLP Preprocessing
       ↓
Extract Required Skills
       ↓
K-Means Clustering
       ↓
Compare Internee Skills
       ↓
 ┌───────────────┐
 ↓               ↓
Matching       Skill Gaps
Skills          ↓
       ↓
Skill Match Percentage
       ↓
Final Report
```

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* Regular Expressions (re)
* Scikit-learn
* TF-IDF Vectorizer
* K-Means Clustering

## How It Works

### 1. Internee Profile

The project stores the current skills of the internee.

Example:

```text
Python
Pandas
NumPy
Matplotlib
Machine Learning
```

### 2. Industry Skills Database

A small sample database contains skills associated with different job roles.

Example:

```text
Python
Pandas
Machine Learning
SQL
Power BI
Statistics
Scikit-learn
```

### 3. Job Description

A sample job description is provided for the target role.

The job description contains information about the skills and responsibilities required for the position.

### 4. NLP Preprocessing

Basic NLP techniques are used to clean the job description.

The text is:

* Converted to lowercase
* Cleaned of punctuation
* Cleaned of extra spaces

### 5. Skill Extraction

The cleaned job description is compared with the industry skills database to identify skills mentioned in the job description.

### 6. K-Means Clustering

TF-IDF is used to convert skill names into numerical features.

K-Means clustering is then used to group the industry skills into clusters.

### 7. Skill Gap Analysis

The internee's current skills are compared with the required skills.

The tool identifies:

* Matching skills
* Missing skills

### 8. Skill Match Percentage

The project calculates the percentage of required skills that the internee already has.

```text
Matching Skills
--------------- × 100
Required Skills
```

## Example Output

```text
==================================================
       SKILL GAP ANALYSIS REPORT
==================================================

Target Job Role:
Data Science Intern

1. INTERNEE SKILLS
------------------------------
• Python
• Pandas
• Numpy
• Matplotlib
• Machine Learning

2. REQUIRED SKILLS
------------------------------
• Python
• Pandas
• Machine Learning
• Sql
• Statistics

3. MATCHING SKILLS
------------------------------
• Python
• Pandas
• Machine Learning

4. SKILL GAPS
------------------------------
• Sql
• Statistics

5. SKILL MATCH PERCENTAGE
------------------------------
60.0 %

==================================================
             END OF REPORT
==================================================
```

## Project Structure

```text
Project-6-Skill-Gap-Analysis-Tool/
│
├── skill_gap_analysis.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── screenshot.png
```

## Setup Instructions

### 1. Clone or download the project

Download the project repository to your computer.

### 2. Install the required libraries

Open a terminal in the project folder and run:

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

Open:

```text
skill_gap_analysis.ipynb
```

using Jupyter Notebook or VS Code.

### 4. Run the notebook

Run the cells from top to bottom.

The notebook will:

1. Load the required libraries
2. Create the industry skills database
3. Create the internee profile
4. Add the job description
5. Process the job description using NLP
6. Extract required skills
7. Apply K-Means clustering
8. Identify skill gaps
9. Calculate the skill match percentage
10. Generate the final report

## Note

This is a basic educational project created to demonstrate the concept of skill gap analysis using NLP and clustering.

The industry skills database is a small sample dataset and is not intended to represent the complete requirements of the job market.
