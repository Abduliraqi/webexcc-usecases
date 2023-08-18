---
title: Pre-requisites
author: Abdul Iraqi
date: 2023-08-01
layout: post
---

```
Last modified: Thursday, 10 August 2023
```

Before you start with adding the use cases to your demo tenant, you will need to have the following configuration already in your tenant:

- Webex Connect WhatsApp, SMS and Bot configuration
- Webex CC basic tenant configuration

Please follow the below list to ensure that you have the needed configuration done. 

## Webex Connect preparation:

The following need to be set up in order for the main Connect flows to work:
-	WhatsApp configured in the Connect Tenant.
- SMS configured in the Connect Tenant.
-	QA and Task Bots

## Webex CC preparation:

- Create an Inbound WhatsApp Entry Point 
- Create an Inbound SMS Entry Point  
- Create a Team 
- Create a WhatsApp queue 
- Create a SMS queue 

Please follow the Lab Guides for the initial Webex CC and Webex Connect configurations. 
[https://webexcc.github.io/](https://webexcc.github.io/){:target="\_blank"}

## Webex Calling Pre-requisites:

Webex Calling has to be configured before you start with the configuration of the Use Cases.
-	Create a User and provide a Webex Calling Extension
-	Use this Extension for your Agent Login in Webex CC Desktop
-	Assign a free Number  in Webex Calling and map it to an Entry Point in Webex CC
For how to set up those elements, please refer to Labs 1 – 3 of the Webex CC Lab guides 
[https://webexcc.github.io/](https://webexcc.github.io/){:target="\_blank"}



### Quick Links

> Control Hub: **[https://admin.webex.com](https://admin.webex.com){:target="\_blank"}**\
> Portal: **[https://portal.wxcc-us1.cisco.com/portal](https://portal.wxcc-us1.cisco.com/portal){:target="\_blank"}**\
> Agent Desktop: **[https://desktop.wxcc-us1.cisco.com](https://desktop.wxcc-us1.cisco.com){:target="\_blank"}**\
> Webex CC Documentation: **[https://www.cisco.com/c/en/us/support/customer-collaboration/webex-contact-center/series.html](https://www.cisco.com/c/en/us/support/customer-collaboration/webex-contact-center/series.html/){:target="\_blank"}**\
> Developer Portal: **[https://developer.webex-cx.com](https://developer.webex-cx.com/){:target="\_blank"}**\
> API Samples Git Repository: **[https://github.com/CiscoDevNet/webex-contact-center-api-samples](https://github.com/CiscoDevNet/webex-contact-center-api-samples){:target="\_blank"}**\
> Widgets Samples Git Repository: **[https://github.com/CiscoDevNet/webex-contact-center-widget-starter/tree/master/Examples](https://github.com/CiscoDevNet/webex-contact-center-widget-starter/tree/master/Examples){:target="\_blank"}**\
> 
<br>
<br>
--

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
