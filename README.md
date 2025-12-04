<doctipy html!>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> الأمن السيبراني</title>
    <style>
        body {
            font-family: "Arial", sans-serif;
            background-color: #f0f4f8;
            color: #2c3e50;
            line-height: 1.6;
            margin: 0;
            padding: 0 20px;
        }
        header {
            text-align: center;
            padding: 40px 0;
            background: linear-gradient(90deg, #4cd137, #00a8ff);
            color: white;
        }
        header img {
            width: 220px;
            border-radius: 20px;
            margin-bottom: 15px;
            transition: transform 0.3s ease;
        }
        header img:hover {
            transform: scale(1.1);
        }
        h1 {
            margin: 10px 0;
            font-size: 2.2em;
            text-shadow: 1px 1px 2px #00000050;
        }
        h2 {
            color: #0097e6;
            margin-top: 25px;
            transition: color 0.3s ease;
        }
        h2:hover {
            color: #e84118;
            cursor: pointer;
        }
        p {
            margin: 8px 0 20px 0;
        }
        .container {
            max-width: 900px;
            margin: auto;
            padding: 25px;
            background-color: white;
            border-radius: 15px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.15);
            transition: transform 0.3s ease;
        }
        .container:hover {
            transform: translateY(-5px);
        }
    </style>
</head>
<body>

<header>
    <img src="data:image/jpeg;base64,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" alt="Cyber Security">
    <h1>الأمن السيبراني</h1>
</header>

<div class="container">
    <h2>1. مقدمة عن الأمن السيبراني</h2>
    <p>الأمن السيبراني هو حماية الأنظمة والشبكات والبرامج من الهجمات الرقمية التي تستهدف الوصول غير المصرح به أو التدمير أو التغيير.</p>

    <h2>2. تعريف التهديدات السيبرانية</h2>
    <p>التهديدات السيبرانية هي أي نشاط يهدف إلى سرقة المعلومات أو إلحاق الضرر بالأجهزة الرقمية.</p>

    <h2>3. أنواع البرمجيات الخبيثة (Malware)</h2>
    <p>البرمجيات الخبيثة تشمل الفيروسات، الديدان، وبرامج التجسس، وتستخدم لإحداث أضرار أو سرقة بيانات المستخدمين.</p>

    <h2>4. الفيروسات والديدان</h2>
    <p>الفيروسات تنتشر عند تشغيل ملفات مصابة، بينما الديدان يمكنها الانتشار تلقائياً عبر الشبكات.</p>

    <h2>5. برامج التجسس (Spyware)</h2>
    <p>برامج التجسس تقوم بمراقبة نشاط المستخدم وسرقة المعلومات الشخصية دون علمه.</p>

    <h2>6. الهندسة الاجتماعية</h2>
    <p>الهندسة الاجتماعية هي أساليب خداعية يستخدمها المهاجمون لإقناع المستخدم بالكشف عن معلومات حساسة.</p>

    <h2>7. التصيد الاحتيالي (Phishing)</h2>
    <p>التصيد الاحتيالي هو إرسال رسائل مزيفة تبدو من مصادر موثوقة بهدف سرقة كلمات المرور أو البيانات المالية.</p>

    <h2>8. كلمات المرور القوية</h2>
    <p>استخدام كلمات مرور طويلة ومعقدة ومختلفة لكل حساب يقلل من خطر الاختراق.</p>

    <h2>9. التشفير (Encryption)</h2>
    <p>التشفير يحول البيانات إلى صيغة غير قابلة للقراءة إلا للأشخاص المخولين، مما يحمي المعلومات أثناء النقل والتخزين.</p>

    <h2>10. الشبكات الآمنة</h2>
    <p>استخدام شبكات آمنة ومحمية بكلمات مرور قوية يقلل من مخاطر الاختراق.</p>

    <h2>11. جدران الحماية (Firewalls)</h2>
    <p>جدار الحماية يمنع الوصول غير المصرح به إلى الشبكات والأجهزة ويعمل كخط دفاع أول.</p>

    <h2>12. تحديثات البرامج والأمن</h2>
    <p>تحديث البرامج بانتظام يسد الثغرات الأمنية ويقلل من فرص استغلالها من قبل المخترقين.</p>

    <h2>13. النسخ الاحتياطي للبيانات</h2>
    <p>النسخ الاحتياطي يحمي البيانات من الفقدان بسبب الهجمات أو الأعطال التقنية.</p>

    <h2>14. حماية الأجهزة المحمولة</h2>
    <p>تثبيت برامج حماية على الهواتف والأجهزة اللوحية يقلل من خطر البرمجيات الخبيثة.</p>

    <h2>15. قوانين الأمن السيبراني</h2>
    <p>توجد قوانين وأنظمة تهدف لمعاقبة الجرائم الرقمية وحماية حقوق الأفراد والمؤسسات.</p>

    <h2>16. نصائح المستخدم النهائي</h2>
    <p>كن حذراً عند فتح الروابط والملفات المرسلة من مصادر غير موثوقة، وحافظ على تحديث برامجك وكلمات مرورك.</p>
<p style="text-align:center; font-weight:bold; margin-top:30px;">
  
        إعداد الطالبات:<br>
نباته العوده<br>
 ريمه العوده<br>
وجدان السالم<br>
 لولوه العبيدالله<br>
الدانه المنحول<br>
نوره العايد
        إعداد الطالبات:<br>
نباته العوده<br>
 ريمه العوده<br>
وجدان السالم<br>
 لولوه العبيدالله<br>
الدانه المنحول<br>
نوره العايد
</div>
</body>
</html>
