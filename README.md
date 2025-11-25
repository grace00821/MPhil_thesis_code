This README.txt file was generated on 20251125 by Eunhye Yang

-------------------
GENERAL INFORMATION
-------------------

1. Title of Dataset: Supporting data for Machine learning based prognosis prediction of
intracerebral hemorrhage outcome

2. Author Information

First Author Contact Information<br>
    Name: Eunhye Yang<br>
    Faculty: Li Ka Shing Faculty of Medicine<br>
    Email: eunhye@connect.hku.hk<br>



Corresponding Author Contact Information<br>
    Name: Joshua Wing Kei Ho<br>
    Faculty: Li Ka Shing Faculty of Medicine<br>
    Email: jwkho@hku.hk<br>


Author Contact Information (if applicable)<br>
    Name: Kay Cheong Teo<br>
    Faculty: Li Ka Shing Faculty of Medicine<br>
    Email: kcteo@hku.hk<br>


Author Contact Information (if applicable)<br>
    Name: Gary Kui Kai Lau<br>
    Faculty: Li Ka Shing Faculty of Medicine<br>
    Email: gkklau@hku.hk<br>


---------------------
DATA & FILE OVERVIEW
---------------------

Directory of Files: 00_preprocessing<p>
   A. Filename: 01_imputer_thesis.ipynb<br>
      Short description: Removal of any samples with missing outcoems and using MissForest to impute any missing information.<br>


        
   B. Filename: 02_correlation_thesis.ipynb<br>
      Short description: Correlation test across features to identify and select out any highly correlated features to minimize bias.<br>


        
   C. Filename: 03_normalizer_thesis.ipynb<br>
      Short description: Normalizing and scaling continuous features to [0, 1] range.<br>
    


   D. Filename: 04_onehotencoder_thesis.ipynb<br>
      Short description: One hot encoding any categorical features and scaling ordinal features to [0, 1] range.<br>

Directory of Files: main<p>
   A. Filename: 01_model_finetune_thesis.ipynb<br>
      Short description: Finetuning Random Forest, Extreme Gradient Boosting, and Gradient Boosting algorithms.<br>
   

   B. Filename: 02_model_selection_thesis.ipynb<br>
      Short description: Comparing the three finetuned algorithms using 10-fold cross validation.<br>
   

   C. Filename: 03_model_development_thesis.ipynb<br>
      Short description: Training and evaluating the selected algorithm on EMR. Also looks into feature importance of the model for interpretation.<br>


   D. Filename: 04_conventional_vs_detailed.ipynb<br>
      Short description: Comparing the model developed in file 03_model_development_thesis.ipynb to another model trained on conventional ICH scoring features to validate the superiority of the model developed in this study.<br>


   E. Filename: 05_counterfactual_thesis.ipynb<br>
      Short description: Using the model developed in file 03_model_development_thesis.ipynb to predict the counterfactual outcoem of surgical patient samples.<br>


   F. Filename: 06_covariate_selection_thesis.ipynb<br>
      Short description: Using correlation analysis and Random Forest algorithm to select out any covariates for surgical interventions. Estimate propensity score of the samples to retrieve the caliper score and the number of propensity score matched samples to select out the most suitable set of covaraites.<br>


   G. Filename: 07_ate_1to1_iptw_thesis.ipynb<br>
      Short description: Using covariates selected from the file 06_covariate_selection_thesis.ipynb to estimate the average treatment effect through propensity score matching and inverse-probability-of-treatment-weighting methods.<br>


Additional Notes on File Relationships, Context, or Content 
(for example, if a user wants to reuse and/or cite your data, 
what information would you want them to know?): Run the code files in the numbered order.

File Naming Convention: [FileNumber]_[ContentSummary]_thesis.[ext]

-----------------------------------------
DATA DESCRIPTION FOR: N/A
-----------------------------------------

No structured dataset is included in this project; therefore, no data dictionary is required.

1. Number of variables: N/A


2. Number of cases/rows: N/A


3. Missing data codes: N/A


4. Variable List

    A. Name: N/A<br>
       Description: N/A<br>


    B. Name: N/A<br>
       Description: N/A<br>

--------------------------
METHODOLOGICAL INFORMATION
--------------------------

1. Software-specific information: <br>

Name: N/A<br>
Version: N/A<br>
System Requirements: N/A<br>
Open Source? (Y/N): N/A<br>

(if available and applicable)<br>
Executable URL: N/A<br>
Source Repository URL: N/A<br>
Developer: N/A<br>
Product URL: N/A<br>
Software source components: N/A<br>


Additional Notes(such as, will this software not run on 
certain operating systems?): N/A

2. Equipment-specific information: N/A

Manufacturer: N/A<br>
Model: N/A

(if applicable)<br>
Embedded Software / Firmware Name: N/A<br>
Embedded Software / Firmware Version: N/A<br>
Additional Notes: N/A
