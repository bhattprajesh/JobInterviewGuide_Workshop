
# Job Interview Guide Workshop — Muthuraj

## Workshop Objectives
This workshop helps students **prepare for a Junior Data Scientist job interview** by combining **machine learning review** with **AI-driven self-assessment**.
Participants experience a mock interview guided by a large language model (LLM), complete a technical quiz, and receive a personalized Jupyter Notebook to reinforce their weak areas.

---

## What Was Done

### 1. LLM Quiz Session (Deliverable 1)
- **Model used:** Claude Opus 4.6
- **Date:** 2026-02-27
- The LLM reviewed all 5 course workshop notebooks and the StudyGuide.txt
- Produced a **500-word content summary** and a **100-word interview topic summary**
- Conducted a **15-question multiple-choice quiz** (A-E, one question at a time) covering:
  - Supervised vs. unsupervised learning
  - Dependent vs. independent variables
  - Train/validation/test splits and data leakage
  - Linear regression (residuals, linearization)
  - Regression metrics (R², MSE)
  - Logistic regression (sigmoid, cross-entropy)
  - KNN (hyperparameters, distance metrics)
  - Decision trees (leaf nodes, overfitting)
  - Scenario-based and behavioral questions
- **Final score: 10/15 (67%)**
- Full session transcript saved in `LLMInteraction_MuthurajforInterviewQuestions.txt`

### 2. Personalized Study Notebook (Deliverable 2)
- **File:** `JobInterviewGuide_Workshop_Muthuraj.ipynb`
- Generated based on the 5 topics missed during the quiz:
  1. Linear Regression — Residual plot interpretation
  2. Regression Metrics — R² vs. MSE distinction
  3. Logistic Regression — Sigmoid function computation
  4. KNN — Distance metric selection (Euclidean vs. Manhattan with outliers)
  5. Model interpretability tradeoffs
- Includes clear markdown explanations, Python code exercises, visualizations, and a reflection section

### 3. Supporting Files (Deliverable 3)
- `.gitignore` — Python/Jupyter project ignores
- `README.md` — This file
- `requirements.txt` — All Python packages needed to run the notebook

---

## Repository Structure

```
JobInterviewGuide_Workshop/
├── JobInterviewGuide_Workshop.ipynb                    # Original workshop notebook (instructions)
├── JobInterviewGuide_Workshop_Muthuraj.ipynb           # Personalized study notebook (main deliverable)
├── LLMInteraction_MuthurajforInterviewQuestions.txt    # Full LLM quiz session transcript
├── StudyGuide.txt.txt                                  # Study guide topics
├── README.md                                           # This file
├── requirements.txt                                    # Python dependencies
├── .gitignore                                          # Git ignore rules
└── images/
    ├── OnlineJobInterview.png
    └── OnlineJobInterview2.png
```

---

## How to Run the Notebook

### Prerequisites
- Python 3.9 or higher
- pip (Python package manager)

### Setup

```bash
# Clone the repository
git clone <repository-url>
cd JobInterviewGuide_Workshop

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate        # macOS/Linux
venv\Scripts\activate           # Windows

# Install dependencies
pip install -r requirements.txt

# Register the Jupyter kernel
python -m ipykernel install --user --name=jobinterview --display-name "Python (JobInterview)"
```

### Run

```bash
jupyter notebook JobInterviewGuide_Workshop_Muthuraj.ipynb
```

Run all cells from top to bottom. The notebook generates visualizations and prints explanations inline.

---

## Assessment Breakdown

| Component | Description | Weight |
|-----------|-------------|--------|
| **Quiz Performance** | 10/15 correct across technical + behavioral questions | 40% |
| **Generated Notebook Quality** | Accuracy, completeness, clarity of personalized notebook | 40% |
| **Reflection** | Self-assessment embedded at the end of the notebook | 20% |

---

## Topics Covered

| Topic | Quiz Result | Covered in Notebook |
|-------|-------------|-------------------|
| Supervised vs. Unsupervised | Correct | - |
| Dependent vs. Independent Variables | Correct | - |
| Train/Val/Test Split | Correct | - |
| Linear Regression: Residuals | Missed | Part 1 |
| Regression Metrics: R² vs. MSE | Missed | Part 2 |
| Sigmoid Function | Missed | Part 3 |
| Cross-Entropy / Log-Loss | Correct | - |
| KNN: GridSearchCV | Correct | - |
| KNN: Distance Metrics | Missed | Part 4 |
| Decision Trees: Leaf Nodes | Correct | - |
| Decision Trees: Overfitting | Correct | - |
| Data Leakage / Pipelines | Correct | - |
| Imbalanced Data | Correct | - |
| Model Interpretability | Missed | Part 5 |
| End-to-End Debugging | Correct | - |

---

## Course Workshop Materials Referenced

1. **DataStreamVisualization_Workshop** — Real-time sensor data, anomaly detection, SPC
2. **Linear Regression (Robot PM MLOps)** — Gradient descent, temporal splits, RMSE/R²
3. **PerformanceMetricsClassification** — MNIST, confusion matrix, precision/recall, ROC/AUC
4. **KNearestNeighbors_Workshop** — KNN, Pipelines, GridSearchCV, distance metrics
5. **LogisticRegressionClassifier_Workshop** — Sigmoid, log-loss, decision boundaries
