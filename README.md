This is a starter template for [Ionic](http://ionicframework.com/docs/) projects.

## How to use this template

*This template does not work on its own*. The shared files for each starter are found in the [ionic2-app-base repo](https://github.com/ionic-team/ionic2-app-base).

To use this template, either create a new ionic project using the ionic node.js utility, or copy the files from this repository into the [Starter App Base](https://github.com/ionic-team/ionic2-app-base).

### With the Ionic CLI:

Take the name after `ionic2-starter-`, and that is the name of the template to be used when using the `ionic start` command below:

```bash
$ sudo npm install -g ionic cordova
$ ionic start myTabs tabs
```

Then, to run it, cd into `myTabs` and run:

```bash
$ ionic cordova platform add ios
$ ionic cordova run ios
```

Substitute ios for android if not on a Mac.


ionic cordova plugin add cordova-plugin-image-picker

ionic cordova plugin add https://github.com/Telerik-Verified-Plugins/ImagePicker.git

ionic generate page gallery

add page into app.module.ts


ionic link //choose PicPrint

ionic upload

question
how to grant permission for this plugin?
for example take photo, read photo from hand ware
do i need add ios and android both platform together for same project
if i want to publish to both platform
or should i add two platform seperately then publish them seperately?

Error: /home/yw/ionic2/PicPrint/src/pages/gallery/gallery.ts has a @IonicPage decorator, but it does not have a corresponding "NgModule" at /home/yw/ionic2/PicPrint/src/pages/gallery
/gallery.module.ts

Testing on Android is much easier and faster. To test on the device, simply plug it in, and run

$ ionic cordova run android

Simulator testing

You can also test right in the simulator using the cordova commands from the previous chapter. For example, to test in the iOS simulator, run:

$ ionic cordova build ios
$ ionic cordova emulate ios

