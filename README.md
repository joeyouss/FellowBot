# FellowBot
# FellowBot 🤖
### MLH kick-off hackathon Project - FellowBuddy Discord Bot
https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white

## **Hi there ! :wave:**

![Cover](Fb.gif)
<div align="center" style="height : 800px">
Talk 💠 Get help 💠 Scrape!
                            </div>

### **This is FellowBot - an MLH kickoff project, a bot and your friend!.**

We understand how sometimes life in particular can be difficult and since we are now MLH Fellows, we thought of making something which can be used by every fellow in the server and which makes their life easy.

## Table of contents :
- [Introduction](#introduction)
- [Techstack](#techstack)
- [Scalability](#scalability)
- [Installing](#installing)
- [Contributing](#contributing)
- [Privacy and security](#privacy-and-security)
- [What we are proud of](#what-we-are-proud-of) 

## Introduction
The project is a discord bot with the following features:
- 🧠 Mental health support - We understand how stressful it can be to manage everything and keep a positive attitude. Come talk to FellowBot about stress, life and unwanted feelings and it will help you!. Have difficulty managinng time? It will recommend you techniques to stay focused. Having a bad day? It will tell you a joke too!. Want motivation? Well, FellowBot will send you an inspiational quote too!.
- ✨ Handbook scraping - We understand that you might not remember every page of the handbook but we also agree it is your best friend in this fellowship!. So, need to search for a particular page? Just type in a relevant keyword from our list of keywords and have the information directly in your discord. Say goodbye to searches again!


## Techstack
- 🤖 Discord API - For creating the bot
- 🧑‍💻 Flask - to keep our bot alive and work in real time!
- 🥣 Beautiful Soup- To scrape the data beautifully.
- 🛌 REST APIs - to fetch quotes and jokes for the fellows
- 🐍 Python - The beautiful language to write our dynamic code.

## Bot commands
### Functionality 1 -> answering your MLH handbook related questions
-> Make sure to prefix your query with "!faq" for trigerring bot faq commands. List of keys:
- 😄 **MLHintro** - For in depth introduction to MLH fellowship.
- 🌲 **MLHevents**- What are MLH events? Know everything about them.
- 🚂 **pods** - What are pods? Know everything here
- 📱 **discord** -How to use discord and which channel serves what purpose
- 📞 **zoom**- What is zoom used for?
- 📢 **feedback** - What is feedback in MLH?
- ⏰ **remote** - How to work remotely and give your 100% in MLH.
- 📏 **hackathonrules** - Rules for hackathons
- 🥇 **hackjudge** - How do judges make a decision for hackathon winner? What is taken into consideration?
- 💯 **hackdemo** - How to prepare a good demo for hackathon?
- 🙋 **attendance** - What is the importance of attendance in MLH and how is it monitored?
- 💁 **expectations** - What MLH expects from you as fellows
- ⛑️ **help** - Facing problems in MLH? Reach out to us


### Functionality 2 -> Mental health bot (recommends quotes, jokes and makes you happy)
-> Enter any sentence which describes how you feel. For example, "I am sad today" and see how out bot brings a smile on your face!

### Functionality 3 -> Emergency Hotline numbers 
Use ![your emergency] to trigger out helper bot or just enter **!all** to get every helpline number.

## Scalability 🌺
The project can be scaled to fulfill huge possibilities. The current scalable paths comprise of :
- Extending the functionality to make the bot more dynamic i.e. text summarization for cosine similarity between asked questions. This will enable us to make our bot more useful.
- An event scheduler embedded into the bot so that every fellow receives a msg reminding him/her of the event/meeting coming up.
- Howdoi integration - We wanted to integrate howdoi library with discord. Howdoi is a library for answering questions asked by developers. Since fellows are developers, it would be a great functionality to integrate it so that their search is just a msg away!

## Installing ⚓
- Fork the repo and clone it in your local system.
- Get all the requirements from the requirements.txt file
- Go to Discord Developers Portal and get your token_id and Guild (application id)
- **IMPORTANT**- Ask the project maintainers for the database access. We understand the database inside the handbook is exclusive and for use by MLH fellows. How to ask? In your local system, add your name, MLH pod number, discord username, gmail id and make a PR. Once we cross check, we will approve the PR and share the "scraped" database with you.
- Enter the variables hence acquired in .env file
- Got to Discord Dev Portal -> Auth0  -> give the bots the rights to send messages -> copy the link which appears.
- copy the link in your own browser and authorize the bot.
- Voila! Your bot is ready!

## Contributing 👬
Being open-source fellows, we used this opportunity to invite contributions from the whole MLH family!. The project is hence hosted as open source and you are welcome to make it more scalable and better !

## Privacy and Security 🔐
We agree that the handbook should be of use to the MLH fellows hence the bot should not be authorized by someone who does not own the rights to the hand book!. So we explicitly ask for details to respect MLH's discretion.

## What we are proud of ? 🥳
Since none of us had any idea about creating Discord bot, the hard work we have put in and the hours we spent on coding made us believe what we as a team can do. Even though we were running late by 2 days, we still decided to start a new project from scratch since it was more useful and ambitious. The experience was thrilling and we had/still having fun coding the project !
