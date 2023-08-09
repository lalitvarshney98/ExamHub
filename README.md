# ExamHub
Online exam portal using SpringBoot Angular

# Contents
-  About the Website	
-  Admin Profile	
-  Registration Page	
-  Login Page	
-  Welcome Page of Admin-Side	
-  Viewing Your Profile Details	
-  Adding a Subject	
-  Viewing Created Subjects	
-  Deleting a Created Subject	
-  Adding a Quiz
-  Adding Questions to a Quiz	
-  Viewing Created Quizzes	
-  Updating Quiz Information	
-  Viewing the Result for a Quiz as a Professor	
-  Student Profile	
-  View All Quizzes	
-  View Quizzes of a Particular Subject	
-  Starting a Quiz	
-  Viewing the Result for a Quiz	


# About the Website

ExamHub is a online portal that provide examiner a user-friendly platform to host quizzes for all of their courses wise and ensure that these quizzes are attempted by examinee or not. After finish the exam examiner and examinee both check performance result also.

There are 2 types of profile available in ExamHub

- Admin – who manage online exam for examinee
- Examinee - who appear in exam

Users working on the Admin Profile have the following functionalities available to them:

- Create Courses Categories
- Modify Courses Categories
- Delete Courses Categories
- Create Quizzes
- Modify Quizzes
- Delete Quizzes
- Enable Tab Switch Prevention
- Create Questions
- View Performance Results

Users working on the Examinee Profile have the following functionalities available to them:

- Attempt Quizzes
- Review Quizzes
- 
# Software Used

This software was developed using

- Angular – Frontend
- SpringBoot – Backend
- MySQL – Database
  
## Software Optimizations
- Authentication is quick and secure with JWT Authentication
- Use of Single Webpages ensures faster load times


# Demonstration Images of the ExamHub Website

## Admin Profile

## Login with admin credential

![examinee login](https://github.com/lalitvarshney98/ExamHub/assets/70005334/db34791c-6652-4f58-beb9-73d2f83eb296)


### Welcome Page of Admin-Side

![home](https://github.com/lalitvarshney98/ExamHub/assets/70005334/2618fce4-b609-4d7f-9e66-9c05c811d857)

### Viewing Your Profile Details

![prof](https://github.com/lalitvarshney98/ExamHub/assets/70005334/769efdfe-4239-457b-b189-b7fe3b4dabf5)


### Adding Multiple Eaxm Categories
  - Click on the ‘*Add Category*’ button from the menu on the left
  - Click on ‘*Add New Category*’ below the created subjects within the ‘*Category*’ sub-menu
- What you have to enter:
  - Name of the exam category
  - Description of the Exam

![add category](https://github.com/lalitvarshney98/ExamHub/assets/70005334/2253a6f6-24f9-41fb-8170-9472802be3b4)

![added cate](https://github.com/lalitvarshney98/ExamHub/assets/70005334/5ab003af-d872-4a52-a525-1b71789ddf77)


### Adding a Quiz
- Click on the ‘*Add Quiz*’ button from the menu on the left
- What you have to enter:
  - Name of the Quiz
  - Description of the Quiz
  - Maximum Marks for the Quiz
  - Number of Questions to be asked
  - Subject that the quiz is part of
  - ‘Publish Status’ toggle will control whether the student is able to view the quiz on their profile

![add quiz](https://github.com/lalitvarshney98/ExamHub/assets/70005334/f0ff47ee-9c29-46f8-811e-58d762d2f275)

![added quiz success](https://github.com/lalitvarshney98/ExamHub/assets/70005334/3a1279b6-5d32-4412-b812-e801fc7f8568)

![after add cate](https://github.com/lalitvarshney98/ExamHub/assets/70005334/9a493e6d-518b-42b4-aa6f-e298b28a8dba)


### Adding Questions to a Quiz
- Admin login with same login page with own credential
- How to Get Here: Click on the ‘Questions’ button from the row of buttons below the name of a created quiz within the Quizzes Page
- How to Create Your First Question:
  - After clicking on the ‘Questions’ button, click on ‘Add Question’ Button
  - Enter your question in the text field given
    - Questions can be formatted with different font styles, equations, colors, hyperlinks or images with the use of the ribbon of formatting options on the top border of the text filed
  - Enter the four options you would like the student to choose from
  - Select the correct answer from the dropdown list
    - The correct answer must be one of the options
  - Click on ‘*Add*’ button at the bottom of the page
  - You have successfully created a question
  - If you would like to start afresh, you can clear the question and associated option with the ‘*Clear*’ button at the bottom of the page before clicking on the ‘Add’ button
  - Repeat this process to add further questions
- Questions can be updated after adding by clicking on the ‘*Update*’ button within the ‘*Questions*’ *Page*


![add ques in quiz](https://github.com/lalitvarshney98/ExamHub/assets/70005334/27769a14-5bce-4048-8068-9bb32030891a)

![ques add success](https://github.com/lalitvarshney98/ExamHub/assets/70005334/01a33bf7-563b-4c22-a091-f67388a4c1bf)



##

### Viewing Created Quizzes
- Click on the ‘*Quizzes*’ button from the menu on the left

![quiz dashboard](https://github.com/lalitvarshney98/ExamHub/assets/70005334/fdfa9172-244c-4897-abe5-c3f4f40b8279)



### Viewing the Result for a Quiz
- From the “Quizzes” page, click on the “*View Result*” button below the name of the quiz you would like to see the results
- The results will be shown student-wise in a tabular manner




## Examinee Profile

### Registration Page
- Users: All who are not registered with ExamHub
- Users are required to enter a valid:
  - Username
  - Password
  - First Name
  - Last Name
  - Email
  - Phone Number
- All entries are validated and appropriate errors will be given
- Accounts are authenticated using JWT Authentication

  ![reg page](https://github.com/lalitvarshney98/ExamHub/assets/70005334/d9168456-336b-4397-98d1-3efac0f946bb)

  ![reg success](https://github.com/lalitvarshney98/ExamHub/assets/70005334/ea1b3346-aa65-46c9-bbef-0bd58d5258d2)


### Login Page
- Users: All who are registered with ExamHub
- Users are required to enter a valid:
  - Username
  - Password
- All entries are validated and appropriate errors will be given
- Accounts are authenticated using JWT Authentication

  ![examinee login](https://github.com/lalitvarshney98/ExamHub/assets/70005334/5837841b-8d09-4e44-8230-5ac1bfeaac07)


### View All Quizzes
- Click on the ‘*All Quizzes*’ button from the menu on the left

![examinee dashboard](https://github.com/lalitvarshney98/ExamHub/assets/70005334/a11f7a82-6905-4a39-8ebf-7d18919844f4)


### Starting a Quiz
- Click on the “*Start*” button below the quiz name
- Instructions for attempting the quiz will be shown on starting the quiz
- To start answering questions, click on the “*Start Quiz*” button from the instructions page
- A confirmation pop-up will be displayed to start the quiz.
- Click on the “*Start*” button to start. Else, click on the “*No*” button
- It is to be noted that the quiz will Auto Submit when the timer on the right side of the screen reaches 0
- The quiz will auto submit will submit automatically if tab is switched to ensure ethical attempts of the quiz
- On submission, the results of the quiz are shown as a summary

![instruction before start quiz](https://github.com/lalitvarshney98/ExamHub/assets/70005334/4406a97a-2469-48d0-89e2-1adfe07c89b6)


![start quiz with timer](https://github.com/lalitvarshney98/ExamHub/assets/70005334/1cd1fa86-fcea-49f3-8eea-7bff59584a05)

![see quiz ques](https://github.com/lalitvarshney98/ExamHub/assets/70005334/167579d7-1be4-4045-adaa-93c46f2c79c8)


### Viewing the Performance Result for a Quiz
- Users: Students
- How to Get Here: From the “Available Quizzes” page, click on the “*See Results*” button below the name of the quiz you would like to see the results for

![quiz result](https://github.com/lalitvarshney98/ExamHub/assets/70005334/b99242b9-d7a3-4b64-840c-597b21e0c699)


