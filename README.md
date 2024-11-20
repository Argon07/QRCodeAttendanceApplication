# **Course Management and Attendance Tracking System**

This is a comprehensive **Course Management and Attendance Tracking System** built as a full-stack web application. It enables seamless interaction for **Admins**, **Instructors**, and **Students**, providing role-based dashboards for efficient course and attendance management. The application has been entirely designed, developed, and implemented by **me**.

---

## **Features and Functionalities**

### **Admin Dashboard**
Admins have complete control over the course management lifecycle, including:
- **Add New Courses**: Add courses with details like title, term, CRN, instructor, capacity, and schedule.
- **Update Existing Courses**: Modify course details dynamically.
- **Bulk Course Upload**: Upload multiple courses using a CSV file.
- **Instructor Assignment**: Assign instructors to courses.
- **Student Enrollment**: Enroll students in courses using a CSV upload or manual selection.

### **Instructor Dashboard**
Instructors can:
- **Track Attendance**: Use a QR-based system to monitor attendance.
- **Generate Reports**: View and download detailed attendance reports for each course.
- **Course Management**: View courses assigned to them and manage associated data.

### **Student Dashboard**
Students can:
- **Track Attendance**: View their attendance records with visually appealing **pie charts**.
- **Course Details**: View a list of enrolled courses with details like time, days, and instructor.
- **Dynamic QR Scanning**: Mark attendance by scanning course-specific QR codes.

---

## **Technologies Used**

This project was developed using:
- **Frontend**: React.js, Axios, and CSS for styling.
- **Backend**: Firebase Realtime Database and Firebase Authentication.
- **CSS Libraries**: Flatpickr for date pickers and custom responsive styles.
- **Charting**: Chart.js for visualizing attendance data.
- **CSV Parsing**: PapaParse for bulk uploads.

---

## **Role-based Functionality**

### **Admin Features**
Admins can control the application entirely:
- Create, update, and manage course and user data.
- Handle bulk actions such as adding multiple courses or enrolling students.

### **Instructor Features**
Instructors focus on their assigned courses:
- Track attendance and visualize data for each class.
- Simplified workflows for classroom attendance management.

### **Student Features**
Students have a streamlined experience:
- View attendance and course details.
- Simple one-click navigation to track attendance using QR codes.

---

## **Developer**
This project was solely developed by **me**, with a strong focus on user-centric design and scalable architecture.

---

## **Future Enhancements**
- **React.js Frontend**: Further improving UI/UX using component-based architecture.
- **Instructor Dashboards Enhancements**: Adding analytics for attendance trends.
- **Admin Reports**: Generate downloadable reports for all courses and users.
