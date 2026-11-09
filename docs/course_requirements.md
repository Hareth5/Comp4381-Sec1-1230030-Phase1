BIRZEIT UNIVERSITY 

**Data Science and Analytics  |  Course Project** 

**COMP 4381** 

# **Individual Data Science Course Project** 

Data Science and Analytics | 2026/2027 

**Project type** Individual **Development environment** Jupyter Notebook + GitHub **Repository** Private GitHub repository **Main deliverables** GitHub repository + Jupyter Notebook(s) + Final Report **Approved topic/dataset source** Data-Science-Projects repository provided by the instructor Dr. Ahmed Sabbah **Instructors** Dr. Tasmin Zayet 

## **1. Project Overview** 

The objective of this project is to apply the concepts and methods learned in data science and analytics course  to a real dataset. Each student must complete the project individually. 

Each student must select one project topic and its associated dataset from following repository: 

<u>https://github.com/asabbah44/Data-Science-Projects</u> 

**Important:** Students are selecting the topic and dataset only. Existing notebooks, code, models, results, and conclusions in the source repository are not the solution to this project and must not be copied. 

Some source projects use methods beyond course. Your analysis must be rebuilt from the beginning using only the concepts, methods, libraries, and techniques taught in this course. 

## **2. Individual Work** 

This is an individual project. Each student is responsible for the complete project and must be able to explain every submitted component, including: 

- topic and dataset selection. 

- problem formulation and analytical question. 

- data understanding and preparation. 

- Python code and visualizations. 

- statistical or predictive analysis, when appropriate. 

- interpretation of results and limitations. 

- GitHub repository management. 

- the final written report. 



<!-- Start of picture text -->
BIRZEIT UNIVERSITY<br><!-- End of picture text -->

**Data Science and Analytics  |  Course Project** 

## **3. GitHub Repository Requirement** 

Each student must create a private GitHub repository for the project. All project work must be maintained in this repository throughout the semester. The instructor and TA must be granted access to the private repository. 

Recommended repository structure: 

```
README.md
data/
    raw/
    processed/
notebooks/
    project.ipynb
figures/
report/
    final_report.pdf
```

The README.md file must include: 

- student name and student ID. 

- project title. 

- selected topic and dataset. 

- short project description. 

- analytical question or objective; 

- repository structure; 

- instructions for running the notebook. 

## **4. GitHub Development Rules** 

GitHub is part of the project, not only a place for the final submission. Students are expected to: 

- create the repository at the beginning of the project. 

- add files gradually as the project develops. 

- make meaningful commits throughout the semester. 

- use clear commit messages. 

- keep the repository organized. 

- maintain the latest working version of the project on GitHub. 

**Uploading the entire project only at the end does not demonstrate proper use of version control.** 

## **5. Required Data Science Process** 

The project should follow the data-science process studied in the course. Not every project must use every available technique. Methods should be selected because they are appropriate for the project question and dataset. 

### **A. Problem Formulation** 

- Explain the problem being studied and why it matters. 



<!-- Start of picture text -->
BIRZEIT UNIVERSITY<br><!-- End of picture text -->

**Data Science and Analytics  |  Course Project** 

- State a clear analytical question or objective. 

- Describe what the dataset represents and the relevant unit of analysis. 

- Identify the type of analysis that is appropriate. 

- Begin with the problem and data - not with a machine-learning algorithm. 

### **B. Data Understanding** 

- Describe the data source. 

- Report the number of observations (instances) and variables. 

- Explain important variables/features and their data types. 

- Identify the target variable, when applicable. 

- Discuss important characteristics and limitations of the dataset. 

### **C. Data Preparation** 

- Correct data types where necessary. 

- Handle missing values appropriately. 

- Identify and handle duplicates and inconsistent values. 

- Investigate extreme values/outliers where relevant. 

- Apply categorical encoding, scaling/normalization, and introductory feature engineering when needed. 

- Explain every important preprocessing decision. 

### **D. Exploratory Data Analysis and Visualization** 

- Use appropriate descriptive statistics. 

- Investigate distributions, patterns, relationships, anomalies, and associations relevant to the objective. 

- Choose visualizations because they help answer a question, not simply to increase the number of figures. 

- Interpret every important table or figure in words. 

### **E. Statistical or Analytical Reasoning** 

- Where appropriate, apply concepts studied in the course such as sampling, probability, confidence intervals, hypothesis testing, bootstrap, correlation, and regression. 

- Do not force a statistical method into a project when it is not relevant. 

### **F. Predictive or Unsupervised Analysis** 

- When appropriate, use introductory predictive or unsupervised techniques taught in the course. 

- Examples may include simple linear regression, introductory classification methods taught in the course, clustering, or introductory association analysis. 

- The method must be appropriate to the question and must have been covered in the course. 

**Restriction on advanced methods:** Do not use an advanced algorithm simply because it appears in the original project notebook. Methods such as neural networks, LSTM, or any other technique not taught in the course are not automatically allowed. 

## **6. Model Evaluation** 

If the project includes a predictive model, evaluate it using methods learned in the course. Depending on the task, this may include: 

- training and test data. 

- prediction errors. 

- confusion matrix. 



<!-- Start of picture text -->
BIRZEIT UNIVERSITY<br><!-- End of picture text -->

**Data Science and Analytics  |  Course Project** 

- accuracy, precision, recall, and F1-score. 

- ROC/AUC where appropriate and covered. 

- discussion of overfitting and generalization. 

Do not report a metric without explaining what it means for your project. 

## **7. Ethics and Responsible Data Use** 

Every project must include a short discussion of relevant ethical considerations. Depending on the dataset, consider privacy, sensitive information, bias, fairness, limitations, misleading interpretations, and responsible use of results. 

For medical, financial, or other sensitive datasets, clearly state that the project is an educational data-analysis exercise and does not provide professional decisions or advice. 

## **8. Jupyter Notebook Requirements** 

All Python analysis must be completed using Jupyter Notebook. The notebook must: 

- run from beginning to end. 

- contain both code and Markdown explanations. 

- organize the stages of the analysis clearly. 

- explain the purpose of important code. 

- explain important outputs. 

- include appropriate tables and visualizations. 

- finish with the main findings and limitations. 

A notebook containing only Python code is not acceptable. A notebook containing many outputs without interpretation is also not acceptable. 

## **9. Reproducibility** 

The project must be reproducible. The notebook should run without requiring the instructor to manually change local file paths. Datasets should either be stored in the private repository or downloaded programmatically from a stable source. 

Use relative paths whenever possible. Example: 

```
data = pd.read_csv("data/raw/dataset.csv")
```

## **10. Final Report** 

Each student must submit a professionally written final report. The report should explain the analysis rather than reproduce the entire notebook. It should contain: 

1. Title 

2. Project Objective / Problem Formulation 

3. Dataset Description 

4. Data Preparation 

5. Exploratory Data Analysis 

6. Statistical / Analytical Methods 

7. Predictive or Unsupervised Analysis, when applicable 

8. Evaluation 

#### BIRZEIT UNIVERSITY 

**Data Science and Analytics  |  Course Project** 

9. Main Findings and Interpretation 

10. Ethical Considerations 

11. Limitations 

12. Conclusion 

13. References, when applicable 

Do not submit a report consisting mainly of screenshots of Python code. Important tables and figures may be included, but each should support the written analysis and be interpreted in the text. 

## **11. Project Development Stages** 

|**Stage**|**Main focus**|**Required work**|
|---|---|---|
|**1**|**Topic Selection and Repository Setup**|Select one approved topic and dataset.<br>Create the private GitHub repository.<br>Create the initial README. Add or<br>document the dataset. Define the initial<br>project objective/question.|
|**2**|**Data Understanding and Preparation**|Explore the dataset. Document variables<br>and data types. Identify data-quality<br>problems. Clean and preprocess the data.<br>explain preprocessing decisions.|
|**3**|**EDA and Analysis**|Perform exploratory analysis. Create<br>appropriate visualizations. Investigate<br>important patterns and relationships.<br>Apply relevant statistical concepts<br>covered in the course.|
|**4**|**Final Analysis and Report**|Apply an appropriate predictive or<br>unsupervised method when relevant.<br>Evaluate results. Discuss ethics and<br>limitations. Finalize the notebook, report,<br>and reproducible repository.|



## **12. Use of the Source Repository** 

The approved source repository contains existing notebooks that may help students understand the general topic and dataset. These notebooks are not templates to reproduce. 

Students must not: 

- copy the original notebook. 

- copy blocks of code without understanding them. 

- reproduce the original results and submit them as their own. 

- use advanced models merely because the original notebook uses them. or 

- structure the entire analysis by copying the original project solution. 

The same dataset can support a different analytical question, different preprocessing decisions, different visualizations, and a different model. The submitted project must demonstrate what the student learned in COMP2350. 



<!-- Start of picture text -->
BIRZEIT UNIVERSITY<br><!-- End of picture text -->

**Data Science and Analytics  |  Course Project** 

## **13. Academic Integrity** 

All submitted work must reflect the student's own understanding. Students must be able to explain their code, preprocessing decisions, visualizations, statistical reasoning, model selection, evaluation results, and conclusions. 

Code or analysis that the student cannot explain may be treated as evidence that the work is not their own. Any external source used must be acknowledged appropriately. 

## **14. Final Submission Checklist** 

- ☐ The project is my individual work. 

- ☐ The GitHub repository is private and the instructor has access. 

- ☐ The selected topic and dataset come from the approved repository. 

- ☐ The notebook runs from start to finish. 

- ☐ Only methods taught in COMP2350 are used. 

- ☐ Important preprocessing decisions are explained. 

- ☐ Visualizations are interpreted, not only displayed. 

- ☐ The selected analytical/modeling method is justified. 

- ☐ Evaluation metrics are explained. 

- ☐ Ethics and limitations are discussed. 

- ☐ The report and repository are professionally organized. 

- ☐ The GitHub commit history shows genuine project development. 

- **The quality of the project will be judged by the correctness of the process, the clarity of the reasoning, and the student's ability to explain the work - not by using the most complex algorithm.** 

