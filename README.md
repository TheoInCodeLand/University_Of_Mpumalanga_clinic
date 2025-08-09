# University_Of_Mpumalanga_clinic

Functional Requirements (What the system must do)
•	User Authentication and Authorization:
o	The system must allow users to log in with a unique identifier (e.g., student number or employee ID) and a password.
o	The system must differentiate between roles: Student, Admin Clerk, and Nurse/Doctor.
o	The system must restrict access to certain pages and features based on the user's role. For example, a student cannot view the administrative dashboard.
•	Appointment Management:
o	The system must display available appointment slots based on the nurse/doctor's schedule.
o	The system must allow students to book an available appointment slot.
o	The system must prevent double-booking of a single time slot.
o	The system must allow students to cancel or reschedule their own appointments.
o	The system must automatically update the appointment schedule when a booking, cancellation, or rescheduling occurs.
•	Data Management:
o	The system must securely store patient data in the SQLite database, including student details, appointment history, and visit notes.
o	The system must allow authorized users (Admin and Nurse/Doctor) to retrieve and update patient information.
o	The system must generate and display an overview of appointments for a specific day or week.
•	Communication:
o	The system should send automated email or SMS notifications to students to confirm appointments and provide reminders.
o	The system should have a way for staff to post public announcements (e.g., clinic closures, flu shot availability) that appear on the student-facing dashboard.
•	User Interface:
o	The website must have a responsive design, working well on desktops, tablets, and mobile phones.
o	The user interface must be intuitive and easy to navigate for all user types.
o	The EJS templates should be used to dynamically render content based on data from the SQLite database.
________________________________________
User Requirements
Student (User)
•	Log In: I want to securely log in using my student number and a password.
•	Book an Appointment: I want to see a list of available dates and times and book an appointment with a clear reason for my visit.
•	View My Appointments: I want to see a list of my upcoming and past appointments.
•	Cancel/Reschedule: I want to easily cancel or reschedule an upcoming appointment if my plans change.
•	Access Information: I want to be able to find answers to frequently asked questions about the clinic's services and find emergency contact numbers.
•	Receive Notifications: I want to get an email or SMS notification confirming my appointment and reminding me of it the day before.
•	View Announcements: I want to see important announcements from the clinic on the main page.
Admin Clerk (User)
•	Log In: I need to securely log in to access the administrative dashboard.
•	Manage Appointments: I need to view all scheduled appointments for the day/week and have the ability to manually book, cancel, or edit appointments for students.
•	Search for Students: I need a search function to quickly find a student's profile by their name or student number.
•	View Student Details: I need to view a student's basic contact information and their appointment history.
•	Manage Staff Schedules: I need to be able to set and adjust the clinic's working hours and block off time for the nurse/doctor.
•	Post Announcements: I need a simple interface to create and publish announcements for the student-facing website.
Nurse/Doctor (User)
•	Log In: I need to securely log in to access my daily schedule and patient records.
•	View My Schedule: I need to see a clear list of all my appointments for the day, including the student's name and reason for the visit.
•	View Patient History: When a student comes in for their appointment, I need to be able to access their past visit notes and history from the system.
•	Add Visit Notes: I need a way to securely and confidentially add my notes and observations for each patient visit.
•	Update Patient Information: I should have the ability to update a patient's health record with relevant information.
•	Appointment Status: I want to be able to mark an appointment as "Completed" or "No Show" to keep records accurate.

