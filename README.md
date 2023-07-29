# Database projects

Welcome to this repository containing information about database projects. Each project is briefly described below and is placed in its respective folder in the repository. In each folder, you can find documentation with detailed project descriptions in the Polish language.


## 1. Library Database Project - MySQL, PHP
This project focuses on creating a database for a library, designed using MySQL and PHP.

### Database tables
The database comprises 8 interconnected tables, each serving a specific purpose. The tables are as follows:

* **Czytelnik** (Reader): Stores information about library readers.
* **Pracownik** (Employee): Contains data about library employees.
* **Rola** (Role): Stores roles associated with library personnel.
* **Książka** (Book): Contains information about books available in the library.
* **Wydawnictwo** (Publisher): Stores data about book publishers.
* **Autor** (Author): Contains details of book authors.
* **Kategoria** (Category): Stores book categories and genres.
* **Wypożyczenie** (Loan): Tracks book loans made by readers.

### The relational database diagram is presented below
<img src="https://github.com/lisajankk/databases/assets/124843836/572f92f7-b25b-4aaf-9dbf-0ffb0a065db7" width="700">

### PHP user interface
A PHP user interface has been designed for the convenient use of the database. It allows the following operations:

* **Displaying Table Contents**: Ability to view the contents of each table (SELECT operation).
* **Adding, Deleting, and Editing Records**: Enables inserting, deleting, and updating records in selected tables (INSERT, DELETE, UPDATE operations).
* **Viewing a Database View**: Allows viewing a database view.
* **Calling Functions**: Enables the execution of predefined functions.
* **Trigger Execution**: Supports running predefined triggers (events + defined actions).

### PHP interface page example

The created PHP interface includes a homepage with buttons that allow navigation to different pages, each representing individual tables. One such table is the "Wypożyczenie" (Loan) table (No 1 in the diagram below), which stores information about book loans made by readers in the library.

Using the page interface, new loan entries can be added to the "Wypożyczenie" (Loan) table (No 2 in the diagram below).

It is also possible to check the number of loans made during a given period (No 3 in the diagram below) using a specially created function in the database.

Furthermore, another function allows obtaining information about the number of loans a specific reader has made, by providing the reader's index (number 4 in the diagram below).

Moreover, there is a possibility to edit and delete (No 5 in the diagram below) each loan to correct the information or delete it.

<img src="https://github.com/lisajankk/databases/assets/124843836/5d1d5d84-3523-4375-9d7a-2f7cfee6e597" width="600">

### Additional information

The project folder contains scripts used to create individual tables, their relationships, and the PHP interface.

The documentation provided with the project offers a detailed description of the project's progress, the purpose of each table, and includes the code.
