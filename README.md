# ATTENDANCE SYSTEM
An attendance tracking application with facial recognition.

## User Guidelines
### Lecturer
1. Register an account.
2. Create a course.
3. Give the course unique ID to your students.
4. Students need to send the request to enrol, approve the enrolment.
5. You do not need upload student's face photo, which will be done by students.
6. After all student enrolled, select a course and take the attendance.
7. You can see how many face photo of all the enrolled students have uploaded.
8. Ensure that the students upload their face photo, otherwise there is no facial data of that student for reference.
9. Only those enrol in the particular course will be counted into dataset for facial classification.
10. Inside attendance taking form, select the time, date and camera.
11. Wait for all the models being loaded.
12. Set the approriate threshold distance as you wish.
13. Submit the attendance form if finished.
14. Visualize the attendance data in "Attendance History", or you can enter a particular course and click "View Attendance History".
15. You can "Warn" or "Kick" the student out of a course.
16. The face photo of the student who is kicked out will not be counted next time taking the attendance.

### Student
1. Register an account.
2. Enrol a course.
3. Wait for approval from the lecturer.
4. Upload your face photo in "Face Gallery", best to have at least 2 face photo.
5. Wait for all models being loaded.
6. The system will perform face detection, ensuring only a single face exist and rejecting photo with empty face or multiple faces.
7. The photo will be uploaded to the image storage.
8. When your lecturer take the attendance of a particular course, all your uploaded facial data will be counted into the dataset for facial comparison.
9. Visualize the attendance data in "Attendance History", or you can enter a particular course and click "View Attendance History".
