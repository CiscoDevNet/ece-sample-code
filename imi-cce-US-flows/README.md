# CCE-digital-channels
This repo provides the templates flows for Contact Center Enterprise (CCE) and imiconnect integration. These flows are specific to imiconnect deployment regions.

## Overview
Inside the imiconnect region specific folder, the following sample flow templates are included:

1. Channel specific flows: 
   * **Facebook Customer Support** - This flow will be triggered for every inbound customer message over the integrated Facebook Messenger page.
   * **SMS Customer Support** - This flow will be triggered for every inbound customer SMS sent over the integrated SMS phone number.
2. Channel Agnostic Flows:
   * **Assigned** – This flow is triggered an agent is assigned to a conversation.
   * **Receive Message Text** – This flow is triggered when imiconnect receives a text message from the agent that is to be sent to the end customer.
   * **Receive Message HTML** – This flow is triggered when imiconnect receives an HTML message from the agent that is to be sent to the end customer.
   * **uploadAttachment** – This flow is triggered when an agent uploads an attachment that is to be sent to the end customer.
   * **pagePush** – This flow is triggered when an agent sends a link to be sent to the end customer.
   * **Transfer** – This flow is triggered when an agent transfers the chat to another agent/queue.
   * **Complete** – This flow is triggered when an agent ends the conversation while customer was still in session.

## Quick start on Flows
* Login to your imiconnect account.
* Click on **Documentation** under the **Help** section.
* The imiconnect platform documentation will open in a new tab.
* Under **GETTING STARTED**, click on **imiconnect Platform Overview**.
* Scroll down to the **IMICONNECT CCE INTEGRATION** section.
* Click on **Solution Overview**.

## Disclaimer
This sample code is only a sample and is **NOT guaranteed to be bug free and production quality**.

## Support Notice
[Support](https://developer.cisco.com/site/support) for the samples is provided on a "best effort" basis via DevNet. Like any custom deployment, it is the responsibility of the partner and/or customer to ensure that the customization works correctly and this includes ensuring that the sample code is properly integrated into 3rd party applications. Cisco reserves the right to make changes to the code and corresponding API as part of the normal release cycle.

Cisco Systems, Inc.<br>
[http://www.cisco.com](http://www.cisco.com)<br>
[http://developer.cisco.com/site/enterprise-chat-and-email](http://developer.cisco.com/site/enterprise-chat-and-email)
