---
layout: post
title: Data Transformation with Microsoft Sentinel
subtitle: How to create DataTransformation using MS Sentinel
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [Sentinel]
comments: true
---

**Use cases and sample scenarios**

Filtering
Ingestion-time transformation provides you with the ability to filter out irrelevant data even before it's first stored in your workspace.

You can filter at the record (row) level, by specifying criteria for which records to include, or at the field (column) level, by removing the content for specific fields. Filtering out irrelevant data can:

Help to reduce costs, as you reduce storage requirements
Improve performance, as fewer query-time adjustments are needed
Ingestion-time data transformation supports multiple-workspace scenarios.

A little information about difference between CEF and Syslog:

![CEFSyslog](https://andrebgc.github.io/mainpage/assets/img/cefxsyslog.png)
