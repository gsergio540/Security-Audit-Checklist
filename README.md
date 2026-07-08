# Security Audit Practice — Botium Toys (Simulated Small Business)

## Scenario
 Botium Toys is a small U.S.-based toy company operating out of a single physical location that serves as their office, storefront, and warehouse. Their online sales have grown significantly, now reaching customers both domestically and internationally including the European Union. This growth has put pressure on their IT department to scale securely.
The IT manager identified the need for an internal audit to strengthen the company's security posture as they expand, with a particular focus on maintaining compliance around online payment processing and E.U. business operations (relevant to GDPR). Using the NIST Cybersecurity Framework as a foundation, the manager defined an audit scope and goals, inventoried IT assets, and completed an initial risk assessment.
My task: Review the audit scope, goals, and risk assessment, then complete a controls and compliance checklist to identify security gaps and provide recommendations to reduce risk and support regulatory compliance.

## Objective
Complete an internal security controls and compliance checklist to 
identify gaps in Botium Toys' current security posture, with a focus 
on payment processing (PCI DSS) and E.U. operations (GDPR).

## Controls Assessment Checklist

| Control | In Place? |
|---|---|
| Least Privilege | No |
| Disaster Recovery Plans | No |
| Password Policies | Yes |
| Separation of Duties | No |
| Firewall | Yes |
| Intrusion Detection System (IDS) | No |
| Backups | No |
| Antivirus Software | Yes |
| Manual Monitoring/Maintenance for Legacy Systems | No |
| Encryption | No |
| Password Management System | No |
| Locks (Offices, Storefront, Warehouse) | Yes |
| Closed-Circuit Television (CCTV) Surveillance | Yes |
| Fire Detection/Prevention (Alarm, Sprinklers, etc.) | Yes |



## Findings
Botium Toys has decent physical security controls in place, but significant gaps exist in their technical and administrative security controls.

## Recommendations
 ### Improve
   - Establish IDS (Intrusion detection system)
   - Centralized password management system.
   - Utilize encryption for PII/SPII.
   - Implement a more complex password policy.
   - Implement access controls pertaining to least privilege and separation of duties. 
   - Establish disaster recovery plan and backups of critical data.

### Sustain
   - Availability and integrated controls for data integrity.
   - European Union 72 hour customer notfication plan in case of data breach.
   - Locks, CCTV surveillance, and functioning fire detection and prevention systems.


## Frameworks/Regulations Referenced
- NIST Cybersecurity Framework (CSF)
- PCI DSS (Payment Card Industry Data Security Standard)
- GDPR (General Data Protection Regulation)
