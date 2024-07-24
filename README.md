# Student Grades Analysis Project

## Overview

This project analyzes student grade data using Python and pandas. We explore grades over time, calculate averages by subject and student, and visualize the results.

## Data

The data is stored in a CSV file named `calificaciones.csv`. It contains the following columns:

- `Fecha` (Date): Date of the grade
- `Estudiante` (Student): Name of the student
- `Matemáticas` (Math): Grade in Math
- `Ciencias` (Science): Grade in Science
- `Historia` (History): Grade in History
- `Inglés` (English): Grade in English

## Steps Taken

### Data Cleaning and Preparation

- Removed rows with missing values.
- Converted the `Fecha` column to datetime format.

### Exploratory Data Analysis (EDA)

- Calculated summary statistics for the grades.
- Grouped data by student to find the average grade per student.
- Grouped data by subject to analyze the average grade per subject.

### Visualizations

- Created a line plot showing grades by subject over time.
- Created a bar plot to visualize the average grades by subject.
- Created a bar plot to visualize the average grades by student.
- Analyzed the distribution of grades in Math using a histogram.

## Results

### Average Grades by Subject

- Math: 85.13
- Science: 87.50
- History: 80.88
- English: 93.00

### Average Grades by Student

- Juan: 84.00
- Ana: 87.25
- Pedro: 82.50
- María: 92.25

### Distribution of Grades in Math

- Mean: 85.13
- Standard deviation: 5.94
