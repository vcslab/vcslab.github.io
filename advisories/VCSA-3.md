---
layout: advisorydetails
permalink: /advisories/VCSA-3
title: RCE in Telerik UI for ASP.NET AJAX
---
VCSA ID|VCSA-3
CVSS SCORE|[9.8](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?calculator&version=3.0&vector=(AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H))
AFFECTED VENDORS|Telerik
AFFECTED PRODUCTS|Telerik UI for ASP.NET AJAX
AFFECTED VERSIONS|Progress Telerik UI for ASP.NET AJAX before R2 2017 SP1 and Sitefinity before 10.0.6412.0
DESCRIPTION|Telerik.Web.UI.dll in Progress Telerik UI for ASP.NET AJAX before R2 2017 SP1 and Sitefinity before 10.0.6412.0 does not properly protect Telerik.Web.UI.DialogParametersEncryptionKey or the MachineKey, which makes it easier for remote attackers to defeat cryptographic protection mechanisms, leading to a MachineKey leak, arbitrary file uploads or downloads, XSS, or ASP.NET ViewState compromise.
DISCLOSURE LINK|[https://yeuchimse.com/rce-in-telerik-ui-for-asp-net-ajax-cve-2017-9248/](https://yeuchimse.com/rce-in-telerik-ui-for-asp-net-ajax-cve-2017-9248/)
SOLUTION|Update to latest version
CREDIT|Thanh Van Tien Nguyen (yeuchimse)
REPORT TIME|2017-06-13
PUBLISHED TIME|2017-12-31
DISCLOSURE TIMELINE|&#8226; 06/06/2017: Discovered the vulnerability.<br>&#8226; 13/06/2017: Reported to Progress.<br>&#8226; 03/07/2017: Security advisory released.
REFERENCES|&#8226; [https://www.telerik.com/support/kb/aspnet-ajax/details/cryptographic-weakness](https://www.telerik.com/support/kb/aspnet-ajax/details/cryptographic-weakness)<br>&#8226; [https://cvedata.com/cve/CVE-2017-9248/](https://cvedata.com/cve/CVE-2017-9248/)<br>&#8226; [https://yeuchimse.com/rce-in-telerik-ui-for-asp-net-ajax-cve-2017-9248/](https://yeuchimse.com/rce-in-telerik-ui-for-asp-net-ajax-cve-2017-9248/)
