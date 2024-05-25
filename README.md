This code creates a schema and tables for a fitness management system named Mindful_Body_Fitness.

The code defines eight tables. Each table has specific columns to store information relevant to the fitness management system. Here's a summary of each table:
Customer: Stores customer information like customer number, name, address, program details (linked to the program table), coach information (linked to the Coach table), and payment ID (linked to the payment table).
Payment: Stores payment details like payment ID (linked to the Customer table), customer number (foreign key referencing Customer table), payment date, transaction mode, and transaction ID.
Coach: Stores coach information like coach ID, name, date of birth, address, contact number, and username (linked to the User_name table).
User_name (should be User_name): Stores user credentials for coaches, containing coach ID (foreign key referencing Coach table), username, and password.
Program: Stores program details like program number, title, start and finish dates, and price.
Program_coach: This table likely links programs to coaches and exercise IDs. It contains program number (foreign key referencing program table), coach ID (foreign key referencing Coach table), and exercise ID (purpose unclear without additional information).
Exercise_Log: Stores exercise log information like exercise ID, date, category (e.g., Cardio, Strength Training), subcategory (e.g., Running, Push-ups), time spent, and calories burned.

This code sets up a database schema and tables to manage customer information, programs, coaches, payments, and exercise logs for a fitness management system. The sample data populates the tables to demonstrate its functionality.
