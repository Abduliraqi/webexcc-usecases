---
title: Template
author: Cisco CC TSA Team
date: 2023-08-10
layout: post
---

```
Last modified: Thu, 10 August 2023
```

## Overview of the Use Case:

This Use Case 



### Demo Video

> The video below shows a demo about this Use Case:

{: .block-tip }
<div style="padding-bottom:60.25%; position:relative; display:block; width: 100%">
	<iframe src="https://app.vidcast.io/share/embed/e4b450ff-9d3f-424d-96bb-2f0988b81743" width="100%" height="100%" title="Station Login" frameborder="0" loading="lazy" allowfullscreen style="position:absolute; top:0; left: 0"></iframe>
</div>

### How to configure this Demo Use Case in your Tenant

1.	**WA_Selector.workflow**
2. Create a new flow and Import from WA_Selector.workflow in the ConnectFlows directory.
3. Make the following changes:




# Basic Features

| **Entity**           | **Name**                                                               |
| -------------------- | ---------------------------------------------------------------------- |
| Agent 1              | <w class = "attendee-class">attendeeID</w>_agent1@mailinator.com       |
| Supervisor 1         | <w class = "attendee-class">attendeeID</w>\_supervisor1@mailinator.com |
| Agent Profile        | <w class = "attendee-class">attendeeID</w>\_agentProfile               |
| Entry Point          | <w class = "attendee-class">attendeeID</w>\_EP                         |
| Queue                | <w class = "attendee-class">attendeeID</w>\_Q                          |
| Team 1               | <w class = "attendee-class">attendeeID</w>\_team1                      |
| Team 2               | <w class = "attendee-class">attendeeID</w>\_team2                      |
| Outdial ANI          | <w class = "attendee-class">attendeeID</w>\_outdialANI                 |
| Outdial ANI Entry 1  | <w class = "attendee-class">attendeeID</w>\_outdialANIEntry1           |
| Address Book         | <w class = "attendee-class">attendeeID</w>\_addressBook                |
| Address Book Entry 1 | <w class = "attendee-class">attendeeID</w>\_addressBookEntry1          |
| Multimedia Profile   | <w class = "attendee-class">attendeeID</w>\_MMP                        |

> **NOTE:** Please create all the tenant entities following the naming convention mentioned specified in the table above. Your _attendeeID_ is provided in the email in the **"Attendee ID"** line.
{: .block-warning }

> Be aware that all entities that don't match with attendee IDs will be deleted
{: .block-warning }



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
		
<p style="text-align:center;"><img src="/assets/gitbook/images/webex.png" width="100"></p>
