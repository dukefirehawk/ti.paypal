ti.paypal [![Build Status](https://travis-ci.org/appcelerator-modules/ti.paypal.svg)](https://travis-ci.org/appcelerator-modules/ti.paypal)
=======

#Appcelerator Paypal Module#
===================================================

This is a fork of appcelerator-modules/ti.paypal project

#Features Implemented#

##System##
- Changed the module to be compilable on Appcelerator Studio with Titanium 5.4.0.GA 

#TODO#

##Bugs##

##Important##
- Android NDK must be installed and configured in Appcelerator Studio under
Preferences -> Studio -> Platforms -> Android
- To compile, Run -> Location (select android/dist folder as output folder)
- To deploy, Run -> Titanium SDK (must have ti.paypal-android-3.0.0.zip file in the android/dist folder)

#Development Progress#

##[27/08/2016]##
- Changed android/build.xml to use the default folder structure.
- Changed android/build.properties to refer to the correct Titanium and Android SDK
- Changed android/manifest to use Titanium 5.4.0.GA