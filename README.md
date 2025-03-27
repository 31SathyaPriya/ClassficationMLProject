# Machine Learning Classification Project

This repository contains a machine learning classification project using **Support Vector Machine (SVM)** and **Random Forest Classifier**. Both models achieve an accuracy of **0.74**.

## Features
- Data preprocessing and feature engineering
- Model training using SVM and Random Forest
- Accuracy evaluation and performance metrics
- Visualization using Matplotlib & Seaborn

---

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

### 2. Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

#### Required Packages
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

---

## Running the Project

1. Ensure all dependencies are installed.
2. Run the Python script:
   ```bash
   python model.py
   ```
3. The script will train the models and print accuracy scores.

---

## Model Performance
| Model            | Accuracy |
|-----------------|----------|
| SVM             | 0.74     |
| Random Forest   | 0.74     |

---

## CSS Guide
For styling web-related components, include the following CSS for a clean UI:

```css
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 20px;
}

.container {
    max-width: 800px;
    margin: auto;
    background: white;
    padding: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
}

h1, h2 {
    color: #333;
}

button {
    background: #007bff;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
    border-radius: 5px;
}

button:hover {
    background: #0056b3;
}
```

---

## Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.
