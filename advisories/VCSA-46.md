---
layout: advisorydetails
permalink: /advisories/VCSA-46
title: DSA-2020-037: Dell Security Management Server Deserialization of Untrusted Data Vulnerability
---
VCSA ID|VCSA-46
CVSS SCORE|[N/A](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?calculator&version=3.0&vector=(N/A))
AFFECTED VENDORS|Dell
AFFECTED PRODUCTS|Dell Security Management Server
AFFECTED VERSIONS|Prior to 10.2.10
DESCRIPTION|Dell Security Management Server versions prior to 10.2.10 contain a Java RMI Deserialization of Untrusted Data vulnerability. When the server is exposed to the internet and Windows Firewall is disabled, a remote unauthenticated attacker may exploit this vulnerability by sending a crafted RMI request to execute arbitrary code on the target host.
SOLUTION|Update to latest version
CREDIT|Trinh Phuoc An
REPORT TIME|2020-04-01
PUBLISHED TIME|2020-07-01
REFERENCES|&#8226; [* https://www.dell.com/support/article/SLN320536](* https://www.dell.com/support/article/SLN320536)
