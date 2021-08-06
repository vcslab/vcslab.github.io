---
layout: advisorydetails
permalink: /advisories/VCSA-18
title: Local Privilege Escalation within Spring Webflux Multipart Request Handling
---
VCSA ID|VCSA-18
CVSS SCORE|[7.8](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?calculator&version=3.0&vector=(CVSS:3.1/AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H))
AFFECTED VENDORS|VMware
AFFECTED PRODUCTS|Spring Framework
AFFECTED VERSIONS|Spring Framework
DESCRIPTION|In Spring Framework, versions 5.2.x prior to 5.2.15 and versions 5.3.x prior to 5.3.7, a WebFlux application is vulnerable to a privilege escalation: by (re)creating the temporary storage directory, a locally authenticated malicious user can read or modify files that have been uploaded to the WebFlux application, or overwrite arbitrary files with multipart request data.
SOLUTION|Users of affected versions should apply the following mitigation. 5.3.x users should upgrade to 5.3.7. 5.2.x users should upgrade to 5.2.15. No other steps are necessary. Releases that have fixed this issue include:
CREDIT|Trung Pham
REPORT TIME|2021-04-30
PUBLISHED TIME|2021-07-30
DISCLOSURE TIMELINE|&#8226; 30/04/2021 – Reported the vulnerability to the vendor<br>&#8226; 25/05/2021 - Initial vulnerability report first published.
REFERENCES|&#8226; [https://tanzu.vmware.com/security/cve-2021-22118](https://tanzu.vmware.com/security/cve-2021-22118)<br>&#8226; [https://nvd.nist.gov/vuln/detail/CVE-2021-22118](https://nvd.nist.gov/vuln/detail/CVE-2021-22118)
