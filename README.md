# Customer Review Analysis: Rating vs. Sentiment

**Author:** Anika Tabassum

**Institution:** University of Redlands, California

**Dataset:** Women's E-Commerce Clothing Reviews — 23,000+ reviews

## Overview
This project investigates whether customer sentiment in written reviews
aligns with the star ratings they give, and whether that combination
of signals can predict recommendation behavior.

## Key Finding
Ratings and sentiment do not always agree. A customer can write a
frustrated review and still give four stars. This project makes that
gap visible, measurable, and actionable.

## What's Inside
- **Exploratory Data Analysis** — rating distribution, review length, sentiment patterns
- **Feature Engineering** — VADER sentiment scoring, review length, engagement flags
- **Predictive Modeling** — decision tree classifier with grid search tuning
- **Interactive Dashboard** — Rating vs. Sentiment comparison tool with CSV export

## Tools & Libraries
Python · pandas · scikit-learn · NLTK (VADER) · matplotlib · seaborn

## How to Run
```bash
pip install kagglehub pandas numpy matplotlib seaborn nltk scikit-learn
jupyter notebook Customer\ Review\ Analysis.ipynb
```

## References
- Hutto & Gilbert (2014) — VADER Sentiment Analysis
- Pedregosa et al. (2011) — scikit-learn
- Bird, Klein & Loper (2009) — NLTK
- Kaggle: Women's E-Commerce Clothing Reviews
