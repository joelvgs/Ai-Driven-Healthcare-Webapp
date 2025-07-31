
## 🩺 AI-Powered Disease Prediction System

This web app uses **machine learning** to predict diseases from symptoms, offering **explainable results** and even **prescription suggestions**. It's built with Streamlit, making it ideal for rapid prototyping, research, and real-world use.

-----

### 🚀 Features at a Glance

  * **Symptom-Based Prediction:** Accurately predicts diseases based on symptoms you input.
  * **Ensemble ML Models:** Leverages a combination of Random Forest, SVM, and Naive Bayes for robust predictions.
  * **Smart Symptom Matching:** Uses **Natural Language Processing (NLP)** to understand and match your symptoms effectively.
  * **Performance Metrics:** Includes model evaluation and clear performance metrics.
  * **Prescription Recommendations:** Provides suggested prescriptions for predicted diseases.
  * **Interactive Interface:** A modern, user-friendly interface powered by Streamlit.
  * **Jupyter Notebook:** A dedicated notebook for exploration and demonstration.

-----

### 🌳 Project Structure

The project is organized for clarity and ease of use:

```
Ai-Driven-Healthcare-Webapp/
│
├── .gitignore
├── LICENSE
├── pyproject.toml
├── README.md
├── requirements.txt
│
├── assets/               # Images, icons, and static assets
├── data/                 # Datasets (Testing.csv, Training.csv)
├── models/               # Trained model binaries (.pkl files)
├── notebooks/            # Jupyter notebooks (disease_pred.ipynb)
├── scripts/              # Utility scripts (train_models.py, evaluate_model.py)
└── src/                  # All source code
    ├── app.py                # Streamlit web app
    ├── disease_pred.py       # Core prediction logic
    ├── model.py              # ML model class
    ├── nlp_processor.py      # NLP utilities
    ├── prescriptions.py      # Prescription mappings
    └── symptoms.py           # Symptom data loader
```

-----

### ⚙️ Get Started

#### **Setup**

1.  **Clone the repository:**
    ```bash
    git clone <repo-url>
    cd Ai-Driven-Healthcare-Webapp
    ```
2.  **Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    # On Windows:
    venv\Scripts\activate
    # On Mac/Linux:
    source venv/bin/activate
    ```
3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

#### **Usage**

  * **Run the Streamlit Web App:**

    ```bash
    streamlit run app.py
    ```

    Open the local URL provided in your browser and enter symptoms to get predictions.

  * **Retrain Models (Optional):**

    ```bash
    python train_models.py
    ```

    This will retrain and update the model files using `Training.csv`.

  * **Evaluate Models (Optional):**

    ```bash
    python evaluate_model.py
    ```

    This script outputs accuracy and a confusion matrix for the current models.

  * **Explore in Jupyter Notebook:**

    ```bash
    jupyter notebook disease_pred.ipynb
    ```

-----

### 🤝 Contributing

We welcome contributions\! Please:

  * Fork the repository and create a feature branch.
  * Add/modify code with clear docstrings and comments.
  * Write or update tests if necessary.
  * Submit a pull request with a clear description.

-----

### 🙋 Author

Developed by **@joelvgs**.

-----

### 📄 License

This project is licensed under the **MIT License**.

-----
