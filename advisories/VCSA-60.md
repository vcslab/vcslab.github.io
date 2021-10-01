---
layout: advisorydetails
permalink: /advisories/VCSA-60
title: Unsafe deserialization migitagion bypass
---
VCSA ID|VCSA-60
CVSS SCORE|[7.0](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?calculator&version=3.0&vector=(CVSS:3.1/AV:L/AC:H/PR:L/UI:N/S:U/C:H/I:H/A:H))
AFFECTED VENDORS|Apache
AFFECTED PRODUCTS|Apache Tomcat
AFFECTED VERSIONS|Apache Tomcat 9.0.0.M1 to 9.0.41
DESCRIPTION|The fix for CVE-2020-9484 was incomplete. When using Apache Tomcat 10.0.0-M1 to 10.0.0, 9.0.0.M1 to 9.0.41, 8.5.0 to 8.5.61 or 7.0.0. to 7.0.107 with a configuration edge case that was highly unlikely to be used, the Tomcat instance was still vulnerable to CVE-2020-9494. Note that both the previously published prerequisites for CVE-2020-9484 and the previously published mitigations for CVE-2020-9484 also apply to this issue.
SOLUTION|Update to latest version
CREDIT|Trung Pham
REPORT TIME|2021-01-20
PUBLISHED TIME|2021-04-20
DISCLOSURE TIMELINE|&#8226; 20/01/2021 – Reported the vulnerability to the vendor<br>&#8226; 02/02/2021 – Vulnerability report published
REFERENCES|&#8226; [http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-25329](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-25329)<br>&#8226; [https://nvd.nist.gov/vuln/detail/CVE-2021-25329](https://nvd.nist.gov/vuln/detail/CVE-2021-25329)
