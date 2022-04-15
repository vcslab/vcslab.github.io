---
layout: advisorydetails
permalink: /advisories/VCSA-92
title: Dynamics GP 2018 Web Client Elevation of Privilege
---
VCSA ID|VCSA-92
CVSS SCORE|[7.1/6.2](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?calculator&version=3.0&vector=(AV:N/AC:L/PR:N/UI:N/S:U/C:L/I:H/A:N/E:U/RL:O/RC:C))
AFFECTED VENDORS|Microsoft
AFFECTED PRODUCTS|Dynamics GP 2018
AFFECTED VERSIONS|18.3.1173, KB4569471
DESCRIPTION|Dynamics GP Web Client allows the user to run arbitrary macro scripts, which can then be used to write files with any extensions with the user's current Windows Identity/Active Directory permission on the target web server. This primitive can be used to overwrite the config file, affecting the entire tennant.
SOLUTION|Update to latest version
CREDIT|Hà Anh Hoàng
REPORT TIME|2021-10-26
PUBLISHED TIME|2022-04-06
DISCLOSURE TIMELINE|&#8226; 26/10/2021 – Reported the vulnerability to the vendor<br>&#8226; 06/01/2022 – The vendor accepted the report and started to work on a fix<br>&#8226; 08/02/2022 - Vendor fixed the issue and published an advisory
REFERENCES|&#8226; [https://msrc.microsoft.com/update-guide/vulnerability/CVE-2022-23273](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2022-23273)
