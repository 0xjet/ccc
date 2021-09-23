# Module 2. Cybercrime and its Underground Economy

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg


This module of the course on [Cybercrime, Cyberespionage and Cyberconflicts](https://github.com/0xjet/ccc) introduces the topic of cybercrime. It first provides an overview of the abuse ecosystem focusing on the main cybercrime activities (spamvertised products, ransomware, identity theft, carding and banking fraud). It then explores the supply chains that facilitate cybercrime and the commoditization of the key products (accounts, hosting, distribution, traffic, botnets, coding and crypters, etc.). The module concludes with some walkthroughs on representative marketplaces and forums.

**Learning Outcomes**
* Know the different types of cybercrime activities.
* Understand the commoditization of capabilities and services tailored to the cybercrime ecosystem.
* Know the different types of services available in the cybercriminal undergound, the role they play in the supply chain, and their prices/pricing models.

## Contents and Readings

* What is Cybercrime
    * [Cybercrime - prosecution guidance](https://www.cps.gov.uk/legal-guidance/cybercrime-prosecution-guidance)
* The Underground Economy of Cybercrime
    * K. Thomas, D. Yuxing Huang, D. Y. Wang, E. Bursztein, C. Grier, T. Holt, C. Kruegel, D. McCoy, S. Savage, G. Vigna. [Framing Dependencies Introduced by Underground Commoditization](https://research.google/pubs/pub43798/). WEIS 2015.
    * K. Huang, M. Siegel, and S. Madnick. [Systematically Understanding the Cyber Attack Business: A Survey](https://dl.acm.org/doi/10.1145/3199674). ACM Computing Surveys, Vol. 51, Issue 4 September 2018, pp. 1–36.
* Marketplaces
    * No mandatory reading
* Intervention
    * Larry G. Wlosinski. [Cybersecurity Takedowns](https://www.isaca.org/resources/isaca-journal/issues/2019/volume-6/cybersecurity-takedowns). 15 November 2019.


## Slides

The slides used in class for this module are available here.


## Questions

### Q1. Underground cybercrime prices
Analyze the evolution of prices for a subset of representative products available in the cybercrime underground. Look for recent reports (e.g., Privacy Affairs Dark Web Price Index [2020](https://www.privacyaffairs.com/dark-web-price-index-2020/) and [2021](https://www.privacyaffairs.com/dark-web-price-index-2021/)) and discuss price changes and potential reasons for observed variations.

### Q2. Click fraud
Do some research about the key metrics used by the online advertising industry, such as Pay-Per-Click (PPC), Cost-Per-Impresion (CPI, or CPM for 1,000 impresions), and Click-Through-Rate (CTR). Read this [brief introduction to the click fraud phenomenon](https://faculty.ist.psu.edu/jjansen/academic/jansen_click_fraud.pdf) by Bernard Jansen (Computer, July 2007). Complement the previous reading with other documents on the same topic. Write up a brief description of technical means used to conduct click fraud at scale.

### Q3. SMS as 2FA
Discuss reasons why using SMS to deliver codes for two-factor authentication (2FA) is a bad design choice.

### Q4. SIM swapping
SIM swapping has become a popular type of account takeover scam. Do some research of how it works and discuss the root causes behind its success. List a few popular cases of account takeovers that leveraged SIM swapping.

### Q5. Residential proxies
Do some research about the services advertised as "residential proxies." Find out how they work, particularly how the company acquires the pool of residential IP addresses. Describe a few uses cases and what advantages they hold over traditional proxies based on data centers. Can you identify any risks for the users who willingly participate in the program?

### Q6. Emotet
Emotet was a very prevalent threat prior to its takedown in January 2021. Its operation has been widely documented. Research about its origins, structure and purpose, focusing on how it evolved to serve loaders to victims that could then download second-stage payloads for different customers. At some point their operators used parked domains to distribute payloads. Find out why this is an interesting strategy.


## Further Reading

* Threat landscape:
    * ENISA. [Threat Landscape](https://www.enisa.europa.eu/topics/threat-risk-management/threats-and-trends).
    * Magno Logan, Erika Mendoza, Ryan Maglaque, and Nikko Tamaña. [The State of Ransomware: 2020's Catch-22](https://www.trendmicro.com/vinfo/us/security/news/cybercrime-and-digital-threats/the-state-of-ransomware-2020-s-catch-22). Trend Micro. February 03, 2021.
* Identity theft:
    * Krebs on Security. [How Much Is Your Identity Worth?](https://krebsonsecurity.com/2011/11/how-much-is-your-identity-worth/), November 8, 2011
    * Krebs on Security. [Confessions of an ID Theft Kingpin, Part I](https://krebsonsecurity.com/2020/08/confessions-of-an-id-theft-kingpin-part-i/). August 26, 2020.
    * Krebs on Security. [Confessions of an ID Theft Kingpin, Part II](https://krebsonsecurity.com/2020/08/confessions-of-an-id-theft-kingpin-part-ii/). August 27, 2020.
    * K. Tomas et al. [Data breaches, phishing, or malware? Understanding the risks of stolen credentials](https://research.google/pubs/pub46437/). CCS 2017.
* Botnets:
    * Mark Bowden. [The Worm That Nearly Ate the Internet](https://www.nytimes.com/2019/06/29/opinion/sunday/conficker-worm-ukraine.html). New York Times. June 29, 2019.
    * [Operation Tovar](https://en.wikipedia.org/wiki/Operation_Tovar). Wikipedia.
    * M. Antonakakis et al. [Understanding the Mirai Botnet](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/antonakakis). USENIX Security 2017.
* Hosting infrastructure:
    * Vladimir Kropotov, Robert McArdle, and Fyodor Yarochkin. [The Hacker Infrastructure and Underground Hosting: Services Used by Criminals](https://documents.trendmicro.com/assets/white_papers/wp-the-hacker-infrastructure-and-underground-hosting-services-used-by-criminals.pdf). Trend Micro. September 01, 2020.
* Phone scams:
    * Jim Browning. [Spying on the Scammers [Parts 1-4]](https://www.youtube.com/watch?v=le71yVPh4uk&list=PLBNmQJqxpaMaxqghShRiOnHUjO00ZCsor). Mar 2, 2020.
* Cybercrime supply chains:
    * R. Bhalerao, M. Aliapoulios, I. Shumailov, S. Afroz, D. McCoy. [Mapping the Underground: Supervised Discovery of Cybercrime Supply Chains](https://damonmccoy.com/papers/ecrime2019.pdf), eCrime 2019.


