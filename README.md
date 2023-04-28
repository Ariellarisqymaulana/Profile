<!DOCTYPE html>
<html lang="en">
   <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Login Page</title>
      <link rel="stylesheet" href="style.css">
   </head>
   <style>
    * {
       margin: 0;
       padding: 0;
       box-sizing: border-box;
    }

    body {
       font-family: Arial, sans-serif;
       background-color: #eee;
    }

    .container {
       max-width: 400px;
       margin: 80px auto;
       background-color: #fff;
       border-radius: 10px;
       padding: 40px;
       box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    form h2 {
       text-align: center;
       margin-bottom: 20px;
    }

    form label {
       display: block;
       margin-bottom: 10px;
       font-weight: bold;
    }

    form input[type="text"],
    form input[type="password"] {
       width: 100%;
       padding: 10px;
       margin-bottom: 20px;
       border-radius: 5px;
       border: none;
    }

    button[type="submit"] {
       display: block;
       width: 100%;
       padding: 10px;
       font-weight: bold;
       background-color: #007bff;
       color: #fff;
       border: none;
       border-radius: 5px;
       cursor: pointer;
    }

    button[type="submit"]:hover {
       background-color: #0069d9;
    }
   </style>
    

   <body>
      <div class="container">
         <form action="">
            <h2>Login Page</h2>
            <div class="form-control">
               <label for="username">Username:</label>
               <input type="text" id="username" name="username" placeholder="Enter username">
            </div>
            <div class="form-control">
               <label for="password">Password:</label>
               <input type="password" id="password" name="password" placeholder="Enter password">
            </div>
            <button type="submit">Login</button>
         </form>
      </div>
   </body>
</html>
