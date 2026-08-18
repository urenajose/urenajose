# JOSE URENA / PROJECT INDEX

`data systems` · `analytics` · `automation` · `disaster recovery`

Selected work across public-sector programs, nonprofit operations, and applied machine learning. Dates are included as compact context because several consulting engagements overlapped.

```text
FOCUS      operational data systems / reporting / automation
TOOLS      Python / SQL / Power BI / Excel / Google Workspace / Salesforce
DOMAINS    disaster recovery / public assistance / housing / education / nonprofit
```

---

## 01 / KITCHEN UNLEASHED — EXPENSE SYSTEM & FORM AUTOMATION

`2026` · `volunteer consulting` · `Google Sheets` · `Google Forms` · `Apps Script`

Built and documented a Google Workspace expense tracker workflow for an all-volunteer nonprofit. Connected a structured expense-reference table to a Google Form and wrote an event-driven Apps Script that keeps the form dropdown synchronized with active expense codes.

```text
DELIVERED   maintainable accounting workbook + automated intake workflow
AUTOMATED   active expense codes flow from Sheets to the Form dropdown
HARDENED    header-based column discovery, validation, logging, and fallback behavior
HANDED OFF  ownership transfer, trigger recreation, testing, troubleshooting, and SOP
IMPACT      $5,409 estimated value of donated professional services
```

[View the implementation and handoff guide](https://docs.google.com/document/d/16cUXXDbVP-c_fcMEcRkfFD5Pwbg__5N8pWT9eufXBDM/edit)

---

## 02 / GEORGIA HURRICANE HELENE NCS & DCM

`Nov 2024–Dec 2025` · `lead analyst / data administrator` · `FEMA DR-4830`

Designed and rapidly deployed Microsoft 365 data infrastructure supporting Georgia's temporary sheltering, temporary housing, and Disaster Case Management operations following Hurricane Helene. The systems served operations teams, project leadership, company executives, and GEMA leadership; selected reporting information was also used in briefings to the governor's team.

```text
SYSTEMS     SharePoint systems of record / Lists / Forms / Power Automate / Power BI
DATA        Smartsheet / Excel Online / CSV / PDF / SharePoint / VisionLink JSON
REPORTING   operational dashboards updated within approximately one hour via API calls
COMPLIANCE  weekly FEMA reports and expenditure reporting supporting reimbursement
DELIVERY    rapid, iterative development under federal-funding scrutiny
```

- Created and customized SharePoint Lists serving as systems of record for temporary sheltering and as an interim Disaster Case Management workflow supporting data transfer to VisionLink.
- Built the principal online applicant-intake form and its handoff to an eligibility-clearing process used to identify duplicate applications.
- Developed a reservation tracker for eligible families, including placement duration and cost-of-stay tracking for households whose participation sometimes extended beyond the original six-month program design.
- Created Power BI reporting for families, rooms, hotels, trailers, program utilization, and daily and weekly progress.
- Produced weekly Excel reports for FEMA; the reporting was a primary information source supporting Georgia's reimbursement of Temporary Housing Program expenditures.
- Integrated operational data from Smartsheet, Excel Online, CSV files, PDFs, SharePoint Lists, and VisionLink JSON extracts loaded through the SharePoint CLI.
- Trained users, documented the systems, administered permissions, and supported operational handoff.

### Trailer repair workflow

Built an internal work-order system with Microsoft Forms, Excel, Power Automate, email, and mobile-accessible technician forms.

```text
CALL CENTER  submits repair request
AUTOMATION   notifies the repair subcontractor
VENDOR       acknowledges the ticket and supplies a projected service time
DISPATCH     sends a text-style email notification to the technician pool
TECHNICIAN   records the resolution or required follow-up
```

Using the project's existing Microsoft environment reduced reliance on procuring and deploying separate system-of-record and work-order SaaS products. Because no formal cost comparison was performed, this is presented as cost avoidance through existing technology—not as a specific dollar saving.

```text
IMPACT      supported a $22M sheltering program serving 1,500 survivors across 113 hotels
SCALE       649+ families; direct temporary housing approved across 24 counties
FINANCIAL   reporting supported reimbursement of eligible Georgia expenditures
GOVERNANCE  permissions / documentation / training / validation / handoff
```

**Public program context:** [GEMA/HS announcement of the HEARTS Georgia temporary sheltering program](https://gema.georgia.gov/press-releases/2024-12-17/gemahs-launches-first-ever-temporary-sheltering-program-hurricane-helene) · [FEMA program context](https://www.fema.gov/press-release/20260610/fema-announces-additional-51-million-georgia)

The public pages establish the program's purpose and scale. My systems, reports, workflows, and underlying data were internal client deliverables and are not displayed or attributed on those pages.

---

## 03 / IOWA NON-CONGREGATE SHELTERING & DISASTER CASE MANAGEMENT

`Jul 2024–Jun 2025` · `lead analyst / data administrator` · `FEMA DR-4779 / DR-4784 / DR-4796`

Developed the operational data layer for temporary housing and recovery-plan case management, including protected household records, field reporting, and stakeholder dashboards.

```text
DELIVERED   case-management forms, system of record, dashboards, and on-demand BI
REPORTED    KPIs, FEMA-required outputs, incidents, and daily shelter updates
INTEGRATED  applicant, FEMA, FIDA, and internal program data
IMPACT      supported temporary housing for 222 households across 26 counties
```

---

## 04 / MAUI WILDFIRE RECOVERY

`Jan–Jun 2024` · `data analyst / data administrator` · `FEMA DR-4724`

Supported recovery operations following the Maui wildfires through custom systems for applicant unmet-needs tracking and case support.

```text
DELIVERED   protected-data databases, KPI reporting, and ad-hoc analysis
SUPPORTED   FEMA Public Assistance, mitigation, and CDBG-DR recovery workstreams
IMPACT      enabled program teams to track recovery activity across a major disaster area
CONTEXT     2,500+ structures exposed in Lahaina; roughly 2,100 acres affected
```

---

## 05 / MISSISSIPPI NON-CONGREGATE SHELTERING

`Sep 2023–Jan 2024` · `data analyst / data administrator` · `FEMA DR-4697-MS`

Built field and case-management tools for a FEMA-funded sheltering program serving disaster survivors transitioning toward permanent housing.

```text
DELIVERED   RecoveryTrac Flex forms, household case system, and operations databases
TRACKED     meal distribution, incidents, shelter updates, and program KPIs
REPORTED    custom BI products and ad-hoc analysis for client and project leadership
IMPACT      supported temporary housing operations for 59 households
```

---

## 06 / PUERTO RICO COMMUNITY ENERGY & WATER RESILIENCE

`Jul 2023–Mar 2024` · `data analyst` · `PRDOH CEWRI-HH`

Analyzed protected household and field data for a CDBG-DR program installing photovoltaic and battery-storage systems.

```text
DELIVERED   Survey123 analysis, custom reporting, KPI tracking, and field support
SUPPORTED   technical training and issue resolution for distributed field teams
IMPACT      improved operational visibility for household renewable-energy installations
```

---

## 07 / FLORIDA HURRICANE IAN RECOVERY PLANNING

`2023–2024` · `data analyst` · `Sarasota / Volusia / Fort Myers`

Supported three local governments preparing CDBG-DR and mitigation programs after Hurricane Ian. Converted federal, state, local, census, survey, and community-input data into decision-ready analysis.

```text
DELIVERED   ETL pipelines, repositories, dashboards, impact analysis, and public reporting
SOURCES     Census / ACS / FEMA / HUD / Florida DEM / county and city datasets
SUPPORTED   action plans, program startup, subject-matter experts, and grant analysis
IMPACT      contributed analytics supporting Sarasota County's $201M allocation
```

---

## 08 / IOWA SCHOOL SAFETY ASSESSMENTS

`Jul 2022–May 2023` · `data analyst / data administrator`

Developed contact, scheduling, field-collection, and reporting systems for a statewide school-safety assessment initiative funded through the American Rescue Plan Act.

```text
DELIVERED   program databases, SaaS field-support workflows, BI, and ad-hoc reporting
TRACKED     assessment scheduling and client-selected operational KPIs
IMPACT      supported assessments across 300+ districts and 1,500 school facilities
```

---

## 09 / IOWA CHILDCARE PROGRAMS

`2022–2023` · `data analyst / Salesforce administrator`

Supported two American Rescue Plan childcare initiatives: provider stabilization and workforce recruitment and retention.

```text
DELIVERED   Salesforce administration, API-enabled analysis, dashboards, and reports
TOOLS       Python / Power Query / Power BI / Microsoft Lists / Excel / Salesforce
REPORTED    financial, demographic, call-center, and KPI results to state and federal users
IMPACT      supported administration and reporting for $200M in stabilization funding
```

---

## 10 / EMERGENCY RENTAL ASSISTANCE

`2021–2022` · `data analyst` · `Pinellas & St. Petersburg / Charleston / Richland`

Managed and analyzed high-volume household, payment, and demographic data for federally funded rent and utility assistance programs.

```text
DELIVERED   API extraction, Python/Excel transformations, dashboards, and Treasury reports
TOOLS       Python / Power Query / Power BI / Excel / Apache Parquet
SCALE       thousands of households across three local programs
IMPACT      analytics supported $90.5M in combined program allocations
```

---

## 11 / SCRIBBLE STADIUM

`machine learning` · `computer vision` · `educational technology`

Contributed to an educational app that gamifies children's storytelling through physical handwriting, helping preserve creative play while minimizing screen time.

```text
DELIVERED   handwriting-recognition experiments and image-preprocessing pipeline
TRAINED     Tesseract OCR with a custom handwriting-style font for testing
IMPROVED    OCR inputs through OpenCV preprocessing and deskewing
EVALUATED   character error rate (CER) and fuzzy-match scores
STACK       Python / Tesseract OCR / OpenCV / Qt Box Editor / ASRToolKit / fuzzywuzzy
```

[View contributions](https://github.com/Lambda-School-Labs/story-squad-ds/commits?author=urenajose)

---

```text
NOTE  Client and survivor information is intentionally omitted. Program values describe
      the scale of the work supported; they are not presented as personally generated savings.
```

