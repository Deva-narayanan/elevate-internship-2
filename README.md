# elevate-internship-2
📘 **Task 2: Data Insertion and Handling Nulls**
================================================

🎯 **Objective:**Practice inserting, updating, deleting data, and handling NULL values in a relational database.

🛠️ **Tools Used:**

*   DB Fiddle
    
*   SQLiteStudio / MySQL Workbench
    

📂 **Deliverables:**

*   SQL file containing INSERT, UPDATE, DELETE statements
    
*   Examples showing how to handle NULL values effectively
    

📄 **Description:**This task helps you gain hands-on experience in manipulating data inside a Library Management System database.

Includes:

✅ **Insert Operations:**

*   Add records into Authors, Books, Members, and IssuedBooks
    
*   Insert NULL where data is incomplete (e.g., missing bio, genre, or email)
    

🔁 **Update Operations:**

*   Update author bio, book genre, member email
    
*   Mark books as returned
    
*   Replace NULL values with default values like "Unknown" or placeholder emails
    

❌ **Delete Operations:**

*   Delete members with no book issues
    
*   Remove books with 0 copies available
    
*   Delete authors without any books
    

❓ **NULL Handling:**

*   Find records with missing values using IS NULL
    
*   Set default values for NULL fields using UPDATE
    

🧪 **Example Scenarios:**

*   List books with missing genre
    
*   Set genre to "Unknown" where it is missing
    
*   Update emails to a default value where not provided
    

🚀 **How to Use:**

1.  Open DB Fiddle or your preferred SQL tool
    
2.  Copy and run the SQL script from the file task2\_data\_operations.sql
    
3.  Observe the changes and tweak values to learn more
    

📁 **File Structure:**

*   task2\_data\_operations.sql – contains all SQL commands
    
*   README.txt – this file
    

🤝 **Contributing:**Feel free to fork the project and submit your improvements via pull requests.

📄 **License:**This project is under the MIT License.

🧱 Part of the Library Management System database project series.
