<h1>PCI DSS Tabletop Exercise – Simulated Cardholder Data Breach</h1>

<h2>Description</h2>

I designed and led a PCI DSS 12.10 tabletop exercise simulating a malware-driven payment card data breach across multiple POS terminals. The goal was to validate the organization's readiness to detect, contain, and recover from a cardholder data compromise while meeting PCI DSS incident response requirements.

<h2>Exercise Phases & My Contributions</h2>

- **Identification:** Guided the team through validating SIEM alerts, memory scraping indicators, and potential PAN/CVV data exposure.

- **Containment:** Directed immediate POS isolation at affected stores, implemented fallback payment systems, and coordinated with store managers to minimize business disruption.

- **Eradication:** Oversaw forensic scanning, system reimaging, patching of outdated services, and enterprise-wide credential resets.

- **Recovery:** Enforced clean image restoration, monitored for anomalies, and staged system reintroduction under strict change control.

- **Communication Protocols:** Structured notification flows to card brands, acquiring banks, regulators, customers, and internal staff, aligned with PCI DSS and legal timelines.


<h2>After-Action Findings </h2>

- Delays in escalation from SIEM to analyst review.<br>
- Confusion on responsibility for notifying card brands.<br>
- Store staff lacked clear escalation contacts for POS isolation.<br>
- No pre-arranged PCI Forensic Investigator (PFI) contract.

<h2>Results & Impact</h2>

- Strengthened Target’s PCI DSS 4.0 incident response maturity.<br>
- Reduced detection-to-escalation gaps by defining escalation playbooks.<br>
- Improved communication speed and clarity across business, legal, and technical teams.<br>
- Ensured Target is better positioned to protect customers, meet compliance obligations, and safeguard brand reputation.

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
