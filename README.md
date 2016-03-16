# eclipse-to-android-studio-migration

How to migrate project from eclipse to android studio

Android Studio is the official integrated development environment (IDE) to develop android apps. It was announced in 2013 Google I/O conference. Based on JetBrains’ IntelliJ IDEA software, Android Studio is designed specifically for Android development. It has replaced Eclipse Android Development Tools (ADT) as Google’s primary IDE for native Android application development. And, now it is strongly recommended to migrate the projects to Android Studio from ADT.

Migrating to Android Studio requires changing the structure of the project and moving to a new build system. Here is the link with instructions for migrating eclipse project to android studio:

http://developer.android.com/sdk/installing/migrate.html

Tired of reading a lengthy documentation? 
Well, I have a simpler way to migrate and here you go!

Start off with a sample android studio project.
Open android studio and create a new project (or) just download a ‘sample’ studio project here: https://github.com/AppLozic/eclipse-to-android-studio-migration.

Now, open the downloaded project in Android Studio by following the below instructions.

Import eclipse project modules into Android Studio.
Select File -> New -> Import Module

ADT project importer

Next, select the path of the eclipse project and import the modules. In case, if you see the message “Failed to sync Gradle project”, then click on “Install Build Tools and sync project…”.

Now, remove the sample project modules by following the below simple steps:

Open settings.gradle and remove “include ‘:app’”
Right click on “app” module and “Delete” it.

Now, what we have is the eclipse project open in android studio with the gradle build.

Here are few other links which might help you:
http://developer.android.com/sdk/installing/migrate.html
https://www.youtube.com/watch?v=b84t7p9YuX8

Hope this helps. Have queries? Feel free to comment below, would be happy to answer/resolve.

Happy Coding :)

Originally posted in: http://www.applozic.com/blog/migrating-project-from-eclipse-to-studio/
