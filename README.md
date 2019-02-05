# Chatbots 201 - Enhance your chatbot! 

This repository contains a lightweight version of the [Watson Assistant Labs](https://github.com/garyrwilson/Watson-Assistant-Labs) created by [@garyrwilson](https://twitter.com/garyrwilson) focused on the advanced abilities of Watson Assistant.

In these workshops you will see how to:
- Understand User Sentiment using _**Watson Natural Language Understanding**_
- Extend your Chatbot using _**Watson Discovery**_
- Integrate External Data using IBM Cloud Functions

Once you've worked through the lab exercises, you'll be fully equipped to create your own chatbot using _**IBM Cloud**_ and _**IBM Watson**_!

## Before you begin

To complete this workshop you will need:
- an IBM Cloud account
- a Watson Assisatnt service
- to import an existing Skill

**Creating your IBM Cloud account**

1. [Sign up for an account here](https://cloud.ibm.com)
2. Verify your account by clicking on the link in the email sent to you
3. Log in to your IBM Cloud account

**Provisioning the Watson Assistant service**
1. Click on "Catalog" on the top-right corner
2. Search and select "Watson Assistant" 
3. Under **Choose a region/location to deploy in:** select **Dallas**
3. Click "Create"

**Importing a Skill to your Watson Assistant**
First of all, download the following Skill file and save it somewhere you'll remember:
[Skill file (Right click -> Save Link As)](https://github.com/IBMDeveloperUK/Watson-Assistant-Labs/raw/master/workspace.json)

1. Go go your [Resource list page](https://cloud.ibm.com/resources)
2. Click on your Assistant service under the **Services** dropdown
3. Launch the tool by clicking on the **Launch tool** button
4. On the homepage, click **Create a Skill**
5. Select **Create New**
6. Go on the **Import Skill** tab, click **Choose JSON File** and select the previously downloaded file.
7. Click **Import**! 

## All set!

# Workshop materials
The workshop materials for each part of the lab are contained in the subfolders README files:
* [Lab 1: Understanding User Sentiment - Integrating Watson Natural Language Understanding](./1-Sentiment)
* [Lab 2: Extending Your Chatbot with Watson Discovery](./2-Discovery)
* [Lab 3: Integrating External Data using IBM Cloud Functions](./3-External)
* [Lab 4: Chatbot Integrations](./4-Integrations)