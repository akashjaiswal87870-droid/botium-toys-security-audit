# Botium Toys Security Audit & Risk Assessment

## Project Overview
An internal cybersecurity audit of Botium Toys' security program to assess assets, controls, and adherence to compliance frameworks including NIST CSF, PCI DSS, GDPR, and SOC 1/SOC 2.

## Key Findings
* **Risk Score:** 8 / 10 (High)
* **Access Control:** Lack of least privilege and separation of duties; all employees have broad access to internal data.
* **Data Protection:** Credit card numbers and customer PII/SPII are processed and stored locally without encryption.
* **Continuity & Detection:** No disaster recovery plan, no data backups, and no Intrusion Detection System (IDS) deployed.

## Recommendations
* Implement Role-Based Access Control (RBAC) and least privilege principles.
* Deploy encryption mechanisms for data in transit and data at rest (PCI DSS requirement).
* Establish regular data backup procedures and a documented disaster recovery plan.
* Implement an IDS/IPS to detect anomalous traffic.
