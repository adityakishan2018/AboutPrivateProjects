
# Brief description about the private projects on my github account.Please contact me if you want to view the complete code.

# DocBot | ML based Disease Prediction and Hospital Booking WebApp
We are living in an era where everyone is so busy with their work that they don’t have time to go through a periodic health check up in clinics.
As a result, we tend to ignore certain signs that our body is trying to give out which eventually turns out to be a deadly uncurable disease.
Apart from this, in India we have very few web platforms which helps us book appointment at multiple hospitals. Few Hospital like Apollo, Sevenhills hospitals have hospital specific booking system.
As of now we don’t have any web platform in india which offers both disease prediction and appointment booking.
Moreover, consulting a doctor by meeting him/her in person, has become even more difficult in this era of a pandemic. Like all other industries, even the digital health industry must cope up with these as soon as possible. 
 ### Objectives:
 1) Build a reliable Disease prediction Web app (apart from Diabetes also working on predicting Parkinson’s and onset of Tourette’s syndrome)
 2) Build Responsive UI
 3) Build AWS Lex based chatbot (integrated with Messanger) for smooth appointment booking experience.
 4) Build “one stop solution” to all covid related services using Web API

### Tech-Stack
 HTML/CSS, Flask, Python, CoWIN API, AWS Lex, Heroku and various ML libraries for model preparation
 
### Architecture Diagram
![GitHub Logo](Architecture.png)

 
### project demo (https://drive.google.com/file/d/14dP7q3WjSTDsgCJ-0KwNvdZ17U5qG7zw/view?usp=sharing )
### project documentation (  )
### visit the WebApp (http://docbot2021.herokuapp.com/).

# Face Recognition Based Attendance Mailing System
The Face Recognition based Attendance (Slot basis) Mailing System is an automated service built to be used by the schools colleges and universities to solve a lot of problems which was not addressed by the previous Attendance System ( mainly Biometric based).  
In the pre-covid era, when the classes used to be held in physical classrooms, attendance used to be taken using biometric sensors located outside the classroom. Separate 10 minutes were allotted for this purpose only. Since it used to be located outside the classroom, even the absentees who were bunking the class could give biometric. It is not feasible for a faculty to make note of all the absentees when the class strength is high.
There are several colleges and schools which have already started doing physical classroom sessions keeping Covid protocol in consideration. But biometric based attendance system has created a challenge because it will increase the risk of spreading covid as all students of a class will be using same biometric machine.
This mini project is a small endeavour towards solving these issues. 

There are four main problems that we are trying to solve with the help of this project:
### Following are some of the problems in the existing system:
1) Extra lecture time (10 minutes) wasted in registering attendance using a biometric sensorbased system.
2) Absentees being able to give attendance because the sensor is located outside the
classroom.
3) High Risk of spreading Covid if continued with the existing biometric based Attendance
System
4) (future problem) Students trying to give a proxy using friends' photos when they realise
face recognition based technology is being used.

### PROPOSED SOLUTION
Following are solutions to the above-stated problems:
1) With the help of face recognition (camera facing towards the classroom), the detected
faces of the students in the live video feed will be taken and then matched with the faces
of the registered students.
2) The entire video feed will be visible to the faculty along with recognition status.
3) There are three possible recognition statuses that a live face will be tagged with. These
are “Name_of_student”, “Unknown”, “Name_of_student_fake”.
4) Upon successful recognition and liveness detection, their name, registration number, and
time-stamp are recorded in a csv file.
5) When the lecture time is over and the faculty ends the session, he/she is prompted to
enter the password of his/her registered mail.
6) The login credentials of only that faculty will be considered who is allotted for that
particular slot (day and time).
7) As soon as the password is entered, a mail consisting of the attendance report (csv file
consisting of present student details) is sent to his/her mail id.

### Tech-Stack: 
Python, OpenCV, Dlib, Numpy, Smtplib and various other libraries

### Architecture Diagram
![GitHub Logo](architecture_diagram.jpg)

### project demo ( )
### project documentation (  )

# CrypTalk
Web application for customized message encryption(only for a single organisation which requires secure message platform).This is a mini project done for ISS (Information and System Security) course at VIT-AP University.
### project demo ( https://youtu.be/0wdVwwQN6Zs )
### project documentation ( https://github.com/adityakishan2018/AboutPrivateProjects/blob/master/CrypTalk_Project_Report.pdf )
### visit the WebApp (https://cryptalk.000webhostapp.com/).


# Image Steganography using Python
Today steganography is mostly used on computers with digital data, like Image, Audio, Video, Network packets, etc, acting as the carriers. Images are an excellent medium for concealing information because they provide a high degree of redundancy - which means that there are lots of bits that are there to provide accuracy far greater than necessary for the object's use (or display). Steganography techniques exploit these redundant bits to hide the information/payload by altering them in such a way that alterations cannot be detected easily by humans or computers.
### project documentation ( https://github.com/adityakishan2018/AboutPrivateProjects/blob/master/Hiding_and_reveal_algo.pdf )



