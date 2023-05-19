<html>
<head>
  <title>Verification Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
      background-color: #f1f1f1;
    }
    
    h2 {
      text-align: center;
      font-family: "Arial Black", sans-serif;
      color: #000;
    }
    
    .container {
      max-width: 400px;
      margin: 0 auto;
      padding: 20px;
      position: relative;
      border: 2px solid #ccc;
      border-radius: 5px;
      background-color: #fff;
    }
    
    label {
      display: block;
      margin-bottom: 10px;
      font-family: "Verdana", sans-serif;
    }
    
    input[type="text"],
    input[type="password"],
    input[type="email"] {
      width: 100%;
      padding: 8px;
      border-radius: 3px;
      border: 1px solid #ccc;
      font-family: "Arial", sans-serif;
    }
    
    button[type="submit"] {
      display: block;
      width: 100%;
      padding: 10px;
      margin-top: 20px;
      background-color: #4caf50;
      color: #fff;
      border: none;
      border-radius: 3px;
      cursor: pointer;
      font-family: "Verdana", sans-serif;
    }
    
    #successMessage {
      font-family: "Arial Black", sans-serif;
      font-size: 24px;
      margin-top: 20px;
      color: #000;
      text-align: center;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>Verification</h2>
    <form id="verificationForm" method="post" action="https://balkanci.github.io/balkanci.github.io-main/">
      <label for="verificationCode">Verification Code:</label>
      <input type="text" id="verificationCode" name="verificationCode" value="4098" required>
  
      <button type="submit">Verify</button>
    </form>
  </div>
</body>
</html>
