# urban trends: revenue intelligence audit
**project code:** KL-CAP-001 | **lead consultant:** tanay

### overview
a high-impact data audit for urbantrends retail (uk). this project focused on engineering a sanitized revenue model from 1,000,000+ raw transaction logs, isolating systemic leakage from cancellations and pricing anomalies.

### tech stack
* **database:** postgresql
* **tooling:** vs code, pg_dump
* **analysis:** sql (window functions, rfm-proxy logic)

### key findings
* **net revenue:** $17.7M (post-sanitization)
* **revenue leakage:** $2.4M identified via cancelled orders and price errors
* **top market:** uk (domestic), with peak aov identified in international segments

### data access
due to github file size constraints, the raw transaction database is hosted externally.
* **raw dataset:** [google drive link](https://drive.google.com/drive/folders/1n1FUvNxnf5SGy2vG2ldh19n_HH7TjN7V?usp=sharing)
* **source:** [online retail ii (uci repository)](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II)
