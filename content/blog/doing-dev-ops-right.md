---
title: "13 clues you are doing DevOps right"
date: 2021-03-11T11:37:34+03:00
author: "Angel Kafazov"
author_image: "/images/Angel.jpg"
tags: ["devops", "cicd", "deployment", "monitoring", "logging"]
weight: 40
image: "/images/daitera-cicd.png"
description: "These thirteen unmistakable signs prove your team has achieved peak DevOps maturity"
featured: false
draft: false
---

Here are 13 best practices which I think are a good indicator for professional DevOps team.

### Do you have fully automatic deployments?  
Having a 100% automated deployment is an essential part of good DevOps practices. It enables a software team to quickly iterate, deploy often and have a good general trust in the running software. Deployments can be triggered by some event like commit or manually. It is good practice to also have automated rollback procedure, just in case something goes wrong.

### Do you have zero-downtime deployment?  
Having zero-downtime deployment is essential for a good user experience and for the release velocity of your DevOps team. There is a lot of work that goes into supporting rolling upgrades like multiple application instances, load-balancers, decoupled state management, CI/CD and others.

### Do you have release management documentation?  
As good as a release management process is, it must be well documented and made available for the whole software team. Having documentation not only means quick on-boarding for new team members, but brings order by having the whole team synchronized on how release management works. This involves all parts of the team, not only DevOps but also developers and testers.

### Are all software components versioned?  
Every software component which is deployed either for testing, integration or in front of live users should be versioned and linked to the release notes. A good approach is to use semantic versioning and also include a GIT-SHA, so that the exact commit history can be linked to the running software.

### Have you implemented performance metrics monitoring?  
Once the software has been deployed to the host environment, performance metrics provide the insight to know if the performance is sufficient. Often performance metrics can be a clue to design issues which only become obvious under particular situations like user traffic, end devices and timing. Not having such information can cost time, resources and diminish the user experience of the product.

### Do you run automatic tests as part of the build/deploy process?  
Having a strict criteria for every deployable component should be documented and implemented as automatic test. These tests allow DevOps to catch faulting software before reaching the users. Another benefit is also continuous improvement in quality by the extension of tests covering newly discovered issues.

### Do you have automatic vulnerability scanning?  
Security must be taken extremely seriously and automatic vulnerability scanning is just one aspect of security. Tools like Anchore enable you to scan docker images against a public database of known vulnerabilities, which is regularly updated. However, one should not assume that passing these test is a sufficiently high bar of security.

### Do you have fully automated Infrastructure as Code?  
Infrastructure as Code is a relatively new trend in DevOps, but a well established and very practical one. Some of the benefits are the ability to orchestrate host environments quickly and a highly structured and repeatable manner. A good practice is to have your infrastructure code committed in Git. Some useful tools to implement this are Ansible, Chef, Puppet, Terraform.

### Do you have bug database?  
Having a system to manage bugs and issues is a good practice which enables to efficient management of bugs in the software. It provides a level of visibility and helps identify areas where more work is needed.

### Do you write tests for all newly found bugs?  
One other benefit of having a bug database is that you can connect it with automatic tests which cover know bugs in the future. This will prevent a bug reappearing again in the future once it is caught and fixed.

### Do you have good logs?  
Having a good log management is absolutely essential to DevOps and system quality. Not having enough logs or insufficient quality of logs can mean being unable to fix an issue. There are several aspect in logging which must be implemented.  
Centralized logging - collect log information from all running components in a centralized system.  
Having enough detail resolution - the ability to collect all necessarily parameters like user, environment, date and time, software version, input/output.  
A good logging strategy enables developers to reproduce issues with close to 100% realistic conditions on a local dev environment and diagnose and fix the issue.

### Do you have system and data recovery strategy?  
Doing backups is just not enough. You should plan for recovery which includes backup, orchestration and installation. Your recovery strategy should account for the host environment, application and user and state data. Ideally you should be able to bring up the whole infrastructure automatically if it is destroyed.

### Do you have separate development, test, integration and production environments?  
A good DevOps teams always have distinct environments for development, testing, integration and production. Those environments should ideally be identical and software flow between them should be managed by a system such. For example untested software should never be installed on production.