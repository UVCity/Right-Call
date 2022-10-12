# Software Architecture
<img width="853" alt="Architecture" src="https://user-images.githubusercontent.com/70332153/195425521-aa124c79-0b02-464e-9360-7499fd03ed1c.png">

- Note: This architecture follows the layering (spaghetti code) model.

## Presentation Layer
  - This layer serves as the primary layer that the user/customer is able to see and interact with. This layer would include all of the necessary information to navigate
  the website such as viewing tabs, the primary lesson screen, the corresponding videos and questions, and even their own user info and scores for each lesson they complete.
  All input data that the user provides, such as answers for the questions they are provided, will be fed into the other two layers being the service layer and the database layer.
  The Presentation Layer will be the only layer out of the 3 to interact with the other layers directly.

## Service Layer
  - The Service Layer would be the meat and bones of the whole program as many of the calculations will be handled within this layer. The user will not be able to interact with the layer
  but they can affect it based on their interactions with the Presentation Layer. The Service Layer's role is properly send information to the Presentation Layer,
  mainly regarding the specific lesson that the user has selected, along with its corresponding video clips, questions, and correct answers as well handling the score
  calculations here which will then be assigned to each specific lesson as a grade. All opertaions within the Service Layer will be directed by the Database Layer,
  the only layer in which it can directly interact with and affect.
  
 ## Database Layer
  - The Database Layer would be the final and bottom-most layer in the diagram provided. All information about the specifics of each subject, such as the lessons and answers,
  would be provided by the database layer. All user information, lesson information, and account information would all be stored here, ready to displayed to any user
  who access the website and would receive any changes sent by the Service Layer in need be.
