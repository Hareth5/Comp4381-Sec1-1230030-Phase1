# Initial setup verification

Verified on 2026-11-09 with Python 3.14.4 on Windows.

- Installed the notebook environment in `.venv/`, which is excluded from Git.
- Recorded the tested direct dependency versions in `requirements.txt`.
- Ran `python -m pip check` in the virtual environment: no broken requirements.
- Executed `notebooks/project.ipynb` from a fresh Python kernel through `nbconvert`: completed without cell errors and saved its outputs.
- Verified the raw CSV against its documented SHA-256 checksum.
- Confirmed 1,338 records, seven columns, no missing cells, and one exact duplicate beyond the first occurrence.
- Created `Hareth5/comp4381-medical-cost-analysis` through GitHub and verified its private visibility.

The notebook locates data relative to the repository and contains no personal absolute data path. Git attributes preserve the raw dataset bytes so line-ending conversion does not invalidate its checksum.

These checks validate the initial setup and data audit. Preparation decisions, EDA, statistical analysis, optional modeling, final interpretations, and the final report remain to be completed. They have not been marked as passed or finished.

## Phase 1 submission setup update — November 9, 2026

- Recorded student ID 1230030, section 1, and phase 1 in the README, notebook, and report outline.
- Renamed the existing private repository to `Hareth5/Comp4381-Sec1-1230030-Phase1`, preserving its history, and updated the local origin URL.
- Sent a collaborator invitation to the confirmed TA account `Hadeel-Abdaljalil`. GitHub returned a newly created invitation with write permission (the supported collaborator role for this personal repository). The invitation is pending acceptance; TA access is not yet confirmed.
- Recorded the Phase 1 deadline: November 13, 2026, end of day in Asia/Hebron, with no repository changes, commits, or pushes after the cutoff.
- Recorded the student's decision to handle sending the notebook/repository URL and the Ritaj assignment reply (TA ID 9027) personally. Neither delivery is marked complete.

Student name spelling and the instructor's GitHub username still need confirmation. No instructor invitation has been sent.
