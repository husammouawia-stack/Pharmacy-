<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <title>تسجيل دخول- صيدلية المنارة</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
         body {
      font-family: "Tahoma", sans-serif;
      background: url('M.jpg') no-repeat center center fixed;
      font-style: normal;
      background-size: cover;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .login-box {
      background: rgba(255, 255, 255, 0.5);
      border: none;
      backdrop-filter: blur(7px);
      border-radius: 20px;
      box-shadow: 0 4px 30px rgba(0,0,0,0.2);
      padding: 40px 30px;
      width: 350px;
      text-align: center;
      color: #222;
    }
    .login-box .icon{
      text-align: center;
      margin-bottom: 15px;
    }
    .login-box .icon i{
      font-size: 80px;
      color: #108700;
      
    }
    .login-box h1 {
      margin-bottom: 25px;
      color: #108700;
      font-size: 25px;
    }
  
    .input-container {
      position: relative;
      margin-bottom: 15px;
    }

    .input-container input {
      width: 85%;
      padding: 12px 35px 12px 12px ;
      border-radius: 25px;
      border: solid #108700;
      outline: none;
      background: rgba(255,255,255,0.30);
      box-shadow: 0 0 5px rgba(0,0,0,0.2);
      color: #333;
      font-size: 15px;
    }

    .input-container i {
      position: absolute;
      right: 12px;
      top: 50%;
      transform: translateY(-50%);
      font-size: 17px;
      color: #108700;
      cursor: pointer;
    }
      .login-box .options {
      display: flex;
      justify-content: space-between;
      align-items: center;
      font-size: 13px;
      margin-bottom: 15px;
    }

    .login-box a{
      color: #108700;
      text-decoration: none;
      border: none;
    }
    .login-box a:hover{
      text-decoration: underline;
    }
    .login-box a:active {
      font-size: 110%;
    }

    .login-box button {
      width: 100%;
      padding: 12px;
      border: none;
      border-radius: 30px;
      background: linear-gradient(45deg, #4caf50, #2e7d32);
      color: #fff;
      font-size: 16px;
      cursor: pointer;
      margin-top: 10px;
      transition: 0.2s;
    }

    .login-box button:hover {
      background: #2e7d32;
    }

    .login-box button:active {
      transform: scale(0.97);
    }
  </style>
</head>
<body>
  <div class="login-box">
      <img src="Snake.png" alt="pharmacy" width="70" height="70">
   <h1>🌿Al-Manara Pharmac</h1>
    <form>
      <div class="input-container"
        <input type="text" placeholder="أسم المستخدم أو الايميل" required>
  <i class="fa-solid fa-user"></i>
  </div>
       <div class="input-container"
        <input type="password" placeholder="كلمة السر"required>
        <i class="fa-solid fa-lock"></i>
      </div>

      <div class="options">
        <label><input type="checkbox">تذكرني</label>
        <a href="#">نسيت كلمة السر؟</a>
      </div>

      <button type="submit">تسجيل دخول</button><br><br>
      
    <a href="New Account.html"><button type="button">إنشاء حساب جديد</button></a>
    </form>
  </div>
</body>
</html>
