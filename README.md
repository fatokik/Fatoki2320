# Fatoki2320

repository for GitHub assignment 1 from CS 4320

Logan Alcaraz, Kenny Fatoki, Thadeus Menesus, Akhil Mulakala CS 4320 Exercise 3.1

Need: A method for easily submitting and collecting programming assignments.
Purpose: To create a system which allows students in programming classes to submit programming work. Additionally, the TAs must be able to collect assignments. Finally, the instructors need to be capable of managing the course, its sections, TAs, and assignments.
Client Base: CS Department – faculty, staff, and students

Users of the software system: CS students, CS course instructors, CS course TAs

Student user requirements:
Log in and out of portal
Relevant data: username, password
Description: student should be able to log in and out of course portal for their course section
View course page and modules
Relevant data: assignment, assignmentInfo, grade, totalGrade, announcement, taInfo, instructorInfo
Description: student should be able to view course modules for their section, including any programming assignment information, assignment grades, instructor/TA announcements, instructor/TA information, and overall course grade
View assignments page
Relevant data: assignment, assignmentInfo
Description: student should be able to view assignments page for their course section
Upload files
Relevant data: file, assignment
Description: student should be able to upload program files to submit for a programming assignment
Submit programming assignments
Relevant data: assignment, submission, studentInfo
Description: student should be able to submit their programming assignments to be graded by the instructor and/or TAs
View assignment submission:
Relevant data: assignment, submission, grade, studentInfo
Description: student should be able to view their programming assignment submissions as well as their grade for the assignment
Resubmit assignments
Relevant data: assignment, submission, grade, studentInfo
Description: student should be able to resubmit their programming assignments as many times as they want before the deadline

Instructor user requirements:
Log in and out of portal
Relevant data: username, password
Description: instructor should be able to log in and out of course portal for all sections of their course
Edit course page; add and remove programming assignments
Relevant data: assignment, assignmentInfo, grade, totalGrade, announcement, studentInfo, taInfo, instructorInfo, courseSection
Description: instructor should be able to edit the course page and its modules for any section, including editing assignment information, student/instructor/TA information, announcements, and student grades
Add and remove students from course
Relevant data: studentInfo, courseSection
Description: instructor should be able to enroll and unenroll students from their course roster for a section
Make announcements
Relevant data: announcement, courseSection
Description: instructor should be able to make course announcements for their students/TAs to view
Upload files
Relevant data: file
Description: instructor should be able to upload any files needed for their course, like program files, files in assignments, announcements, modules, etc.
View and grade student assignment submissions
Relevant data: assignment, submission, grade, studentInfo
Description: instructor should be able to view student submissions for programming assignments and grade them
Edit student grades
Relevant data: assignment, grade, totalGrade, studentInfo
Description: instructor should be able to edit student assignment grades and overall grade
Add and remove TAs from course
taInfo, courseSection
Description: instructor should be able to enroll and unenroll TAs from their course roster for a section

TA user requirements:
Log in and out of portal
Relevant data: username, password
Description:
View course page and modules
Relevant data: assignment, assignmentInfo, grade, totalGrade, announcement, studentInfo, taInfo, instructorInfo
Description: TA should be able to view course modules for their section, including any programming assignment information, assignment grades, instructor/TA announcements, student/instructor/TA information, and overall course grade
Make announcements
Relevant data: announcement, courseSection
Description: TA should be able to make course announcements for their students/TAs to view
Upload files
Relevant data: file
Description: TA should be able to upload any files needed for their course, like program files, files in assignments, announcements, modules, etc.
View and grade student assignment submissions
Relevant data: assignment, submission, grade, studentInfo
Description: TA should be able to view student submissions for programming assignments and grade them
Edit student assignment grades
Relevant data: assignment, grade, studentInfo
Description: TA should be able to edit student programming assignment grades

Constraints (non-functional) on the activity or the resultant state of the system:
Security
Not allow students or TAs have the same power as the teacher unless they are approved by the teacher
Will prevent student from changing their own grade
Speed
Website has to be relatively fast in order for it to be of use
Can’t be a long delay when it comes to submitting or viewing assignments
Account Creation
Needs to have account creation for everybody and give them the correct security access in order to view the right pages
Compatibility
Allow users to be able to access the websites from multiple operating systems. This allows more people to be able to use the software
Portability
Allow the software to run about the same no matter if its run on a laptop or a phone.

System constraints and requirements (i.e. hardware and necessary components):
Equipment or Device used to view Software
If user has a device that is out of date then it might cause some elements of the page to not be accessible
If the user has a faulty keyboard or mouse then some elements of the page might also not be accessible
People or Users
Users may have problems using technology and that might cause them to not know how to use the web page
Internet Access
Users may not have access to stable internet which might in turn cause the webpage to run slower than initially expected
