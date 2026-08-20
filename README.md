Create the table:
CREATE TABLE RBU creates a table called RBU to store employee details.
Employee ID:
empld INTEGER PRIMARY KEY creates an employee ID column. Each ID must be unique.
Employee name:
name TEXT NOT NULL stores the employee's name. The name cannot be empty.
Department:
dept TEXT NOT NULL stores the employee's department. It also cannot be empty.
Insert John:
INSERT INTO RBU VALUES (0001, 'John Doe', 'Sales'); adds John Doe with ID 1 to the Sales department.
Insert Khushi:
INSERT INTO RBU VALUES (0002, 'kHUSHI', 'INDUSTRY EXECUTIVE'); adds Khushi with ID 2.
Insert Shardul:
INSERT INTO RBU VALUES (0003, 'sHARDUL', 'EXECUTIVE'); adds Shardul with ID 3.
Search for SMART:
SELECT * FROM RBU WHERE dept = 'SMART'; searches for employees in the SMART department. At this point, there are none.
Insert Aalok:
INSERT INTO RBU VALUES (0004, 'Aalok', 'SMART'); adds Aalok with ID 4 to the SMART department.
Search for SMART again:
The final SELECT searches again and now displays Aalok, because he belongs to the SMART department.
