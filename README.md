# Awesome UAE GRC [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of United Arab Emirates **Governance, Risk & Compliance** resources: cybersecurity regulations, data protection laws, sector frameworks, regulators, tools, and communities.

<p>
  <i>قائمة مختارة لموارد الحوكمة والمخاطر والامتثال في دولة الإمارات</i>
</p>

![Link Check](https://github.com/mfgrcconsultant/awesome-uae-grc/actions/workflows/link-check.yml/badge.svg)
![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

**Maintained by** [Mohamed Faizal (MoFa)](https://github.com/mfgrcconsultant) · CISSP · CISM · CISA · CRISC · CIPP/E

> ⚠️ **Disclaimer:** This list is for awareness and education only. It is **not legal advice**. Always confirm current requirements with the official regulator. Laws and standards are updated regularly.

---

## Contents

- [Regulators and Authorities](#regulators-and-authorities)
- [Cybersecurity Frameworks and Standards](#cybersecurity-frameworks-and-standards)
- [Data Protection and Privacy](#data-protection-and-privacy)
- [Financial Services and Insurance](#financial-services-and-insurance)
- [Healthcare](#healthcare)
- [Business Continuity and Resilience](#business-continuity-and-resilience)
- [AI Governance](#ai-governance)
- [Cybercrime and Related Laws](#cybercrime-and-related-laws)
- [International Frameworks Commonly Mapped in the UAE](#international-frameworks-commonly-mapped-in-the-uae)
- [Open-Source GRC Tools](#open-source-grc-tools)
- [Communities and Events](#communities-and-events)
- [Related Projects](#related-projects)
- [Contributing](#contributing)

---

## Regulators and Authorities

### Federal

- [UAE Cyber Security Council](https://csc.gov.ae) - Federal body leading national cybersecurity strategy, policy, and incident coordination.
- [Telecommunications and Digital Government Regulatory Authority (TDRA)](https://tdra.gov.ae) - Regulator for telecoms and digital government services.
- [Central Bank of the UAE (CBUAE)](https://www.centralbank.ae) - Regulator for banks, finance companies, payment providers, and insurers.
- [Securities and Commodities Authority (SCA)](https://www.sca.gov.ae) - Federal regulator for capital markets.
- [National Emergency Crisis and Disaster Management Authority (NCEMA)](https://www.ncema.gov.ae) - Owner of the national business continuity standard.
- [UAE Legislation Portal](https://uaelegislation.gov.ae) - Official source for federal laws and decree-laws.
- [UAE Government Portal (u.ae)](https://u.ae) - Official government information portal, including digital and data policies.

### Emirate Level

- [Dubai Electronic Security Center (DESC)](https://www.desc.gov.ae) - Dubai government's cybersecurity authority.
- [Digital Dubai](https://www.digitaldubai.ae) - Dubai's digital transformation and data authority.
- [Department of Health – Abu Dhabi (DoH)](https://www.doh.gov.ae) - Abu Dhabi health regulator and owner of ADHICS.
- [Dubai Health Authority (DHA)](https://www.dha.gov.ae) - Dubai health regulator.
- [Virtual Assets Regulatory Authority (VARA)](https://www.vara.ae) - Dubai regulator for virtual assets.

### Financial Free Zones

- [Dubai International Financial Centre (DIFC)](https://www.difc.ae) - Home of the DIFC Commissioner of Data Protection.
- [Dubai Financial Services Authority (DFSA)](https://www.dfsa.ae) - Financial regulator for the DIFC.
- [Abu Dhabi Global Market (ADGM)](https://www.adgm.com) - Home of the ADGM Office of Data Protection and the FSRA.

---

## Cybersecurity Frameworks and Standards

- **UAE Information Assurance (IA) Standard** - National risk-based control framework, originally published by NESA, with management and technical control families. Commonly required for government entities and critical sectors. See the [UAE Cyber Security Council](https://csc.gov.ae).
- **Dubai Information Security Regulation (ISR)** - DESC's security regulation for Dubai government entities and related parties. See [DESC](https://www.desc.gov.ae).
- **ADHICS (Abu Dhabi Healthcare Information and Cyber Security Standard)** - Mandatory security standard for Abu Dhabi healthcare entities. See [Healthcare](#healthcare).
- **CBUAE Requirements** - Technology risk, outsourcing, and consumer protection expectations for licensed financial institutions. See the [CBUAE Rulebook](https://rulebook.centralbank.ae).

---

## Data Protection and Privacy

| Jurisdiction | Law | Regulator |
|---|---|---|
| Federal (onshore) | Federal Decree-Law No. 45 of 2021 on the Protection of Personal Data (PDPL) | UAE Data Office |
| DIFC | DIFC Data Protection Law No. 5 of 2020 | DIFC Commissioner of Data Protection |
| ADGM | ADGM Data Protection Regulations 2021 | ADGM Office of Data Protection |
| DHCC | DHCC Health Data Protection Regulation | Dubai Healthcare City Authority |

- [UAE Legislation Portal](https://uaelegislation.gov.ae) - Search for the official PDPL text.
- [DIFC Data Protection](https://www.difc.ae) - Law, regulations, guidance, and breach notification resources.
- [ADGM Office of Data Protection](https://www.adgm.com) - Regulations, guidance, and templates.

> 💡 **Tip:** Free zones have their own data protection regimes. Map which regime applies to each legal entity before starting a privacy program.

---

## Financial Services and Insurance

- [CBUAE Rulebook](https://rulebook.centralbank.ae) - Consolidated regulations for banks, insurers, and payment providers.
- [DFSA Rulebook](https://www.dfsa.ae) - Rules for DIFC-licensed firms, including technology and cyber risk.
- [ADGM FSRA](https://www.adgm.com) - Rules and guidance for ADGM-licensed firms.
- [SCA Regulations](https://www.sca.gov.ae) - Capital markets regulations.
- [VARA Rulebooks](https://www.vara.ae) - Technology and information security rules for virtual asset service providers.
- [PCI Security Standards Council](https://www.pcisecuritystandards.org) - PCI DSS for any entity handling card data.

---

## Healthcare

- [DoH Abu Dhabi](https://www.doh.gov.ae) - ADHICS standard, compliance guidance, and audit requirements.
- [DHA](https://www.dha.gov.ae) - Dubai health data and cybersecurity requirements.
- **Federal Law No. 2 of 2019** - Use of ICT in health fields, including health data localization. See the [UAE Legislation Portal](https://uaelegislation.gov.ae).

---

## Business Continuity and Resilience

- [NCEMA](https://www.ncema.gov.ae) - National Business Continuity Management Standard (NCEMA 7000).
- [ISO 22301](https://www.iso.org/standard/75106.html) - International BCM standard commonly mapped to NCEMA 7000.

---

## AI Governance

- [UAE Artificial Intelligence Office](https://ai.gov.ae) - National AI Strategy 2031, AI principles, and guidelines.
- [Digital Dubai](https://www.digitaldubai.ae) - Dubai AI ethics principles and guidelines.
- [ISO/IEC 42001](https://www.iso.org/standard/81230.html) - AI management system standard.
- [NIST AI RMF](https://www.nist.gov/itl/ai-risk-management-framework) - AI risk management framework.

---

## Cybercrime and Related Laws

- **Federal Decree-Law No. 34 of 2021** - Combating Rumours and Cybercrimes.
- **Federal Decree-Law No. 46 of 2021** - Electronic Transactions and Trust Services.
- Search both on the [UAE Legislation Portal](https://uaelegislation.gov.ae).

---

## International Frameworks Commonly Mapped in the UAE

- [ISO/IEC 27001:2022](https://www.iso.org/standard/27001) - Information security management system.
- [ISO/IEC 27701](https://www.iso.org/standard/71670.html) - Privacy information management.
- [NIST Cybersecurity Framework 2.0](https://www.nist.gov/cyberframework) - Risk-based cybersecurity framework.
- [CIS Critical Security Controls](https://www.cisecurity.org/controls) - Prioritized technical safeguards.
- [CSA Cloud Controls Matrix](https://cloudsecurityalliance.org/research/cloud-controls-matrix) - Cloud security controls.
- [GDPR](https://gdpr-info.eu) - EU regulation that influenced DIFC and ADGM laws.

---

## Open-Source GRC Tools

- [CISO Assistant](https://github.com/intuitem/ciso-assistant-community) - Open-source GRC platform with many built-in frameworks.
- [Microsoft Presidio](https://github.com/microsoft/presidio) - PII detection and anonymization. Extend it with UAE-specific recognizers.
- [NIST OSCAL](https://pages.nist.gov/OSCAL/) - Machine-readable format for control catalogs and assessments.
- [Compliance Trestle](https://github.com/IBM/compliance-trestle) - Tooling for compliance-as-code with OSCAL.
- [Checkov](https://github.com/bridgecrewio/checkov) - Infrastructure-as-code policy scanning.

---

## Communities and Events

- [GISEC Global](https://gisec.ae) - The region's largest annual cybersecurity event, held in Dubai.
- [ISACA](https://www.isaca.org) - Check for the UAE chapter for local events and CPEs.
- [ISC2](https://www.isc2.org) - Check for UAE chapters for local events and CPEs.
- [OWASP](https://owasp.org) - Check for UAE chapters for application security meetups.
- [Cloud Security Alliance](https://cloudsecurityalliance.org) - Check for the UAE chapter.

---

## Related Projects

- 🤖 [UAE GRC Claude Skills](https://github.com/mfgrcconsultant/uae-grc-claude-skills) - AI skills for UAE compliance tasks *(coming soon)*
- 🗺️ [UAE Control Crosswalk](https://github.com/mfgrcconsultant/uae-control-crosswalk) - Machine-readable UAE framework mappings *(coming soon)*
- 🔍 [UAE PII Patterns](https://github.com/mfgrcconsultant/uae-pii-patterns) - Detection rules for UAE identifiers *(coming soon)*

---

## Contributing

Contributions are welcome. Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the maintainer has waived all copyright and related rights to this list.
