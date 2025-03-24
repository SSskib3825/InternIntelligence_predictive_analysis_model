# Predictive Analysis of Sales and Wastage Ratio

## Project Overview
This project focuses on predicting the **Wastage-to-Sales Ratio** using historical sales and wastage data. The goal is to optimize inventory management, minimize waste, and improve decision-making through machine learning models.

## Dataset
- Source: 'well-task-raw.xlsx'
- Features: Date-based attributes (Year, Month, Weekday), Sales, and Wastage
- Preprocessing: Handling missing values, feature engineering, and dataset splitting

## Models Used
The following machine learning models were implemented and evaluated:
1. **XGBoost** - Gradient boosting algorithm optimized for structured data.
2. **Random Forest** - An ensemble of decision trees to enhance prediction accuracy.
3. **LSTM (Long Short-Term Memory)** - A deep learning model suited for sequential data.
4. **Ensemble Model (LSTM + XGBoost)** - A hybrid approach combining deep learning and gradient boosting.

## Model Performance
| Model | R² Score | MAE | RMSE |
|--------|----------|------|-------|
| XGBoost | 0.7832 | 0.0114 | 0.0253 |
| LSTM | 0.8843 | 0.0088 | 0.0185 |
| Ensemble (LSTM + XGBoost) | 0.8553 | 0.0093 | 0.207 |

## Key Findings
- **LSTM outperforms other models**, achieving the highest R² and lowest errors.
- **XGBoost provides moderate accuracy**, suitable for structured data.
- **The ensemble model did not significantly improve results**, showing instability in RMSE.

## Future Enhancements
- Further optimization of the ensemble approach to stabilize performance.
- Incorporate additional external factors like weather or promotions.
- Deploy the model in a real-time forecasting system.




## How to Run the Project
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-repo-name.git
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the model training script:  
   ```bash
   python train_model.py
   ```

 

## License
This project is licensed under the MIT License.


# InternIntelligence_predictive_analysis_model
