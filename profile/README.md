# Exeter Diabetes research team Github repositories

This Github organisation contains a number of repositories from members of the Exeter Diabetes research team and collaborators. Many are linked to our ongoing work using CPRD data (Clinical Research Practice Datalink; UK primary care records and linked data). Of particular interest to others using CPRD data for research are the following repositories which are pinned below:
* **CPRD-Codelists**: Codelists (medcode, prodcode, HES [ICD10, OPCS4]) which we have developed for use with CPRD Aurum, and the algorithms we use when implementing them to define patient features. Also includes details of how we developed these codelists and the Read and SNOMED codelists produced during medcode list development.
* **CPRD-Cohort-scripts**: Details of the pipeline we use to flexibly define different diabetes cohorts (and pull in relevant patient features) from CPRD Aurum.
* **CPRD-analysis-package**: The R package (`aurum`) which we use to create our CPRD MySQL database from the raw data provided by CPRD, and query it from R. It also includes functions for adding codelists to MySQL and using these in queries. This package is used extensively in the scripts in the CPRD-Cohort-scripts repository.
* **EHRBiomarkr**: An R package to clean biomarker measurements in CPRD Aurum, and calculate CVD and kidney risk scores.
