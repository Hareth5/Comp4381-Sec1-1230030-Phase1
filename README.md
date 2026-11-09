# Medical Insurance Charges: Smoking Status, Age, and BMI

**Course:** COMP 4381 — Data Science and Analytics, Birzeit University, 2026/2027<br>
**Student name:** Hareth shoman (from GitHub profile; confirm spelling)<br>
**Student ID:** 1230030<br>
**Section:** 1<br>
**Phase:** 1<br>
**Repository:** [Hareth5/Comp4381-Sec1-1230030-Phase1](https://github.com/Hareth5/Comp4381-Sec1-1230030-Phase1) (private; keep private)<br>
**Phase 1 deadline:** November 13, 2026, end of day, Asia/Hebron time.<br>
**Status:** Initial project setup; topic selected. Analysis and final report remain in progress.

## Topic, dataset, and objective

**Selected approved topic:** Medical Cost Prediction.<br>
**Dataset:** `insurance.csv` from the instructor's [Data-Science-Projects repository](https://github.com/asabbah44/Data-Science-Projects/tree/main/Medical%20Cost%20Prediction).

This project will investigate patterns in medical insurance charges using a small table of beneficiary attributes. The checked source file contains **1,338 rows and seven columns**: `age`, `sex`, `bmi`, `children`, `smoker`, `region`, and `charges`. One row represents a beneficiary record; no unique beneficiary identifier is supplied.

**Proposed analytical question:** How do insurance charges differ by smoking status, and how are charges associated with age and BMI?

Start with descriptive statistics, group comparisons, and interpretable charts. Use simple linear regression only if it helps answer the question and has been covered in class. Confirm all permitted libraries and techniques before expanding the analysis. No source notebooks, models, results, or conclusions are included.

See [data documentation](data/README.md) for provenance and variable definitions, and the [development plan](docs/project_plan.md) for the four project stages.

## Repository structure

```text
README.md
requirements.txt                 # Tested direct dependency versions
AGENTS.md                        # Deadline and repository instructions
.gitignore
.gitattributes
data/
  README.md                      # Source, dictionary, and data-quality notes
  source_metadata.json           # Source revision and SHA-256 checksum
  raw/insurance.csv              # Unmodified approved dataset
  processed/                     # Save justified derived data here later
notebooks/
  project.ipynb                  # Executable starter notebook with explanations
figures/                         # Save selected figures here during analysis
report/
  final_report.md                # Required-section outline; not a finished report
  final_report.pdf               # Create after completing the analysis (pending)
docs/
  course_requirements.md         # Supplied assignment, retained for reference
  project_plan.md
  submission_checklist.md
  submission_instructions.md     # Phase 1 deadline, TA, and Ritaj delivery rules
  verification.md
  source_repository_license.txt  # Notice accompanying the dataset source
```

## Run the notebook

The starter is tested with Python 3.14. Use the exact dependency versions in `requirements.txt`. From this repository's root in Windows PowerShell:

```powershell
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
.\.venv\Scripts\python.exe -m jupyterlab
```

On macOS/Linux, use `.venv/bin/python` in place of `.\.venv\Scripts\python.exe`.

Open `notebooks/project.ipynb`, select the virtual environment's Python kernel, then choose **Restart Kernel and Run All Cells**. The notebook finds the project root from its folder or the repository root; no machine-specific data paths are needed. The raw CSV is stored in this private repository, so running it does not require a dataset download.

To execute without the interactive interface, run from the repository root:

```powershell
.\.venv\Scripts\python.exe -m jupyter nbconvert --to notebook --execute --inplace --ExecutePreprocessor.kernel_name=python3 --ExecutePreprocessor.timeout=120 notebooks/project.ipynb
```

The initial notebook loads and audits the dataset. Later sections contain prompts for your own cleaning decisions, EDA, statistical reasoning, optional modeling/evaluation, and final interpretation. Running the starter successfully does not mean these stages are complete.

## GitHub development and access

Keep this repository private. The designated TA account is [Hadeel-Abdaljalil](https://github.com/Hadeel-Abdaljalil). A collaborator invitation was sent on November 9, 2026 and is **pending acceptance**. TA access is established only after acceptance. The instructor's GitHub username is still needed; do not infer it from the dataset author's username.

Make clear, meaningful commits as real work develops and push the latest working version throughout the semester. See [project_plan.md](docs/project_plan.md) for example commands. Do not upload only at the end or fabricate development history.

## Phase 1 submission

Commit and push all Phase 1 work before the end of November 13, 2026 (Asia/Hebron). **Do not modify the repository, commit, or push after that deadline.** Late updates lose marks.

The student will send the repository URL and a copy of `notebooks/project.ipynb` to the TA. The student will also submit the notebook through the designated Ritaj assignment by replying to its message, using **TA ID 9027**. Do not submit via Ritaj Memo or another method. These manual submissions are pending. See [submission instructions](docs/submission_instructions.md).

## Ethics, limitations, and originality

This project is an educational data-analysis exercise and does not provide professional decisions or advice. Do not use results for medical decisions, insurance pricing, or individual risk judgments. Discuss sensitive attributes, fairness, bias, confounding, and the source's limited documentation of sampling and collection. Observational associations do not establish causation.

Build the analysis independently and be able to explain every submitted component. Acknowledge external sources and assistance according to course policy. The setup and notebook scaffold were prepared with AI assistance; the student must review, understand, adapt, and disclose that assistance as required. No original source solution was copied.

## Remaining before submission

- Confirm the student name spelling.
- Verify that the TA has accepted the collaborator invitation; provide the instructor's GitHub username and verify instructor access.
- Confirm the methods/libraries taught in class. The assignment title says COMP 4381 but later refers to COMP2350.
- Complete the cleaning, interpreted EDA, appropriate analysis, ethics, and limitations.
- Finish the report and export `report/final_report.pdf`.
- Work through the [submission checklist](docs/submission_checklist.md).
