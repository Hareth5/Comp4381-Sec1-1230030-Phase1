# Medical Cost Prediction

**Student:** Hareth shoman<br>
**Student ID:** 1230030<br>
**Course:** COMP 4381 — Section 1<br>

## Topic and dataset

The selected topic is **Medical Cost Prediction** from the instructor's [approved repository](https://github.com/asabbah44/Data-Science-Projects/tree/main/Medical%20Cost%20Prediction).

The dataset is [insurance.csv](https://raw.githubusercontent.com/asabbah44/Data-Science-Projects/b170e5ff9104dcbcfacbc431d75cd08422721c91/Medical%20Cost%20Prediction/insurance.csv), included in `data/raw/insurance.csv`. It contains 1,338 beneficiary records and seven columns: `age`, `sex`, `bmi`, `children`, `smoker`, `region`, and `charges`.

## Initial objective and question

The project will examine how medical insurance charges vary with smoking status, age, and BMI.

**Question:** How do insurance charges differ by smoking status, and how are charges associated with age and BMI?

## Repository structure

```text
README.md
data/
  raw/
    insurance.csv
  processed/
notebooks/
figures/
report/
```

## Run the notebook

Install JupyterLab and pandas, then open JupyterLab:

```powershell
python -m pip install jupyterlab pandas
python -m jupyterlab
```

Open `notebooks/project.ipynb` and choose **Restart Kernel and Run All Cells**. The notebook uses relative paths; no personal file paths need changing.
