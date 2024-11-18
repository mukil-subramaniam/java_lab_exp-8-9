Java Lab Exp-8 & Exp-9

This repository contains the source code for Java Lab Experiment 8 and Experiment 9.
Instructions to Clone and Open Both Projects in VS Code
Step 1: Clone the Repository
Copy the repository URL:
https://github.com/mukil-subramaniam/java_lab_exp-8-9.git
Open a terminal in your desired directory and run:
git clone https://github.com/mukil-subramaniam/java_lab_exp-8-9.git
Step 2: Open the Project in VS Code
Launch Visual Studio Code.
Go to File -> Open Folder, and select the cloned repository folder.
Step 3: Install Maven
Download Maven from this link.
Extract the downloaded ZIP file.
Add the Maven bin directory to your system's environment variables:
Go to System Properties -> Environment Variables.
Edit the Path variable and add the path to Maven’s bin directory (e.g., C:\apache-maven-3.x.x\bin).
Verify Maven installation by running the following command in the terminal:
mvn -version
This should display the Maven version if everything is set up correctly.
Step 4: Required Extensions for VS Code
Install the following extensions in VS Code:
Java Extension Pack
Spring Boot Extension Pack
Step 5: Configure Database for Exp-9
Navigate to the Exp9\src\main\resources folder.
Open the application.properties file and ensure the following configuration is set:


spring.datasource.url=jdbc:mysql://localhost:3306/exp9  
spring.datasource.username=root  
spring.datasource.password=admin  
spring.jpa.hibernate.ddl-auto=update  

Important: Change the spring.datasource.username and spring.datasource.password to match your MySQL credentials. Ensure that a database named exp9 is created in your MySQL instance.
Step 6: Run the Project
To start the projects, open the terminal and navigate to each project folder. Run the following command:
mvn spring-boot:run
Step 7: Access the Applications
After running the command, open your browser and access the projects using the following URLs:
Experiment 8: http://localhost:9696/
Experiment 10: http://localhost:8080/
