# CSV Summary Generator

This project loads a CSV file and generates summary statistics such as **mean, median, min, max**.  
It is a beginner-friendly project to practice working with **pandas** in Python.

# 📂 Project Structure

```
csv-summary-generator/
│
├── summary_generator.ipynb   # Notebook for data summary
├── sample.csv                # Example dataset
├── requirements.txt          # Dependencies
└── README.md                 # Instructions
```

## Features

- Load any CSV file
- Preview dataset
- Generate summary (`describe()`)
- Calculate Mean, Median, Min, Max

## Example

Input (`sample.csv`):

```csv
Name,Age,Salary
Jawad,25,50000
Rima,30,60000
Hasan,28,55000
Mitu,35,70000
Siam,40,65000
```

Output:

```
👉 Dataset Preview:
    Name   Age  Salary
0  Jawad   25   50000
1    Rima   30   60000
...

👉 Summary Statistics:
             Age        Salary
count   5.000000      5.000000
mean   31.600000  60000.000000
...

👉 Mean of each numeric column:
Age          31.6
Salary    60000.0
dtype: float64
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/csv-summary-generator.git
cd csv-summary-generator
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open notebook:

```bash
jupyter notebook summary_generator.ipynb
```

4. Run all cells to see summary statistics.

```

```
