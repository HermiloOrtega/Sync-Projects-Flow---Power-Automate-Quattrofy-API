# 🔄 Sync Projects Flow – Power Automate + Quattrofy API

## 🧭 Overview
**Sync Projects Flow** is a Power Automate flow developed to orchestrate real-time data synchronization across critical internal systems at **Quattro Constructors**. The automation connects to the **Quattrofy API** and triggers a back-end process that keeps project data consistent between **Finance**, **Safety**, and **Operations** platforms—ensuring a single source of truth with no manual intervention.

---

## 💡 Idea & Concept
Multiple business units rely on accurate project data for decision-making, reporting, and compliance. Manually updating systems leads to errors, delays, and inefficiencies. This flow automates the sync process to:
- Retrieve the latest project data from external sources.
- Propagate updated financial data across all connected platforms.
- Send operational updates to the financial system.

This ensures **all departments work with the most current and aligned project data**.

---

## ✨ Features & Functionality
- **Scheduled Automation**: Triggers daily or hourly to check for updates.
- **HTTP Request**: Securely calls a Quattrofy API endpoint to execute the sync logic.
- **Cross-System Syncing**:
  - Pulls latest data from finance platform.
  - Pushes operational updates to financial systems.
  - Propagates master project data to all systems.
- **High-Fidelity Validation**:
  - Ensures no duplication or data corruption.
  - Only applies confirmed changes.

---

## ⚙️ Tech Stack

| Technology | Purpose |
|------------|---------|
| ![Power Automate](https://img.shields.io/badge/Power%20Automate-0089D6?logo=Microsoft%20Power%20Automate&logoColor=white&style=for-the-badge) | Orchestration of automation |
| ![HTTP](https://img.shields.io/badge/HTTP%20Request-000000?logo=http&logoColor=white&style=for-the-badge) | Calls Quattrofy Sync API securely |
| ![JSON](https://img.shields.io/badge/JSON-000000?logo=json&logoColor=white&style=for-the-badge) | Data format for API payload |
| ![Quattrofy](https://img.shields.io/badge/Quattrofy%20API-007ACC?style=for-the-badge) | Central API managing sync operations |
| ![Azure SQL](https://img.shields.io/badge/Azure%20SQL-0078D4?logo=microsoft-azure&logoColor=white&style=for-the-badge) | Stores project metadata |
| ![Microsoft Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?logo=microsoft-azure&logoColor=white&style=for-the-badge) | Hosting & integration platform |

---

## 🧑‍💻 My Role & Contributions
- Designed and implemented the entire flow logic in Power Automate
- Integrated with the Quattrofy API using secured HTTP actions and JSON payloads
- Validated multi-system dependencies and orchestrated reliable sync sequences
- Collaborated with business analysts to map data relationships between systems

---

## 📊 Results
- Reduced risk of data mismatch between departments
- Enabled real-time visibility into updated project data
- Improved reliability of reports generated from synced systems
- Saved hours of manual reconciliation and update effort per week

---

## 🔍 Related Projects
- [Quattrofy](#)
- [Quattrofy API](#)
- [Microsoft Flow PO Requests (AI)](#)
