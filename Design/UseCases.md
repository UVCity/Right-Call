## Actors
- Business Administrator (Admin)
- Trainee
## Use Cases

- UC1: The website can display a video file.
    - We need this use case so that the admin can produce lesson material for the trainee to observe & interact with. Within this display, the trainee can view the
      video file that the admin has made available to them.
    - The actor at play is the admin
    - The admin will have the ability to upload video files onto their website.
    - This connects to BR1
 
- UC2: A video stops at a timestamp.
    - We need this use case to initiate questions created by the admin. Timestamps will be made obvious that there was a call within the video, there is a pause
      and a set of interactions to continue watching the videos.
    - The actor at play is the admin
    - The admin will have the ability to add interactions to the video on their website. The admin can visualize where and when the timestamp pause is initiated.
    - This connects to BR2
 
- UC3: A pop-up appears with a question asking about the call in the video at each timestamp.
    - We need this use case as an interactable function of the application. In order for the trainee to successfully pass the RefReps course, they must observe
    footage from a sport clip and correctly respond to the pop-up that questions the trainee about the call in that clip.
    - The actor at play is the trainee
    - The trainee will have the ability to interact with the video at a specific time. In order to continue with the training to complete RefReps course, they
    must interact with a pop-up.
    - This connects to BR1
 
- UC4: The trainee picks their call/answer.
    - We need this use case for the lesson engaging functionality of the application. Timestamps suggest multiple answers to their questions, therefor the trainee
    has a choice of what call or answer they believe is to be correct.
    - The actor at play is the trainee
    - The trainee will have an opportunity to engage with the lessons that the admin has provided along with the training videos.
    - This connects to BR2
 
- UC5: The trainee receives feedback on their answer.
    - This use case is important because the point of stopping and asking questions at each timestamp is to give the
      trainee the opportunity to learn about the right call. The trainee should receive a congratulatory message when correct, and a message that explains the call and the reasoning for it when incorrect. This gives trainees the ability to learn more about the right call in that situation and to further their knowledge of officiating.
    - The actor at play is the trainee
    - When the trainee reaches a timestamp in the video, is prompted with a question, and answers that question they
     are given proper feedback on whether they made the right call, or if not, what is the right call and why it is the right call.
    - This connects to BR3
 
- UC6: The trainee's webcam will track where the trainee is looking on the screen.
    - This use case is important because using eye tracking on certain calls to see what the trainee is looking at will
      allow for more trainee interactivity and an improved learning environment. For this software, it is not only important to allow the user to learn what is the right call, but to also understand how to spot it.
    - The actor at play is the trainee
    - The admin will assign a timestamp with an eye-tracking activity that will check where the trainee is looking on
      the screen during that time. When that timestamp arrives, the software should check what part of the screen the trainee's eyes are looking at.
    - This connects to BR4
 
- UC7: The Info on the webcam and time stamp will determine if the trainee was looking in the correct location.
    - This use case is important because giving the trainee proper feedback based on where they were looking during the
      call will allow the user to learn how to spot that call in an actual game situation.
    - The actor at play is the trainee
    - The admin will assign an eye-tracking activity to a timestamp, the software will check what part of the screen
      the trainee is looking at, and then proper feedback will be given to the trainee to help better their understanding of the call.
    - This connects to BR4
 
- UC8: The admin can upload a video and place timestamps connected to a question (calls).
    - This use case is important because it is the basis of the system that offers the trainee this learning
      experience. The admin can set up a specific timestamp with the specific activity they want, which will in turn set up the trainee to learn about these calls and how they are spotted.
    - The actor at play is the admin
    - The admin will find a time in the video, and assign a timestamp to it along with the specific activity they want
      to be associated with it. When the user reaches that part of the video, the activity will run and display the proper feedback one it is answered.
    - This connects to BR2