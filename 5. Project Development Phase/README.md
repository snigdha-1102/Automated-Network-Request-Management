
# 5. Project Development Phase

This folder contains the implementation and development documentation for the Automated Network Request Management project developed using ServiceNow App Engine Studio.

## Development Components

1. Scoped Application Creation
2. Service Catalog and Network Request Form
3. Catalog Variables and Variable Sets
4. Catalog UI Policies and Form Validation
5. Custom Database Tables
6. Flow Designer Approval Workflow
7. Request-Created Email Notification
8. Network Task Table Configuration
9. Network Task Completion Email Flow
10. Application Roles and Access Control Lists
11. Testing and Validation

## Implementation Overview

The application was developed using ServiceNow's native platform capabilities.

### Main Features

- Network Request catalog item for submitting service requests.
- Requester Information variable set with automatic population of user details.
- Conditional Existing ID field based on connection type.
- Mandatory-field configuration.
- Database Tables for storing request information.
- Flow Designer workflow for approval processing.
- Separate approved and rejected workflow branches.
- Network Task Table for tracking fulfilment work.
- Automated resolution email when Work Status changes to Completed.
- Application roles and table-level access controls.

## Development Platform

ServiceNow App Engine Studio  
ServiceNow Service Portal  
Service Catalog  
Flow Designer

## Important Implementation Note

The Network Request flow creates and updates request records. Network Task Table records are created separately in the current implementation.

## Testing Evidence

This folder can contain screenshots of the catalog form, custom tables, Flow Designer workflows, approval records, and email previews.
