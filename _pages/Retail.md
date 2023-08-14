---
title: Retail
author: Cisco CC TSA Team
date: 2023-08-10
layout: post
---

```
Last modified: Thu, 10 August 2023
```

## Overview of the Use Case:

Following use cases are part of the Retails Demo:
- Order Status 
- Find nearest store
- Chat to Agent (requires the [Agent Handover](/pages/AgentHandover.md/) use case)
- Call Me - Call back request




### Demo Video

> The video below shows a demo about this Use Case:

{: .block-tip }
<div style="padding-bottom:60.25%; position:relative; display:block; width: 100%">
	<iframe src="https://app.vidcast.io/share/ad512769-3b5e-48e6-910f-57e5247aeae3" width="100%" height="100%" title="Station Login" frameborder="0" loading="lazy" allowfullscreen style="position:absolute; top:0; left: 0"></iframe>
</div>

### How to configure this Demo Use Case in your Tenant



# Import Retail Flow

- **WA_Retail.workflow**
- Create a new flow and Import from WA_Retail.workflow in the ConnectFlows directory.
- Make the following changes:
- Edit the Custom Variables to add agent name and email address for the Callback API:

<<<<<<< HEAD


<center><img src="https://webexcctsa.github.io/wxcc-usecases/assets/gitbook/images/Retail/triggerword.png" width="80%"></center>




-	Edit the Trigger Node to add AbdulDemoRetail (or whatever unique trigger you want to use)


<center><img src="https://webexcctsa.github.io/wxcc-usecases/assets/gitbook/images/Retail/customvar.png" width="80%"></center>


-	In the Agent Handover path edit the Queue Task to add your own queue
-	Open and save All Receive nodes 
-	Open the QnABot node and select the QA BOT created above [QA BOT Name]
-	Save and Make Live – select the appropriate WhatsApp App.


# Files


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

<p style="text-align:center"><strong>Congratulations, you have completed this lab! You can continue with the next one.</strong></p>
		
<center><img src="https://webexcctsa.github.io/wxcc-usecases/assets/gitbook/images/webex-small.png" width="100"></center>
