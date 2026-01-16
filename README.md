# aws-security-monitoring-project
# AWS Security Monitoring & Alerting System

## Overview
This project implements a real-time security monitoring system on AWS to detect sensitive access using CloudTrail logs and automated alerting.

## Architecture
![Architecture Diagram](architecture/architecture.png)
CloudTrail logs API activity → CloudWatch Logs stores events → Metric Filters detect risky actions → CloudWatch Alarms trigger → SNS sends alerts via email.

## Security Use Cases
- Detection of sensitive access events
- Real-time alerting for suspicious activity
- Cloud-native security monitoring

## AWS Services Used
- AWS CloudTrail
- Amazon CloudWatch
- Amazon SNS

## What I Learned
- How CloudTrail and CloudWatch work together for security monitoring
- Designing alert thresholds to reduce false positives
- Implementing cloud-native detection and alerting

