# Medical Insurance Charges: Smoking Status, Age, and BMI

**Course:** COMP 4381 — Data Science and Analytics, Birzeit University, 2026/2027<br>
**Student:** Hareth shoman<br>
**Student ID:** 1230030<br>
**Section:** 1<br>
**Phase:** 1 — Topic Selection and Repository Setup<br>
**Private repository:** [Comp4381-Sec1-1230030-Phase1](https://github.com/Hareth5/Comp4381-Sec1-1230030-Phase1)

## Selected topic and dataset

**Topic:** Medical Cost Prediction, selected from the instructor's [approved repository](https://github.com/asabbah44/Data-Science-Projects/tree/main/Medical%20Cost%20Prediction).

**Dataset:** `insurance.csv`, stored unchanged in `data/raw/insurance.csv`. It contains 1,338 beneficiary records and seven columns: age, sex, BMI, number of children, smoking status, residential region, and insurance charges. See [data/README.md](data/README.md) for the source.

## Project description and initial objective

This project will investigate how medical insurance charges vary with recorded beneficiary characteristics. It provides a manageable setting for exploring relationships between numerical measurements, categories, and charges.

**Initial analytical question:** How do insurance charges differ by smoking status, and how are charges associated with age and BMI?

One row represents a beneficiary record. The objective is to describe associations in this supplied dataset. This is an educational data-analysis exercise and does not provide professional decisions or advice.

## Repository structure

```text
README.md
requirements.txt
.gitignore
.gitattributes
data/
  README.md
  SOURCE_LICENSE.txt
  raw/
    insurance.csv
notebooks/
  project.ipynb
```

## Run the Phase 1 notebook

Tested with Python 3.14. From the repository root in Windows PowerShell:

```powershell
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
.\.venv\Scripts\python.exe -m jupyterlab
```

Open `notebooks/project.ipynb`, select the virtual environment's Python kernel, and choose **Restart Kernel and Run All Cells**. On macOS/Linux, use `.venv/bin/python` instead of `.\.venv\Scripts\python.exe`.

The notebook introduces the topic, dataset, and objective, then loads a preview using a portable relative path. The CSV is included, so no runtime dataset download is needed.

## Phase 1 submission checklist

- [x] Select an approved topic and dataset.
- [x] Define the initial project question and unit of analysis.
- [x] Create the private repository with the required name.
- [x] Create the initial README and add/document the dataset.
- [x] Prepare the Phase 1 notebook.
- [x] Send a collaborator invitation to TA [Hadeel-Abdaljalil](https://github.com/Hadeel-Abdaljalil).
- [ ] Verify TA acceptance; invitation was pending when last checked.
- [ ] Add the instructor once their GitHub username is provided.
- [ ] Review the final Phase 1 notebook and verify the intended version is committed and pushed before the deadline.
- [ ] Send the TA the repository URL and a notebook copy (student will do this).
- [ ] Submit the notebook by replying to the designated Ritaj assignment message using **TA ID 9027** (student will do this). Do not use Ritaj Memo or another method.

**Deadline:** End of November 13, 2026, Asia/Hebron time. Complete all repository changes, commits, and pushes before November 14 at 00:00 local time. **Do not modify the repository, commit, or push after the deadline.**

## Sources and acknowledgment

The dataset comes from the approved repository; its source notice is retained in `data/SOURCE_LICENSE.txt`. No source notebook, code, model, results, or conclusions were copied. AI assistance was used for repository setup and the Phase 1 notebook; review, understand, and disclose that assistance according to course policy.
