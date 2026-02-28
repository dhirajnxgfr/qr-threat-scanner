@"
# 🛡️ QR Shield — QR Code Threat Scanner

Instantly scan any QR code to detect phishing, malware, and suspicious URLs.

## Features
- QR code decoding via OpenCV + pyzbar
- 8 heuristic checks (typosquatting, suspicious TLDs, redirect chains...)
- VirusTotal API (90+ threat engines)
- Google Safe Browsing API
- Risk score 0-100 with verdict

## Run locally
pip install -r requirements.txt
streamlit run app.py

## Stack
Python · Streamlit · OpenCV · pyzbar · VirusTotal API · Google Safe Browsing
"@ | Out-File -FilePath README.md -Encoding utf8
