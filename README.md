# 🏙️ CityTrace — Civic Issue Reporting & Resolution Verification

**Making civic complaints transparent, accountable, and verifiable.**

CityTrace is a civic-tech platform concept designed to help citizens report public infrastructure issues and verify whether reported problems have actually been resolved. By introducing evidence-based verification into the complaint lifecycle, CityTrace aims to bridge the trust gap between citizens and civic authorities.

🔗 **Live Demo:** [Explore CityTrace](https://comenater.github.io/CityTrace/)  

---

## 📌 The Problem

Citizens regularly encounter civic issues such as:

- 🛣️ Potholes and damaged roads
- 💡 Broken streetlights
- 🗑️ Improper garbage disposal
- 💧 Water leakage

Traditional complaint systems may mark an issue as *Resolved* without providing sufficient evidence that the problem has actually been fixed.

This creates three major challenges:

1. **Lack of verifiable proof:** A status update alone does not establish that the issue has been resolved.
2. **Unreliable evidence:** Submitted photographs may be outdated, incorrectly located, or unrelated to the reported issue.
3. **Limited citizen participation:** Citizens may have little opportunity to confirm or dispute the claimed resolution.

## 💡 Our Solution

CityTrace proposes an evidence-based resolution workflow that keeps citizens involved until the reported issue is verified.

Instead of moving directly from *Reported* to *Resolved*, the platform introduces an intermediate verification process.

### 🔄 Complaint Lifecycle

```text
Issue Reported
      ↓
Work Completed
      ↓
Proof Submitted
      ↓
Evidence Verification
      ↓
Citizen Confirmation
      ↓
Issue Resolved
```

If the citizen disputes the resolution, the case can return for further action rather than being treated as successfully closed.

### How It Works

1. **Report an Issue:** A citizen reports a civic problem with supporting information, including a photograph, location, and timestamp.
2. **Complete the Work:** The responsible department indicates that corrective work has been completed.
3. **Submit Evidence:** Before-and-after photographs provide evidence of the work performed.
4. **Verify the Evidence:** The proposed verification process checks factors such as timestamps, location consistency, and image differences.
5. **Confirm the Resolution:** The citizen gets an opportunity to confirm or dispute the outcome.
6. **Close or Reopen the Case:** A confirmed issue can be marked resolved, while a disputed case returns for further action.

## ✨ Key Features

- **Unique Complaint Tracking:** A distinct case ID for tracking each reported issue.
- **Location-Based Reporting:** Geotagging and timestamps help establish where and when an issue was reported.
- **Before-and-After Evidence:** Photographic evidence supports the assessment of completed work.
- **Evidence-Based Verification:** A proposed verification layer checks temporal, geographical, and visual consistency.
- **Citizen-in-the-Loop Resolution:** Citizens can confirm or dispute the reported outcome.
- **Department Accountability:** Resolution outcomes can inform department-level trust and performance indicators.

*CityTrace is currently a prototype/concept build. The features above describe the project's intended workflow and design; full operational functionality should not be assumed.*

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Webpage structure and content |
| CSS3 | Interface styling and visual layout |
| JavaScript | Client-side logic and interactive behaviour |

The current repository contains a single-page web implementation in `index.html`.

## 🚀 Getting Started

You can explore the deployed project or run the source locally.

### Option 1: View the Live Demo

Visit: [https://comenater.github.io/CityTrace/](https://comenater.github.io/CityTrace/)

### Option 2: Run Locally

**1. Clone the repository**

```bash
git clone https://github.com/comenater/CityTrace.git
```

**2. Navigate to the project directory**

```bash
cd CityTrace
```

**3. Open the webpage**

Open `index.html` in your preferred web browser.

Alternatively, open the folder in Visual Studio Code and use a local development server to preview the page.

No package installation is required for basic local viewing of the HTML page.

## 📂 Project Structure

```text
CityTrace/
│
├── index.html    # Main single-page web implementation
└── README.md     # Project documentation
```

## 🌍 Impact and Vision

CityTrace aims to make civic issue resolution more transparent and accountable by ensuring that a completed-work status is supported by evidence and meaningful citizen participation.

Potential benefits include:

- **Greater transparency:** Citizens can evaluate the evidence behind a resolution.
- **Improved accountability:** Departments have an incentive to provide credible proof of completed work.
- **Reduced false closures:** Verification and citizen feedback can help identify unresolved problems.
- **Better civic engagement:** Citizens become active participants in the resolution process.
- **Data-informed oversight:** Resolution and dispute patterns could help evaluate civic service performance.

These are intended benefits of the proposed platform, not measured outcomes from a live deployment.

## 🔮 Future Enhancements

Potential future development directions include:

- Implementing a complete complaint submission and tracking system.
- Integrating map services for visualising reported issues.
- Developing automated image comparison and evidence-validation modules.
- Adding citizen, department, and administrator dashboards.
- Introducing notifications and case-status updates.
- Developing analytics for complaint resolution and department performance.
- Connecting the platform to civic authority workflows and databases.

## 👥 Team

CityTrace was developed as a collaborative project by:

- Dakshita Koli
- Kkusumpreet Kaur
- Sneha Yadav
- Varnika Hooda

## 📌 Project Status

**Prototype / Concept Build**

CityTrace demonstrates a proposed approach to civic issue reporting and resolution verification. Further development would be required to establish a complete, production-ready platform.

## 📄 License

No formal open-source license is currently specified in the repository. Please check with the project maintainers before redistributing or reusing the source code.

---

**CityTrace — Because a complaint should not be considered resolved until the resolution can be verified.**
