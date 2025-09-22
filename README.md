# 🧬 Date-A-Scientist: OKCupid Data Analysis Project

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org)
[![Machine Learning](https://img.shields.io/badge/ML-Supervised%20%7C%20Unsupervised-green.svg)](https://scikit-learn.org)
[![Status](https://img.shields.io/badge/Status-Completed-green.svg)](https://github.com/Tuminha)

## 📋 Project Overview

In recent years, there has been a massive rise in the usage of dating apps to find love. Many of these apps use sophisticated data science techniques to recommend possible matches to users and to optimize the user experience. These apps give us access to a wealth of information that we've never had before about how different people experience romance.

This portfolio project analyzes data from **OKCupid**, an app that focuses on using multiple choice and short answers to match users. The project investigates whether zodiac signs can be predicted from profile data, including essays and lifestyle choices, using machine learning techniques.

## 🎯 Project Objectives

- ✅ Complete a project to add to your portfolio
- ✅ Use Jupyter Notebook to communicate findings
- ✅ Build, train, and evaluate a machine learning model
- ✅ Practice formulating questions and implementing ML techniques

## 📚 Prerequisites

- Natural Language Processing
- Supervised Machine Learning
- Unsupervised Machine Learning

## 🚀 Getting Started

### Setup Instructions

1. **Download Materials**
   - Download the Date-A-Scientist project zip folder
   - Double-click to "unzip" the folder
   - You should see:
     - `date-a-scientist.ipynb`
     - `profiles.csv`

2. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
   This will open a browser tab with Jupyter interface.

3. **Open Project File**
   - Click on `date-a-scientist.ipynb` in the browser tab
   - Start building your project in this file

4. **Git Repository Setup**
   - Create a new Git repository for this project
   - Initialize with proper `.gitignore` for Python/Jupyter projects

## 📊 Project Tasks & Progress Tracking

### 🔄 Project Workflow

<table>
<tr>
<td width="33%">

### 📝 To Do
<ul>
<li>☐ All tasks completed!</li>
</ul>

</td>
<td width="33%">

### ⚡ In Progress
<ul>
<li>☐ Project completed and ready for presentation</li>
</ul>

</td>
<td width="33%">

### ✅ Done
<ul>
<li>☐ Project Setup - Download materials, launch Jupyter, create Git repository</li>
<li>☐ Load and explore OKCupid dataset - understand structure and data types</li>
<li>☐ Define research question - zodiac sign prediction using lifestyle and essay data</li>
<li>☐ Clean zodiac field - extract core signs from messy text data</li>
<li>☐ Assess data quality - missing values, essay completion rates, zodiac patterns</li>
<li>☐ Analyze essay completion patterns by zodiac sign</li>
<li>☐ Explore lifestyle choices correlations with zodiac signs</li>
<li>☐ Create features from essays and lifestyle data for ML model</li>
<li>☐ Build and train machine learning model for zodiac prediction</li>
<li>☐ Evaluate model performance and interpret results</li>
<li>☐ Analyze essay content using NLP techniques for zodiac prediction</li>
<li>☐ Create PowerPoint presentation with findings</li>
<li>☐ Finalize project documentation and deliverables</li>
</ul>

</td>
</tr>
</table>

### 📋 Detailed Task Breakdown

#### 1. Project Setup
- [ ] Download the Date-A-Scientist project zip folder
- [ ] Double-click to "unzip" the folder
- [ ] Verify contents: `date-a-scientist.ipynb` and `profiles.csv`
- [ ] Launch Jupyter Notebook via command line
- [ ] Open `date-a-scientist.ipynb` in browser
- [ ] Create new Git repository for the project

#### 2. Project Scoping
- [ ] State goals for the project
- [ ] Gather and understand the data
- [ ] Consider analytical steps required
- [ ] Create project roadmap
- [ ] Identify potential challenges and adjustments

#### 3. Select ML-Solvable Problem
- [ ] Choose a problem solvable with machine learning
- [ ] Ensure problem can be solved in reasonable time
- [ ] Verify data availability for the chosen problem
- [ ] Break down complex problems into smaller units if needed

#### 4. Load and Check Data
- [ ] Load the dataset into Jupyter Notebook
- [ ] Check for label/response variable (if supervised learning)
- [ ] Verify data completeness
- [ ] Identify missing crucial pieces for analysis
- [ ] Adjust problem selection if data is insufficient

#### 5. Explore and Explain Data
- [ ] Generate summary statistics
- [ ] Create visualizations to examine data
- [ ] Document insights gained from analysis
- [ ] Identify patterns and trends
- [ ] Note any data quality issues

#### 6. Preprocess Data
- [ ] Join data if necessary
- [ ] Standardize variables
- [ ] Remove unnecessary variables
- [ ] Handle missing values (imputation)
- [ ] Split data into train and test sets

#### 7. Build Model(s)
- [ ] Select appropriate model types for the problem
- [ ] Implement and train models
- [ ] Run data through each model
- [ ] Store and compare results
- [ ] Evaluate model performance

## 📁 Project Structure

```
OKCupid/
├── README.md
├── date-a-scientist.ipynb
├── profiles.csv
├── Date-A-Scientist-Predicting-Zodiac-Signs-from-OKCupid-Profiles.pptx
└── images/
    ├── date-A-Scientist.png
    ├── confusion_matrix_structured_logistic.png
    └── confusion_matrix_random_forest.png
```

## 🔧 Technologies Used

- **Python 3.8+**
- **Jupyter Notebook**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Scikit-learn** - Machine learning
- **Matplotlib/Seaborn** - Data visualization
- **Git** - Version control

## 📈 Key Findings

### 🎯 Research Question
**Can we predict zodiac signs from OKCupid profile data?**

### 📊 Results Summary
- **Dataset**: 48,890 profiles with 12 zodiac signs
- **Best Model**: Text-only model with 9.1% accuracy
- **Baseline**: 8.9% (majority class)
- **Improvement**: 0.2% over random chance

### 🔍 Key Insights
1. **Zodiac signs are not predictable** from profile data
2. **Text features are most informative** (essays perform better than demographics)
3. **Demographics matter more** than lifestyle choices
4. **Data quality issues** (80% missing income, 59% missing offspring data)
5. **Each zodiac sign has distinct word patterns** in essays

### 🏆 Model Performance
- **Structured Logistic**: 8.3% accuracy
- **Random Forest**: 9.0% accuracy  
- **Text-only**: 9.1% accuracy (best performer)

### 📊 Confusion Matrices

#### Structured Logistic Regression Model
![Structured Logistic Confusion Matrix](images/confusion_matrix_structured_logistic.png)

#### Random Forest Model
![Random Forest Confusion Matrix](images/confusion_matrix_random_forest.png)

### 📝 Top Discriminative Words by Sign
- **Cancer**: "odd, damn, data, cancer, answering"
- **Leo**: "competitive, saying, foundation, svu, culture"
- **Pisces**: "evenings, annoying, policy, different types, camping"
- **Gemini**: "things really, wings, adult, currently reading, missed"

## 👨‍💻 About the Author

**Francisco Teixeira Barbosa**  
*Data Science Enthusiast & Machine Learning Practitioner*

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Tuminha-black?style=for-the-badge&logo=github)](https://github.com/Tuminha)
[![Email](https://img.shields.io/badge/Email-cisco@periospot.com-red?style=for-the-badge&logo=gmail)](mailto:cisco@periospot.com)
[![Twitter](https://img.shields.io/badge/Twitter-cisco_research-blue?style=for-the-badge&logo=twitter)](https://twitter.com/cisco_research)

</div>

## 📖 Learning Resources

- [CodeCademy Data Science Path](https://www.codecademy.com/learn/paths/data-scientist)
- [OKCupid Dataset Documentation](https://github.com/rudeboybert/JSE_OkCupid)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)

## 🤝 Contributing

This is a learning project, but suggestions and improvements are welcome! Feel free to:
- Open issues for bugs or questions
- Suggest additional analysis approaches
- Share insights about the dataset

## 📄 License

This project is for educational purposes as part of the CodeCademy Data Science curriculum.

---

<div align="center">

**Happy Analyzing! 🚀**

*"Data is the new oil, but unlike oil, data is not a finite resource."*

</div>
