<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Facebook Login</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      background-color: #f0f2f5;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .login-container {
      background: white;
      padding: 20px;
      width: 360px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      border-radius: 8px;
      text-align: center;
    }
    .login-container h1 {
      color: #1877f2;
      font-size: 36px;
      margin-bottom: 20px;
    }
    input[type="text"], input[type="password"] {
      width: 100%;
      padding: 12px;
      margin: 8px 0;
      border: 1px solid #ddd;
      border-radius: 6px;
      font-size: 16px;
    }
    .login-btn {
      background-color: #1877f2;
      color: white;
      padding: 12px;
      width: 100%;
      border: none;
      border-radius: 6px;
      font-size: 16px;
      font-weight: bold;
      cursor: pointer;
    }
    .login-btn:hover {
      background-color: #165cdb;
    }
    .forgot-link {
      display: block;
      margin: 12px 0;
      color: #1877f2;
      text-decoration: none;
      font-size: 14px;
    }
    hr {
      margin: 20px 0;
      border: 0;
      border-top: 1px solid #ddd;
    }
    .create-account {
      background-color: #42b72a;
      margin-top: 10px;
      padding: 10px;
      color: white;
      border: none;
      border-radius: 6px;
      width: 100%;
      font-size: 15px;
      font-weight: bold;
      cursor: pointer;
    }
    .create-account:hover {
      background-color: #36a420;
    }
  </style>
</head>
<body>

  <div class="login-container">
    <h1>facebook</h1>
    <form>
      <input type="text" placeholder="Email or Phone Number" required>
      <input type="password" placeholder="Password" required>
      <button class="login-btn" type="submit">Log In</button>
      <a class="forgot-link" href="#">Forgotten password?</a>
      <hr>
      <button class="create-account" type="button">Create New Account</button>
    </form>
  </div>

</body>
</html>