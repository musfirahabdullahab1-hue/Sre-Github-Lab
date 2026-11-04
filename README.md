# Sre-Github-Lab
Requirements documentation for a Student Task Tracker
Online ID Card Application and Management System
## Overview
Applying for or renewing a national ID card currently requires repeated visits to registration centers, long waits, travel costs, and little visibility into application progress. This project proposes a web platform, working with NADRA, that lets citizens apply, upload documents, pay fees, and track their application online. Physical visits remain only where biometric verification requires them. The intended benefit is fewer visits, shorter waits, and a more transparent process for applicants and staff.

## Scope
- In scope: Create an applicant account and log in securely.
- In scope: Submit an ID card application (new, renewal, update, replacement) with documents and photographs.
- In scope: Track application status using a unique reference number.
- In scope: Pay application fees online and receive a receipt.
- In scope: Review, approve, reject, or request more information on applications (staff dashboard).
- Out of scope: Manufacturing or printing ID cards.
- Out of scope: Banking services (only fee payment through authorized gateways).
- Out of scope: Modifying official identity records without authority approval.

## Stakeholders
- Applicant / Citizen: Applies for an ID card, uploads documents, pays fees, and tracks progress.
- Registration / NADRA Staff: Processes applications and handles biometric requirements.
- Verification Officer: Verifies identity and supporting documents before approval.
- Manager / Administrator: Monitors applications and staff, and resolves operational issues.
- Customer Support Staff: Answers queries and handles complaints.
- NADRA / Government Authority: Maintains accurate, secure national identity records.
- IT Team: Keeps the system available, secure, and backed up.

## Functional requirements
- FR-01: The system shall let an eligible citizen create an account and log in securely.
- FR-02: The system shall let an applicant submit an ID card application with required information, documents, and photographs.
- FR-03: The system shall give each submitted application a unique reference number.
- FR-04: The system shall let an applicant view the status of their application (Submitted, Under Verification, Approved/Rejected, Processing, Ready/Dispatched).
- FR-05: The system shall let an applicant pay the applicable fee online and receive a receipt.
- FR-06: The system shall let authorized staff approve, reject, or request additional information for an application.

## Nonfunctional requirements
- NFR-01: The application status page shall appear within 3 seconds in at least 95 of 100 trials on the agreed test device.
- NFR-02: All applicant actions shall be operable using a keyboard alone, verified against each documented workflow.
- NFR-03: Sensitive applicant data shall be visible only to authorized staff roles, verified by testing each role.

## Acceptance criteria
- FR-01: Given valid details, creating an account allows the user to log in with those credentials.
- FR-02: Given a completed form with required documents, submitting it saves the application.
- FR-03: Given a submitted application, a unique reference number is displayed.
- FR-04: Given a reference number, the status page shows the current stage.
- FR-05: Given a successful payment, a receipt is generated and shown to the applicant.
- FR-06: Given an application under verification, a staff member's approval changes its status to Approved.

## Assumptions and open questions
- Assumption A-01: NADRA provides access to its identity verification service for this system.
- Assumption A-02: Applicants have internet access and a device that can upload documents and photos.
- Question Q-01: Which applicants must attend a physical biometric appointment, and which can complete the process fully online?
- Question Q-02: Which device and environment will test NFR-01?

## Project status and viewing
Documentation only. Application implementation has not started. Clone this repository and open README.md in a Markdown viewer, or read the rendered file on GitHub.

## Author
Group 10, [course identifier]
- Sana Gohar (BSEF25M524)
- Anoosha Eman (BSEF25M535)
- Musfirah Abdullah (BSEF25M553)

## Contributing
Create a documentation branch, edit and review the README, commit the change, push the branch, and open a pull request.