# Crime, Conflicts and Espionage in Cyberspace
[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This is a graduate course providing an introduction to some topics in the areas of crime, espionage and conflicts in cyberspace. The material is used for the _"Cybercrime, Cyberespionage, and Cyberwar"_ course currently taught in the [Master in Cybersecurity](https://www.uc3m.es/master/cybersecurity) at [UC3M](https://www.uc3m.es/Home).

The course provides a gentle, not very technical introduction to various current security and privacy topics, including
* some bits of history,
* opponents and the current cyberthreat landscape,
* the underground economy of cybercrime,
* surveillance, including commercial surveillance, and
* the security of industrial control systems and IoT devices.

The main goal of the course is to provide students who approach cybersecurity with little-to-none previous backgound with a socio-techno-economic perspective of current security and privacy phenomena in the Internet, how we got here, and what might be done about it. The treatment of some topis might be too superficial for some audiences or might miss some key topics. The material can be extended with some extra effort to make up for these limitations.

---
**jet: revise this**

For each topic, this repository contains:
* A **contents file** providing a description of the contents covered in the topic and links to supplemental material
* A **problem set** to reinforce knowledge and skills
* A **slide deck** used for presentations during lectures and labs 

There is also a set of [labs](https://github.com/0xjet/sec101/tree/main/labs) that are used as part of the assessment (see details below).
---




**[jet] ADAPT EVERYTHING BELOW*




## Syllabus

* Module 1. Introduction to Cybersecurity
    * What is cybersecurity?
    * The CIA Triad
    * Vulnerabilities, Threats, Risks, and Controls
    * Adversaries
    * Design Principles
    * Research Areas in Cybersecurity 

* Module 2. User Authentication
    * Authentication Factors
    * Passwords
    * Password Managers
    * Federated Identity

* Module 3. Access Control
    * The Protection Problem
    * Access Control Models
    * Access Control in Linux (I): Credentials and the Permission System:
    * Access Control in Linux (II): POSIX ACLs and Capabilities

* Module 4. Network Security
    * Communication Security 
    * TCP/IP Security
    * Network Discovery and Scanning
    * Web Security

* Module 5. Security Protocols: TLS
    * History and Design Goals
    * Cryptographic Background
    * The Handshake Protocol
    * The Record Protocol
    * Interception and Certificate Pining

* Module 6. Vulnerabilities
    * Vulnerability Types and Lifecycle
    * Vulnerability Numbering (CVE, CPE, CWE)
    * Vulnerability Scoring (CVSS)

* Module 7. Malware
    * Malicious Code
    * Malware Types
    * Malware Analysis Techniques
    * Case Studies

* Module 8. Cybersecurity Regulation
    * Computer Crime and the Law
    * The Cybersecurity Act
    * The NIS 2 Directive
    * The GDPR


## Schedule

The course is designed to be taught over one 14-week term, with two 2-hour sessions per week plus time off class for self-study and assessments. The computer is used pervasively throughout the course for both theory contents and labs. 

| *Session* | *Module*          | *Contents* |
| --------: | ----------------- | ---------- | 
| 1         | Introduction      | Cybersecurity. CIA. Vulnerabilities, threats, risks, controls. Adversaries. Principles |
| 2         | Introduction      | Threat modeling |
| 3         | Authentication    | User authentication. Factors. Passwords |
| 4         | Authentication    | Passwords in Linux. Breaking passwords |
| 5         | Authentication    | Password managers |
| 6         | Authentication    | Federated identity |
| 7         | Access Control    | Protection. Access control models |
| 8         | Access Control    | Linux credentials and the permission system |
| 9         | Access Control    | POSIX ACLs. Capabilities |
| 10        | Access Control    | Permission and ACL labs |
| 11        | Network Security  | Comms security. TCP/IP security |
| 12        | Network Security  | Analyzing traffic traces with wireshark |
| 13        | Network Security  | More TCP/IP security issues |
| 14        | Network Security  | Network discovery and port scanning |
| 15        | Network Security  | Web security|
| 16        | Network Security  | Basic web attacks. Authentication. XSS. Injection |
| 17        | TLS               | TLS goals. Design. Cryptographic background |
| 18        | TLS               | Certificates and certification authorities |
| 19        | TLS               | Handshake and record protocols |
| 20        | TLS               | Interception. Certificate pinning. Labs |
| 21        | Vulnerabilities   | Vulnerability types. Lifecycle. Numbering (CVE, CPE, CWE) |
| 22        | Vulnerabilities   | Scoring (CVSS). Labs |
| 23        | Malware           | Malicious code. Types |
| 24        | Malware           | Binary analysis tools. Reversing binaries |
| 25        | Malware           | Malware analysis |
| 26        | Malware           | Case studies and labs |
| 27        | Regulation        | Computer Crime. Cyberscurity Act. NIS 2 Directive |
| 28        | Regulation        | GDPR |



## Labs

The labs are small practical projects meant to help students gain skills in a topic and reinforce knowledge discussed in class. Each lab consists of a practical task that require some independent study and experimentation with one or a few tools. They are used as part of the course assessment.

| *Lab*                       | *Points* | *Available* | *Deadline* |
| --------------------------- | -------: | ----------- | ---------- |
| Threat modeling exercise    | 1        | Session 2   | 1 week     |
| Breaking passwords          | 1        | Session 4   | 2 weeks    |
| User permissions            | 1        | Session 8   | 2 weeks    |
| Analysis of pcap            | 0.5      | Session 12  | 1 week     |
| Network scanning            | 0.5      | Session 14  | 1 week     |
| Vulnerable web app          | 1        | Session 16  | 2 weeks    |
| CVE/CVSS lab                | 1        | Session 21  | 1 week     |
| Binary reversing (optional) | 1        | Session 24  | 1 week     |



## License

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg


## Contact

[Contact me](https://0xjet.github.io/) for any comments, questions or suggestions on this material.






---
MATERIAL TO BE MOVED ELSEWHERE (CYBERCRIME)

Check:
* Search for other uni courses on cybercrime, cyberthreats, etc.
    * https://www.cl.cam.ac.uk/teaching/2021/R254/materials.html
    * https://www.google.com/search?q=A+cybercrime+course&oq=A+cybercrime+course&aqs=chrome..69i57j69i60.1868j0j1&sourceid=chrome&ie=UTF-8
    * https://london.ac.uk/courses/cybercrime
    * https://www.udemy.com/course/introduction-to-cybercrime/?utm_source=adwords&utm_medium=udemyads&utm_campaign=CyberSecurity_v.PROF_la.EN_cc.ROW&utm_content=deal4584&utm_term=_._ag_120822692101_._ad_535397282079_._kw__._de_c_._dm__._pl__._ti_dsa-1187335280558_._li_2724_._pd__._&matchtype=b
    * https://www.cepol.europa.eu/tags/cybercrime
    * https://www.coursera.org/lecture/cyber-conflicts/introduction-to-cybercrime-and-fundamental-issues-xndSq
    * 
* https://ec.europa.eu/home-affairs/what-we-do/policies/cybercrime_en
* https://www.fbi.gov/investigate/cyber
* https://www.tandfonline.com/doi/pdf/10.1080/15614263.2018.1507888
* cyber-dependent and cyber-enabled:
    * https://www.bedfordshire.police.uk/information-and-services/Crime/Cyber-crime-and-online-safety/What-is-cyber-crime
    * https://www.cps.gov.uk/legal-guidance/cybercrime-prosecution-guidance
    * https://www.victims-first.org.uk/crime-info/guidance-and-support/cyber-crime/
    * https://www.unodc.org/unodc/en/cybercrime/global-programme-cybercrime.html 
* https://www.unodc.org/e4j/en/tertiary/cybercrime.html
    * https://www.unodc.org/e4j/en/cybercrime/module-1/index.html
    * https://www.unodc.org/e4j/en/cybercrime/module-2/key-issues/intro.html
* ENISA reports: https://www.enisa.europa.eu/topics/threat-risk-management?tab=articles
    * https://www.enisa.europa.eu/topics/threat-risk-management?tab=publications
    * 

---



