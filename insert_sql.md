-- Insert data into BookBorrower table   
INSERT INTO BookBorrower (CardNo, BookName, BookEmail, BookAddress, BookIssued)
VALUES
    (1, 'The Great Gatsby', 'john.doe@email.com', '123 Main Street', '2023-01-15'),
    (2, 'To Kill a Mockingbird', 'jane.smith@email.com', '456 Oak Avenue', '2023-02-20'),
  

-- Insert data into Books table   
INSERT INTO Books (BookId, ISBN, Published, BookTitle, AuthorName, CopiesAvailable)
VALUES
    (101, '978-0-7475-3269-6', '2003-05-01', 'Harry Potter and the Order of the Phoenix', 'J.K. Rowling', 25),
    (102, '978-0-385-08137-7', '1960-07-11', 'To Kill a Mockingbird', 'Harper Lee', 15),
    

-- Insert data into Publisher table  
INSERT INTO Publisher (PublisherId, PublisherName, PublisherAddress, PublisherMobile)
VALUES
    (1001, 'Penguin Books', '123 Publishing Street', '+1 555-1234'),
    (1002, 'Random House', '456 Publishing Avenue', '+1 555-5678');
    
