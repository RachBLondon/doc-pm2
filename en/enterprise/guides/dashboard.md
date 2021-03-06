---
layout: page
title: Dashboards | Guides | PM2 Enterprise Documentation
menu: starter
lang: en
section: enterprise
hide_comments: true
permalink: "/en/enterprise/guides/dashboard/"
---

## Overview

It's common in the devops culture to have a screen in your office that monitor the state your production apps.
This feature is actually that. it allows you to see what's going on in realtime (max 5 sec delay), it can help you detect faster any wrong behavior of your application.

**Note**: We are currently working on a version that can also show historic data, so you can both have realtime and historical data next to you.

## Use cases

#### Have an overview of what's happening

The main use case of this feature is of course to have an overview of all the important metrics of your app in one place, to avoid looking at multiple dashboards to have all the informations.

#### Detect error quickly

The dashboards can also help you detect faster issue if you have a screen constantly showing your dashboard, any developer can look at it and might see a wrong behavior at any time, even before the alerts comes if you have configured some.

## Requirements

In the following documention, we assume that you already have connected your application to PM2 Enterprise (either on-premise and cloud).
We also assume that you know how custom metrics and customs actions works.

## Configuration

Since the feature is really just customization for your needs, there a no specific configuration to have. You need to evaluate what you want to see on your dashboard and configure each compoments to show you what you want.

## Common Questions

* Is there a way to show historic value of a metric ?

  No, currently it's only in realtime but we are working towards a way to configure all components to show historical data.

* I need to show a metric in a specific way (one that isn't covered by one of your component) ?

  We are totally open to implement other components, please contact us so we can discuss that !

## Common Issues

* It's slow on my PC

  The realtime dashboard can cost a lot depending on how much process you want to monitor in realtime, we are constantly looking to optimize our frontend, we advise to contact us so we can inspect the problem and find a solution.




<center>
Contact our team at <a href="mailto:tech@keymetrics.io">tech@keymetrics.io</a> if you have any questions/issues
</center>
