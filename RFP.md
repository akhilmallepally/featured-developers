# Featured-Developers
## Project Charter:
This is the project charter for Featured Developer. This application will be developed as a web application. 
## Project Purpose:
Its a web application comprise of 28 students enrolled for Graduate Direct project under Dr.Danis case, it Determines a level of student attainments, their goals, cheers and wishes from their colleagues and instructors, this invigorate a student to achieve heights.As well as, it helps students to know acheivements of other students enrolled in their class and also get familiar with each other.This engross users to accustom.
## Team Members:
 [Amulya Baddam](https://github.com/amulyareddybaddam)</br>
 [Kushal Satya Durgaji Katari](https://github.com/kushalkatari)</br>
 [Sai vivek reddy Tadipathri](https://github.com/vivektadiparthi)</br>
 [Akhil Kumar Reddy Mallepally](https://github.com/akhilmallepally/)</br>
## Project Architecture:

### Database design:
#### Entities & Attributes:
 USERS</br>
 &nbsp; UserId        ->    Primary Key</br>
 &nbsp; UserName</br>
 &nbsp; Password</br>
 &nbsp; CreatedOn</br>

STUDENT</br>
  &nbsp; StudentId     ->    Primary Key</br>
  &nbsp; FirstName</br>
  &nbsp; LastName</br>
  &nbsp; image</br>
  &nbsp; Date</br>
  &nbsp; Attainment</br>
  &nbsp; PhoneNumber</br>
#### Entity-Relationship diagram:

## Functional Requirements

### Authentication page:
The authenication is only for admin, who has control over the data in the app. The authentication page must contain the following:

1. <b>*username*, *password*</b> fields
2. A <b>*Captcha*</b> field to verify it's a real person and not a bot.
3. A <b>*submit*</b> button to validate the credentials provided by the admin.
4. If the details entered are <b>correct</b>, the page is redirected to <b>admin panel</b>.
5. If the details entered are <b>incorrect</b>, an error message is displayed stating <b>"Invalid credentials. Please contact the administrator"</b>

Roles to access the app : 
1. User
2. Admin

* User will be able to navigate through the pages and have access to all the displayed content.

* Admin will have access to create, update and delete the data along with the user privileges.
### Technology Stack:
<br>Frontend : React.Js , Bootstrap</br>
<br>Backend: NodeJS</br>
<br>Database : MySQL</br>

### Screen Flow:
<br>Home Screen: Consists of a header with login button, a footer and a box that displays picture of the student, all the attributes and a button that directs to the person details screen.</br>
<br>Header menu screen: This screen consists a list off all the students displaying their name and picture.</br>
<br>Login page: This a admin login page, from where admin gets access to add, remove or update the data.</br>
<br>Person details screen: This screen displays all the details of the student.</br>
### Themes & Colors: 
Application carries a theme of white for the background and teal for headers, footers, buttons and menues.
### Device Support:
It is a Progressive Web Application that runs on browser as well as, native on Android and iOS.
### Development Details:
Team:
The development team for this project should comprise of a UI designer , Full Stack Engineer , Quality Analyst , Team Lead
### Font size: 
Font preference  is between 12 -14.
## Bidder Qualifications
<br>Have the best optimized solution for the project.</br>
<br>Implement functionality wiyhin time agreed at the contract.</br>
<br>Must be able to communicate in person & remote, based on situation.</br>
<br>Development team having a proven record in building web application is a plus.</br>

### Terms and Conditions:
The entire project should be open-source and licensed under the <b>GNU General License v3.0</b>


