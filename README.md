# NFL Clutch Factor Model

This project analyzes **NFL player performance in clutch situations** using play-by-play data from the 2022 season.

## What Is Clutch?
- 4th Quarter or Overtime
- Score differential ≤ 7
- 3rd or 4th down
- Offensive pass or run plays

## Objectives
- Identify top clutch players using EPA
- Train ML model to predict clutch play success
- Visualize team/player trends under pressure

## Tools Used
- Python (Pandas, Scikit-learn, Seaborn, SHAP)
- Jupyter Notebooks
- Play-by-play data via `nflfastR`

## Project Structure
- `notebooks/`: EDA + modeling
- `data/`: Raw and processed PBP CSVs
- `models/`: Saved classifiers (e.g., Random Forest)
- `plots/`: Visuals used in the README

## Modeling Results
- Trained a Random Forest classifier with ROC-AUC of 0.83
- Top features: `down`, `ydstogo`, `score_differential`, `play_type`

## Sample Visualization

![top_qbs](plots/top_qbs.png)

## Author
Nick Miller | [Linkedin](www.linkedin.com/in/nicholas-miller-n17) | [GitHub](https://github.com/Nickmill17) 
