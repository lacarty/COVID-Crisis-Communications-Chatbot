# COVID Crisis Communications Chatbot

This project provided an understanding of chatbots and other AI-enabled resources through the use of IBM Watson Assistant services to build, train and deploy conversational interactions into an application.  

## Contents

1. [Overview](#overview)
2. [Video](#video)
3. [Steps for Initial Build](#steps-for-initial-build)
4. [Features of Expanded Build](#features-of-expanded-build)
5. [Resources](#resources)
6. [Datasets](#datasets)
7. [Technology](#technology)
8. [Disclosures](#disclosures)
9. [License](#license)

## Overview
With the Watson Assistant powered Crisis Communications Starter Kit, created a chatbot on an IBM Cloud hosted web server.  
The chatbot can be accessed at https://covid-assistant-simple-carty.mybluemix.net when a Watson Assistance instance is launched.

By building out a more complete solution of the initial chatbot framework provided by IBM’s Call-for-Code 2020 Solution Starter Kit, its capabilities were expanded to provide answers and comfort to children affected by the COVID19 crisis.  This was accomplished by creating new intents, entities and dialog nodes capable of addressing the concerns of children during the COVID-19 pandemic, as well as, creating additional entities and annotations to further train the chatbot.

The chatbot can respond by sharing consistent and accurate information, automating answers to common COVID-19 questions and dynamically updating information with the latest developments and recommendations.

### The problem
Communications are needed in a time of crisis and chatbots are an excellent way to provide information and open up resources.  Though it may not be noticeable, children experience quite a bit of fear and anxiety during a crisis situation.  This chatbot was expanded to help alleviate those fears by answering the questions of children, such as, “Can I hug my dog?” or “Why do I have to stay home?” Children can interact with the chatbot by asking various questions regarding coronavirus, laughing at chatbot’s jokes and even playing a few games!  This chatbot will be you child’s source of comfort and a digital friend when they find themselves feeling uneasy and facing the unknown.  They will gain a better understanding of the coronavirus, thereby enabling them to feel more in control and secure. 


## Video

[![Project Demo](/images/demo_video-img.png)](https://vimeo.com/435363746)


## Steps for Initial Build 
Summary of steps for initial build of COVID Crisis Communication Chatbot using tutorials provided by IBM.

1. Provision an instance of Watson Assistant (Requires registering for an IBM Cloud account).
2. Add a dialog skill to your Watson Assistant instance.
3. Connect your Watson Assistant with Watson Discovery.
4. Create Cloud Functions.
5. Integrate data sources via a Watson Assistant webhook.
6. Create a simple Node.js application.
7. Connect the application to a chatbot using the IBM Watson Assistant APIs.
8. Test and run the application locally.
9. Deploy the application on IBM Cloud as a Cloud Foundry application.


### Watson Assistant Dialog Skill
![Skills FAQ](/images/skill_cdc_covid_faq-img.png) 



## Features of Expanded Build 
Built out chatbot by adding Intents, Entities and Dialog Nodes to address concerns specific to children.


### 1. Add new Intents 
![Intent ChatbotForKids](/images/intents_chatbotforkids_chatbotimage-img.png) 
![Intent Jokes](/images/intent_jokes-img.png)  

### 2. Add new Entities; Add synonyms to existing Entities
![Entity Family](/images/entity_family-img.png) 
![Entity Friends](/images/entity_friends-img.png) 
![Entity Pet](/images/entity_pet-img.png) 
![Entity Child](/images/entity_child-img.png) 
![Entity SchoolType](/images/entity_school_type-img.png) 

### 3. Add Dialog Nodes 
![Dialog Node](/images/dialog_node_chatbotforkids-img.png)

### 4. Create favicon for chatbot at www.favicon.cc.
![Favicon Chatbot](/images/favicon_chatbot-img.ico) 

### 5. Create game features for children such as a guessing game (similar to “Hangman”) for common COVID-19 terms, or design a face covering for bot. (Future feature)  

### 6. Deploy as a third party integration by adding to Slack app as a bot user. (Future feature)



## Resources

### Source for COVID-19 information
- [CDC COVID-19 FAQ](https://www.cdc.gov/coronavirus/2019-ncov/faq.html)

### Tutorials and Documents:
- [Create a crisis communication chatbot and connect it to news and COVID-19 data sources](https://developer.ibm.com/tutorials/crisis-communication-chatbot-watson-assistant-webhook-integration-discovery-covid-data/) 
- [Integrate a COVID-19 crisis communication chatbot on a website](https://developer.ibm.com/tutorials/create-a-covid-19-chatbot-embedded-on-a-website/)
- [IBM Call for Code 2020 Solution Starter Kit](https://github.com/Call-for-Code/Solution-Starter-Kit-Communication-2020)
- [Watson Assistant, Skills](https://cloud.ibm.com/docs/assistant?topic=assistant-skills)
- [Watson Assistant, Adding Entities](https://cloud.ibm.com/docs/assistant?topic=assistant-entities#entities-annotations-overview)
- [Watson Assistant, Contextual Entities](https://youtu.be/3WjzJpLsnhQ)
- [CDC, Coronavirus Disease COVID-19, Frequently Asked Questions](https://www.cdc.gov/coronavirus/2019-ncov/faq.html)



## Datasets

- [covid19api](https://covid19api.com/)


## Technology

### IBM technology

- [IBM Watson Assistant](https://www.ibm.com/cloud/watson-assistant/)
- [Watson Discovery](https://www.ibm.com/cloud/watson-discovery)
- [IBM Cloud Functions](https://cloud.ibm.com/functions/)

### Open source technology

- [Node.js](https://nodejs.org/en/)
- [Apache OpenWhisk](https://openwhisk.apache.org/)


## Disclosures from IBM

"This tool is intended to provide information based on currently available CDC and other public information to help you make decisions about seeking appropriate medical care. This system is not intended for the diagnosis or treatment of disease or other conditions, including COVID-19, and you should not provide any personally identifying or private health information.

This Watson Assistant bot is populated with data that is sourced from the following resources:

- Most static responses provide information found on the CDC's COVID FAQ Page: https://www.cdc.gov/coronavirus/2019-ncov/faq.html
- Dynamic infection and death counts are sourced from Johns Hopkins University via the following API: https://www.covid19api.com/
- Dynamic news stories are sourced from Watson Discovery's news feed. Additional information on that service can be found here: https://www.ibm.com/watson/services/discovery-news/"


## License

This solution starter is made available under the [Apache 2 License](LICENSE).
