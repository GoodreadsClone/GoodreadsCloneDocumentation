GoodreadsCloneDocumentation

DB diagram: https://dbdiagram.io/d/643c9e8e6b31947051b0570c

The application has following actors
1. User
2. Author

## User
1. A user can sign up if its their first time
2. A user can login into the application
3. A user can read books, by searching by name, genre, author name or tags
4. A user can add or remove books from bucket list
5. A user can mark a book as currently reading ( can only mark one book )
6. A user can add comments to a book
7. A user can give rating to a book
8. A user can look at the history of books
9. A user can resume reading of any books of the past, the application needs to open the page user last left off.

 **Additional features**
10. A user can add friends
11. A user can join groups
12. User can set a status just like instagram or snapchat status, about the books they are reading.
13. A user can follow authors
14. An user gets notified when the author publishes a book or makes an announcement

## Author
1. An author can publish books
2. An author gets his books rated by the users,
3. rating of the author is the average of all the ratings of his/her books

**Additional features**
4. An author has followers
5. An author can make an announcenment.


# User Facing Features
1. Dark mode (of course)
2. State of the art search functionality with custom search algorithm
3. custom recommendation algorithm.
4. Smooth animation wherever applicable
5. Mocking a e-book layout when a user choooses to open a book
6. Reactive nature

# Developer Facing Features
1. Low latency
2. Load balancing
3. Clean and sleek UI
4. Ultra clean code for improved code maintainance
5. Distributed database and servers for high availability and low latency
6. caching of data wherever applicable to reduce load times
7. Lazy loading of data

# Current API List (will be modified ad-hoc)
Create User.    
Create Author.     
Create Book.    
getAllBooks.    
getBookByBookId     
addBookToWantToReadListByUserId.    
updateCurrentlyReadingByUserId.   
getAllWantToReadsByUserId.   
getUserCurrentlyReading.   
getAllBooksByAuthor.    
APIs that still need to be added.   

Related to user history.   
Related to user comments.   
Related to comments.   
Ad hoc APIs.   

# Implementing Real-Time fast search in React using debouncing and memoization.
https://javascript.plainenglish.io/how-to-create-an-optimized-real-time-search-with-react-6dd4026f4fa9
