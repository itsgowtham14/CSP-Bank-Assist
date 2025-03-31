# CSP-Bank-Assist
CSP BankAssist is a web-based app for CSP branches, enabling operators to handle balance inquiries, deposits, withdrawals, fast cash, and PIN changes efficiently. It reduces customer visits to main bank branches by providing quick, secure, and accessible banking services at local CSP centers.

## Objectives
- To streamline small-scale banking operations at CSP centers.
- To provide a user-friendly interface for CSP operators to handle transactions.
- To reduce the need for customers to visit main bank branches for basic services.
- To enhance security and efficiency in CSP banking transactions.

## Key Features
1. **User Authentication**  
   - Secure login system for CSP operators.  
   - Session management for active users.

2. **Balance Inquiry**  
   - Allows operators to check customer account balances instantly.  

3. **Deposits & Withdrawals**  
   - CSP operators can facilitate deposit and withdrawal transactions.  

4. **Fast Cash Transactions**  
   - Quick withdrawal of predefined cash amounts for faster service.  

5. **PIN Change**  
   - Allows customers to securely update their ATM PINs via CSP operators.  

6. **Transaction Logging**  
   - Records all transactions for audit and security purposes.  

## Technologies Used
- **Frontend:** HTML, CSS  
- **Backend:** Java (Servlets, JSP)  
- **Database:** MySQL / Supabase  
- **Server:** Apache Tomcat  

## Project Structure
- **`src/main/java/com/csp/`** → Contains Java Servlet files for handling business logic.  
- **`src/main/webapp/`** → Frontend files (HTML, CSS, JSP) for user interaction.  
- **`WEB-INF/`** → Web application configuration files.  
- **`database/`** → SQL scripts for database setup and management.  

## Deployment Guide
### **Prerequisites**
- Java Development Kit (JDK)  
- Apache Tomcat Server (Version 9.0 or above)  
- MySQL Database or Supabase  
- Eclipse/IntelliJ (for development)  

### **Setup Steps**
1. **Clone the Repository**  

2. **Configure Database**  
- Import the SQL script (`database/schema.sql`) into MySQL.  
- Update `db-config.properties` with database credentials.  

3. **Deploy on Tomcat**  
- Copy the project folder to `C:\Program Files\Apache Software Foundation\Tomcat 9.0\webapps\CSP_BankAssist`.  
- Start Tomcat Server and navigate to `http://localhost:8080/CSP_BankAssist/`.  

4. **Login and Use**  
- Use test credentials to log in and start using the application.  

## Future Enhancements
- **Mobile-friendly design** for better usability.  
- **Transaction reports** for CSP operators.  
- **Integration with bank APIs** for real-time updates.  
- **Multi-factor authentication** for enhanced security.  

## Author
**231FA04094**, **231FA04097**, **231FA04222**, **231FA04408**
B.Tech CSE, VFSTR University  
