```
CREATE TABLE Persons (
    ID int NOT NULL,
    LastName varchar(255) NOT NULL,
    FirstName varchar(255),
    Age int,
    PRIMARY KEY (ID)
);
```
```
INSERT INTO Persons (ID, LastName, FirstName, Age) VALUES
(1, 'Smith', 'John', 25),
(2, 'Johnson', 'Emily', 30),
(3, 'Williams', 'Michael', 22),
(4, 'Jones', 'Jessica', 28),
(5, 'Brown', 'Christopher', 35);
```
```
UPDATE Persons
SET LastName = 'Gupta'
WHERE FirstName = 'kumar';
```
