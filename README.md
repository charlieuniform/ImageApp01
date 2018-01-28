# ImageApp01
Static fullscreen HTML image application for a screen. For digital displays with a changing image and or other static elements, like a brochure, map, advertisement, etc.

This is a very rudimentary sample of a web application that can be shown on a digital screen. Great for use with [Charlie Uniform](https://charlieuniform.com).

This app displays an image of your choice that fills the entire screen of your digital display. It optionally can show a static message or even other web components.

## CharlieUniform
[Charlie Uniform](https://charlieuniform.com) is an app for your PC, tablet or cellphone that lets you manage HTML content on unattended digital screens. Virtually any HTML content will work on any combination of hardware and browser. 

It is just a browser in full screen mode with your content. You can change that content from anywhere using Charlie Uniform without touching the screen itself.

For info about CharlieUniform contact charlieuniformco+info@gmail.com.

## Usage
If you create several copies of the app, each with a different image and swap them periodically with [Charlie Uniform](https://charlieuniform.com) your digital screen becomes effective for targeting your audience thruout the day. Upload them independantly to [Charlie Uniform](https://charlieuniform.com) with different names to have each available to show in any of your digital screens.

## To Change the Fullscreen Image
Download the zipfile from github. Extract into you filesystem. THe top level directory of the app should be ImageApp01-master, we will change this later. The top level directory or folder name will be the name of the content app in [Charlie Uniform](https://charlieuniform.com). Open the file ImageApp01-master/css/tapp1.css in any text editor. There will be a line like:
```
background-image: url(../img/okeechobee.png);
```
This basically means the background style of a div that takes up the whole screen is this image file. You can add any image file you want to the ImageApp01-master/img dir and use it here, thus chaging the fullscreen image for the app. NOTE: the shape of the image makes a difference. A landscape oriented image similar to the aspect ration of your screen of whatever size works best. ALso, the style here blurs the image and removes part of the edges. To remove this effect comment out these lines: 
```
filter: blur(5px);
margin: -20px;
```
Like so:
```
/*filter: blur(5px);
margin: -20px;*/
```
Now name the top level folder something to help you know which image you are using. Say you want to display on one of your digital screens in the morning your best breakfast dish, "Waffles Henry". So upload an image of the dish and change the code as above. Now reame the top level directory from "ImageApp01-master" to "WafflesHenry". At this point you can drag and drop the new WafflesHenryf directory to [Charlie Uniform](https://charlieuniform.com) app. It is now a content application for any of your screens managed by [Charlie Uniform](https://charlieuniform.com). In the morning set the WafflesHenry content app to any of the screens that you want to display it on.





