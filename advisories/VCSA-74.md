---
layout: advisorydetails
permalink: /advisories/VCSA-74
title: Dynamics GP Elevation of Privilege
---
VCSA ID|VCSA-74
CVSS SCORE|[8.1/7.1](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?calculator&version=3.0&vector=(CVSS:3.1 AV:N/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:N/E:U/RL:O/RC:C))
AFFECTED VENDORS|Microsoft
AFFECTED PRODUCTS|Dynamics GP 2018
AFFECTED VERSIONS|18.3.1173, KB4569471
DESCRIPTION|Dynamics GP 2018's Rich client allows regular users to perform arbitrary SQL DML via file upload. This SQLi is only exploitable when emailing for workflow and email multi-factor authentication is enabled.
SOLUTION|NOPE
CREDIT|Hà Anh Hoàng
REPORT TIME|2021-10-26
PUBLISHED TIME|2022-02-26
DISCLOSURE TIMELINE|&#8226; 10/26/2021 – Reported the vulnerability to the vendor<br>&#8226; 11/25/2021 – The vendor reproduced the issue and accepted the report<br>&#8226; 08/02/2022 - Vendor fixed the issue and published an advisory
REFERENCES|&#8226; [https://msrc.microsoft.com/update-guide/vulnerability/CVE-2022-23272](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2022-23272)
