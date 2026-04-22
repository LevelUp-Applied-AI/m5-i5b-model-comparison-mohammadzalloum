# Error Analysis

- **Threshold used:** 0.50
- **Total test samples:** 900
- **False positives:** 16
- **False negatives:** 123

## Highest-Confidence False Positives

- **sample_idx=3799** | proba=0.7647 | tenure=0, monthly_charges=72.61, total_charges=20.41, num_support_calls=5, senior_citizen=0, has_partner=1, has_dependents=1, contract_months=1
- **sample_idx=2837** | proba=0.7301 | tenure=7, monthly_charges=112.79, total_charges=1075.34, num_support_calls=2, senior_citizen=0, has_partner=1, has_dependents=0, contract_months=1
- **sample_idx=2850** | proba=0.6717 | tenure=8, monthly_charges=46.19, total_charges=22.29, num_support_calls=4, senior_citizen=0, has_partner=1, has_dependents=0, contract_months=1
- **sample_idx=2428** | proba=0.6251 | tenure=5, monthly_charges=81.85, total_charges=160.51, num_support_calls=4, senior_citizen=0, has_partner=1, has_dependents=0, contract_months=12
- **sample_idx=4372** | proba=0.6186 | tenure=8, monthly_charges=86.23, total_charges=368.77, num_support_calls=5, senior_citizen=0, has_partner=1, has_dependents=0, contract_months=12
- **sample_idx=4060** | proba=0.5998 | tenure=36, monthly_charges=20.0, total_charges=1077.33, num_support_calls=2, senior_citizen=0, has_partner=0, has_dependents=0, contract_months=1
- **sample_idx=1566** | proba=0.5887 | tenure=28, monthly_charges=20.0, total_charges=1485.27, num_support_calls=3, senior_citizen=0, has_partner=1, has_dependents=1, contract_months=1
- **sample_idx=3700** | proba=0.5707 | tenure=2, monthly_charges=32.06, total_charges=0.0, num_support_calls=4, senior_citizen=0, has_partner=0, has_dependents=1, contract_months=1
- **sample_idx=1823** | proba=0.5690 | tenure=72, monthly_charges=68.93, total_charges=0.0, num_support_calls=4, senior_citizen=0, has_partner=0, has_dependents=0, contract_months=1
- **sample_idx=1007** | proba=0.5533 | tenure=3, monthly_charges=34.9, total_charges=124.05, num_support_calls=4, senior_citizen=0, has_partner=0, has_dependents=0, contract_months=1

## Lowest-Confidence False Negatives

- **sample_idx=3633** | proba=0.0234 | tenure=22, monthly_charges=97.44, total_charges=3480.51, num_support_calls=1, senior_citizen=1, has_partner=1, has_dependents=0, contract_months=12
- **sample_idx=202** | proba=0.0280 | tenure=59, monthly_charges=53.3, total_charges=1823.88, num_support_calls=1, senior_citizen=0, has_partner=0, has_dependents=0, contract_months=1
- **sample_idx=3087** | proba=0.0280 | tenure=60, monthly_charges=91.51, total_charges=10053.55, num_support_calls=1, senior_citizen=0, has_partner=0, has_dependents=1, contract_months=1
- **sample_idx=1414** | proba=0.0475 | tenure=20, monthly_charges=94.32, total_charges=2914.1, num_support_calls=2, senior_citizen=0, has_partner=0, has_dependents=0, contract_months=12
- **sample_idx=3735** | proba=0.0570 | tenure=15, monthly_charges=32.46, total_charges=660.61, num_support_calls=1, senior_citizen=0, has_partner=1, has_dependents=1, contract_months=1
- **sample_idx=1391** | proba=0.0601 | tenure=9, monthly_charges=52.13, total_charges=317.54, num_support_calls=0, senior_citizen=0, has_partner=0, has_dependents=0, contract_months=1
- **sample_idx=1803** | proba=0.0610 | tenure=13, monthly_charges=47.0, total_charges=209.26, num_support_calls=1, senior_citizen=0, has_partner=1, has_dependents=0, contract_months=1
- **sample_idx=2332** | proba=0.0639 | tenure=6, monthly_charges=67.19, total_charges=371.08, num_support_calls=0, senior_citizen=0, has_partner=0, has_dependents=0, contract_months=1
- **sample_idx=296** | proba=0.0755 | tenure=17, monthly_charges=76.87, total_charges=1844.94, num_support_calls=1, senior_citizen=1, has_partner=0, has_dependents=0, contract_months=1
- **sample_idx=2617** | proba=0.0871 | tenure=1, monthly_charges=63.97, total_charges=57.75, num_support_calls=0, senior_citizen=0, has_partner=1, has_dependents=1, contract_months=24