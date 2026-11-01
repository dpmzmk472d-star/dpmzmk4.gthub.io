<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>دخول الإدارة - مركز الروضة المحمدية</title>
    <style>
        :root {
            --primary-color: #0b4f6c;
            --secondary-color: #1a73e8;
            --accent-color: #f1f3f4;
            --text-color: #333;
            --light-text: #fff;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--accent-color);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .login-container {
            background-color: var(--light-text);
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            width: 100%;
            max-width: 400px;
            text-align: center;
        }

        .login-container h2 {
            color: var(--primary-color);
            margin-bottom: 25px;
        }

        .form-group {
            margin-bottom: 20px;
            text-align: right;
        }

        .form-group label {
            display: block;
            margin-bottom: 8px;
            color: var(--text-color);
            font-weight: 600;
        }

        .form-group input {
            width: 100%;
            padding: 12px;
            border: 1px solid #ccc;
            border-radius: 8px;
            box-sizing: border-box;
            font-size: 1rem;
        }

        .btn {
            display: inline-block;
            background-color: var(--primary-color);
            color: var(--light-text);
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 8px;
            font-size: 1.1rem;
            font-weight: bold;
            transition: background-color 0.3s ease;
            width: 100%;
            border: none;
            cursor: pointer;
        }

        .btn:hover {
            background-color: #083c51;
        }
    </style>
</head>
<body>

    <div class="login-container">
        <h2>تسجيل دخول الإدارة</h2>
        <form>
            <div class="form-group">
                <label for="username">اسم المستخدم</label>
                <input type="text" id="username" name="username" required>
            </div>
            <div class="form-group">
                <label for="password">كلمة المرور</label>
                <input type="password" id="password" name="password" required>
            </div>
            <button type="submit" class="btn">دخول</button>
        </form>
    </div>

</body>
</html>
