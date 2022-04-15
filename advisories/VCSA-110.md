---
layout: advisorydetails
permalink: /advisories/VCSA-110
title: SSRF on Skype For Business Server
---
VCSA ID|VCSA-110
CVSS SCORE|[5.3](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?calculator&version=3.0&vector=(AV:N/AC:L/PR:N/UI:N/S:U/C:L/I:N/A:N))
AFFECTED VENDORS|Microsoft
AFFECTED PRODUCTS|Skype For Business Server
AFFECTED VERSIONS|Before Skype for Business Server 2019 CU6
DESCRIPTION|An attacker could make a specially crafted network call to the target Skype for Business server, which could cause the parsing of an http request made to an arbitrary address. This could disclose IP addresses or port numbers or both to the attacker.
SOLUTION|Update to latest version
CREDIT|rskvp93 (Phạm Văn Khánh)
REPORT TIME|2021-12-21
PUBLISHED TIME|2022-03-21
DISCLOSURE TIMELINE|&#8226; 21/12/2021 – Reported the vulnerability to the vendor<br>&#8226; 12/04/2022 – The vendor accepted the report and publish the patch
REFERENCES|&#8226; [https://msrc.microsoft.com/update-guide/vulnerability/CVE-2022-26910](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2022-26910)
