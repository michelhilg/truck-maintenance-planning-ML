# Maintenance Planning Optimization - Data Science Proof of Concept

## Summary
This project focuses on optimizing maintenance planning for a truck fleet by predicting air system defects. Leveraging historical maintenance data, the goal is to reduce maintenance costs associated with false negatives and prevent unnecessary inspections in false positives.


## Project Goals
The main requirements for this proof of concept are:

1. Determine if AI techniques can reduce maintenance expenses.
2. Identify the main factors that indicate potential failures in the air system.


## Project Structure
The project follows the basic cookie cutter structure, since we have a simple Proof of Concept, will be  a very straighfoward definiton:

```
maintenance-planning-optimization/
│
├── data/
│   ├── air_system_present_year.csv
│   ├── air_system_previous_years.csv
│   └── (other generated data files, ignored by .gitignore)
│
├── notebooks/
│   ├── 00_Challenger_Activities.ipynb
│   └── (other Jupyter notebooks)
│
└── requirements.txt
└── README.md


## Folder Contents

- **data/:** Contains all the data files used in the project. These files are ignored by .gitignore to avoid sharing large files in the Git repo. All the necessary data could be generated using the notebooks code.

- **notebooks/:** Contains Jupyter notebooks used for data exploration, analysis, and modeling.

The `00_Challenger_Activities.ipynb` address some important test questions and also describes the content of each other notebook on the repo.

## Getting Started
To get started with the project, please follow these steps:

1. Clone the repository:

```
git clone https://github.com/michelhilg/bix-tech-test.git

2. Navigate until the folder

```
cd bix-tech-test

3. Set up a virtual environment:

You can use either Pienv, by:

```
pip install -r requirements.txt

Or a Conda environment:

```



## Results
The results of this proof of concept will address the following:

- **Reduction in Maintenance Expenses:** Using AI techniques, we will evaluate if it's possible to reduce the costs associated with air system maintenance.

- **Factors Indicating Potential Failures:** Identify the key factors that are indicative of potential air system failures in the trucks.

Both questions are answered in the `05_Model_Training.ipynb` notebook.


## Deployment




