# WSA-QUICKINSTALL
A simple script for installing apks onto the Windows Subsystem for Android by simply double clicking it. 
This is just a bat script run through bat to exe to allow Windows to set it as a default app for .apk files.
Includes ADB.
Windows Defender can faslely flag this for whatever reason, so keep that in mind. 

Installation (Ensure that Developer mode in WSA is enabled beforehand):

1) Extract the ZIP (NOTE: Windows Defender falsely flags the exe)
2) Right click on any APK Files and select properties.
![Screenshot (125)](https://user-images.githubusercontent.com/63358288/138408565-915ff6aa-6226-4b22-bc0b-20827f408504.png)
2) Select change 
3) Scroll down to the bottom and select choose app
![Screenshot (126)](https://user-images.githubusercontent.com/63358288/138408800-1203fde0-3e12-4c41-b022-86e6d0cf6fb2.png)
4) Browse to the location you extracted the ZIP and select install.exe
![Screenshot (127)](https://user-images.githubusercontent.com/63358288/138408967-795c50db-0b61-4e85-a78e-57fd355ac51d.png)
5) Apply settings.

Now just double click any APK you want and it should install instantly. 

Credits to (https://github.com/99fk) for bat to exe, HarshalKudale for making the same script before me and remixicon.com for the Android logo.
