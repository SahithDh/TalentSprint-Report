# TalentSprint-Report
Internship Detailed Report

Industrial Internship Report
 At “ TalentSprint ”

By Venkat Sahith Dhulipudi

Currently Studying in Vellore Institute of Technology, Vellore
Reg No. 21BCE0733

Bachelor of Technology
in
Computer Science ( Batch of 25’)


Under Supervision of 
Ms.Asha Jyothi , Tech Manager 
TalentSprint pvt.Ltd, 
Hyderabad

Internship Duration : 17th Oct 2023 to 14th Nov 2023
Acknowledgement

Firstly, I would like to thank Ms. Asha Jyothi, Tech Team Manager, of TalentSprint Pvt.Ltd , Hyderabad for giving me the opportunity to do an internship within the organisation and for helping me along each step of the way while assisting and mentoring me with my work as well.

I also would like to thank all the people that work along with me for TalentSprint, Hyderabad with their patience and openness they created an enjoyable working environment. It is indeed with a great sense of pleasure and immense sense of gratitude that I acknowledge the help of these individuals. 

I am highly indebted to Dr. Santanu Paul (MD and CEO) and Anurag Bansal (Chief Sales Officer), for the facilities provided to accomplish this internship. 

I would like to thank the Chief Technology Officer,  Jitendra Singh for his constructive instructions and continuous support throughout my internship. 

I would like to thank Dr. Sathya K, (Assistant Professor Sr. Grade 1) for her support and advices to get and complete internship in above said organisation. I am extremely grateful to my department staff members who helped me in successful completion of this internship.


About the company

TalentSprint is well-reputed startup in the Ed-Tech industry offering professional courses for college graduates and freshers to up-skill their abilities and make them industry-ready . They use the latest concepts and technologies to create content for the users to maximise their learnings. TalentSprint strives to achieve the highest level of quality with each program offered and is dedicated to build partnerships with the leading universities in India to collaborate along with. The goal is to maximise the learning of each student and to provide them with the necessary skills to begin their career or advance forward in it. From prestigious university partners like IISc Bangalore, IIT Madras, IIT Kanpur, IIT Hyderabad and more, all the way to collaborations with top MNCs such as Google, Pega, Salesforce, etc.




ChatBot Implementation

Learning Objectives
 - To learn the creation, design, backend and the user interactions of a chatbot. 
 - Using Google DialogFlow and the Microsoft bot composer to create the flow of intents of the chatbot
 - To save user-given data to a database using integrated API calls

Abstract

Chatbots are computer programs that simulate human conversation through text or voice interactions. These AI-powered tools have become increasingly prevalent across various industries, offering a range of benefits, including 24/7 availability, improved customer service, and reduced costs. Chatbots can be categorised into two main types: rule-based and AI-powered. Rule-based chatbots follow predetermined rules and scripts, while AI-powered chatbots utilise natural language processing (NLP) to understand user intent and respond accordingly. AI chatbots are more sophisticated and can handle complex conversations, while rule-based chatbots are simpler and more suitable for straightforward tasks. Chatbots are employed across a wide spectrum of applications, including customer service, product recommendations, and marketing. They can provide immediate answers to frequently asked questions, guide users through complex processes, and even offer personalised recommendations. In the future, chatbots are expected to become even more advanced and integrated into various aspects of our lives. They may play a crucial role in healthcare, education, and even personal relationships, offering assistance and companionship.

Workflow

I started by watching a sample chatbot concept video to understand the goal of what the final product needs to look like. Then after finding two no-code chatbot developer tools to design a sample chatbot to understand the basic prompt and response structure. The two most prominent & user-friendly chatbot tools are Google DialogFlow and Microsoft Bot Composer. I started with the Google DialogFlow ES version to make the first sample chatbot with the purpose of getting basic details from the user. 



DialogFlow ES - Part 1

I began with the greetings intent to initiate the conversation with the chatbot, as soon as the greeting intent gets triggered, the agent(chatbot) will respond by asking the user for their name. This flow continues with the agent asking for basic details of the user and classifying each response as a particular entity that can be called later. Then the chatbot will prompt the user to choose a particular course that they are interested in and saves the users choice. 



Microsoft BotFramework Composer

The BotComposer is a service provided by Microsoft Azure Cloud to use their implementation of AI services to develop a chatbot to have real human-like conversation with the bot. This tool provides a lot of language/mood settings that can be activated to cultivate the response output of the bot. An option of witty, smart, funny, serious, etc. can be selected to tune the responses accordingly . This feature makes it more interactive for the user which could help the business attain higher customer reviews.  

I began by creating a sample bot to take an input(zip code) from the user and use the zip code to connect with the OpenWeather API to respond with the live weather conditions in the respective area as the zip code. The following temperature and weather conditions will be sent back to the user immediately. 


DialogFlow ES - Part 2

The second sample agent I created had the purpose of taking the name and email input of the user and then storing those inputs in the Google Firestore database. I began by creating the basic greeting intent by initiating the conversation with the user. Then the bot prompts the user to enter their name and the user responses are taken as entities. These entities for this agent have been made mandatory and are required to be entered. The entities are used to connect certain pre-defined parameters and we have the option to use them in any function that is required. In this case, I used the inline editor to edit the fulfilment code of the chatbot and then connect it using an API to the database created in Firestore. Each user response gets saved in the database immediately and then the bot asks the user to enter their email ID which also gets saved along with the names in the database. This database collection can be used to analyse data or initiate a trigger as required. 
Screenshots

Google DialogFlow 

Project 1 : To create a chatbot that can greet customers and ask basic questions such as college/work details

Agent Link : https://bot.dialogflow.com/764c57c7-e5d9-4244-84b8-14a95b591e0d


Project 2: To create a chatbot that collects users’ name and email address and saves it in a database for future reference
  
Microsoft BotFramework Composer


Project : The aim of this chatbot is accept a zip code input from the user and return the weather conditions and temperature back to the user. This Bot uses an API to connect it to the OpenWeather App to process the zip code and return the weather details.
