# Database Interaction Program

## Description
The `Module5` program is a Java application designed to interact with a MySQL database, allowing users to create new records and view all existing records in the `contacts` table. The program connects to the database, provides a user-friendly menu for interaction, validates user input, and performs SQL operations to insert and retrieve records.

## Features
- **Database Connection:** Establishes a connection to a MySQL database using JDBC.
- **User Interaction:** Presents a menu with options to create a new record, show all records, or exit the program.
- **Input Validation:** Validates user input for fields such as phone number and email, ensuring data integrity.
- **Record Creation:** Inserts new records into the `contacts` table in the database.
- **Record Retrieval:** Retrieves and displays all records from the `contacts` table.
- **Exception Handling:** Handles SQL and I/O exceptions gracefully.

## How to Run
1. **Compile the Java Program:**
   ```sh
   javac Module5.java
## Database Setup and Connection
Before running the `Module5` program, you will need to set up the MySQL database model included in this repository and configure the database connection in the code.

### 1. **Download and Import the Database Model:**
   - Download the MySQL database model provided in this repository.
   - Import the database model into your MySQL server to create the required database and table.

### 2. **Configure Database Connection:**
   - Open the `Module5.java` file in your preferred IDE or text editor.
   - Locate the following lines of code:
     ```java
     String url = "jdbc:mysql://127.0.0.1:3306/module5";
     String user = "root";
     String password = "your_password";
     ```
   - Replace `"your_password"` with the actual password for your MySQL server.
   - Save the changes.

### 3. **Run the Program:**
   - After setting up the database and configuring the connection, follow the instructions in the [How to Run](#how-to-run) section to compile and run the program.

### Note:
   - Ensure that your MySQL server is running and accessible from your development environment.
   - The program assumes that you are using the default MySQL user `"root"`. If you are using a different user, update the `user` variable accordingly.
