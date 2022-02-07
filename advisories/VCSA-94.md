---
layout: advisorydetails
permalink: /advisories/VCSA-94
title: Apache NiFi information disclosure by XXE in TransformXML
---
VCSA ID|VCSA-94
CVSS SCORE|[7.1](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?calculator&version=3.0&vector=(AV:N/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:L))
AFFECTED VENDORS|Apache
AFFECTED PRODUCTS|Apache NiFi
AFFECTED VERSIONS|Apache NiFi 0.1.0 - 1.15.0
DESCRIPTION|In the TransformXML processor, an authenticated user could configure an XSLT file which, if it included malicious external entity calls, may reveal sensitive information.
SOLUTION|The 'Secure processing' property will now apply to the configured XSLT file as well as flow files being transformed. Users running any previous NiFi release should upgrade to the latest release.
CREDIT|DangKhai (Nguyễn Đặng Khải)
REPORT TIME|2021-11-19
PUBLISHED TIME|2022-02-19
DISCLOSURE TIMELINE|&#8226; 19/11/2021 – Reported the vulnerability to the vendor<br>&#8226; 15/12/2021 – The vendor accepted the report and publish the patch
REFERENCES|&#8226; [https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-44145](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-44145)<br>&#8226; [https://nifi.apache.org/security.html#CVE-2021-44145](https://nifi.apache.org/security.html#CVE-2021-44145)
