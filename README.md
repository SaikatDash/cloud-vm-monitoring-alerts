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
See the screenshots folder for alert and notification proof.
