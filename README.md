# Sigstore Audit Mapping: ISO 27001:2022 to NIST CSF 2.0

**Audit Scope & Methodology:** This mapping artifact translates specific security non-conformities (NCRs) identified during an ISO/IEC 27001:2022 assessment of the Sigstore ecosystem into the NIST Cybersecurity Framework (CSF) 2.0. The evaluation assesses how upstream governance and policy gaps directly impact active defensive capabilities, incident response, and continuous monitoring.

📄 **Full Mapping Document**

👉 [Click here to view or download the complete Mapping Assessment (Excel)](./Sigstore_NIST_CSF2_Mapping.xlsx)

📌 **Executive Summary**

* **Target System:** Sigstore Ecosystem (Fulcio, Rekor, Cosign)
* **Base Standard:** ISO/IEC 27001:2022
* **Target Framework:** NIST CSF 2.0
* **Mapping Objective:** Contextualize compliance findings into operational risk tiers (1–4).
* **Key Focus:** Translating 6 Minor Non-Conformities into specific NIST functions (Govern, Identify, Protect, Detect, Respond), highlighting the real-world operational risk introduced by informal procedures.

🛠️ **Key Technical Focus Areas**

* **Incident Response Routing (RS.CO):** Analyzing the absence of established escalation pathways for engaging external authorities during active response execution.
* **Proactive Threat Intelligence (ID.RA):** Mapping the operational impact of relying solely on reactive CVE disclosures rather than active adversary TTP monitoring.
* **Infrastructure Resilience Assurance (PR.IR):** Evaluating the gap between architectural resilience capabilities and the lack of validated, documented disruption testing under adverse conditions.
