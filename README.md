<html>
  <head>
    <title>Forms</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
            color:black;
            background-size:cover;
           background-image:url("https://img.freepik.com/free-vector/simple-blank-green-background-vector-business_53876-166892.jpg?t=st=1738420376~exp=1738423976~hmac=f507db24938ca441981cdedd2a8260d4083d04bafe42bfb8aa7702ade58f10fb&w=360");
        }

        h1 {
            color: black;
        }

        input, button {
            margin: 10px 0;
            padding: 10px;
            font-size: 16px;
            border-radius:10px;
            color:white;
        }

        button {
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 10px;
            cursor: pointer;
        }

        
    </style>
  </head>
  <body>
    <h1>Form</h1>
    <form action="/submit-form">
    Name: <input type="text" placeholder="Enter Name" requried/><br>
    Age: <input type="number" placeholder="Enter Age" requried/><br>
    Gender: <input type="radio" name="gender"/> Female
    <input type="radio" name="gender"/> Male
    <br>
    Gmail : <input type="email" placeholder="Enter Email" requried/>
    <br>
      University Name: <input type="text" placeholder="Enter University Name"/><br>
    <button type="Submit">Submit</button>
    <button type="Reset">Reset</button>
    </form>
  </body>
</html>
