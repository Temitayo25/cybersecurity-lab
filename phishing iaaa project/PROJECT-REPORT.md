# Project Report

## Phishing Simulation, Credential Misuse & Identity Protection Using the IAAA Model

### Background

This report documents a controlled simulation designed to illustrate the risks of phishing and social engineering and to examine the role of the IAAA model in reducing those risks.

The simulation involved creating a fake phishing campaign, capturing test credentials, demonstrating the potential misuse of those credentials, and reviewing logging and accountability measures.

### Tools Used

- GoPhish
- Kali Linux
- Windows Event Viewer

### Phishing Simulation

A phishing email was created to resemble a corporate IT request. The message included a link to a simulated login portal hosted through GoPhish and was sent to approved test users.

The campaign included a sending profile, email template, landing page, and test recipient list.

### Credential-Misuse Demonstration

The exercise demonstrated the potential danger of captured test credentials in the controlled environment. The purpose was to show how phishing can compromise a user's digital identity and create an opportunity for unauthorized access.

### Defense Phase

Windows Event Viewer was used to examine logging and monitoring evidence. The logs demonstrated how security teams can investigate suspicious activity and establish an auditable trail of events.

### IAAA Discussion

#### Identification and Authentication

The phishing exercise showed how an attacker can target a user's identity and exploit dependence on password-based authentication.

#### Authorisation

Authorization controls helped restrict the activities available to the compromised test account and reduced the potential impact of the incident.

#### Accountability

Logs supported investigation by providing a record of relevant actions and events.

### Recommendations

1. Provide mandatory security-awareness training focused on phishing.
2. Implement multi-factor authentication.
3. Enforce least-privilege authorization.
4. Review authorization policies regularly.
5. Ensure critical authentication and authorization events are logged and monitored.

### Conclusion

The simulation demonstrated the practical risks of phishing and the importance of combining user awareness, strong authentication, least-privilege authorization, and reliable logging. These controls work together to reduce the likelihood and impact of identity-related attacks.
