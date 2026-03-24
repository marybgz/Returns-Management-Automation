# Returns Management Automation
## Overview

This project focuses on redesigning and automating a returns management process using Microsoft Power Platform.

The original workflow relied heavily on emails, manual updates, and disconnected tools, which made it difficult to track requests, ensure consistency, and extract reliable data.

The solution centralizes the entire process into a single structured system, improving visibility, control, and enabling data analysis.

# Problem

## The process had several operational issues:

- Multiple entry points (email, SharePoint, informal communication)
- Lack of standardization
- High dependency on email for communication and tracking
- Limited visibility of request status, especially in logistics
- Manual control through spreadsheets
- No structured data for analysis

# Solution

A centralized workflow was designed using Microsoft 365 tools:

- Power Apps for request creation and process management
- SharePoint as the main data source
- Power Automate for approvals and notifications
- Power BI for monitoring and analysis

This approach ensures that all requests follow the same structure and lifecycle.

## Process Flow

1. Request is created through Power Apps
2. Data is stored in a SharePoint list
3. The request is assigned and analyzed
4. Approval is handled through automated flows
5. Logistics updates the status directly in the system
The process is tracked until completion
