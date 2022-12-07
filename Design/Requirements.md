## Functional Requirements
- FR1: The user should select which right call lesson they want to take. - HIGH - BR1
- FR2: The application should display a video for the course the user is taking. - HIGH - BR1
- FR3: The video will have question-related actions assigned to each timestamp in the video. - HIGH - BR1
- FR4: The system should have eye-tracking actions assigned to each timestamp. - MEDIUM - BR2
- FR5: The user should use their webcam during the lesson for eye-tracking actions. - MEDIUM - BR2
- FR6: The video must stop and ask the user what they think the call is at each timestamp call. - HIGH - BR1
- FR7: User shall select their answer to each timestamped call throughout the video/lesson. - HIGH - BR1
- FR8: Admin should be able to upload, alter, and delete videos from the database through the application. - MEDIUM - BR1
- FR9: A instructor should be able make their own version of a lesson. - MEDIUM - BR1
- FR10: User shall receive immediate feedback based on the result of each timestamp action - MEDIUM - BR2
- FR11: User should see on the screen where they were meant to be looking if the system detects no webcam was used. - LOW - 
  BR2
- FR12: User shall see their answer results to each call at the end of the lesson/video. - MEDIUM - BR2
- FR13: User shall have the option to retake a lesson if they did not pass or get all the calls correct. - LOW - BR1
- FR14: User shall have the option to watch the video in a virtual reality environment. - LOW - BR1
- FR15: The student should be able to login and logout out of the application. - MEDIUM - BR1
- FR16: The application will connect to a mongo database through an api. - Medium - BR1
- FR17: The application should store all of the user's results for each lesson under the user's account - Medium - BR2.
- FR18: The admin should be able to login and logout of the application. - Medium - BR1
- FR19: Instructors should be able to login and logout of the application - Medium - BR1
- FR20: Instructor should be able to custom timestamps and questions into the database for a lesson. - Medium- BR1


## Non-functional Requirements
- NR1: The user should not be able to go back and redo a question at a timestamp if they were incorrect during their current video session, which means they must complete the whole video before reattempting the lesson. -- MEDIUM -- BR1