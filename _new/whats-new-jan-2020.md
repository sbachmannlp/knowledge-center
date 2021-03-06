---
pagename: January 2020
categoryName: What's new
subCategoryName: ''
indicator: both
subtitle: Highlights include updates to the enhanced agent workspace for messaging, new manager workspace & more
level3: ''
permalink: whats-new-january-2020.html
isTutorial: false
isNew: false

---
**Happy New Year!** 
LivePerson is kicking off 2020 with a number of important updates and exciting new features.
Watch this two minute video for the upcoming features for the weeks ahead...
<iframe src="https://player.vimeo.com/video/385805928?autoplay=1&title=0&byline=0&portrait=0" width="640" height="360" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

Recently, LivePerson launched the New Manager Workspace and the Enhanced Agent Workspace for messaging. We’ve made some important updates to these workspaces based on great feedback from our users.

### New Manager Workspace
For a comprehensive tutorial of the New Manager Workspace check out this [video.](https://vimeo.com/358055055/d830be4007) 
Here’s the latest updates to the manager workspace:

## Global Skill Filter [New Manager workspace]

We’re making it easier for managers to make data driven decisions by allowing them to easily filter the entire workspace by specific skills. Until now, the skill filter was available per widget (e.g. by queue summary, agents and conversation widget). 
When filtering by skill, the agent’s widget will retrieve the list of agents which are assigned to the selected skills.  The metrics associated will not be filtered according to the skill, but for all of the agent’s activity.
For example, if an agent is assigned multiple skills, the metrics will reflect all of their conversations and not just the filtered skill. The filter is available on the top right corner of the page.

{: .notice}
This filter will be automatically enabled for any user that is using the new manager workspace.

![](img/Jan2020_whats_new_2.png)

## Global filter setting at logout retained upon login [New Manager workspace]
In order to spare managers from resetting their workspace filter preferences each time they log in, the global filter settings will be saved automatically. The filters that are retained are only the global filters (available at the top right corner of the workspace) including: timeframe, group and skill filters. 

{: .notice}
The filter settings are kept on the local storage of the specific computer and browser per user.

## Active metric [New Manager workspace] 
The “active” metric which was available until today only on the list view of the agents widget has been added to the card view as well. The metric displays the number of conversations at full intensity. 
{: .notice}
This will automatically be enabled for any user that enabled the new manager workspace.

![](img/Jan2020_whats_new_3.png)

## Wait time metric [New Manager workspace]
A new metric, “Wait time” has been added to the “Queue summary” widget. The metric is shown by skill breakdown.  The metric displays the 90th percentile of the consumers wait time for an agent assignment which means that 90% of consumers are currently waiting for an agent assignment X amount of time or less. 

{: .notice}
Automatically enabled for any user that enabled the new manager workspace.

![](img/Jan2020_whats_new_4.png)

## Overdue metrics [New Manager workspace]
The overdue metrics have been added in two locations:
**Activity summary** - This metric displays the number of conversations assigned to agents that exceeded the target response time. The metric will include only the conversations of agents under the groups the manager is managing.
**Queue summary** - This metric displays the number of conversations waiting in queue that exceeded the target response time. The metric will include only the conversations assigned to skills the manager is managing.

{: .notice}
Automatically enabled for any user that enabled the new manager workspace.

![](img/Jan2020_whats_new_5.png)

## Filter by specific hour [New Manager workspace]
Ability to set and monitor operations performance from specific hours, such as the beginning of a shift or the beginning of a business day.
Until now, users have only been able to change the time range of the manager workspace to view data from the past X hours (maximum supported time range being 24 hours).

With new ‘filter by specific hour’, users can filter the workspace from a specific hour in time, in a range between midnight and the current time. 

![](img/Jan2020_whats_new_6.png)

## Seamless Navigation from agent to manager workspace 
We're making it easier to navigate between the enhanced agent workspace for messaging and the new manager workspace. When a user drills down to read a transcript of a specific conversation from the “Conversations widget” in the manager workspace, users are navigated to the enhanced agent workspace. In order to navigate back to the conversation list, users will be able to simply click the new “Back to Manager workspace” button.

{: .notice}
This feature applies only to messaging agent managers who are using both the new manager workspace and the enhanced agent workspace.

![](img/Jan2020_whats_new_7.png)

### Enhanced Agent Workspace for Messaging
For a comprehensive tutorial of the New Agent Workspace, check out this [video.](https://vimeo.com/357193087/7d6d59ca85) 

Here’s the latest updates to the enhanced agent workspace for messaging:
## Personalize the predefined content widget display [agent workspace]
In the enhanced workspace for messaging - each agent will be able to personalize how they'd like to view their predefined content widget and in how much detail. The predefined content widget enables each user to decide whether to display each content as titles &  text, or to hide the content text and display the titles only. If the user chooses the “Titles only” display, hovering each item will display it’s content on a tooltip for assistance. 

{: .notice}
The configuration is enabled per agent only and does not affect the entire account.

[](img/Jan2020_whats_new_8.png)

## Deselect conversation [agent workspace]
We know that sometimes agents need to be in the workspace and perform actions that are not specific to one conversation. We have added an option for agents to shift focus of the conversation from their screen. Users can click on the action menu and choose  “Unselect conversation”. When choosing this option, the conversation will disappear from the user’s screen and will only be visible from the “My connections” list. 

[](img/Jan2020_whats_new_9.png)

## Display summary notes to previous conversations [agent workspace]
Agents will receive a more holistic picture of previous conversations with a consumer through the addition of summary notes to the conversation history and notes. 
In the new workspace, previous conversations are displayed above the current conversation.
We now are added the ability to see previous conversations summary as written by previous agents who participated in the conversation (one or more). 

[](img/Jan2020_whats_new_10.png)

### Application Framework
We’re making some updates to how our customers can access LivePerson apps.

## New applications dashboard (this feature has been delayed)
The new Applications dashboard coming soon gives brands and partners the ability to manage all LivePerson applications on a self-serve basis. It also exposes them to applications that developers have created by presenting them with information about the application, such as an overview of the app and screenshots from the app. By using the dashboard, an admin can enable or disable the app, decide which user profiles can use this app, change its name and icon, and decide if the app should be launched from the Quick launch menu. Read the internal release notes for
more info.

[](img/Jan2020_whats_new_11.png)

## Access to applications - additional security measure
A new security measure has been introduced and defines which type of roles and profiles can access which applications. Some users may have to approach their account administrator to request access to applications. We defined access permissions to the following applications for admins only (by default): MCS Toolkit, Realtime Dashboard, Liveintent, Data Transporter, Maven Workspace, Functions (FaaS), CoBrowse for Voice. 

[](img/Jan2020_whats_new_12.png)

## Quicklaunch menu redesign
Quicklaunch redesign is more scalable and intuitive to users trying to find the right app by expanding the window and giving the menu a fresh look & feel.

[](img/Jan2020_whats_new_13.png)

### In the coming weeks we’re also making some updates to the Consumer Experience for Web Messaging.
## New structured content template “Multiple select checkbox”
The Multiple select checkbox template enables humans or automated agents (bots) to share a list of items, while allowing the consumer to select multiple items and reply back with their selection. 
The template increases use cases brands can serve on messaging and allows brands to more efficiently receive input from customers for complex questions. 
For consumer; they will be able to select their choices and click on the action button to submit. Once submitted, the consumer's selections will be sent as a message on behalf of the consumer, appearing in the conversation transcript.

{: .notice}
The consumer selections will be displayed as plain text, with a comma separator between each selection.

If you are using a bot to send the structured content template, the consumer selection will be published as part of the conversation metadata. Using Messaging Agent SDK, bots can access conversation metadata and analyze the consumer selections.

For agents, the consumer selections will be displayed as a consumer message in the agent workspace as part of the conversation transcript.

[](img/Jan2020_whats_new_14.png)

## Hyperlinks for Web Messaging
When messaging, users will be able to share hyperlinks with consumers as part of the general message. Within the agent input area, a new button will appear that enables agents to add the URL link and title to be displayed while sending to the consumer. 

[](img/Jan2020_whats_new_15.png)

## Post conversation survey in the Conversation Builder (currently in early access)
Customers can use Conversation Builder for all their bot needs, including surveys as the Post Conversation Survey is now in the Conversation Builder platform.
Brands can now ask their customers to fill a brief survey at the end of a conversation and collect feedback in a single flow. The collected data provides valuable insights about the customer experience.

{: .notice}
If you would like to take part of the early access program, please contact your account team.  

[](img/Jan2020_whats_new_16.png)

## Bot transfers based on conversation context
Normally, when a conversation moves from one bot to the other, the conversation context is not exchanged. With this feature the conversational context will automatically be transferred from the sender bot to the receiver bot. The receiver bot understands the conversational context and initiates appropriate dialog which enables a smoother transition of conversation.

### Report Builder
## Conversion attribution model for messaging [Report Builder]

The new ‘Goal tracker report for Messaging’ will allow brands to attribute conversions to all agents assigned to the conversation for the converted consumer (options for all agents or human agents only). The new settings will enable brands to choose the attribution model for messaging (First, Last, All).


