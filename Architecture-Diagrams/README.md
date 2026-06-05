# MASIC Enterprise Architecture & System Specifications

This directory contains the core systems architecture blueprints, data workflow structures, and integration models analyzed during the fieldwork at **MASIC (Mohammed I. Alsubaie & Sons Investment Company)**. 

The models below represent MASIC's digital infrastructure transition from legacy manual processes to an optimized, audited enterprise environment based on findings from technical team consultations.

---

## 1. The Input-Process-Output (IPO) Model Diagram

This model illustrates how financial assets, real estate pipelines, and high-net-worth client data flow through MASIC’s core Information Systems, specifically capturing the functional parameters of their ERP system.

| Inputs (Data Deployed) | Core Processing (System Actions) | Outputs (Strategic Value) |
| :--- | :--- | :--- |
| • **Liquid & Private Equity Assets:** Daily stock market entries, investment portfolio balances.<br>• **Real Estate Portfolio:** Office spaces, commercial shops, leasing logs, and property details.<br>• **Stakeholder Records:** Historical data tracking 60+ years of institutional client relationships.<br>• **Financial Capital:** Bank account synchronizations, transaction inputs, and procurement invoices. | • **Automated Accounting & Reconciliation:** Processing high-volume transaction entries without manual oversight.<br>• **Asset Monitoring & Valuations:** Live tracking and calculation of liquid equity performance and asset changes.<br>• **Database Auditing & Fraud Mitigation:** Applying rigorous input validation protocols to ensure information security.<br>• **Process Optimization:** Reducing operational complexity and eliminating manual paper-driven silos. | • **Executive Business Intelligence:** Real-time dashboards summarizing investment yields and portfolio health.<br>• **Operational Property Reports:** Automated leasing updates and pipeline tracking for real estate management.<br>• **Audited Financial Statements:** Transparent, instantly generated reports for family offices and stakeholders.<br>• **Secured Client Ledgers:** Tamper-proof, centralized data tracking representing long-term strategic integrity. |

---

## 2. High-Level Enterprise Integration Architecture

The blueprint below displays the conceptual interconnectivity between MASIC’s core operational modules, showing how raw assets map directly into simplified executive Business Intelligence (BI) tools.

```text
       ┌────────────────────────────────────────────────────────┐
       │     High-Net-Worth Investors & Al-Subaie Family        │
       └───────────────────────────┬────────────────────────────┘
                                   │
                    (Strategic Capital & Asset Input)
                                   │
                                   ▼
       ┌────────────────────────────────────────────────────────┐
       │             MASIC Centralized Data Pipeline            │
       └───────────────────────────┬────────────────────────────┘
                                   │
         ┌─────────────────────────┴─────────────────────────┐
         ▼                                                   ▼
┌─────────────────────────────────┐                 ┌─────────────────────────────────┐
│     Microsoft Dynamics ERP      │                 │   Property & Asset Management   │
├─────────────────────────────────┤                 ├─────────────────────────────────┤
│ • Automated Financial Accounting│                 │ • Real Estate Pipeline Tracking │
│ • Procurement Module Integration│                 │ • Commercial Office Leasing Logs│
│ • System Auditing & Validation  │                 │ • Maintenance & Operational Data│
└────────────────┬────────────────┘                 └────────────────┬────────────────┘
                 │                                                   │
                 └─────────────────────────┬─────────────────────────┘
                                           │
                            (Clean & Aggregated Data Feed)
                                           │
                                           ▼
       ┌────────────────────────────────────────────────────────┐
       │          Business Intelligence (BI) Dashboard           │
       ├────────────────────────────────────────────────────────┤
       │ • High-Level Strategic Analytical Reporting            │
       │ • Simple, Accessible, and User-Friendly UI             │
       │ • Real-Time Investment and Portfolio Health Metrics    │
       └────────────────────────────────────────────────────────┘
