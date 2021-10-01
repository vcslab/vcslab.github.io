---
layout: advisorydetails
permalink: /advisories/VCSA-65
title: Json unsafe deserialize - new gadget
---
VCSA ID|VCSA-65
CVSS SCORE|[8.1](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?calculator&version=3.0&vector=(AV:N/AC:H/PR:N/UI:N/S:U/C:H/I:H/A:H))
AFFECTED VENDORS|Jackson
AFFECTED PRODUCTS|Jackson
AFFECTED VERSIONS|2.9.10.4 and before
DESCRIPTION|FasterXML jackson-databind 2.x before 2.9.10.4 mishandles the interaction between serialization gadgets and typing, related to org.springframework.aop.config.MethodLocatingFactoryBean (aka spring-aop)
SOLUTION|Update to latest version
CREDIT|duongbv2 (Bùi Văn Dương)
REPORT TIME|2020-08-05
PUBLISHED TIME|2020-07-01
DISCLOSURE TIMELINE|&#8226; 2020-04-01 – Reported the vulnerability to the vendor<br>&#8226; 07/04/2020 – The vendor accepted the report and publish the patch
REFERENCES|&#8226; [https://github.com/FasterXML/jackson-databind/issues/2680](https://github.com/FasterXML/jackson-databind/issues/2680)<br>&#8226; [https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-11619](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2020-11619)
