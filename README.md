# DrawOnImage

### class BackgroundView:
- scaling a image (here: photo from the camera roll) in the original ratio if it is too big
- landscape and portrait support

### class OverlayView:
- get touch events
- display the drawn path

### class DrawOnImage:
- 'Container' for all views, including the scrollview   
   
   
   
Please be patient after pressing the save button, because several tasks have to be done (ui2png, png2alpha, paste background and overlay). Closing automatically after processing.
You can't use a black path because it's the png background color. Any suggestions?

<br />
Tested with Pythonista 3.1 for iOS (Python 3.5)<br />
<br />
![Screenshot](https://raw.githubusercontent.com/humberry/DrawOnImage/master/image.png)
