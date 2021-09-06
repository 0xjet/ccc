# Cybercrime, Cyberespionage, and Cyberwar
[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]


**TBD EVERYTHING BELOW*

This is an graduate course providing an introduction to some topics in the areas of cybercrime, cyberespionage, and cyberwar. The material is used for the _Cybercrime, Cyberespionage, and Cyberwar (12395)_ course currently taught in the CS curriculum at UC3M.

The course covers user authentication, access control systems, network security, malware, vulnerabilities, and regulation. The purpose is to provide a gentle --though practical-- introduction to the main principles, concepts and tools in these topics. The course design aims at finding a good balance between breadth and depth of learning for a CS student who approaches cybersecurity with little-to-none previous backgound. As a result, the treatment of some topis is often very general, limited, and with some obvious omissions. The material can be extended with some extra effort to make up for these limitations.

For each topic, this repository contains:
* A **contents file** providing a description of the contents covered in the topic and links to supplemental material
* A **problem set** to reinforce knowledge and skills
* A **slide deck** used for presentations during lectures and labs 

There is also a set of [labs](https://github.com/0xjet/sec101/tree/main/labs) that are used as part of the assessment (see details below).


## Prerequisites

Parts of the course require the student to have some basic grasp of:
* Computer programming
* Operating systems
* Networking, especially TCP/IP
* Web systems
* Cryptography


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

