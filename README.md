# Android-NotificationBubble

Add the following to your Project level gradle

allprojects {
    repositories {
        jcenter()
        //The line below is added.
        maven {
            url "https://jitpack.io"
        }
    }
}

And also add to your app level gradle

 compile 'com.txusballesteros:bubbles:1.2.1'
