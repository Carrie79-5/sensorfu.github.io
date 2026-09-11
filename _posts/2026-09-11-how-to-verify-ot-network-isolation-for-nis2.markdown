---
layout: post
title: "How to Verify OT Network Isolation for NIS2"
date: 2026-09-11 09:30:00 +0300
category: article
tags:
- article
image: /assets/img/articles/ot-network-isolation.jpg
image_alt: Verify OT Network Isolation
---

Network isolation and segmentation are fundamental to protecting critical operations, particularly where IT networks intersect with high-value OT environments. Organisations invest heavily in firewalls, VLANs, access controls and air-gapped architectures to create strong, trusted boundaries.

But a boundary is only effective if it continues to hold.

Networks are constantly changing. Firewall rules are updated, configurations evolve, firmware is upgraded, new systems are connected, and third-party access is introduced or modified. Yet many organisations only validate their network isolation through point-in-time audits, with the assumption that once a boundary has been proven secure, it will remain that way.

## Prove that network boundaries protecting OT, ICS and critical infrastructure remain effective as environments change.

Security teams already have plenty of dashboards. They monitor alerts, assets, configurations, vulnerabilities and suspicious activity. But knowing what might be wrong is only part of the challenge. SensorFu Beacon takes a different approach. Rather than simply monitoring the network, it actively tests whether your network isolation is working as intended.
Beacon is placed inside an isolated network segment and continuously tests whether it can reach Beacon Home, which is located outside the isolated segment, either in another network segment or on the Internet. It uses multiple escape methods to test for possible paths across the network boundary.
If SensorFu Beacon successfully reaches Home, Beacon Home records an observation containing the information collected during the test and sends an alert. Observations can be viewed in the Beacon Home dashboard, while alerts can be integrated directly into your SOC through the API or Webhook.

![Dashboard](/assets/img/articles/dashboard.png)

Organisations may feel their firewall rules look correct, a VLAN may be properly configured or an access control may appear exactly as intended. But if a connection can still be established outside the intended network segment, the network is not isolated. We find this to be more common than many organisations realise.

More than 80% of SensorFu client networks have found that their network segmentation was not as isolated as they believed. Hidden connectivity paths, misconfigurations and unexpected access can undermine even carefully designed network boundaries. You can read about our most common findings [here.](https://sensorfu.com/article/2026/07/02/beacon-escape-testing-and-common-leaks.html)

But compliance isn’t just about having the right policies, controls and documentation in place. Organisations also need to demonstrate that those controls are working continuously, in the environments they are protecting.

Continuous verification can help organisations meet regulatory, sector-specific and contractual requirements, including NIS2 Article 21, ISO 27001, and cybersecurity requirements for TSOs and DSOs. In Europe, this also includes the EU Network Code on Cybersecurity (NCCS), which sets sector-specific cybersecurity requirements for the electricity sector.

With SensorFu, compliance becomes part of the continuous security process rather than an annual exercise. Instead of relying solely on periodic audits or documentation that describes how a network should be protected, security teams can continuously validate critical controls across their OT environments and build an ongoing body of evidence that those controls are working as intended.

Because when it comes to protecting critical OT environments, you shouldn’t have to assume your network isolation is secure. You should be able to prove it.




