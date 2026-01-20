# Heart Disease Prediction System

A machine learning-based web application for predicting the risk of heart disease in patients using Django and scikit-learn.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Model Details](#model-details)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

This project implements a predictive model to assess the risk of heart disease based on patient health metrics. The system uses machine learning algorithms trained on medical data to provide accurate predictions.

## ✨ Features

- **Web Interface**: User-friendly Django-based web application
- **ML Prediction**: Scikit-learn based classification model
- **Database**: SQLite database for data persistence
- **Input Validation**: Comprehensive validation for medical parameters
- **Real-time Predictions**: Get instant risk assessment

## 🛠️ Tech Stack

- **Backend**: Django (Python web framework)
- **ML Library**: scikit-learn
- **Database**: SQLite
- **Language**: Python 3.x
- **Frontend**: Django Templates

## 📦 Installation

### Prerequisites
- Python 3.x
- pip (Python package manager)

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/101Krishna/Heart-Disease-Prediction-System.git
   cd Heart-Disease-Prediction-System
   ```

2. **Create virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run migrations**
   ```bash
   python manage.py migrate
   ```

5. **Start the development server**
   ```bash
   python manage.py runserver
   ```
   The application will be available at `http://localhost:8000/`

## 🚀 Usage

1. Navigate to the web application
2. Enter patient health metrics:
   - Age
   - Sex
   - Chest pain type
   - Resting blood pressure
   - Cholesterol levels
   - And other relevant parameters
3. Click "Predict" to get the risk assessment
4. View results and recommendations

## 📁 Project Structure

```
Heart-Disease-Prediction-System/
├── manage.py              # Django management script
├── db.sqlite3            # SQLite database
├── requirements.txt       # Project dependencies
├── .gitignore           # Git ignore file
├── .gitattributes       # Git attributes
└── temp.txt             # Temporary file
```

## 🧠 Model Details

- **Algorithm**: Classification model using scikit-learn
- **Features**: Medical parameters including age, sex, blood pressure, cholesterol, etc.
- **Output**: Risk level prediction (0 = Low Risk, 1 = High Risk)
- **Performance**: [Add your model's accuracy/metrics here]

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request


## 👨‍💻 Author

**Krishna** - [GitHub Profile](https://github.com/101Krishna)

## 📞 Support

For support, open an issue on the GitHub repository or contact the project maintainer.

---

**Note**: This application is for educational purposes. For real medical diagnosis, consult qualified healthcare professionals.
