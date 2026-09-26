# Azure Storage Explorer and SAS Token Governance

## Project Overview

This project demonstrates secure file access using Azure Blob Storage and Shared Access Signatures (SAS).

SAS tokens provide users with limited permissions and access for a specific period of time.

## Objectives

- Store files securely using Azure Blob Storage.
- Generate SAS tokens for controlled file access.
- Provide different permissions such as Read and Write.
- Set an expiry time for SAS access.
- Prevent unauthorized operations.
- Audit storage access using Azure Monitor and Log Analytics.

## Technologies Used

- Microsoft Azure
- Azure Blob Storage
- Shared Access Signature (SAS)
- Azure Monitor
- Log Analytics
- Kusto Query Language (KQL)

## Main Features

### 1. SAS Permissions

Different permissions can be assigned to a SAS token, such as:

- Read
- Write
- Delete

### 2. SAS Expiry

The SAS token is valid only for the specified time period.

### 3. Permission Restriction

A user with Read-only permission cannot perform a Write operation.

### 4. Audit Logging

Storage Read, Write, and Delete activities are sent to Log Analytics for auditing.=

## Testing

The project demonstrates:

- Successful Read access
- Successful Write access
- Rejection of unauthorized Write operation
- SAS expiry
- Storage access audit logs

## Project Structure

```text
Azure-SAS-Token-Governance/
│
├── README.md
├── Documentation/
├── Architecture/
├── Screenshots/
└── Services-Technologies/
