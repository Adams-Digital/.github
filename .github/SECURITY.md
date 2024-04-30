# Security Policy

## Reporting a vulnerability

***Please do not report security vulnerabilities through public GitHub issues.***

_Source_: <https://adamsdigital.com/security>

_Last updated_: April 27, 2024

Welcome to the Adams Digital Security Policy. As a leading hosting company, we prioritize the security of our networks, systems, and data, as well as the trust of our customers. We are committed to providing secure and reliable services and this policy outlines the measures we have put in place to protect our stakeholders.

## Our Commitment

At Adams Digital, we strive to:

- **Protect customer data** with the highest standards of security.
- **Uphold transparency** in our security practices.
- **Continuously improve** our security measures in response to evolving threats.
- **Comply** with industry standards and regulatory requirements.

## Data Protection

We utilize a range of technologies and practices to ensure the security of data on our platforms:

- **Encryption**: Data is encrypted both in transit and at rest using strong encryption protocols.
- **Access Control**: Strict access controls are enforced to ensure that only authorized personnel have access to sensitive information.
- **Regular Audits**: Our systems are audited regularly for security vulnerabilities and compliance with our security policies.

## Incident Response

Adams Digital has a dedicated incident response team that is ready to act in case of a security breach. Our response procedure includes:

- **Immediate Response**: Quick action to contain and mitigate any damage caused by a security breach.
- **Investigation**: Comprehensive investigation to understand the cause and scope of the breach.
- **Notification**: Affected parties are promptly notified in accordance with legal and regulatory requirements.
- **Review and Remediation**: Post-incident review of our practices and systems, implementing improvements to prevent future occurrences.

## Reporting a Vulnerability

We encourage responsible disclosure of any potential security vulnerabilities. For secure communication, we recommend using PGP encryption when sending sensitive information related to security vulnerabilities. Compatible email clients can automatically retrieve our public PGP key via the [Web Key Directory (WKD) protocol](https://wiki.gnupg.org/WKD), ensuring secure and confidential communication.

Here’s how you can use PGP encryption:

1. Ensure your email client supports automatic key retrieval via WKD, or configure your PGP tool to use WKD.
2. Compose your message and use your PGP tool to encrypt and sign it for `security@adamsdigital.com`.
3. Send the encrypted message to us at [security@adamsdigital.com](mailto:security@adamsdigital.com).

For clients that do not support WKD, you may manually retrieve our public PGP key from:

``` text
https://openpgpkey.adamsdigital.com/.well-known/openpgpkey/adamsdigital.com/hu/t5s8ztdbon8yzntexy6oz5y48etqsnbb
```

After downloading the key, you can encrypt and sign your message using a command like:

``` bash
gpg --encrypt --sign --armor -r security@adamsdigital.com yourmessage.txt
```

Please report suspected vulnerabilities to us at [security@adamsdigital.com](mailto:security@adamsdigital.com). We appreciate your help in keeping our services secure for everyone.

## Updates to Our Security Policy

This security policy may be updated periodically to reflect new regulatory requirements, changes in industry standards, or improvements to our security practices. We encourage you to review this policy regularly.

## Contact Us

For more information about our security practices, or if you have any questions, please contact us at:
**Email**: [security@adamsdigital.com](mailto:security@adamsdigital.com)

We are dedicated to maintaining the highest standard of security at Adams Digital and appreciate your partnership in helping us achieve this goal.
