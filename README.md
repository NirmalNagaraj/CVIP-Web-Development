# CVIP-Web-Development
Progress of the CodersCave internship

This Repo contains ..
  ```
    1.Netflix Clone page
    2.Online Code Editor
```

## 1. Online Code Editor

A simple web-based code editor for HTML, CSS, and JavaScript. Edit and run your code directly in your browser.

## Usage

1. **Clone the Repository:**

   ```
   git clone https://github.com/NirmalNagaraj/CVIP-Web-Development.git
   ```

2. **Navigate to the Project Directory:**

   ```
   cd Online-Code-Editor
   ```

3. **Open `index.html` in your Web Browser:**


## 2. Netflix Clone
This is a simple clone of the Netflix page , which depicts the UI of the Netflix and the user authentication.

# Prerequisites
  1. Mysql
  2. Mysql Workbench (optional)
  3. Node js
     
# Usage

1. **Clone the Repository:**

   ```
   git clone https://github.com/NirmalNagaraj/CVIP-Web-Development.git
   ```

2. **Navigate to the Project Directory:**

   ```
   cd Netflix-Clone
   ```
3. **Setting Up the Database**
    
    1. Open the Mysql terminal
    2. Create a database and the schema by referring `db.sql` .
    3. Check whether the table is created for User validation.

4. **Setting Up the server**

   Change this code with local db details
     ```
     const connection = mysql.createConnection({
    host: 'localhost',
    user: 'root',
    password: '',
    database: 'netflix'
    });
    ```
5. **Executing the Server**
   ```
   node server.js
   ```
6.**Executing the frontend**
    After setting and executing the server , open the `info.html` in your prefered browser (Chrome and Edge is recommended)

**Happy Executing !!**
