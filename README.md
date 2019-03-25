# Voice Agent with Watson

Voice Agent with Watson enhances your call center operations by orchestrating Watson services and integrating them with the telephone network. Your voice agent can listen and respond to customers using natural language.

## Pre-requisites

1. [IBM Cloud Account](https://ibm.biz/IBMCloudtrialfree)
2. [Twilio Account](https://www.twilio.com/try-twilio)

## Steps to build voice agent with Watson

Step 1- Create [Voice agent with Watson](https://cloud.ibm.com/catalog/services/voice-agent-with-watson) service in IBM Cloud 

![1](https://github.com/RiyaMRoy04/watson-voice-agent/blob/master/images/watson-1.png)


Step 2: Choose `DALLAS` as region and click on `CREATE`

![2](https://github.com/RiyaMRoy04/watson-voice-agent/blob/master/images/watson-2.png)


Step 3: Copy your `voice agent endpoint` in notepad for later use.

![3](https://github.com/RiyaMRoy04/watson-voice-agent/blob/master/images/watson-2a.png)


Step 4: Login Twilio and click on `Get a trial number` or `Get a free phone number`

![4](https://github.com/RiyaMRoy04/watson-voice-agent/blob/master/images/watson-3.png)


Step 5: Click on `Choose this number`

![5](https://github.com/RiyaMRoy04/watson-voice-agent/blob/master/images/watson-4.png)


Step 6: In the left side menu bar, click on `Elastic SIP Trunking`

![6](https://github.com/RiyaMRoy04/watson-voice-agent/blob/master/images/watson-4a.png)


Step 7: Click on `Get Started`.

![7](https://github.com/RiyaMRoy04/watson-voice-agent/blob/master/images/watson-4b.png)


Step 8: Click on `Create a SIP Trunk`.

![8](https://github.com/RiyaMRoy04/watson-voice-agent/blob/master/images/watson-4c.png)


Step 9: Create a New SIP Trunk by entering a name and click on `Create`

![9](https://github.com/RiyaMRoy04/watson-voice-agent/blob/master/images/watson-4d.png)


Step 10: In the menu option, click on `Origination` and in the right side click `Add new Origination URI`

![10](https://github.com/RiyaMRoy04/watson-voice-agent/blob/master/images/watson-4e.png)


Step 11: Enter the voice agent endpoint you had noted in Step 3 to `ORIGINATION SIP URI` textbox and click on ADD

![11](https://github.com/RiyaMRoy04/watson-voice-agent/blob/master/images/watson-4f.png)


Step 12: In the left menu options, click on `Phone Numbers`.

![12](https://github.com/RiyaMRoy04/watson-voice-agent/blob/master/images/watson-5.png)


Step 13: Under Manage Numbers>Active Numbers, Click on the phone number hyperlink

![13](https://github.com/RiyaMRoy04/watson-voice-agent/blob/master/images/watson-5a.png)


Step 14: In Configure>Voice & Fax, Select `SIP Trunk` option in `CONFIGURE WITH` and your SIP Trunk name in `SIP TRUNK`. Click on `Save`

![14](https://github.com/RiyaMRoy04/watson-voice-agent/blob/master/images/watson-5b.png)


Step 15: Click on `Manage`(within the Voice Agent service created in your IBM Cloud account) and click on `Create a voice agent`

![15](https://github.com/RiyaMRoy04/watson-voice-agent/blob/master/images/watson-6.png)


Step 16: Enter Name, Phone number and Description

![16](https://github.com/RiyaMRoy04/watson-voice-agent/blob/master/images/watson-6b.png)


Step 17: Click on `Create voice agent`

![17](https://github.com/RiyaMRoy04/watson-voice-agent/blob/master/images/watson-6c.png)


Awesome, you have now integrated your Twilio number and Voice agent with Watson!

Try dialing the Twilio number, you should now be able to hear Watson speaking!