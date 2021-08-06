---
layout: advisorydetails
permalink: /advisories/VCSA-7
title: SSRF on Zimbra Collaboration Server
---
VCSA ID|VCSA-7
CVSS SCORE|[7.5](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?calculator&version=3.0&vector=(AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:N/A:N))
AFFECTED VENDORS|Zimbra
AFFECTED PRODUCTS|Zimbra Collaboration Server
AFFECTED VERSIONS|Zimbra Collaboration Server before 8.6.0 P9, 8.7.11 P9, 8.8.10 P6 and 8.8.11 P2
DESCRIPTION|Zimbra Collaboration Suite before 8.6 patch 13, 8.7.x before 8.7.11 patch 10, and 8.8.x before 8.8.10 patch 7 or 8.8.x before 8.8.11 patch 3 allows SSRF via the ProxyServlet component.
DISCLOSURE LINK|[https://blog.viettelcybersecurity.com/a-saga-of-code-executions-on-zimbra/](https://blog.viettelcybersecurity.com/a-saga-of-code-executions-on-zimbra/)
SOLUTION|Update to latest version
CREDIT|An Phuoc Trinh
REPORT TIME|2019
PUBLISHED TIME|2020-03-31
DISCLOSURE TIMELINE|&#8226; 2019 – Reported the vulnerability to the vendor<br>&#8226; 06/06/2019 – The vendor accepted the report and publish the patch
REFERENCES|&#8226; [https://bugzilla.zimbra.com/show_bug.cgi?id=109127](https://bugzilla.zimbra.com/show_bug.cgi?id=109127)<br>&#8226; [https://cvedata.com/cve/CVE-2019-9621/](https://cvedata.com/cve/CVE-2019-9621/)
