---
layout: advisorydetails
permalink: /advisories/VCSA-6
title: XXE on Zimbra ZxChat component
---
VCSA ID|VCSA-6
CVSS SCORE|[9.8](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?calculator&version=3.0&vector=(AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H))
AFFECTED VENDORS|Zimbra
AFFECTED PRODUCTS|Zimbra Collaboration Server
AFFECTED VERSIONS|Zimbra Collaboration Server before 8.7.11 P9, 8.8.9 P8, 8.8.10 P4 and 8.8.11
DESCRIPTION|ZxChat (aka ZeXtras Chat), as used for zimbra-chat and zimbra-talk in Synacor Zimbra Collaboration Suite 8.7 and 8.8 and in other products, allows XXE attacks, as demonstrated by a crafted XML request to mailboxd.
DISCLOSURE LINK|[https://blog.viettelcybersecurity.com/a-saga-of-code-executions-on-zimbra/](https://blog.viettelcybersecurity.com/a-saga-of-code-executions-on-zimbra/)
SOLUTION|Update to the latest version
CREDIT|An Phuoc Trinh
REPORT TIME|2018
PUBLISHED TIME|2019-12-31
DISCLOSURE TIMELINE|&#8226; 2018 – Reported the vulnerability to the vendor<br>&#8226; 29/05/2019 – The vendor accepted the report and publish the patch
REFERENCES|&#8226; [https://cvedata.com/cve/CVE-2018-20160/](https://cvedata.com/cve/CVE-2018-20160/)<br>&#8226; [https://bugzilla.zimbra.com/show_bug.cgi?id=109093](https://bugzilla.zimbra.com/show_bug.cgi?id=109093)
