---
layout: advisorydetails
permalink: /advisories/VCSA-5
title: RCE on LimeSurvey
---
VCSA ID|VCSA-5
CVSS SCORE|[9.1](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?calculator&version=3.0&vector=(AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:N))
AFFECTED VENDORS|LimeSurvey
AFFECTED PRODUCTS|LimeSurvey
AFFECTED VERSIONS|LimeSurvey before 2.6.7 LTS, 2.73.1 and 3.4.2
DESCRIPTION|LimeSurvey 2.6.x before 2.6.7, 2.7x.x before 2.73.1, and 3.x before 3.4.2 mishandles application/controller/InstallerController.php after installation, which allows remote attackers to access the configuration file.
SOLUTION|Update as soon as possible!
CREDIT|Nguyen Van Tien Thanh (yeuchimse)
REPORT TIME|2018-02
PUBLISHED TIME|2018-09-29
DISCLOSURE TIMELINE|&#8226; 2018 – Reported the vulnerability to the vendor<br>&#8226; 23/02/2018 – The vendor accepted the report and publish the patch
REFERENCES|&#8226; [https://www.limesurvey.org/blog/21-general/112-limesurvey-security-advisory-02-2018](https://www.limesurvey.org/blog/21-general/112-limesurvey-security-advisory-02-2018)<br>&#8226; [https://cvedata.com/cve/CVE-2018-7556/](https://cvedata.com/cve/CVE-2018-7556/)
