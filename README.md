# SQL-Intro

Code From SQLiteStudio

CREATE TABLE IF NOT EXISTS Books (
    BookID INTEGER PRIMARY KEY,
    Title TEXT NOT NULL,
    Author TEXT NOT NULL,
    PublicationYear INTEGER NOT NULL,
    Price REAL NOT NULL
);

INSERT INTO Books (BookID, Title, Author, PublicationYear, Price)
VALUES
    (1, 'To Kill a Fish', 'Fish1', 1960, 7.99),
    (2, '1984: Fish Tales', 'Fish2', 1949, 6.99),
    (3, 'The Da Vinci Fish', 'Fish3', 2003, 8.99),
    (4, 'The Fish in the Rye', 'Fish4', 1951, 5.99),
    (5, 'The Great Fish', 'Fish5', 1925, 10.99);

SELECT * FROM Books;
SELECT * FROM Books WHERE PublicationYear > 2000;
SELECT * FROM Books WHERE Author = 'Fish2';
UPDATE Books SET Price = 7.49 WHERE Title = 'The Da Vinci Fish' AND Author = 'Fish3';
DELETE FROM Books WHERE Title = 'The Great Fish' AND Author = 'Fish5';

Reflection:
Creating this code was a really simple and fun experience.
I learned that Chris's words were true in the fact that writing this code was almost literally reading a writing the English language.
I learned the commands are super simple to write out and do essentially exactly what you type out. 
Getting the SGLiteStudio figured out was probably the most challenging part of this assignment. It took me a minute to figure out how to run everything and how to visualize what I had created.
Overall, I learned that the commands are pretty simple and that the assignments going forward shouldn't be really too hard.