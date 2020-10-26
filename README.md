# Gruppe 3 - Uptight Wealth
*Ikke vores valg af gruppenavn*

**Gruppemedlemmer:**
- Cahit
- Marcus
- Michael

Dette github repository er tilrettet opgavestillinger, så udspecifieret her: [Uge7 Opgave](https://docs.google.com/document/d/1ojSiBWwLo4-Rc7763vx6aVEYdNluATOMja9qqk4dodU/edit#) 


#### Assignment 1, Data Persistance
1. Make a class **Book** with the following variables:
    a. book_id
    b. title
    c. author
    d. num_of_pages
    e. published_date
2. Give the class a function **information**, that functions like a toString for the book
3. Make a database called **book_repository**
4. Make a **facade** class, that will handle communication with the database, with two functions, **Push** and **Pull**. How these work is up to you.
4. Persist 5 books into the database as dummy data
a. Check the database, to see if they are correctly stored
b. try pulling them back into the notebook, and see if you can turned them back into an instance of the **Book** class.
c. use the **information** function on the books pulled from the database.

#### Assignment 2, Web Service
*Note, that these endpoints does not have to be connected database yet, as that is part of Assignment 3, but you can do that right away if you wish*
1. Setup a Web Service where you have the following endpoints with you **Book** class from Assignment 1.
a. ***'/todo/api/book'*** as a **GET** endpoint, to get all books
b. ***'/todo/api/book/<int:book_id>'*** as a **GET** endpoint, to get a specific book
c. ***'/todo/api/book'*** as a **POST** endpoint, to add a book
d. ***'/todo/api/book/<int:book_id>'*** as a **PUT** endpoint, to edit a specific book
e. ***'/todo/api/book/<int:book_id>'*** as a **DELETE** endpoint, to delete a specific book


#### Assignment 3, Combine and deploy
1. Edit assignement 1 & 2, so when a endpoint is used, the book changes are affecting the database instead of local data, if that is not already the case.
2. Deploy the solution, in either of the two ways recommened from the material in 8.2 from the lessons.

