# Phase 3 – Project Design

## Project Title
Streamlining IT Procurement – Automating Standard Laptop Orders with Flow Designer

## 1. System Design

The proposed system is designed to automate the standard laptop procurement process using ServiceNow Flow Designer.

## 2. System Architecture

The workflow consists of the following major components:

1. User / Employee
2. ServiceNow Request
3. Request Validation
4. Approval Process
5. Flow Designer
6. Procurement Processing
7. Notification
8. Request Status Update

## 3. Workflow Design

The proposed workflow follows these steps:

User submits laptop request
        ↓
Request is created
        ↓
Request information is validated
        ↓
Approval is triggered
        ↓
Approver reviews request
        ↓
Approved?
   ┌────┴────┐
  Yes        No
   ↓          ↓
Procurement  Request
Processing   Rejected
   ↓
Status Updated
   ↓
Notification Sent
   ↓
Request Completed

## 4. Use Case Design

### Actor: Employee
- Submit laptop request
- View request status

### Actor: Approver
- Review request
- Approve request
- Reject request

### Actor: IT Procurement Team
- Process approved request
- Update procurement status

### Actor: ServiceNow
- Validate request
- Trigger workflow
- Send notifications
- Update request status

## 5. Flow Designer Design

The Flow Designer workflow will contain:

### Trigger
A standard laptop request is submitted.

### Actions
1. Validate request details
2. Identify the required approver
3. Request approval
4. Check approval result
5. Process approved request
6. Update request status
7. Send notification

## 6. Data Design

The laptop request may contain the following information:

- Request Number
- Requested For
- Requested By
- Laptop Model
- Department
- Business Justification
- Approval Status
- Procurement Status
- Request Date
- Completion Date

## 7. Security Design

The system should ensure that:

- Only authorized users can submit requests.
- Only authorized approvers can approve or reject requests.
- Procurement information is accessible to appropriate users.
- Workflow activities are tracked.

## 8. Error Handling

The workflow should handle situations such as:

- Missing request information
- Approval rejection
- Invalid request data
- Workflow execution failure
- Notification failure

## 9. Expected Design Outcome

The final design provides a structured automated workflow for processing standard laptop procurement requests with reduced manual intervention and improved process visibility.

## 10. Conclusion

The project design defines the architecture, workflow, actors, data, security, and automation logic required for implementing the IT procurement solution using ServiceNow Flow Designer.
