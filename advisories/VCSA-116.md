---
layout: advisorydetails
permalink: /advisories/VCSA-116
title: All-in-One WP Migration <=7.58 – Directory Traversal to File Deletion on Windows Hosts
---
VCSA ID|VCSA-116
CVSS SCORE|[6.6](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?calculator&version=3.0&vector=(A:H/I:H/C:H/S:U/UI:N/PR:H/AC:H/AV:N))
AFFECTED VENDORS|Servmask
AFFECTED PRODUCTS|All-in-One WP Migration
AFFECTED VERSIONS|<= 7.58
DESCRIPTION|The All-in-One WP Migration plugin for WordPress is vulnerable to arbitrary file deletion via directory traversal due to insufficient file validation via the ~/lib/model/class-ai1wm-backups.php file, in versions up to, and including, 7.58. This can be exploited by administrative users, and users who have access to the site’s secret key on WordPress instances with Windows hosts.
SOLUTION|Update to latest version
CREDIT|haidv35 (Đinh Viết Hải)
REPORT TIME|2022-04-22
PUBLISHED TIME|2022-07-22
DISCLOSURE TIMELINE|&#8226; 22/04/2022 – Reported the vulnerability to the vendor<br>&#8226; 26/04/2022 – The vendor accepted the report and publish the patch
REFERENCES|&#8226; [https://www.wordfence.com/vulnerability-advisories/#CVE-2022-1476](https://www.wordfence.com/vulnerability-advisories/#CVE-2022-1476)<br>&#8226; [https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-1476](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-1476)
