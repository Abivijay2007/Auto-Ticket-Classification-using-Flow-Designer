# Auto Ticket Classification using Flow Designer

## Project Overview
This project automates the classification of IT support tickets using ServiceNow Flow Designer. The system analyzes the short description of an incident and automatically assigns the appropriate Category and Subcategory.

## Problem Statement
The school IT helpdesk receives multiple incident requests such as Wi-Fi issues, projector failures, password problems, and slow computers. Manually reviewing and categorizing every ticket is time-consuming and inefficient.

## Objectives
- Automatically classify incidents when they are created.
- Reduce manual effort for IT agents.
- Improve ticket routing efficiency.
- Provide a no-code and easily maintainable solution.
- Send an automated email notification to the caller.

## Technologies Used
- ServiceNow
- Flow Designer
- Update Sets
- Custom Tables
- Choice and Reference Fields
- Email Notifications

## Ticket Classification

| Keyword / Issue | Category | Subcategory |
|---|---|---|
| WiFi / Network | Network | Wi-Fi |
| Projector | Hardware | Projector |
| Password / Login | Access | Forgot Password |
| Slow / Hanging | Performance | Slow Computer |

## How It Works
1. A student creates an IT support ticket.
2. The Flow Designer is triggered when the record is created.
3. The flow checks the Short Description for predefined keywords.
4. Category and Subcategory are automatically assigned.
5. An email confirmation is sent to the caller.
6. The ticket is stored in a structured format.

## Key Features
- Automatic ticket classification
- Dependent Category and Subcategory fields
- Automated email notification
- No-code automation using Flow Designer
- Structured ticket management
- Easy maintenance and scalability

## Testing
The project was tested with different ticket scenarios such as:
- WiFi not working in library → Network → Wi-Fi
- Projector not turning on → Hardware → Projector

## Conclusion
The project provides an end-to-end automated solution for school IT helpdesk ticket classification. It reduces manual effort, improves data accuracy, and provides faster ticket processing using ServiceNow Flow Designer.
