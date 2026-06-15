<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <title>Mening birinchi HTML sahifam</title>
</head>
<body>

    <h1>Bu asosiy sarlavha (h1)</h1>
    <h2>Bu ikkinchi darajali sarlavha (h2)</h2>

    <p>Bu oddiy matn bloki. Bu yerda darsda o'rgatilgan asosiy teglarni mashq qilish mumkin.</p>

    <h3>Kunning muhim rejalari:</h3>
    <ul>
        <li>HTML teglarini o'rganish</li>
        <li>GitHub-ga fayllarni to'g'ri yuklashni mashq qilish</li>
        <li>Veb-sahifa yaratish</li>
    </ul>

    <a href="https://github.com" target="_blank">GitHub saytiga o'tish</a>

</body>
</html>
<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <title>HTML va CSS darsi</title>
    
    <style>
        body {
            background-color: #f4f6f9; /* Orqa fon rangi */
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 40px;
            text-align: center;
        }

        .konteyner {
            background-color: white;
            max-width: 600px;
            margin: 0 auto;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1); /* Soya berish */
        }

        h1 {
            color: #2c3e50;
            font-size: 28px;
            margin-bottom: 10px;
        }

        p {
            color: #5a6c7d;
            font-size: 16px;
            line-height: 1.6;
        }

        .tugma {
            background-color: #2ecc71; /* Yashil rang */
            color: white;
            padding: 12px 24px;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-size: 16px;
            font-weight: bold;
            transition: 0.3s; /* Rang silliq o'zgarishi uchun */
        }

        /* Sichqoncha tugma ustiga kelganda */
        .tugma:hover {
            background-color: #27ae60; 
            transform: scale(1.05); /* Biroz kattalashadi */
        }
    </style>
</head>
<body>

    <div class="konteyner">
        <h1>2-dars: HTML Teglar va CSS stillar</h1>
        <p>
            Ushbu sahifa toza HTML teglari yordamida yozildi va CSS kodlari bilan 
            chiroyli ko'rinishga keltirildi. Endi GitHub'da faqat README emas, 
            haqiqiy kod fayli mavjud!
        </p>
        <button class="tugma">Kodni tekshirish</button>
    </div>

</body>
</html>
