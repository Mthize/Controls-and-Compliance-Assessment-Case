# Controls and Compliance Assessment

## Case Study

This is based on a fictional company:

**PlayTech Innovations** is a U.S.-based company that develops and sells innovative toys. With its main office serving as a storefront, warehouse, and business hub, PlayTech Innovations has expanded its online presence, attracting both U.S. and international customers. As the company's IT department faces increasing pressure to support a growing online market, the IT manager recognizes the need for a comprehensive internal IT audit. This audit aims to enhance business continuity, compliance, and security posture amid the company's growth.

## Scenario

**PlayTech Innovations: Scope, Goals, and Risk Assessment Report**

### Scope

The audit will cover the entire security program at PlayTech Innovations. This includes assessing all assets and internal processes related to implementing controls and compliance best practices.

### Goals

- Assess existing assets and complete a controls and compliance checklist.
- Identify necessary controls and best practices to enhance PlayTech Innovations’ security posture.

### Current Assets

- On-premises equipment: office business needs
- Employee equipment: desktops/laptops, smartphones, remote workstations, peripherals
- Storefront products: retail and online sales; warehouse storage
- Systems, software, and services: accounting, telecommunication, database, security, ecommerce, inventory management
- Internet access
- Internal network
- Data retention and storage
- Legacy systems maintenance

### Risk Assessment

#### Risk Description

The company faces inadequate asset management and lacks comprehensive controls, potentially leading to non-compliance with U.S. and international regulations.

#### Control Best Practices

The NIST Cybersecurity Framework (CSF) emphasizes the **Identify** function. PlayTech Innovations needs to focus resources on asset identification, classification, and impact assessment to ensure business continuity and effective risk management.

#### Risk Score

Risk score: **8/10**. This high score reflects a significant gap in controls and compliance best practices.

#### Additional Comments

- **Potential Impact**: Medium risk due to insufficient asset identification.
- **Regulatory Risk**: High risk due to incomplete adherence to compliance regulations.

## Controls Assessment Checklist

| Yes / No / ? | Control                 | Explanation                                                                                           |
|--------------|--------------------------|-------------------------------------------------------------------------------------------------------|
| No           | Least Privilege          | Employees have excessive access to customer data. Restrict access to reduce breach risks.              |
| No           | Disaster Recovery Plan   | No plan in place. Implement a plan to ensure business continuity in case of disaster.                 |
| Yes          | Firewall                 | Firewall is active with defined security rules.                                                      |
| ?            | Password Policies        | Existing policies are weak. Strengthen password requirements to enhance identity management.          |
| Yes          | Antivirus                | Antivirus software is active and monitored regularly.                                                 |
| No           | Backups                  | No backup plan in place. Implement incremental, full, or partial backups to prepare for breaches.      |
| No           | Encryption               | Encryption is needed to protect data confidentiality.                                                 |
| No           | IDS                      | An Intrusion Detection System (IDS) is required to detect potential intrusions.                       |
| Yes          | Storefront Security      | Storefront has sufficient locks, though IT team is not responsible for management.                    |
| Yes          | CCTV                     | CCTV systems are operational and monitored.                                                           |
| Yes          | Fire Detection           | Fire detection systems are in place but need regular maintenance and an established usage plan.       |

## Compliance Checklist

### Payment Card Industry Data Security Standard (PCI DSS)

| Yes / No / ? | Best Practice                                     | Explanation                                                                      |
|--------------|----------------------------------------------------|----------------------------------------------------------------------------------|
| No           | Access Control                                    | Unauthorized access to customer credit card data. Restrict access to authorized personnel only. |
| No           | Secure Storage of Credit Card Information         | Credit card data is not encrypted, violating PCI DSS regulations.                |
| No           | Encryption                                        | Encryption protocols are not implemented.                                        |

### GDPR

| Yes / No / ? | Best Practice                                     | Explanation                                                                      |
|--------------|----------------------------------------------------|----------------------------------------------------------------------------------|
| No           | EU Customer Data Protection                       | GDPR practices are not applied, risking potential fines.                         |
| Yes          | Privacy Policies                                  | Privacy policies are properly maintained.                                        |

### System and Organization Controls (SOC)

| Yes / No / ? | Best Practice                                     | Explanation                                                                      |
|--------------|----------------------------------------------------|----------------------------------------------------------------------------------|
| No           | User Access Policies                              | Access policies are not established. Employees have excessive access to internal data. |
| Yes          | Data Integrity                                    | Data integrity measures are in place and maintained.                             |
| No           | Authorized Data Access                            | All employees have unrestricted access to data. Implement access controls.        |

## Recommendations

After evaluating PlayTech Innovations’ security posture, the following improvements are recommended:

1. **Implement Least Privilege Access**: Restrict access to sensitive data.
2. **Develop a Disaster Recovery Plan**: Ensure business continuity.
3. **Enhance Password Policies**: Strengthen password requirements.
4. **Deploy Encryption**: Protect data confidentiality.
5. **Establish Backup Procedures**: Implement a robust backup strategy.
6. **Introduce an IDS**: Monitor and detect potential security incidents.

To address compliance gaps, PlayTech Innovations must update their policies, implement recommended controls, and ensure adherence to regulatory requirements to improve their security posture.
