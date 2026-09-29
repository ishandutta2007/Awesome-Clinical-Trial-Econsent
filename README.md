# Awesome-Clinical-Trial-Econsent

## Top Clinical Trial eConsent Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Electronic Informed Consent, Patient Comprehension Verification, Regulatory Compliance & Remote Consenting*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Clinical Trial eConsent**. These tools help research sites, sponsors, and CROs digitize the informed consent process, verify participant comprehension, capture electronic signatures, and maintain audit-ready consent documentation in compliance with 21 CFR Part 11 and ICH-GCP.



**Examples** include Medidata eConsent, Veeva eConsent, Signant Health, Castor eConsent, THREAD, IQVIA eConsent, Florence eConsent, Clinion eConsent, TrialKit, Science37, Medable eConsent, Advarra eConsent, and Clario eConsent (the category leaders).



**Open-source emphasis**: Clinical trial eConsent has a **developing open-source ecosystem**. **gICS (generic Informed Consent Service)** is the most established open-source consent management tool, developed at University Medicine Greifswald, with **336,000+ consents and 2,400+ withdrawals** documented since 2014 . **OpenSpecimen** provides an eConsents module for research centers with IRB-formatted consent forms, versioning, and eSignature support . **REDCap** offers an Enhanced eConsent Framework with PDF snapshots, certification pages, and version control . This section documents these self-hostable solutions and the broader open-source consent management landscape.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Medidata eConsent](https://www.medidata.com/)**  

  Patient-friendly electronic informed consent and enrollment system within Medidata's Patient Cloud suite. Uses multimedia technology to educate participants on key trial elements. Supports onsite and remote consenting, 100% BYOD, and direct integration with Rave EDC, RTSM, and eCOA via iMedidata single sign-on . Reduces setup timelines from months to weeks and provides dedicated Patient Cloud Helpdesk support .



- **[Veeva eConsent](https://www.veeva.com/)**  

  Site-focused eConsent solution within Veeva SiteVault. Sites manage and capture signatures on electronic informed consent forms (eICFs), send and countersign completed forms, and upload paper-signed ICFs as certified copies . Participants receive eICFs via MyVeeva for Patients mobile and web applications. Reduces administrative burden and ensures compliance for sites and study teams .



- **[Advarra eConsent](https://www.advarra.com/)**  

  Site-specific eConsent module within Advarra's eRegulatory Management System. Designed to reduce audit risk and enhance participant engagement with 21 CFR Part 11 and HIPAA-compliant workflows . Features interactive multimedia (text, video, audio), knowledge assessments for comprehension verification, real-time consent progress tracking, remote consenting for participants and legally authorized representatives (LAR), and automatic re-consent notifications . Integrates with CIRBI IRB platform and Clinical Conductor/OnCore CTMS .



- **[THREAD eConsent](https://www.threadresearch.com/)**  

  Mobile-based eConsent accessible through iOS and Android with support for both BYOD and provisioned device approaches. Offers single-signature and dual-signature workflows with full compliance, audit trails, and reporting . Dual-signature option allows site teams and Principal Investigators to send ICFs to participants remotely during telehealth visits, phone calls, or in-clinic visits for real-time review and digital signature.



- **[Science 37 eConsent](https://www.science37.com/)**  

  eConsent module within Science 37's Metasite unified platform. Enables virtual electronic consent as part of end-to-end trial orchestration with ePRO, telemedicine, scheduling, and wearable integration . Patients participate from home using intuitive app-based processes with standardized workflows ensuring GCP compliance .



- **[Castor eConsent](https://www.castoredc.com/)**  

  eConsent module within Castor EDC platform. Provides electronic informed consent capture integrated with the broader Castor clinical data management ecosystem.



- **[Clinion eConsent](https://clinion.com/)**  

  eConsent module within Clinion's AI-powered clinical trial platform. Provides electronic consent capture, comprehension quizzes, and audit trails.



- **[TrialKit eConsent](https://www.trialkit.com/)**  

  eConsent capability within TrialKit's cloud-based clinical research platform. Provides flexible consent workflows and electronic signature capture.



- **[Medable eConsent](https://www.medable.com/)**  

  eConsent module within Medable's decentralized clinical trial platform. Provides patient-friendly electronic consent with multimedia education and BYOD support .



- **[Clario eConsent](https://clario.com/)**  

  eConsent module within Clario's clinical trial technology suite. Provides electronic informed consent integrated with eCOA and cardiac safety endpoints.



## Open-Source GitHub Projects



- **[gICS (generic Informed Consent Service)](https://github.com/miracum/icm-gics)**  

  **The most established open-source consent management tool** for research. Developed by the Institute for Community Medicine (ICM) at University Medicine Greifswald, Germany. Free-of-charge, open-source software facilitating digital informed consent management based on **IC modularisation**. Supports both electronic depiction of paper-based consents and fully electronic consents . **336,000+ informed consents and 2,400+ withdrawals documented since 2014**. Features fine-granular consents, differentiated consent states, and direct system-to-system exchange for automated data processing. Supports various research workflows. **Open source, free of charge** .



- **[OpenSpecimen eConsents Module](https://github.com/krishagni/openspecimen)**  

  eConsents module within OpenSpecimen, a biobanking and clinical research data management platform. Helps research centers collect **study-specific and broad-based consents**. Features include **IRB-approved format consent forms**, **eSignature support**, **consent form versioning**, **multiple language support**, tablet support with patient mode data entry, email consent form delivery, and reporting . The new mobile app enables offline data entry on Android devices for field specimen collection. **Open source**.



- **[REDCap Enhanced eConsent Framework](https://projectredcap.org/)**  

  REDCap's built-in **eConsent 2.0** framework (as of February 2025) provides comprehensive electronic consent capabilities. Major features include **eConsent framework configuration** via Designer (not Survey Settings), **consent form versioning** with historical audit trail, **PDF Snapshots** combining multiple forms and signatures into a single PDF, **end-of-survey certification page** displaying in-line PDF for participant verification before completion, **automatic archival of consent-specific PDF** to File Repository, and **optional inclusion of name/DOB** on PDF footer for identity documentation . Supports survey-based consent with eSignature fields and branching logic. **Free for non-profit organizations** through REDCap Consortium.



- **[REDCap Multi-Signature Consent](https://github.com/susom/multi-signature-consent)**  

  REDCap External Module that creates a **single PDF containing data from multiple REDCap forms**. Designed to merge **participant and coordinator consent signatures** into a single final PDF document. When defined logic is true, the module merges forms into a single PDF and optionally saves it to the file repository or a file-upload field . Can be coupled with Alert and Notification to send combined PDF to participants. **Open source** (REDCap External Module).



- **[Pryv.io](https://github.com/pryv/pryv.io)**  

  Personal data lifecycle management software recognized as a **Digital Public Good** by the Digital Public Goods Alliance (UN-endorsed initiative). Provides ready-to-use infrastructure for CROs and Pharma to design and run **decentralized, remote clinical trials** . Includes built-in **federated consent protocol** for cross-account messaging and consent flows between end-user accounts. The **RWD eConsent solution** enhances clinical trials with Real-World Data, achieving privacy compliance and improving patient engagement . **Open source**.



- **[Improved e-Consent Framework (Cincinnati Children's)](https://confluence.research.cchmc.org/)**  

  Documentation and configuration guidance for REDCap's Enhanced eConsent Framework, developed by Cincinnati Children's Hospital Medical Center. Provides detailed setup instructions for **eConsent 2.0** including PDF Snapshots, certification pages, version control, and optional identity fields (name, DOB) for consent documentation . The transition guide from eConsent 1.0 to 2.0 provides step-by-step migration instructions . **Documentation resource** for REDCap eConsent implementations.



### Additional Strong Open-Source Options



- **Consent Management Foundations**: **gICS** (336,000+ consents, modular IC management) , **Pryv.io** (Digital Public Good, federated consent) .

- **Research Platform eConsent**: **OpenSpecimen** (biobanking focus, IRB forms, eSignature) , **REDCap** (Enhanced eConsent 2.0, free for non-profits) .

- **REDCap Extensions**: **Multi-Signature Consent** (merge participant + coordinator signatures) , **Improved e-Consent Framework** (documentation and configuration guidance) .

- **Broader Consent Infrastructure**: **gICS** integration patterns for research networks, **Pryv.io** for personal data lifecycle in decentralized trials.



**Frameworks for building custom systems**: Combine **gICS** for modular, fine-grained consent management across research projects, **OpenSpecimen** or **REDCap** for study-specific eConsent with IRB-formatted forms and eSignatures, and **Pryv.io** for decentralized trial consent and personal data lifecycle management. Add **PostgreSQL/MySQL** for persistence and **Docker** for deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Clinical trial eConsent platforms handle sensitive participant health information; ensure compliance with 21 CFR Part 11, ICH-GCP, HIPAA, GDPR, and applicable regional regulations.

- **Open-source reality**: The open-source eConsent ecosystem is **developing but not yet equivalent to commercial platforms**. **gICS** provides mature modular consent management . **OpenSpecimen** and **REDCap** offer study-specific eConsent with eSignature support . However, commercial platforms (Medidata, Veeva, Advarra, THREAD) provide deeper integration with EDC/eCOA systems, multimedia comprehension tools, real-time remote monitoring, and dedicated patient helpdesks that open-source alternatives cannot match without significant custom development.



---



**Made for clinical research coordinators, site administrators, regulatory affairs teams, and clinical data managers.**

Let's make clinical trial consent more open, transparent, and patient-centered.
