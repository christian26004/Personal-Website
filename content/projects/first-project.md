---
title: "Penny Wise"
date: 2025-12-03
author: "Christian Burek, Jace Coose, Apollo Payne"
description: "Personal Finance Manager"
summary: "Personal Finance Manger"
tags: ["Java", "JavaFX", "MVC", "Development"]
---

[View on GitHub](https://github.com/christian26004/PennyWise)


## Overview
Penny Wise is a personal finance management application designed to help inexperienced young adults take control of their finances. The application features an intuitive user interface that guides users through simple menus, making it easy to track income and expenses without any prior financial knowledge. The name Penny Wise is also a pop-culture reference, a deliberate choice to make the app feel approachable and relevant to its young adults.

## The Problem
Managing personal finances with spreadsheets is tedious and error prone. We wanted a clean, local application that could track multiple accounts without relying on the cloud or third party services.

## Scope
features and functions include:
- An overall finance report with user input to add, delete, or modify entries.
- A meal tracker that, once the total cost of ingredients is inputted, implements a counter to track how many meals the given recipe provided for, and shows money saved per meal based on average fast food meal cost.
- Subscription tracker that tracks total cost of subscriptions (per month/year/total), shows individual subscription cost, and how long the user has been subscribed to each service. User input: management (add, delete, modify) for subscription services, meal tracker, budget report, and account details
- Supports multiple user accounts on the same machine

## Architecture
Penny Wise is a Java/JavaFX application which uses a model-view-controller (MVC) architecture. The application controls data though effective use of CSV files.

## What I Learned
- How to architect a real application using MVC from scratch
- Working with JavaFX for the first time and building a responsive UI
- Managing file I/O for persistent local storage

## Contributors
- Christian Burek
- Jace Coose
- Apollo Payne
