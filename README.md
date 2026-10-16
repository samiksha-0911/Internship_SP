# Student Performance Predictor

A single-page web app that trains a small ML model in the browser and predicts a student's final score.

## Run
Open `index.html` in any modern browser. No install or server needed.

## Models
- Linear regression (gradient descent) for final score
- Logistic regression for pass/fail (threshold 60)
- Trained on 900 simulated students; evaluated on a 20% hold-out set

Note: Google Fonts load online; the page falls back to system fonts offline.
