---
theme: "@xebia/slidev-theme-xebia"
transition: "fade"
addons:
  - slidev-component-progress
  - "@xebia/slidev-addon-components-common"
  - slidev-addon-qrcode
# disabled pdf downloading in SPA build, can also be a custom url
download: false
browserExporter: true
# disable slide recording, can be boolean, 'dev' or 'build'
record: false
# disable editor for slides editing, can be boolean, 'dev' or 'build'
editor: true
# take snapshot for each slide in the overview
overviewSnapshots: false
# background glow animation
glowEnabled: true
###### slides start ######
# the routeAlias must be named like the entry md file
layout: cover
background: /pilot-large.jpg
description: "Power Platform Training Kick-off: PL-900 & Introduction"
hideInToc: true
routeAlias: powerPlatformPL900
---

# Power Platform Training Kick-off

## PL-900 & Introduction to the Power Platform

---
title: Speaker
layout: intro
src: special-slides/speaker.md
---

---
title: Welcome to Power Platform
---

# Welcome to Power Platform

<v-clicks>

- **Your journey begins here** - From zero to citizen developer
- **PL-900 certification** - Microsoft Power Platform Fundamentals
- **Real-world skills** - Build apps, automate processes, analyze data
- **Low-code/no-code** - Democratizing application development

</v-clicks>

<!-- 

Welcome to the Power Platform training kick-off! This course is designed to give you a comprehensive introduction to Microsoft's Power Platform and prepare you for the PL-900 certification exam.

Whether you're new to low-code development or looking to formalize your knowledge, this training will equip you with the fundamentals you need to start building business solutions.

-->

---
title: Agenda
layout: default
---

# Agenda

<Toc minDepth="1" maxDepth="1" />

---
title: What is Power Platform?
---

# What is Power Platform?

<v-clicks>

- **Unified platform** for business solutions
- **Four core products**:
  - Power Apps - Build custom applications
  - Power Automate - Automate workflows
  - Power BI - Analyze and visualize data
  - Power Pages - Create external websites
- **Powered by Dataverse** - Common data platform
- **Microsoft 365 & Dynamics 365 integration**

</v-clicks>

<!-- 

The Power Platform is Microsoft's low-code platform that enables anyone to create business solutions. It consists of four main products that work together seamlessly.

Power Apps lets you build custom applications without extensive coding knowledge. Power Automate helps you automate repetitive tasks and business processes. Power BI provides powerful data analytics and visualization capabilities. And Power Pages allows you to create external-facing websites.

All of these are built on top of Dataverse, which provides a common data platform and integrates deeply with Microsoft 365 and Dynamics 365.

-->

---
title: Why Learn Power Platform?
---

# Why Learn Power Platform?

<div class="grid grid-cols-2 gap-8">
<div>

## Business Value

<v-clicks>

- Rapid application development
- Reduce backlog & IT dependencies
- Democratize innovation
- Lower total cost of ownership
- Faster time to market

</v-clicks>

</div>
<div>

## Career Benefits

<v-clicks>

- High demand skill set
- Become a citizen developer
- Bridge business & IT
- Microsoft certification path
- Cross-industry applicability

</v-clicks>

</div>
</div>

<!-- 

Learning Power Platform brings value from both business and career perspectives.

From a business standpoint, it enables rapid development, reduces dependency on IT departments, and lowers costs by empowering non-developers to build solutions.

From a career perspective, Power Platform skills are in high demand. You can become a citizen developer, bridge the gap between business needs and technical implementation, and earn valuable Microsoft certifications that are recognized across industries.

-->

---
title: PL-900 Certification Overview
---

# PL-900 Certification Overview

## Microsoft Power Platform Fundamentals

<v-clicks>

- **Entry-level certification** - No prerequisites required
- **Exam duration**: 60 minutes
- **Question types**: Multiple choice, case studies, drag-and-drop
- **Passing score**: 700 out of 1000
- **Validates**: Understanding of Power Platform capabilities and business value

</v-clicks>

<!-- 

The PL-900 certification is your first step into the Power Platform ecosystem. It's an entry-level exam that doesn't require any prerequisites, making it perfect for beginners.

The exam is 60 minutes long and includes various question types like multiple choice, case studies, and interactive scenarios. You need a score of 700 out of 1000 to pass.

This certification validates that you understand the capabilities of Power Platform and can articulate its business value to stakeholders.

-->

---
title: PL-900 Exam Domains
---

# PL-900 Exam Domains

<div class="grid grid-cols-2 gap-4">
<div>

## Describe Power Platform (20-25%)

<v-clicks>

- Business value
- Core components
- Dataverse
- Connectors
- AI Builder

</v-clicks>

</div>
<div>

## Describe Power Apps (25-30%)

<v-clicks>

- Canvas apps
- Model-driven apps
- Power Pages
- Use cases

</v-clicks>

</div>
</div>

<div class="grid grid-cols-2 gap-4 mt-4">
<div>

## Describe Power Automate (25-30%)

<v-clicks>

- Cloud flows
- Desktop flows
- Process advisor
- Business process flows

</v-clicks>

</div>
<div>

## Describe Power BI (10-15%)

<v-clicks>

- Reports & dashboards
- Data visualization
- Integration options

</v-clicks>

</div>
</div>

<!-- 

The PL-900 exam covers four main domains:

1. Describing the Power Platform itself - understanding the business value, core components, Dataverse, connectors, and AI Builder capabilities.

2. Power Apps - including canvas apps, model-driven apps, Power Pages, and appropriate use cases for each.

3. Power Automate - covering different types of flows: cloud flows for automation, desktop flows for RPA, process advisor for process mining, and business process flows for guided experiences.

4. Power BI - understanding reports, dashboards, data visualization, and how Power BI integrates with the rest of the platform.

-->

---
title: Training Structure
---

# Training Structure

<v-clicks>

- **Module-based learning** - Follow PL-900 exam objectives
- **Hands-on labs** - Build real solutions as you learn
- **Best practices** - Learn from real-world scenarios
- **Q&A sessions** - Interactive discussions
- **Practice exercises** - Reinforce your knowledge
- **Exam preparation** - Tips and resources for success

</v-clicks>

<!-- 

Our training is structured to align with the PL-900 exam objectives, but we go beyond just exam prep.

Each module includes hands-on labs where you'll build real solutions. We'll cover best practices from real-world implementations, have interactive Q&A sessions, and provide practice exercises to reinforce your learning.

By the end of this training, you'll be ready to take the PL-900 exam and start building Power Platform solutions in your organization.

-->

---
title: Power Apps Deep Dive
---

# Power Apps Deep Dive

<div class="grid grid-cols-2 gap-8">
<div>

## Canvas Apps

<v-clicks>

- Drag-and-drop interface
- Pixel-perfect layouts
- Start from blank or template
- Mobile-first design
- Custom business logic

</v-clicks>

</div>
<div>

## Model-Driven Apps

<v-clicks>

- Data-driven approach
- Responsive & adaptive
- Built on Dataverse
- Business process automation
- Complex forms & views

</v-clicks>

</div>
</div>

<!-- 

Let's dive into the two main types of Power Apps.

Canvas apps give you complete control over the user experience. You use a drag-and-drop interface to create pixel-perfect layouts. They're great for mobile-first scenarios and when you need custom business logic.

Model-driven apps take a different approach - they're data-driven and automatically generate responsive interfaces based on your data model. They're built on top of Dataverse and are ideal for complex business processes that require sophisticated forms, views, and business rules.

-->

---
title: Power Automate Capabilities
---

# Power Automate Capabilities

<v-clicks>

- **Cloud Flows** - Automate tasks across apps and services
- **Desktop Flows (RPA)** - Automate legacy desktop applications
- **Business Process Flows** - Guide users through defined processes
- **Process Advisor** - Discover and optimize processes
- **Approvals** - Built-in approval workflows
- **AI Builder integration** - Add intelligence to your flows

</v-clicks>

<!-- 

Power Automate is incredibly versatile when it comes to automation.

Cloud flows let you automate tasks across hundreds of apps and services. Desktop flows bring RPA capabilities to automate legacy applications that don't have APIs.

Business process flows guide users through standardized processes in your model-driven apps. Process advisor helps you discover inefficiencies and optimize your processes.

Built-in approvals make it easy to create approval workflows, and AI Builder integration lets you add intelligence like form processing, object detection, and prediction to your automation.

-->

---
title: Power BI Essentials
---

# Power BI Essentials

<div class="grid grid-cols-2 gap-8">
<div>

## Core Concepts

<v-clicks>

- Data modeling
- DAX formulas
- Interactive visualizations
- Reports vs. Dashboards
- Power BI Desktop vs. Service

</v-clicks>

</div>
<div>

## Power Platform Integration

<v-clicks>

- Embed in Power Apps
- Trigger flows from reports
- Dataverse as data source
- Shared workspaces
- Unified security model

</v-clicks>

</div>
</div>

<!-- 

Power BI is the analytics pillar of the Power Platform.

You'll learn core concepts like data modeling, DAX formulas for calculations, creating interactive visualizations, and the difference between reports and dashboards. We'll also cover when to use Power BI Desktop versus the Power BI Service.

The real power comes from integration with the rest of the platform. You can embed Power BI reports in Power Apps, trigger Power Automate flows from report interactions, use Dataverse as a data source, and benefit from shared workspaces and unified security across the platform.

-->

---
title: Dataverse - The Foundation
---

# Dataverse - The Foundation

<v-clicks>

- **Unified data platform** - Single source of truth
- **Built-in tables** - Pre-configured entities for common scenarios
- **Custom tables** - Define your own data structures
- **Relationships** - Connect data across tables
- **Business rules** - Enforce data quality
- **Security** - Row-level and column-level security
- **Integration** - Connect to external data sources

</v-clicks>

<!-- 

Dataverse is the foundational data platform that powers the entire Power Platform ecosystem.

It provides a unified data platform that serves as a single source of truth for your organization. You get built-in tables for common business scenarios like contacts, accounts, and activities.

You can also create custom tables to match your specific business needs, define relationships between tables, and enforce business rules to maintain data quality.

Dataverse includes robust security features with row-level and column-level security controls. And it can integrate with external data sources through connectors.

-->

---
title: Connectors & Integration
---

# Connectors & Integration

<v-clicks>

- **900+ connectors** - Connect to virtually any service
- **Standard connectors** - Included in most licenses
- **Premium connectors** - Advanced services (SQL Server, SAP, etc.)
- **Custom connectors** - Build your own integrations
- **Triggers & actions** - Event-driven automation
- **Common Data Service** - Native integration with Dataverse

</v-clicks>

<!-- 

One of Power Platform's greatest strengths is its connectivity.

With over 900 pre-built connectors, you can connect to virtually any service - from Microsoft 365 and Azure to third-party services like Salesforce, Twitter, and Dropbox.

Standard connectors are included in most licenses, while premium connectors for enterprise systems like SQL Server or SAP require additional licensing.

You can even build custom connectors for proprietary systems. All connectors provide triggers to start automation and actions to perform operations.

-->

---
title: AI Builder Overview
---

# AI Builder Overview

## Add Intelligence to Your Apps and Flows

<div class="grid grid-cols-2 gap-8">
<div>

## Pre-built Models

<v-clicks>

- Business card reader
- Receipt processing
- Text recognition (OCR)
- Sentiment analysis
- Language detection
- Key phrase extraction

</v-clicks>

</div>
<div>

## Custom Models

<v-clicks>

- Object detection
- Form processing
- Prediction
- Category classification
- Entity extraction

</v-clicks>

</div>
</div>

<!-- 

AI Builder brings artificial intelligence capabilities to Power Platform without requiring data science expertise.

Pre-built models are ready to use out of the box for common scenarios like reading business cards, processing receipts, extracting text from images, analyzing sentiment, detecting language, and extracting key phrases.

For more specific needs, you can train custom models for object detection in images, processing custom forms, predicting outcomes based on historical data, classifying text into categories, or extracting specific entities from text.

All of this intelligence can be easily integrated into your Power Apps and Power Automate flows.

-->

---
title: Licensing Overview
---

# Licensing Overview

<v-clicks>

- **Per-user plans** - Best for power users
  - Power Apps per user
  - Power Automate per user
  - Power BI Pro & Premium per user
- **Per-app plans** - Cost-effective for specific scenarios
- **Included capabilities** - Office 365 and Dynamics 365
- **Premium connectors** - Require premium licenses
- **Capacity-based** - Pay As You Go, Reserved Capacity

</v-clicks>

<!-- 

Understanding licensing is important for the PL-900 exam and real-world implementations.

Per-user plans are best when someone will use multiple apps or build solutions. Power Apps, Power Automate, and Power BI each have per-user options.

Per-app plans are more cost-effective when users only need access to specific applications.

Many capabilities are already included in Office 365 and Dynamics 365 licenses, so check what your organization already has.

Premium connectors and advanced features require premium licenses. There are also capacity-based options for high-volume scenarios.

-->

---
title: Governance & Administration
---

# Governance & Administration

<v-clicks>

- **Environments** - Isolate and manage resources
- **Data Loss Prevention (DLP)** - Control connector usage
- **Center of Excellence (CoE) Toolkit** - Monitor and govern at scale
- **Application Lifecycle Management (ALM)** - Dev, Test, Production
- **Security roles** - Control access and permissions
- **Audit logs** - Track changes and usage

</v-clicks>

<!-- 

As Power Platform adoption grows, governance becomes critical.

Environments let you isolate and manage resources for different teams or purposes. Data Loss Prevention policies control which connectors can be used together to prevent data leakage.

The Center of Excellence toolkit helps you monitor and govern Power Platform at scale. Proper Application Lifecycle Management ensures you have separate dev, test, and production environments.

Security roles control who can access what, and audit logs help you track changes and usage patterns across your organization.

-->

---
title: Getting Started - Your First App
---

# Getting Started - Your First App

## Building a Simple Canvas App

<v-clicks>

1. **Choose your data source** - SharePoint, Excel, SQL, etc.
2. **Generate app from data** - Let Power Apps create the foundation
3. **Customize the interface** - Add your branding and logic
4. **Test on mobile** - Power Apps mobile app
5. **Share with users** - Control access permissions
6. **Gather feedback** - Iterate and improve

</v-clicks>

<!-- 

Let's talk about how you'll build your first app in this training.

Start by choosing a data source - it could be a SharePoint list, Excel table, SQL database, or Dataverse table. Power Apps can automatically generate an app from your data source, creating browse, detail, and edit screens for you.

Then you'll customize the interface to match your requirements and branding. Test it using the Power Apps mobile app to ensure it works well on phones and tablets.

Once ready, share it with your users and control who has access. Then gather feedback and iterate - Power Apps makes it easy to continuously improve your solutions.

-->

---
title: Best Practices
---

# Best Practices

<div class="grid grid-cols-2 gap-8">
<div>

## Development

<v-clicks>

- Start simple, iterate
- Use naming conventions
- Document your solutions
- Leverage templates
- Test thoroughly

</v-clicks>

</div>
<div>

## Governance

<v-clicks>

- Define approval processes
- Implement DLP policies
- Monitor usage
- Provide training
- Foster community

</v-clicks>

</div>
</div>

<!-- 

Let me share some best practices from successful Power Platform implementations.

For development, always start simple and iterate. Use consistent naming conventions for your components. Document your solutions so others can maintain them. Leverage templates and components to avoid reinventing the wheel, and test thoroughly before deployment.

For governance, define clear approval processes for new solutions. Implement DLP policies to protect your data. Monitor usage to identify successful patterns and potential issues. Provide training to your users, and foster a community of citizen developers who can learn from each other.

-->

---
title: Learning Resources
---

# Learning Resources

<v-clicks>

- **Microsoft Learn** - Free, self-paced learning paths
- **PL-900 Study Guide** - Official exam preparation
- **Power Platform Community** - Forums, blogs, events
- **YouTube channels** - Video tutorials and tips
- **Practice environments** - Developer plans (free)
- **Documentation** - Comprehensive reference materials

</v-clicks>

<!-- 

You have access to amazing free resources for learning Power Platform.

Microsoft Learn offers comprehensive, self-paced learning paths that align with the PL-900 exam. The official study guide provides structured exam preparation.

The Power Platform Community is incredibly active with forums, blogs, and events where you can learn from experts and peers. There are many great YouTube channels with tutorials and tips.

You can get free developer environments to practice in, and the documentation is comprehensive and regularly updated.

-->

---
title: Success Stories
---

# Success Stories

## Real-World Power Platform Impact

<v-clicks>

- **HR Department** - Automated onboarding process, reducing time by 70%
- **Sales Team** - Custom mobile app for field data collection, improving accuracy
- **Finance** - Automated expense approval, saving 100+ hours monthly
- **Operations** - Power BI dashboards providing real-time insights
- **Customer Service** - AI-powered chatbot handling common inquiries

</v-clicks>

<!-- 

Let me share some real-world success stories to inspire you.

An HR department automated their entire onboarding process, reducing time by 70%. A sales team built a custom mobile app for field data collection, dramatically improving data accuracy.

A finance department automated expense approvals, saving over 100 hours every month. An operations team created Power BI dashboards that provide real-time insights into their processes.

And a customer service team deployed an AI-powered chatbot that handles common inquiries, freeing up agents for complex issues.

These are the kinds of solutions you'll be able to build after this training.

-->

---
title: Your Training Journey
---

# Your Training Journey

<div class="grid grid-cols-3 gap-4">
<div>

## Week 1-2

<v-clicks>

- Power Platform overview
- Dataverse fundamentals
- Power Apps basics
- First canvas app

</v-clicks>

</div>
<div>

## Week 3-4

<v-clicks>

- Model-driven apps
- Power Automate flows
- Power BI reports
- Integration scenarios

</v-clicks>

</div>
<div>

## Week 5-6

<v-clicks>

- AI Builder
- Advanced topics
- Governance & ALM
- Exam preparation

</v-clicks>

</div>
</div>

<!-- 

Here's what your training journey will look like over the next six weeks.

In weeks 1-2, we'll cover the Power Platform overview, Dataverse fundamentals, Power Apps basics, and you'll build your first canvas app.

Weeks 3-4 dive into model-driven apps, Power Automate flows, Power BI reports, and integration scenarios between the different components.

In weeks 5-6, we'll explore AI Builder, advanced topics, governance and ALM strategies, and dedicated exam preparation to ensure you're ready for the PL-900 certification.

-->

---
title: What to Expect
---

# What to Expect

<v-clicks>

- **Interactive sessions** - Hands-on exercises, not just lectures
- **Build real solutions** - Portfolio-worthy projects
- **Collaborative learning** - Work with peers
- **Expert guidance** - Get your questions answered
- **Certification ready** - Prepared for PL-900 exam
- **Ongoing support** - Community access after training

</v-clicks>

<!-- 

Here's what you can expect from this training experience.

Sessions will be highly interactive with hands-on exercises - this is not about sitting and listening to lectures. You'll build real solutions that you can add to your portfolio.

You'll collaborate with peers, learning from each other's perspectives and experiences. I'll provide expert guidance and make sure all your questions are answered.

By the end, you'll be fully prepared to take the PL-900 exam. And you'll have ongoing access to our learning community for continued support.

-->

---
title: Getting Your Environment Ready
---

# Getting Your Environment Ready

<v-clicks>

- **Microsoft 365 account** - Required for Power Platform
- **Power Apps Developer Plan** - Free environment for learning
- **Power BI Desktop** - Free download for report development
- **Modern browser** - Chrome, Edge, or Firefox
- **Mobile device** - Optional, for testing mobile apps
- **Access to training resources** - Links will be provided

</v-clicks>

<!-- 

Before our next session, let's make sure you have everything ready.

You'll need a Microsoft 365 account - if you don't have one, we'll help you set up a trial. Sign up for the Power Apps Developer Plan which gives you a free environment for learning and development.

Download Power BI Desktop for creating reports. Make sure you have a modern browser like Chrome, Edge, or Firefox.

Optionally, having a mobile device will help you test mobile apps. And I'll provide links to all the training resources you'll need.

-->

---
title: Questions & Discussion
---

# Questions & Discussion

<v-clicks>

- What brings you to Power Platform training?
- What business challenges are you hoping to solve?
- Any specific scenarios you'd like to explore?
- Questions about the PL-900 certification?
- Concerns or expectations?

</v-clicks>

<!-- 

Now I'd like to hear from you.

What brought you to this Power Platform training? What business challenges are you hoping to solve with these tools?

Are there specific scenarios or use cases you'd like us to explore during the training?

Do you have any questions about the PL-900 certification process?

And are there any concerns or specific expectations you have for this training?

-->

---
src: /special-slides/questions.md
---

---
src: /special-slides/thank-you.md
---
