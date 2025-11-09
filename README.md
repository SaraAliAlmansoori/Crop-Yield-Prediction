## Crop Yield Prediction — Parent Paper Verification (Team 55)

This repository contains our implementation for verifying the results of the Parent Paper:

California Crop Yield Benchmark: Combining Satellite Image, Climate, Evapotranspiration, and Soil Data Layers for County-Level Yield Forecasting of Over 70 Crops.

Per the assignment instructions, we reconstructed part of the paper’s workflow using our own code, reproduced in:

main.ipynb — our complete Python pipeline extracted from the notebook
requirements.txt — dependencies needed to run our script

This repo is designed for the instructor/TA to reproduce what we implemented and evaluate our understanding of the Parent Paper’s methods.

### What This Code Does

Our file team_code_clean.py includes:

Data loading and preprocessing

Splitting into training/validation/testing

Feature engineering steps

Model training

Evaluation metrics

Any additional analysis we performed

This is the only Python file used in the project, as required.

## Assignment Objectives Covered
### Reproduce the Parent Paper’s methodology

We follow the same ideas used in the Parent Paper, such as:

Using multi-modal inputs (imagery/climate/etc. where applicable in our dataset)

Performing temporal splitting similar to the paper

Predicting county-level yield

Using R², MAE, and RMSE as evaluation metrics

✔ Implement the pipeline in Python

Our entire implementation is in one Python file (team_code_clean.py), as allowed by the assignment.

✔ Demonstrate modular understanding

Even though we use a single file, the functions and structure are written clearly so we can swap or modify parts during the explanation.

✔ Provide a line-by-line video walkthrough

We included a complete line_by_line_narration.md that we used to record our explanation for every line of code.



🚀 How to Run
1. Install Dependencies
pip install -r requirements.txt

2. Run the Script
python main.ipynb


If our script depends on specific file paths or a dataset, instructions/editable paths are written inside the Python file.

🎥 Video Recording (Deliverable)

Our video demonstrates:

Each team member explaining sections of main.ipynb

What each line or block of code does

How our approach connects to the Parent Paper

Evidence that our implementation works

Results from running the script

This satisfies the assignment requirement to show the code and our understanding of it.

Although our dataset and exact setup may differ, the performance trend and reasoning align with the paper’s methodology.

👥 Team 55

Sara Almansoori
Carelle Matthews
