---
title: First Steps
author: Cisco CC TSA Team
date: 2023-08-02
layout: post
---

```
Last modified: Thu, 16 August 2023
```

## Overview - First Steps and Preparation:


This section explains the needed praparation in order to get the Demo use cases ready on your Webex CC tenant. 
Please complete the below steps:
-	Import the WhatsApp Demo selector Flow
-	Import the generic Flows 

The needed Files are at the end of this page under Flows.

### How to configure this Demo Use Case in your Tenant

### Demo Selector

The Selector Flow is the main Flow for all use cases.
It routes the user to the right Use Case based on the key word.
For Example to use the Retail Use Case, type **RetailDemo** to start the Demo. 

<center><img src="https://webexcctsa.github.io/wxcc-usecases/assets/gitbook/images/Firststeps/demoselecotor1.png" width="80%"></center>

1. Create a new Webex Connect Service and give it a name, e.g Demo Use Cases
2. **WA_Selector.workflow**
3. Create a new flow and Import from WA_Selector.workflow in the ConnectFlows directory.
4. Make the following changes:  
   - Check and change the Branch Node to reflect your Trigger words for the different Use Cases.


<center><img src="https://webexcctsa.github.io/wxcc-usecases/assets/gitbook/images/Firststeps/demobranch.png" width="80%"></center>

5. Save and Make your Flow Live
   
The Selector Flow also provides you the possibility to clear an existing conversation. This is helpful when there is an existing conversation which blocks other new messages coming into the flow from the same user. 

The Trigger word is “clear conversation”. 

<center><img src="https://webexcctsa.github.io/wxcc-usecases/assets/gitbook/images/Firststeps/clearconveration.png" width="80%"></center>

### Generic Flows

The generic flow are optional. Those Flow helps you to trigger an activity if a Task is routed, modified, or closes. Example: If you are looking to generate a screen pop, then you just need to add the screen pop URL in the Routed Flow. 

## Import the 3 generic Flows
Import all tree flow into your Webex Connect Service. You can also create a separate Webex Connect Service for the Generic Flows. 

   - Task Routed
   - Task Modified
   - Task Closed

<center><img src="https://webexcctsa.github.io/wxcc-usecases/assets/gitbook/images/Firststeps/genericflow.png" width="80%"></center>

## Flows 

<a href="https://webexcctsa.github.io/wxcc-usecases/assets/ConnectFlows/WA_Selector.workflow">WhatsApp Selector.workflow</a><br> 
<a href="https://webexcctsa.github.io/wxcc-usecases/assets/ConnectFlows/Task_Routed.workflow">Task Routed.workFlow</a><br> 
<a href="https://webexcctsa.github.io/wxcc-usecases/assets/ConnectFlows/Task_Modified.workflow">Task Modified.workflow</a><br> 
<a href="https://webexcctsa.github.io/wxcc-usecases/assets/ConnectFlows/Task_Closed.workflow">Task Closed.workflow</a><br> 


<br>
<br>
---

  <script>
    document.addEventListener('DOMContentLoaded', () => {
      console.log('DOMContentLoaded OKOK')
    })

    window.addEventListener('load', () => {
      console.log('window load OK')
    })
  </script>

<p style="text-align:center"><strong>Congratulations, you have completed the configuration for this Demo Use Case! You can continue with the next one.</strong></p>

<center><img src="https://webexcctsa.github.io/wxcc-usecases/assets/gitbook/images/webex-small.png" width="100"></center>

