# Burp Suite Setup

This guide covers setup for learning and authorized testing only.

## 1. Download

Download Burp Suite from the [official PortSwigger downloads page](https://portswigger.net/burp/downloads). Choose the edition appropriate to your needs and operating system. Burp Suite Professional requires a valid license or trial; do not use third-party loaders or license-bypass patches.

## 2. Start with a safe lab

The easiest starting point is the [PortSwigger Web Security Academy](https://portswigger.net/web-security), which offers guided labs. Alternatively, use an intentionally vulnerable application running locally in an isolated environment.

## 3. Understand the proxy

Burp's proxy can intercept traffic between a configured browser and a web application. Follow the official [getting started documentation](https://portswigger.net/burp/documentation/desktop/getting-started) for browser configuration and certificate instructions.

Use a dedicated testing browser profile. Do not route personal browsing or sensitive sessions through a testing proxy.

## 4. Configure scope

Set the target scope to the lab or approved host you are authorized to test. Keep unrelated hosts out of scope and stop if traffic reaches a system not covered by your authorization.

## 5. Record the lab

For every exercise, record the objective, the steps taken, what happened, sanitized evidence, impact, and remediation. Use [the report template](../reports/TEMPLATE.md).

## Troubleshooting

- Consult the [official documentation](https://portswigger.net/burp/documentation) and the help pages for your installed edition.
- Keep your installation updated from the official source.
- Never run unknown JAR or EXE files from a chat, file-sharing site, or repository.
- Do not delete Burp or Java settings as a generic troubleshooting step unless official support documentation specifically recommends it for your situation.
