---
layout: advisorydetails
permalink: /advisories/VCSA-76
title: CVE-2021-37942 Elastic APM Java Agent  Local Privilege Escalation
---
VCSA ID|VCSA-76
CVSS SCORE|[8.7](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?calculator&version=3.0&vector=(AV:L/AC:L/PR:L/UI:N/S:C/C:H/I:H/A:L))
AFFECTED VENDORS|Elastic
AFFECTED PRODUCTS|Elastic APM
AFFECTED VERSIONS|Versions 1.18.0 through 1.27.0
DESCRIPTION|A local privilege escalation issue was found with the APM Java agent, where a user on the system could attach a malicious plugin to an application running the APM Java agent. By using this vulnerability, an attacker could execute code at a potentially higher level of permissions than their user typically has access to.
SOLUTION|Update to 1.27.1 or newer
CREDIT|Trung Pham
REPORT TIME|2021-10-17
PUBLISHED TIME|2021-12-10
DISCLOSURE TIMELINE|&#8226; 17/10/2021 – Reported the vulnerability to the vendor<br>&#8226; 21/10/2021 – Triaged<br>&#8226; 10/12/2021 – Disclose
REFERENCES|&#8226; [https://discuss.elastic.co/t/apm-java-agent-security-update/291355](https://discuss.elastic.co/t/apm-java-agent-security-update/291355)<br>&#8226; [https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-37942](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-37942)
