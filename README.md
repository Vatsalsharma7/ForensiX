# ForensiX
A cyber triage tool to streamline digital forensic investigation


ForensiX is an advanced cyber triage tool designed to streamline and automate the digital forensic investigation process. Developed under the Smart India Hackathon 2024, this tool empowers investigators with a unified platform that integrates memory analysis, file system parsing, registry evaluation, and network data inspection using state-of-the-art forensic frameworks such as Sleuth Kit (TSK), Volatility, and PyShark.

At its core, ForensiX combines traditional forensic methods with machine learning models such as Isolation Forest and Random Forest to detect behavioral anomalies and assess their severity in real time. The tool assigns risk scores based on user and device activities, prioritizes alerts, and provides adaptive threat intelligence with customizable thresholds.

Its intuitive interface ensures that even non-technical stakeholders can visualize critical findings through color-coded dashboards, severity charts, and user activity heatmaps. ForensiX simplifies evidence handling, enhances threat detection accuracy, and accelerates the incident response process—making it an essential asset for law enforcement, incident responders, and cybersecurity professionals.

**<h1>🔧 How ForensiX Works</h1>**

<h2>🗃 Evidence Ingestion</h2>

Investigators import system images, memory dumps, registry files, and network traffic captures.

Tools used:

Sleuth Kit (TSK) for disk & file system data

Volatility for memory analysis

PyShark for network traffic parsing

<h2>📊 Data Extraction & Preprocessing</h2>

Metadata, logs, user activity, running processes, registry entries, and network flows are parsed and structured.

Custom scripts organize raw data for machine learning compatibility.

<h2>🤖 Anomaly Detection</h2>

Behavior-based anomaly detection using:

Isolation Forest – Flags unusual user/device actions

Random Forest – Scores severity based on anomaly patterns

<b2>📈 Risk Scoring & Prioritization<b2>

Each anomaly is assigned a risk level (High, Medium, Low)

Threats are ranked to guide investigators to the most critical areas first.

<h2>🧭 Real-Time Visualization</h2>
Interactive dashboards display:

Anomaly heatmaps

Severity charts

User behavior trends

File/network activity timelines

<h2>📝 Reporting & Export</h2>

Auto-generates investigation reports with filtered logs, risk scores, and timelines.

Formats: PDF, JSON, and CSV for compatibility with external tools.

