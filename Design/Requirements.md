## Functional Requirements
- FR1: The user should select which right call lesson they want to take. -- MEDIUM -- BR1
- FR2: The application should display a video/series of videos for the course the user is taking. -- HIGH -- BR1
- FR3: Admin should be able to assign question-related actions to each timestamp in the video. -- HIGH -- BR1
- FR4: Admin should be able to assign eye-tracking actions to a timestamp. -- MEDIUM -- BR2
- FR5: User shall use their webcam during the eye-tracking activity to know if they are looking in the right place during
  the call. -- MEDIUM -- BR2
- FR6: The application should retrieve the course videos from a database. -- HIGH -- BR1
- FR7: The application should retrieve the timestamp information from a database. -- HIGH -- BR1
- FR8: Admin shall upload videos to the database. -- HIGH -- BR1
- FR9: Admin should be able to change and delete videos from the database. -- HIGH -- BR1
- FR10: Admin should be able to upload timestamp information to the database. -- HIGH -- BR1
- FR11: Admin should be able to change and delete timestamp information from the database. -- HIGH -- BR1
- FR12: User shall receive feedback based on the result of the timestamp action. -- Medium -- BR1
- FR13: User should see on the screen where they were meant to be looking if the system detects no webcam was used. -- Low -- BR2
- FR14: User shall see their overall results based on all of their answers to each call at the end of the lesson/video, which should consist of total questions, percentage, which questions were correct/incorrect. -- Medium -- BR2
- FR15: User shall have the option to retake a lesson if they did not pass or get all the calls correct. -- Low -- BR1

## Non-functional Requirements
- NR1: The system shall still work and display feedback if the user cannot use their webcam. -- Medium -- BR2
- NR2: The user should not be able to go back and redo a question at a timestamp if they were incorrect during their current video session, which means they must complete the whole video before reattempting the lesson. -- High -- BR2