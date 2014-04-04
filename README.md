Getting started:

# Android

* cordova add android
* cordova plugin add ../cordova-plugin-video-thumbnailer


## Usage

If using the Cordova CLI (or plugman) to install the plugin, there will be a javascript variable available for you to use called 'thumbnailer'. You will usually call a create method with a file:// path to a video or image.

Thumbnail from an image:

`thumbnailer.createImageThumbnail(path, callback);`

Thumbnail from a video:

`thumbnailer.createVideoThumbnail(path, callback);`