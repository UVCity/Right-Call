## Actors
- Business Administrator (Admin)
- Trainee
## Use Cases

- UC1: Display an interactive video in the browser.
  - Explanation: This is a use case because this is a use of the system that helps achieve the first business requirement. We need this use case so that the admin can produce lesson material for the trainee to observe & interact with. Within this display, the trainee can view the
    video file that the admin has made available to them. This helps increase the efficiency of lessons being produced for the trainees.
  - Actors: Admin
  - Flow: The admin uploads video files onto their website. The admin visualizes where and when the timestamp pause is initiated. The admin adds interactions to the video. 
  - Business Requirement Connection: BR1
- UC2: Display a question for each call timestamped in the video.
    - Explanation: This is a use case because it describes a use of the system that helps improve the efficiency of lessons being displayed. We need this use case to initiate questions created by the admin. Timestamps will be made obvious that there was a call within the video, due to their being a pause
      and a question/call to continue watching the videos. We need this use case as an interactable function of the application. This interactivty and multiples timestamps in each video definitely contributes towards increasing the efficiency of lessons being displayed.
    - Actors: Admin and Trainee
    - Flow: The admin provides a question/call at each timestamp in the video. The video stops at each timestamp. The trainee watches teh video and sees each question.
    - Business Requirement Connection: BR1
- UC3: Collect the user's answer to each question.
    - Explanation: This is a use case because it allows the system to collect the user's responses, which will in turn, help the system achieve proper feedback. We need this use case for the lesson engaging functionality of the application. Without collecting the user's answers, we would not be able to achieve the second business requirement, which is to improve the accuracy of the feedback. We need this use case to collect the data to help provide improvements in the eventual feedback.
    - Actors: Trainee 
    - Flow: The trainee picks their answer to the call at each timestamp. The user's answer is collected into the system and is stored for later evaluation and feedback.
    - Business Requirement Connection: BR2
- UC4: Collect user's eye-tracking data via webcam for each call.
    - Explanation: This use case is very important to improving the accuracy of the feedback the system will provide. Using eye tracking on certain calls to see what the trainee is looking at will
      allow for more trainee interactivity and an improved learning environment. For this software, it is not only important to allow the user to learn what is the right call, but to also understand how to spot it. In order for the user to see this accurate feedback, this use case must be in place for the system collect the data to formulate this feedback.
    - Actors: Trainee 
    - Flow: User looks at the screen while picking their answer and watching the video. The system uses eye-tracking via webcam to  determine where the user's eyes were looking. The system collects and stores this data.
    - Business Requirement Connection: BR2
- UC5: Display feedback based on eye-tracking data.
    - Explanation: This use case also is very important to achieving the second business requirement. This use case literally describes how the trainee will see this improved, accurate feedback. This use case gives the trainee more accurate feedback based on where they were looking during the
      call which will allow the user to learn how to spot that call in an actual game situation. Without this use case, the trainee would never obtain this improved feedback, and would not know if they were looking at the place on the screen.
    - Actors: Trainee
    - Flow: Trainee sees if they got the call correct or not. If they missed the question, trainee sees whether they were looking at the wrong side of the screen.
    - Business Requirement Connection: BR2
- UC6: Display user's overall results at end of lesson.
    - Explanation: This use case helps achieve the user seeing feedback part of the second business requirement. This use case describes how the user will see their overall results to all the calls. This feature helps achieve better feedback, because it is a new way of the user seeing their results and feedback. Overall, this use case is mainly for the improved feedback part of the system, instead of more accurate feedback, which deals with the eye-tracking part of the system (UC5).
    - Actors: Trainee
    - Flow: The lesson ends. Trainee sees their overall results for all the timestamped calls.
    - Business Requirement Connection: BR2