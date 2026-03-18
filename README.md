# BMI Calculator

A simple command-line Python program that calculates a user's Body Mass Index (BMI) based on their weight and height, then provides a personalized health classification.

## Overview

This project implements the standard BMI formula used by the [NIH/NHLBI](https://www.nhlbi.nih.gov/health/educational/lose_wt/BMI/bmicalc.htm). The user enters their name, weight (in pounds), and height (in inches), and the program returns their BMI along with a category and a brief message.

## How It Works

The BMI is calculated using the imperial formula:
```
BMI = (weight in pounds × 703) / (height in inches)²
```

The result is then classified into one of four standard categories:

| BMI Range | Category |
|-----------|----------|
| ≤ 18.5 | Underweight |
| 18.5 – 24.9 | Normal weight |
| 25.0 – 29.9 | Overweight |
| ≥ 30.0 | Obesity |

## Usage

Run the notebook in Jupyter and follow the prompts:
```
Enter your name: Harish
Enter your weight in pounds: 155
Enter your height in inches: 66
```

**Output:**
```
Your BMI is: 25.01
Harish, you are overweight. It's important to exercise daily to improve your health.
```

## Requirements

- Python 3.x
- Jupyter Notebook

## Notes

- Weight must be entered in **pounds**
- Height must be entered in **inches**
- BMI is rounded to 2 decimal places in the output
- Input validation ensures only positive BMI values are processed
