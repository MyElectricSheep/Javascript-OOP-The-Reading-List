# The Reading List: an Object Oriented Booklist

- ##### This is an exercise created for the [WBS Coding School](https://www.wbscodingschool.com/) to practice **Object Oriented Programming (OOP)** concepts in Javascript.  
- ##### This repo contains the solution to the following exercise

##### Achieve the following tasks:

- Create a class called `BookList`
- Create another class called `Book`

- BookLists should have the following properties:
-- An array of all the Books
-- Number of books marked as read
-- Number of books marked not read yet
-- A reference to the next book to read (book object)
-- A reference to the current book being read (book object)
-- A reference to the last book read (book object)

- Each Book should have several properties:
-- Title
-- Genre
-- Author
-- Read (true or false)
-- Read date, can be blank, otherwise needs to be a JS Date() object

- Every Booklist should have a few methods:
-- `.add(book)` should add a book to the books list.
-- `.finishCurrentBook()` should mark the book that is currently being read as "read"
-- Give it a read date of new Date(Date.now())
-- Change the last book read to be the book that just got finished
-- Change the current book to be the next book to be read
-- Change the 	next book to be read property to be the first unread book you find in the list of books
-- Booklists and Books might need more methods than that. Try to think of more that might be useful.


