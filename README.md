Tushunarli! Topshiriq shartlarini toʻliq bajarish va kodni toza ajratish uchun bizga 2 ta fayl (index.html va style.css) kerak boʻladi.

Quyidagi kodlarni nusxalab, oʻz loyihangizga qoʻshishingiz mumkin:

1. index.html fayli
HTML
<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>3 xil usulda CSS bog'lash</title>

    <link rel="stylesheet" href="style.css">

    <style>
        body {
            background-color: #f0f4f8; /* background property */
            margin: 0; /* margin property */
            font-family: sans-serif;
        }

        .konteyner {
            max-width: 800px;
            margin: 40px auto;
            padding: 20px; /* padding property */
            background: white;
            border-radius: 8px;
        }

        .tavsif-matn {
            font-size: 16px; /* font-size property */
            color: #555555; /* color property */
        }
    </style>
</head>
<body>

    <div class="konteyner">
        <h1 style="color: #ff5722; font-size: 36px;">Bu loyihaning asosiy sarlavhasi (Hero text)</h1>
        
        <p class="tavsif-matn">
            Ushbu matn ko'rinishi head qismidagi style tegi orqali boshqarilmoqda.
        </p>

        <div class="karta">
            <h3>Tashqi CSS yordamida bezatilgan blok</h3>
            <p>Bu blokning ko'rinishi butunlay style.css fayliga bog'liq.</p>
        </div>
    </div>

</body>
</html>
2. style.css fayli
Ushbu kodni style.css deb nomlangan alohida faylga saqlang (index.html bilan bir xil papkada boʻlishi kerak):

CSS
/* Tashqi CSS fayli */
.karta {
    background-color: #e3f2fd;
    padding: 15px;
    margin-top: 20px;
    border-left: 5px solid #2196f3;
    border-radius: 4px;
}

.karta h3 {
    color: #0d47a1;
    margin: 0 0 10px 0;
}
3. README.md fayli uchun matn
GitHub'dagi README.md faylingiz ichiga quyidagi tushuntirishni joylashtiring. Bu har bir usulning qachon foydali ekanligini koʻrsatib beradi:

Markdown
# CSS-ni ulashning 3 xil usuli va ularning qo'llanilishi

Ushbu loyihada CSS stillarini ulashning barcha 3 ta usuli amalda ko'rsatilgan:

### 1. Inline Style ( some element ichida yozish )
* **Qachon yaxshi:** Faqat bitta elementga tezda, vaqtincha yoki unikal stil bermoqchi bo'lganda (masalan, sahifadagi bitta asosiy Hero matn rangini o'zgartirishda).
* **Kamchiligi:** Kod ko'payib ketsa, HTML chalkashib ketadi va boshqa joyda qayta ishlatib bo'lmaydi.

### 2. Internal Style (<head> ichida <style> tegi bilan)
* **Qachon yaxshi:** Faqat bitta sahifadan iborat kichik saytlar (Landing page) yaratilayotganda. Shu sahifaning o'ziga xos stillarini bir joyda saqlash uchun qulay.
* **Kamchiligi:** Saytda sahifalar ko'paysa, har bir sahifaga kodni qayta ko'chirib chiqish kerak bo'ladi.

### 3. External Style (Alohida .css fayl orqali)
* **Qachon yaxshi:** Eng to'g'ri va professional usul. Ko'p sahifali katta loyihalarda bitta CSS fayli orqali butun sayt dizaynini boshqarish imkonini beradi. HTML va CSS kodlari bir-biridan mustaqil ajralib turadi.
🚀 GitHub'ga yuklash tartibi:
Repozitoriyangizda index.html va style.css fayllarini yarating va yuqoridagi kodlarni soling.

README.md faylini ochib, tushuntirish matnini qo'shing.

Hammasini Commit qiling.
