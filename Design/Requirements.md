## Functional Requirements
- FR1: The user should select which right call lesson they want to take. - HIGH - BR1
- FR2: The application should display a video for the course the user is taking. - HIGH - BR1
- FR3: The video will have question-related actions assigned to each timestamp in the video. - HIGH - BR1
- FR4: The system should have eye-tracking actions assigned to each timestamp. - MEDIUM - BR2
- FR5: The user should use their webcam during the lesson for eye-tracking actions. - MEDIUM - BR2
- FR6: The video must stop and ask the user what they think the call is at each timestamp call. - HIGH - BR1
- FR7: User shall select their answer to each timestamped call throughout the video/lesson. - HIGH - BR1
- FR8: Admin should be able to upload, alter, and delete videos from the database through the application. - MEDIUM - BR1
- FR9: A instructor should be able make their own version of a lesson and save it in the database. - MEDIUM - BR1
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
- FR20: Instructor should be able to add custom timestamps and questions into the database for a lesson. - Medium- BR1
- FR21: An Admin can create a full lesson with many video clips and questions and publish it when ready. - Medium - BR1
- FR22: An instructor should be able to create a class with students in it, and students should be assigned to that instructor. - Medium - BR1
- FR23: An instructor should be able to assign their custom lesson to a class. - Medium - BR1
- FR24: An instructor should be able to see the results of each of their students. - Medium - BR1
- FR25: A student should see any lessons that they have been assigned. - Medium - BR1
- FR26: A student can have the option to either use or don’t use eye-tracking, and a dot will follow where they are looking on the screen. - Medium - BR2
- FR27: The admin and instructor can add different types of questions, including asking what section of the screen the foul occurs in, text input, multiple choice - Medium - BR1
- FR28: The user should be able to calibrate the eye tracker to increase accuracy - Medium - BR2
- FR29: A student can answer all types of questions, and should be able to answer an eye tracking question, without a camera on. - Medium - BR2
- FR30: A student should see their instructors name on each lesson - Medium - BR1
- FR31: An instructor can add/remove lessons and students to and from each of their classes. - Medium - BR1
- FR32: An instructor or admin will be able to create a Drag-n-drop question, where the question will give a word bank and the image of the timestamp, and the student will move the words to the right location on screen. - Low - BR1
- FR33: A student should see increased accuracy and calibration in the eye tracking. - Medium - BR2
- FR34: The students time it takes to answer for each question is stored and checked for a different type of feedback. - Low - BR2
- FR35: An Admin can delete a whole lesson, or a specific video in the lesson. - Medium - BR1
- FR36: The user's eye-tracking question can be split into columns or rows(3rds or 4ths) instead of quadrants.
- FR37: The instructor can add multiple students or lessons to and from a class all at one time, and not individually.
- FR38: The user's best result for each quiz is stored.
- FR39: The instructor can see the time it took for a user to answer a question.
- FR40: The usability of the eye-tracking questions are improved, such as loading states and making sure the user knows its an eye-tracking question before starting the question immediately. 
- FR41: The user has the option to view or hide teh eye-tracking red dot on the screen.
- FR42: When an Instructor is adding timestamps, Icons are used to indicate question types. Question text is also easily viewable.







## Non-functional Requirements
- NR1: The user should not be able to go back and redo a question at a timestamp if they were incorrect during their current video session, which means they must complete the whole video before reattempting the lesson. -- MEDIUM -- BR1