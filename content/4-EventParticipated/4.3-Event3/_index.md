---
title: "Event 3"
date: 2026-07-13
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---

# Event Report: FCAJ — Agentic AI Build Week: Demo & Pitch Day

**Date:** July 25, 2026  
**Location:** AWS Vietnam Office  
**Role:** Attendee  

---

## Summary and Key Activities

This was the closing day of the FCAJ Agentic AI Build Week — a hackathon where teams built agentic AI products on the AWS platform and pitched them to a packed auditorium. The event format was incredibly straightforward and practical: each team took the stage, presented their chosen problem, demonstrated exactly what they had built during the week, and then entered a Q&A session.

**Key activities of the event:**

*   **Event Opening:** Kicking off the demo day at the AWS office with about 100 tech enthusiasts in attendance.
![Opening of the demo day of Agentic AI Build Week](/images/4-EventParticipated/event3-1.jpg)
*   **Presentation by 3KA (The Hackathon Journey):** Provided a genuine perspective on working under time pressure, told through an emotional arc: doubt → engagement → pride.
*   **Presentation by One Team (AI Conversational Ordering):** Showcased a solution allowing customers to place orders directly within the chat app they are already using, eliminating the need to install a separate application.
![One Team presenting "Ordering Without Leaving the Chat"](/images/4-EventParticipated/event3-3.jpg)
*   **Presentation by Plan V (Solution Architect native app):** Unveiled an agent that solves a real bottleneck for solution architects. This agent can receive requirements (in natural or structured language), draft architectures, generate draw.io diagrams, output infrastructure as code (IaC), and estimate costs.
*   **Presentation by Signal Scout (Early detection of corporate strategy shifts):** Introduced a solution that tracks public signals to identify when a company is pivoting before any official announcement. The solution integrates AWS, LangFuse, TinyFish, Apify, and delivers insights via a self-service dashboard.
![A team presenting the value creation and distribution canvas](/images/4-EventParticipated/event3-2.jpg)

---

## Outcomes and Key Takeaways

### 1. Breaking down and planning real-world AWS costs
* Observing Signal Scout's cost breakdown helped me realize the importance of splitting costs by specific services (Bedrock tokens, AgentCore runtime, WAF, DynamoDB, Lambda, etc.).
* I learned how to estimate three benchmark figures (minimum, average, and maximum monthly costs) instead of relying on a single number. This allows for accurate predictions of which service component will dominate the bill or is likely to "break" when traffic scales.

### 2. Expanding the mindset on "Agentic AI" architecture
* Plan V's project completely changed how I envision using LLMs on the cloud. Instead of merely using AI as a simple text classification API call, "agentic" represents the ability to connect an entire business process (from reading documents to exporting infrastructure code) using building blocks like Bedrock AgentCore.

### 3. Optimizing the User Touchpoint
* One Team's approach offered an immediate lesson that can be applied to our team's current project: instead of building an entirely new interface, bring the product to where the users already are.
* This reinforces the direction of developing our team's content moderation service as an "API-first" solution, seamlessly integrated into existing platforms rather than operating solely as a standalone demo page.

### 4. The value of authenticity in the development process
* The sharing from 3KA provided an incredibly relatable view of the "middle part" of product building — the phase where the code isn't running yet and uncertainty is high. This honesty served as a necessary counterbalance to the polished demos, accurately reflecting the real-life work of engineers.

> "The Agentic AI Demo Day was not just a showcase of programming skills or cloud architecture, but a profound, practical lesson in product development mindset: from detailed cost planning and designing fully automated agentic AI workflows, to truly understanding the end user's actual touchpoints."