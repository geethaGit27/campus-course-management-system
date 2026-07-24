# campus-course-management-system
A Full Stack MERN application for managing student registration, course enrollment, authentication, notifications, and real-time communication.


**Project Title**
Campus Course Management System (CCMS)
A web application for managing students, courses, enrollments, announcements, and communication.

**Problem Statement**
Educational institutions often maintain student records, course enrollment, and communication manually or using disconnected systems. This results in inefficient data management, delayed communication, and difficulty tracking student progress.
The proposed Campus Course Management System provides a centralized platform where students can register, log in securely, enroll in courses, view their dashboard, and receive notifications. Administrators can manage courses and student information through an intuitive web interface.

**Features**
Student
•	Register 
•	Login 
•	JWT Authentication 
•	View Dashboard 
•	Edit Profile 
•	Enroll in Courses 
•	Drop Courses 
•	View Enrolled Courses 
•	Receive Notifications 
•	Real-time Chat with Admin 
Admin
•	Login 
•	Manage Students 
•	Manage Courses 
•	View Enrollments 
•	CRUD Operations 
•	Broadcast Notifications 
•	Chat with Students 

Technology Stack
Frontend
•	HTML5 
•	CSS3 
•	JavaScript (ES6) 
•	React.js 
•	React Router 
•	Axios 
•	Context API / Redux Toolkit 

**Backend**
•	Node.js 
•	Express.js 
•	JWT 
•	bcrypt 
•	Express Validator 
•	Socket.io 

**Database**
•	MongoDB Atlas 
•	Mongoose 

**Deployment**
•	Frontend → Vercel / Netlify 
•	Backend → Render 
•	Database → MongoDB Atlas 

**Folder Structure**
CampusCourseManagement/

│
├── frontend/
│   ├── public/
│   ├── src/
│   │
│   ├── components/
│   │      Navbar
│   │      Footer
│   │      StudentCard
│   │      CourseCard
│   │      Notification
│   │
│   ├── pages/
│   │      Home
│   │      Login
│   │      Register
│   │      Dashboard
│   │      Courses
│   │      Profile
│   │      Chat
│   │
│   ├── context/
│   ├── redux/
│   ├── services/
│   ├── hooks/
│   ├── App.js
│   └── index.js
│
├── backend/
│
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── socket/
│   ├── utils/
│   ├── server.js
│   └── package.json
│
└── README.md

**Database Collections**
**Student**
StudentID
Name
Email
Password
Department
Year
Phone
CreatedAt

**Course**
CourseID
CourseName
Faculty
Credits
Description

**Enrollment**
EnrollmentID
StudentID
CourseID
Date
Status

**Notification**
NotificationID
StudentID
Message
Time
ReadStatus

Chat
SenderID
ReceiverID
Message
Timestamp

