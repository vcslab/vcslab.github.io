---
layout: advisorydetails
permalink: /advisories/VCSA-108
title: Spring Cloud Gateway Code Injection
---
VCSA ID|VCSA-108
CVSS SCORE|[7.5](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?calculator&version=3.0&vector=(AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:H/A:N))
AFFECTED VENDORS|Spring by VMware
AFFECTED PRODUCTS|Spring Cloud Gateway
AFFECTED VERSIONS|Spring Cloud Gateway 3.1.0, 3.0.0 to 3.0.6 and older version
DESCRIPTION|Applications using Spring Cloud Gateway are vulnerable to a code injection attack when the Gateway Actuator endpoint is enabled, exposed and unsecured. A remote attacker could make a maliciously crafted request that could allow arbitrary remote execution on the remote host.
DISCLOSURE LINK|[https://blog.viettelcybersecurity.com/cve-2022-22947-spring-cloud-gateway-code-injection-vulnerability/](https://blog.viettelcybersecurity.com/cve-2022-22947-spring-cloud-gateway-code-injection-vulnerability/)
SOLUTION|Update to latest version
CREDIT|nxhoang99 (Nguyễn Xuân Hoàng)
REPORT TIME|2022-01-16
PUBLISHED TIME|2022-03-10
DISCLOSURE TIMELINE|&#8226; 16/01/2022 – Reported the vulnerability to the vendor<br>&#8226; 24/01/2022 – The vendor accepted the report and assigned for triage.<br>&#8226; 16/02/2022 – The vendor conclude as a duplicate.<br>&#8226; 01/03/2022 – The vendor release new patch
REFERENCES|&#8226; [https://tanzu.vmware.com/security/cve-2022-22947](https://tanzu.vmware.com/security/cve-2022-22947)
