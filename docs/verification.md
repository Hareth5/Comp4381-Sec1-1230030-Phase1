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

Student ID and confirmed instructor/TA GitHub usernames are still needed. No collaborator invitations have been sent and no access is claimed for them.
