-- Table for Book Borrower
CREATE TABLE BookBorrower (
    CardNo INT PRIMARY KEY,
    BookName VARCHAR(255),
    BookEmail VARCHAR(255),
    BookAddress VARCHAR(255),
    BookIssued DATE
);

-- Table for Books
CREATE TABLE Books (
    BookId INT PRIMARY KEY,
    ISBN VARCHAR(13),
    Published DATE,
    BookTitle VARCHAR(255),
    AuthorName VARCHAR(255),
    CopiesAvailable INT
);

-- Table for Publisher
CREATE TABLE Publisher (
    PublisherId INT PRIMARY KEY,
    PublisherName VARCHAR(255),
    PublisherAddress VARCHAR(255),
    PublisherMobile VARCHAR(20)
);
