# AI-Enhanced SOC Capstone

This project integrates all major components of a modern AI-driven Security Operations workflow.

## Components
- ETL pipeline for AWS logs (CloudTrail, GuardDuty, VPC Flow)
- Identity Risk ML model
- Anomaly Detection model
- Threat Intelligence RAG System
- Dashboards (Streamlit/Dash)
- MITRE ATT&CK detection coverage map
- SOC runbooks & response playbooks

## Structure
etl/
  pipeline.py

models/
  identity_risk/
  anomaly_detection/

rag/
  ti_rag_assistant/

dashboards/
  streamlit_app.py

runbooks/
  detection_playbook.md
  incident_response_playbook.md

## Goals
- Improve detection coverage
- Reduce false positives and MTTD/MTTR
- Demonstrate applied AI for cloud security operations

