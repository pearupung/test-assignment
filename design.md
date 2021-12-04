# Design

## Design overview

An overview to showcase main components and prioritise tasks.

### Opening page

Basically we want to make a big view of books with a search bar on top and main statuses of books between the view of books and the search bar. Those main statuses are:

- All books
- Available
- Borrowed
- Other

Opening page has an 'add a book' button.

### Books list

In the books list view, there are some details of the books on which the user can sort them. Clicking on a book links to a detailed book page. Every book has a lending button in the list - stationary or appearing when hovered on, let's decide that later. Lending button on the list is a nice to have and not a priority.


### Book detailed page

Detailed book page has a descriptive section about the book on top and a list of checkouts underneath. The detailed page has to have a status change button that pops up a modal and let's the user modify the status of the book. Detailed book page has to have a button that pops up a change the book modal. 

### State change modal

Has a save button, a cancel button and a due date for the state. 

### Change the book modal

Has a delete button and text fields to change to book.

### List of checkouts

Not a priority. Should contain all checkouts. Needs changes to the database in order to persist history. A massive change and does not help in the POC.

