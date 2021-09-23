---
layout: page
permalink: /policy
title: VCS Vulnerability Disclosure Policy
version: 1.0
update: 2021-09-09
---
[Đọc phiên bản tiếng Việt](/policy-vi)

Viettel Cyber Security Company (VCS) was established in 2011 with ongoing efforts to ensure the cybersecurity of the Viettel Group and providing cybersecurity services for other businesses and organizations. With the slogan of attaching great weight to intensive research, our security research team was established in the early stage. The goal of our team is to conduct research on vulnerabilities, exploitation techniques and latest cybersecurity threats, to alert and prevent the impact of them on the community. In 2021, our team has been firstly identified as VCSLab with the orientation to not only professionally detect and disclose the vulnerabilities, but also contribute to community-driven values.

### 1. Concept definition
**The vulnerability disclosure program** of Viettel Cyber Security complies with the [“Responsible Disclosure”](https://cheatsheetseries.owasp.org/cheatsheets/Vulnerability_Disclosure_Cheat_Sheet.html) form. This means vulnerabilities in the program will be alerted to the affected vendor(s) instantly when they have been identified. Furthermore, the description of the vulnerability and solution will be cautioned to the community in the form of an advisory after 90 days. This method was referred to the Google Research Team – Project Zero ([https://www.google.com/about/appsecurity/](https://www.google.com/about/appsecurity/))  

**Advisory** is the vulnerability alerts to members of the public to ensure that the vulnerability is properly perceived in terms of severity, and widely remedied. The advisories are posted on the website: [lab.viettelcybsecurity.com](https://lab.viettelcybsecurity.com)

**Vulnerability reports** are details of the vulnerability sent separately to the organization and vendor(s). There are 3 groups of report as follows:
-   **Non-profit report (Community report)**: is the report sent to the organization, vendor(s) under a research program or for community purposes.
-   **Non-profit report in Vietnam (VN Community report)**: Due to some legal issues, vulnerability reports in Vietnam will be made through the approval of the organization or through State agencies or others.
-   **Bug bounty vulnerability report** is under a Bug bounty program, compliant with the program's disclosure policy.

### 2. Principles
The Vulnerability Disclosure Policy is subject to the following principles:
-   **Respect for Vulnerabilities**: the guiding principle and orientation of the program. Vulnerabilities need to be properly recognized and fully remedied as possible. 
-   **Respect for Law**: All vulnerability programs are aimed at a safer cyber space. Thus, we are committed to detect vulnerabilities within the allowed framework and complying with the law.
-   **Respect for Product**: While function is the core value of the product, security is the added value to it. Vulnerability disclosure always contributes the product’s value without affecting its reputation and image.

### 3. Remediation deadline
General statuses and deadlines: Each vulnerability identified in the program is VCSA-coded and has its respective status changed until published. Specifically, there are the following statuses:
-   **New:** Newly identified vulnerability has been sent privately to the organization. The vulnerability VCSA of this status is not displayed on [lab.viettelcybsecurity.com](https://lab.viettelcybsecurity.com)
-   **Not Responded:** After 3 times the report is sent and reminded (every 7 business days), if the owner does not respond, the advisory will be changed to Not-Responded status and displayed in the Upcoming section on the homepage: [lab.viettelcybsecurity.com](https://lab.viettelcybsecurity.com)
-   **Accepted:** Vulnerabilities confirmed by the owner will be displayed in the Upcoming section until the remediation period expires.
-   **Fixed:** The vulnerabilities have been overcome and already had the method to fix by the owner.
-   **Upcoming:** Is a display feature in the advisory, listing the advisory status has been changed Not-Responded, Accepted or Fixed.
-   **Published:** After the remediation period (90 days), the details of vulnerability are released to the public and appear in the Published section on [lab.viettelcybsecurity.com](https://lab.viettelcybsecurity.com)

The 90-day disclosure deadline can vary in the following ways:
-   If a deadline is due to expire on a weekend or Vietnam public holiday, the deadline will be moved to the next business day.
-   Before the 90-day deadline has expired, if the owner lets us know that a patch is scheduled for release on a specific day that will fall within 14 days following the deadline, we will change the advisory publication date until the fix is implemented.
-   When we identify a vulnerability that is being actively exploited in practice (a “0-day”), we believe more urgent action is needed– within 7 days is acceptable and considered as an important timeline. Although some vendors possibly find it too short to update their products, it should be enough time to put risk mitigation measures in place, such as temporarily disabling a service, restricting access, or contacting the provider for more information. As a result, after the period of seven days, if the owner does not take any patch action or advisory, we will provide detailed information so that users can take steps to protect themselves. 

### 4. References
-   [https://cheatsheetseries.owasp.org/cheatsheets/Vulnerability_Disclosure_Cheat_Sheet.html](https://cheatsheetseries.owasp.org/cheatsheets/Vulnerability_Disclosure_Cheat_Sheet.html) 
-   [https://www.google.com/about/appsecurity/](https://www.google.com/about/appsecurity/)