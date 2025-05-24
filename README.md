# Remote_pi

## Small Introduction
**Remote_pi** is a project made in node red platform it is used to operate the raspberry pi via your phone's messaging app called Telegram 

Means your phone's messaging app is your pi terminal, you can list the directory, run any script, write the notes using echo command etc

![Block Diagram](/Images/Block_Diagram.png)

## Hardware and software Component

**1. Raspberry pi - Hardware** 
>Any version of PI user can use that is having ethernet or Wifi functionality

>User can also use any other linux machine rather than raspberrey pi but in this project we took Raspberrey PI only for reference. 

**2. Node-RED platform - Software tool**
 >Refer this [link](https://nodered.org/docs/getting-started/raspberrypi) for installing Node-red software in your PI.

 ## Creating Telegrambot 

 1. Open Telegram app in your phone
 2. Search "BotFather" and go into that chat
 3. Write "/start" command in chat, it will give you list of commands that this bot support

 ![start](/Images/start_new_bot.jpg)

 4. After this write "/newbot" for creating your new bot

 ![create](/Images/create_new_bot.jpg) 

 5. Name your bot that should display in telegram list 

 ![created](/Images/Bot_name_done_2.jpg)

 6. Now you has to create the username as stated in the message 

 ![username](/Images/Bot_done.jpg)

 >Copy the HTTP API token and paste it somewhere, this token is used by node-red in coming steps 

 ## Steps to enable RemotePI using Node-RED






