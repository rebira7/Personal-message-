
<!DOCTYPE html>
<html>
<head>
  <title>Special Message</title>
  <style>
    body {
      text-align: center;
      padding: 100px;
    }
    button {
      padding: 10px 20px;
      font-size: 20px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <h1>For Aesop</h1>
  <button id="messageButton">Click me!</button>
  <p id="messageDisplay"></p>

  <script>
    document.getElementById("messageButton").addEventListener("click", function() {
      document.getElementById("messageDisplay").textContent ="wish you a happy day ";
    });
  </script>
</body>
</html>
