<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>إشعار توصيل جديد</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #FF9800; /* اللون البرتقالي */
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .header {
            background-color: #4CAF50; /* اللون الأخضر */
            color: white;
            padding: 20px;
            border-radius: 10px 10px 0 0;
        }
        .content {
            padding: 20px;
            font-size: 18px;
            color: #333;
        }
        .button {
            display: inline-block;
            padding: 15px 30px;
            font-size: 18px;
            color: white;
            text-decoration: none;
            background-color: #4CAF50;
            border-radius: 50px;
            margin: 10px 0;
            transition: background-color 0.3s;
        }
        .button:hover {
            background-color: #45a049;
        }
        .button.reject {
            background-color: #f44336; /* اللون الأحمر */
        }
        .button.reject:hover {
            background-color: #d32f2f;
        }
        .footer {
            font-size: 14px;
            color: #777;
            margin-top: 20px;
        }
        .important {
            background-color: #ffeb3b;
            padding: 10px;
            font-weight: bold;
            color: #000;
            border-radius: 5px;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="header">
            <h2>إشعار طلب توصيل جديد</h2>
        </div>

        <div class="content">
            <p><strong>عزيزي السائق،</strong></p>
            <p>يرجى اتخاذ إجراء عاجل على هذا الطلب. يمكنك قبول أو رفض الطلب باستخدام الأزرار أدناه.</p>
            
            <p class="important">يرجى اتخاذ القرار بأسرع وقت.</p>

            <!-- زر قبول الطلب -->
            <a href="mailto:magicdelivery@yahoo.com?subject=تأكيد%20الطلب&body=تم%20تأكيد%20الطلب" class="button">قبول الطلب</a>

            <!-- زر رفض الطلب -->
            <a href="mailto:magicdelivery@yahoo.com?subject=رفض%20الطلب&body=تم%20رفض%20الطلب" class="button reject">رفض الطلب</a>
        </div>

        <div class="footer">
            <p>إذا كنت بحاجة إلى مساعدة، يرجى الرد على هذا البريد الإلكتروني.</p>
        </div>
    </div>

</body>
</html>
