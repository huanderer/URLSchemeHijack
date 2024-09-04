Use Android studio to run this. 
Modify line 34 in AndroidManifest.xml in the POC app to clash with the identical application. 
E.g. you're running a test against an app which has <data android:scheme="Nukacola" android:host="main"/> defined in its AndroidManifest.xml. Replicate that. 

Modify line 29 in app/res/layout/activity_main.xml to change the title text for the login page. 
Press the play icon in Android studio with your test device plugged in and then proceed to click on your deep link/launch it through ADB. 
You should see a dialog box pop at the bottom of the screen asking you which app you would like to use to open the deep link. 
