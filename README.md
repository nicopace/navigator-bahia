This repo contains a technology demo for an OpenTripPlanner hibrid application.

Compiling
---------

The app is ready to be packaged as a Phonegap/Cordova app.
To do this, there are two options:
* using local tools
* using Phonegap Build

### Local build

1. Install cordova-cli: https://github.com/apache/cordova-cli/#install
2. Run the following commands:
```
git clone git@github.com:nicopace/navigator-bahia.git
cd navigator-bahia
cordova create .
cordova platform add android # or the platform of your choice
cordova build android
```

### Using Phonegap Build

1. Compress repo into a zip file
2. upload it to your build.phonegap.com account.
