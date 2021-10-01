---
layout: advisorydetails
permalink: /advisories/VCSA-61
title: Zip-slip mitigation bypass in Spring Integration Zip extension
---
VCSA ID|VCSA-61
CVSS SCORE|[5.3](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?calculator&version=3.0&vector=(AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:L/A:N))
AFFECTED VENDORS|VMware
AFFECTED PRODUCTS|Spring Integration Extension
AFFECTED VERSIONS|1.0.3.RELEASE and earlier
DESCRIPTION|spring-integration-zip , versions prior to 1.0.4, exposes an arbitrary file write vulnerability, that can be achieved using a specially crafted zip archive (affects other archives as well, bzip2, tar, xz, war, cpio, 7z), that holds path traversal filenames. So when the filename gets concatenated to the target extraction directory, the final path ends up outside of the target folder. The previous cve-2018-1263 prevented the framework from unzipping general traversal file names. The special file names, containing a working directory for unzipping, still can slip out of that working directory. This specifically applies to the unzip transformer. This can only happen if an application using this library accepts and unpacks zip files from untrusted sources.
SOLUTION|Update to latest version
CREDIT|Trung Pham
REPORT TIME|2021-01-28
PUBLISHED TIME|2021-05-26
DISCLOSURE TIMELINE|&#8226; 28/01/2021 – Reported the vulnerability to the vendor<br>&#8226; 28/01/2021 – Fix updated<br>&#8226; 26/02/2021 – Initial vulnerability report published.
REFERENCES|&#8226; [https://tanzu.vmware.com/security/cve-2021-22114](https://tanzu.vmware.com/security/cve-2021-22114)<br>&#8226; [https://spring.io/blog/2021/03/01/spring-integration-zip-1-0-4-cve-2021-22114](https://spring.io/blog/2021/03/01/spring-integration-zip-1-0-4-cve-2021-22114)<br>&#8226; [https://nvd.nist.gov/vuln/detail/CVE-2021-22114](https://nvd.nist.gov/vuln/detail/CVE-2021-22114)<br>&#8226; [https://cve.mitre.org/cgi-bin/cvename.cgi?name=2021-22114](https://cve.mitre.org/cgi-bin/cvename.cgi?name=2021-22114)
