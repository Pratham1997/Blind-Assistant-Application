<b>BLIND ASSISTANT APPLICATION</b>

People with complete blindness or low vision often have a difficult time self-navigating outside well-known environ- ments. Traveling or simply walking down the road may pose great difficulty.
The aim of our project is to create an application in order to help blind people in their day to day lives. We help to make their lives easier by performing some of the task in which they may face difficulties in life.
We try to solve some of these problems via our application. We performs 3 major tasks which are:
1) Detection and tracking of incoming vehicles towards the person and warn him to prevent any accidents.
2) Detect and recognize any text present in an image taken by the person, and read it out to him.
3) Send the current location to friends or relatives in case of emergency via voice command.

Implementation details have been explained in detail in ProjectReport.pdf

<b>Vehicle Detection, Tracking and Warning</b>
1. Go to folder VehicleDetTrak.
2. Install darknet with pretrained yolo weights for image detection in the corresponding darknet folder from the link in references.
3. Save the test video file to this folder.
4. Use the following command to detect and track vehicles in video and give audio warning message.<br>
	python3 Vehicle.py videoname<br>
5. Not integrated to android currently.

<b>Text Detection, Recognition and Speech</b>
1. Go to folder TextDetRec in terminal.
2. Save the test image to this folder.
3. Use the following command to detect and recognize text in image and convert it to speech.<br>
	python3 Text.py imagename<br>
4. Not integrated to android currently.

<b>GPS Tracking and Sharing</b>
This part has been integrated in android application.

References
https://pjreddie.com/darknet/yolo/
