Android keystore (credential storage) access
============================================

Direct access to Android's credential storage (keystore). Sample code for the 
'Storing application secrets in Android's credential storage' blog post: http://nelenkov.blogspot.com/2012/05/storing-application-secrets-in-androids.html. 

Accesses the credential storage directly using a private API. Not guaranteed to
 work on all Android versions, but tested with 2.1 to 4.0. 

2013/8/21: updated for Android 4.3. Blog post: 
http://nelenkov.blogspot.com/2013/08/credential-storage-enhancements-android-43.html

2014/1/16: updated for Android 4.4. Major changes in Android are support for 
EC and DSA keys. Added ECDSA sign/verify sample.

