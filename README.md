A fork of Google VR SDK for Unity, seperated gvr.aar into two files, with uilayer.jar containing the new UiLayer class with isSettingsButtonEnabled set to false in constructor and getBackButtonEnabled() always return false

To apply the change to your project, download the new uilayer.jar and gvr.aar (you can find them here https://github.com/cdr9042/gvr-unity-sdk/tree/master/Assets/GoogleVR/Plugins/Android)

Put them in Assets/Plugins/Android in your project.

Delete the old gvr.aar. If you used Unity Package Manager to get Google VR, you can find that file in Packages/Google VR Android/Plugins/Android/. You can locate it in explorer to delete it
