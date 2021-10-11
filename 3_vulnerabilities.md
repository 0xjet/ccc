# Module 3. The Vulnerability and Exploit Markets

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg


This module of the course on [Cybercrime, Cyberespionage and Cyberconflicts](https://github.com/0xjet/ccc) examines the topic of software vulnerabilites, their associated exploits, and the role they play in the cyberarms industry. The module first provides some foundational definitions on how vulnerabilities are numbered (CVE) and scored (CVSS). It then discusses the notion of zero-day vulnerability and the white/gray/black industries that emerged around them -- notably vulnerability reward ("bug bounty") programs and clandestine markets. Some key ideas about the dynamics of zero-day vulnerabilities are discussed using a 2017 RAND report that analyzes the life statuses, longevity, collision rate, and costs of a dataset of 200 0-day exploits spanning 14 years. The module concludes with an overview of the ethical conundrums of vulnerability -- and computer security -- research.

**Learning Outcomes**
* Understand the information available in a CVE entry.
* Know the CVSS scoring rubrics and how to use them.
* Know the lifecycle and markets for zero-day vulnerabilities and associated exploits.
* Recognize and discuss the ethical challenges related to vulnerabilities and exploits due to their potential for harm.


## Contents and Readings

* Vulnerabilities
    * FIRST. [Mastering CVSS v3.1](https://learning.first.org/courses/course-v1:FIRST+CVSSv3.1+2020/about).
* Zero-day Vulnerabilities
    * No mandatory reading
* The Rise of an Industry
    * No mandatory reading
* Analysis: The life of Zero-days and Their Exploits
    * L. Ablon and A. Bogart. [Zero Days, Thousands of Nights: The Life and Times of Zero-Day Vulnerabilities and Their Exploits](https://www.rand.org/pubs/research_reports/RR1751.html). RAND Corporation, 9 March 2017.
* The Ethics of Vulnerability Research
    * Bynum, Terrell, [Computer and Information Ethics](https://plato.stanford.edu/archives/sum2018/entries/ethics-computer/), The Stanford Encyclopedia of Philosophy (Summer 2018 Edition), Edward N. Zalta (ed.).

## Slides

The slides used in class for this module are available [here](https://docs.google.com/presentation/d/10g3HtQ1Si9Qb7orqk2mH0rxStX1GsAZCqyAfkqGEZXg).


## Questions

### Q1. CVE evolution 
The data feeds available at [CVE Details](https://www.cvedetails.com/) provide you with historical data and visualizations about CVEs. Youu can browse vulnerabilities by type, year, vendor, product/version, and CVSS score. Provide a longitudinal analysis of the evolution of the number and type of vulnerabilities over time. Discuss trends and identify how dif- ferent types of vulnerabilities have evolved, providing likely explanations for the observed figures.

### Q2. Ethical dilemmas
Discuss ethical positions for the following scenarios. Provide arguments in favor or against each position depending on your views. If the argument invoves an "it depends," elaborate on what circumstances make your position go one side or the other. These questions are complex and often there is no single right answer, but try to be as concise and clear in your answers as possible.

* __Ransomware__. Should victims pay or not to pay the ransom?
* __Legal malware__. You work for an AV / cyberthreat intelligence company and you come across an operation run by a law enforcement agency of your government that is affecting the society at large. Should you expose it or whitelist it?
* __Privacy disclosure__. You discover that a company implements an abusive data collection and dissemination policy. Should you: (i) conctact the vendor to express your concerns; (ii) disclose it publicly for everybody to know; or (iii) report it to your data protection agency?


## Further Reading

* Vulnerability disclosure
    * [security.txt - A File Format to Aid in Security Vulnerability Disclosure](https://securitytxt.org/).
* Zero-days
    * D. Danchev. [Black market for zero day vulnerabilities still thriving](https://www.zdnet.com/article/black-market-for-zero-day-vulnerabilities-still-thriving/). ZDNet, 2 November 2008.
    * Andy Greenberg. [Meet the hackers who sell spies the tools to crack your PC (and get paid six-figure fees)](https://www.forbes.com/sites/andygreenberg/2012/03/21/meet-the-hackers-who-sell-spies-the-tools-to-crack-your-pc-and-get-paid-six-figure-fees/?sh=3a8348aa1f74). Forbes, 21 March 2012.
    * Andy Greenberg. [Shopping For Zero-Days: A Price List For Hackers' Secret Software Exploits](https://www.forbes.com/sites/andygreenberg/2012/03/23/shopping-for-zero-days-an-price-list-for-hackers-secret-software-exploits/?sh=5b8d12522660). Forbes, 23 March 2012.
    * Sebastian Anthohy. [The first rule of zero-days is no one talks about zero-days (so we’ll explain)](https://arstechnica.com/information-technology/2015/10/the-rise-of-the-zero-day-market/). Ars Technica, 20 October 2015.
    * Andy Greenberg. [The Shadow Brokers Mess Is What Happens When the NSA Hoards Zero-Days](https://www.wired.com/2016/08/shadow-brokers-mess-happens-nsa-hoards-zero-days/). 17 August 2016.
    * Project Zero. [A very deep dive into iOS Exploit chains found in the wild ](https://googleprojectzero.blogspot.com/2019/08/a-very-deep-dive-into-ios-exploit.html). Agusut 29, 2019.
* Ethics and disclosure
    * Michael Daniel. [Heartbleed: Understanding When We Disclose Cyber Vulnerabilities](https://obamawhitehouse.archives.gov/blog/2014/04/28/heartbleed-understanding-when-we-disclose-cyber-vulnerabilities). The White House, 28 April 2014.
    * Bruce Schneier. [Should U.S. Hackers Fix Cybersecurity Holes or Exploit Them?](https://www.theatlantic.com/technology/archive/2014/05/should-hackers-fix-cybersecurity-holes-or-exploit-them/371197/). The Atlantic, 19 May 2014.
    * Bruce Schneier. [Who Are the Shadow Brokers?](https://www.theatlantic.com/technology/archive/2017/05/shadow-brokers/527778/). The Atlantic, 23 May 2017.
    * Alex Hoffman. [Moral Hazards in Cyber Vulnerability Markets](https://ieeexplore.ieee.org/document/8909925). Computer, December 2019.
    * Halvar Flake. [Rashomon of disclosure](http://addxorrol.blogspot.com/2019/08/rashomon-of-disclosure.html). August 17, 2019.
    * Ivan Kwiatkowski. [We need to talk - opening a discussion about ethics in infosec](https://www.virusbulletin.com/conference/vb2019/abstracts/we-need-talk-opening-discussion-about-ethics-infosec/). Virus Bulletin 2019.
* Legal issues
    * EFF. [Coders’ Rights Project Vulnerability Reporting FAQ](https://www.eff.org/issues/coders/vulnerability-reporting-faq).
    * EFF. [Van Buren v. United States](https://www.eff.org/cases/van-buren-v-united-states). June 2021.
