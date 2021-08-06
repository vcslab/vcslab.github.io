---
layout: advisorydetails
permalink: /advisories/VCSA-4
title: Cisco Email Security Appliance Header Bypass Vulnerability
---
VCSA ID|VCSA-4
CVSS SCORE|[5.8](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?calculator&version=3.0&vector=(AV:N/AC:L/PR:N/UI:N/S:C/C:N/I:L/A:N))
AFFECTED VENDORS|CISCO
AFFECTED PRODUCTS|Cisco Email Security Appliance (ESA)
AFFECTED VERSIONS|Cisco Bug IDs: CSCvf44666
DESCRIPTION|A vulnerability in the Multipurpose Internet Mail Extensions (MIME) scanner of Cisco AsyncOS Software for Cisco Email Security Appliances (ESA) could allow an unauthenticated, remote attacker to bypass configured user filters on the device. The vulnerability is due to improper error handling of a malformed MIME header in an email attachment. An attacker could exploit this vulnerability by sending an email with a crafted MIME attachment. For example, a successful exploit could allow the attacker to bypass configured user filters to drop the email. The malformed MIME headers may not be RFC compliant. However, some mail clients could still allow users to access the attachment, which may not have been properly filtered by the device. Cisco Bug IDs: CSCvf44666.
SOLUTION|Update to latest version
CREDIT|Mai Ngoc Duong
REPORT TIME|2017-11-29
PUBLISHED TIME|2018-04-30
DISCLOSURE TIMELINE|&#8226; 2017 – Reported the vulnerability to the vendor<br>&#8226; 29/11/2017 – The vendor accepted the report and publish the patch
REFERENCES|&#8226; [https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-20171129-esa](https://tools.cisco.com/security/center/content/CiscoSecurityAdvisory/cisco-sa-20171129-esa)<br>&#8226; [https://cvedata.com/cve/CVE-2017-12353/](https://cvedata.com/cve/CVE-2017-12353/)
