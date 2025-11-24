PROJECT TITLE

University Online Portal Simulation using Java Multithreading


OVERVIEW OF THE PROJECT

This project simulates a basic University Online Portal where multiple academic operations run simultaneously using Java multithreading.
The system models real portal behavior by executing login, attendance viewing, fee payment, marks upload, and notifications concurrently.
The project demonstrates how threads can be used to improve performance, handle parallel tasks, and create a responsive environment—similar to live university ERP systems.




FEATURES

Concurrent Login Handling
Simulates verifying user credentials using a dedicated thread.

Attendance Viewing
Loads attendance records parallel to other tasks.

Fee Payment Processing
Simulates online fee payment workflow using thread delays.

Marks Upload Module
Represents faculty uploading marks while other operations continue.

Live Notifications
Sends notifications in real-time through a separate thread.

Non-blocking Operations
All tasks run independently using multithreading.

Console-based Output
Easy visualization of thread execution order.





TECHNOLOGIES / TOOLS USED

Programming Language: Java

Concepts: Multithreading, Thread class, Sleep method

Execution Environment:

IntelliJ IDEA / VS Code / Eclipse / Java Compiler (javac)


Operating System: Windows / macOS / Linux / Android (Termux)





STEPS TO INSTALL & RUN THE PROJECT

1. Install Java

If not installed:

Windows → Install JDK from Oracle

Android → Use Termux + pkg install openjdk


 2. Download the Project

Option A: Clone repository

git clone https://github.com/yourusername/University-Portal-Multithreading-Java.git

Option B: Direct download

Go to the repository

Click Code → Download ZIP

Extract the ZIP


3. Navigate to Project Folder

Open terminal/command prompt:

cd University-Portal-Multithreading-Java

4. Compile the Java Program

javac UniversityPortal.java

5. Run the Program

java UniversityPortal




INSTRUCTIONS FOR TESTING

1. Run the program in terminal/IDE.


2. Observe the output:

Login

Attendance

Fee Payment

Marks Upload

Notifications



3. You will see all operations executing concurrently, proving successful thread execution.


4. Re-run multiple times — output order will change based on JVM scheduling.


5. Modify Thread.sleep() timings to test different concurrency effects.

