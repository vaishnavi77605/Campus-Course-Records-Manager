# Campus Course & Records Manager (CCRM)

A **console-based Java SE application** designed to manage **students, courses, enrollments, grades, transcripts, and file utilities**.  
The project highlights **OOP concepts, Java Streams, NIO.2, Date/Time API, exception handling, enums, recursion, and design patterns (Singleton & Builder)**.

---

## 🚀 Features

### 1. Student Management
- Add, view, update, or deactivate student records
- Generate detailed student profiles and transcripts

### 2. Course Management
- Create, list, update, or deactivate courses
- Filter/search courses by instructor, department, or semester using **Streams API**

### 3. Enrollment & Grading
- Enroll or remove students from courses
- Enforce rules like maximum credits per semester
- Record marks, compute GPA, and generate transcripts
- Uses enums for `Semester` and `Grade`
- Polymorphic `toString()` methods for transcript display

### 4. File Operations (NIO.2)
- Import and export CSV-style data for students and courses
- Backup exported files into **timestamped directories**
- Recursive utility to calculate backup folder size or perform operations

### 5. CLI Workflow
- Menu-driven console interface
- Options for Students, Courses, Enrollments, Grades, Reports, Import/Export, Backup, and Exit

---

## 🛠️ Tech Stack
- **Java SE 24**
- **Apache Maven 3.9+**
- Utilizes Streams, NIO.2, Date/Time API, OOP principles, and design patterns

### Prerequisites
- Java 24+ installed
- Apache Maven 3.9+



