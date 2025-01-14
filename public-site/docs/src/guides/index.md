---
title: Guides
---

# Get to know Radix

The basic requirements are covered in [Getting started](getting-started/).

The most beginner-friendly way to get started is the [Configuring an app](configure-an-app/) guide. You can also watch the [Introduction to Radix video](https://web.microsoftstream.com/video/fa523b5c-3509-4e11-97b0-868ae499f603) 🎥 for a more visual overview.

Builds in Radix are Docker builds! The [Docker builds](docker/) guide has recommendations for creating good `Dockerfile`s that work well in the cloud ☁️

# Building, deploying and managing the app

How should you set up Git branches and Radix environments?

Read about [workflows](workflows/) for an overview. A common strategy is to use [promotion](deployment-promotion) to control how deployments end up in environments.

# Deploy only - other CI tool

Teams that have a need for more advanced CI feature can use other CI tools and [deploy into Radix](deploy-only). This feature is in progress, utilised by only a few teams. If you have any input or would like to be involved in testing this feature, please contact us for a walkthrough.

# Pipeline job badges

Radix API provides an URL to generate pipeline job status badges in SVG format. These badges can be included in web pages or markdown files, for example in a README.md in a GitHub repository. Read [this guide](pipeline-badge).

# Application component start, stop, restart function

Another functionality available is the ability to [restart, stop and start a component](component-start-stop-restart/), the feature is available on your app component page in the Web Console

# Resource allocation - cost

To ensure that an application is allocated enough resources to run as it should, it is important to set resource requirements for containers. This resource allocation is also used to distribute cost to an application. An app without resource requirements specified will be allocated default [values](https://github.com/equinor/radix-operator/blob/master/charts/radix-operator/values.yaml#L24). A guide on how to find resource requests and limits for an app can be found [here](resource-request)

# Authentication

There is no checkbox that automatically provide authentication for your application in Radix. However there is still several way to introduce it to new and existing applications, without to much work. The [Authentication](authentication/) guide goes through the basic to get authentication going for a Client and API.

# Monitoring

You can use monitoring "out of the box" (the link to Grafana is in the top-right corner of the [Web Console](https://console.radix.equinor.com)). But you will get the most value by implementing [monitoring relevant for your app](monitoring).

# Samples and scenarios

We also have a collection of [scenarios](scenarios/) that can be used as templates for new or existing projects.
