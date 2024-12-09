# Samta-school-
موقع مدرسه سامتا الثانويه للبنين يهدف لتعريف جميع الطلاب إلى مدرستنا 
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>مدرسة سامتا الثانوية للبنين</title>
  <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Tajawal', sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(to bottom, #00416a, #e4e5e6);
      color: #333;
    }
    header {
      background: #00416a;
      color: #fff;
      padding: 20px 10px;
      text-align: center;
      position: relative;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
      animation: fadeIn 2s ease-in-out;
    }
    header p {
      margin: 5px 0;
      font-size: 1.2rem;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    .welcome {
      text-align: center;
      margin-top: 50px;
      display: none;
    }
    .welcome h2 {
      font-size: 2rem;
      color: #00416a;
      animation: slideIn 2s ease-in-out;
    }
    .welcome p {
      font-size: 1.2rem;
      margin-top: 10px;
    }
    @keyframes slideIn {
      from { transform: translateY(-50px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
    .features {
      padding: 20px;
      margin: 20px;
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .section {
      margin: 30px auto;
      max-width: 800px;
    }
    .section h3 {
      text-align: center;
      font-size: 1.8rem;
      margin-bottom: 15px;
    }
    .teachers, .grades {
      list-style: none;
      padding: 0;
    }
    .teachers li, .grades li {
      margin: 10px 0;
      font-size: 1.2rem;
      padding: 10px;
      background: #f9f9f9;
      border-radius: 5px;
      box-shadow: 0 0 5px rgba(0,0,0,0.1);
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #00416a;
      color: #fff;
      margin-top: 30px;
    }
    footer a {
      color: #f4d03f;
      text-decoration: none;
    }
    .login {
      text-align: center;
      padding: 20px;
      margin-top: 50px;
    }
    .login input {
      padding: 10px;
      margin: 10px 0;
      width: 80%;
      max-width: 300px;
      border-radius: 5px;
      border: 1px solid #ccc;
      display: block;
      margin-left: auto;
      margin-right: auto;
    }
    .login button {
      padding: 10px 20px;
      color: #fff;
      background: #00416a;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s;
    }
    .login button:hover {
      background: #003354;
    }
    .error {
      color: red;
    }
    .success {
      color: green;
    }
  </style>
</head>
<body>

<header>
  <h1>مرحبًا بكم في مدرسة سامتا الثانوية للبنين</h1>
  <p>مدير المدرسة: عبد الحميد المومني</p>
</header>

<div id="login-section" class="login">
  <h2>تسجيل الدخول</h2>
  <input type="text" id="username" placeholder="اسم المستخدم">
  <input type="password" id="password" placeholder="كلمة المرور">
  <button onclick="handleLogin()">تسجيل الدخول</button>
  <p id="login-message"></p>
</div>

<div id="welcome-section" class="welcome">
  <h2>أهلاً وسهلاً! 👋</h2>
  <p>مرحبًا بك في موقع مدرسة سامتا الثانوية للبنين. استمتع بتجربة استثنائية!</p>
</div>

<div class="section">
  <h3>عن المدرسة</h3>
  <p>مدرسة سامتا الثانوية للبنين هي مؤسسة تعليمية متميزة تقدم التعليم من الصف الرابع إلى الثانوية العامة. تأسس هذا الموقع بواسطة المبرمج المحترف والخبير <strong>مصلح أيمن يحيى القضاه</strong>.</p>
</div>

<div class="section">
  <h3>الصفوف الدراسية</h3>
  <ul class="grades">
    <li>الصف الرابع: بداية التعليم الأساسي.</li>
    <li>الصف الخامس: تعزيز المهارات الأساسية.</li>
    <li>الصف السادس: التمهيد للمواد المتقدمة.</li>
    <li>الصف السابع: بناء المعرفة العلمية.</li>
    <li>الصف الثامن: تطوير الفهم العملي والنظري.</li>
    <li>الصف التاسع: الاستعداد للمرحلة الثانوية.</li>
    <li>الصف العاشر: التركيز على التخصصات.</li>
    <li>الثانوية العامة: التجهيز للجامعة.</li>
  </ul>
</div>

<div class="section">
  <h3>أهم المعلمين</h3>
  <ul class="teachers">
    <li>الأستاذ محمد الشرع</li>
    <li>الأستاذ أنس الغرايبة</li>
    <li>الأستاذ أحمد الصغير</li>
    <li>الأستاذ وليد الشواشرة</li>
    <li>الأستاذ عمار</li>
    <li>الأستاذ محمد طلافحة</li>
    <li>الأستاذ محمد الرفاعي</li>
  </ul>
</div>

<div class="section">
  <h3>الدعم الفني</h3>
  <p>للحصول على الدعم الفني، يمكنك التواصل عبر البريد الإلكتروني: <a href="mailto:moslehqudah567@gmail.com">moslehqudah567@gmail.com</a></p>
</div>

<footer>
  <p>زوروا صفحتنا على الفيسبوك: <a href="https://www.facebook.com/profile.php?id=61554180368999&mibextid=kFxxJD" target="_blank">مدرسة سامتا الثانوية للبنين</a></p>
  <p>&copy; 2024 - جميع الحقوق محفوظة</p>
</footer>

<script>
  function handleLogin() {
    const username = document.getElementById('username').value;
    const password = document.getElementById('password').value;
    const message = document.getElementById('login-message');
    if (username === 'admin' && password === '1234') {
      message.textContent = 'تسجيل الدخول ناجح!';
      message.className = 'success';
      document.getElementById('login-section').style.display = 'none';
      document.getElementById('welcome-section').style.display = 'block';
    } else {
      message.textContent = 'اسم المستخدم أو كلمة المرور غير صحيحة!';
      message.className = 'error';
    }
  }
</script>

</body>
</html>
