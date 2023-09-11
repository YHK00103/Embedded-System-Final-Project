# Embedded-System-Final-Project

## Introduction
The project is to implement a smart medicine remindbox by using raspberry pi4.  
The functions of smart medicine remindbox are the following:
1. Recording  
Users can record the name of medicine and when they need to be reminded to take medicine via voice. Then, the raspberry pi will use STT to translate their voice to words and update to Google sheets. Meanwhile, it will check whether users put the medicines into remind box.

3. Reminding  
When the reminder time is up, raspberry pi will get the medicine information from Google sheet and use TTS to convert the reminder texts into sound.

3. Checking  
After reminding the medicine-takers, raspberry pi will check if the medicines in the remindbox have been taken. If the medicines still exist, raspberry pi will remind the medicine-taksers again.

## Demo Video
https://youtu.be/kjYIVIQ_vwI
