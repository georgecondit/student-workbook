In a SQL table, what is the difference between information in a row and information in a column? 

A row is a complete object and a column makes up the properties of the object. 

Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

CREATE TABLE characters
(
  name VARCHAR(255) NOT NULL,
  age VARCHAR(255) NOT NULL,
  description VARCHAR(255) NOT NULL,
  id INT NOT NULL,
  
);

What is the difference between the following statements:
DELETE FROM table_name;this will delete a compmlete object
DROP TABLE table_name; this will delete the entire ta;ble

