# 💧 AQUACORE Management Information System (MIS)
> **Comprehensive Enterprise Water Utility Management Information System**  
> **Official Demo & Production URL:** [https://thiwasco-5.onrender.com/](https://thiwasco-5.onrender.com/)  
> **GitHub Repository:** [https://github.com/Debest01-gif/AQUACORE-SYSTEM](https://github.com/Debest01-gif/AQUACORE-SYSTEM) *(or `THIWASCO`)*  
> **Target Audience:** Managing Director, Board of Directors, Utility Managers & Technical Teams  

---

## 🔐 Default Access Credentials
* **Login URL:** `/login.php`
* **Username:** `admin`
* **Password:** `password` *(or `Admin@2026`)*
* **Role:** System Administrator (Full Enterprise Access)

---

## 📸 Complete System Walkthrough with Screenshots & Descriptions

All high-resolution screenshot images are stored in the [`screenshots/`](./screenshots/) directory for easy offline viewing, printing, and download.

---

### Part 1: Secure System Access & Authentication

#### 1.1 Secure Login Portal
![AQUACORE Secure Login Portal](./screenshots/01_login_portal.png)
* **Description:** The enterprise security portal provides encrypted single-sign-on access for utility employees. It features brute-force lockout safeguards (locking accounts after 5 failed attempts for 30 minutes), password visibility toggles, session token generation, corporate identity branding, and institutional regulatory indicators (WASREB compliance).

---

### Part 2: Executive Command & Decision Intelligence

#### 2.1 C-Suite Executive Command Dashboard
![C-Suite Executive Dashboard](./screenshots/02_executive_dashboard.png)
* **Description:** Designed for the Managing Director and Executive Board, this real-time command dashboard synthesizes utility-wide operations into vital KPI cards: Total Active Customers (12 active of 15 registered), Monthly Collections (KES 15,531.00), Outstanding Arrears (KES 342,350.00 across 13 accounts), In-Service Meters (15 units), and Current Non-Revenue Water (NRW: 34.1% against the $\le 20\%$ WASREB target). It features quick-action shortcuts for rapid field dispatch and revenue protection.

---

### Part 3: Customer Lifecycle Management (CRM)

#### 3.1 Master Customer Registry
![Master Customer Registry](./screenshots/03_customer_registry.png)
* **Description:** The central customer database tracks all residential, commercial, industrial, and institutional accounts. It allows instant multi-filter searches by account number, name, phone, zone, and tariff class. Interactive badges show customer connection states (Active, Disconnected, Defaulter) with one-click actions to view customer dossiers, edit profiles, or review billing ledgers.

#### 3.2 Customer 360° Profile & Account Dossier
![Customer 360 Profile](./screenshots/04_customer_profile_detail.png)
* **Description:** Comprehensive customer profile displaying all personal data, national ID, mobile contact, street/plot address, and exact GPS coordinates. The integrated tabs display meter details, monthly consumption records, invoice histories, payment receipts, and any revenue protection inspections.

#### 3.3 New Customer Connection Onboarding Wizard
![New Customer Onboarding Wizard](./screenshots/05_customer_add_wizard.png)
* **Description:** Digital onboarding wizard capturing customer KYC data, plot number, pipe connection size (½", ¾", 1", 2"), supply zone assignment, tariff category, and initial security deposit verification. Geolocation tagging ensures every connection is mapped directly to the utility's network GIS.

#### 3.4 Defaulters & Aged Debt Recovery Portfolio
![Defaulters & Aged Debt Portfolio](./screenshots/06_defaulters_debt_management.png)
* **Description:** Automated debt recovery tracking identifying accounts that have exceeded their 30-day grace period. It aggregates total default balances (KES 342,350.00) and enables debt collection teams to generate statutory disconnection warnings and dispatch field cut-off teams.

#### 3.5 Disconnected Connections Registry
![Disconnected Connections Registry](./screenshots/07_disconnected_customers.png)
* **Description:** Dedicated ledger of all physically disconnected water service connections. It tracks meter lock numbers, disconnection dates, outstanding balances, and mandatory reconnection penalty fees, ensuring unauthorized reconnections are prevented.

---

### Part 4: Meter Management & Consumption Intelligence

#### 4.1 Master Meter Asset Registry
![Master Meter Asset Registry](./screenshots/08_meter_registry.png)
* **Description:** Complete physical meter inventory tracking serial numbers, meter make/model, physical size, calibration dates, tamper-proof seal numbers, and current health status (Active, Replaced, Faulty, Disconnected).

#### 4.2 Meter Reading & Consumption Capture Log
![Meter Reading & Consumption Log](./screenshots/09_meter_readings_consumption.png)
* **Description:** Records monthly field readings. The engine automatically calculates consumed volume: $\text{Current Reading} - \text{Previous Reading} = m^3$. It captures meter reader attribution, timestamps, dial photo evidence, and detects abnormal variances.

#### 4.3 Bulk Supply & District Metered Area (DMA) Meters
![Bulk & DMA Meters](./screenshots/10_bulk_dma_meters.png)
* **Description:** Manages master bulk meters installed at treatment works, storage reservoirs, and DMA intake points. It compares total water supplied into a sector against consumer meter totals to locate localized distribution losses.

#### 4.4 Meter Anomalies, Tampering & Outlier Detection
![Meter Anomalies & Outliers](./screenshots/11_meter_anomalies_tampering.png)
* **Description:** Automated audit screen flagging suspicious reading patterns: zero consumption on active commercial premises, negative meter indexing, broken seals, or sudden 300%+ consumption surges before bills are generated.

---

### Part 5: Automated Billing, Tariffs & Revenue Collection

#### 5.1 Billing Operations & Invoice Management
![Billing Operations Dashboard](./screenshots/12_billing_invoices_dashboard.png)
* **Description:** Monthly billing cycle control centre. It tracks invoiced amounts, payment states (Paid, Partial, Unpaid), invoice numbers, and due dates, providing a complete monthly cash flow overview.

#### 5.2 Automated Batch Bill Generation Engine
![Batch Bill Generation Engine](./screenshots/13_batch_bill_generation.png)
* **Description:** Powerful batch billing engine that calculates thousands of customer invoices in seconds. It applies tiered tariff rates, base facility charges, sewerage levies (60%), and rolls forward previous unpaid arrears with duplicate-billing safeguards.

#### 5.3 Tiered Tariff Structure Configuration (WASREB Compliant)
![Water Tariff Configuration](./screenshots/14_water_tariffs_configuration.png)
* **Description:** Configuration interface for gazetted WASREB tariff structures across Domestic (0–6 $m^3$ @ KES 52, 7–20 $m^3$ @ KES 62, 21–50 $m^3$ @ KES 75, >50 $m^3$ @ KES 95), Commercial, Industrial, Institutional, and Water Kiosks.

#### 5.4 Official Water Invoice & Printable Bill Statement
![Official Water Bill Statement](./screenshots/15_invoice_printable_view.png)
* **Description:** Professional, itemized printable water bill provided to consumers. It details previous/current meter readings, consumed volume ($m^3$), graduated water consumption charge, sewerage fee, fixed meter rent, arrears, total payable, and M-Pesa Paybill payment instructions.

#### 5.5 Payment Processing & Live Revenue Ledger
![Payment Processing Ledger](./screenshots/16_payment_processing_ledger.png)
* **Description:** Real-time financial ledger capturing all incoming customer settlements. Displays Receipt Number, Account Number, Payer Name, Payment Method, Reference Code, and processing Cashier with automatic balance updating.

#### 5.6 Multi-Channel Payment Receipting
![Record Payment Form](./screenshots/17_record_new_payment.png)
* **Description:** Counter receipting interface for cashiers to log payments via Cash, M-Pesa, Bank Transfer, Cheque, Debit Card, or RTGS with instant receipt generation.

#### 5.7 Live M-Pesa Paybill (888300) Integration Hub
![M-Pesa Paybill Integration Hub](./screenshots/18_mpesa_paybill_integration.png)
* **Description:** Automated mobile money hub monitoring Paybill `888300`. It reconciles incoming C2B transactions against customer account numbers in real time, eliminating physical bank queues and manual entry.

---

### Part 6: Non-Revenue Water (NRW) & Water Loss Mitigation

#### 6.1 Non-Revenue Water (NRW) Command Dashboard
![NRW Command Dashboard](./screenshots/19_non_revenue_water_dashboard.png)
* **Description:** Strategic water conservation dashboard tracking total system losses. Differentiates physical leakage (burst mains, storage leaks) from commercial losses (unmetered theft, faulty meters).

#### 6.2 Water Production & Intake Logging
![Water Production & Intake Logging](./screenshots/20_water_production_intake.png)
* **Description:** Daily abstraction logs from rivers, dams, and treatment plants. Tracks total volume produced ($m^3$), pump running hours, and electrical energy consumption ($kWh/m^3$) to monitor production cost efficiency.

#### 6.3 Commercial vs. Physical Loss Analytics
![NRW Loss Analysis](./screenshots/21_nrw_loss_analysis.png)
* **Description:** Zonal loss analytics ranking distribution areas by water loss severity. Directs engineering teams and leak detection crews to high-loss zones to maximize water recovery.

#### 6.4 IWA Standard Water Balance Matrix
![IWA Standard Water Balance Matrix](./screenshots/22_iwa_water_balance_matrix.png)
* **Description:** Global International Water Association (IWA) standardized water audit matrix: System Input Volume (SIV) = Authorised Consumption + Water Losses. Computes Revenue Water vs Non-Revenue Water for statutory reporting to WASREB and development financiers.

---

### Part 7: Revenue Protection & Anti-Fraud Enforcement

#### 7.1 Field Inspection Cases & Surveillance Registry
![Field Inspections Registry](./screenshots/23_field_inspections_registry.png)
* **Description:** Surveillance tracking system for illegal connections, meter bypasses, and unauthorized abstractions. Currently tracks active cases with **KES 95,000.00** in assessed statutory penalties.

#### 7.2 Illegal Connections, Bypasses & Fraud Investigations
![Illegal Connections Audit](./screenshots/24_illegal_connections_audit.png)
* **Description:** Investigates tampering methods including unmetered tappings, reversed meters, broken utility seals, and illegal reconnections. Converts stolen water volumes into recoverable penalty charges.

#### 7.3 Disconnection Orders & Field Enforcement Dispatch
![Disconnections & Field Enforcement](./screenshots/25_disconnections_enforcement.png)
* **Description:** Generates and dispatches field disconnection job cards. Tracks execution status, meter locking, and line capping until arrears and penalty fees are settled.

#### 7.4 Field Inspection Case Dossier & Photographic Evidence
![Field Inspection Case Dossier](./screenshots/26_field_inspection_case_detail.png)
* **Description:** Legal evidence dossier containing inspector findings, GPS coordinates, photographic proof of tampering, and statutory penalty invoicing controls.

---

### Part 8: Strategic Executive Reporting & Business Intelligence

#### 8.1 Executive Management Summary Report
![Executive Management Summary Report](./screenshots/27_executive_summary_report.png)
* **Description:** Board-ready annual performance briefing for the Managing Director. Summarizes Annual Water Billing (KES 39,370.00), Collections (KES 20,195.40), Collection Efficiency (51.3%), and Zonal Revenue Contribution rankings.

#### 8.2 Revenue & Collections Efficiency Report
![Revenue & Collections Report](./screenshots/28_revenue_collections_report.png)
* **Description:** Monthly collection efficiency trends comparing billed vs collected revenue across payment channels.

#### 8.3 Non-Revenue Water (NRW) Audit Report
![NRW Audit Report](./screenshots/29_nrw_audit_report.png)
* **Description:** Audit report monitoring compliance with national water loss benchmarks and calculating the financial value of unbilled water.

#### 8.4 Billing & Consumption Category Report
![Billing & Consumption Report](./screenshots/30_billing_consumption_report.png)
* **Description:** Analyzes consumption volume across customer classes to guide tariff restructuring and water demand management.

#### 8.5 Aged Debtors & Defaulters Portfolio
![Aged Debtors & Defaulters Report](./screenshots/31_aged_debt_defaulters_report.png)
* **Description:** Aging debt schedule (Current, 30–60, 61–90, Over 90 Days) showing total debt exposure (KES 342,350.00) to focus credit control efforts.

---

### Part 9: System Governance & Administration

#### 9.1 Role-Based Access Control (RBAC) & Staff Accounts
![User Management & Roles](./screenshots/32_user_management_roles.png)
* **Description:** Enforces strict role segregation across Super Admin, Admin, Meter Reader, Cashier, Supervisor, Revenue Officer, and Accounts roles.

#### 9.2 Enterprise System Settings & Operational Parameters
![System Settings Configuration](./screenshots/33_system_settings_configuration.png)
* **Description:** Central configuration for utility parameters: Legal Company Name, Official Addresses, Invoice/Receipt prefixes, Penalty rates (5%), Grace period (30 days), Paybill (`888300`), and modular toggles.

---

### Part 10: Integrated Enterprise Modules (ERP Extensions)

#### 10.1 Stores & Materials Inventory Management
![Stores & Inventory Management](./screenshots/34_stores_inventory_management.png)
* **Description:** Tracks engineering hardware (meters, PVC/HDPE pipes, gate valves, repair saddles, water treatment chemicals) with reorder alerts.

#### 10.2 Central Stock Movement Ledger
![Central Stock Movement Ledger](./screenshots/35_stores_stock_ledger.png)
* **Description:** Complete audit trail of stock receipts, dispatches, and adjustments linked directly to maintenance work orders.

#### 10.3 Water Infrastructure Asset & Plant Maintenance
![Assets & Infrastructure Maintenance](./screenshots/36_assets_infrastructure_maintenance.png)
* **Description:** Fixed asset register for high-lift pumps, storage reservoirs, intake stations, and dosing pumps with maintenance service histories.

#### 10.4 Procurement, Suppliers & Purchase Orders (LPO)
![Procurement & Purchase Orders](./screenshots/37_procurement_purchase_orders.png)
* **Description:** Supplier management and Local Purchase Order (LPO) tracking to ensure transparent public procurement.

#### 10.5 Capital Works & Water Infrastructure Projects Portfolio
![Water Infrastructure Projects](./screenshots/38_water_infrastructure_projects.png)
* **Description:** Tracks capital expansion projects (pipeline network extensions, borehole drilling, storage tank construction) with budget vs actual spend tracking and contractor completion percentages.

---

## 📥 How to Download All Screenshots

All 38 screenshots are stored in the root [`screenshots/`](./screenshots/) folder.
* **Via Git Clone:**
  ```bash
  git clone https://github.com/Debest01-gif/AQUACORE-SYSTEM.git
  # All images are immediately accessible in /screenshots/
  ```
* **Via ZIP / Direct Download:**
  Navigate to the `/screenshots/` directory on GitHub and download any image directly.

---

## 🌐 Cloud Hosting on Render

This application includes a production-ready `Dockerfile` and `render.yaml` for instant cloud deployment:

```yaml
services:
  - type: web
    name: aquacore-mis
    env: docker
    plan: free
    region: oregon
    dockerfilePath: Dockerfile
    envVars:
      - key: APP_NAME
        value: "AQUACORE MIS"
      - key: DB_CONNECTION
        value: "sqlite"
      - key: APP_TIMEZONE
        value: "Africa/Nairobi"
```

The container automatically initializes the database schema, seeds sample operational data, configures permissions, and launches Apache on the cloud-assigned port.
