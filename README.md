# project
reproduction to https://github.com/ionic-team/ionic/issues/21207

steps to reproduce:

- npm install

- ionic serve

- Click links Page1 and Page2, look at ion-back-button animation. (erros only on iOS animations and with ion-menu-button)

ionic info:

```
Ionic:

   Ionic CLI                     : 6.6.0 (/Users/theo/.nvm/versions/node/v10.15.0/lib/node_modules/@ionic/cli)
   Ionic Framework               : @ionic/angular 5.1.0
   @angular-devkit/build-angular : 0.803.26
   @angular-devkit/schematics    : 8.3.26
   @angular/cli                  : 8.3.26
   @ionic/angular-toolkit        : 2.2.0

Cordova:

   Cordova CLI       : 9.0.0 (cordova-lib@9.0.1)
   Cordova Platforms : android 8.1.0, ios 5.1.1
   Cordova Plugins   : cordova-plugin-ionic-keyboard 2.2.0, cordova-plugin-ionic-webview 4.1.3, (and 6 other plugins)

Utility:

   cordova-res (update available: 0.14.0) : 0.6.0
   native-run (update available: 1.0.0)   : 0.2.8

System:

   Android SDK Tools : 26.1.1 (/Users/theo/Library/Android/sdk)
   ios-deploy        : 1.9.4
   ios-sim           : 8.0.2
   NodeJS            : v10.15.0 (/Users/theo/.nvm/versions/node/v10.15.0/bin/node)
   npm               : 6.4.1
   OS                : macOS Catalina
   Xcode             : Xcode 11.4.1 Build version 11E503a
```
