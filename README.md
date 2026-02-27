
# Job Interview Guide Workshop

This repository contains the **Job Interview Guide Workshop** submissions from **3 students**. Each student conducted an independent LLM-guided mock interview, completed a 15-question technical + behavioral quiz, and received a personalized Jupyter notebook targeting their weak areas.

---

## Workshop Objectives

This workshop helps students **prepare for a Junior Data Scientist job interview** by combining **machine learning review** with **AI-driven self-assessment**.
Participants experience a mock interview guided by a large language model (LLM), complete a technical quiz, and receive a personalized Jupyter Notebook to reinforce their weak areas.

### Core Learning Objectives
- Strengthen understanding of **core ML concepts**: supervised vs. unsupervised learning, regression, classification, KNN, and decision trees.
- Practice **AI interaction** and **prompt engineering** for professional development.
- Receive **tailored feedback and exercises** generated from quiz performance.
- Demonstrate practical **data science competency** through coding exercises.
- Reflect on learning progress and interview readiness.

---

## Student Submissions

| Student | Notebook | LLM Used | Session Transcript | Status |
|---------|----------|----------|--------------------|--------|
| **Muthuraj** | `JobInterviewGuide_Workshop_Muthuraj.ipynb` | Claude Opus 4.6 | `LLMInteraction_MuthurajforInterviewQuestions.txt` | Complete |
| **Kevinkumar Patel** | `JobInterviewGuide_Workshop_Kevinkumar_Patel.ipynb` | — | *To be added* | Notebook submitted; LLM session transcript pending |
| **Prajesh Bhatt** | `JobInterviewGuide_Workshop_Prajesh Bhatt.ipynb` | — | *To be added* | Notebook submitted; LLM session transcript pending |

> **Note:** Kevinkumar Patel and Prajesh Bhatt have submitted their personalized notebooks but have not yet included their LLM session transcripts. These will be added in a future update.

---

## Muthuraj — Submission Details

### Quiz Results
- **Score:** 10/15 (67%)
- **Model used:** Claude Opus 4.6
- **Date:** 2026-02-27

### What Was Done

#### 1. LLM Quiz Session (Deliverable 1)
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

#### 2. Personalized Study Notebook (Deliverable 2)
- **File:** `JobInterviewGuide_Workshop_Muthuraj.ipynb`
- Generated based on the 5 topics missed during the quiz:
  1. Linear Regression — Residual plot interpretation
  2. Regression Metrics — R² vs. MSE distinction
  3. Logistic Regression — Sigmoid function computation
  4. KNN — Distance metric selection (Euclidean vs. Manhattan with outliers)
  5. Model interpretability tradeoffs
- Includes clear markdown explanations, Python code exercises, visualizations, and a reflection section

#### 3. Supporting Files (Deliverable 3)
- `.gitignore` — Python/Jupyter project ignores
- `README.md` — This file
- `requirements.txt` — All Python packages needed to run the notebooks

### Topics Covered

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

## Workshop Summary

Students follow this workflow:
1. Copy the course workshop folders and **StudyGuide.txt**.
2. ZIP the `.ipynb` workshop files into **StudyMaterials.zip**.
3. Open a new LLM session using a model of their choice.
4. Upload **StudyGuide.txt** and **StudyMaterials.zip**.
5. Paste a structured prompt to instruct the LLM to act as an interviewer, quiz them, and create a custom study notebook.
6. Complete a **15-question interview quiz** (technical + behavioral).
7. Receive a personalized **JobInterviewGuide_Workshop.ipynb** notebook based on the quiz results.
8. Push the final graded notebook to GitHub.

---

## Assessment Breakdown

| Component | Description | Weight |
|-----------|-------------|--------|
| **Quiz Performance** | Accuracy across 15 technical + behavioral questions | 40% |
| **Generated Notebook Quality** | Completeness, correctness, and clarity | 40% |
| **Reflection** | Insightful self-assessment within the notebook | 20% |

---

## Topics Covered (Review Scope)

1. **Supervised vs. Unsupervised** learning algorithms
2. **Dependent vs. Independent Variables**
3. **Train / Validation / Test Split** (data leakage, stratification)
4. **Linear Regression**: residuals, linearization
5. **Regression Analysis**: parametric vs. non-parametric, R², MSE
6. **Logistic Regression**: intercept, slope, cross-entropy
7. **K-Nearest Neighbors (KNN)**: hyperparameters
8. **Decision Trees**: leaf nodes and predictions

---

## Repository Structure

```
JobInterviewGuide_Workshop/
├── JobInterviewGuide_Workshop.ipynb                    # Original workshop instructions
├── JobInterviewGuide_Workshop_Muthuraj.ipynb           # Muthuraj's personalized study notebook
├── JobInterviewGuide_Workshop_Kevinkumar_Patel.ipynb   # Kevinkumar's personalized study notebook
├── JobInterviewGuide_Workshop_Prajesh Bhatt.ipynb      # Prajesh's personalized study notebook
├── LLMInteraction_MuthurajforInterviewQuestions.txt    # Muthuraj's LLM quiz session transcript
├── StudyGuide.txt                                      # Study guide topics
├── StudyMaterials.zip                                  # Zipped workshop notebooks
├── README.md                                           # This file
├── requirements.txt                                    # Python dependencies
├── .gitignore                                          # Git ignore rules
└── images/
    ├── OnlineJobInterview.png
    └── OnlineJobInterview2.png
```

---

## How to Run the Notebooks

### Prerequisites
- Python 3.9 or higher
- pip (Python package manager)

### Setup

```bash
# Clone the repository
git clone https://github.com/bhattprajesh/JobInterviewGuide_Workshop.git
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
jupyter notebook
```

Then open any of the student notebooks from the Jupyter file browser. Run all cells from top to bottom. The notebooks generate visualizations and print explanations inline.

---

## Course Workshop Materials Referenced

1. **DataStreamVisualization_Workshop** — Real-time sensor data, anomaly detection, SPC
2. **Linear Regression (Robot PM MLOps)** — Gradient descent, temporal splits, RMSE/R²
3. **PerformanceMetricsClassification** — MNIST, confusion matrix, precision/recall, ROC/AUC
4. **KNearestNeighbors_Workshop** — KNN, Pipelines, GridSearchCV, distance metrics
5. **LogisticRegressionClassifier_Workshop** — Sigmoid, log-loss, decision boundaries
