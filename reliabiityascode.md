---
authors:
- Denise Nzeyimana
tags:
- RaC
- Reliability as Code
date: 2015-04-23T12:21:50.000Z
title: "The Fundamentals of RaC Reliability as Code"
---

RaC Reliability as Code 

What is Reliability as code? As it implies, it's the idea that your code can only be as good as it is reliable and thoroughly composed. After all, what is code if it's not reliable? 

Reliability as Code (or RaC as I’ll refer to it) is a multi-disciplinary approach that integrates the concept of reliability and durability as a best practice measure into source code in order to design the highest quality infrastructure.

I’m going to break down the 4 fundamental factors that makeup RaC.

Reliability KPI’s
1. Detection and Discovery
	Detection and discovery are imperative strategies to RaC because without them we wouldn’t be able to identify any current and/or future underlying issues or bugs within our code. Detection and discovery can be packaged in many forms, but some of the most common tools we see are monitoring tools.

2. Mean time to Detect (MTTD) 
	In terms of RaC, monitoring is important because it acts as a cardiologist to your code. Your cardiologist (monitoring/discovering & detection and discovery service) can inform you on what you need to do in order to prevent failures and maintain your (code) health in order to live a longevous life. Your ability to detect and address an issue does have a direct correlation to your code health and quality. 
3. Mean Time to Recovery (MTTR)
	Recovery resolution is also an important factor because a prompt notification system can ensure challenges and issues are addressed in a timely manner. Whether that means implementing cost measure parameters or resolution source usage metric notifications, recovery resolution is imperative to RaC. Utilizing tools such as SQS, SMS, or SNS (to name a few) can ensure a strong sense of reliability for your code.
4. Observability
	What’s the point of having all these fancy measuring tools if you don’t have one homogenous (or cohesive) way of viewing it? That’s where the concept of observability in RaC comes in. Observability in RaC (particularly when it comes to cloud and dev ops)  can provide a granular view of all the resources being utilized and an in-depth view of how to diagnose problems that might exist in your code. This can include the ability to scale quickly, which can better help you or you and your team formulate the best strategy to address and tackle any issue you may come across.

All in all, when implementing Reliability as Code you and your team need to do their due diligence in order to ensure your team not only produces the best code but also lays down the proper foundation infra structurally and culturally to have the most successful projects.
