# GDG-VR-AR-CodeLab

## Importing Packages

The packages can be imported like follows:
Assets->Import Package->Custom Package


The CodelabDemo.unitypackage contains the scenes and Unity folder of the codelab.

The Demo_Images.unitypackage is the package for Vuforia [stones-hire](https://www.google.com/url?q=http://www.azmangames.com/wp-content/uploads/2013/01/stones_hires.jpg&sa=D&usg=AFQjCNFvX1K9lrj51Uh3BSJlo9G0XvXMDg) image database.

CardboardSDKForUnity.unitypackage contains the Cardboard SDK.

vuforia-unity-5-0-5.unitypackage is the Vuforia SDK for Unity. It contains ARCamera, ImageTarget etc.


## Resources

[Vuforia Developer Portal](https://developer.vuforia.com/) for AR

[Unity Tutorials](https://unity3d.com/learn/tutorials)

[Cardboard Unity SDK guide](https://developers.google.com/cardboard/unity/guide)

[Cardboard Design Guidelines](http://www.google.com/design/spec-vr/designing-for-google-cardboard/a-new-dimension.html#)

3D models can be downloaded from the internet or from the Unity Asset Store. One of the websites is:
[Archive3D](http://archive3d.net/)

A guide on models supported in Unity can be found [here](http://docs.unity3d.com/Manual/3D-formats.html)

For model format conversion [Blender](https://www.blender.org/download/) can be used.

A [basic outline](http://docs.unity3d.com/Manual/android-sdksetup.html) on Android Developer Environment setup for Unity. While building for Unity under Player Settings for Android the Bundle Indetifier and company's name needs to be changed. The scene also needs to be included.

## Some things for AR

Select “ARCamera” and in Inspector panel, under “Dataset Load Behaviour (Script)”, “Load Data Set Image_Targets” and “Activate” needs to be checked(selected).

Make sure that all the required augmented objects are children of ImageTarget. 

Make sure that License key is entered in ARCamera in Inspector Panel.

## Unity Installation

Unity setup can be found [here](http://adarshaj.cse.iitk.ac.in/gdg/VR%20setup/)
