---

> ## Challenge Advisor: Update & Finalize Your Project Overview
>
> > 💡 **These grey text instructions are just for you, the team's Challenge Advisor; please delete them once you have completed the steps below.**
>
> We've pre-populated this Challenge Project Overview page — which is what will be shared with your Break Through Tech student team in August — using the details from your submission form. You should have received an email inviting you to join this repo as a Collaborator, enabling you to add files and make edits.
> 
> In order for your project to be finalized and assigned to a team, please:
> 1. **Review all sections below** and update or expand any content as needed, making sure to address the SME Feedback in the section immediately below. Look for square brackets to find the places below that require additional inputs from you (e.g., "About [Company / Org Name]").
> 2. **Add your dataset** to the [data folder](data) in this repo.
> 3. **Close the Issue assigned to you in this repo** to let us know that you have made your edits and the overview page is ready for final review. You can do this by going to the _Issues_ tab in the top left section of the menu above, add a comment that says "CA review complete", and click the button to Close the Issue. 
>
> If you're unfamiliar with how to edit a page like this in GitHub, check out [this tutorial](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/handson/edit-readme.html) for a quick overview (start with step 2 and only edit this page), and [this guide](https://ubc-lib-geo.github.io/gis-workshop-waml-template/content/markdown.html) on how to use Markdown to compose text.
>
>
> ❌ Remember that this is a public repo. Do NOT include: Proprietary data, PII, API keys, credentials, or anything confidential.

---
## 📋 BTT Internal Evaluation Notes
*(This section is for BTT staff only — remove before sharing with students)*

| Check | Status | Notes |
|-------|--------|-------|
| Python Compatibility | 🟢 | The project utilizes Python-based tools and libraries for ML, which aligns well with students' existing skills from ML Foundations. |
| Data Readiness | 🟢 | The dataset is under 1GB, making it feasible for students to utilize without extensive cleaning, allowing focus on modeling and analysis. |
| Resource Check | 🟢 | The use of Google Colab's free tier makes the project accessible regarding hardware requirements, with no proprietary tools involved. |

**Student Fit Score:** 7/10  
**Technical Depth Score:** 8/10  
**Overall Recommendation:** APPROVE

**Advisor Feedback Draft:**
The project presents an engaging application of machine learning to real-world health data, suitable for students. However, focus on the imbalanced dataset will demand extra attention in teaching and may benefit from a preliminary session on handling such datasets. Consider integrating targeted learning modules to address this aspect while keeping students aligned with the data and ML techniques.

---

# Predicting Heart Disease Risk from Health Survey Indicators

**Company / Org:** Accenture  
**Challenge Advisor:** Joseph Chiasson, josephlchiasson@outlook.com  
**Program:** Break Through Tech AI Studio - Fall 2026

---

## 🏢 About Accenture

Accenture is a global professional services company specializing in digital, cloud, and security services, and consulting. We help clients build their digital capabilities to improve productivity and achieve tangible results.

---

## 🎯 The Challenge

### Project Summary
In this project, you will use anonymized national health-survey data from the CDC's Behavioral Risk Factor Surveillance System (BRFSS 2022) and supervised machine learning techniques (e.g. logistic regression, tree-based ensembles, and gradient boosting) to build an ML model that predicts whether an individual has a history of coronary heart disease or heart attack from lifestyle, demographic, and self-reported clinical risk factors. What makes this challenge project unique is the fact that it is an example of an imbalanced dataset, in which only 5-6% of the roughly 445k total records are of positive prevalence/class.

### Success Criteria
Metrics include PR-AUC, F1, ROC-AUC, Precision, Recall, and confusion matrix. Success is also measured by the model's effectiveness/fairness across demographic subgroups (race/ethnicity, age, sex, income) and identification of risk drivers via SHAP analysis.

### Project Milestones

Use these milestones to guide your work. Your team will create a **GitHub Projects board** to track tasks within each milestone.

| Month | Milestone | Key Activities |
|-------|-----------|----------------|
| **September** | Data Understanding | Explore dataset, handle missing values, document findings |
| **October** | Model Development | Train baseline model, experiment with approaches, iterate |
| **November** | Evaluation & Presentation | Finalize model, prepare presentation, document results |

> **Note for the team:** Please create a GitHub Projects board in this repository to break these milestones into weekly tasks. Go to the **Projects** tab → **New project** → Choose **Board** → Add columns for each month.

---

## 📊 Dataset

**Name and Source:** Anonymized national health-survey data from the CDC's Behavioral Risk Factor Surveillance System (BRFSS 2022)  
**Format:** CSV  
**Size:** under 1gb  
**Location:** [Available at Kaggle](https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease)

### Key Details
- Anonymized national health-survey data containing numerical and categorical data.
- Known limitations include dealing with the imbalanced nature of the dataset.
- [Link to data dictionary or documentation, if available]

---

## 🛠️ Suggested Approach

**ML Problem Type:** Classification

**Recommended Libraries:**
- Supervised machine learning techniques: Logistic Regression (L1/L2), Random Forest, K-Nearest Neighbors, Gradient Boosting (XGBoost, LightGBM), Neural Networks (stretch goal). Tools: Python, Google Colab.

**Evaluation Metrics:**
- PR-AUC, F1 Score, ROC-AUC, Precision, Recall, and confusion matrix.

---

## 📚 Resources to Get Started

The following resources will help your team understand the problem space and potential technical approaches for this project:

**Background Reading:**
- [CDC Behavioral Risk Factor Surveillance System](https://www.cdc.gov/brfss/index.html)
- [Heart Disease Data Analysis](https://www.kaggle.com/datasets/)

**Technical Tutorials:**
- [Introduction to Machine Learning in Python](https://www.datacamp.com/community/tutorials/machine-learning-python)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/documentation.html)

**Code Examples:**
- [Kaggle Notebook on Heart Disease Prediction](https://www.kaggle.com/)

**Other:**
- [SHAP: SHapley Additive exPlanations](https://shap.readthedocs.io/en/latest/)

*Feel free to explore beyond these, and share anything interesting you find with me!*

---

## 🤝 How We'll Work Together

**Check-ins:** During our biweekly 60-min AI Studio Lab Section meeting block (2nd and 4th week of every month)  
**Communication:** Slack (Break Through Tech workspace)  
**Response time:** Within 48 hours on weekdays  

**Recommended Tools:**
- **Coding:** Google Colab, VS Code
- **Collaboration:** GitHub, Notion
- **Virtual Meetings:** Zoom, Google Meet

---

## 🚀 Getting Started

1. **Review this overview document** and note any questions for our first meeting
2. **Begin reviewing the dataset** using the link above
3. **Read the GitHub Projects documentation** [here](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)

I'm excited to work with you!

---

## ❓ Questions?

Please bring any questions to our first meeting during the week of August 24th (Break Through Tech's Bridge to Studio - Session B).


---
