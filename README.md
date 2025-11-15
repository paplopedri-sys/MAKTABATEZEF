# MAKTABATEZEF
تعريف مكتبة الاخوة الزف

[مكتبة الاخوة الزف.html](https://github.com/user-attachments/files/23564735/default.html)
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مكتبة الأخوة الزف</title>
    <!-- رابط Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- رابط Google Fonts لخط جميل (Cairo) -->
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Cairo', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: #333;
            margin: 0;
            padding: 0;
        }
        .hero {
            background: linear-gradient(135deg, #2c3e50 0%, #3498db 100%);
            color: white;
            padding: 80px 0;
            text-align: center;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            border-bottom: 5px solid #e74c3c;
        }
        .hero h1 {
            font-size: 3rem;
            font-weight: 700;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        .hero p {
            font-size: 1.2rem;
            margin-top: 20px;
        }
        .container {
            max-width: 1200px;
        }
        .card {
            border: none;
            border-radius: 15px;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            background: linear-gradient(135deg, #ffffff 0%, #f8f9fa 100%);
            margin-bottom: 30px;
        }
        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 40px rgba(0, 0, 0, 0.2);
        }
        .card-title {
            color: #2c3e50;
            font-weight: 700;
            font-size: 1.5rem;
        }
        .card-text {
            color: #555;
            line-height: 1.6;
        }
        h2 {
            color: #2c3e50;
            font-weight: 700;
            margin-bottom: 30px;
            text-align: center;
            position: relative;
        }
        h2::after {
            content: '';
            display: block;
            width: 100px;
            height: 4px;
            background: linear-gradient(90deg, #3498db, #e74c3c);
            margin: 10px auto;
            border-radius: 2px;
        }
        footer {
            background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
            color: white;
            text-align: center;
            padding: 20px 0;
            box-shadow: 0 -5px 15px rgba(0, 0, 0, 0.2);
        }
        footer p {
            margin: 0;
            font-size: 1rem;
        }
        /* تأثيرات إضافية للاستجابة */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2rem;
            }
            .card {
                margin-bottom: 20px;
            }
        }
    </style>
</head>
<body>
    <!-- قسم الرأس (Hero Section) -->
    <div class="hero">
        <div class="container">
            <h1>مرحبًا بكم في مكتبة الأخوة الزف</h1>
            <h1> صاحب المكتبة هو محمد الزف </h1>
            <p class="lead"> مكتبة الاخوة الزف تقدم لكم أفضل الإصدارات والخدمات الادارية و القانونية و اللوازم المدرسية .</p>
        </div>
    </div>

    <!-- قسم عن المكتبة -->
    <div class="container my-5">
        <div class="row">
            <div class="col-md-12">
                <div class="card">
                    <div class="card-body">
                        <h2>عن المكتبة</h2>
                        <p class="card-text">مكتبة الأخوة الزف هي مكتبة تقليدية تقدم مجموعة  من الكتب المدرسية في مختلف المواد  و مجموعة من الخدمات الادارية  .</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- قسم الخدمات -->
    <div class="container my-5">
        <h2>الخدمات المتاحة</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">تحرير العقود</h5>
                        <p class="card-text">نقدم خدمات تحرير وصياغة العقود القانونية بأسعار مناسبة.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">الطباعة السريعة</h5>
                        <p class="card-text">طباعة وثائق، تقارير، ومواد تعليمية بسرعة وجودة عالية.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">الصور السريعة</h5>
                        <p class="card-text">طباعة صور فوتوغرافية سريعة ومخصصة للاحتياجات الشخصية أو التجارية.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">الأدوات المدرسية</h5>
                        <p class="card-text">توفير مجموعة واسعة من الأدوات المدرسية مثل الأقلام، الدفاتر، واللوازم الأخرى.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">كتابة شكايات</h5>
                        <p class="card-text">مساعدة في صياغة شكايات رسمية أو قانونية بطريقة احترافية.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">تنازلات</h5>
                        <p class="card-text">إعداد وثائق التنازل عن الحقوق أو الالتزامات بطريقة قانونية.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">الكتب المدرسية</h5>
                        <p class="card-text">بيع مختلف الكتب المدرسية باتمنة مناسبة </p>
                    </div>
                </div>
            </div>            
        </div>
    </div>

    <!-- قسم معلومات الاتصال -->
    <div class="container my-5">
        <div class="row">
            <div class="col-md-12">
                <div class="card">
                    <div class="card-body">
                        <h2>معلومات الاتصال</h2>
                        <p><strong>العنوان:</strong> [المركز القصيبية سيدي سليمان]</p>
                        <p><strong>الهاتف:</strong> [0666743141]</p>
                        <p><strong>البريد الإلكتروني:</strong> maktabateezef03@gmail.com</p>
                        <p><strong>ساعات العمل:</strong> من 9 صباحًا إلى 7 مساءً يوميًا.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- الفوتر -->
    <footer>
        <p>&copy;  مكتبة الأخوة الزف. جميع الحقوق محفوظة.</p>
    </footer>

    <!-- رابط Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
