# Student Performance Prediction Project

This machine learning project focuses on predicting student performance in mathematics based on various demographic and educational factors. It demonstrates a complete end-to-end machine learning pipeline implementation, from data analysis to model deployment.

## Project Overview
The project analyzes student academic performance data to identify patterns and predict math scores using features such as gender, race/ethnicity, parental education level, and test preparation course completion. The implemented solution includes comprehensive exploratory data analysis (EDA), data preprocessing, model training, and a web interface for predictions.

## Tech Stack
- **Python** - Primary programming language
- **Scikit-learn** - Machine learning implementations
- **Pandas & NumPy** - Data manipulation and numerical operations
- **Matplotlib & Seaborn** - Data visualization
- **Flask** - Web application framework
- **HTML/CSS** - Frontend interface

## Features
- **Data Analysis**: Comprehensive EDA with visualizations
- **Preprocessing Pipeline**: Custom transformers for data preparation
- **Model Training**: Implementation of various ML algorithms
- **Web Interface**: User-friendly interface for predictions
- **Error Handling**: Custom exception handling
- **Logging**: Detailed logging for monitoring

## Project Structure
```
mlproject/
├── artifacts/          # Model artifacts and processed data
├── notebook/          # Jupyter notebooks for EDA and modeling
│   ├── data/         # Raw dataset
│   └── EDA & Model Training notebooks
├── src/              # Source code
│   ├── components/   # Core components
│   └── pipeline/     # Prediction pipeline
├── templates/        # HTML templates
├── logs/            # Application logs
├── requirements.txt  # Project dependencies
└── application.py   # Flask application
```

## Installation
1. Clone the repository
```bash
git clone https://github.com/berkay000/mlproject.git
cd mlproject
```

2. Create and activate virtual environment (Windows)
```bash
python -m venv venv
.\venv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Run the application
```bash
python application.py
```

## Usage
1. The web interface will be available at `http://localhost:5000`
2. Input student information in the provided form
3. Get instant predictions for math performance

## Model Information
- Algorithm: Optimized using multiple models including Linear Regression, Random Forest, and CatBoost
- Features: 8 input variables including demographic and educational factors
- Metrics: Evaluated using R2 Score, MAE, and RMSE

## Development Workflow
1. Data exploration and cleaning in Jupyter notebooks
2. Feature engineering and preprocessing pipeline creation
3. Model training and hyperparameter optimization
4. Error handling and logging implementation
5. Web interface development
6. Testing and deployment

## Future Enhancements
- [ ] Implement model retraining pipeline
- [ ] Add more visualization options
- [ ] Enhance prediction explanations
- [ ] Deploy to cloud platform
- [ ] Add user authentication
- [ ] Implement API endpoints


## Contact
- LinkedIn: [https://www.linkedin.com/in/berkay-akparlar]()
- Email: [bakparlarr@gmail.com]()


## License
This project is licensed under the MIT License. See the LICENSE file for details.

---
**Note**: This project was developed as part of a data science portfolio to demonstrate machine learning and software engineering capabilities.