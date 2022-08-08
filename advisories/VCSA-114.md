---
layout: advisorydetails
permalink: /advisories/VCSA-114
title: RCE on TL-WR841N
---
VCSA ID|VCSA-114
CVSS SCORE|[8.2](https://nvd.nist.gov/vuln-metrics/cvss/v3-calculator?calculator&version=3.0&vector=(AV:N/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H/E:F/RL:T/RC:C))
AFFECTED VENDORS|TPLink
AFFECTED PRODUCTS|TPLink TL-WR841N V12
AFFECTED VERSIONS|Firmware version 3.16.9
DESCRIPTION|TPLink TL-WR841N V12 (firmware version 3.16.9) devices allow an authenticated allows remote code execution via GET request to the page for the System Tools of the Wi-Fi network.
SOLUTION|Check data length before processing
CREDIT|cuongtm30 (Trần Minh Cường)
REPORT TIME|2022-04-14
PUBLISHED TIME|2022-07-14
DISCLOSURE TIMELINE|&#8226; 14/04/2022 – Reported the vulnerability to the vendor<br>&#8226; 26/04/2022 – The vendor accepted the report and publish the patch
REFERENCES|&#8226; [https://www.tp-link.com/us/home-networking/wifi-router/tl-wr841n/](https://www.tp-link.com/us/home-networking/wifi-router/tl-wr841n/)<br>&#8226; [https://pastebin.com/0XRFr3zE](https://pastebin.com/0XRFr3zE)
