##Development tasks

* Using backend api endpoint /getBooks, implement table of books view
* Using backend api endpoint /getCheckouts, also implement the checkouts view. Suppport paging and sorting for both views
* Implement individual book and checkout view, support basic CRUD operations, implement checking out and returning books
* Implement searching for books using freetext criteria
* Implement filtering for books by status
* Implement saving / displaying favorite books for current user (you can use localStorage if you don't want to make back-end changes)
* Add modal confirmation dialogues when deleting or checking out books
* Implement a user-friendly way to display late checkouts

#####Bonus tasks:
* Implement advanced search form for books, where user can specify and combine different criterias (title, author year etc)
* Add UI and backend tests 
* Add support for multiple languages
* Add support for multiple users and different user roles: reader and librarian.
Reader should not be able to add / modify / delete existing book information or tamper with checkouts
but should be able to save favorites and check out / return books (that they have checked out)

## User stories

- `001` As a user, I want to see books at the library so I can skim over what the library has.
    - `0010` As a lender I want to see books that are available.
    - `0011` As a librarian I want to see which books need to be returned to ensure that books are not stolen.
    - `0012` As a lender that desperately needs a book, I want to see who has lended the book in order to collaborate with them.
    - `0013` As a librarian I want to know who has lended a book in order to report stolen books to the police.
    - `0014` As a user I want to see other statuses of the book in order to know when the book is available and what happened to a book.
    - `0015` As a user I want to see my favourite books in order to lend them again or reccommend them to friends.
    - `0016` As a librarian I want to see the most favourited books in order to make decisions on which books to order.
    - `0017` As a librarian I want to see the most checked out books in order to make decisions on which books to order.
    - `0018` As a user I want to sort books to see books that are more relevant to me first.
    - `0019` As a user I want to filter books based on certain criteria.
    - `001a` As a reader I want to see my favourite books to quickly recommend them to friends or lend them again.
- `002` As a user I want to interact with a book in detail in order to decide what to make of it.
    - `0021` As a user I want to know the book's description, author, title and publishing year to decide whether to borrow it.
    - `0022` As a user I want to know the borrowing history of a book to know whether it is popular or not.
    - `0023` As a user I want to know the rating of a book to decide whether to lend it or not.
    - `0024` As a user I want to rate the book to give feedback to the library.
    - `0025` As a librarian I want to see the book rating to decide whether to throw it out and free some space.
    - `0026` As a librarian I want to check out books to readers in order to keep track of inventory and not lose valuable books.
    - `0027` As a librarian I want to change the status of a book to let the users know which books are available.
    - `0028` As a librarian I want to specify when the book is going to be available again to keep track of overdue checkouts and let users know when the book is available.
    - `0029` As a librarion I want to see book's checkouts to analyse who has damaged the book.
    - `002a` As a librarian I want to see a reader's checkouts to analyse readers reading speed and customise due dates based on it.
    - `002b` As a librarian I want to create books to enlist new books and show users that they are available.
    - `002c` As a librarian I want to change book details to correct an error in the data.
    - `002d` As a system administrator I want to delete books from the database to clean up disk space.
    - `002e` As a user I want to be notified when I am making important or non-reversible changes to a book to never accidentally delete or lend a book without prior knowledge or understanding.
- `003` As an Estonian user I want to operate in my native language to be able to understand and preserve my culture.
- `004` As a business owner I want to have reader and librarian capabilities separated to ensure that operations are carried out by people who I can trust.
- `005` As a business owner I want the application to be covered by tests to ensure a stable overview and documentation of operations and easier handover-takeover in the future.
