# ERD Assessment

Create an ERD using the tool of your choice (ex. db diagram, drawsql, etc.). The ERD is for a library to keep track of what books are on the shelves. The ERD should match the following description:

* The Book table should include
  * id
  * title
  * year published
  * number of copies

* The Author table should include:
  * id
  * first name
  * last name

* The Section table should include:
  * id
  * name

* The Subject table should include:
  * id
  * name

For the relationships between tables:
* A Book will belong in one section
* A Book can have more than one Author
* An Author will have more than one book in the library
* A Book can be about multiple Subjects
* Subjects will be reused for multiple books
