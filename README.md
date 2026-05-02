# 📊 Data Analytics in Modern Corporate Business
### International Hellenic University — ΚΕΔΙΒΙΜ

---

## 🇬🇧 English

### About This Repository

This repository contains all coursework, assignments, datasets, notebooks, and projects completed as part of the **Data Analytics in Modern Corporate Business** continuing education program, offered by the **International Hellenic University (IHU) — Centre for Lifelong Learning (ΚΕΔΙΒΙΜ)**.

The program provides a rigorous, end-to-end introduction to the modern data analytics stack used in corporate environments — spanning relational databases, cloud data warehousing, ETL pipeline design, version control, and business intelligence visualization.

---

### 📁 Repository Structure

```
📦 data-analytics-ihu-kedivim
 ┣ 📂 datasets/              # Raw and processed datasets used in exercises
 ┣ 📂 notebooks/             # Python Jupyter Notebooks for ETL & analysis
 ┣ 📂 sql/                   # SQL queries, schemas, and database exercises
 ┣ 📂 assignments/           # Module assignments and submissions
 ┣ 📂 capstone-project/      # End-to-end capstone: pipeline, notebooks, dashboards
 ┣ 📂 resources/             # Course notes, references, and module summaries
 ┗ 📄 README.md
```

---

### 🛠️ Tools & Technologies

| Category | Tools |
|---|---|
| **Languages** | Python, SQL |
| **Databases** | PostgreSQL |
| **Cloud Data Warehouse** | Google BigQuery |
| **Data Streaming / CDC** | Google Datastream |
| **Authentication** | Google Cloud Service Account (JSON Key) |
| **ETL & Automation** | Python (Pandas, NumPy) |
| **Data Visualization** | Tableau Cloud, Metabase |
| **Version Control** | Git, GitHub |

---

### ☁️ Cloud Data Pipeline — Capstone Project

The capstone project simulates a real-world corporate data operations scenario and covers the full data analytics lifecycle — from raw transactional data to business-ready dashboards.

#### Pipeline Architecture

```
PostgreSQL (Source DB)
        │
        ▼
Google Datastream  ←── Change Data Capture (CDC)
        │
        ▼
Google BigQuery  ──→  Staging Schema  ──→  Reporting Schema
        │
        ▼
Python Notebooks  ──→  ETL Transformations & Automation
        │
        ▼
Tableau Cloud  +  Metabase  ──→  Interactive Dashboards
```

#### Key Implementation Steps

- **Google Cloud Service Account & JSON Key:** Configured a GCP Service Account with the appropriate IAM roles and generated a JSON authentication key to enable secure, programmatic access to the BigQuery and Datastream APIs — following the principle of least privilege.

- **Google Datastream (CDC Pipeline):** Designed and deployed a Change Data Capture (CDC) stream to continuously replicate transactional data from a PostgreSQL source database into BigQuery, ensuring near real-time data synchronization without manual exports.

- **BigQuery Data Warehouse:** Structured the warehouse into staging and reporting schemas. Raw replicated data lands in the staging layer and is subsequently transformed and loaded into the reporting layer, ready for analytical queries and visualization.

- **ETL with Python:** Developed Jupyter Notebooks handling additional extraction, transformation, and loading (ETL) tasks — including data cleaning, type casting, aggregation, and workflow automation on top of the BigQuery environment.

- **Version Control with Git:** Managed the entire codebase using Git, following standard branching and commit practices, with notebooks and configuration files tracked and published to GitHub.

- **BI Dashboards:** Created interactive, stakeholder-facing dashboards in both **Tableau Cloud** and **Metabase**, applying data visualization best practices to communicate actionable business insights effectively.

---

### 🎯 Learning Objectives

By completing this program, participants are able to:

- Apply the foundational steps of data analytics: collection, cleaning, analysis, interpretation, and visualization
- Write advanced SQL queries including Window Functions, CTEs, and JSON handling
- Design and manage cloud data warehouses using Google BigQuery
- Build end-to-end data pipelines with real-time replication via Google Datastream
- Perform ETL processes and automation using Python
- Use Git for version control and collaborative development on analytical projects
- Develop interactive dashboards in Tableau Cloud and Metabase for business decision-making
- Communicate data-driven insights to non-technical stakeholders through data storytelling

---

### 📐 Program Structure

| Module | Topic | Hours |
|---|---|---|
| 1 | Intro to Data Analytics & Data Roles | 5h |
| 2 | Databases & SQL | 15h |
| 3 | Git | 10h |
| 4 | Data Warehousing | 15h |
| 5 | Data Visualization | 15h |
| — | Capstone Project | 50h |
| **Total** | | **110h** |

---

### 🏛️ Institution

| | |
|---|---|
| **University** | International Hellenic University (IHU) |
| **Program Provider** | ΚΕΔΙΒΙΜ — Centre for Lifelong Learning |
| **Program Title** | Data Analytics in Modern Corporate Business |
| **Credits** | 3.5 ECTS |
| **Duration** | 110 hours / 3 months |
| **Mode** | Asynchronous distance learning |
| **Location** | Thessaloniki, Greece |
| **IHU Website** | [www.ihu.gr](https://www.ihu.gr) |
| **ΚΕΔΙΒΙΜ Website** | [kedivim.ihu.gr](https://kedivim.ihu.gr) |
| **Program Page** | [Data Analytics in Modern Corporate Business — 2026](https://kedivim-apply.ihu.gr/progs/prog-428) |

---

### 📌 Notes

All content in this repository was developed for **educational purposes** as part of the IHU ΚΕΔΙΒΙΜ program. Datasets used are either publicly available or provided by the program instructors. Credentials and sensitive configuration files (e.g., service account JSON keys) are excluded from version control via `.gitignore`.

---
---

## 🇬🇷 Ελληνικά

### Σχετικά με το Αποθετήριο

Αυτό το αποθετήριο περιέχει όλες τις εργασίες, ασκήσεις, σύνολα δεδομένων, notebooks και projects που εκπονήθηκαν στο πλαίσιο του προγράμματος επαγγελματικής κατάρτισης **«Data Analytics in Modern Corporate Business»**, το οποίο προσφέρεται από το **Διεθνές Πανεπιστήμιο της Ελλάδος (ΔΙ.ΠΑ.Ε.) — Κέντρο Επιμόρφωσης και Διά Βίου Μάθησης (ΚΕΔΙΒΙΜ)**.

Το πρόγραμμα παρέχει ολοκληρωμένη εισαγωγή στο σύγχρονο data analytics stack που χρησιμοποιείται σε εταιρικά περιβάλλοντα — καλύπτοντας σχεσιακές βάσεις δεδομένων, αποθήκευση δεδομένων στο cloud, σχεδιασμό ETL pipelines, έλεγχο εκδόσεων και οπτικοποίηση επιχειρηματικής νοημοσύνης.

---

### 📁 Δομή Αποθετηρίου

```
📦 data-analytics-ihu-kedivim
 ┣ 📂 datasets/              # Αρχικά και επεξεργασμένα σύνολα δεδομένων
 ┣ 📂 notebooks/             # Python Jupyter Notebooks για ETL & ανάλυση
 ┣ 📂 sql/                   # SQL ερωτήματα, σχήματα και ασκήσεις βάσεων δεδομένων
 ┣ 📂 assignments/           # Εργασίες ανά ενότητα
 ┣ 📂 capstone-project/      # Ολοκληρωμένο capstone: pipeline, notebooks, dashboards
 ┣ 📂 resources/             # Σημειώσεις, αναφορές και περιλήψεις ενοτήτων
 ┗ 📄 README.md
```

---

### 🛠️ Εργαλεία & Τεχνολογίες

| Κατηγορία | Εργαλεία |
|---|---|
| **Γλώσσες Προγραμματισμού** | Python, SQL |
| **Βάσεις Δεδομένων** | PostgreSQL |
| **Αποθήκη Δεδομένων Cloud** | Google BigQuery |
| **Data Streaming / CDC** | Google Datastream |
| **Αυθεντικοποίηση** | Google Cloud Service Account (JSON Key) |
| **ETL & Αυτοματισμός** | Python (Pandas, NumPy) |
| **Οπτικοποίηση Δεδομένων** | Tableau Cloud, Metabase |
| **Έλεγχος Εκδόσεων** | Git, GitHub |

---

### ☁️ Cloud Data Pipeline — Capstone Project

Το capstone project προσομοιώνει ένα πραγματικό εταιρικό σενάριο διαχείρισης δεδομένων και καλύπτει τον πλήρη κύκλο ζωής της ανάλυσης δεδομένων — από τα ακατέργαστα συναλλακτικά δεδομένα έως τα έτοιμα για λήψη αποφάσεων dashboards.

#### Αρχιτεκτονική Pipeline

```
PostgreSQL (Πηγή Δεδομένων)
        │
        ▼
Google Datastream  ←── Change Data Capture (CDC)
        │
        ▼
Google BigQuery  ──→  Staging Schema  ──→  Reporting Schema
        │
        ▼
Python Notebooks  ──→  ETL Μετασχηματισμοί & Αυτοματισμός
        │
        ▼
Tableau Cloud  +  Metabase  ──→  Διαδραστικά Dashboards
```

#### Βασικά Βήματα Υλοποίησης

- **Google Cloud Service Account & JSON Key:** Διαμορφώθηκε Service Account στο GCP με τους κατάλληλους ρόλους IAM και δημιουργήθηκε κλειδί JSON για ασφαλή, προγραμματική πρόσβαση στα APIs του BigQuery και του Datastream — με τήρηση της αρχής του ελάχιστου προνομίου (principle of least privilege).

- **Google Datastream (CDC Pipeline):** Σχεδιάστηκε και αναπτύχθηκε ροή Change Data Capture (CDC) για συνεχή αντιγραφή συναλλακτικών δεδομένων από βάση PostgreSQL στο BigQuery, εξασφαλίζοντας συγχρονισμό δεδομένων σε σχεδόν πραγματικό χρόνο χωρίς χειροκίνητες εξαγωγές.

- **BigQuery Data Warehouse:** Οργανώθηκε η αποθήκη δεδομένων σε staging και reporting schemas. Τα ακατέργαστα δεδομένα φορτώνονται στο staging layer και μετασχηματίζονται στο reporting layer, έτοιμα για αναλυτικά ερωτήματα και οπτικοποίηση.

- **ETL με Python:** Αναπτύχθηκαν Jupyter Notebooks για πρόσθετες εργασίες εξαγωγής, μετασχηματισμού και φόρτωσης (ETL) — συμπεριλαμβανομένων καθαρισμού δεδομένων, μετατροπής τύπων, συγκεντρώσεων και αυτοματισμού ροής εργασιών.

- **Έλεγχος Εκδόσεων με Git:** Διαχείριση του συνόλου του κώδικα με Git, με notebooks και αρχεία διαμόρφωσης ανεβασμένα στο GitHub.

- **BI Dashboards:** Δημιουργία διαδραστικών dashboards σε **Tableau Cloud** και **Metabase**, με εφαρμογή βέλτιστων πρακτικών οπτικοποίησης για αποτελεσματική μεταφορά επιχειρηματικών insights στους stakeholders.

---

### 🎯 Μαθησιακοί Στόχοι

Με την ολοκλήρωση του προγράμματος, οι συμμετέχοντες είναι σε θέση να:

- Εφαρμόζουν τα βασικά βήματα της ανάλυσης δεδομένων: συλλογή, καθαρισμός, ανάλυση, ερμηνεία και οπτικοποίηση
- Συντάσσουν προχωρημένα SQL ερωτήματα, συμπεριλαμβανομένων Window Functions, CTEs και JSON χειρισμού
- Σχεδιάζουν και διαχειρίζονται αποθήκες δεδομένων cloud με χρήση Google BigQuery
- Δημιουργούν end-to-end data pipelines με real-time αντιγραφή μέσω Google Datastream
- Εκτελούν διαδικασίες ETL και αυτοματισμού με Python
- Χρησιμοποιούν Git για έλεγχο εκδόσεων και συνεργατική ανάπτυξη αναλυτικών projects
- Αναπτύσσουν διαδραστικά dashboards σε Tableau Cloud και Metabase για επιχειρηματική λήψη αποφάσεων
- Επικοινωνούν συμπεράσματα βάσει δεδομένων σε μη τεχνικούς stakeholders μέσω data storytelling

---

### 📐 Δομή Προγράμματος

| Ενότητα | Θέμα | Ώρες |
|---|---|---|
| 1 | Εισαγωγή στην Ανάλυση Δεδομένων & Ρόλοι | 5ω |
| 2 | Βάσεις Δεδομένων & SQL | 15ω |
| 3 | Git | 10ω |
| 4 | Data Warehousing | 15ω |
| 5 | Οπτικοποίηση Δεδομένων | 15ω |
| — | Capstone Project | 50ω |
| **Σύνολο** | | **110ω** |

---

### 🏛️ Εκπαιδευτικό Ίδρυμα

| | |
|---|---|
| **Πανεπιστήμιο** | Διεθνές Πανεπιστήμιο της Ελλάδος (ΔΙ.ΠΑ.Ε.) |
| **Φορέας Προγράμματος** | ΚΕΔΙΒΙΜ — Κέντρο Επιμόρφωσης & Διά Βίου Μάθησης |
| **Τίτλος Προγράμματος** | Data Analytics in Modern Corporate Business |
| **Πιστωτικές Μονάδες** | 3,5 ECTS |
| **Διάρκεια** | 110 ώρες / 3 μήνες |
| **Τρόπος Διεξαγωγής** | Ασύγχρονη εξ αποστάσεως εκπαίδευση |
| **Τοποθεσία** | Θεσσαλονίκη, Ελλάδα |
| **Ιστότοπος ΔΙ.ΠΑ.Ε.** | [www.ihu.gr](https://www.ihu.gr) |
| **Ιστότοπος ΚΕΔΙΒΙΜ** | [kedivim.ihu.gr](https://kedivim.ihu.gr) |
| **Σελίδα Προγράμματος** | [Data Analytics in Modern Corporate Business — 2026](https://kedivim-apply.ihu.gr/progs/prog-428) |

---

### 📌 Σημειώσεις

Όλο το περιεχόμενο αυτού του αποθετηρίου δημιουργήθηκε για **εκπαιδευτικούς σκοπούς** στο πλαίσιο του προγράμματος ΚΕΔΙΒΙΜ του ΔΙ.ΠΑ.Ε. Τα σύνολα δεδομένων που χρησιμοποιούνται είναι είτε διαθέσιμα στο κοινό είτε παρέχονται από τους διδάσκοντες. Διαπιστευτήρια και ευαίσθητα αρχεία διαμόρφωσης (π.χ. κλειδιά JSON service account) εξαιρούνται από τον έλεγχο εκδόσεων μέσω `.gitignore`.

---

*Last updated: May 2026*
