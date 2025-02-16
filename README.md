
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yobazar - تحقق من ملصق الضمان</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #2c3e50;
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        p {
            font-size: 1.2rem;
            color: #555;
        }
        .input-group {
            display: flex;
            align-items: center;
            gap: 10px; /* المسافة بين العناصر */
            margin: 20px 0;
        }
        .input-container {
            position: relative;
            flex: 1; /* يأخذ المساحة المتبقية */
        }
        .input-container input {
            width: 100%;
            padding: 15px;
            border: 2px solid #3498db;
            border-radius: 25px; /* حواف دائرية */
            font-size: 1.2rem;
            outline: none;
            transition: border-color 0.3s ease;
        }
        .input-container input:focus {
            border-color: #2980b9;
        }
        .input-container label {
            position: absolute;
            top: 50%;
            left: 15px;
            transform: translateY(-50%);
            font-size: 1.2rem;
            color: #777;
            background-color: #fff;
            padding: 0 5px;
            transition: all 0.3s ease;
            pointer-events: none;
        }
        .input-container input:focus + label,
        .input-container input:not(:placeholder-shown) + label {
            top: 0;
            font-size: 1rem;
            color: #3498db;
        }
        button {
            padding: 15px 30px;
            background-color: #f1c40f; /* لون أصفر */
            color: white;
            border: none;
            border-radius: 25px; /* حواف دائرية */
            font-size: 1.2rem;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        button:hover {
            background-color: #f39c12; /* لون أصفر داكن */
        }
        #result {
            margin-top: 20px;
            padding: 15px;
            border-radius: 10px;
            font-size: 1.1rem;
        }
        .success {
            background-color: #d4edda;
            color: #155724;
            border: 1px solid #c3e6cb;
        }
        .error {
            background-color: #f8d7da;
            color: #721c24;
            border: 1px solid #f5c6cb;
        }
        .logo {
            width: 100px;
            margin-bottom: 20px;
        }
        .banner {
            width: 100%;
            max-height: 200px;
            object-fit: cover;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        .footer {
            margin-top: 40px;
            padding: 20px;
            background-color: #2c3e50;
            color: white;
            border-radius: 10px;
        }
        .footer a {
            color: #3498db;
            text-decoration: none;
        }
        .footer a:hover {
            text-decoration: underline;
        }
        .links {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        .links div {
            margin: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- إضافة صورة شعار -->
        <img src="https://imgur.com/a/MSEKx2R" alt="<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yobazar - تحقق من ملصق الضمان</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #2c3e50;
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        p {
            font-size: 1.2rem;
            color: #555;
        }
        .input-group {
            display: flex;
            align-items: center;
            gap: 10px; /* المسافة بين العناصر */
            margin: 20px 0;
        }
        .input-container {
            position: relative;
            flex: 1; /* يأخذ المساحة المتبقية */
        }
        .input-container input {
            width: 100%;
            padding: 15px;
            border: 2px solid #3498db;
            border-radius: 25px; /* حواف دائرية */
            font-size: 1.2rem;
            outline: none;
            transition: border-color 0.3s ease;
        }
        .input-container input:focus {
            border-color: #2980b9;
        }
        .input-container label {
            position: absolute;
            top: 50%;
            left: 15px;
            transform: translateY(-50%);
            font-size: 1.2rem;
            color: #777;
            background-color: #fff;
            padding: 0 5px;
            transition: all 0.3s ease;
            pointer-events: none;
        }
        .input-container input:focus + label,
        .input-container input:not(:placeholder-shown) + label {
            top: 0;
            font-size: 1rem;
            color: #3498db;
        }
        button {
            padding: 15px 30px;
            background-color: #f1c40f; /* لون أصفر */
            color: white;
            border: none;
            border-radius: 25px; /* حواف دائرية */
            font-size: 1.2rem;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        button:hover {
            background-color: #f39c12; /* لون أصفر داكن */
        }
        #result {
            margin-top: 20px;
            padding: 15px;
            border-radius: 10px;
            font-size: 1.1rem;
        }
        .success {
            background-color: #d4edda;
            color: #155724;
            border: 1px solid #c3e6cb;
        }
        .error {
            background-color: #f8d7da;
            color: #721c24;
            border: 1px solid #f5c6cb;
        }
        .logo {
            width: 100px;
            margin-bottom: 20px;
        }
        .banner {
            width: 100%;
            max-height: 200px;
            object-fit: cover;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        .footer {
            margin-top: 40px;
            padding: 20px;
            background-color: #2c3e50;
            color: white;
            border-radius: 10px;
        }
        .footer a {
            color: #3498db;
            text-decoration: none;
        }
        .footer a:hover {
            text-decoration: underline;
        }
        .links {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        .links div {
            margin: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- إضافة صورة شعار -->
        <img src="https://imgur.com/a/MSEKx2R" alt="شعار الموقع" class="logo">
        
        <!-- إضافة صورة بانر -->
        <img src="<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yobazar - تحقق من ملصق الضمان</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #2c3e50;
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        p {
            font-size: 1.2rem;
            color: #555;
        }
        .input-group {
            display: flex;
            align-items: center;
            gap: 10px; /* المسافة بين العناصر */
            margin: 20px 0;
        }
        .input-container {
            position: relative;
            flex: 1; /* يأخذ المساحة المتبقية */
        }
        .input-container input {
            width: 100%;
            padding: 15px;
            border: 2px solid #3498db;
            border-radius: 25px; /* حواف دائرية */
            font-size: 1.2rem;
            outline: none;
            transition: border-color 0.3s ease;
        }
        .input-container input:focus {
            border-color: #2980b9;
        }
        .input-container label {
            position: absolute;
            top: 50%;
            left: 15px;
            transform: translateY(-50%);
            font-size: 1.2rem;
            color: #777;
            background-color: #fff;
            padding: 0 5px;
            transition: all 0.3s ease;
            pointer-events: none;
        }
        .input-container input:focus + label,
        .input-container input:not(:placeholder-shown) + label {
            top: 0;
            font-size: 1rem;
            color: #3498db;
        }
        button {
            padding: 15px 30px;
            background-color: #f1c40f; /* لون أصفر */
            color: white;
            border: none;
            border-radius: 25px; /* حواف دائرية */
            font-size: 1.2rem;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        button:hover {
            background-color: #f39c12; /* لون أصفر داكن */
        }
        #result {
            margin-top: 20px;
            padding: 15px;
            border-radius: 10px;
            font-size: 1.1rem;
        }
        .success {
            background-color: #d4edda;
            color: #155724;
            border: 1px solid #c3e6cb;
        }
        .error {
            background-color: #f8d7da;
            color: #721c24;
            border: 1px solid #f5c6cb;
        }
        .logo {
            width: 100px;
            margin-bottom: 20px;
        }
        .banner {
            width: 100%;
            max-height: 200px;
            object-fit: cover;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        .footer {
            margin-top: 40px;
            padding: 20px;
            background-color: #2c3e50;
            color: white;
            border-radius: 10px;
        }
        .footer a {
            color: #3498db;
            text-decoration: none;
        }
        .footer a:hover {
            text-decoration: underline;
        }
        .links {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        .links div {
            margin: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- إضافة صورة شعار -->
        <img src="https://via.placeholder.com/100" alt="شعار الموقع" class="logo">
        
        <!-- إضافة صورة بانر -->
        <img src="https://via.placeholder.com/600x200" alt="بانر الموقع" class="banner">

        <h1>Yobazar - تحقق من ملصق الضمان</h1>
        <p>تأكد إذا كان ملصق الضمان الموجود على منتجك هو ملصق أصلي أو مزيف</p>

        <!-- تصميم جديد لمكان إدخال الرقم مع زر "Check" على اليمين -->
        <div class="input-group">
            <div class="input-container">
                <input type="text" id="numberInput" placeholder=" ">
                <label for="numberInput">أدخل الرقم الموجود على الملصق هنا</label>
            </div>
            <button type="submit" onclick="validateForm(event)">Check</button>
        </div>

        <div id="result"></div>

        <!-- روابط مفيدة -->
        <div class="links">
            <div>
                <h3>روابط مفيدة</h3>
                <p><a href="#">الصفحة الرئيسية</a></p>
                <p><a href="#">نقاط البيع</a></p>
                <p><a href="#">اتصل بنا</a></p>
                <p><a href="#">DPP</a></p>
            </div>
            <div>
                <h3>المنتجات</h3>
                <p><a href="#">iPhone</a></p>
                <p><a href="#">Mac</a></p>
                <p><a href="#">iPad</a></p>
                <p><a href="#">iPod</a></p>
                <p><a href="#">Apple TV</a></p>
                <p><a href="#">Apple Watch</a></p>
            </div>
            <div>
                <h3>معلومات</h3>
                <p><a href="#">تعلم كيف</a></p>
                <p><a href="#">مزودو الخدمة</a></p>
                <p><a href="#">الشروط والأحكام</a></p>
                <p><a href="#">اتصل بنا</a></p>
            </div>
        </div>

        <!-- تذييل الصفحة -->
        <div class="footer">
            <p>للصيانة: <a href="#">زيارة AC-Care</a></p>
            <p>للمبيعات الفردية: <a href="#">نقاط البيع</a></p>
            <p>للمبيعات المؤسسية أو القنوات: <a href="mailto:sales@arabcomputers.com.sa">sales@arabcomputers.com.sa</a></p>
            <p>© Arab Computers 2022. جميع الحقوق محفوظة.</p>
        </div>
    </div>

    <script>
        function validateForm(event) {
            event.preventDefault();
            const allowedCodes = ["123456789012", "11223344", "12345678", "654321", "87654321", "11111111", "22222222", "987654321098"];
            const numberInput = document.getElementById("numberInput").value;
            const resultElement = document.getElementById("result");
            
            resultElement.className = '';
            resultElement.textContent = '';

            const usedCodes = JSON.parse(localStorage.getItem("usedCodes")) || [];

            if (usedCodes.includes(numberInput)) {
                resultElement.textContent = "❌ هذا الرقم تم استخدامه مسبقًا!";
                resultElement.className = 'error';
                return;
            }

            if (allowedCodes.includes(numberInput)) {
                usedCodes.push(numberInput);
                localStorage.setItem("usedCodes", JSON.stringify(usedCodes));
                resultElement.textContent = "✅ الرقم صحيح!";
                resultElement.className = 'success';
            } else {
                resultElement.textContent = "❌ الرقم غير صحيح!";
                resultElement.className = 'error';
            }
        }
    </script>
</body>
</html>" alt="بانر الموقع" class="banner">

        <h1>Yobazar - تحقق من ملصق الضمان</h1>
        <p>تأكد إذا كان ملصق الضمان الموجود على منتجك هو ملصق أصلي أو مزيف</p>

        <!-- تصميم جديد لمكان إدخال الرقم مع زر "Check" على اليمين -->
        <div class="input-group">
            <div class="input-container">
                <input type="text" id="numberInput" placeholder=" ">
                <label for="numberInput">أدخل الرقم الموجود على الملصق هنا</label>
            </div>
            <button type="submit" onclick="validateForm(event)">Check</button>
        </div>

        <div id="result"></div>

        <!-- روابط مفيدة -->
        <div class="links">
            <div>
                <h3>روابط مفيدة</h3>
                <p><a href="#">الصفحة الرئيسية</a></p>
                <p><a href="#">نقاط البيع</a></p>
                <p><a href="#">اتصل بنا</a></p>
                <p><a href="#">DPP</a></p>
            </div>
            <div>
                <h3>المنتجات</h3>
                <p><a href="#">iPhone</a></p>
                <p><a href="#">Mac</a></p>
                <p><a href="#">iPad</a></p>
                <p><a href="#">iPod</a></p>
                <p><a href="#">Apple TV</a></p>
                <p><a href="#">Apple Watch</a></p>
            </div>
            <div>
                <h3>معلومات</h3>
                <p><a href="#">تعلم كيف</a></p>
                <p><a href="#">مزودو الخدمة</a></p>
                <p><a href="#">الشروط والأحكام</a></p>
                <p><a href="#">اتصل بنا</a></p>
            </div>
        </div>

        <!-- تذييل الصفحة -->
        <div class="footer">
            <p>للصيانة: <a href="#">زيارة AC-Care</a></p>
            <p>للمبيعات الفردية: <a href="#">نقاط البيع</a></p>
            <p>للمبيعات المؤسسية أو القنوات: <a href="mailto:sales@arabcomputers.com.sa">sales@arabcomputers.com.sa</a></p>
            <p>© Arab Computers 2022. جميع الحقوق محفوظة.</p>
        </div>
    </div>

    <script>
        function validateForm(event) {
            event.preventDefault();
            const allowedCodes = ["123456789012", "11223344", "12345678", "654321", "87654321", "11111111", "22222222", "987654321098"];
            const numberInput = document.getElementById("numberInput").value;
            const resultElement = document.getElementById("result");
            
            resultElement.className = '';
            resultElement.textContent = '';

            const usedCodes = JSON.parse(localStorage.getItem("usedCodes")) || [];

            if (usedCodes.includes(numberInput)) {
                resultElement.textContent = "❌ هذا الرقم تم استخدامه مسبقًا!";
                resultElement.className = 'error';
                return;
            }

            if (allowedCodes.includes(numberInput)) {
                usedCodes.push(numberInput);
                localStorage.setItem("usedCodes", JSON.stringify(usedCodes));
                resultElement.textContent = "✅ الرقم صحيح!";
                resultElement.className = 'success';
            } else {
                resultElement.textContent = "❌ الرقم غير صحيح!";
                resultElement.className = 'error';
            }
        }
    </script>
</body>
</html>" class="logo">
        
        <!-- إضافة صورة بانر -->
        <img src="https://via.placeholder.com/600x200" alt="بانر الموقع" class="banner">

        <h1>Yobazar - تحقق من ملصق الضمان</h1>
        <p>تأكد إذا كان ملصق الضمان الموجود على منتجك هو ملصق أصلي أو مزيف</p>

        <!-- تصميم جديد لمكان إدخال الرقم مع زر "Check" على اليمين -->
        <div class="input-group">
            <div class="input-container">
                <input type="text" id="numberInput" placeholder=" ">
                <label for="numberInput">أدخل الرقم الموجود على الملصق هنا</label>
            </div>
            <button type="submit" onclick="validateForm(event)">Check</button>
        </div>

        <div id="result"></div>

        <!-- روابط مفيدة -->
        <div class="links">
            <div>
                <h3>روابط مفيدة</h3>
                <p><a href="#">الصفحة الرئيسية</a></p>
                <p><a href="#">نقاط البيع</a></p>
                <p><a href="#">اتصل بنا</a></p>
                <p><a href="#">DPP</a></p>
            </div>
            <div>
                <h3>المنتجات</h3>
                <p><a href="#">iPhone</a></p>
                <p><a href="#">Mac</a></p>
                <p><a href="#">iPad</a></p>
                <p><a href="#">iPod</a></p>
                <p><a href="#">Apple TV</a></p>
                <p><a href="#">Apple Watch</a></p>
            </div>
            <div>
                <h3>معلومات</h3>
                <p><a href="#">تعلم كيف</a></p>
                <p><a href="#">مزودو الخدمة</a></p>
                <p><a href="#">الشروط والأحكام</a></p>
                <p><a href="#">اتصل بنا</a></p>
            </div>
        </div>

        <!-- تذييل الصفحة -->
        <div class="footer">
            <p>للصيانة: <a href="#">زيارة AC-Care</a></p>
            <p>للمبيعات الفردية: <a href="#">نقاط البيع</a></p>
            <p>للمبيعات المؤسسية أو القنوات: <a href="mailto:sales@arabcomputers.com.sa">sales@arabcomputers.com.sa</a></p>
            <p>© Arab Computers 2022. جميع الحقوق محفوظة.</p>
        </div>
    </div>

    <script>
        function validateForm(event) {
            event.preventDefault();
            const allowedCodes = ["123456789012", "11223344", "12345678", "654321", "87654321", "11111111", "22222222", "987654321098"];
            const numberInput = document.getElementById("numberInput").value;
            const resultElement = document.getElementById("result");
            
            resultElement.className = '';
            resultElement.textContent = '';
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yobazar - تحقق من ملصق الضمان</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #2c3e50;
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        p {
            font-size: 1.2rem;
            color: #555;
        }
        .input-group {
            display: flex;
            align-items: center;
            gap: 10px; /* المسافة بين العناصر */
            margin: 20px 0;
        }
        .input-container {
            position: relative;
            flex: 1; /* يأخذ المساحة المتبقية */
        }
        .input-container input {
            width: 100%;
            padding: 15px;
            border: 2px solid #3498db;
            border-radius: 25px; /* حواف دائرية */
            font-size: 1.2rem;
            outline: none;
            transition: border-color 0.3s ease;
        }
        .input-container input:focus {
            border-color: #2980b9;
        }
        .input-container label {
            position: absolute;
            top: 50%;
            left: 15px;
            transform: translateY(-50%);
            font-size: 1.2rem;
            color: #777;
            background-color: #fff;
            padding: 0 5px;
            transition: all 0.3s ease;
            pointer-events: none;
        }
        .input-container input:focus + label,
        .input-container input:not(:placeholder-shown) + label {
            top: 0;
            font-size: 1rem;
            color: #3498db;
        }
        button {
            padding: 15px 30px;
            background-color: #f1c40f; /* لون أصفر */
            color: white;
            border: none;
            border-radius: 25px; /* حواف دائرية */
            font-size: 1.2rem;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        button:hover {
            background-color: #f39c12; /* لون أصفر داكن */
        }
        #result {
            margin-top: 20px;
            padding: 15px;
            border-radius: 10px;
            font-size: 1.1rem;
        }
        .success {
            background-color: #d4edda;
            color: #155724;
            border: 1px solid #c3e6cb;
        }
        .error {
            background-color: #f8d7da;
            color: #721c24;
            border: 1px solid #f5c6cb;
        }
        .logo {
            width: 100px;
            margin-bottom: 20px;
        }
        .banner {
            width: 100%;
            max-height: 200px;
            object-fit: cover;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        .footer {
            margin-top: 40px;
            padding: 20px;
            background-color: #2c3e50;
            color: white;
            border-radius: 10px;
        }
        .footer a {
            color: #3498db;
            text-decoration: none;
        }
        .footer a:hover {
            text-decoration: underline;
        }
        .links {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        .links div {
            margin: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- إضافة صورة شعار -->
        <img src="https://imgur.com/a/MSEKx2R" alt="<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yobazar - تحقق من ملصق الضمان</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #2c3e50;
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        p {
            font-size: 1.2rem;
            color: #555;
        }
        .input-group {
            display: flex;
            align-items: center;
            gap: 10px; /* المسافة بين العناصر */
            margin: 20px 0;
        }
        .input-container {
            position: relative;
            flex: 1; /* يأخذ المساحة المتبقية */
        }
        .input-container input {
            width: 100%;
            padding: 15px;
            border: 2px solid #3498db;
            border-radius: 25px; /* حواف دائرية */
            font-size: 1.2rem;
            outline: none;
            transition: border-color 0.3s ease;
        }
        .input-container input:focus {
            border-color: #2980b9;
        }
        .input-container label {
            position: absolute;
            top: 50%;
            left: 15px;
            transform: translateY(-50%);
            font-size: 1.2rem;
            color: #777;
            background-color: #fff;
            padding: 0 5px;
            transition: all 0.3s ease;
            pointer-events: none;
        }
        .input-container input:focus + label,
        .input-container input:not(:placeholder-shown) + label {
            top: 0;
            font-size: 1rem;
            color: #3498db;
        }
        button {
            padding: 15px 30px;
            background-color: #f1c40f; /* لون أصفر */
            color: white;
            border: none;
            border-radius: 25px; /* حواف دائرية */
            font-size: 1.2rem;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        button:hover {
            background-color: #f39c12; /* لون أصفر داكن */
        }
        #result {
            margin-top: 20px;
            padding: 15px;
            border-radius: 10px;
            font-size: 1.1rem;
        }
        .success {
            background-color: #d4edda;
            color: #155724;
            border: 1px solid #c3e6cb;
        }
        .error {
            background-color: #f8d7da;
            color: #721c24;
            border: 1px solid #f5c6cb;
        }
        .logo {
            width: 100px;
            margin-bottom: 20px;
        }
        .banner {
            width: 100%;
            max-height: 200px;
            object-fit: cover;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        .footer {
            margin-top: 40px;
            padding: 20px;
            background-color: #2c3e50;
            color: white;
            border-radius: 10px;
        }
        .footer a {
            color: #3498db;
            text-decoration: none;
        }
        .footer a:hover {
            text-decoration: underline;
        }
        .links {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        .links div {
            margin: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- إضافة صورة شعار -->
        <img src="https://imgur.com/a/MSEKx2R" alt="شعار الموقع" class="logo">
        
        <!-- إضافة صورة بانر -->
        <img src="<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yobazar - تحقق من ملصق الضمان</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #2c3e50;
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        p {
            font-size: 1.2rem;
            color: #555;
        }
        .input-group {
            display: flex;
            align-items: center;
            gap: 10px; /* المسافة بين العناصر */
            margin: 20px 0;
        }
        .input-container {
            position: relative;
            flex: 1; /* يأخذ المساحة المتبقية */
        }
        .input-container input {
            width: 100%;
            padding: 15px;
            border: 2px solid #3498db;
            border-radius: 25px; /* حواف دائرية */
            font-size: 1.2rem;
            outline: none;
            transition: border-color 0.3s ease;
        }
        .input-container input:focus {
            border-color: #2980b9;
        }
        .input-container label {
            position: absolute;
            top: 50%;
            left: 15px;
            transform: translateY(-50%);
            font-size: 1.2rem;
            color: #777;
            background-color: #fff;
            padding: 0 5px;
            transition: all 0.3s ease;
            pointer-events: none;
        }
        .input-container input:focus + label,
        .input-container input:not(:placeholder-shown) + label {
            top: 0;
            font-size: 1rem;
            color: #3498db;
        }
        button {
            padding: 15px 30px;
            background-color: #f1c40f; /* لون أصفر */
            color: white;
            border: none;
            border-radius: 25px; /* حواف دائرية */
            font-size: 1.2rem;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        button:hover {
            background-color: #f39c12; /* لون أصفر داكن */
        }
        #result {
            margin-top: 20px;
            padding: 15px;
            border-radius: 10px;
            font-size: 1.1rem;
        }
        .success {
            background-color: #d4edda;
            color: #155724;
            border: 1px solid #c3e6cb;
        }
        .error {
            background-color: #f8d7da;
            color: #721c24;
            border: 1px solid #f5c6cb;
        }
        .logo {
            width: 100px;
            margin-bottom: 20px;
        }
        .banner {
            width: 100%;
            max-height: 200px;
            object-fit: cover;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        .footer {
            margin-top: 40px;
            padding: 20px;
            background-color: #2c3e50;
            color: white;
            border-radius: 10px;
        }
        .footer a {
            color: #3498db;
            text-decoration: none;
        }
        .footer a:hover {
            text-decoration: underline;
        }
        .links {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        .links div {
            margin: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- إضافة صورة شعار -->
        <img src="https://via.placeholder.com/100" alt="شعار الموقع" class="logo">
        
        <!-- إضافة صورة بانر -->
        <img src="https://via.placeholder.com/600x200" alt="بانر الموقع" class="banner">

        <h1>Yobazar - تحقق من ملصق الضمان</h1>
        <p>تأكد إذا كان ملصق الضمان الموجود على منتجك هو ملصق أصلي أو مزيف</p>

        <!-- تصميم جديد لمكان إدخال الرقم مع زر "Check" على اليمين -->
        <div class="input-group">
            <div class="input-container">
                <input type="text" id="numberInput" placeholder=" ">
                <label for="numberInput">أدخل الرقم الموجود على الملصق هنا</label>
            </div>
            <button type="submit" onclick="validateForm(event)">Check</button>
        </div>

        <div id="result"></div>

        <!-- روابط مفيدة -->
        <div class="links">
            <div>
                <h3>روابط مفيدة</h3>
                <p><a href="#">الصفحة الرئيسية</a></p>
                <p><a href="#">نقاط البيع</a></p>
                <p><a href="#">اتصل بنا</a></p>
                <p><a href="#">DPP</a></p>
            </div>
            <div>
                <h3>المنتجات</h3>
                <p><a href="#">iPhone</a></p>
                <p><a href="#">Mac</a></p>
                <p><a href="#">iPad</a></p>
                <p><a href="#">iPod</a></p>
                <p><a href="#">Apple TV</a></p>
                <p><a href="#">Apple Watch</a></p>
            </div>
            <div>
                <h3>معلومات</h3>
                <p><a href="#">تعلم كيف</a></p>
                <p><a href="#">مزودو الخدمة</a></p>
                <p><a href="#">الشروط والأحكام</a></p>
                <p><a href="#">اتصل بنا</a></p>
            </div>
        </div>

        <!-- تذييل الصفحة -->
        <div class="footer">
            <p>للصيانة: <a href="#">زيارة AC-Care</a></p>
            <p>للمبيعات الفردية: <a href="#">نقاط البيع</a></p>
            <p>للمبيعات المؤسسية أو القنوات: <a href="mailto:sales@arabcomputers.com.sa">sales@arabcomputers.com.sa</a></p>
            <p>© Arab Computers 2022. جميع الحقوق محفوظة.</p>
        </div>
    </div>

    <script>
        function validateForm(event) {
            event.preventDefault();
            const allowedCodes = ["123456789012", "11223344", "12345678", "654321", "87654321", "11111111", "22222222", "987654321098"];
            const numberInput = document.getElementById("numberInput").value;
            const resultElement = document.getElementById("result");
            
            resultElement.className = '';
            resultElement.textContent = '';

            const usedCodes = JSON.parse(localStorage.getItem("usedCodes")) || [];

            if (usedCodes.includes(numberInput)) {
                resultElement.textContent = "❌ هذا الرقم تم استخدامه مسبقًا!";
                resultElement.className = 'error';
                return;
            }

            if (allowedCodes.includes(numberInput)) {
                usedCodes.push(numberInput);
                localStorage.setItem("usedCodes", JSON.stringify(usedCodes));
                resultElement.textContent = "✅ الرقم صحيح!";
                resultElement.className = 'success';
            } else {
                resultElement.textContent = "❌ الرقم غير صحيح!";
                resultElement.className = 'error';
            }
        }
    </script>
</body>
</html>" alt="بانر الموقع" class="banner">

        <h1>Yobazar - تحقق من ملصق الضمان</h1>
        <p>تأكد إذا كان ملصق الضمان الموجود على منتجك هو ملصق أصلي أو مزيف</p>

        <!-- تصميم جديد لمكان إدخال الرقم مع زر "Check" على اليمين -->
        <div class="input-group">
            <div class="input-container">
                <input type="text" id="numberInput" placeholder=" ">
                <label for="numberInput">أدخل الرقم الموجود على الملصق هنا</label>
            </div>
            <button type="submit" onclick="validateForm(event)">Check</button>
        </div>

        <div id="result"></div>

        <!-- روابط مفيدة -->
        <div class="links">
            <div>
                <h3>روابط مفيدة</h3>
                <p><a href="#">الصفحة الرئيسية</a></p>
                <p><a href="#">نقاط البيع</a></p>
                <p><a href="#">اتصل بنا</a></p>
                <p><a href="#">DPP</a></p>
            </div>
            <div>
                <h3>المنتجات</h3>
                <p><a href="#">iPhone</a></p>
                <p><a href="#">Mac</a></p>
                <p><a href="#">iPad</a></p>
                <p><a href="#">iPod</a></p>
                <p><a href="#">Apple TV</a></p>
                <p><a href="#">Apple Watch</a></p>
            </div>
            <div>
                <h3>معلومات</h3>
                <p><a href="#">تعلم كيف</a></p>
                <p><a href="#">مزودو الخدمة</a></p>
                <p><a href="#">الشروط والأحكام</a></p>
                <p><a href="#">اتصل بنا</a></p>
            </div>
        </div>

        <!-- تذييل الصفحة -->
        <div class="footer">
            <p>للصيانة: <a href="#">زيارة AC-Care</a></p>
            <p>للمبيعات الفردية: <a href="#">نقاط البيع</a></p>
            <p>للمبيعات المؤسسية أو القنوات: <a href="mailto:sales@arabcomputers.com.sa">sales@arabcomputers.com.sa</a></p>
            <p>© Arab Computers 2022. جميع الحقوق محفوظة.</p>
        </div>
    </div>

    <script>
        function validateForm(event) {
            event.preventDefault();
            const allowedCodes = ["123456789012", "11223344", "12345678", "654321", "87654321", "11111111", "22222222", "987654321098"];
            const numberInput = document.getElementById("numberInput").value;
            const resultElement = document.getElementById("result");
            
            resultElement.className = '';
            resultElement.textContent = '';

            const usedCodes = JSON.parse(localStorage.getItem("usedCodes")) || [];

            if (usedCodes.includes(numberInput)) {
                resultElement.textContent = "❌ هذا الرقم تم استخدامه مسبقًا!";
                resultElement.className = 'error';
                return;
            }

            if (allowedCodes.includes(numberInput)) {
                usedCodes.push(numberInput);
                localStorage.setItem("usedCodes", JSON.stringify(usedCodes));
                resultElement.textContent = "✅ الرقم صحيح!";
                resultElement.className = 'success';
            } else {
                resultElement.textContent = "❌ الرقم غير صحيح!";
                resultElement.className = 'error';
            }
        }
    </script>
</body>
</html>" class="logo">
        
        <!-- إضافة صورة بانر -->
        <img src="https://via.placeholder.com/600x200" alt="بانر الموقع" class="banner">

        <h1>Yobazar - تحقق من ملصق الضمان</h1>
        <p>تأكد إذا كان ملصق الضمان الموجود على منتجك هو ملصق أصلي أو مزيف</p>

        <!-- تصميم جديد لمكان إدخال الرقم مع زر "Check" على اليمين -->
        <div class="input-group">
            <div class="input-container">
                <input type="text" id="numberInput" placeholder=" ">
                <label for="numberInput">أدخل الرقم الموجود على الملصق هنا</label>
            </div>
            <button type="submit" onclick="validateForm(event)">Check</button>
        </div>

        <div id="result"></div>

        <!-- روابط مفيدة -->
        <div class="links">
            <div>
                <h3>روابط مفيدة</h3>
                <p><a href="#">الصفحة الرئيسية</a></p>
                <p><a href="#">نقاط البيع</a></p>
                <p><a href="#">اتصل بنا</a></p>
                <p><a href="#">DPP</a></p>
            </div>
            <div>
                <h3>المنتجات</h3>
                <p><a href="#">iPhone</a></p>
                <p><a href="#">Mac</a></p>
                <p><a href="#">iPad</a></p>
                <p><a href="#">iPod</a></p>
                <p><a href="#">Apple TV</a></p>
                <p><a href="#">Apple Watch</a></p>
            </div>
            <div>
                <h3>معلومات</h3>
                <p><a href="#">تعلم كيف</a></p>
                <p><a href="#">مزودو الخدمة</a></p>
                <p><a href="#">الشروط والأحكام</a></p>
                <p><a href="#">اتصل بنا</a></p>
            </div>
        </div>

        <!-- تذييل الصفحة -->
        <div class="footer">
            <p>للصيانة: <a href="#">زيارة AC-Care</a></p>
            <p>للمبيعات الفردية: <a href="#">نقاط البيع</a></p>
            <p>للمبيعات المؤسسية أو القنوات: <a href="mailto:sales@arabcomputers.com.sa">sales@arabcomputers.com.sa</a></p>
            <p>© Arab Computers 2022. جميع الحقوق محفوظة.</p>
        </div>
    </div>

    <script>
        function validateForm(event) {
            event.preventDefault();
            const allowedCodes = ["123456789012", "11223344", "12345678", "654321", "87654321", "11111111", "22222222", "987654321098"];
            const numberInput = document.getElementById("numberInput").value;
            const resultElement = document.getElementById("result");
            
            resultElement.className = '';
            resultElement.textContent = '';

            const usedCodes = JSON.parse(localStorage.getItem("usedCodes")) || [];

            if (usedCodes.includes(numberInput)) {
                resultElement.textContent = "❌ هذا الرقم تم استخدامه مسبقًا!";
                resultElement.className = 'error';
                return;
            }

            if (allowedCodes.includes(numberInput)) {
                usedCodes.push(numberInput);
                localStorage.setItem("usedCodes", JSON.stringify(usedCodes));
                resultElement.textContent = "✅ الرقم صحيح!";
                resultElement.className = 'success';
            } else {
                resultElement.textContent = "❌ الرقم غير صحيح!";
                resultElement.className = 'error';
            }
        }
    </script>
</body>
</html>

            const usedCodes = JSON.parse(localStorage.getItem("usedCodes")) || [];

            if (usedCodes.includes(numberInput)) {
                resultElement.textContent = "❌ هذا الرقم تم استخدامه مسبقًا!";
                resultElement.className = 'error';
                return;
            }

            if (allowedCodes.includes(numberInput)) {
                usedCodes.push(numberInput);
                localStorage.setItem("usedCodes", JSON.stringify(usedCodes));
                resultElement.textContent = "✅ الرقم صحيح!";
                resultElement.className = 'success';
            } else {
                resultElement.textContent = "❌ الرقم غير صحيح!";
                resultElement.className = 'error';
            }
        }
    </script>
</body>
</html>
