# Growth Chart App for Boys & Girls 📈

A comprehensive Streamlit web application for evaluating pediatric growth metrics (height and weight), calculating age equivalents, predicting adult target height from mid-parental height, and generating print-ready A4 growth charts.

## Features ✨

- **Combined Growth Charts**: Interactive height and weight centile curves (3rd to 97th percentiles) for boys and girls ages 5–18.
- **SD Score Calculation**: Automatic calculation of height and weight Standard Deviation (Z) scores based on exact age percentile metrics.
- **Centile Ranges**: Clear determination of where patient height and weight lie relative to standard percentiles.
- **Calculated Age Equivalents**: Automatic estimation of Height Age and Weight Age (50th percentile equivalent age).
- **Adult Target Height Prediction**: Calculation of Mid-Parental Height (MPH) and predicted adult Target Height (TH).
- **High-Resolution A4 Export**: Download custom 300 DPI A4 PNG growth charts with patient plots and timestamps.

## Files 📂

- `app.py`: Main Streamlit application entry point.
- `growthchart_boy_girl_best.py`: Standalone script version of the growth chart application.
- `requirements.txt`: Python dependencies required for running the application.

## Running Locally 🚀

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the Streamlit application:
```bash
streamlit run app.py
```
