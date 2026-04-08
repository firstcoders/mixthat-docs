---
title: "Self-Hosting"
description: "Guide for organizations evaluating a self-hosted Mix That deployment."
summary: "Overview of self-hosted Mix That for organizations that need infrastructure control, continuity, or internal governance."
date: 2025-03-01T16:04:48+02:00
lastmod: 2025-06-11T00:00:00+02:00
weight: 303
toc: true
seo:
  title: "Self-Hosting Mix That"
  description: "Learn how to deploy and operate your own Mix That instance in AWS."
  canonical: "/docs/reference/self-hosted/"
  robots: "index, follow"
---

Mix That offers a self-hosted path for organizations that want to run the platform in their own AWS environment.

This is primarily intended for teams that need stronger control over infrastructure, procurement, continuity, data handling, or internal governance than a hosted service can provide.

Mix That uses a serverless AWS architecture, which keeps the deployment model straightforward while still giving your team ownership of the environment.

A self-hosted Mix That instance provides a solid foundation for audio asset management and delivery, with core features including:

- **Track & Metadata Storage:** Store tracks along with rich metadata. Each track can contain multiple audio stems, supporting complex, multi-track projects.
- **Audio Transcoding:** Automatically transcodes uploaded audio into streaming-ready formats, optimized for use with our advanced stem player.
- **Secure CDN Delivery:** Delivers audio assets securely and efficiently over a preconfigured Content Delivery Network (CDN), ensuring fast and reliable access worldwide.
- **Mixing & Downloading:** Enables users to mix audio stems directly in the platform and download high-quality mixes on demand.

## Why Choose Self-Hosted

- Your organization keeps operational ownership of the platform
- The deployment sits inside your AWS account rather than ours
- The model reduces supplier lock-in and gives internal stakeholders a clearer continuity story
- It is often the better fit for companies with stricter security review, procurement, or governance requirements

For commercial terms or deployment discussions, see [Business Plans](/docs/plans/business/) or [contact us]({{< relref "/docs/other/contact-and-support" >}}).
