---
copyright:
  years: 2017, 2018
lastupdated: "2018-01-09"
---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}

# Getting started with MQ on IBM Cloud
{: #index}

MQ on IBM Cloud enables you to quickly and easily deploy queue managers in the cloud and connect your applications to them, for reliable data transfer between different parts of your enterprise application landscape.

This document describes two approaches to get started with IBM MQ on Cloud:
  - **Getting started using the Guided Tour** - this describes how to start the embedded tutorial, which will guide you through the process of creating and using your first IBM MQ on Cloud queue manager.
  - **Manually creating and using an IBM MQ on Cloud queue manager** - this provides documented steps describing how to create and use your first IBM MQ on Cloud queue manager.

---

## Getting started using the Guided Tour
{: #index_guidedtour}

The MQ on Cloud service comes with a Guided Tour, which provides step by step guidance through the following steps:
 - creating a queue manager
 - creating an administrator user
 - using a demo application to put and get messages on a queue
 - accessing the IBM MQ Web Console

Before you can create the queue manager, you need to create a service instance, which is described in the next section 'Launching MQ on IBM Cloud'

### Launching MQ on IBM Cloud
{: #launch_mqoc_create_qm}

In order to access the Guided Tour, you must first launch the IBM MQ on Cloud service, which is achieved by creating an IBM MQ on Cloud service instance.

To create an MQ on Cloud service instance:
1. Log in to the IBM Cloud console, accessible at: http://console.bluemix.net/
2. Click **Catalog**.
3. Click **Integration**, and
4. Click **MQ**.
5. Type in a service name.
6. Select a plan, for example **Default**.
7. Click **Create**.

You are now presented with a view of your service instance from where you will be able to view and manage your queue managers. This is also the page from which you can launch the Guided Tour.

### Using the Guided Tour

You can launch the Guided Tour by clicking on the folding icon at the top right of the page.

![Image showing the location of the Guided Tour start icon](./images/mqoc_getting_started_gt_icon.png)

**Note:** if you don't yet have any queue managers, the Guided Tour will automatically be expanded.

Once the Guided Tour is expanded, you can begin by clicking 'Get Started'.

![Image showing the location of the Guided Tour start icon](./images/mqoc_getting_started_gt_open.png)

---

## Manually creating and using an IBM MQ on Cloud queue manager
{: #index_manual}

As an alternative to the Guided Tour, you can instead follow the documented steps below to create and use the IBM MQ on Cloud service:

1. [Create a queue manager.](/docs/services/mqcloud/mqoc_create_qm.html)
2. [Administer a queue manager](/docs/services/mqcloud/mqoc_admin_mqweb.html) using the IBM MQ Web Console.
3. [Connect a sample application to a queue manager.](/docs/services/mqcloud/mqoc_connect_app_qm.html)
