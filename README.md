# VirtualMouse-OpenCV

a Windows-based application which can be used for controlling mouse with hand gestures using web cam input in python. It can be used for mouse events like single click , double click , drag etc. The application detects the hand movements given by user and performs operation accordingly . User can perform multiple tasks with his gestures. No additional hardware will be required except an in- built Webcam or an external Webcam. 


Python Modules used: OpenCV , Numpy, Pynput, WX

The code continuously streams video from the webcam and takes the frames of the video (at a gap of 2 millisecond). Initially the noises which are present in frames collected from web cam are minimized. Then the frame which is collected in RGB format is converted to HSV format (which is basically intended for effective background subtraction) . Hand in frame collected is recognized by using global HSV value range for skin color. By using few functions we have detected hand motion and static gestures made by the user 
