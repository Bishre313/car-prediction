# Flask Machine Learning Classifier

This is a Flask-based web application that uses a trained Machine Learning model
to generate predictions from user input. The application settings are managed
using a `config.yml` configuration file.

---

## 📁 Project Structure

FLASK3/
├── templates/
│ └── index.html # Frontend HTML page
├── app.py # Main Flask application
├── classifier.py # Prediction logic
├── train_reg.py # Model training script
├── model.pkl # Saved trained model
├── wsgi.py # WSGI entry point for deployment
├── config.yml # Application configuration file
├── requirements.txt # Project dependencies
└── README.md # Project documentation


---

## 🚀 Features

- Web-based user interface
- Machine Learning model integration
- Real-time prediction
- Configurable settings using YAML
- Ready for deployment using WSGI

---

## 🛠️ Technologies Used

- Python
- Flask
- Scikit-learn
- PyYAML
- NumPy
- Pandas
- HTML/CSS

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd FLASK3
