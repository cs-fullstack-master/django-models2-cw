# Review and introduction to basic CRUD

Begin by opening the starter project in intelliJ. The starter project has an existing data model. Start the server and ensure it is working properly by going to http://127.0.0.1:8000/ before proceeding.

### Exercise 1:
Create a view and corresponding route for endpoint ```createres/``` that will add a new Respondent to the database. Use the functions provided in ```views.py``` to generate a random name, age, and salary. Print the resulting collection of ALL instance records from the database.

### Exercise 2:
Create a view and corresponding route for endpoint ```readres/``` that will retrieve all of the Respondent instance records and print the result

### Exercise 3:
Create a view and corresponding route for endpoint ```updateres/``` that will update the salary of the Respondent ```Joe Walsh``` and print the updated record once changes are saved. Use the random salary function to get a new salary.

### Exercise 4:
Create a view and corresponding route for endpoint ```deleteres/``` that will delete a specific Respondent of your choosing. Print all of the Respondent instance records BEFORE *and* AFTER the delete operation. 

### Challenges:
* Use Django templates and views to return a response as HTML to the browser after every operation
* Implement a view and corresponding route for endpoint ```richdudes/``` that will return a list of all respondents with a salary over 200000
* Implement a view and corresponding route for endpoint ```olddudes/``` that will return a list of all respondents with an age over 80

### NOTE:
Migrate and create a superuser to use Django admin as needed
