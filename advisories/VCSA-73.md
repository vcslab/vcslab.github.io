---
layout: advisorydetails
permalink: /advisories/VCSA-73
title: Dynamics GP 2018 Remote Code Execution
---
VCSA ID|VCSA-73
CVSS SCORE|[8.3 / 7.2](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?calculator&version=3.0&vector=(AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:L/E:U/RL:O/RC:C))
AFFECTED VENDORS|Microsoft
AFFECTED PRODUCTS|Dynamics GP 2018
AFFECTED VERSIONS|18.3.1173, KB4569471
DESCRIPTION|Dynamics GP 2018 Web Service handled the document id parameter incorrectly during invoice creation, allowing users to inject SQL and write arbitrary data into the database. This was then used to plant a serialized object to be processed later, resulting in code execution.
SOLUTION|Update to latest version
CREDIT|Hà Anh Hoàng
REPORT TIME|2021-10-26
PUBLISHED TIME|2022-02-26
DISCLOSURE TIMELINE|&#8226; 8/2/2022 - Vendor fixed the issue and published an advisory<br>&#8226; 10/26/2021 – Reported the vulnerability to the vendor<br>&#8226; 11/25/2021 – The vendor reproduced the issue and accepted the report
REFERENCES|&#8226; [https://msrc.microsoft.com/update-guide/vulnerability/CVE-2022-23274](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2022-23274)
