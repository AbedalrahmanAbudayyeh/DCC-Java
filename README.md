# Dental Center Management System  

This project is a Java-based application designed to manage operations in a dental center, including scheduling, staff management, and patient records. It employs key **design patterns** such as Singleton, Strategy, and Proxy to ensure scalability, maintainability, and security.

 Features  
- Doctor and Nurse Management: Handles doctor and nurse details, including specializations and availability.  
- Patient and Appointment Scheduling: Allows patients to book, modify, or cancel appointments.  
- Employee and Receptionist Management: Manages employee roles, tasks, and interactions with patients.  
- Design Patterns:
  - Singleton Pattern: Ensures a single instance of key classes, such as the central scheduling system.  
  - Strategy Pattern: Allows flexible appointment booking and payment strategies.  
  - Proxy Pattern: Provides controlled access to sensitive patient data.  

 Class Structure  
- Doctor: Manages doctor details and availability.  
  *Nurse: Supports doctor and patient care management.  
- Patient: Stores patient information and history.  
- Appointment: Manages booking and appointment details.  
- Receptionist: Handles front-desk operations and scheduling.  
- Employee: Base class for all staff roles.
- Bill: Base class to print the bills.
- Main: Entry point for the application.  

 Usage  
1. Compile the Project:
   ```bash  
   javac *.java  
   ```  
2. Run the Application:* 
   ```bash  
   java Main  
   ```  

 Key Design Patterns in Use  
- Singleton Ensures the core system component are single instances.  
- Strategy: Enables dynamic selection of algorithms for appointment handling.  
- Proxy: Restricts direct access to sensitive patient information for security purposes.   

