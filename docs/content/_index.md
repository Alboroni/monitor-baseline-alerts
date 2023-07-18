+++
title = "Home"
description = "Welcome to the home of the Baseline Alerts for Monitoring in Azure"
weight = 1
+++

Welcome to the home of the Baseline Alerts for Monitoring in Azure.

<img src="/monitor-baseline-alerts/static/media/img/abla-white.png" width=40%>

## Disclaimer

Please note that the policies in this GitHub repository are currently in development and may be subject to frequent changes and updates. This means that the functionality and features of the polices may change without notice. As such, you are advised to ensure that the policies are tested thoroughly in a test environment before considering moving to production.

Additionally you are advised to reach out to the authors of this repository to discuss the policies and their suitability for your environment, before deploying them in production. To do so create an issue [here](https://github.comm/monitor-baseline-alerts/issues), and we will get back to you as soon as possible.

By accessing or using the code in this repository, you agree to assume all risks associated with its use and to use it at your own discretion and risk. Microsoft shall not be liable for any damages or losses resulting from the use of this code. For support details, please see the [Support section](https://github.com/Azure/monitor-baseline-alerts/blob/main/SUPPORT.md).

## Overview

One of the most common questions faced when working with customers is, "What should we monitor in Azure?" and "What thresholds should we configure our alerts for?"

There isn't definitive list of what you should monitor when you deploy something to Azure because "it depends", on what services you're using and how the services are used, which will in turn dictate what you should monitor and what thresholds the metrics you do decide to collect are and what errors you should alert on in logs.

Microsoft has tried to address this by providing a number of 'insights or solutions' for popular services which pull together all the things you should care about ([Storage Insights](https://learn.microsoft.com/en-us/azure/storage/common/storage-insights-overview), [VM Insights](https://learn.microsoft.com/en-us/azure/azure-monitor/vm/vminsights-overview), [Container Insights](https://learn.microsoft.com/en-us/azure/azure-monitor/containers/container-insights-overview)); but what about everything else???

The purpose of this project is to establish a set of baseline alerts for Azure resources/services used to within an organization workload. This provided us with a starting point on addressing "What should be monitored in my workload in Azure?" It also provides an example of how to monitor-at-scale while leveraging Infrastructure-as-code principles.

This project is an opinionated view on what you should monitor for the key components of your workload i.e:

- Virtual Machines
- TBD

## Get Started

To get started head over to the [Azure Services section]({{< ref "services/_index.md">}}) and then navigate via the appropriate category to find example policies.

{{< alert style="info" >}}

You can also use the basic search functionality provided by this site to locate the Azure service you are looking for guidance, recommendations and supporting queries and scripts for.

{{< /alert >}}

## Contributing

Please see the [contribution guide here]({{< ref "contributing/_index.md">}}).

{{< alert style="info" >}}

Please note that this site is built upon [GithHub Pages](https://pages.github.com) using [Hugo](https://gohugo.io/) which is using the [Ace Documentation theme](https://docs.vantage-design.com/ace/)

{{< /alert >}}
