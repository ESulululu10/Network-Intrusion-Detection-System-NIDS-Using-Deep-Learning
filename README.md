# Network Intrusion Detection System (NIDS) Using Deep Learning

## Overview
This project develops a Network Intrusion Detection System using deep learning (CNN, LSTM) to detect malicious network activity like DoS attacks, malware, and unauthorized access in real time.

## Features
- Real-time network traffic monitoring
- Multi-class and binary intrusion classification
- Deep learning and classical ML models included
- Alerts and reports on detected threats
- Scalable and adaptable to different network setups

## Project Files
- `app.js` — Backend server
- Model files (`*.h5`, `*.sav`) — Trained models
- Python scripts (`nids_csv_updated.py`, etc.) — Data processing and training
- Dataset (`fs_new validation project.csv`)
- `requirements.txt` and `package.json` — Dependencies

## Setup

### Python
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate
pip install -r requirements.txt
python nids_csv_updated.py

Node.js
bash
Copy
Edit
npm install
node app.js
Evaluation
Models are evaluated with accuracy, precision, recall, and F1 score, outperforming traditional NIDS.

Future Work
Cloud integration

Enhanced privacy/security

Detection of advanced threats


Contact
gaurabkhadka03@gmail.com
