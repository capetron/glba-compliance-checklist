# GLBA Compliance Checklist

A step-by-step actionable checklist for financial institutions complying with the Gramm-Leach-Bliley Act (GLBA) and the revised FTC Safeguards Rule (effective June 9, 2023).

Maintained by [Petronella Technology Group, Inc.](https://petronellatech.com/compliance/glba/) | Call 919-348-4912 for a free GLBA compliance assessment.

---

## Phase 1: Determine Applicability and Scope

### 1.1 Coverage Determination

- [ ] Determine if your organization qualifies as a "financial institution" under GLBA (15 U.S.C. 6809(3))
- [ ] Identify which federal agency has enforcement authority over your organization (FTC, OCC, FDIC, Federal Reserve, NCUA, state regulators)
- [ ] If under FTC jurisdiction, confirm the revised Safeguards Rule (16 CFR Part 314) applies
- [ ] Determine if the small institution exemption applies (fewer than 5,000 customer records exempts from some requirements)
- [ ] Document the scope determination and retain for compliance records

### 1.2 Data Inventory

- [ ] Identify all categories of nonpublic personal information (NPI) your organization collects
- [ ] Map where NPI is stored (databases, file systems, paper records, cloud services, third-party systems)
- [ ] Map how NPI flows through your organization (collection, processing, storage, sharing, disposal)
- [ ] Identify all systems and applications that process, store, or transmit NPI
- [ ] Identify all personnel who have access to NPI
- [ ] Identify all third-party service providers that receive or have access to NPI
- [ ] Document the data inventory and update at least annually

## Phase 2: Governance and Organization

### 2.1 Designate a Qualified Individual

- [ ] Appoint a Qualified Individual to oversee the information security program
- [ ] Ensure the Qualified Individual has sufficient knowledge and experience in cybersecurity and information security
- [ ] If outsourcing, execute a contract with a virtual CISO provider that includes:
  - [ ] Specific responsibilities and scope of oversight
  - [ ] Reporting requirements to the board/governing body
  - [ ] Access to personnel, systems, and records needed for oversight
- [ ] Document the designation and qualifications of the Qualified Individual
- [ ] Ensure the Qualified Individual has authority to direct resources and make security decisions

### 2.2 Board/Governing Body Engagement

- [ ] Establish a reporting cadence (annual report required; quarterly recommended)
- [ ] Define the content of the annual board report:
  - [ ] Overall status of the information security program
  - [ ] Compliance with the Safeguards Rule
  - [ ] Material matters related to the program (incidents, audit findings, significant risks)
  - [ ] Recommendations for changes to the program
- [ ] Ensure the board has sufficient cybersecurity literacy to provide meaningful oversight
- [ ] Document board meeting minutes reflecting security program discussions

## Phase 3: Risk Assessment

### 3.1 Written Risk Assessment

- [ ] Identify reasonably foreseeable internal threats to NPI (employee error, insider threats, system failures)
- [ ] Identify reasonably foreseeable external threats to NPI (cyberattacks, social engineering, physical theft)
- [ ] For each identified threat, assess:
  - [ ] Likelihood of occurrence (Low, Medium, High)
  - [ ] Potential impact to NPI confidentiality, integrity, and availability
  - [ ] Severity rating combining likelihood and impact
- [ ] Evaluate the sufficiency of existing safeguards to control identified risks
- [ ] Document the risk assessment in writing
- [ ] Identify risk treatment decisions (accept, mitigate, transfer, avoid) for each risk
- [ ] Prioritize remediation activities based on risk severity
- [ ] Have the Qualified Individual review and approve the risk assessment
- [ ] Schedule annual risk assessment updates (and update after significant changes)

### 3.2 Asset and Threat Inventory

- [ ] Inventory all data repositories containing NPI
- [ ] Inventory all devices that access, process, or store NPI
- [ ] Inventory all personnel with NPI access (by role and level of access)
- [ ] Inventory all facilities where NPI is stored or accessed
- [ ] Document network topology and data flow diagrams for systems handling NPI
- [ ] Maintain a current inventory (update within 30 days of changes)

## Phase 4: Written Information Security Program (WISP)

### 4.1 Administrative Safeguards

- [ ] Develop a comprehensive Written Information Security Program (WISP) document
- [ ] Define roles and responsibilities for information security
- [ ] Establish acceptable use policies for systems handling NPI
- [ ] Develop data classification policies identifying NPI
- [ ] Establish data retention and disposal policies
- [ ] Develop change management procedures for systems handling NPI
- [ ] Establish an employee background check policy for personnel with NPI access
- [ ] Develop a remote work policy addressing NPI security
- [ ] Establish a clean desk/clean screen policy

### 4.2 Technical Safeguards: Access Controls

- [ ] Implement role-based access controls (RBAC) for all systems containing NPI
- [ ] Apply the principle of least privilege (grant minimum access necessary for job functions)
- [ ] Implement multi-factor authentication (MFA) for all users accessing systems with NPI
- [ ] Implement unique user IDs for all personnel (no shared accounts)
- [ ] Implement automated session timeouts for inactive sessions
- [ ] Implement automated account lockout after failed login attempts
- [ ] Conduct access reviews quarterly and remove unnecessary access promptly
- [ ] Implement procedures for immediate access revocation upon employee separation

### 4.3 Technical Safeguards: Encryption

- [ ] Encrypt all NPI in transit over external networks (TLS 1.2 or higher)
- [ ] Encrypt all NPI at rest in databases and file systems
- [ ] Encrypt all NPI on portable devices (laptops, mobile devices, removable media)
- [ ] Encrypt all NPI in email communications
- [ ] Encrypt all backups containing NPI
- [ ] If encryption at rest is infeasible for any system:
  - [ ] Document why encryption is infeasible
  - [ ] Identify and implement alternative compensating controls
  - [ ] Have the Qualified Individual approve the compensating controls in writing
- [ ] Manage encryption keys securely with documented key management procedures

### 4.4 Technical Safeguards: Monitoring and Detection

- [ ] Implement audit logging on all systems containing NPI
- [ ] Log all access to NPI (successful and failed attempts)
- [ ] Log all administrative actions on systems containing NPI
- [ ] Implement a centralized log management solution (SIEM recommended)
- [ ] Configure alerting for suspicious activities (multiple failed logins, unusual access patterns, large data exports)
- [ ] Retain audit logs for a minimum of one year (two years recommended)
- [ ] Review logs regularly (daily for critical alerts; weekly for aggregate analysis)
- [ ] Implement endpoint detection and response (EDR) on all systems handling NPI
- [ ] Implement network intrusion detection/prevention

### 4.5 Technical Safeguards: Secure Development

- [ ] If developing in-house applications that handle NPI:
  - [ ] Implement secure development lifecycle (SDLC) practices
  - [ ] Conduct code reviews with security focus
  - [ ] Perform application security testing (SAST, DAST)
  - [ ] Separate development, testing, and production environments
  - [ ] Do not use real NPI in development or testing environments

### 4.6 Technical Safeguards: Data Disposal

- [ ] Establish procedures for secure disposal of NPI when no longer needed
- [ ] Implement secure deletion for electronic NPI (NIST SP 800-88 compliant)
- [ ] Implement secure destruction for physical NPI (cross-cut shredding minimum)
- [ ] Implement secure decommissioning procedures for hardware that stored NPI
- [ ] Maintain disposal records documenting what was destroyed and when

### 4.7 Physical Safeguards

- [ ] Implement physical access controls for areas containing NPI (badge readers, locks)
- [ ] Maintain visitor logs for secure areas
- [ ] Implement clean desk policies in areas where NPI is handled
- [ ] Secure paper records containing NPI in locked cabinets
- [ ] Implement video surveillance in areas with physical NPI storage (recommended)
- [ ] Secure server rooms and network infrastructure

## Phase 5: Testing and Monitoring

### 5.1 Vulnerability Assessments and Penetration Testing

Choose one of the following approaches:

**Option A: Periodic Testing**
- [ ] Conduct annual penetration testing of external-facing systems
- [ ] Conduct semi-annual vulnerability assessments of all systems containing NPI
- [ ] Remediate critical and high vulnerabilities within 30 days
- [ ] Remediate medium vulnerabilities within 90 days
- [ ] Document all findings, remediation actions, and timelines
- [ ] Retain testing reports for a minimum of three years

**Option B: Continuous Monitoring**
- [ ] Implement continuous monitoring infrastructure that detects threats and vulnerabilities in real time
- [ ] Document the continuous monitoring program scope and methodology
- [ ] Demonstrate that continuous monitoring provides equivalent or better coverage than periodic testing
- [ ] Generate regular reports from continuous monitoring data

### 5.2 Ongoing Security Assessments

- [ ] Conduct annual reviews of the information security program effectiveness
- [ ] Assess whether safeguards continue to address risks identified in the risk assessment
- [ ] Test incident response procedures at least annually (tabletop exercise minimum)
- [ ] Review access controls quarterly
- [ ] Test backup and restoration procedures at least annually
- [ ] Document all assessment activities and findings

## Phase 6: Privacy Notices

### 6.1 Initial Privacy Notice

- [ ] Develop an initial privacy notice that includes:
  - [ ] Categories of NPI collected
  - [ ] Categories of NPI disclosed to third parties
  - [ ] Categories of third parties to whom NPI is disclosed
  - [ ] Description of policies for protecting NPI
  - [ ] Consumer's right to opt out of disclosures to non-affiliated third parties
  - [ ] Instructions for exercising opt-out rights
- [ ] Deliver the initial notice at the time of establishing a customer relationship
- [ ] Deliver the notice in a clear, conspicuous manner

### 6.2 Annual Privacy Notice

- [ ] Determine if annual privacy notice is required (not required if you do not share NPI with non-affiliated third parties and have not changed your privacy practices)
- [ ] If required, deliver annual privacy notice to all existing customers
- [ ] Post the current privacy notice on your website
- [ ] Update the privacy notice when practices change

### 6.3 Opt-Out Procedures

- [ ] Implement procedures for consumers to opt out of NPI sharing with non-affiliated third parties
- [ ] Provide a reasonable means of opting out (toll-free number, reply form, website form)
- [ ] Honor opt-out requests within a reasonable time period (30 days recommended)
- [ ] Maintain records of opt-out requests and compliance

## Phase 7: Service Provider Management

### 7.1 Vendor Assessment and Contracts

- [ ] Inventory all service providers that receive, access, or process NPI
- [ ] Categorize service providers by risk level based on their access to NPI
- [ ] Conduct security due diligence on service providers before engagement:
  - [ ] Request SOC 2 reports or equivalent security documentation
  - [ ] Review the provider's information security policies
  - [ ] Assess the provider's incident response capabilities
- [ ] Include contractual provisions requiring service providers to:
  - [ ] Implement and maintain appropriate safeguards for NPI
  - [ ] Notify your organization of security incidents affecting NPI
  - [ ] Allow audit or assessment of their security practices
  - [ ] Return or destroy NPI upon contract termination
- [ ] Maintain a service provider inventory with contract terms and review dates

### 7.2 Ongoing Monitoring

- [ ] Conduct periodic assessments of service provider compliance (annual minimum for high-risk providers)
- [ ] Review service provider SOC 2 reports annually
- [ ] Monitor service providers for security incidents and breaches
- [ ] Update service provider risk assessments when services or access change
- [ ] Document all monitoring activities and findings

## Phase 8: Training

### 8.1 Security Awareness Training

- [ ] Develop a security awareness training program covering:
  - [ ] GLBA requirements and the organization's obligations
  - [ ] What constitutes NPI and how to identify it
  - [ ] Proper handling and protection of NPI
  - [ ] Recognizing social engineering and phishing attacks
  - [ ] Incident reporting procedures
  - [ ] Acceptable use policies
  - [ ] Password security and MFA
  - [ ] Clean desk and physical security practices
- [ ] Deliver training to all employees upon hire
- [ ] Deliver annual refresher training to all employees
- [ ] Maintain training completion records

### 8.2 Specialized Training

- [ ] Provide role-based training for personnel with security responsibilities
- [ ] Provide specialized training for the Qualified Individual
- [ ] Provide training for service provider management personnel
- [ ] Provide training for incident response team members
- [ ] Document all specialized training activities and attendance

## Phase 9: Incident Response

### 9.1 Written Incident Response Plan

- [ ] Develop a written incident response plan that includes:
  - [ ] Goals of the incident response program
  - [ ] Incident response team roles and responsibilities
  - [ ] Internal communication procedures during an incident
  - [ ] External communication procedures (regulators, customers, law enforcement)
  - [ ] Incident classification and severity levels
  - [ ] Step-by-step procedures for containing and eradicating incidents
  - [ ] Evidence preservation and forensic procedures
  - [ ] Recovery and restoration procedures
  - [ ] Post-incident review and lessons learned process
  - [ ] Plan revision procedures based on lessons learned
- [ ] Identify and document applicable breach notification requirements (federal and state)
- [ ] Establish relationships with external resources (forensic investigators, legal counsel, PR)

### 9.2 Testing and Maintenance

- [ ] Conduct tabletop exercises at least annually
- [ ] Test technical incident response capabilities (containment, eradication, recovery)
- [ ] Update the incident response plan based on lessons learned from exercises and actual incidents
- [ ] Ensure all incident response team members have current contact information and access
- [ ] Maintain a log of all security incidents and response actions

## Phase 10: Ongoing Compliance

### 10.1 Program Maintenance

- [ ] Review and update the WISP at least annually
- [ ] Review and update the risk assessment at least annually
- [ ] Update policies and procedures when regulations, technology, or business operations change
- [ ] Monitor FTC enforcement actions and guidance for compliance updates
- [ ] Monitor state-level privacy and cybersecurity regulations for additional requirements
- [ ] Maintain compliance documentation for a minimum of five years

### 10.2 Annual Board Reporting

- [ ] Prepare the annual report from the Qualified Individual to the board/governing body covering:
  - [ ] Overall status of the information security program
  - [ ] Compliance with the Safeguards Rule
  - [ ] Material matters (incidents, audit findings, significant risks, vendor issues)
  - [ ] Recommendations for program changes
  - [ ] Budget and resource requirements
- [ ] Present the report to the board/governing body
- [ ] Document board acknowledgment and any directives
- [ ] Implement board-directed changes to the program

---

## Need Help with GLBA Compliance?

Petronella Technology Group, Inc. provides comprehensive GLBA compliance services, including Qualified Individual (virtual CISO) services, risk assessments, WISP development, penetration testing, and continuous monitoring.

**Call 919-348-4912** or visit [https://petronellatech.com/compliance/glba/](https://petronellatech.com/compliance/glba/) to schedule a free compliance assessment.

**Petronella Technology Group, Inc.**
5540 Centerview Dr. Suite 200, Raleigh, NC 27606
[https://petronellatech.com](https://petronellatech.com)

Last Reviewed: March 2026
