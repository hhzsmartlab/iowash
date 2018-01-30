# 4. Evaluation
## 4.1 Validation
### Observations in #1 Iteration

**Phase 1)**

The users either scan the QR code either directly when they come to the washing machine and interact with the smartphone 
or they only use the tablet. They do not understand why they need the smartphone for doing their laundry. 

**Phase 2)**

Users that use their smartphone immediately focus on the mobile application without taking note of the washing machine's display. 
Many probands choose their program on the tablet and change the settings via the display. Therefore, they do not understand why to use the smartphone. 
Many probands change the program settings on the machine's display and on the smartphone and expect that the settings are not applied when choosing an option on one of the displays. 
Additionally, many users search the start button on the tablet, because they are not using their smartphone for selecting the program. After a while of searching the start button, the probands that may be the QR code might help. However, this media break confuses when focusing on the washing machine's display.

**Phase 3)**

Some probands react positive on the expiration of the timer, others do not see the notification immediately.


### Claim Feedback in Google Form

**How did you like the iowash service?**

+ Application was basically seen positively
+ Verry accessible
+ Concise smartphone interface
+ Good Idea
+ Missing start button on the UI on the washing machine
+ If the setting is made on the washing machine and then the QR code is scanned, the settings made will overwrite


**Which Features did you find most useful?**

+ Quick access
+ easy to start
+ easy selection of washing programms
+ easy payment
+ Timer
+ timer should provides an audio signal


**What additional features would you expect?**

+ Reminder, e.g. Some minutes before time is over to prepare to get the laundry
+ direkt start with the UI on the washing maschine
+ possibility to save customer settings
+ Timer start, e.g. Put the laundry in the machine on the morning, later on (finish when I come home)


**Which Features did you struggle with?**

+ media break between smartphone and machine display
+ If the setting is made on the washing machine and then the QR code is scanned, the settings made will overwrite
+ starting the machine
+ Transition from the machine to the app unclear


**How could the service be easier to use?**

+ Guide the user to detail configuration settings on the maschine’s display
+ one central controll
+ exclude unrealistic settings
+ Note on cash machine in the UI

### Implications

Due to the observations and feedback in the first iteration, changes are made to the test application:
-	Now it is possible that not only changes on the smartphone are transferred to the tablet, but also vice versa, that changes made to the machine display are reflected on the smartphone display. 
-	Some test persons also looked for the start button on the display attached to the washing machine. Therefore, the note "scan QR code or go to pay station" was added. 
-	In addition, the result of the observations is incorporated, that as soon as changes have been made to the washing machine, the "Custom" button is selected on the smartphone display, which shows "see on washer". This informs the user that special settings have been selected directly at the washing machine and can be looked up there.

-----


### Observations in #2 Iteration

**Phase 1)**

Most of the probands are focused on the washing machine's display. 
The probands usually try to change the settings on this display. 

After one of the probands has changed settings on the tablet and changed the QR code with the smartphone, he is focused on his smartphone.   
Another test person changes the settings again via smartphone and observes the transferred changes on the tablet.
The hint on the tablet that you should either scan to the payment machine or the QR code is helpful for switching from the tablet to the smartphone. The test persons understand that the QR code is to be scanned and then the washing process is to be started via the app. 

**Phase 2)**

The test persons choose their desired program directly at the washing machine. 
However, the three standard programs on the smartphone usually cause confusion. 

**Phase 3)**

The test persons observe the timer and notice the notification on the smartphone. 


### Claim Feedback in Google Form

**How did you like the iowash service?**

+ good
+ okay
+ I like it


**Which Features did you find most useful?**

+ made settings on the washing machines are shown on the smartphone
+ digital process more convincing than analogue
+ Timer on the smartphone


**What additional features would you expect?**

+ Custom settings should be saved and not lost again
+ Automatic filling of the washing powder


**Which Features did you struggle with?**

+ Scan QR code does not work properly. Display on the machine does not really change when the timer is started in the app. It makes sense to disable the menu selection and only show the timer with a note "occupied" or "reserve now afterwards" with its own QR code (?)
+ Find the right program


**How could the service be easier to use?**

+ Machine should remain locked until the user is authenticated again - Otherwise, someone steals my laundry
+ Control everything through the app


### Implications
Due to the observations and feedback in the second iteration, the following changes are made:
- As soon as changes are made to the tablet attached to the washing machine, the "Custom" button is selected on the smartphone and now also the exact details of what has been selected. In this way, the smartphone allows the user to recognize which wash setting is currently set. 
 - Because the test application does not send out a notification that the laundry is finished until the timer has arrived at 0min. As this has been criticized, the trigger for the notification is set to 5min, so that the user is informed shortly before the end of the washing process.


## 4.2 Conclusions

[:arrow_backward: ](../03_Experimentation/3_Experimentation.md)[:arrow_up_small: ](../README.md)

