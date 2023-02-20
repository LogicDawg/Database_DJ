### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
 free and open-source relational database management system emphasizing extensibility and SQL compliance.

- What is the difference between SQL and PostgreSQL?
- PostgreSQL is an object-relational database, SQL is a relational database. PostgreSQL offers more complex data types.

- In `psql`, how do you connect to a database?
- psql `database name`

- What is the difference between `HAVING` and `WHERE`?
- `WHERE` applies to individual rows and `HAVING` applies to a group.

- What is the difference between an `INNER` and `OUTER` join?
- `INNER` join will keep only information from both tables that are related to each other, `OUTER` join will keep information that is not related in the resulting table.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
- `LEFT OUTER` keeps information that is in the left table even if there is no related information. `RIGHT OUTER` does the same thing but on the right table.

- What is an ORM? What do they do?
Obeject Relational Mapping, it allows you to write sql in the selected language your writing your app in, for example in our Python apps we are writing flask commands that create database vs actual SQL commands.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
  It is more secure, only requests that are created in the library can go through and be directed which allows the data to stay consistent as well. Also we can provide specific server side errors that may arise versus browser generic errors.

- What is CSRF? What is the purpose of the CSRF token? Cross-Site Request Forgery, this token keeps the legitamicy of a user. When we preform server-side task we want to make sure that they are done by an end-user and not someone trying to do sketchy things.

- What is the purpose of `form.hidden_tag()`?
This generates a hidden field in which we can pass the CSRF without it being able to be seen by end users.
