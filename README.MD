ClinicalTrials (https://clinicaltrials.gov) is a registry and results database of publicly and privately supported research studies conducted in the United States and around the world. Sponsors or investigators of certain clinical trials are required by U.S. law to register their trials on and submit summary results to ClinicalTrials.gov. Users can freely find clinical trials of interest by using the Advanced Search. In this notebook, we will go through step by step to:

- Access the clinicaltrial database by webscraping **nct_ids** which match the search criteria. 
    - **nct_ids** (NCT ID) is a unique identification code given to each clinical study registered on ClinicalTrials.gov.
- Extract datasets from **AACT** database by using the **nct_ids** from above and generate the final output.

In the final output, we will have a database for people responsible for studies and show what clinical trials are associated with those people, corresponding **nct_ids**, number of trials, etc. 