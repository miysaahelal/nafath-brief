Version: NAFATH-V1
Track: Networking
## Overview
The Single Sign-On (SSO) system allows citizens to access multiple government services using one account through a mobile app and website. Software is used to develop a secure login system that integrates different government services. Artificial Intelligence (AI) helps detect unusual login patterns and potential fraud. Mobile technology provides a user-friendly application with multi-factor authentication and security notifications. Networking ensures fast, reliable, and secure connections between users and government servers. Cybersecurity protects citizens’ accounts and personal information through encryption, strong authentication, and continuous monitoring. Data management ensures that user information is accurate, private, and accessible only to authorized users. In conclusion, integrating these six IT fields will help create a secure, reliable, and accessible SSO system that improves citizens’ trust in digital government services.
## Software
OAuth 2.0 and OpenID Connect (OIDC) serve different purposes. OAuth 2.0 is designed for authorization and delegated access to protected resources, allowing applications to access APIs with the user’s permission. OpenID Connect (OIDC) builds on OAuth 2.0 and is designed for user authentication and login. It provides an ID token containing information about the user. In summary, OAuth 2.0 answers “What can the application access?”, while OIDC answers “Who is the user?”
Resource: OAuth 2.0 and OpenID Connect overview | Okta Developer - 
https://developer.okta.com/docs/concepts/oauth-openid/ 
## AI
Using NIST’s AI Risk Management Framework, the authority must assess accuracy, false positives and false negatives, data privacy, algorithmic bias, cybersecurity vulnerabilities, and model reliability. It should ensure decisions are explainable, establish clear accountability and human oversight, and test the model against realistic login scenarios. The authority must also monitor performance, detect model drift, and update safeguards as threats evolve. Strong governance, secure data handling, continuous monitoring, and compliance with relevant regulations are essential before deployment to protect users and prevent unauthorized access.
Resource: 5 Steps to Modernizing Network Security in an AI-Driven Era - https://www.forescout.com/5-steps-to-modernizing-network-security-in-an-ai-driven-era/
## Mobile
Android’s runtime permission model limits the login app to accessing its own sandbox by default. Access to sensitive data or device resources requires specific permissions, preventing unauthorized access. The app must request dangerous permissions at runtime when the user initiates a feature that needs them, rather than asking unnecessarily at startup. Before requesting permission, the app should explain why access is needed. Users can grant or deny requests, and the app must respect their decisions and continue functioning where possible.

Resource: Request runtime permissions - https://developer.android.com/training/permissions/requesting
## Networking
DNS over HTTPS (DoH) is a protocol that encrypts DNS queries using HTTPS, protecting users’ browsing requests from being easily monitored or manipulated. It helps prevent internet service providers and network observers from seeing which domains users request, and reduces DNS spoofing and redirection attacks. However, DoH does not hide all browsing activity, encrypt website traffic by itself, or prevent websites from tracking users. The chosen DNS provider can still see queries and may retain logs.

Resource: What is DNS over HTTPS (DoH)? - https://www.ssl.com/faqs/what-is-dns-over-https-doh/
## Cybersecurity
A phishing-resistant authentication method cryptographically binds credentials to the legitimate website, so they cannot be reused on a fake domain. It prevents attackers from relaying stolen login codes through phishing proxies. Qualifying methods include FIDO2/WebAuthn passkeys and security keys, especially device-bound passkeys, and PIV smart cards. Non-qualifying methods include SMS codes, email one-time passwords, authenticator-app codes (TOTP), and push-notification approvals, because attackers can intercept or relay them. Organizations should also secure recovery options and avoid weaker fallback methods whenever possible.

Resource: What Is Phishing-Resistant MFA? - https://www.zscaler.com/zpedia/phishing-resistant-mfa
## Data
Under Oman’s Personal Data Protection Law, the authority must collect and process citizens’ personal data transparently and obtain explicit consent, unless a legal exception applies. It must inform individuals about collection purposes, data sources, processing methods, and their rights. The authority must implement appropriate technical and procedural safeguards, assess risks, maintain confidentiality, and appoint a data protection officer. It must notify the Ministry and affected individuals of personal data breaches and respect individuals’ rights to access, correct, transfer, or request erasure of their data.

Resource: Royal Decree 6/2022 Issuing the Personal Data Protection Law - https://decree.om/2022/rd20220006/
## Misconception in My Track
One common wrong belief about DNS over HTTPS (DoH) is that it makes users completely anonymous online. In reality, DoH encrypts DNS queries, making it harder for internet service providers and network observers to see which domains users request. However, it does not guarantee complete anonymity, hide all browsing activity, or prevent websites from tracking users. The DNS provider can still see users’ queries and may keep logs. The relevant section to support this correction is the discussion of DoH’s privacy limitations in the resource.

**Resource:** [What is DNS over HTTPS (DoH)? – SSL.com](https://www.ssl.com/faqs/what-is-dns-over-https-doh/)
## Open Question
One thing I would like to learn next is how to use reliable sources to verify information, identify common misconceptions, and distinguish facts from false claims. This would help me improve my research skills, think critically, and make better-informed decisions in my studies and daily life.
