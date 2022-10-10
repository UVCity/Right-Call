# Domain Model
<img src="Pictures\ClassDiagram.png " alt="domain diagram" />

## Classes
### - Trainee  
The Trainee is the user that is being tested. The class contains user information. It has basic information like name and id. 

### - Lesson  
A lesson is a class that contains the informaiton needed to teach a trainee. It contains many clips and activities for the user to complete. 
### - TraineeLesson
This is a joint class that connects a Trainee to any specific lesson. It contains data on what trainee has passed any specific lesson.
### - VideoClip  
A VideoClip class contains information needed to stream a video. It contianes the url to the video that is stored in the cloud, along with a list of all the timestamps that it needs to stop at.
### - TimeStamp  
A time stamp stores information about a specific call. It has the start and end time of a call. It also contains the quadrant of the screen that the foul occurs on. jWhen a stime stamp is active it dispays an activity.
### - ScreenQuadrant  
This calss is a way to describe the quandrant of the screen the user is looking at, in order to compare the quandrant that the foul occurs at.
### - Activity  
An activiy can be any problem that the trainee needs to solve. They will usually be the question "What foul happened" but it could also challenge the trainee other ways.
### - Answer  
This class describes the possible answers to an activity. It contains the answer text as well as if it is correct. If all correct answers are selected, the activity is deemed complete.

