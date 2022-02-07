---
layout: advisorydetails
permalink: /advisories/VCSA-78
title: NOPE
---
VCSA ID|VCSA-78
CVSS SCORE|[7.0](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?calculator&version=3.0&vector=(AV:L/AC:H/PR:L/UI:N/S:U/C:H/I:H/A:H))
AFFECTED VENDORS|Apache
AFFECTED PRODUCTS|Apache Tomcat
AFFECTED VERSIONS|10.1.0-M1 to 10.1.0-M8
DESCRIPTION|The fix for bug CVE-2020-9484 introduced a time of check, time of use vulnerability into Apache Tomcat 10.1.0-M1 to 10.1.0-M8, 10.0.0-M5 to 10.0.14, 9.0.35 to 9.0.56 and 8.5.55 to 8.5.73 that allowed a local attacker to perform actions with the privileges of the user that the Tomcat process is using. This issue is only exploitable when Tomcat is configured to persist sessions using the FileStore.
SOLUTION|Update to latest version
CREDIT|Trung Pham
REPORT TIME|2021-12-17
PUBLISHED TIME|2022-01-27
DISCLOSURE TIMELINE|&#8226; 17/12/2021 – Reported the vulnerability to the vendor<br>&#8226; 04/01/2021 – The vendor accepted the report<br>&#8226; 27/01/2022 – Disclosure
REFERENCES|&#8226; [https://nvd.nist.gov/vuln/detail/CVE-2022-23181](https://nvd.nist.gov/vuln/detail/CVE-2022-23181)<br>&#8226; [https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-23181](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-23181)
