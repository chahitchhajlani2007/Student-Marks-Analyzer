## Student Marks Analyzer

A beginner-friendly Python project that uses **NumPy** to analyze marks for 50 students across 5 subjects.

## Project Objective

Generate random marks for students and analyze their academic performance, including subject-wise toppers, failed students, averages, pass percentages, and grade bands.

## Technologies Used

- Python
- NumPy
- Google Colab

## Features

- Generates marks for 50 students across 5 subjects.
- Displays array shape, dimensions, size, and data type.
- Calculates minimum, maximum, and average marks.
- Uses array slicing to display selected students and subjects.
- Uses Boolean masking to identify marks below 40 and above 90.
- Groups marks into grade bands.
- Finds subject-wise highest marks and pass percentages.
- Identifies the overall topper and students who failed at least one subject.

## Subjects

- Maths
- Physics
- Chemistry
- English
- Computer

## How It Works

1. Import NumPy.
2. Create an array of subject names.
3. Generate a 50 × 5 marks array using `np.random.randint(35, 100, (50, 5))`.
4. Inspect the array and calculate summary statistics.
5. Use slicing and Boolean masks to analyze the marks.
6. Calculate subject-wise toppers and pass percentages.
7. Print the overall performance summary.

**Note:** Marks are randomly generated, so the results may change each time the notebook is run.

## How to Run

### Google Colab

1. Open Google Colab.
2. Upload or open `Student_Marks_Analyzer.ipynb`.
3. Run each code cell from top to bottom.

### Local Python Setup

1. Install Python.
2. Install NumPy:

   ```bash
   pip install numpy
   ```

3. Run the notebook in Jupyter Notebook or JupyterLab.

## Project Structure

```text
Student-Marks-Analyzer/
├── Student_Marks_Analyzer.ipynb
└── README.md
```

## Learning Outcomes

This project demonstrates the use of:

- NumPy arrays (`np.array`)
- Random number generation (`np.random.randint`)
- Array attributes (`shape`, `ndim`, `size`, `dtype`)
- Array slicing and negative indexing
- Boolean masking
- Aggregation functions such as `min()`, `max()`, `mean()`, and `sum()`
- Basic student performance analysis

## Resume Description

Built a NumPy-based student performance analyzer for 50 students across 5 subjects, using 2D slicing and Boolean masking to identify toppers, failures, subject-wise averages, pass percentages, and grade bands.

## Author

Chahit Chhajlani
