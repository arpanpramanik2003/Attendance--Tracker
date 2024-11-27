# Attendance Tracker
![Attendance--Tracker].(image_attendance_tracker.jpg)

The **Attendance Tracker** is a Python-based GUI application designed to simplify the management of student attendance. Built using the Tkinter library, this program provides a user-friendly interface for teachers or administrators to efficiently register students, mark their daily attendance, and maintain records in a CSV file.

## Key Features

- **User Authentication**: The application starts with a secure login system, ensuring that only authorized users can access sensitive attendance data.
  
- **Student Registration**: Easily register new students by entering their names and unique IDs (UID). The system checks for duplicate UIDs to maintain a unique student record, preventing inconsistencies.

- **Daily Attendance Tracking**: Mark attendance for registered students on a daily basis, with attendance recorded alongside the current date for straightforward tracking.

- **Dynamic Date Handling**: Automatically creates a new column for the current date in the CSV file each time attendance is marked, simplifying attendance history tracking.

- **Presence Indication**: Attendance status is indicated by 'P' for present and 'A' for absent, ensuring clarity in records.

- **Student Removal**: Includes functionality to remove students from the attendance list when necessary, maintaining an updated roster.

## Requirements

- Python 3.x
- Tkinter (included with most Python installations)
- Pandas (install via pip with `pip install pandas`)
