# IND AS 109/IFRS 9 EXPECTED CREDIT LOSS (ECL) MODELLING

**A Comprehensive End-to-End Methodology from Raw Freddie Mac Mortgage Cohorts to Systemic Life-Cycle Provisions under IFRS 9 and Ind AS 109**

*   **Model Developer:** CA Sumit Mahato
*   **Reference Data Source:** Freddie Mac Single-Family Loan-Level Dataset (2015 Q1 – 2025 Q3)
*   **Regulatory Frameworks:** IFRS 9 (International Financial Reporting Standards) and Ind AS 109 (Indian Accounting Standard)

*All methodologies, parameter estimates, and views in this report reflect the model developer’s personal analytical work and are included for portfolio demonstration purposes. They are not presented as a corporate, institutional, or regulatory submission.*

---

## Abstract
This report develops an end-to-end expected credit loss modelling framework for residential mortgage portfolios. It begins with raw Freddie Mac loan-level data, applies data quality checks and cohort construction, estimates TTC and PIT PD models, derives lifetime LGD and EAD components, and integrates them into IFRS 9 and Ind AS 109 compliant ECL calculations. The framework is intended as a portfolio demonstration of practical credit risk modelling rather than an official regulatory submission.

This report presents an empirical, end-to-end implementation of the IFRS 9 and Ind AS 109 Expected Credit Loss framework for residential mortgage portfolios. The analysis begins with a raw sample of 10,000 loans drawn from the Freddie Mac Single-Family Loan-Level Dataset covering 2015 through 2025Q3 and develops the modelling components needed to estimate portfolio-level credit provisions. The model architecture integrates a static Through-the-Cycle (TTC) Probability of Default (PD) scorecard, a forward-looking Point-in-Time (PIT) macro-financial Vasicek–Merton linkage, a lifetime workout Loss Given Default (LGD) model with House Price Index (HPI) property indexation, and a contractual Exposure at Default (EAD) amortisation schedule. The report documents raw data pre-processing, Weight of Evidence (WOE) variable binning, snapshot filtering, and credit staging rules, together with the key modelling limitations encountered — specifically the constraint of forcing a zero intercept in the systematic Z-score regression to preserve statistical significance (p-value < 5%), and the lag selection of macroeconomic variables (GDP YoY growth lagged by two quarters) required to maintain economically consistent sign behaviour. LGD is evaluated purely on a lifetime basis using realised workout dynamics. All findings represent the personal assessments of the model developer.

---

## Full Report (Page-by-Page View)
Below is the complete, high-resolution rendering of the report:

![Page 1](images/page_1.png)
![Page 2](images/page_2.png)
![Page 3](images/page_3.png)
![Page 4](images/page_4.png)
![Page 5](images/page_5.png)
![Page 6](images/page_6.png)
![Page 7](images/page_7.png)
![Page 8](images/page_8.png)
![Page 9](images/page_9.png)
![Page 10](images/page_10.png)
![Page 11](images/page_11.png)
![Page 12](images/page_12.png)
![Page 13](images/page_13.png)
![Page 14](images/page_14.png)
![Page 15](images/page_15.png)
![Page 16](images/page_16.png)
![Page 17](images/page_17.png)
![Page 18](images/page_18.png)
![Page 19](images/page_19.png)
![Page 20](images/page_20.png)
![Page 21](images/page_21.png)
![Page 22](images/page_22.png)
![Page 23](images/page_23.png)
![Page 24](images/page_24.png)
![Page 25](images/page_25.png)
![Page 26](images/page_26.png)
