# Project development plan

This repository starts at the setup stage. Unfinished analysis and report sections are intentionally marked as pending; they are not completed findings.

## Stage 1 — Topic selection and repository setup

- [x] Confirm an approved topic and dataset: Medical Cost Prediction.
- [x] Define the initial analytical question and unit of analysis in the README.
- [ ] Confirm student name and add student ID to the README and report.
- [x] Create and verify the private GitHub repository: `Hareth5/comp4381-medical-cost-analysis`.
- [ ] Invite the instructor and TA using their confirmed GitHub usernames.
- [x] Store the raw dataset and document its exact source.
- [ ] Verify which libraries and methods were taught in the course.

## Stage 2 — Data understanding and preparation

- [ ] Report shape, column types, and a data dictionary.
- [ ] Check missingness, duplicate rows, inconsistent categories, and extreme values.
- [ ] Explain each cleaning decision before applying it.
- [ ] Preserve the raw dataset; save justified derived data in `data/processed/`.

## Stage 3 — EDA and analysis

- [ ] Select summary statistics and charts that address the question.
- [ ] Interpret important tables and figures in Markdown.
- [ ] Apply appropriate statistical reasoning covered in class.
- [ ] Discuss assumptions and distinguish association from causation.

## Stage 4 — Final analysis and report

- [ ] Add modeling only if appropriate and taught; explain its justification.
- [ ] If modeling, use an appropriate holdout, baseline, metrics, and generalization discussion.
- [ ] Discuss ethics, findings, and limitations.
- [ ] Finish the report and export `report/final_report.pdf`.
- [ ] Run the notebook from a fresh kernel, top to bottom.
- [ ] Follow the final checklist and push the latest working files.

## Version control

Commit actual progress as it happens. Suggested future messages are `Document dataset quality checks`, `Explain cleaning decisions`, `Add interpreted exploratory figures`, and `Write findings and limitations`. Do not manufacture or backdate history. The initial setup commit alone does not satisfy the semester-long development requirement.

From the repository root:

```powershell
git status
git add README.md notebooks/project.ipynb
git commit -m "Describe the actual change"
git push
```

## Requirement ambiguity

The assignment is titled COMP 4381 but mentions COMP2350 in its method restrictions. Confirm this discrepancy and the exact permitted methods with the instructor. The supplied document specifies no submission date or report length.
