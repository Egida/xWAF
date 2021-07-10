# xWAF - Web Application Firewall

Original Free Web Application Firewall, Open-Source.

# Features

- [x] XSS Vulns Fixed.
- [x] SQL Injection Fixed.
- [x] Anti-Cookie-Steal Method.
- [x] HTML Malicious Code's Vulns Fixed.
- [x] CSRF Easy to use, and validation.
- [x] Block HTML Upgraded.
- [x] Lightweight.
- [x] Array Support, All Bypass fixed.
- [x] Advanced Bot validation, Browser Validation.
- [x] Most Poc's SQLi and XSS.
- [x] Security upgraded.
- [x] Errors supression.
- [x] Cloudflare and BlazingFast Support.

# New Features
- [x] Fixed Issues
- [x] New HTML Detection Site (Leads to a Gov Site)  

# Installation

```php

// Before of all your CODE.
require('secured.php');
$secured = new secured();
// Cloudflare Mode [Optional]
$secured->useCloudflare();
// BlazingFast Mode [Optional]
$secured->useBlazingfast();
// Use Own IP Header [Optional]
$secured->customIPHeader('IP-Header');
// Anti-Cookie-Steal Method [Optional]
$secured->antiCookieSteal('username'); // For trigger if on PHPSESSID is logged.

// Check separated types.
$secured->checkGET();
$secured->checkPOST();
$secured->checkCOOKIE();
// Your code below.
```

# Credits

> CourtesyDev - Reworked

> Alemalakra - [Original Developer](https://github.com/Alemalakra/xWAF)
