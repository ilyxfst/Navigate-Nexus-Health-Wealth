# NAVIGATING THE NEXUS OF HEALTH AND WEALTH
## A Survival Analysis Model for Chronic Disease Management, Cost Efficiency and Quality Care in Health Insurance

### Project Proposal

One of the main objectives of health insurance organizations is to ensure the health and well-being of their participating members. We propose the development of a survival analysis model, specifically one using Cox proportional hazards regression, to identify members who have been diagnosed with a chronic disease—and/or members with a comorbidity—and are most at risk of death. A well performing model could lead to improved quality of care for health plan members and bring significant financial benefits to health insurers.

- **Cox Model**. Research has shown the Cox proportional hazards regression model to be highly effective in predicting time-to-event outcomes, particularly in medical research. The Cox model is semi-parametric and thus makes fewer assumptions about the underlying data enabling it to be more robust and flexible than other models. In addition, the hazard ratio inherent in the model can be directly interpreted in terms of risk. For example, a hazard ratio of 1.25 for a specific covariate—say, smoking—would mean that, holding other covariates constant, smokers have a 25% higher risk of the death (the event) compared to non-smokers. In its basic form, the Cox model assumes a linear relationship between the log-hazard and each covariate. However, the model can be extended to handle complex interactions and non-linear relationships between covariates. Extensions range from covariate transformations and splines to neural network models like Cox-nnet and DeepSurv.

- **Enhanced Preventive Care and Improved Quality of Care**. Survival analysis and the Cox model can help to identify the most significant predictors of adverse health events, this can lead to the development of personalized care plans and targeted preventive care strategies (e.g. a “house-call” program for a segment of a health plan’s Medicaid enrollees). Additionally, proactively Identifying health plan members at high risk of sickness/death can help manage their conditions more effectively, potentially slowing disease progression, improving their quality of life, and even extending their lifespan.
  
- **Profitability and Resource Optimization**. Identifying health plan members most at risk of death is not only crucial for their health but also for the financial health of the organization managing their care. Members with chronic diseases and comorbidities often require extensive medical care, leading to high costs. By identifying these members early, health insurers can implement preventive measures and disease management programs that can reduce hospitalizations, emergency room visits, as well as other forms of resource-intensive high-cost care, thereby reducing overall healthcare costs. In addition, improved resource allocation where high-risk members can be prioritized for interventions, while low- risk members can be monitored less intensively ensures that resources are used where they are most needed, improving efficiency and potentially reducing costs.

- **Financial Forecasting and Improved Risk Stratification**: Our proposed model can aid in financial forecasting. By predicting the number and timing of adverse events, health insurers can estimate future healthcare costs. This can inform pricing strategies, ensuring that premiums cover expected costs. Furthermore, by identifying factors that influence the time to an event (e.g., hospitalization, cancer recurrence, death), health plan members can be stratified into different risk categories. This proactive identification of risk can help insurers reduce their Medical Loss Ratio (MLR). The MLR is a metric established by the Affordable Care Act (ACA) that represents the percentage of insurance premium dollars that a health insurer spends on healthcare and quality improvement activities, compared to administrative costs, marketing, and profits. If an insurer does not meet these MLR standards, they are required to provide rebates to policyholders. Therefore, a lower MLR can be advantageous for insurers as it means they are spending less on healthcare costs relative to the premiums they collect, reducing the likelihood of having to issue rebates.

- **Federal Reimbursements**. Our proposed model can also increase federal reimbursement to health insurers from programs such as the Healthcare Effectiveness Data and Information Set (HEDIS). HEDIS measures the performance of health plans on various dimensions of care and service. By improving care for individuals with chronic diseases who are most at risk of death, health plans can improve HEDIS scores, which can lead to higher federal reimbursements.
  
### Source Data
We have two datasets from which we expect to create our model/s.

- The Breast Cancer Wisconsin (Prognostic) dataset is a widely used dataset in machine learning and data mining for the purpose of developing predictive models. It's a collection of samples taken from patients who had been diagnosed with breast cancer. Each sample is described by a set of features that were computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. The dataset includes information about the characteristics of the cell nuclei present in the image, and it also includes key features for survival analysis (whether the cancer recurred, time between follow-up and recurrence). The features in the dataset include information like the radius of the cell, texture, perimeter, area, smoothness, compactness, concavity, number of concave points, symmetry, and fractal dimension.
  
- The Worcester Heart Attack Study dataset is the result of a 30-Year perspective study (1975– 2005) on patients hospitalized with initial acute myocardial infarction. The dataset includes key features for survival analysis (death event, and time to death) as well as health and demographic characteristics of each patient.
  
### Our Team

#### Project Leader:
- **Scott Howard**: Responsible for the design and direction of research.

#### Researchers and Developers:
- **Esther Xu**: Main developer responsible for research and statistical/machine learning development. Esther has led the development efforts, ensuring the integration of advanced algorithms and overseeing the implementation of key components.
- **Mu (Airc) Miao**: Responsible for research and statistical/machine learning development. Contributed significantly to the development and fine-tuning of the machine learning models.


### References
- Clark TG, Bradburn MJ, Love SB, Altman DG. Survival analysis part I: basic concepts and first analyses. Br J Cancer. 2003 Jul 21;89(2):232-8. doi: 10.1038/sj.bjc.6601118. PMID: 12865907; PMCID: PMC2394262.
- Cox-nnet. https://github.com/lanagarmire/cox-nnet
- DeepSurv. https://github.com/jaredleekatzman/DeepSurv
- Deo SV, Deo V, Sundaram V. Survival analysis-part 2: Cox proportional hazards model. Indian J
Thorac Cardiovasc Surg. 2021 Mar;37(2):229-233. doi: 10.1007/s12055-020-01108-7. Epub 2021
Jan 2. PMID: 33642726; PMCID: PMC7876211.
- HEDIS. https://health.gov/healthypeople/objectives-and-data/data-sources-and-methods/data-
sources/healthcare-effectiveness-data-and-information-set-hedis#:~:text=The%20Healthcare%20Effectiveness%20Data%20and,report%20quality%20results
%20using%20HEDIS
- Medical Loss Ratio. https://www.cms.gov/cciio/programs-and-initiatives/health-insurance-
market-reforms/medical-loss-ratio
- UCI Breast Cancer (Prognostic) dataset.
https://archive.ics.uci.edu/dataset/16/breast+cancer+wisconsin+prognostic
- Worcester Heart Attack Study.
https://www.ahajournals.org/doi/10.1161/CIRCOUTCOMES.108.811828?url_ver=Z39.88- 2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed
