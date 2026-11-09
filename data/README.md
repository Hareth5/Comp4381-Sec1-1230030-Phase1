# Dataset provenance and dictionary

## Selected topic

Medical Cost Prediction, from the instructor-approved [Data-Science-Projects repository](https://github.com/asabbah44/Data-Science-Projects/tree/main/Medical%20Cost%20Prediction). The student selected this topic on 2026-11-09.

Only the CSV dataset and the source repository's license notice were downloaded. Existing source notebooks, code, models, results, and conclusions were not imported.

**Immutable source revision:** `b170e5ff9104dcbcfacbc431d75cd08422721c91`<br>
**Source file:** [insurance.csv](https://raw.githubusercontent.com/asabbah44/Data-Science-Projects/b170e5ff9104dcbcfacbc431d75cd08422721c91/Medical%20Cost%20Prediction/insurance.csv)<br>
**Description:** [source description](https://github.com/asabbah44/Data-Science-Projects/blob/b170e5ff9104dcbcfacbc431d75cd08422721c91/Medical%20Cost%20Prediction/description.md)<br>
**Local raw file:** `data/raw/insurance.csv`<br>
**Integrity metadata:** `data/source_metadata.json`

The upstream repository lists an MIT notice credited to **Sukhman Singh (2023)**; its notice is retained in `docs/source_repository_license.txt`. The supplied project description does not establish the dataset's original collection procedure, sampling frame, collection period, or separate dataset license. Do not invent provenance or assume the repository notice resolves all rights for other uses. The CSV is retained in this private course repository for the educational task.

## Initial inspection

- 1,338 records and seven columns, verified directly from the downloaded file.
- No blank/missing cells found in the initial inspection; verify again in the notebook.
- No unique person ID is provided. Identical rows are not sufficient evidence that two records belong to the same person; investigate before removing duplicates.
- Keep the raw file unchanged. Record each cleaning decision in the notebook and save any justified derived dataset to `data/processed/`.

## Data dictionary

| Column | Expected type | Meaning | Notes |
| --- | --- | --- | --- |
| `age` | Integer | Age of the primary beneficiary | Source age unit is understood as years; examine observed range. |
| `sex` | Category | Sex label recorded in the CSV | Preserve source terminology and discuss limited categories. |
| `bmi` | Decimal | Body mass index | Check range and extreme values; avoid clinical interpretation. |
| `children` | Integer | Number of children covered by the insurance | A count; check nonnegative values. |
| `smoker` | Category | Recorded smoking status | Expected labels `yes` and `no`; inspect actual labels. |
| `region` | Category | Beneficiary's US residential region | Regional categories do not establish national representativeness. |
| `charges` | Decimal | Individual medical costs billed by health insurance | Main outcome; exact billing period and currency are not established by the supplied source description. |

## Proposed scope

Compare charges across smoking-status groups and examine associations with age and BMI. Start with descriptive analysis. If a course-covered predictive method is justified, keep its evaluation separate from exploratory summaries and fit preprocessing on training data only.

## Responsible use

This project is an educational data-analysis exercise and does not provide professional decisions or advice. Do not treat associations as causal effects or use results to make decisions about individuals. Discuss privacy, sensitive attributes, possible unfair use, unmeasured confounders, and uncertain representativeness.
