# Club-Management-System
A desktop application (Java Swing + MySQL) for managing college/university clubs — clubs, students, staff, events, subscriptions, and student-club enrollments. Includes role-based login (Admin/Staff), club statistics, and PDF event notices emailed to students.

Tech Stack
Language: Java (Swing for the desktop UI)
Database: MySQL (via JDBC, DriverManager)
PDF generation: OpenPDF (com.lowagie.text, an iText fork) for event notices
Email: Brevo (formerly Sendinblue) transactional email API, called via java.net.http.HttpClient
Architecture: Simple layered structure — Model / DAO (Data Access Object) / Form (Swing UI)
