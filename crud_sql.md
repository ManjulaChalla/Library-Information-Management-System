## Create operation for BookBorrower table  
INSERT INTO BookBorrower (CardNo, BookName, BookEmail, BookAddress, BookIssued)
VALUES (3, 'The Catcher in the Rye', 'alice.jones@email.com', '789 Pine Street', '2023-03-10');

-- Create (INSERT) operations for Books table  
INSERT INTO Books (BookId, ISBN, Published, BookTitle, AuthorName, CopiesAvailable)
VALUES (103, '978-0-06-112008-4', '1951-07-16', 'The Catcher in the Rye', 'J.D. Salinger', 10);

-- Create (INSERT) operations for Publisher table  
INSERT INTO Publisher (PublisherId, PublisherName, PublisherAddress, PublisherMobile)
VALUES (1003, 'HarperCollins', '789 Publishing Lane', '+1 555-9012');

## Read Operation
-- Select all records from BookBorrower table  
SELECT * FROM BookBorrower;

-- Select specific columns from Books table  
SELECT BookId, BookTitle, AuthorName FROM Books;

-- Select records based on a condition from Publisher table  
SELECT * FROM Publisher WHERE PublisherName = 'Penguin Books';  

## Update Operation

-- Update BookBorrower's email address for a specific CardNo  
UPDATE BookBorrower SET BookEmail = 'alice.jones.updated@email.com' WHERE CardNo = 3;

-- Update the number of CopiesAvailable for a specific book in the Books table  
UPDATE Books SET CopiesAvailable = 5 WHERE BookId = 103;

## Delete Operation

-- Delete a record from BookBorrower based on CardNo  
DELETE FROM BookBorrower WHERE CardNo = 3;

-- Delete a record from Books based on BookId  
DELETE FROM Books WHERE BookId = 103;



