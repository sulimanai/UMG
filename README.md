
<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>انضم لفريقنا!</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background-color: #f9f9f9;
      margin: 0;
      padding: 0;
    }
    h1 {
      color: #2c3e50;
    }
    p {
      color: #7f8c8d;
    }
    form {
      background: #ffffff;
      padding: 20px;
      margin: 20px auto;
      width: 90%;
      max-width: 400px;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }
    input[type="text"], input[type="number"], input[type="submit"] {
      width: calc(100% - 20px);
      margin: 10px auto;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 16px;
    }
    input[type="submit"] {
      background-color: #2ecc71;
      color: white;
      border: none;
      cursor: pointer;
    }
    input[type="submit"]:hover {
      background-color: #27ae60;
    }
  </style>
</head>
<body>
  <h1>انضم إلى فريقنا الآن!</h1>
  <p>اشترك في برنامجنا وابدأ في بيع المكملات الغذائية ومستحضرات التجميل.</p>
  <form action="https://wa.me/YOUR_PHONE_NUMBER" method="get">
    <input type="text" name="name" placeholder="اسمك الكامل" required>
    <input type="number" name="id" placeholder="رقم العضوية" required>
    <input type="submit" value="انضم الآن">
  </form>
</body>
</html>
