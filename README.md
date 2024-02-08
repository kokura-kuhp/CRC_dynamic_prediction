# CRC_dynamic_prediction

Dynamic prognostic prediction for patients with advanced and reccurent colorectal cancer

In many guidelines, multidisciplinary treatment is recommended for advanced and recurrent colorectal cnancer. We need to take it account for each patient characteristics, so personalized treatment strategy is required.

However, conventionial Cox proportional hazards model is based on fixed-point information. In order to these problems, we performed dynamic prediction by incorporating longitudinal tumor marker values and individual treatment history.

In this study, clinical data was extracted from Data Warehouse, receipt information, and hospital-based cancer registry in order to colloect patient information comprehensively and efficiently. Each files used in the analysis is described below.

# p01_dwh2table1

1. Handling eligible patient from DWH

2. Extracting last-followup date from electoronic medical record

3. Summarizing patient characteristics in Table 1

# p02_data_handling

1. Handling data on procedures from receipt information

2. Handling clinical data from DWH 

# p03_modeling

Performing Cox proportional hazards model, mixed effect model and Joint model

# p04_eval_models

Comparison between measured CEA and predicted CEA

Copmarison between Cox proportional hazards model and Joint model

Case presentatioin

# p05_validation

The number of patients who received each treatment