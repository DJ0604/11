

Downloading 13 objects requires the command-line tool
Only individual objects can be downloaded using the Cloud Console. To download a folder or multiple objects at a time, you can run this code for the selected resources in the gcloud command line tool.


gcloud storage cp \
  "gs://usmedp-svcops-proddprocstg-piabrpt/data/NY_Medicaid/Ex_temp.xlsx" \
  "gs://usmedp-svcops-proddprocstg-piabrpt/data/NY_Medicaid/Exhibit_b_and_e.xlsx" \
  "gs://usmedp-svcops-proddprocstg-piabrpt/data/NY_Medicaid/NY_temp.xlsx" \
  "gs://usmedp-svcops-proddprocstg-piabrpt/data/NY_Medicaid/Newyork_medicaid_master.xlsx" \
  "gs://usmedp-svcops-proddprocstg-piabrpt/data/NY_Medicaid/apg-outpatient-rate-list.xlsx" \
  "gs://usmedp-svcops-proddprocstg-piabrpt/data/NY_Medicaid/exhibit-a-apg-base-rates-for-mhotrs-providers.xlsx" \
  "gs://usmedp-svcops-proddprocstg-piabrpt/data/NY_Medicaid/exhibit-b-mhotrs-apg-weight-schedule.xlsx" \
  "gs://usmedp-svcops-proddprocstg-piabrpt/data/NY_Medicaid/exhibit-c-non-apg-omh-outpatient-fee-schedule.xlsx" \
  "gs://usmedp-svcops-proddprocstg-piabrpt/data/NY_Medicaid/exhibit-d-non-apg-omh-provider-level-fee-schedule.xlsx" \
  "gs://usmedp-svcops-proddprocstg-piabrpt/data/NY_Medicaid/exhibit-e-mhotrs-apg-fee-schedule.xlsx" \
  "gs://usmedp-svcops-proddprocstg-piabrpt/data/NY_Medicaid/oasas-ambulatory-provider-level-fee-schedule-1.xlsx" \
  "gs://usmedp-svcops-proddprocstg-piabrpt/data/NY_Medicaid/oasas-outpatient-apg-fee-schedule.xlsx" \
  "gs://usmedp-svcops-proddprocstg-piabrpt/data/NY_Medicaid/sbmhc-program-site-list.xlsx" \
  .
