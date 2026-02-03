# Cloud VM Monitoring & Alert System

## Overview
This project demonstrates infrastructure monitoring and alerting for virtual machines in a cloud environment.

## Architecture
VM Instance → Cloud Monitoring → Alert Policy → Email Notification

## Cloud Services Used
- Compute Engine / EC2
- Cloud Monitoring / CloudWatch
- Alert Policies
- Email Notification (SNS / GCP Email)

## What I Implemented
- Deployed a virtual machine
- Enabled CPU utilization monitoring
- Created alert policy for CPU threshold breach (>70%)
- Integrated email notifications for incidents
- Simulated high CPU usage using stress testing

## Incident Simulation
A CPU spike was artificially generated to simulate a real production incident and verify alert triggering.

## Outcome
The system successfully detected abnormal CPU usage and notified the administrator via email.

## Screenshots
<img width="1918" height="888" alt="cloud vm1" src="https://github.com/user-attachments/assets/1dd0d398-a829-4a63-b38a-f147f8ae1916" />
<img width="1153" height="907" alt="cloud vm 2" src="https://github.com/user-attachments/assets/0acafa9f-2972-4072-9484-fec4d9b9384a" />
<img width="1905" height="975" alt="cloud vm 3" src="https://github.com/user-attachments/assets/1f5601a9-0e7d-40a3-9155-1f98959e7493" />
<img width="1582" height="806" alt="cloud vm 4" src="https://github.com/user-attachments/assets/43e692db-2f33-4e03-9b75-d9d375696364" />
<img width="1911" height="953" alt="cloud vm 5" src="https://github.com/user-attachments/assets/d5b0a08b-4c68-4839-abfc-822f7cfac523" />
