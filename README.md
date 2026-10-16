# Burp Suite Web Security Lab

A practical learning repository for **web application security testing** with Burp Suite. Keep your notes, repeatable workflows, lab reports, and helper scripts organized in one place.

[![Focus](https://img.shields.io/badge/Focus-Web%20Security-blue)](#-learning-roadmap)
[![Practice](https://img.shields.io/badge/Practice-Authorized%20Labs-success)](#-safe-practice-rules)
[![Tool](https://img.shields.io/badge/Tool-Burp%20Suite-orange)](https://portswigger.net/burp)

> **Scope:** This repository is for learning and authorized security testing. Only test applications you own or have explicit permission to assess. Do not commit passwords, session cookies, API keys, personal data, licensed software installers, or license-bypass tools.

## 🚀 Getting started

1. Install Burp Suite from the [official PortSwigger downloads page](https://portswigger.net/burp/downloads).
2. Begin with the [PortSwigger Web Security Academy](https://portswigger.net/web-security), which provides free learning material and interactive labs.
3. Configure a dedicated browser and Burp proxy by following the [official documentation](https://portswigger.net/burp/documentation/desktop/getting-started).
4. Practise first on Web Security Academy labs or a local deliberately vulnerable application.
5. Record observations and remediation recommendations in the templates in this repository.

## 🧭 Learning roadmap

| Stage | Topic | Practice goal |
|---|---|---|
| 1 | HTTP fundamentals | Understand requests, responses, headers, cookies, and status codes |
| 2 | Proxy and browser setup | Intercept and inspect your own lab traffic |
| 3 | Scope and target mapping | Define in-scope hosts and map application functionality |
| 4 | Repeater and request editing | Reproduce requests and compare responses in a lab |
| 5 | Authentication and sessions | Learn session handling and access-control concepts |
| 6 | Common web vulnerabilities | Study SQL injection, XSS, CSRF, path traversal, SSRF, and related topics in guided labs |
| 7 | Reporting | Write clear reproduction steps, impact, evidence, and remediation advice |

Use the [Web Security Academy learning paths](https://portswigger.net/web-security/learning-paths) to study each topic in a structured order.

## 🗂️ Repository structure

```text
burp-suite-web-security-lab/
├── README.md
├── docs/
│   ├── setup.md
│   └── testing-methodology.md
├── notes/
│   └── README.md
├── reports/
│   ├── TEMPLATE.md
│   └── README.md
└── checklists/
    └── pre-engagement.md
```

## 🛡️ Safe practice rules

- Test only systems you own or are expressly authorized to assess.
- Use Web Security Academy or an isolated local lab for vulnerability exercises.
- Confirm written scope, allowed techniques, test window, and reporting contact before an engagement.
- Avoid denial-of-service, destructive actions, persistence, or accessing other people's data.
- Redact session tokens, credentials, personal data, and internal hostnames from notes and screenshots.
- Do not commit Burp Suite installers, proprietary files, cracked tools, or license-bypass loaders. Link to the official source instead.

## 📝 Lab report format

For each lab or authorized assessment, record:

- **Title and date**
- **Lab or target** (use a permitted test environment; redact sensitive details)
- **Scope and authorization**
- **Objective**
- **Steps performed**
- **Expected and observed behavior**
- **Evidence** (sanitized request/response excerpts)
- **Impact**
- **Remediation**
- **Retest result and references**

Start from the [report template](reports/TEMPLATE.md).

## 🔗 Official learning resources

- [Burp Suite downloads](https://portswigger.net/burp/downloads)
- [Burp Suite documentation](https://portswigger.net/burp/documentation)
- [PortSwigger Web Security Academy](https://portswigger.net/web-security)
- [Web Security Academy labs](https://portswigger.net/web-security/all-labs)
- [PortSwigger research](https://portswigger.net/research)

## 🤝 Contributing

Add original notes, safe lab write-ups, checklists, and scripts. Explain the lab context and include remediation guidance. Never commit secrets, private target data, unlicensed software, or credentials. See [GitHub's guidance on secret scanning](https://docs.github.com/en/code-security/secret-scanning/introduction/about-secret-scanning).

## ⚖️ Disclaimer

This repository is an independent educational project and is not affiliated with or endorsed by PortSwigger. Burp Suite is a trademark/product of its respective owner. Use it responsibly and in compliance with applicable laws, licenses, and engagement rules.
