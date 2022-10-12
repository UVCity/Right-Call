## Functional Requirements
- FR1: The user should select which right call lesson they want to take. -- HIGH -- BR1
- FR2: The application should display a video/series of videos for the course the user is taking. -- HIGH -- BR1
- FR3: The video should have question-related actions assigned to each timestamp in the video. -- HIGH -- BR1
- FR4: The system should have eye-tracking actions assigned to each timestamp. -- MEDIUM -- BR2
- FR5: The user shall use their webcam during the lesson to know if they are looking in the right place during
  each call. -- MEDIUM -- BR2
- FR6: The video must stop and ask the user what they think the call is at each timestamped call. -- HIGH -- BR1
- FR7: User shall select their answer to each timestamped call throughout the video/lesson.  -- HIGH -- BR1
- FR8: Admin should be able to upload, change, retrieve, and delete videos from the database. -- HIGH -- BR1
- FR9: Admin should be able to upload, change, retrieve, and delete timestamp information from the database. -- HIGH -- BR1
- FR10: User shall receive feedback based on the result of the timestamp action, which includes if their answer was correct and what spot of the screen they should have been looking at if incorrect. -- MEDIUM -- BR1
- FR11: User should see on the screen where they were meant to be looking if the system detects no webcam was used. -- LOW -- BR2
- FR12: User shall see their overall results based on all of their answers to each call at the end of the lesson/video, which should consist of total questions, percentage, which questions were correct/incorrect. -- MEDIUM -- BR2
- FR13: User shall have the option to retake a lesson if they did not pass or get all the calls correct. -- LOW -- BR1

## Non-functional Requirements
- NR1: The system shall still work and display feedback if the user cannot use their webcam. -- MEDIUM -- BR2
- NR2: The user should not be able to go back and redo a question at a timestamp if they were incorrect during their current video session, which means they must complete the whole video before reattempting the lesson. -- Medium -- BR2