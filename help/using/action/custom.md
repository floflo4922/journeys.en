---
title: About custom action configuration
description: Learn how to configure a custom action
page-status-flag: never-activated
uuid: 269d590c-5a6d-40b9-a879-02f5033863fc
contentOwner: sauviat
audience: rns
content-type: reference
topic-tags: journeys
discoiquuid: 5df34f55-135a-4ea8-afc2-f9427ce5ae7b
internal: n
snippet: y
---

# About custom action configuration {#concept_sxy_bzs_dgb}

If you're using a third-party system to send messages or if you want Journey Orchestration to send API calls to a third-party system, this is where you configure its connection to Journey Orchestration. The custom action defined by technical users will then be available in the left palette of your journey, in the **Action** category (see [](../building-journeys/journeyaction.md). Here are a few examples of systems that you can connect to with custom actions: Epsilon, Facebook, Adobe.io, Firebase, etc.
Limitations are listed here: [](../action/customlimitations.md).

Here are the main steps required to configure a custom action:

1. From the **Actions** list, click **Add** to create a new action. The action configuration pane opens on the right side of the screen.

    ![](../assets/custom2.png)

1. Enter a name for your action.

    >[!NOTE]
    >
    >Do not use spaces or special characters. Do not use more than 30 characters.

1. Add a description to your action. This step is optional.
1. The number of journeys that use this action is displayed in the **Used in** field. You can click the **View journeys** button to display the list of  journeys using this action.
1. Define the different **URL Configuration** parameters. See [](../action/customurl.md).
1. Configure the **Authentication** section. This configuration is the same as for data sources.  See [](../datasource/dsexternal.md#section_wjp_nl5_nhb).
1. Define the **Message parameters**. See [](../action/customparameters.md).
1. Click **Save**.

    The custom action is now configured and ready to be used in your journeys. See [](../building-journeys/journeyaction.md).

    >[!NOTE]
    >
    >When a custom action is used in a journey version, most parameters are read-only. You can only modify the Name and Description fields.
