# TestMyBot (Botframework)

## What is it ?
Testmybot is a user friendly interface wich allow you to create functional tests for your chatbot.

## How to use it ?
First of all, in order to install it you will need to execute these commands :

    npm install
Also make sure you have installed docker.

To launch the emulator, use this command :

    npm run emulator

testmybot simulates your chatbot and then you can start a dialog with it. Once you are satisfied with your test, you can write #SAVE \<filename\> to save the test or #EXIT to quit the interface.

> files are saved in spec/convo

![enter image description here](https://cdn-images-1.medium.com/max/1600/0*Nds_sN8-YAVrMOQA.)
 
When you wrote all your tests, you can launch it with the command :

    npm run test

You will get an output similar to this :
![enter image description here](https://cdn-images-1.medium.com/max/1600/1*NXTbHbmZtnubamumDEeMjw.png)

sources :
https://github.com/codeforequity-at/testmybot
https://github.com/botium/botium
