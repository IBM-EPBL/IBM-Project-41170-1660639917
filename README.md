# IBM-Project-41170-1660639917
A Gesture-based Tool for Sterile Browsing of Radiology Images<br><br>

        In this project we use gestures to browse images obtained during radiology. Gestures refer
to non-verbal form of communication made using hands. A major challenge involved in this 
process is to provide doctors with efficient, intuitive, accurateand safe means of interaction
without affecting the quality of their work.<br><br>

        This model uses the integrated webcam to capture the video frame. The image of the gesture 
captured in the video frame is compared with the Pre-trained model and the gesture is identified. <br>
         If the gesture predicts is:<br><br>
         0 - Images is converted into rectangle.<br>
         1 - Image is resized into (200,200).<br>
         2 - Image is rotated by -45॰.<br>
         3 - Image is blurred.<br>
         4 - Image isresized into (400,400).<br>
         5 - Image is converted into grayscale.<br>

