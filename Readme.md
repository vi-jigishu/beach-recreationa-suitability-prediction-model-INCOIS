Perfect! Here's the updated README.md with your model performance metrics:

# Beach Recreational Suitability Prediction Model - INCOIS

**LSTM-based deep learning model for real-time beach safety assessment using live INCOIS oceanographic data.**

## Objective
Predict beach recreational suitability across Indian coastal regions using real-time oceanic and meteorological data to enhance tourist safety and support sustainable coastal tourism.

## Dataset
- **Source**: INCOIS (Indian National Centre for Ocean Information Services) live data
- **Parameters**: Wave heights, ocean currents, wind speed/direction, water quality, weather conditions
- **Coverage**: Indian coastal regions with real-time monitoring

## Methodology
**LSTM Neural Network** for time-series analysis of sequential oceanographic data with three-tier classification:
- 🟢 **Suitable (S1 > 0.8)**: Safe for all activities
- 🟡 **Moderately Suitable (0.5 ≤ S2 ≤ 0.8)**: Caution advised
- 🔴 **Not Suitable (S3 < 0.5)**: Unsafe conditions

## Model Performance
- **Mean Absolute Error (MAE)**: 0.0148
- **Mean Squared Error (MSE)**: 0.0010
- **R² Score**: 0.785 (78.5% variance explained)
- **Cross-Validation MAE**: 0.0201
- **Cross-Validation MSE**: 0.0015
- **Cross-Validation R²**: 0.801 (80.1% variance explained)

**Model demonstrates strong predictive accuracy with low error rates and high correlation between predicted and actual values.**

## Features
- Real-time prediction using live INCOIS data streams
- Multi-parameter oceanic condition analysis
- Temporal pattern recognition via LSTM architecture
- Safety-first conservative risk assessment approach

## Applications
- **Tourist Safety**: Real-time beach condition alerts
- **Tourism Planning**: Advanced safety planning tools
- **Beach Management**: Support for coastal authorities
- **Emergency Response**: Early warning system for hazardous conditions

## Technical Stack
- **Model**: LSTM deep learning architecture
- **Data**: Real-time INCOIS API integration
- **Processing**: Multi-parameter normalization and feature engineering
- **Output**: Three-tier suitability classification system

## Impact
Enhances coastal tourism safety through data-driven beach condition predictions, supporting India's Blue Economy Policy and reducing tourism-related coastal accidents.

*Real-time oceanic intelligence for safer coastal recreation.*

Your model shows excellent performance with very low error rates and strong R² scores, indicating reliable predictions for beach suitability assessment!