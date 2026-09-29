# Phase 5 – Project Development

## Project Title
Streamlining IT Procurement – Automating Standard Laptop Orders with Flow Designer

## 1. Development Objective

The objective of this phase is to implement the automated standard laptop procurement workflow using ServiceNow Flow Designer.

## 2. Development Platform

- ServiceNow
- Flow Designer
- ServiceNow Request Management
- Web Browser

## 3. Development Components

The project will include:

1. Laptop Request
2. Request Information
3. Request Validation
4. Approval Workflow
5. Flow Designer Automation
6. Procurement Processing
7. Status Updates
8. Notifications

## 4. Workflow Implementation

The planned workflow is:

User submits laptop request
        ↓
Request is created
        ↓
Validate request
        ↓
Send approval request
        ↓
Approval decision
        ↓
Approved → Procurement Processing
        ↓
Update request status
        ↓
Send notification
        ↓
Complete request

If the request is rejected:

Approval rejected
        ↓
Update request status
        ↓
Send rejection notification
        ↓
Complete request

## 5. Development Steps

### Step 1 – Create Request Structure
Configure the information required for a standard laptop request.

### Step 2 – Configure Request Fields
Add fields such as:

- Requested For
- Department
- Laptop Model
- Business Justification
- Request Date
- Approval Status
- Procurement Status

### Step 3 – Create Flow
Create a Flow Designer flow for the standard laptop procurement process.

### Step 4 – Configure Trigger
Configure the flow to start when a valid laptop request is submitted.

### Step 5 – Configure Approval
Add the required approval step to the flow.

### Step 6 – Configure Decision Logic
Configure the flow to handle approved and rejected requests.

### Step 7 – Configure Procurement Processing
Process the request after approval.

### Step 8 – Configure Notifications
Send notifications for approval, rejection, and completion events.

### Step 9 – Update Request Status
Update the request status based on the workflow result.

## 6. Development Status

| Component | Status |
|---|---|
| Request Structure | Planned |
| Request Fields | Planned |
| Flow Trigger | Planned |
| Approval | Planned |
| Decision Logic | Planned |
| Procurement Processing | Planned |
| Notifications | Planned |
| Status Updates | Planned |

## 7. Expected Output

The completed development should provide an automated workflow that processes standard laptop procurement requests with minimal manual intervention.

## 8. Development Evidence

Screenshots of the ServiceNow configuration and Flow Designer workflow will be added to this folder during implementation.

## 9. Conclusion

This phase implements the design created in the previous phases and converts the planned procurement process into an automated ServiceNow workflow.
