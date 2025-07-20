# Drive-gurd
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Protected Drive Link</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f2f2f2;
      text-align: center;
      margin-top: 100px;
    }
    .box {
      background: white;
      display: inline-block;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
    }
    input {
      padding: 10px;
      width: 200px;
      font-size: 16px;
    }
    button {
      padding: 10px 20px;
      font-size: 16px;
      margin-top: 10px;
      cursor: pointer;
    }
  </style>
  <script>
    function checkPassword() {
      var userInput = document.getElementById("password").value;
      var correctPassword = "Dena 17july";

      if (userInput === correctPassword) {
        window.location.href = "https://drive.google.com/drive/folders/17WzpXFfXeHlPHgq3OC41dpHvKExR3Y5q";
      } else {
        alert("Wrong password! Try again.");
      }
    }
  </script>
</head>
<body>
  <div class="box">
    <h2>Enter Password to Access the Drive Folder</h2>
    <input type="password" id="password" placeholder="Enter Password" />
    <br>
    <button onclick="checkPassword()">Submit</button>
  </div>
</body>
</html>
