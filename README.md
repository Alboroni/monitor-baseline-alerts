# Baseline Alerts for Monitoring in Azure

> **Please access the GitHub Pages site, unless looking to contribute, over at: [https://github.com/Azure/monitor-baseline-alerts](https://github.com/Azure/monitor-baseline-alerts)**

Welcome to the home of the Baseline Alerts for Monitoring in Azure.

<img src="docs/static/media/img/abla-white.png" width=40%>

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

## Contributing

> The contribution guide can be found on the GitHub pages site here: [https://azure.github.io/monitor-baseline-alerts/contributing/](https://azure.github.io/monitor-baseline-alerts/contributing)

This project only currently accepts Pull Requests from Microsoft FTEs as of today. However, anyone is welcomed to create issues/features requests on the repo for the team to triage and action.  Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit [https://cla.opensource.microsoft.com](https://cla.opensource.microsoft.com).

When you submit a pull request, a CLA bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft trademarks or logos is subject to and must follow [Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/legal/intellectualproperty/trademarks/usage/general). Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship. Any use of third-party trademarks or logos are subject to those third-party's policies.
