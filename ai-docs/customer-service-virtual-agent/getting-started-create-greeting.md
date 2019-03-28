---
title: "Creating a custom greeting for your virtual agent"
description: "Learn how to create a custom greeting for your virtual agent."
keywords: ""
ms.date: 3/15/2019
ms.service:
  - "dynamics-365-ai"
ms.topic: article
ms.assetid: 
author: stevesaunders1952
ms.author: stevesaunders1952
manager: shellyha
---

# Creating a custom greeting for your virtual agent

A customer can start a conversation with a virtual agent by entering any trigger phrase that starts a conversation defined by a topic. Sometimes the customer may start a conversation with a simple greeting, such as *Hello* or *Good morning*. To help you handle this common situation, Virtual Agent Designer automatically includes a built-in Greeting system topic when you create a virtual agent, which you can customize.

Customizing your greeting gives you an opportunity to let the customer know that they are interacting with a virtual agent rather than a human agent, and to tailor the virtual agent to reflect your organization's personality.

For information on creating a custom topic, see [Creating custom topics for your virtual agent](getting-started-create-topics.md).

## To customize your virtual agent's greeting

1. On the Home page, select **Edit Greeting Topic** to open the Greeting topic in the conversation editor.

   > ![Open Greeting topic](media/open-greeting-topic.png)

    You can also open the Greeting topic in the conversation editor by selecting **Topics** in the navigation pane to open the Topics page, scrolling to the **System topics** section, and selecting the Greeting topic's **Edit** icon.

   > ![Alternate open greeting](media/alternate-open-greeting.png)

    The Greeting topic by default is named *Greeting* and includes a built-in description and trigger phrases, which can't be edited. However, you can customize the greeting by editing the topic's conversation path.

2. In the conversation editor, edit the topic's **Bot Says** nodes to customize the greeting.

   > ![Custom greeting](media/custom-greeting.png)

    Select **Save** to save the topic.

## To test the greeting

1. In the Test Virtual Agent pane, select **Start over with latest content** to make sure you are using the most current virtual agent content.

2. At the **Type your message** prompt at the bottom of the Test Virtual Agent pane, enter a trigger phrase for the Greeting topic. The Virtual Agent responds with the customized greeting you created.

   > ![Test greeting](media/test-greeting.png)