# CCE-digital-channels
This repo provides the templates flows for Contact Center Enterprise (CCE) and imiconnect integration. These flows are specific to imiconnect deployment regions.

## Overview
Inside the region specific folder, the following sample flow templates are included:

1. Channel specific flows: 
   * **Facebook Customer Support** - This flow will be triggered for every inbound customer message over the integrated Facebook Messenger page.
   * **SMS Customer Support** - This flow will be triggered for every inbound customer SMS sent over the integrated SMS phone number.
2. Channel Agnostic Flows:
   * **Process ECE Events** – This flow is used to process events received from Enterprise Chat and Email (ECE) to imiconnect.
   * **Clear Session** – This flow is invoked from channel specific flows through Call Workflow node to clear the session details.

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
