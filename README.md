<html>
  <head>
    <title>Forms</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }

        h1 {
            color: #333;
        }

        input, button {
            margin: 10px 0;
            padding: 10px;
            font-size: 16px;
        }

        button {
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #0056b3;
        }
    </style>
  </head>
  <body>
    <h1>Form</h1>
    Name: <input type="text" placeholder="Enter Name" requried/><br>
    Age: <input type="number" placeholder="Enter Age" requried/><br>
    Gender: <input type="radio" name="gender"/> Female
    <input type="radio" name="gender"/> Male
    <br>
    Gmail : <input type="email" requried/>
    <br>
    <button type="Submit">Submit</button>
    <button type="Reset">Reset</button>
    
  </body>
</html>
