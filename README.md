# AI Threat Modelling Workshop Summary.

## Introduction
A 3 Hour threat modelling workshop took place to detail the runbook scenario of multiple AI attacks against the web-facing health care application Solaris Care Connect 360..

## Attendess
Care Connect Eng team, Product Managers, DevEx Engineers and the DevSecOps Team.

## Scope
4 Scenarios were run covering: (1) AI Generated External phishing email utilising admin credentials, (2) Attack against Machine Processes and the data lake, (3) SQL Injection attack and (4) Insider attack taking Quant algorithms.

## Methodology
All scenarios were run against the cyber attack killchain, utilising the Mitre Att&ack methods and STRIDE for control gap assessments. Culminating in identified risks. 

## Conclusion
A total of 4 high risks and 3 medium risks were found during the threat modelling workshop.

## Controls Required

- Regular security audits specifically targeting the Solaris Health 360 application to detect vulnerabilities and weaknesses in its security measures.
- Patch management to ensure the Solari Health 360 application and its underlying technologies are up-to-date and protected against known vulnerabilities.
- Comprehensive employee training on phishing awareness to educate users of the Solaris Health 360 application about the risks of phishing attacks and how to identify and report suspicious emails.
- Implementation of a Web Application Firewall (WAF) tailored to the Solari Health 360 application's traffic to monitor and filter incoming requests for malicious activity.
- Deployment of Multi-factor Authentication (MFA) to enhance authentication security and prevent unauthorized access to the Solari Health 360 application.
- Continuous network traffic monitoring to detect and respond to suspicious activity within the Solari Health 360 application's infrastructure.
- Implementation of Role-based Access Control (RBAC) within the Solari Health 360 application to limit access to sensitive health data and functionalities based on user roles and permissions.

# Threat Modelling Process Summary

```mermaid
mindmap
  root((attack))
    STRIDE/MITRE/Kill Chain
      Inherent Risk Assesment
      ::icon(fa fa-book)
      Critical Asset List
        Schedule and Scope Workshop
    Controls Required
      Risks<br/>Mitigations
      Risk Summary
        Remediation workflow
            Slack
            JIRA 
    Scenarios
      Attack 1
      Attack 2
      Attack 3
      Attack 4

