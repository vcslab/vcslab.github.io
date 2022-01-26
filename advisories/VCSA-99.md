---
layout: advisorydetails
permalink: /advisories/VCSA-99
title: Remote Code Execution through Insight - Asset Management
---
VCSA ID|VCSA-99
CVSS SCORE|[8.8](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?calculator&version=3.0&vector=(AV:N/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H))
AFFECTED VENDORS|Atlassian
AFFECTED PRODUCTS|Insight - Asset Management app
AFFECTED VERSIONS|Insight - Asset Management app: All 5.x to 8x versions before 8.9.3
DESCRIPTION|nsight - Asset Management has a feature to import data from several databases (DBs). One of these DBs, the H2 DB, has a native function in its library which an attacker can use to run code on the server (remote code execution a.k.a. RCE). The H2 DB is bundled with Jira to help speed up the setup of Jira test environments.
SOLUTION|Update to latest version
CREDIT|khoadha (Đinh Hồ Anh Khoa)
REPORT TIME|2021-05-31
PUBLISHED TIME|2021-10-20
DISCLOSURE TIMELINE|&#8226; 31/05/2021 – Reported the vulnerability to the vendor<br>&#8226; 20/10/2021 – The vendor accepted the report and publish the patch
REFERENCES|&#8226; [https://confluence.atlassian.com/adminjiraserver/jira-service-management-security-advisory-2021-10-20-1085186548.html](https://confluence.atlassian.com/adminjiraserver/jira-service-management-security-advisory-2021-10-20-1085186548.html)
