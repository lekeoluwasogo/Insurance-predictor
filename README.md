# Insurance Cost Predictor - Interactive ML Demo

An interactive web application that predicts insurance costs using machine learning, built with Streamlit and scikit-learn.

## 🎯 Live Demo
🔗 **[Try the live app here!](https://your-streamlit-app-url)**

## 📊 Model Performance
- **Algorithm**: Random Forest Regressor
- **R² Score**: 86.55%
- **MSE**: 0.1425
- **Features**: Age, BMI, Smoking Status, Region, Number of Children, Gender

## 🚀 Features
- **Interactive Predictions**: Input customer details and get instant insurance cost estimates
- **Risk Assessment**: Visual indicators for high-risk profiles
- **Feature Importance**: SHAP-based analysis showing which factors drive costs
- **Cost Breakdown**: Pie chart visualization of contributing factors
- **Model Metrics**: Transparent display of model performance statistics

## 🛠️ Technical Details
- **Framework**: Streamlit for web interface
- **ML Library**: Scikit-learn Random Forest with hyperparameter tuning
- **Visualization**: Plotly for interactive charts
- **Data Processing**: Pandas and NumPy
- **Model Interpretation**: SHAP values for explainability

## 📦 Installation & Setup

### Prerequisites
- Python 3.7+
- pip package manager

### Quick Start
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/insurance-predictor.git
   cd insurance-predictor
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```bash
   streamlit run insurance_demo_app.py
   ```

4. **Open your browser**
   - The app will automatically open at `http://localhost:8501`

## 📁 Project Structure
```
insurance-predictor/
├── insurance_demo_app.py    # Main Streamlit application
├── requirements.txt         # Python dependencies
├── README.md               # This file
└── linkedin_showcase_guide.md  # LinkedIn promotion guide
```

## 🎨 Screenshots

### Main Interface
![App Interface](https://via.placeholder.com/800x400?text=Add+Screenshot+Here)

### Prediction Results
![Prediction Results](https://via.placeholder.com/800x400?text=Add+Screenshot+Here)

## 🔍 Model Training Process
The Random Forest model was trained with:
- **Hyperparameter Tuning**: RandomizedSearchCV for optimal parameters
- **Best Parameters**: n_estimators=500, max_features='log2', max_depth=10
- **Cross-Validation**: Rigorous validation to prevent overfitting
- **Feature Engineering**: Categorical encoding and numerical scaling

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 👤 Author
**Oluwasogo Adeleke**
- LinkedIn: [Your LinkedIn Profile](https://linkedin.com/in/yourprofile)
- GitHub: [@yourusername](https://github.com/yourusername)

## 🙏 Acknowledgments
- Insurance dataset for training the model
- Streamlit community for the amazing framework
- SHAP library for model interpretability

---
⭐ **If you found this project helpful, please give it a star!** ⭐