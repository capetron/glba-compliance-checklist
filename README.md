# GLBA Compliance Checklist

A comprehensive guide and actionable checklist for compliance with the Gramm-Leach-Bliley Act (GLBA) and the revised FTC Safeguards Rule. This resource covers financial institution requirements, nonpublic personal information (NPI) protection, the Qualified Individual requirement, information security program development, and the relationship between GLBA and NIST SP 800-53.

Maintained by [Petronella Technology Group, Inc.](https://petronellatech.com/compliance/glba/) (PTG), a compliance and cybersecurity firm led by Craig Petronella with 23+ years of experience helping financial institutions and businesses protect customer data.

## Table of Contents

- [What Is GLBA?](#what-is-glba)
- [Who Must Comply with GLBA?](#who-must-comply-with-glba)
- [The Three Components of GLBA](#the-three-components-of-glba)
- [The Revised FTC Safeguards Rule (2023)](#the-revised-ftc-safeguards-rule-2023)
- [Key GLBA Requirements](#key-glba-requirements)
- [What Is Nonpublic Personal Information (NPI)?](#what-is-nonpublic-personal-information-npi)
- [The Qualified Individual Requirement](#the-qualified-individual-requirement)
- [How GLBA Relates to NIST SP 800-53](#how-glba-relates-to-nist-sp-800-53)
- [GLBA vs. Other Frameworks](#glba-vs-other-frameworks)
- [GLBA Compliance Checklist](#glba-compliance-checklist-1)
- [Common GLBA Compliance Challenges](#common-glba-compliance-challenges)
- [Penalties for GLBA Violations](#penalties-for-glba-violations)
- [Frequently Asked Questions](#frequently-asked-questions)
- [About Craig Petronella and PTG](#about-craig-petronella-and-ptg)
- [Additional Resources](#additional-resources)

## What Is GLBA?

The Gramm-Leach-Bliley Act (GLBA), also known as the Financial Modernization Act of 1999 (Public Law 106-102, 15 U.S.C. 6801-6809), is a federal law that requires financial institutions to explain their information-sharing practices to their customers and to safeguard sensitive data. GLBA was enacted on November 12, 1999, and fundamentally changed the financial services industry by allowing commercial banks, investment banks, securities firms, and insurance companies to consolidate.

As a condition of this consolidation, Congress included critical consumer privacy and data security provisions. The core principle of GLBA is straightforward: financial institutions have an obligation to protect the security, confidentiality, and integrity of their customers' nonpublic personal information (NPI).

GLBA is enforced by multiple federal agencies depending on the type of financial institution. The Federal Trade Commission (FTC) enforces GLBA for non-bank financial institutions, including mortgage brokers, tax preparers, automobile dealers, payday lenders, real estate settlement companies, and other entities. Federal banking regulators (OCC, FDIC, Federal Reserve, NCUA) enforce GLBA for their respective institutions.

The FTC's Safeguards Rule (16 CFR Part 314), originally issued in 2003 and substantially revised in October 2021 with an effective date of June 9, 2023, provides the most detailed and prescriptive implementation requirements for GLBA's information security provisions. The revised Safeguards Rule transformed GLBA compliance from a flexible, principles-based approach to a more prescriptive, specific set of requirements that closely mirror established cybersecurity frameworks.

## Who Must Comply with GLBA?

GLBA defines "financial institution" broadly. It applies to any institution that is "significantly engaged" in financial activities as defined by the Bank Holding Company Act. This includes many businesses that do not consider themselves traditional financial institutions:

### Clearly Covered Entities
- Banks, credit unions, and savings institutions
- Securities firms, broker-dealers, and investment advisors
- Insurance companies and agencies
- Mortgage lenders and brokers
- Finance companies and consumer lending firms

### Less Obvious Covered Entities
- **Tax preparation firms**: Businesses that prepare tax returns for consumers
- **Automobile dealers**: Dealers that arrange financing or leasing for customers
- **Real estate settlement companies**: Title companies and settlement agents
- **Payday lenders and check cashers**: Short-term lending and check cashing businesses
- **Wire transfer services**: Companies providing money transfer services
- **Collection agencies**: Firms that collect debts for financial institutions
- **Credit counseling services**: Organizations providing financial advice and debt management
- **Accountants and CPAs**: When providing financial advisory or tax services
- **Financial technology (fintech) companies**: Companies offering financial products or services through technology platforms
- **Higher education institutions**: Colleges and universities that process student financial aid (Title IV funds)

The FTC's Safeguards Rule applies to all financial institutions under FTC jurisdiction that are not regulated by another federal agency. If you are unsure whether your organization qualifies as a financial institution under GLBA, consult legal counsel.

## The Three Components of GLBA

GLBA contains three principal rules that, together, create a comprehensive framework for consumer financial privacy and data security:

### 1. The Financial Privacy Rule (Regulation P, 12 CFR Part 1016)

The Privacy Rule governs how financial institutions collect, use, and share consumers' NPI. Key requirements include:

- Provide initial privacy notices at the time of establishing a customer relationship
- Provide annual privacy notices to existing customers (with limited exceptions after a 2015 amendment)
- Clearly describe information-sharing practices and consumer opt-out rights
- Honor consumer opt-out requests for sharing NPI with non-affiliated third parties
- Implement reasonable policies to prevent unauthorized access during the notice process

### 2. The Safeguards Rule (16 CFR Part 314)

The Safeguards Rule requires financial institutions to develop, implement, and maintain a comprehensive information security program. The revised 2023 Safeguards Rule significantly expanded these requirements (detailed in the next section).

### 3. The Pretexting Provisions (15 U.S.C. 6821-6827)

The pretexting provisions prohibit the practice of obtaining customer information from a financial institution under false pretenses. This includes:

- Using fraudulent statements or forged documents to obtain customer information
- Impersonating a customer to obtain account information
- Using stolen or fraudulently obtained documents to access customer information

## The Revised FTC Safeguards Rule (2023)

The FTC issued a substantially revised Safeguards Rule in October 2021 (effective June 9, 2023) that replaced the original 2003 rule's flexible, principles-based approach with specific, prescriptive requirements. The revised rule applies to all financial institutions under FTC jurisdiction (non-bank financial institutions). Organizations with fewer than 5,000 customer records are exempt from some (but not all) of the new requirements.

### Nine Core Elements of the Revised Safeguards Rule

The revised Safeguards Rule requires covered financial institutions to:

1. **Designate a Qualified Individual** to oversee and implement the information security program
2. **Conduct a written risk assessment** that identifies reasonably foreseeable risks to NPI and assesses the sufficiency of safeguards
3. **Design and implement safeguards** to control the risks identified in the risk assessment, including:
   - Access controls for information systems
   - Inventory of data, personnel, devices, systems, and facilities
   - Encryption of NPI in transit and at rest
   - Multi-factor authentication for accessing information systems
   - Secure development practices for in-house applications
   - Disposal procedures for NPI no longer needed
   - Change management procedures
   - Monitoring and logging of information system activity
4. **Regularly test and monitor** the effectiveness of safeguards through continuous monitoring or annual penetration testing and semi-annual vulnerability assessments
5. **Implement security awareness training** for all personnel, with specialized training for security personnel
6. **Monitor service providers** that handle NPI, including contractual requirements and periodic assessments
7. **Keep the information security program current** as risks, technology, and business operations change
8. **Create a written incident response plan** covering how to respond to security events
9. **Report to the board of directors** (or equivalent governing body) annually on the overall status of the information security program

## Key GLBA Requirements

### Written Information Security Program (WISP)

Every covered financial institution must develop, implement, and maintain a Written Information Security Program. The WISP must be appropriate to the size and complexity of the institution, the nature and scope of its activities, and the sensitivity of the customer information it handles. The WISP must address:

- Administrative safeguards (policies, procedures, employee management)
- Technical safeguards (access controls, encryption, monitoring)
- Physical safeguards (facility access, workstation security, device disposal)

### Risk Assessment

The risk assessment must be written and must:

- Identify reasonably foreseeable internal and external threats to NPI
- Assess the likelihood and potential damage of those threats
- Evaluate the sufficiency of existing safeguards to control identified risks
- Be updated regularly (at least annually and after significant changes)

### Encryption Requirements

The revised Safeguards Rule specifically requires encryption of NPI:

- Data in transit over external networks must be encrypted
- Data at rest must be encrypted
- If encryption is not feasible for data at rest, alternative compensating controls must be documented and approved by the Qualified Individual

### Multi-Factor Authentication

The revised rule requires MFA for any individual accessing information systems that contain NPI. MFA must use at least two of the following factor types:

- Something you know (password, PIN)
- Something you have (token, smart card, mobile device)
- Something you are (biometric)

### Incident Response Plan

Financial institutions must develop a written incident response plan that addresses:

- Goals and roles/responsibilities of the incident response team
- Internal processes for responding to security events
- Communication and notification procedures
- Remediation and documentation requirements
- Revision procedures based on lessons learned

### Service Provider Oversight

Financial institutions must take reasonable steps to ensure that service providers maintain appropriate safeguards for NPI. This includes:

- Contractual requirements for service providers to implement safeguards
- Periodic assessment of service provider compliance
- Due diligence in selecting service providers

## What Is Nonpublic Personal Information (NPI)?

NPI is the category of data that GLBA protects. It includes:

### Personally Identifiable Financial Information
- Account numbers, balances, and transaction history
- Income, credit history, and credit scores
- Social Security numbers when associated with financial records
- Tax return information
- Insurance claim information

### Information Derived from Financial Transactions
- Lists of customers derived from financial records
- Information collected through cookies or other tracking technologies on financial service websites
- Information from applications (loan applications, insurance applications, account opening forms)

### NPI Does NOT Include
- Publicly available information (phone directories, government records, widely distributed media)
- Information that does not identify a specific consumer
- Aggregate or de-identified data that cannot be linked to a specific individual

## The Qualified Individual Requirement

The revised Safeguards Rule requires every covered financial institution to designate a "Qualified Individual" responsible for overseeing, implementing, and enforcing the information security program. Key aspects:

- The Qualified Individual does not need a specific certification or degree, but must have the knowledge and experience necessary to develop and oversee the program
- The Qualified Individual can be an employee or an outsourced service provider (such as a virtual CISO)
- If outsourced, the financial institution retains ultimate responsibility for compliance
- The Qualified Individual must report to the board of directors (or equivalent) annually
- The report must cover the overall status of the information security program, compliance with the Safeguards Rule, material matters related to the program, and recommendations for changes

PTG provides Qualified Individual (virtual CISO) services for financial institutions that lack in-house security expertise, leveraging AI-powered compliance tools to provide comprehensive oversight at a fraction of the cost of a full-time hire.

## How GLBA Relates to NIST SP 800-53

The revised FTC Safeguards Rule was intentionally designed to align with established cybersecurity frameworks, and NIST SP 800-53 provides the most comprehensive control catalog that maps to GLBA requirements:

- **The FTC has stated** that the revised Safeguards Rule draws on the NIST Cybersecurity Framework (CSF), which itself maps to NIST SP 800-53. Organizations that implement the NIST CSF or SP 800-53 controls will find significant overlap with GLBA requirements.
- **Risk Assessment** (GLBA) maps to the Risk Assessment (RA) family in NIST SP 800-53, including RA-3 (Risk Assessment) and RA-5 (Vulnerability Monitoring and Scanning).
- **Access Controls** (GLBA) map to the Access Control (AC) family, including AC-2 (Account Management), AC-3 (Access Enforcement), AC-6 (Least Privilege), and AC-17 (Remote Access).
- **Encryption** (GLBA) maps to the System and Communications Protection (SC) family, including SC-8 (Transmission Confidentiality and Integrity), SC-13 (Cryptographic Protection), and SC-28 (Protection of Information at Rest).
- **Multi-Factor Authentication** (GLBA) maps to the Identification and Authentication (IA) family, including IA-2 (Identification and Authentication), specifically IA-2(1) (Multi-Factor Authentication to Privileged Accounts) and IA-2(2) (Multi-Factor Authentication to Non-Privileged Accounts).
- **Monitoring and Testing** (GLBA) maps to the Audit and Accountability (AU) family and the Assessment, Authorization, and Monitoring (CA) family in NIST SP 800-53.
- **Incident Response** (GLBA) maps to the Incident Response (IR) family, including IR-1 (Incident Response Policy and Procedures), IR-4 (Incident Handling), IR-5 (Incident Monitoring), and IR-8 (Incident Response Plan).
- **Service Provider Oversight** (GLBA) maps to the Supply Chain Risk Management (SR) family, including SR-1 (Supply Chain Risk Management Policy and Procedures) and SR-6 (Supplier Assessments and Reviews).

PTG's AI-powered compliance tools automate the mapping between GLBA Safeguards Rule requirements and NIST SP 800-53 controls, enabling organizations that have already implemented NIST controls to rapidly demonstrate GLBA compliance.

## GLBA vs. Other Frameworks

| Feature | GLBA/Safeguards Rule | HIPAA Security Rule | PCI DSS 4.0 | SOC 2 |
|---|---|---|---|---|
| Governing Body | FTC / Federal banking regulators | HHS/OCR | PCI SSC | AICPA |
| Applicability | Financial institutions | Healthcare entities/BAs | Card payment processors | Service organizations |
| Protected Data | NPI (financial data) | PHI (health data) | CHD (cardholder data) | Per Trust Service Criteria |
| Risk Assessment | Required (written) | Required | Required | Required |
| Encryption | Required (transit + at rest) | Addressable | Required | Per criteria |
| MFA | Required | Not explicitly required | Required | Per criteria |
| Qualified Individual | Required | Security Officer required | Not specified | Not specified |
| Incident Response Plan | Required (written) | Required | Required | Required |
| Penetration Testing | Annual (or continuous monitoring) | Not explicitly required | Annual + semi-annual | Per criteria |
| Board Reporting | Annual report required | Not required | Not required | Not required |
| Based on NIST | Aligned with NIST CSF | Mapped via NIST SP 800-66 | Crosswalks to NIST | Crosswalks to NIST |

## GLBA Compliance Checklist

See the detailed [compliance-checklist.md](compliance-checklist.md) file in this repository for a comprehensive, actionable checklist. Key areas include:

1. **Determine Applicability**: Confirm your organization qualifies as a financial institution under GLBA
2. **Designate a Qualified Individual**: Appoint an internal resource or outsource to a virtual CISO
3. **Conduct a Risk Assessment**: Identify and document threats to NPI
4. **Develop the WISP**: Create a Written Information Security Program
5. **Implement Technical Safeguards**: Encryption, MFA, access controls, monitoring
6. **Privacy Notices**: Develop and distribute customer privacy notices
7. **Service Provider Management**: Contractual requirements and oversight
8. **Training**: Security awareness for all personnel
9. **Incident Response**: Develop and test the written incident response plan
10. **Board Reporting**: Annual report on the information security program

## Common GLBA Compliance Challenges

### Challenge 1: Determining Coverage

Many businesses do not realize they qualify as "financial institutions" under GLBA's broad definition. Tax preparers, auto dealers, real estate settlement companies, and even some retailers offering financing are covered. PTG helps organizations determine their GLBA obligations and scope the compliance effort appropriately.

### Challenge 2: The Qualified Individual Requirement

The revised Safeguards Rule requires a Qualified Individual to oversee the information security program. For small and mid-size financial institutions, hiring a full-time CISO is often cost-prohibitive. PTG provides virtual CISO services that satisfy the Qualified Individual requirement, backed by AI-powered monitoring and compliance tools that deliver enterprise-grade oversight.

### Challenge 3: Encryption Implementation

The encryption requirements in the revised Safeguards Rule, particularly for data at rest, can be technically challenging for organizations with legacy systems, on-premise databases, and complex data architectures. PTG's patented technology stack helps organizations implement encryption across diverse environments while maintaining operational functionality.

### Challenge 4: Vendor Management at Scale

Financial institutions often work with dozens or hundreds of service providers that handle NPI. Assessing each vendor's security posture, maintaining contractual requirements, and conducting periodic reviews is a significant operational burden. PTG's AI-powered compliance tools automate vendor risk assessments and continuously monitor third-party security posture.

### Challenge 5: Annual Penetration Testing

The revised Safeguards Rule requires annual penetration testing and semi-annual vulnerability assessments (unless continuous monitoring is implemented). Many small financial institutions lack the internal expertise to manage penetration testing engagements effectively. PTG provides both penetration testing services and continuous monitoring solutions.

## Penalties for GLBA Violations

GLBA violations carry significant consequences:

- **Institutional Penalties**: Financial institutions can be fined up to $100,000 per violation
- **Individual Penalties**: Officers and directors can be fined up to $10,000 per violation
- **Criminal Penalties**: Knowing and intentional violations can result in up to 5 years imprisonment
- **FTC Enforcement Actions**: The FTC can bring enforcement actions under Section 5 of the FTC Act for unfair or deceptive practices, resulting in consent orders, ongoing monitoring, and substantial remediation costs
- **State Attorney General Actions**: State AGs can bring civil actions on behalf of residents for GLBA violations
- **Reputational Damage**: Public enforcement actions and data breaches erode customer trust in financial institutions

The FTC has been increasingly active in GLBA enforcement since the revised Safeguards Rule took effect. Recent enforcement actions have targeted financial institutions for failures in risk assessment, access controls, encryption, and vendor management.

## Frequently Asked Questions

**Q: Does GLBA apply to my business if we are not a bank?**
A: GLBA applies to all "financial institutions," which is defined broadly to include any entity "significantly engaged" in financial activities. This includes tax preparers, auto dealers that arrange financing, mortgage brokers, payday lenders, real estate settlement companies, collection agencies, and many other businesses. If you handle customers' financial information as part of a financial product or service, you are likely covered.

**Q: What changed with the revised FTC Safeguards Rule in 2023?**
A: The revised rule, effective June 9, 2023, added specific requirements that the original 2003 rule did not include: designation of a Qualified Individual, written risk assessments, encryption of NPI in transit and at rest, multi-factor authentication, annual penetration testing (or continuous monitoring), a written incident response plan, and annual reporting to the board of directors.

**Q: Can I outsource the Qualified Individual role?**
A: Yes. The revised Safeguards Rule explicitly permits outsourcing the Qualified Individual role to a third-party service provider. However, the financial institution retains ultimate responsibility for compliance. The outsourced Qualified Individual must still provide the annual board report and maintain appropriate oversight of the information security program.

**Q: Do I need to encrypt all customer data at rest?**
A: The revised Safeguards Rule requires encryption of customer information at rest. If encryption of data at rest is "infeasible," you must document the alternative compensating controls and have the Qualified Individual approve them in writing. However, "infeasible" sets a high bar; simply being inconvenient or expensive does not qualify.

**Q: How often must I conduct a risk assessment?**
A: The revised Safeguards Rule requires a written risk assessment but does not specify a frequency beyond keeping it current. Best practice, and the approach recommended by the FTC, is to update the risk assessment at least annually and after any significant change in business operations, technology, or threat landscape.

**Q: What are the privacy notice requirements?**
A: Financial institutions must provide an initial privacy notice when establishing a customer relationship and, in some cases, annual privacy notices. The notice must describe the categories of NPI collected, categories of NPI disclosed, categories of third parties to whom NPI is disclosed, and the consumer's right to opt out of certain disclosures. A 2015 amendment allows institutions that do not share NPI with non-affiliated third parties to use a simplified annual notice process.

**Q: Does GLBA require penetration testing?**
A: The revised Safeguards Rule requires either (a) annual penetration testing and semi-annual vulnerability assessments or (b) continuous monitoring in lieu of periodic testing. Organizations with fewer than 5,000 customer records are exempt from this specific requirement but must still implement reasonable safeguards.

**Q: How does GLBA interact with state data privacy laws?**
A: GLBA generally preempts state laws only to the extent those laws are inconsistent with GLBA. Many states have their own data breach notification laws, financial privacy laws, and cybersecurity requirements that apply in addition to GLBA. New York's Department of Financial Services (DFS) Cybersecurity Regulation (23 NYCRR 500) is a notable example of a state rule that exceeds GLBA requirements for financial institutions.

## About Craig Petronella and PTG

This checklist is maintained by **Craig Petronella**, founder of Petronella Technology Group, Inc. Craig brings deep expertise to compliance consulting:

- **CMMC Registered Practitioner** (RP)
- **Licensed Digital Forensic Examiner** (#604180)
- **Cisco CCNA, CWNE** certified
- **MIT Artificial Intelligence Certificate** holder
- **Amazon #1 Best-Selling Author** of 14+ cybersecurity books
- **23+ years in cybersecurity**, helping organizations of all sizes achieve and maintain compliance

### Why PTG for GLBA Compliance?

**AI-Powered Compliance**: PTG uses its own private AI fleet, including on-premise LLMs and custom GPU infrastructure, to accelerate GLBA compliance assessments, automate risk assessments, and continuously monitor security posture. No other firm in the Triangle has this capability.

**Patented Technology Stack**: PTG's proprietary and patented security tools automate what competitors do manually, from risk assessments to vendor management to continuous monitoring, dramatically reducing the cost of GLBA compliance.

**Licensed Digital Forensic Examiner**: When a security incident occurs, PTG has the forensic expertise to investigate, preserve evidence, and support regulatory response. Craig Petronella's digital forensic license (#604180) ensures investigations meet evidentiary standards required by regulators and courts.

**Virtual CISO / Qualified Individual Services**: PTG provides outsourced Qualified Individual services that satisfy the revised Safeguards Rule requirement, backed by AI-powered tools that deliver enterprise-grade oversight at a fraction of the cost of a full-time CISO.

**AI + Cybersecurity Combined**: PTG is one of the only firms that combines AI development (custom AI agents, private LLMs, GPU hosting) with cybersecurity and compliance. This unique combination enables PTG to deploy AI-powered monitoring and automation that traditional compliance firms cannot offer.

**Fleet Infrastructure**: PTG's on-premise AI infrastructure (GPU clusters, private cloud) demonstrates that financial data can be processed securely without relying on third-party cloud environments.

**SMB Focus**: PTG makes enterprise-grade compliance accessible to small and mid-size financial institutions that face the same GLBA obligations as large banks.

### Get Started

Call **919-348-4912** or visit [https://petronellatech.com/compliance/glba/](https://petronellatech.com/compliance/glba/) to schedule a free GLBA compliance assessment.

Explore PTG's full compliance service offerings at [https://petronellatech.com/compliance/packages/](https://petronellatech.com/compliance/packages/).

## Additional Resources

- [Gramm-Leach-Bliley Act (15 U.S.C. 6801-6809)](https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title15-chapter94A)
- [FTC Safeguards Rule (16 CFR Part 314)](https://www.ecfr.gov/current/title-16/chapter-I/subchapter-C/part-314)
- [FTC Safeguards Rule Compliance Guide](https://www.ftc.gov/business-guidance/resources/ftc-safeguards-rule-what-your-business-needs-know)
- [FTC Financial Privacy Rule (16 CFR Part 313)](https://www.ecfr.gov/current/title-16/chapter-I/subchapter-C/part-313)
- [NIST Cybersecurity Framework 2.0](https://www.nist.gov/cyberframework)
- [NIST SP 800-53 Rev. 5](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)
- [PTG NIST SP 800-53 Guide](https://petronellatech.com/compliance/nist-800-53-compliance/)
- [PTG SOC 2 Compliance Guide](https://petronellatech.com/compliance/soc-compliance/)
- [PTG HIPAA Guide](https://petronellatech.com/hipaa/)
- [PTG Compliance Services](https://petronellatech.com/compliance/)
- [PTG AI Services](https://petronellatech.com/ai/)
- [PTG Cybersecurity Services](https://petronellatech.com/cybersecurity/)

## About Petronella Technology Group, Inc.

**Petronella Technology Group, Inc.**
5540 Centerview Dr. Suite 200
Raleigh, NC 27606
Phone: 919-348-4912
Web: [https://petronellatech.com](https://petronellatech.com)

PTG provides cybersecurity, compliance, AI, and managed IT services to organizations nationwide. With a unique combination of AI-powered compliance automation, patented security tools, and licensed digital forensic expertise, PTG helps financial institutions and businesses achieve and maintain compliance with GLBA, SOC 2, HIPAA, PCI DSS, NIST, and other frameworks.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

Last Reviewed: March 2026
