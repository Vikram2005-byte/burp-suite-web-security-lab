# Authorized Web Testing Methodology

Use this workflow only for systems in an explicitly authorized scope.

## Before testing

- Confirm written permission and the exact target scope.
- Read the rules of engagement, including prohibited test types, time windows, rate limits, and reporting contacts.
- Use a dedicated browser profile and a clean project.
- Identify sensitive data and define how evidence will be sanitized.

## During testing

1. Map the application's intended functionality.
2. Inspect normal requests and responses before changing inputs.
3. Form one test hypothesis at a time.
4. Make controlled, low-impact changes in the lab or permitted target.
5. Keep notes of the request, observed response, timestamp, and test condition.
6. Stop if a test may affect availability, access data outside your authorization, or expose sensitive information.

## After testing

- Validate findings safely and avoid unnecessary data access.
- Explain the root cause, realistic impact, and a specific remediation.
- Redact credentials, tokens, personal data, and unrelated identifiers from evidence.
- Follow the agreed reporting and data-retention process.
- Retest the fix only when authorized.

## Suggested finding format

- **Title**
- **Severity and rationale**
- **Affected component**
- **Prerequisites**
- **Reproduction steps**
- **Observed result**
- **Expected result**
- **Impact**
- **Remediation**
- **Sanitized evidence**
- **Retest status**
