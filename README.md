# Intune HealthCheck

Intune HealthCheck assesses a Microsoft Intune and Entra ID tenant that manages Windows devices, and writes two Word reports on the computer that runs it:

- **Executive report**, for leadership: the score, the maturity level, what matters most, quick wins and a 90 day plan.
- **Technical findings**, for engineers: every finding with its evidence, the business impact, the remediation steps and what the check could not see.

Each report can also create a PDF version.

The tool is free. It has no licence, no vendor server and no telemetry. It reads your tenant through Microsoft Graph with an app registration that you create and own, using read-only permissions, and evaluates around 225 rules in memory on your workstation. Tenant data is never written to disk and never leaves your environment.

## Documentation

Check out the Wiki page on how to run the rool

## Releases

Check out the Releases page to download the most up to date version of the tool
