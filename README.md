<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>LmzTools Free Diamond</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .login-box {
      background-color: #ffffff;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      width: 90%;
      max-width: 350px;
      text-align: center;
    }
    .login-box h2 {
      color: #009688;
      margin-bottom: 20px;
    }
    .login-box input {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 6px;
    }
    .login-box button {
      width: 100%;
      padding: 12px;
      background-color: #009688;
      color: white;
      border: none;
      border-radius: 6px;
      font-weight: bold;
      cursor: pointer;
    }
    .login-box button:hover {
      background-color: #00796b;
    }
    .login-box .get-key {
      margin-top: 15px;
      font-size: 14px;
    }
    .login-box .get-key a {
      color: #007bff;
      text-decoration: none;
      font-weight: bold;
    }
    .login-box .get-key a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

<div class="login-box">
  <h2>LmzTools Free Diamond</h2>
  
  <input type="text" id="username" placeholder="User name">
  <input type="password" id="password" placeholder="Password">
  
  <button onclick="login()">Login</button>
  
  <div class="get-key">
    No account? <a href="https://t.me/lmztools" target="_blank">Get Free Key</a>
  </div>
</div>

<script>
  function login() {
    const user = document.getElementById('username').value;
    const pass = document.getElementById('password').value;

    if (user && pass) {
      alert("Login successful! (This is a demo)");
      // You can add redirection here if needed
    } else {
      alert("Pakilagay ang username at password.");
    }
  }
</script>

</body>
</html>
