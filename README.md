# Website-to-APK
Website-to-APK

Ref.:
https://www.youtube.com/watch?v=FxkB_oiG3RI

DL:
https://drive.google.com/file/d/0B4ixd6TmQ1o5bUp5SmVXM1FYVmc/view

--------------------------------------------------------------------

STEPS:

1. Open the Drive link to download the file, save and extract.

2. Open the folder into editor.

3. Go to src/pages/home/home.ts

4. Find text  ur_website_url  and replace it with your website url.

5. Open the folder into cmd prompt and enter the following code:
ionic cordova build android

6. Hit enter 

7. After the build, the APK will be generated to the folder address:
websitetoapk\platforms\android\build\outputs\apk

8. Install it and you are good to go.

--------------------------------------------------------------------
FAQ

1.) Is there a way to change the name of the app and its icon image?

There will be a file named package.json in the folder where you can change the icon of the app. was able to change name and image in the file config.xml. Then you should have a folder such as resource ---> android ---> icon ...In icon folder add the respective icon image you want to.

2.)  I try to publish the generated apk from your project in the play store, but it shows me an error. To be more exact is this: "The file could not be uploaded. You have uploaded an APK or Android App Bundle that can be debugged. For security reasons, you must disable debugging in order to publish them on Google Play. See more information about the APK or Android App Bundles debuggable."

If you know how I can solve it, I appreciate it!
 
 the apk is not being uploaded to playstore because before uploading you need to sign your apk, its a proof that this apk belongs only to you .... mainly for security .... you search on youtube for signing ionic application....enjoy﻿

3.) how to add image in template instead of normal texts? well actually you added a text in home.ts I.e "<p> .....loading <p>" right ?then it goes to the respective URL we mentioned ..I wanna add a image instead of that text..I tried everything to my knowledge but nothing worked Sir ..is it possible to add a image instead of "<p>..... loading<p>"
 
<img src="assets/imgs/your_img_logo.png"  > use this tag to insert image

4.) I'm  getting [ERROR] An error occurred while running cordova build android (exit code 1)

        Error: Failed to find 'ANDROID_HOME' environment variable. Try setting setting it manually.
        Failed to find 'android' command in your 'PATH'. Try update your 'PATH' to include path to valid SDK directory.﻿
  
  please refer this https://forum.ionicframework.com/t/android-home-is-not-set-and-android-command-not-in-your-path/14821/5﻿









