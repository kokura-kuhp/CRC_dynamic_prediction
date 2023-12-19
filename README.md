# CRC_dynamic_prediction

Dynamic prognostic prediction for patients with advanced and reccurent colorectal cancer

In many guidelines, multidisciplinary treatment is recommended for advanced and recurrent colorectal cnancer. We need to take it account for each patient characteristics, so personalized treatment strategy is required.

However, conventionial Cox proportional hazards model is based on fixed-point information. In order to these problems, we performed dynamic prediction by incorporating longitudinal tumor marker values and individual treatment history.

In this study, clinical data was extracted from Data Warehouse, receipt information, and hospital-based cancer registry in order to colloect patient information comprehensively and efficiently. Each files used in the analysis is described below.

# p01_dwh2table1
## p01_dwh2table_03_pts__ex_list.Rmd

Handling eligible patient from DWH

## p01_dwh2table1_04_mdmr_path_suv.Rmd

Extracting last-followup date from electoronic medical record

## p01_dwf2table1_05_table1.Rmd

Summarizing patient characteristics in Table 1

# p02_data_handling
## p02_data_handling_si.Rmd

Handling data on procedures from receipt information

## p02_data_handling.Rmd

Handling clinical data from DWH 

# p03_modeling
## p03_modeling.Rmd

Performing Cox proportional hazards model, mixed effect model and Joint model

# p04_eval_models
## p04_eval_model.Rmd

Comparison between measured CEA and predicted CEA

Copmarison between Cox proportional hazards model and Joint model

Case presentatioins

