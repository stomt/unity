# STOMT Unity-SDK [![STOMT API](https://img.shields.io/badge/stomt-v2.10.X-brightgreen.png)](https://rest.stomt.com/)

<p align="center">
  <img alt="STOMT Unity Feedback Integration" src="https://cdn.stomt.com/uploads/Dh1x/origin/Dh1xzkpSoHXH2UGuh3rNX35WR4DSjiqq4TLeu9Ag_origin.gif" />
</p>

This Widget allows the easy integration of the feedback solution [www.stomt.com](https://www.stomt.com/) in your Unity apps and games. Of course you can find the STOMT feedback widget for Unity3D in the [Unity Asset Store](https://www.assetstore.unity3d.com/en/#!/content/64669).


## Use-Cases

_What will the result look like?_ 

Example Games that use our integrations:

* [Empires of the Undergrowth](https://www.stomt.com/empires-of-the-undergrowth)      
* [All Walls Must Fall](https://www.stomt.com/AWMF)


## Installation

1. Download this repository and [or get it from the AssetStore](https://www.assetstore.unity3d.com/en/#!/content/64669) and copy the assets into your project.

2. Add the ```StomtPopup``` prefab to your main UI canvas.


## Configuration

1. Register on [www.stomt.com](https://www.stomt.com/signup/game) 

2. And create an [App Id](https://www.stomt.com/integrate) for your project.

3. Enter all necessary data into the ```StomtAPI``` component on the prefab.     

* Enter the `Rest Server Url`: `https://rest.stomt.com` (Or use our Sandbox for testing - See below)
* Enter the `App Id` you obtained in the second step     
* Enter the `page username (as Target Id)` (you find it in your profile-url. E.g. stomt.com/stomt => stomt)     

<img alt="Configure STOMT Unity plugin" src="http://schukies.io/images/stomt/config.gif" />

Finished! *Regularly communicate your page on social channels and checkout our [Website-Widget](https://www.stomt.com/dev/js-sdk) for your websites to collect feedback from anywhere.*    


## Usage

The Widget can be enabled by using a toggle key or calling the API Methods.

StomtPopup Class
* Enable:	ShowWidget()
* Disable:	HideWidget()


## Use our Sandbox

If you want to test the integration please feel free to do what you want on [test.stomt.com](https://test.stomt.com/) 

Just go through the configuration steps again using the test server:

1. Register on [test.stomt.com](https://test.stomt.com/signup/game).
2. And create an [App Id](https://test.stomt.com/integrate) for your project.
3. Enter "https://test.rest.stomt.com" as `Rest URL` in the widget.


## Common Issues

* Error (401) Unauthorized: Is your application ID right? ```test.stomt.com``` and ```stomt.com``` use different ID's.
* Error (500) Internal Server Error: [Report] (https://www.stomt.com/dev/unity-sdk) us the problem.
* Target Name doesn't fit: you can easily adjust the width. 

<img alt="Adjust target bubble" src="http://schukies.io/images/stomt/targetname.gif" />

* Stomts are not sent out on Android: change the API Compatibility Level from `.NET 2.0 Subset` to `.NET 2.0` in the Player Settings.


## Contribution

We would love to see you contributing to this project. Feel free to fork it and send in your pull requests! Visit the [project on STOMT](https://www.stomt.com/stomt-unity) to support with your ideas, wishes and feedback.


## Authors

[Daniel Schukies](https://github.com/daniel-schukies) | [Follow Daniel Schukies on STOMT](https://www.stomt.com/danielschukies)    
[Patrick Mours](https://github.com/crosire) | [Follow Patrick Mours on STOMT](https://www.stomt.com/crosire)


## More about STOMT

* On the web [www.stomt.com](https://www.stomt.com)
* [STOMT for iOS](http://stomt.co/ios)
* [STOMT for Android](http://stomt.co/android)
* [STOMT for Unreal](http://stomt.co/unreal)
* [STOMT for Websites](http://stomt.co/web)
* [STOMT for Wordpress](http://stomt.co/wordpress)
* [STOMT for Drupal](http://stomt.co/drupal)
