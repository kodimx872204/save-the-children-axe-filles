# save-the-children-axe-filles
📌 Project Overview
A sophisticated monitoring and evaluation (M&E) dashboard developed for Save the Children's "AXE-Filles" program in the Kasaï province, DRC. The system centralizes data from 9 educational sub-divisions to provide real-time analysis of school enrollment, program participation, and performance metrics. It serves as a decision-support tool to ensure program resources are targeted where they are needed most.

🇨🇩 The Challenge: Data Quality in Rural Education
Collecting data in the Kasaï region presents significant challenges for M&E teams:

The Bias Problem: Field data often contained collection biases or human errors that skewed the evaluation of program impact.

Geographical Spread: Managing data from 9 different educational sub-divisions in real-time was logistically difficult.

Delayed Insights: Conventional reporting cycles were too slow to detect if an educational sub-division was failing to meet its targets.
🛠 Technical Solution
I developed a reactive, statistical pipeline that cleanses incoming data and visualizes trends instantly.

The Stack:
Data Source: KoboToolbox (ODK-based) for field collection across remote schools.

Processing Engine: Python for automated data cleaning, normalization, and bias detection algorithms.

Dashboarding: R/Shiny for statistical visualization and interactive reporting.

Key Features:
Real-time Bias Detection: Automated algorithms scan incoming data from KoboToolbox to flag statistical anomalies or collection errors before they impact the final report.

Regional Benchmarking: Compare performance across 9 different educational sub-divisions to identify "hotspots" and "cold-spots."
Impact & Results
Higher Data Fidelity: Significantly reduced noise and reporting errors, ensuring that the "AXE-Filles" impact evaluation is based on clean, verifiable data.

Operational Agility: Enabled Save the Children staff to identify underperforming sub-divisions immediately, allowing for rapid course-correction.

Evidence-Based Programming: Provided a solid data foundation for program reports, essential for continued donor funding and resource allocation.

📸 Technical Showcase
[!IMPORTANT]

Privacy Note: Data shown is anonymized/synthetic to comply with NGO data protection policies regarding student records.
Trend Analysis: Visualizes enrollment and attendance trends over time, helping leadership understand if interventions are working.

Interactive UI: User-friendly dashboard for field managers who are not necessarily data experts.

📂 Repository Structure
/app: R/Shiny dashboard source code.

/scripts: Python logic for data cleaning, bias detection, and ETL.

/models: Statistical models used for trend analysis.

/docs: Methodological notes on M&E best practices.

📫 Contact
For inquiries regarding M&E (Monitoring & Evaluation) tech, R/Shiny dashboards, or NGO data pipelines:
Alpha Mubay - lucmubay@gmail.com
