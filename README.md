# CRUD-application-using-ExpressJS-and-MYSQL
💡 Procedure description.

## Table of Context

### *Database Variables
### *Setup
### *Screenshots

#### Database Variables
1. Open the index.js folder located inside the repository.
2. Change the index.js variables in accordance to your specific MYSQL username and password.

```
//Create Connection
const conn = mysql.createConnection({
  host: 'localhost',
  user: 'root',
  password: 'root',
  database: 'crud_db'
});
```
3.Find the database used for the project, in the exported msql db folder and import it to your mysql database. 

#### Setup
1. Clone or fork the CRUD application repository.
2. Ensure the necessary software editors such as sublime(or any other approppriate text-editor), MYSQL Workbench and Git are installed.
3. Install the following node.js dependencies:
  - Express
  - MYSQL
  - Body-parse
  - Handlebars
  Type the below command in the git terminal of the project to get the above dependencies:
  ```
  npm install --save express mysql body-parser hbs
  ```
 4. Run project:
 ```
 node index
  ```
 5. See output:
  ```
  http://localhost:8000/
  ```
#### Screenshots
![Screenshot (86)](https://user-images.githubusercontent.com/50831575/131509177-872ce062-72c7-4325-87c7-4d4cdf599f82.png)

