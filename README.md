# ZagsBeFree
## About:
A Google Assistant Bot for EXLCUSIVELY ANDROID DEVICES that automates interactions with the Zagster bicycle SMS bot.

## Elevator Pitch
  Do you have a subscription to Zagster Bicycles on your campus? Do you hate being charged $24 each time you forget to end your rental overnight? If so, ZagsBeFree is here to fix your problems.
  
## What does ZagsBeFree Do?
  Essentially what this bot does is allow the user to use voice commands in Google Assistant to interact with the Zagster bicycle SMS 
bot to receive an SMS notification containing the unlock code for the desired zagster bicycle. At the same time, the ZagsBeFree bot will automatically terminates the user's ride after 30 minutes. This allows the the user to lock his or her bike at the end of their rental and walk away without needing to worry about Zagster charging them extra money for not ending their rides. Because of a design flaw in Zagster bicycles, users can still ride an UNLOCKED Zagster bicycle even after the rental has ended. This means that even though my ZagsBeFree bot automatically ends the rental after 30 minutes, a user can still have rides that extend past 30 minutes. Just remember to lock up the Zagster after you park it!  

## VERY IMPORTANT NOTE:
You can only start a zag rental by telling Google Assistant the Zagster bike number in exactly this format: "Unlock zag ####" where #### represents the Zagster bike number of the bike you want to unlock. 

## How to get ZagsBeFree on your device?
It's about to get super complicated. Follow my directions closely...
1. Create IFTTT account at https://ifttt.com and sign in on your PC
2. Install IFTTT on your phone from the Google Play Store and log in on your phone
3. Install Stringify on your phone from the Google Play Store
4. On your phone, open Stringify.
5. Go to the flows menu on the bottom right of the screen
6. Click the plus sign on the bottom right and tap "Create a new flow"
7. At the Center bottom, click the plus sign and then click on IFTTT
8. Drag the IFTTT circle icon to any circle outline on the screen
9. Click the plus sign on the bottom center again, and this time select Timer.
10. Drag the timer icon to the circle outline right and directly adjacent of the IFTTT circle. 
11. Tap the timer and tap "start timer"
12. Set the Countdown for 30 minutes.
13. Navigate back to the flow map with the circle icons and the circle outlines. 
14. Drag a line from the IFTTT circle to the Timer circle to connect them
15. Tap on the center bottom plus sign again, and tap on the IFTTT Circle. 
16. Drag the IFTTT circle icon to the circle outline right and directly adjacent of the Timer circle.
17. Finally, drag a line from the Timer circle to the IFTTT circle to the right of it to connect them.
18. Tap Enable Flow at the bottom of the screen. 
19. Go to https://ifttt.com/applets/F6shHdzZ-google-assistant-start-zagster-rental on your PC and toggle on the applet. Make sure you're         signed in.
20. Click on the Gear icon on the applet, and in the dropdown menu for Stringify ID, select the Stringify ID that matches with the            Stringify ID that you can access by tapping on the leftmost IFTTT circle in your Stringify flow on your phone. (Note, after you tap       on the IFTTT circle to check your Stringify ID, instead of tapping save to go back to the flow map, tap your back button instead          so that Stringify doesn't think that you made any changes) 
21. Click on the textbox right below "Phone Number" and enter the phone number that accesses the Zagster SMS bot. 
22. Click Save at the bottom.
23. Go to https://ifttt.com/applets/rUt9YP5z-end-zagster-rental on your PC and toggle on the applet. Make sure you're signed in. 
24. Click on the Gear icon on the applet, and in the dropdown menu for Stringify ID, select the Stringify ID that matches with the            Stringify ID that you can access by tapping on teh leftmost IFTTT circle in your Stringify flow on your phone. (Note, after you tap
      on the IFTTT circle to check your Stringify ID, instead of tapping save to go back to the flow map, tap your back button instead
        so that Stringify doesn't think that you made any changes)
25. Click on the textbox right below "Phone Number" and enter the phone number that access the Zagster SMS bot.
26. Click on Save at the bottom.
27. FINISHED!

## Demo Conversation
User: Ok Google, unlock zag 3237

Google Assistant: Ok. You should receive an SMS notification with the unlock code soon

Zagster SMS bot: Your rental of bike 3337 has begun. Unlock by typing 33131 into the bike's keypad. This code is available...

*30 minutes later*

IFTTT: *sends text message saying "end" to the Zagster SMS bot*

Zagster SMS bot: Your zagster has ended. Thanks for riding Zagster!

