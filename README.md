# CRUD-application-using-ExpressJS-and-MYSQL
💡 Procedure description.

## Table of Context

### -Setup
### -Database Variables
### -Screenshots

## 1.Setup
1. [Clone](https://github.com/frankmutethia/CRUD-application-using-ExpressJS-and-MYSQL"Clone") or [fork](https://github.com/frankmutethia/CRUD-application-using-ExpressJS-and-MYSQL) the CRUD application repository.
2. Ensure the necessary software editors such as sublime(or any other approppriate text-editor), MYSQL Workbench and Git are installed.
3. Install the following node.js dependencies: Express, MYSQL, Body-parse and Handlebars using the below command in the git terminal.
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
## 2.Database Variables

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

## 3.Screenshots
![Screenshot (86)](https://github.com/frankmutethia/CRUD-application-using-ExpressJS-and-MYSQL/blob/master/images/Screenshot%20(86).png)
![Screenshot (87)](https://github.com/frankmutethia/CRUD-application-using-ExpressJS-and-MYSQL/blob/master/images/Screenshot%20(87).png)

