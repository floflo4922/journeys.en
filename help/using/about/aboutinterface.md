---
title: The user interface
description: Learn more on the user interface
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

# User interface {#concept_rcq_lqt_52b}

>[!NOTE]
>
>To get the best out of Journey Orchestration, we recommend using Chrome as your Internet browser.
>
>This documentation is frequently updated to reflect recent changes in the product. However, some screenshots can slightly differ from the product's interface.

## Discovering the interface{#section_jsq_zr1_ffb}

To access the Journey Orchestration's interface, click the **App selector** icon, in the top right. Then click **Journey Orchestration**, on the right side, below "Experience Platform".

![](../assets/journey1.png)  

You can also access Journey Orchestration from the Experience Cloud home page, in the **Quick access** section.

![](../assets/journey1bis.png)  

The top menus allows you to navigate through the different functionalities of Journey Orchestration: **Home** (the journeys), **Data Sources**, **Events**, **Actions**.

![](../assets/journey2.png)  

## Searching and filtering{#section_lgm_hpz_pgb}

In the **Home**, **Data Sources**, **Events** and **Actions** lists, a search bar allows you to search for an item. 

The **Filters** can be accessed by clicking on the filter icon on the top left of the list. The filters menu allows you to filter the displayed elements according to different criteria. You can choose to only display the elements of a certain type or status, the ones you created, or the ones modified in the last 30 days.

In the **Data Sources**, **Events** and **Actions** lists, use the **Creation filters** to filter on the creation date and user. You can choose, for example, to only display the events that you created in the past 30 days.

In the journey list (under **Home**), in addition to the **Creation filters**, you can also filter the displayed journeys according to their status and version (**Status and version filters**). You can also choose to only display the journeys that use a particular event, field group or action (**Activity filters** and **Data filters**). The **Publication filters** let you select a publication date or user. You can choose, for example, to only display the latest versions of live journeys that were published yesterday. See [](../building-journeys/journeyinterface.md).

>[!NOTE]
>
>Note that columns displayed can be personalized using the configuration button on the top right of the lists. Personalization is saved for each user.

![](../assets/journey74.png)  

In the event, data source and action configuration panes, the **Used in** field displays the number of journeys that use that particular event, field group or action. You can click the **View journeys** button to display the list of corresponding journeys.

![](../assets/journey3bis.png)  

In the different lists, you can perform basic actions on each element. For example, you can duplicate or delete an item.

![](../assets/journey4.png)  

## Using the different shortcuts{#section_ksq_zr1_ffb}

Here are the different shortcuts available in the Journey Orchestration's interface.

_In the list of journeys_

* Press **c** to create a new journey.

_When configuring an activity in a journey:_

The canvas is automatically saved. You can see, on the top left of the canvas, the saving status.

* Press **escape** to close the configuration pane and discard the changes made. This is the equivalent of the **Cancel** button.
* Press **enter** or click outside the pane to close the configuration pane. Changes are saved. This is the equivalent of the **OK** button.
* If you press **delete** or **backspace**, you can then press **enter** to confirm the deletion.

_In pop-ups:_

* Press **escape** to close it (equivalent of the **Cancel** button).
* Press **enter** to save or confirm (equivalent of the **OK** or **Save** button).

_In the event, data source or action configuration pane:_

* Press **escape** to close the configuration pane without saving.
* Press **enter** to save modifications and close the configuration pane.
* Press **tab** to jump between the different fields to configure.

_In the simple expression editor_

* Double-click on a field, on the left, to add a query (equivalent to drag & drop).

_When browsing through XDM fields:_

* Checking a "node" will select all the fields of the node.

_In all text areas:_

* Use the **Ctrl/Command + A** key combination to select the text. In the payload preview, it selects the payload.

_In a screen with a search bar:_

* Use the **Ctrl/Command + F** key combination to select the search bar.

_In the canvas of a journey:_

* Use the **Ctrl/Command + A** key combination to select all activities.
* When one or several activities are selected, press **delete** or **backspace** to delete them. Then you can press **enter** to confirm in the confirmation pop-up.
* Double-click on an activity from the left palette to add it at the first available position (from top to bottom).
