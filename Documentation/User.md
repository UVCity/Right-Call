# Ref Reps User Manual
This is the documentation that guides a user on how to use the Ref-Reps Right call Application

## Navigation
- Currently the three links: 'Explore', 'The Team', and 'Contact Us' on the navigation bar at the top of the application is for visual purposes only. 
- For when a student is logged in, clicking the RefReps logo at the top left will redirect them back to the lesson selection page where they can take another quiz. 
<img src="Assets/navLinks.png" width="600">

## Register for the Website
<img src="Assets/register_screen.png" width="600">

- If the user does not have an account, the user can go to the Register Page from the Login Page by clicking on the register button at the top right of the page.
- User must enter an email, and create a username and password for the use of the website.
- User can also register as a student, instructor, or admin.
- Student role: can take the quizzes.
- Admin role: allows you to upload and delete videos, and add questions at specific timestamps to each video.
- Instructor role: can create classes and add students to their classes. Can also add/remove videos to each class for their students to take. They also can alter and add their own questions to timestamps for each video added by the admin.
- Once all boxes are filled, the user hits the register button and if successful, it will direct them back to the Login Screen for them to now login.

## Login to The Website
<img src="Assets/login_screen.png" width="600">

- If one is already registered, they can enter their username (or email) and password to login into their account in the text fields provided.
- If the account exists, they will be directed to their respective page based on if they registered as student, instructor, or admin.
- If the account does not exist or the username or password is incorrect, they will remain on the Login Page with a message saying "Invalid Username or Password".

# Upon Logging In
## Admin Logged In

<img src="Assets/admin_per2.png" width="600">

- If an admin logs in, they will have three options to choose from. They could either upload a lesson video, delete the lesson video, or assign questions/activities at specific timestamps to a lesson.
- The admin can click the Admin button at the top of the screen to go back to the main admin page after doing any of the three actions.

## Uploading Videos
<img src="Assets/uploadMultiple.PNG" width="600">

- If the admin selects the Upload Lesson Video link, the admin will be redirected to the upload video page. 
- To upload a video, the user would click on the select video button, and then they would select a video file from their computer.
- Multiple files can be uploaded at the same time.
- For the video input, there are three supported types of videos that can be uploaded: MP4, WebM, and Ogg.
- Once selected, they would then click upload and if it works, it would direct them back to the admin page and a lesson(s) would succesfully be created.
- A message will appear to let the admin know the lesson is still uploading.
- The lesson may take a little bit (around 10 seconds per video in lesson) to upload, so don't click upload again or anything else until redirected back to the admin page. 


## Deleting Videos/Lessons
<img src="Assets/deleteLessonsOrVideos.PNG" width="600">

- Clicking the Delete Lessons button on the Admin page will allow an admin to delete Videos or entire Lessons.
- Clicking the Delete Video in Lesson option will allow the Admin to select which specific video to delete. All Activities and Feedback associated with the video will be deleted from the database, along with the video itself.
- Clicking the Delete Entire Lesson option will delete all videos, Activities, and Feedback from the database associated with the entire Lesson.

## Adding Timestamps/Questions/Feedback to Existing Lessons
<img src="Assets/assignTimestampsAndQuestions.png" width="600">

- If the admin selected the Assign Timestamps and Question to a video link, the admin can see what lessons they have created and like the deletion page, they can click on the lesson they wish to edit.

<img src="Assets/openVideo.png" width="600">

- The User would be taken to a Lesson Creation page where they can add timestamps to the video they uploaded and cannot save/upload the lesson until they attach a question to it.
- User would click the "Timestamp" button to save a timestamp where that timestamp would then appear in a menu above the big button with an additional option to add an activity.
- The user can also update the lesson name at any time by typing in the new name and clicking the Update Name button.
- The user cannot save/upload the timestamp until each timestamp has a filled out question attached to it.

<img src="Assets/questionInfo.png" width="600">

- To view the information of already added questions like the question, answer choices, and the correct answer, you just need to hover over the left icon for any activity.
- When you hover over a question icon, a box will appear and display the specifics for that question.

<img src="Assets/questionTypeOptions.png" width="600">

- The User then clicks on the left icon beside the timestamp to create a new activity, and would be able to insert a question and possible answer choices, including selecting the correct answer, in the text fields provided before saving. 
- The User has the option of creating a multiple choice, short answer, Eye Tracking, or Drag & Drop question.

<img src="Assets/create_lesson.png" width="600">

- The short answer and multiple choice questions are how they sound: if a user chooses the short answer, they just add one answer choice, and if a user chooses the multiple choice, they must add a minimum of two answer choices and max of four.

<img src="Assets/eyeTrackingQuestion.png" width="600">

- For the eye-tracking question, you can write the question, and then choose the quadrant of the screen the student should be looking at. 
- You also have the option to choose between Corner Quadrants and Vertical Quadrants of the screen.
- On the "Assign New Activity" popup, the user must click the save button if they wish to attach the question to the timestamp. Clicking close would not add the question to the timestamp, and the admin would need to add the question again.
- Once finished adding questions and timestamps, the User can click the "Save" button at the bottom left corner of the timestamps and activities list which will upload the timestamps and questions and redirect the user back to the page where they can select lessons to add timestamps to.
- If the user is done editing lessons, they can click the Save button to go back to the main admin page.

<img src="Assets/dragAndDropActivity.PNG" width="600">

- Drag and Drop questions let the user drag the options exactly where they want on top of the video. An image of the video frame from the Activity's timestamp will be displayed, and input options or number options can be dragged on top. 
- Once inputs are dragged onto the picture, they can be typed in to establish their value during the actual quiz. Any option, number or text, can be deleted by clicking the red X. All of the inputs of a certain type can be reset by clicking its respective Reset button. If you have numbers 1-4 dragged onto the picture, and delete one of them, all numbers that are higher than the deleted number will decrement to keep the proper order.

<img src="Assets/newFeedback.PNG" width="600">

- Creating Feedback for quiz questions works very similar to how creating an activity works. Once you Add a Timestamp, you will be able to click on the right button to add the Feedback. Clicking that button will bring up the Feedback modal. 
- An Activity will not be uploaded and saved unless both the question and feedback are filled out.

## Instructor Logged In
<img src="Assets/instructorHomePage.png" width="600">

- When an instructor logs in, they will see five buttons to choose from.

<img src="Assets/createClass.png" width="600">

- When the instructor chooses the Create Classroom Page button, they are directed to the Classroom Creation page.
- The Instructor must enter a class name.
- Then, they can select students from the left column of students to add to their class. 
- Any students they click on will show up in the column to the right of Selected Students. 
- When the instructor is done adding students, they must click the Create Class button to officially create the class. 

<img src="Assets/addVideosToClass.png" width="600">

- After creating a class, they are back on the instructor page, and then the instructor can click the Update Class option. 
- On this page, they can see all of the classes they have created, along with the number of students and lessons in the class.
- The instructor can add/remove students to and from the class, and they can also add/remove lessons to the class. 
- They can only add their own custom lessons to their classes.

<img src="Assets/addStudentsToClass.png" width="600">

- Instructor can select the Add/Remove Students button.
- The instructor sees all available students, and can either click a student from the left section to remove from the class or a student from the right section to add to the class.

<img src="Assets/addLessonsToInstructorClass.png" width="600">

- Instructor can select the Add/Remove Lessons button.
- Here they can see all of their custom lessons they can add to the class.
- Right now there are three lessons in the class, to add one, the instructor can just click a lesson from the right section.
- To remove a lesson from the class, the instructor must select a lesson from the left section.
- All students can only take video quizzes in lessons that are assigned to the classes they are in.

<img src="Assets/createCustomLesson.PNG" width="600">

- An Instructor can create a copy of an Admin template lesson, and customize it to meet their own wants and needs. 
- From the Instructor page, clicking the Create Custom Lesson Pack button will direct them to a page containing the Admin template lessons available. The Instructor can select one of these to copy.

<img src="Assets/customLesson.PNG" width="600">

<img src="Assets/newCustomLesson.PNG" width="600">

<img src="Assets/lessonEditor.PNG" width="600">

- Back on the Intructor page, clicking the Update Your Lessons button will take you to a page that contains all of the Lesson Packs for that specific Instructor account. From here, an Instructor can select the lesson they want to edit, and they will go to the AssignTimestamps page, much the same as an admin.
- From here, they can make any edits or customizations that will be completely their own. No other Instructors will have the edits that are made to that lesson.

<img src="Assets/classResults.png" width="600">

- Back on the Instructor Page, clicking the Student Results button, will send them to a page that shows the instructor all of their classes.

<img src="Assets/lessonResults.png" width="600">

- By clicking on a class, all of the lessons in the class appear.
- To view the class' results for a lesson, the user should click on a lesson.

<img src="Assets/studentResults.png" width="600">

- After selecting a lesson, the instructor sees the students in the class.
- To view the results of each student for the selected lesson, the instructor must select a student and the results will display to the right of the student list. 
- The highest score for each quiz in the lesson taken by the student will display.
- If the quiz contains any non eye-tracking or drag-and-drop questions, then they will have the option to view the time it took for the student to answer each question.

<img src="Assets/studentTimes.png" width="600">

- To view these times, the instructor selects the view buttton.
- This displays the time it took for the student to answer each question.
- Note: Eye-tracking and Drag & Drop questions do not have timers, so they don't have times.

## Student Logged In

## Select Lesson
<img src="Assets/lessonSelection.png" width="600">

- There are a group of lessons available at the homepage to select from.
- A new student may not have any lessons to choose from, because they may not be added to a class by an intructor yet.
- Students can only take lessons that are assigned to the classes they are in. If they are in multiple classes and the classes have the same video assigned, the student only sees that video once. 
- Select a lesson by clicking on a lesson object.

## Completing a Lesson
<img src="Assets/availableQuizzes.png" width="600">

- After selecting a lesson, the user sees the quizzes in the lesson.
- The user can then select a quiz to take.

<img src="Assets/webcamPermission.png" width="600">

- After selecting a quiz, the user is asked if they want to use their camera for eye-tracking questions. 

<img src="Assets/video_start.png" width="600">

- If they select decline, the user is shown a video file.
- To start a lesson the user must play the video by pressing the play button.
- The current time of the video is displayed beneath the video player along with the length of the video.

## Make a Call
<img src="Assets/what_is_the_call.png" width="600">

- During a lesson, there will be a number of questions that appear while the user is watching the video file.
- The user should select what they believe is the right referee call.
- After selecting an answer, the video should automatically resume and play until the next question pops up or the video ends.

<img src="Assets/noWebcamQuestion.png" width="600">

- One type of question that may pop up is this one, where it asks the student a question and the student must select the quadrant of the video screen where they think the answer to the video is/occurred. 

<img src="Assets/calibrationPage.png" width="600">

- If the student selects accept to use their webcam, they are sent to the eye-tracking calibration page.
- This page is only completed once per login session.
- The student must wait around 15-20 seconds for the red dot to show up on their screen. Once it displays, the student must click all five buttons five times each until each one is red. 
- A pop-up then appears telling you to stare at the red button in the middle of the screen for 5 seconds to check the accuracy of the eye-tracking.
- The user closes the pop-up and stares at the red button.
- After 5 seconds, two buttons appear. 
- One to redo the eye-tracking calibration and another to go back to the quiz.
- If the user feels like the red dot wasn't accurate when staring at the middle button, they can choose to redo it.
- If it was accurate, they can select the go back to the quiz button.
- The student is sent back to the video, and they can press play and start the quiz.
- Questions can show up at any timestamps. 

<img src="Assets/hideRedDot.png" width="600">

- At any time in the quiz, the student can toggle the 'Hide Eye-Tracking Red Dot' button at the bottom of the video.
- This hides/displays the red dot on the screen.

<img src="Assets/eye-TrackingQuestion.png" width="600">

- An eye-tracking question may show up, and the student must look at the quadrant of the screen they think the answer is in.
- A modal will display when it's time for an eye-tracking question.
- It will contain the question, and also a warning that this is an eye-tracking question so that the user is ready to look at the video.
- A screen will display after the question to say if the student looked at the right part of the screen.

## Lesson Results
<img src="Assets/endResults.png" width="600">

- At the end of a video, a lesson results pop-up will appear.
- This Lesson results pop-up includes the % of right and wrong calls that a user has made during the lesson.
- The lesson results pop-up includes the title of each question that asked while watching the video, and if they were answered correctly or incorrectly.
- After viewing the results, the user should press the "Back to Lesson Selection Page" button which sends them back to the original page to select another video.

## View Student's Results
<img src="Assets/viewResults.png" width="600">

- The student can click on the View Results button at the top of the screen to view the results to all of the lessons they have taken.
- This results page contains the lesson name, quiz name, the trainee's highest score for the quiz, and the number of attempts the user has taken for the quiz.
- To take another quiz, the student must click the refreps logo image at the top left of the screen, which will take them back to the lesson selection page.