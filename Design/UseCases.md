## Actors
- Business Administrator (Admin)
- Trainee
## Use Cases

- UC1: The website can display a video file.
    - We need this use case so that the admin can produce lesson material for the trainee to observe & interact with.
    - The actor at play is the "admin" 
    - The admin will have a the ability to upload video files onto their website.
    - BR1

- UC2: A video stops at a timestamp.
    - We need this use case to initiate questions created by the admin.
    - The actor at play is the "admin" 
    - The admin will have a the ability to add interactions to the video on their website.
    - BR2

- UC3: A pop-up appears with a question asking about the call in the video at each timestamp.
    - We need this use case as a interactable function of the application. 
    - The actor at play is the "trainee" 
    - The trainee will have a the ability to interact with the video at a specific time.
    - BR1

- UC4: The trainee picks their call/answer.
    - We need this use case for the lesson engaging functionality of the application. 
    - The actor at play is the "trainee" 
    - The trainee will have a opportunity to engage with the lessons that the admin has provided along with the training videos.
    - BR2

- UC5: The trainee receives feedback on their answer.
    - This use case is important because the point of stopping and asking questions at each timestamp is to give the 
      trainee the opportunity to learn about the right call. The trainee should receive a congratulating message when correct, and an message that explains the call and the reasoning for it when incorrect. This gives trainees the ability to learn more about the right call in that situation and to further their knowledge of officiating.
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

- UC7: The Info on the webcam and time stamp will determind if the trainee was looking in the correct location.
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
