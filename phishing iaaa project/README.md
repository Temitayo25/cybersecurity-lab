# Phishing Simulation, Credential Misuse & Identity Protection Using the IAAA Model

## Project Overview

This project documents a **controlled phishing and social-engineering simulation** carried out during my cybersecurity training at **Metro Innovation Hub**.

The goal was to demonstrate how phishing can compromise a user's digital identity and how the **IAAA security model** can support detection, limitation, and investigation of suspicious activity.

> **IAAA:** Identification, Authentication, Authorisation, and Accountability.

## Objectives

- Simulate a realistic phishing email in an authorized lab environment.
- Demonstrate how a fake login portal can be used to capture test credentials.
- Show the risks associated with credential misuse.
- Demonstrate how authorization controls can limit the impact of compromised credentials.
- Examine logging and monitoring for investigation and accountability.
- Recommend practical controls for reducing phishing risk.

## Tools Used

- **GoPhish** — phishing-campaign simulation and tracking
- **Kali Linux** — security testing environment
- **Windows Event Viewer** — log review and investigation

## Methodology

### 1. Phishing Campaign Preparation

A simulated corporate IT email was created to imitate a request such as **Your Microsoft Account Login**. The email contained a link to a fake login page hosted through the GoPhish campaign.

### 2. Campaign Launch

The campaign was sent only to approved test users in a controlled environment. The following components were configured:

- Sending profile
- Email template
- Landing page
- Test recipient list
- Campaign tracking

### 3. Credential-Misuse Demonstration

The exercise demonstrated the potential danger of captured test credentials by attempting to use them in the controlled environment. No real credentials or unauthorized accounts were targeted.

### 4. Defense and Investigation

Windows Event Viewer was used to review relevant activity and demonstrate how logging can support detection, investigation, accountability, and incident response.

## IAAA Analysis

| IAAA Component | Role in the Exercise |
|---|---|
| Identification | The phishing exercise targeted the user's digital identity |
| Authentication | The attack demonstrated how stolen passwords can undermine password-based authentication |
| Authorisation | Access restrictions helped limit what a compromised account could do |
| Accountability | Logs provided an auditable trail for investigation |

## Key Findings

- Phishing can trick users into disclosing sensitive identity information.
- Password compromise can create a serious security risk.
- Least-privilege authorization can reduce the potential impact of compromised credentials.
- Logging and monitoring are important for detecting and investigating suspicious activity.
- Security awareness is an important part of phishing defense.

## Recommendations

1. Conduct regular security-awareness training.
2. Implement multi-factor authentication (MFA).
3. Enforce least-privilege access.
4. Review and harden authorization policies.
5. Collect and monitor important authentication and authorization events.
6. Forward critical logs to a centralized monitoring or SIEM platform.
7. Perform controlled phishing simulations to measure user awareness.

## Ethical and Safety Considerations

This project was performed for educational and defensive purposes in a controlled environment.

- Only approved test users and systems should be involved.
- Do not collect real passwords or sensitive information.
- Do not reuse phishing pages against real users without explicit written authorization.
- Remove or redact credentials, SMTP passwords, email addresses, tokens, and other secrets before publishing evidence.
- Screenshots should be reviewed carefully before being uploaded.

## Evidence

Add sanitized screenshots and supporting files to the `screenshots/` or `evidence/` folders.

Recommended evidence includes:

- Redacted GoPhish dashboard
- Redacted email template
- Redacted landing-page configuration
- Sample phishing email
- Fake login page with no real credentials
- Windows Event Viewer evidence
- Campaign results with personal information removed

## Project Status

- [x] Phishing simulation documented
- [x] GoPhish and Kali Linux identified
- [x] IAAA analysis documented
- [x] Defense and logging phase documented
- [ ] Add sanitized screenshots
- [ ] Add a short demonstration video, if permitted
- [ ] Add final observations and lessons learned

## Disclaimer

This repository is for educational purposes only. All security testing must be authorized, scoped, and conducted in a controlled environment.
