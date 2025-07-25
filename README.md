## 📊 Employee Tracker – CEN 3024C Final Project </br>

✅ Overview</br>
Employee Tracker is a Java-based Data Management System (DMS) built with Spring Boot, Thymeleaf, and SQLite. It allows users to perform full CRUD operations (Create, Read, Update, Delete) and includes a custom tenure report feature that groups employees by years of service.</br></br>

This project was completed as the final deliverable for CEN 3024C – Data Management Systems 

🚀 Features </br>
✅ Add, edit, delete, and view employees

✅ Tenure report feature: calculates years of service for each employee and groups them by tenure

✅ Input validation and exception handling to prevent crashes

✅ SQLite database integration

✅ User-friendly GUI (via Thymeleaf)

✅ Fully packaged as a runnable JAR

📂 Project Structure
css
Copy
Edit
Assigment_DMS_Phase4/
├── src/</br>
│   └── main/</br>
│       ├── java/</br>
│       │   └── com/addingdatabase/...</br>
│       └── resources/</br>
│           ├── templates/ (Thymeleaf HTML files)</br>
│           └── application.properties</br>
├── target/</br>
│   └── employee-tracker-1.0.0.jar (executable JAR)</br>
├── sample.db (SQLite database with 20+ records)</br>
└── README.md</br>

🛠️ Requirements
Java 17+

Maven 3.6+

SQLite JDBC driver (bundled in the JAR)

📦 How to Build the Project
In the project root folder, run:

mvn clean package -DskipTests
If mvn clean package fails due to tests, use -DskipTests as shown above.

▶️ How to Run the Application
Make sure you are in the project directory and run the following command:

java -jar target/employee-tracker-1.0.0.jar
This will start a web server (by default on http://localhost:8080).

🌐 How to Use the App
Once the app is running:

Home Page – Lists all employees

Add Employee – Click "Add New Employee" to add manually

Edit/Delete – Use links next to each employee

Tenure Report – Navigate to /tenure (or click "Tenure Report") to see grouped tenure data

🗃️  Database
Included: dms.db

Format: SQLite3

Contains 20+ sample employees

Auto-used by the app via application.properties configuration</br>

🧪 Test Rubric Coverage</br>
✅ 1. Menu & GUI for CRUD operations</br>
✅ 2. Loads data from SQLite DB with error handling</br>
✅ 3. Displays all data via GUI</br>
✅ 4. Create data (form input)</br>
✅ 5. Remove records with immediate reflection</br>
✅ 6. Update fields with validation</br>
✅ 7. Custom Feature (Tenure report with mathematical logic)</br>
✅ 8. Proper inline code comments and documentation</br>

📖 Software Development Process (SDLC)</br>
Phase 1: Logic and Input Validation (Manual/CLI)

Phase 2: Software Testing with edge cases and exception handling

Phase 3: Added GUI via Thymeleaf

Phase 4: Connected GUI with database and implemented full CRUD + custom action

🧠 Lessons & Reflection
This project helped reinforce my understanding of:

Full-stack development with Spring Boot

Integrating GUI with backend and database

Writing maintainable code with clear validation and exception handling

Following a complete SDLC process in a real-world project scenario

🧾 Comments & Documentation
Every class and method is documented with purpose-driven comments, as per Canvas rubric.

🔗 GitHub Repository
(https://github.com/SheilaTran-UCF/Data-Management-System-)</br>

📦 Submission Checklist</br>
✅ Exported IntelliJ project</br>
✅ Executable JAR file</br>
✅ Sample SQLite database with 20+ items</br>
✅ GitHub repository</br>
✅ Final video presentation</br>
### How to Build and Run

To build the project and create the executable JAR:


### 1. Clean and build without running tests
mvn clean package -DskipTests

### 2. Run the JAR that was created
java -jar target/employee-tracker-1.0.0.jar





