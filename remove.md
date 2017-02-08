# How to remove MDM from an iPad
*I am not responsible for anything that goes wrong. I am also in no way responsible if you get in trouble for doing this. This guide is purely for people wishing to experiment with iOS.*

***

# The process

MDM stands for Mobile Device Management, it allows your institution to control your iPad. It also allows them to install restrictions.
The tool we are going to use cannot work with encrypted backups, as most MDM suites force backup encryption we will have to reset our iPad.

**ALL DATA WILL BE LOST.**

1: Plug in your iPad into your computer using a thunderbolt USB cable.

2: iTunes *should* automatically open. (If it doesn't open it from your start menu.)

3: A screen should pop up saying "Welcome to iPad" just click continue. You should now be on an information page. (If it doesn't open,
look on the far left on the devices screen and click on it.)

4: There should be a photo of your iPad. To the right of that, there should be two buttons - "CHECK FOR UPDATE" and "RESTORE". We want to select restore.

5: A popup asking you whether or not you want to restore will show up, select "Restore". Your computer will begin to download the latest version of iOS. You can check the progress of the download at the top right of the screen (near the minimize and close buttons.)

6: As soon as you have restored the default setup screen should show. With words such as "Hello" and "Hola" showing up. Keep your iPhone plugged into your computer and make sure you select (setup as new iPhone) on your PC.

7: Do the usual setup process that involves setting up Wifi and entering student or employee username and password. After you have done this your iPad will finally say "Welcome to iPad."

**IMPORTANT: READ THE STEP BELOW CAREFULLY.**

8: *AS SOON AS YOU CLICK THIS YOU WILL SEE YOUR HOMESCREEN* **OPEN THE CONTROL CENTER (SWIPE UP) AND TURN ON AIRPLANE MODE.** If you were quick enough, your appstore and iMessage app should still be there. **DO NOT TURN OFF AIRPLANE MODE.**

9: Go onto your computer and download iBackupBot from [here](http://www.icopybot.com/download.htm). Make sure you download iBackupBot and **NOT iCOPYBOT**. Most computers will be 64bit.

10: Open iBackupBot with your computer plugged in. On the devices section your iPad name should appear. Click on the name and a screen will popup. Make sure it says "Backup Encryption Off". Now click "Backup Now". Pick the default iTunes location and carry on. When it's done, a message will appear - "LOAD BACKUP INTO iBACKUPBOT" click Yes. At the top left of the screen a list of files should appear. Click the little plus (+) sign next to the name of your backup.

11: Scroll down and look for **System Files > HomeDomain > Library > ConfigurationProfiles** as soon as you have opened that folder (ConfigurationProfiles), delete everything in it. A warning will appear, ignore it (select yes.)

12: Look for the restore option at the top of iBackupBot. It is next to the red X (not the close program button.) Click it and a list of options will appear. Leave them as they are (**MAKE SURE THERE IS NO PASSWORD ON YOUR IPAD. MAKE SURE THERE IS NO AIRPLANE MODE.**) and click Restore. Leave your iPad to restore and wait for it to reboot. When it reboots verify it works correctly, you can now turn off airplane mode and you no longer have restrictions.

Congratulations, you have finished the guide. I will be adding images shortly.
