# Threat Model Project

This project is a threat model analysis focusing on a document delivery and management workflow within a secure trust boundary. It involves interactions between internal processes (such as scheduling, document generation, and data storage) and external entities (like Print Services, Banking, and Email Providers). The objective is to analyze potential security threats to the system and propose mitigations based on threat modeling frameworks.

## Key Components
- P2 Delivery: Manages the flow of documents and communication with external services.
- P1 Scheduler: Coordinates tasks and interacts with internal components.
- P3 PDS: Stores sensitive user data and documents securely.
- P4 Document Generator: Creates documents for further processing and delivery.

## Threat Analysis
The project utilizes LINDDUN and STRIDE frameworks to evaluate threats. Identified threats include:
- Spoofing: Impersonation of system entities.
- Tampering: Unauthorized modification of data.
- Information Disclosure: Exposure of sensitive data.
- Denial of Service (DoS): Overloading the system to disrupt services.
- Elevation of Privilege: Gaining unauthorized control within the system.

## Team Contributions
The project was a collaborative effort, with team members focusing on specific threat types:
- Retaj Baaqeel: Linked threats and non-repudiation analysis.
- Razan Almalki: Data disclosure and compliance checks.
- Ruba Alotaibi: Addressed repudiation, privilege escalation, and DoS.
- Wafaa Alawadhi: Investigated spoofing, information disclosure, and tampering.

## Lessons Learned
Through this project, the team gained practical experience in identifying and categorizing data flows, designing secure system elements, and handling team collaboration effectively. Despite challenges with advanced tools like OWASP Threat Dragon, the project enhanced the team's skills in threat modeling and system security.
