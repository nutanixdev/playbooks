# Nutanix Cloud Manager (NCM) Self-Service and Nutanix Intelligent Ops Integration

Export Version: pc.7.5

Description: This playbook is intended for use with the following article:

[NCM Self-Service and Nutanix v4 API Integration: Generate Ops Mgmt report using NCM Self-Service](https://www.nutanix.dev/2025/12/22/ncm-self-service-and-nutanix-v4-api-integration-generate-ops-mgmt-report-using-ncm-self-service/)

It uses a simple VM creation trigger to generate an Intelligent Ops report via Nutanix v4 REST APIs.  Distributed with this playbook is an NCM Self-Service Runbook, used to complete the actual report generation.

Steps to Enable:

1. Edit the NCM Self-Service Runbook
2. Edit the runbook, making sure appropriate credentials and **Input Variables** are entered for your environment.
3. Import the Intelligent Ops Playbook
4. Edit the playbook, making sure Execute Runbook action is configured to execute the imported Runbook
5. Save **and Enable** the playbook
