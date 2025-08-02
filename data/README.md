# Data
The [Cervical Cancer (Risk Factors) dataset](https://archive.ics.uci.edu/dataset/383/cervical+cancer+risk+factors) from the UCI Machine Learning Repository is a multivariate dataset containing demographic, behavioural, and historical medical records of 858 patients from a hospital in Caracas, Venezuela. The dataset's purpose is to predict indicators or a diagnosis of cervical cancer. The dataset contains 36 features and 4 target variables.

# Codebook for Cervical Cancer (Risk Factors) dataset

## Variable Names and Descriptions:

Age: The patient's age (in years).
Number of sexual partners: The number of sexual partners the patient has had.
First sexual intercourse: The patient's age at their first sexual intercourse (in years).
Num of pregnancies: The number of pregnancies the patient has had.
Smokes: A binary indicator of whether the patient is a smoker (1 = yes, 0 = no).
Smokes (years): The number of years the patient has been smoking.
Smokes (packs/year): The number of packs of cigarettes smoked per year.
Hormonal Contraceptives: A binary indicator of whether the patient uses hormonal contraceptives (1 = yes, 0 = no).
Hormonal Contraceptives (years): The number of years the patient has used hormonal contraceptives.
IUD: A binary indicator of whether the patient uses an Intrauterine Device (IUD) (1 = yes, 0 = no).
IUD (years): The number of years the patient has used an IUD.
STDs: A binary indicator of whether the patient has or has had sexually transmitted diseases (STDs) (1 = yes, 0 = no).
STDs (number): The number of STDs diagnosed.
STDs:condylomatosis: A binary indicator for condylomatosis (1 = yes, 0 = no).
STDs:cervical condylomatosis: A binary indicator for cervical condylomatosis (1 = yes, 0 = no).
STDs:vaginal condylomatosis: A binary indicator for vaginal condylomatosis (1 = yes, 0 = no).
STDs:vulvo-perineal condylomatosis: A binary indicator for vulvo-perineal condylomatosis (1 = yes, 0 = no).
STDs:syphilis: A binary indicator for syphilis (1 = yes, 0 = no).
STDs:pelvic inflammatory disease: A binary indicator for pelvic inflammatory disease (1 = yes, 0 = no).
STDs:genital herpes: A binary indicator for genital herpes (1 = yes, 0 = no).
STDs:molluscum contagiosum: A binary indicator for molluscum contagiosum (1 = yes, 0 = no).
STDs:AIDS: A binary indicator for AIDS (1 = yes, 0 = no).
STDs:HIV: A binary indicator for HIV (1 = yes, 0 = no).
STDs:Hepatitis B: A binary indicator for Hepatitis B (1 = yes, 0 = no).
STDs:HPV: A binary indicator for HPV (1 = yes, 0 = no).
STDs: Time since first diagnosis: The time in months since the first STD diagnosis.
STDs: Time since last diagnosis: The time in months since the last STD diagnosis.
Dx:Cancer: A binary indicator from the doctor's diagnosis for cancer (1 = yes, 0 = no).
Dx:CIN: A binary indicator from the doctor's diagnosis for Cervical Intraepithelial Neoplasia (CIN) (1 = yes, 0 = no).
Dx:HPV: A binary indicator from the doctor's diagnosis for HPV (1 = yes, 0 = no).
Dx: A binary indicator for any of the above diagnoses (Dx:Cancer, Dx:CIN, Dx:HPV) (1 = yes, 0 = no).
Hinselmann: A binary target variable from a Hinselmann test result (1 = positive, 0 = negative).
Schiller: A binary target variable from a Schiller test result (1 = positive, 0 = negative).
Citology: A binary target variable from a cytology test result (1 = positive, 0 = negative).
Biopsy: A binary target variable from a biopsy test result (1 = positive, 0 = negative).

## Data Types:

Age                                 858 non-null    int64  
Number of sexual partners           832 non-null    float64
First sexual intercourse            851 non-null    float64
Num of pregnancies                  802 non-null    float64
Smokes                              845 non-null    float64
Smokes (years)                      845 non-null    float64
Smokes (packs/year)                 845 non-null    float64
Hormonal Contraceptives             750 non-null    float64
Hormonal Contraceptives (years)     750 non-null    float64
IUD                                 741 non-null    float64
IUD (years)                         741 non-null    float64
STDs                                753 non-null    float64
STDs (number)                       753 non-null    float64
STDs:condylomatosis                 753 non-null    float64
STDs:cervical condylomatosis        753 non-null    float64
STDs:vaginal condylomatosis         753 non-null    float64
STDs:vulvo-perineal condylomatosis  753 non-null    float64
STDs:syphilis                       753 non-null    float64
STDs:pelvic inflammatory disease    753 non-null    float64
STDs:genital herpes                 753 non-null    float64
STDs:molluscum contagiosum          753 non-null    float64
STDs:AIDS                           753 non-null    float64
STDs:HIV                            753 non-null    float64
STDs:Hepatitis B                    753 non-null    float64 
STDs:HPV                            753 non-null    float64
STDs: Number of diagnosis           858 non-null    int64  
STDs: Time since first diagnosis    71 non-null     float64
STDs: Time since last diagnosis     71 non-null     float64
Dx:Cancer                           858 non-null    int64  
Dx:CIN                              858 non-null    int64  
Dx:HPV                              858 non-null    int64  
Dx                                  858 non-null    int64  
Hinselmann                          858 non-null    int64  
Schiller                            858 non-null    int64  
Citology                            858 non-null    int64  
Biopsy                              858 non-null    int64 


