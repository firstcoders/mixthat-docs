---
title: "Security of Your Audio Assets"
description: "Learn how Mix That secures audio assets, including encryption, access controls, and options for business customers."
summary: "An overview of Mix That's security practices for protecting your audio files and data."
date: 2025-03-01T16:04:48+02:00
lastmod: 2025-06-12T00:00:00+02:00
draft: false
weight: 300
toc: true
seo:
  title: "Audio Asset Security | Mix That"
  description: "Discover how Mix That protects your audio assets with encryption, secure access, and business-ready deployment options."
  canonical: "/docs/reference/security/"
  robots: "index, follow"
---

## How We Secure Your Audio Assets

At Mix That, the security of your audio files and personal data is a core design concern. We use encryption for data at rest and in transit, robust authentication, and strict access controls to protect content throughout upload, storage, sharing, and playback.

For hosted customers, Mix That runs on a serverless AWS architecture designed for high availability and low operational overhead. For organizations that need more direct control over infrastructure and governance, a self-hosted path is also being prepared.

## Enterprise-Grade Security Experience

Mix That is developed by [Firstcoders](https://www.firstcoders.co.uk), a software consultancy with experience delivering software for large music companies. That background informs how the platform approaches asset protection, access control, and commercial deployment requirements.

The goal is not to imitate a large enterprise software vendor. The goal is to provide a reliable platform with a clear security model, and a self-hosted option for organizations that want to mitigate supplier risk through infrastructure ownership and internal control.

## Authentication & Account Security

Mix That uses a robust, cloud-based authentication service that provides secure user account management and authentication. This system handles user registration, login, password management, and session security with industry-standard protocols.

Key authentication features include:

- **Secure Password Requirements:** Strong password policies to protect your account
- **Encrypted Session Management:** All user sessions are encrypted and securely managed
- **Password Reset Security:** Secure password recovery processes via email verification
- **Account Verification:** Email-based account verification for new registrations

**Note:** Multi-factor authentication (MFA) is not currently enabled but may be added in future updates to further enhance account security. Let us know if this is something you desire!

## Asset Protection

- **Access Controls:** Only authorized users can access your private tracks. Public tracks are only accessible via their unique URLs.
- **Secure Asset Delivery:** We protect your audio files using CloudFront signed URLs combined with JWT (JSON Web Tokens) authentication. All encryption keys use a minimum of 256-bit encryption to ensure robust security for asset access.
- **Monitoring:** We continuously monitor our systems for suspicious activity and regularly update our security protocols.

## Hosted vs Self-Hosted Considerations

Hosted Mix That is a strong fit for teams that want a reliable service without managing infrastructure directly.

Self-hosted Mix That is intended for organizations that need more direct control over deployment, access policies, procurement review, or long-term continuity planning.

For organizations evaluating commercial or self-hosted use, we can discuss architecture, deployment controls, and security review requirements as part of the business planning process.

If you have questions about our security practices or need more information, please [contact us](/docs/other/contact-and-support).

