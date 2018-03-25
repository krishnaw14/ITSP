# ITSP

As part of our summer project at IIT Bombay, we made a human detection autonomour hexacopter.    

For autonomour flight, we used a F550 frame with pixhawk control board. We configured the control board with qgroundcontrol and used GPS for localization of the drone.

For human detection, we had a raspberry pi with a camera module that captured and transmitted images wirelessly to the computer at ground station where we had implemented 2 approaches for detecting humans in the image:

1. The first approach was with using SVM and hogDescriptor, implemented with openCV.
2. Second approach was using SURF module in Matlab. 

All the relevant codes and documentation to be added shortly.
