---
layout: advisorydetails
permalink: /advisories/VCSA-77
title: CVE-2021-37941 Elastic APM Java Agent Local Privilege Escalation
---
VCSA ID|VCSA-77
CVSS SCORE|[7.0](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?calculator&version=3.0&vector=(AV:L/AC:H/PR:L/UI:N/S:U/C:H/I:H/A:H))
AFFECTED VENDORS|Elastic
AFFECTED PRODUCTS|Elastic APM
AFFECTED VERSIONS|Versions 1.10.0 through 1.26.0
DESCRIPTION|A local privilege escalation issue was found with the APM Java agent, where a user on the system could attach a malicious file to an application running with the APM Java agent. Using this vector, a malicious or compromised user account could use the agent to run commands at a higher level of permissions than they possess.
SOLUTION|Update to 1.27.0 or newer or use the unaffected -javaagent-based installation method 5 and disable the profiling_inferred_spans_enabled 9 option.
CREDIT|Trung Pham
REPORT TIME|2021-10-17
PUBLISHED TIME|2021-11-19
DISCLOSURE TIMELINE|&#8226; 17/10/2021 – Reported the vulnerability to the vendor<br>&#8226; 21/10/2021 – Triaged<br>&#8226; 19/11/2021 – Disclose
REFERENCES|&#8226; [https://discuss.elastic.co/t/apm-java-agent-security-update/289627](https://discuss.elastic.co/t/apm-java-agent-security-update/289627)<br>&#8226; [https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-37941](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2021-37941)
