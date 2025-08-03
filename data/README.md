# Data
The [Cervical Cancer (Risk Factors) dataset](https://archive.ics.uci.edu/dataset/383/cervical+cancer+risk+factors) from the UCI Machine Learning Repository is a multivariate dataset containing demographic, behavioural, and historical medical records of 858 patients from a hospital in Caracas, Venezuela. The dataset's purpose is to predict indicators or a diagnosis of cervical cancer. The dataset contains 36 features and 4 target variables.

# Codebook for Cervical Cancer (Risk Factors) dataset

## [Variable Names, Data Types and Descriptions:](https://archive.ics.uci.edu/dataset/383/cervical+cancer+risk+factors)

| Variable Name                               | Description                                                                                                   | Data Type |
|---------------------------------------------|---------------------------------------------------------------------------------------------------------------|-----------|
| Age                                         | The patient's age (in years).                                                                                 | int64     |
| Number of sexual partners                   | The number of sexual partners the patient has had.                                                            | float64   |
| First sexual intercourse                    | The patient's age at their first sexual intercourse (in years).                                               | float64   |
| Num of pregnancies                          | The number of pregnancies the patient has had.                                                                | float64   |
| Smokes                                      | A binary indicator of whether the patient is a smoker (1 = yes, 0 = no).                                      | float64   |
| Smokes (years)                              | The number of years the patient has been smoking.                                                             | float64   |
| Smokes (packs/year)                         | The number of packs of cigarettes smoked per year.                                                            | float64   |
| Hormonal Contraceptives                     | A binary indicator of whether the patient uses hormonal contraceptives (1 = yes, 0 = no).                     | float64   |
| Hormonal Contraceptives (years)             | The number of years the patient has used hormonal contraceptives.                                             | float64   |
| IUD                                         | A binary indicator of whether the patient uses an Intrauterine Device (IUD) (1 = yes, 0 = no).                | float64   |
| IUD (years)                                 | The number of years the patient has used an IUD.                                                              | float64   |
| STDs                                        | A binary indicator of whether the patient has or has had STDs (1 = yes, 0 = no).                              | float64   |
| STDs (number)                               | The number of STDs diagnosed.                                                                                 | float64   |
| STDs:condylomatosis                         | A binary indicator for condylomatosis (1 = yes, 0 = no).                                                      | float64   |
| STDs:cervical condylomatosis                | A binary indicator for cervical condylomatosis (1 = yes, 0 = no).                                             | float64   |
| STDs:vaginal condylomatosis                 | A binary indicator for vaginal condylomatosis (1 = yes, 0 = no).                                              | float64   |
| STDs:vulvo-perineal condylomatosis          | A binary indicator for vulvo-perineal condylomatosis (1 = yes, 0 = no).                                       | float64   |
| STDs:syphilis                               | A binary indicator for syphilis (1 = yes, 0 = no).                                                            | float64   |
| STDs:pelvic inflammatory disease            | A binary indicator for pelvic inflammatory disease (1 = yes, 0 = no).                                         | float64   |
| STDs:genital herpes                         | A binary indicator for genital herpes (1 = yes, 0 = no).                                                      | float64   |
| STDs:molluscum contagiosum                  | A binary indicator for molluscum contagiosum (1 = yes, 0 = no).                                               | float64   |
| STDs:AIDS                                   | A binary indicator for AIDS (1 = yes, 0 = no).                                                                | float64   |
| STDs:HIV                                    | A binary indicator for HIV (1 = yes, 0 = no).                                                                 | float64   |
| STDs:Hepatitis B                            | A binary indicator for Hepatitis B (1 = yes, 0 = no).                                                         | float64   |
| STDs:HPV                                    | A binary indicator for HPV (1 = yes, 0 = no).                                                                 | float64   |
| STDs: Number of diagnosis                   | The number of STDs diagnosed.                                                                                 | int64     |
| STDs: Time since first diagnosis            | The time in months since the first STD diagnosis.                                                             | float64   |
| STDs: Time since last diagnosis             | The time in months since the last STD diagnosis.                                                              | float64   |
| Dx:Cancer                                   | A binary indicator from the doctor's diagnosis for cancer (1 = yes, 0 = no).                                  | int64     |
| Dx:CIN                                      | A binary indicator from the doctor's diagnosis for Cervical Intraepithelial Neoplasia (CIN) (1 = yes, 0 = no).| int64     |
| Dx:HPV                                      | A binary indicator from the doctor's diagnosis for HPV (1 = yes, 0 = no).                                     | int64     |
| Dx                                          | A binary indicator for any of the above diagnoses (Dx:Cancer, Dx:CIN, Dx:HPV) (1 = yes, 0 = no).              | int64     |
| Hinselmann                                  | A binary target variable from a Hinselmann test result (1 = positive, 0 = negative).                          | int64     |
| Schiller                                    | A binary target variable from a Schiller test result (1 = positive, 0 = negative).                            | int64     |
| Citology                                    | A binary target variable from a cytology test result (1 = positive, 0 = negative).                            | int64     |
| Biopsy                                      | A binary target variable from a biopsy test result (1 = positive, 0 = negative).                              | float64   |

